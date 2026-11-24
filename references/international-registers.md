# International registers: what is published, how to read it, and what you may reuse (as of 24 November 2026)

Load this file for questions about a specific country's company or beneficial ownership register as a **data source**: what it publishes, in what form (API, bulk file, page), how its identifiers join to the LEI, and what its licence or law allows you to do with it.

**Where this comes from.** OpenCheck (opencheck.world, github.com/StephenAbbott/opencheck) reads 74 open sources across company registers, BO registers, sanctions and PEP data, procurement and extractives disclosures. Everything below was measured while building those adapters between June and November 2026. Each item carries the date it was checked. Register sites change their APIs, block new address ranges and revise their terms, so treat a date older than a few months as a prompt to re-check.

**For access status** (who may see BO data, legitimate-interest routes), use `bo-access-status.md`. **For the law**, use `regulatory-context.md`.

---

## 1. Lessons that apply to every register

1. **Licence first, then build.** An open-data portal's headline licence often does not cover personal data. Norway's NLOD 2.0 §3 excludes personal data without a legitimate basis; Botswana's CIPA refused republication outright (30 Oct 2026); the BVI FSC's portal terms ban scraping and republication without consent. Ask the register in writing and keep the answer.
2. **Some laws forbid republishing BO data even where it is visible.** France: INPI entries flagged `beneficiaireEffectif` must never be republished (Loi Sapin II, décret 2017-1094). Strip them from the raw payload, not only from the mapped output.
3. **"Public" can still mean "not in bulk".** The Netherlands' KvK keeps anything possibly personal out of its High-Value Dataset under Wet hergebruik van overheidsinformatie art. 2(1)(h) (KvK reply, 17 Nov 2026): the bulk file has no KvK number and no names, and the open API allows one request per minute per IP plus a shared pool. Gibraltar's public BO register (free since Feb 2026, at ubo.fsc.gi since 1 Oct 2026) has no bulk access.
4. **Datacentre blocks are common and are not a licence question.** Several registers answer cloud and CI addresses with a Cloudflare challenge, a geofence or HTTP 407, while a home connection works:
   - Lithuania JAR (Registrų centras) and its data.gov.lt copy (geo-fenced to Lithuania): build the index from a home connection.
   - Ukraine data.gov.ua downloads (the CKAN API answers; the files do not).
   - Bulgaria data.egov.bg: Bulgarian addresses only (a VPN to Bulgaria works).
   - Slovenia podatki.gov.si: HTTP 407 to every non-browser client (12 Nov 2026).
   - Peru OECE's OCDS API: 403 from datacentres.
   Never spoof a browser to get past a block; download by hand and say so.
5. **Never assume an absent owner means no owner.** A register may not collect owners for that legal form, may withhold an entry for a person at risk, or may simply not have answered. Say which.
6. **Personal data you did not ask for arrives anyway.** Nigeria CAC's v1 API returns email, phone, full date of birth and ID number to anonymous callers; Estonia's files carry people's addresses; Ukrainian ЄДР BO strings carry citizenship. Copy fields by **allowlist**, never a denylist.
7. **Identifiers rarely match as filed.** GLEIF stores national numbers in the issuer's spelling: grouped SIRENs (`542 051 180`), zero-padded or not, check digits after a hyphen (Canada `1709920-7`), punctuated CNPJs, Greek letters in Cyprus (`ΗΕ 449149`). Normalise on both sides and keep the register's own spelling for display.
8. **A wrong number in GLEIF is real.** GLEIF records sometimes name another company's register number (DC: American Foreign Policy Council's `L21249` is CONNIE-19 STREET LLC). Gate a number join on the name.

---

## 2. Country notes

### Europe

| Country | Register and form | Identifier / GLEIF RA | Reuse notes (date checked) |
|---|---|---|---|
| **United Kingdom** | Companies House API and bulk files: companies, officers, PSCs, filing history; PSC exemptions on their own endpoint | `GB-COH`; RA000585 E&W, RA000586 NI, **RA000587 Scotland** (RA000591 is the Pensions Regulator, not a register) | OGL v3.0. PSC filings can be traced to the PSC01/CS01 that declared them |
| **Estonia** | e-Business Register: daily open-data files (companies, officers, shareholders, BOs, off-card persons, rulings, pledges); print page; credentialed SOAP and REST (one simultaneous query, 50,000 answers a day per contract) | `EE-ARIREGISTER`; RA000181 | BO data public (restriction postponed; see `bo-access-status.md`). Files carry a person hash (`isikukood_hash`) that links one person across lists; never publish personal codes. Cloudflare rate-limits back-to-back downloads (error 1015) |
| **Latvia** | Register of Enterprises (UR) open data on data.gov.lv (CKAN) and dati.ur.gov.lv | `LV-RE`; RA000423 | Since 19 Nov 2026 natural-person AS shareholders are non-public (Constitutional Court, 9 Nov 2026); the stockholders resource answers 403 |
| **Lithuania** | JAR open data, weekly | RA000430 | Cloudflare challenge on all datacentres; sole proprietors' names withheld by form |
| **Denmark** | CVR via Datafordeler GraphQL (key; aliases forbidden; one root field per query; 100-row pages) | `DK-CVR`; RA000170 | BO, directors and legal owners only via Erhvervsstyrelsen System-til-System; BO restricted since 1 Sept 2025, never republishable |
| **Norway** | Brreg Enhetsregisteret (open), annual accounts API (open since 1 Oct 2026); Skatteetaten's Aksjonærregisteret extract (on request) | `NO-BRC`; RA000472 | Shareholder extract: NLOD §3 excludes personal data; reuse question pending with Skatteetaten (Nov 2026). Never publish birth year, postcode or town |
| **Netherlands** | KvK open data | RA000463 | See lesson 3. No paid-API fallback: it needs a Dutch subscriber and is not openly licensed |
| **France** | INPI RNE (companies, officers); Sirene (INSEE); BODACC and JOAFE notices via DILA's Opendatasoft | `FR-INSEE` (SIREN); RA000189, RA000192, RA001129 | Sapin II prohibition on BO (lesson 2). BODACC and JOAFE: never copy a natural person's name or address |
| **Belgium** | KBO Open Data full file, monthly, free login | `BE-BCE_KBO`, dotted (`0202.239.951`); RA000025 | Active entities only |
| **Bulgaria** | Commercial Register daily XML deltas since 2021, CC0 | `BG-EIK`; RA000065 (+RA000730, RA000731) | Bulgarian IPs only. Entries carry a salted ID hash and sometimes a raw birth date: drop them |
| **Cyprus** | DRCOR's three CSVs on data.gov.cy, monthly | `CY-DRCOR`; RA000161 | Officers only; no shareholders or BOs published |
| **Czechia** | ARES API | RA000163 | Former owners carry `datumVymazu` |
| **Slovakia** | RPO; RPVS (public-sector partners' BOs, procurement-linked) | `SK-ICO`; RA000526 | RPVS is the model for procurement-linked BO |
| **Slovenia** | AJPES Business Register CSV, CC BY 4.0 | RA000529 | 407 to non-browser clients (lesson 4); no status, dates or people |
| **Austria** | Firmenbuch; BMF list of shell companies (Scheinunternehmen) | RA000017 | BMF Impressum forbids putting its content on other sites; permission requested 23 Nov 2026 |
| **Ukraine** | ЄДР (Unified State Register) with beneficial owners, data.gov.ua | `UA-EDR`; RA000567, RA001026, RA001027 | Law 4576-IX withholds addresses and locations; never fill them from older Open Ownership data. Prozorro procurement data is CC BY 4.0 |
| **Moldova** | ASP State Register; MTender procurement | `MD-IDNO`; RA000451 | MTender licence unclear; the tender.gov.md ban list refuses datacentres (read it through OpenSanctions `md_interdictie`) |
| **Serbia** | APR | `RS-APR`; RA000517 | |
| **Greece** | G.E.MI. | RA000685 | BO register moving to AADE (Law 5354/2026) |
| **Romania** | ONRC open data | `RO-ONRC` | |
| **Switzerland** | Zefix and the UID register | RA000548, RA000549 | Transparency register (1 Oct 2026) is authorities only |

### Americas

| Country | Register and form | Identifier / GLEIF RA | Notes |
|---|---|---|---|
| **Canada** | Corporations Canada daily CSVs (whole federal register) plus API; ISC register via API key | `CA-CC`; RA000072 | Number includes its check digit. ESTMA payments (Statistics Canada Open Licence) |
| **United States** | No federal company register. State registers: New York DOS, Connecticut, Pennsylvania (data.pa.gov), DC DLCP, Florida Sunbiz (SFTP bulk) | `US-NY`, `US-CT`, `US-PA`, `US-DC`, `US-FL` | Officers and agents only; no BO. SEC EDGAR Schedules 13D/13G (renamed `SCHEDULE 13D/G` after the Dec 2024 XML mandate) and Form 13F (investment managers with discretion, never owners) |
| **Colombia** | RUES on datos.gov.co, CC BY-SA 4.0 | `CO-RUE` (NIT with check digit) | Legal persons only; never select personal ID columns |
| **Peru** | OECE RNP: suppliers' declared make-up (procurement), ODC-By | `PE-RUC`; RA000689 etc. | A self-declaration to a procurement regulator, not a BO register |
| **Chile** | RES (simplified-regime companies) on datos.gob.cl, CC BY; ChileCompra supplier BO declarations (Ley 21.634) | | ChileCompra BO declarations are not open data; Open Ownership works with ChileCompra |
| **Argentina** | RNS and IGJ | `AR-CUIT`; RA000009, RA000010, RA000800 | RNS has no status; IGJ people counted, never published |
| **Brazil** | Receita Federal CNPJ open data (QSA partners) | `BR-CNPJ`; RA000681 | |
| **Ecuador** | Supercias shareholders | | Portal answered 403 from the cloud (Nov 2026) |

### Asia-Pacific and Africa

| Country | Register and form | Identifier / GLEIF RA | Notes |
|---|---|---|---|
| **Taiwan** | MOEA GCIS open data: companies and directors' and supervisors' holdings | `TW-CR`; RA000551 | Holdings are directors'/supervisors' only; never call them "the shareholders" |
| **Japan** | NTA corporate numbers, monthly signed zip, PDL-1.0 | `JP-JCN`; RA000412, RA001075 | Identity and standing only, nothing on owners |
| **South Korea** | Open DART (listed-company disclosures; key; 20,000 calls a day) | `KR-BRN`/`KR-CRN` | Terms art. 19② forbid sharing the key |
| **Singapore** | ACRA | RA000523 | |
| **Hong Kong** | Companies Registry | `HK-BRN`; RA000388, RA000389 | |
| **New Zealand** | Companies Office API; Role Search | `NZ-NZBN`; RA000466 | Role search is name-keyed: grade every match |
| **Australia** | ABR, ASIC | RA000013, RA000014 | No BO register |
| **India** | MCA21 | RA000394 | |
| **Nigeria** | CAC BO register, v1 API (Sept 2026 redesign) | RA000469 | Not BODS despite the homepage's claim; the API returns PII to anonymous callers (lesson 6) |
| **Thailand** | DBD | | Reuse enquiry sent (Nov 2026) |

---

## 3. Cross-border and thematic sources

- **GLEIF**: Level 1 (who is who) and Level 2 (accounting consolidation, not ownership; "consolidated by", never "owned by"). Golden Copy daily files and deltas; the API rate limit is 60 requests a minute. GLEIF no longer fills `entity.expiration`: date a dissolution from Legal Entity Events. GLEIF file storage refused GitHub runners on 18 Nov 2026.
- **OECD-UNSD MEIP Global Register**: published in BODS v0.4 (Sept 2026). Group membership under a statistical method, not ownership; every edge runs to the group head.
- **OpenSanctions**: CC BY-NC (commercial use needs a licence). The `/match` API is billed per query.
- **OpenAleph** (DARC): FtM entities with percolation and document mentions.
- **ICIJ Offshore Leaks**: gate a match on the leak's date and jurisdiction, never on ICIJ's own match flag.
- **EITI**: three databases with three ID systems; company IDs are not portable between them.
- **GEM Global Energy Ownership Tracker**: CC BY 4.0, monthly; OpenSanctions republishes it, so do not count it twice.
- **Open Ownership bulk BODS**: UK PSC and GLEIF in BODS v0.4 (OGL v3.0 and CC0).

---

## 4. Reading a register into BODS: checks that catch most errors

- Map the register's own entity type to `entityType.details`, never to `entityType.subtype` (a closed codelist).
- Use ISO 3166 codes for jurisdictions and nationalities; give the name alone when you cannot resolve a code, never a stand-in.
- A person's non-document identifiers (Wikidata Q-ids, register person keys) belong in annotations, not `personStatement.identifiers`.
- Officers are `seniorManagingOfficial` or `boardMember`; an officer is never an owner. A secretary has no v0.4 role code.
- Ended relationships are kept and closed (`recordStatus: closed`), never dropped. A closed record with no published date says "ended", with no invented date.
- Date a statement by the register's own record date or cut, never by the day you read it.
- Leave a value uncoded when no ISO 5009 or ELF code clearly fits. Precision over coverage.
