# Beneficial ownership access status, by jurisdiction

Who may see each jurisdiction's beneficial ownership (BO) register, since when, and what is changing. **Snapshot of 23 November 2026** (21:30 UTC), taken from Stephen's Notion database *Beneficial ownership access status* (https://app.notion.com/p/ce531f47972f4b579ec6bc70d99c7830) through the copy OpenCheck syncs into its repository (`backend/opencheck/data/jurisdictions.json`, rendered as https://github.com/StephenAbbott/opencheck/blob/main/docs/knowability.md). 75 jurisdictions; 68 carry a *Last verified* date from Stephen and the others are marked "unverified draft".

**How to use this file**

- Treat every row as dated. Access regimes moved monthly in 2026; before relying on a row, check its sources and the live register, and say how old the row is.
- For the newest state, query the Notion database itself (or OpenCheck's MCP tool `opencheck_knowability(jurisdictions)`, which serves the synced table) rather than this snapshot.
- "Verified" means Stephen checked the row against the cited sources on that date. Text marked "Draft from the CEFILAT/FTC report" or "drafted by Claude" is a summary of the source named, verified on the date shown, not a reading of the statute.
- Describe and date; do not judge. A closed register is a legal fact about access, not evidence about any company.

**Access categories**

| Category | Meaning |
|---|---|
| Public | Anyone can search without showing a purpose (UK PSC, Latvia, Estonia, Nigeria, Ukraine, Canada federal, Gibraltar, Botswana, St Helena). |
| Legitimate-interest access | A route is open for people who show a legitimate interest (journalists, CSOs, academics, counterparties, etc.), usually on application. Since the CJEU *WM and Sovim* judgment (C-37/20, C-601/20, 22 Nov 2022) this is the EU model under 6AMLD Arts 11–13 and 15. |
| Restricted; route in law but not yet open | Public or broad access has ended and the law provides a legitimate-interest route, but no working application process exists yet (Italy, Netherlands, Poland, Portugal, Romania, Spain, Sweden at the snapshot date, Anguilla). |
| Authorities and obliged entities only | Only competent authorities and AML-obliged entities can see it; no route for anyone else. Most of Latin America, the Crown Dependencies (Jersey and Guernsey have agreed LIA policies), Switzerland, Singapore. |
| No central BO register | No central register of beneficial owners (the US, where FinCEN no longer collects BO from domestic companies; Japan, Korea, New Zealand, Australia, Mexico, Chile and most of Central America). Company registers may still publish officers or shareholders. |

**Column guide**: *Since* = when the current access regime started; *Next change* = a dated, announced change to access; *6AMLD LIA* = whether the jurisdiction's law already gives the 6AMLD legitimate-interest route (Yes/No; "Not applicable" outside the EU/EEA); *BORIS* = whether its register is connected to the EU interconnection system.

## Summary table

| Code | Jurisdiction | BO register | Access | Since | Next change | 6AMLD LIA | BORIS | Verified |
|---|---|---|---|---|---|---|---|---|
| AI | Anguilla | Commercial Registration Electronic System (CRES) | Restricted; legitimate-interest route in law but not yet open | 2026-05-11 | — | Not applicable | Not applicable | 2026-10-20 |
| AR | Argentina | Registro de Beneficiarios Finales (ARCA) | Authorities and obliged entities only | — | — | Not applicable | Not applicable | 2026-11-11 |
| AU | Australia | — | No central BO register | — | — | Not applicable | Not applicable | unverified |
| AT | Austria | Austria Register of Beneficial Owners | Legitimate-interest access | 2026-11-05 | — | Yes | Yes | 2026-11-06 |
| BE | Belgium | Belgium UBO Register | Legitimate-interest access | — | — | No | Yes | 2026-10-21 |
| BZ | Belize | Beneficial ownership information held by the Financial Services Commission (FSC) | Authorities and obliged entities only | — | — | Not applicable | Not applicable | 2026-11-23 |
| BM | Bermuda | Bermuda's register of legal persons | Legitimate-interest access | 2026-09-14 | — | Not applicable | Not applicable | 2026-10-06 |
| BO | Bolivia | — | No central BO register | — | — | Not applicable | Not applicable | 2026-11-23 |
| BW | Botswana | Online Business Registration System | Public | 2025-03-20 | — | Not applicable | Not applicable | 2026-09-30 |
| BR | Brazil | National Register of Legal Persons (CNPJ) | Not yet recorded | — | — | Not applicable | Not applicable | 2026-09-18 |
| VG | British Virgin Islands | Beneficial Ownership Secure Search System (BOSSS) | Legitimate-interest access | 2026-04-01 | — | Not applicable | Not applicable | 2026-11-10 |
| BG | Bulgaria | Bulgaria Commercial Register | Legitimate-interest access | 2025-06-04 | — | No | No | 2026-09-18 |
| CA | Canada | Individuals with significant control register | Public | 2024-01-01 | — | Not applicable | Not applicable | 2026-09-18 |
| KY | Cayman Islands | Cayman Islands General Registry | Legitimate-interest access | 2025-02-01 | — | Not applicable | Not applicable | unverified |
| CL | Chile | — | No central BO register | — | — | Not applicable | Not applicable | 2026-11-23 |
| CO | Colombia | Registro Único de Beneficiarios Finales (RUB), DIAN | Authorities and obliged entities only | — | — | Not applicable | Not applicable | 2026-11-10 |
| CR | Costa Rica | Registro de Transparencia y Beneficiarios Finales (Banco Central de Costa Rica) | Authorities and obliged entities only | — | — | Not applicable | Not applicable | 2026-11-23 |
| HR | Croatia | Croatia Register of Beneficial Owners | Authorities and obliged entities only | — | — | No | Yes | 2026-09-18 |
| CY | Cyprus | Cyprus Register of Beneficial Owners | Authorities and obliged entities only | — | — | No | Yes | 2026-10-21 |
| CZ | Czechia | Information System of Real Owners | Authorities and obliged entities only | — | 2027-01-01 | No | Yes | 2026-09-18 |
| DK | Denmark | Centrale Virksomhedsregister (CVR) | Legitimate-interest access | 2025-09-01 | — | Yes | Yes | 2026-09-18 |
| EC | Ecuador | Registro de Beneficiarios Finales (REBEFICS), Servicio de Rentas Internas (SRI) | Authorities and obliged entities only | — | — | Not applicable | Not applicable | 2026-11-23 |
| SV | El Salvador | — | No central BO register | — | — | Not applicable | Not applicable | 2026-11-23 |
| EE | Estonia | e-Business Register | Public | — | — | No | No | 2026-11-19 |
| FI | Finland | Finland Register of Companies | Authorities and obliged entities only | — | — | No | Yes | 2026-09-18 |
| FR | France | Registre National des Entreprises (RNE) | Legitimate-interest access | 2025-05-03 | — | Yes | Yes | 2026-09-18 |
| DE | Germany | Transparenzregister | Legitimate-interest access | — | 2027-01-01 | No | Yes | 2026-11-18 |
| GI | Gibraltar | UBO Public Register | Public | 2026-02-23 | — | Not applicable | Not applicable | 2026-10-08 |
| GR | Greece | Single Digital Portal | Authorities and obliged entities only | — | — | No | Yes | 2026-11-18 |
| GT | Guatemala | — | No central BO register | — | — | Not applicable | Not applicable | 2026-11-23 |
| GG | Guernsey | Guernsey Beneficial Ownership Registry | Authorities and obliged entities only | — | — | Not applicable | Not applicable | 2026-11-18 |
| HN | Honduras | — | No central BO register | — | — | Not applicable | Not applicable | 2026-11-23 |
| HK | Hong Kong | — | Not yet recorded | — | — | Not applicable | Not applicable | unverified |
| HU | Hungary | UBO Register | Authorities and obliged entities only | — | — | No | Yes | 2026-09-18 |
| IS | Iceland | Register of Enterprises | Not yet recorded | — | — | No | Yes | 2026-09-18 |
| IN | India | India BO register | Not yet recorded | — | — | Not applicable | Not applicable | unverified |
| IE | Ireland | Central Register of Beneficial Ownership of Companies and Industrial and Provident Societies (RBO) | Legitimate-interest access | 2026-11-10 | — | Yes | No | 2026-11-15 |
| IM | Isle of Man | Isle of Man Database of Beneficial Ownership (IOMDBO) | Authorities and obliged entities only | 2024-12-31 | — | Not applicable | Not applicable | 2026-09-18 |
| IL | Israel | — | Authorities and obliged entities only | — | — | Not applicable | Not applicable | 2026-11-11 |
| IT | Italy | Registro dei Beneficiari Effettivi delle Società | Restricted; legitimate-interest route in law but not yet open | 2026-06-10 | — | Yes | No | 2026-11-20 |
| JP | Japan | Beneficial Ownership List system (実質的支配者リスト制度), Legal Affairs Bureaus — voluntary | No central BO register | — | — | Not applicable | Not applicable | 2026-11-23 |
| JE | Jersey | JFSC Registry | Authorities and obliged entities only | — | — | Not applicable | Not applicable | 2026-11-22 |
| LV | Latvia | Register of Enterprises | Public | 2026-07-01 | — | Yes | Yes | 2026-11-19 |
| LI | Liechtenstein | — | Authorities and obliged entities only | — | — | No | No | 2026-09-18 |
| LT | Lithuania | Information System of Legal Entities Participants (JADIS) | Legitimate-interest access | — | — | No | Yes | 2026-09-18 |
| LU | Luxembourg | Registre de Bénéficiaires Effectifs (RBE) | Legitimate-interest access | 2025-01-27 | — | No | Yes | 2026-09-18 |
| MT | Malta | Business Automation Registry Online System (BAROS) | Legitimate-interest access | 2026-07-10 | 2027-01-10 | Yes | Yes | 2026-10-06 |
| MX | Mexico | — | No central BO register | — | — | Not applicable | Not applicable | 2026-11-23 |
| MD | Moldova | — | Not yet recorded | — | — | Not applicable | Not applicable | unverified |
| NL | Netherlands | UBO register | Restricted; legitimate-interest route in law but not yet open | 2025-07-16 | — | No | Yes | 2026-11-20 |
| NZ | New Zealand | — | No central BO register | — | — | Not applicable | Not applicable | 2026-09-18 |
| NI | Nicaragua | Registro del Beneficiario Final de las Sociedades Mercantiles (Sistema Nacional de Registros) | Authorities and obliged entities only | — | — | Not applicable | Not applicable | 2026-11-23 |
| NG | Nigeria | CAC Beneficial Ownership Register | Public | 2023-05-25 | — | Not applicable | Not applicable | 2026-09-18 |
| NO | Norway | Registeret over reelle rettighetshavere | Legitimate-interest access | 2024-10-01 | — | Not applicable | Yes | 2026-09-18 |
| PA | Panama | Sistema Privado y Único de Registro de Beneficiarios Finales (Superintendencia de Sujetos No Financieros) | Authorities and obliged entities only | — | — | Not applicable | Not applicable | 2026-11-23 |
| PY | Paraguay | Registro Administrativo de Personas y Estructuras Jurídicas y Beneficiarios Finales (Ministerio de Economía y Finanzas) | Authorities and obliged entities only | — | — | Not applicable | Not applicable | 2026-11-23 |
| PE | Peru | Registro de Beneficiarios Finales (SUNAT) | Authorities and obliged entities only | — | — | Not applicable | Not applicable | 2026-11-12 |
| PL | Poland | Centralny Rejestr Beneficjentów Rzeczywistych (CRBR) | Restricted; legitimate-interest route in law but not yet open | 2026-07-01 | — | No | No | 2026-11-23 |
| PT | Portugal | Central Register of Effective Beneficiaries (RCBE) | Restricted; legitimate-interest route in law but not yet open | — | — | No | Yes | 2026-09-18 |
| KR | Republic of Korea | — | No central BO register | — | — | Not applicable | Not applicable | 2026-11-10 |
| RO | Romania | Registrul Beneficiarilor Reali (RBR) | Restricted; legitimate-interest route in law but not yet open | — | — | No | Yes | 2026-09-18 |
| RS | Serbia | Central Records of Beneficial Owners | Not yet recorded | — | — | Not applicable | Not applicable | 2026-09-18 |
| SG | Singapore | Register of Registrable Controllers (RORC) | Authorities and obliged entities only | — | — | Not applicable | Not applicable | 2026-09-18 |
| SK | Slovakia | Register of legal entities, entrepreneurs and public authorities (RPO) | Legitimate-interest access | 2026-07-10 | — | Yes | No | 2026-10-01 |
| SI | Slovenia | Register of Beneficial Owners (RDL) | Legitimate-interest access | 2025-08-09 | — | Yes | Yes | 2026-09-18 |
| ES | Spain | Registro de Titularidades Reales (RETIR) | Restricted; legitimate-interest route in law but not yet open | — | — | No | Yes | 2026-09-18 |
| SH | St Helena | Saint Helena Beneficial Ownership Register | Public | 2025-07-01 | — | Not applicable | Not applicable | unverified |
| SE | Sweden | Register of Real Principals | Restricted; legitimate-interest route in law but not yet open | 2026-07-01 | — | Yes | Yes | 2026-10-14 |
| CH | Switzerland | Swiss Transparency Register | Authorities and obliged entities only | 2026-10-01 | — | Not applicable | Not applicable | 2026-10-08 |
| TW | Taiwan | — | Authorities and obliged entities only | — | — | Not applicable | Not applicable | 2026-10-30 |
| TC | Turks and Caicos Islands | Turks and Caicos Islands beneficial ownership register | Legitimate-interest access | 2025-07-01 | — | Not applicable | Not applicable | unverified |
| UA | Ukraine | Unified State Registry | Public | 2026-01-19 | — | Not applicable | Not applicable | 2026-09-18 |
| GB | United Kingdom | Register of People with Significant Control and Register of Overseas Entities | Public | — | — | Not applicable | Not applicable | 2026-09-18 |
| US | United States | Beneficial Ownership Information System (BOIS) | No central BO register | — | — | Not applicable | Not applicable | 2026-09-18 |
| UY | Uruguay | Registro de Entidades y Beneficiarios Finales (Banco Central del Uruguay) | Authorities and obliged entities only | — | — | Not applicable | Not applicable | 2026-11-23 |

## Country notes

### Anguilla (AI) — verified 2026-10-20

**Access**: Restricted; legitimate-interest route in law but not yet open.
- **BO register**: Commercial Registration Electronic System (CRES) — http://www.commercialregistry.ai/
- **Company register**: Commercial Registration Electronic System (CRES) — https://cres.gov.ai/bereg/searchbusinesspublic; public: Yes
- **Next FATF/FSRB assessment**: CFATF; onsite 2031-06-01; plenary 2032-05-01
- **Notes**: LIA amendment bill published on 2026-05-11 https://houseofassembly.ai/documents/a-bill-for-commercial-registry-and-beneficial-ownership-registration-system-amendment-act-2026

### Argentina (AR) — verified 2026-11-11

**Access**: Authorities and obliged entities only.
- **How to apply**: https://datos.jus.gob.ar/dataset/registro-nacional-de-sociedades
- **Company register**: Registro Nacional de Sociedades (Ministerio de Justicia) and Inspección General de Justicia (City of Buenos Aires) — https://datos.jus.gob.ar/dataset/registro-nacional-de-sociedades; public: Partly
- **Notes**: Beneficial owners are reported to ARCA (Registro de Beneficiarios Finales, RG AFIP 4697/2020) and declared to the IGJ (RG IGJ 7/2015); neither is published. The RNS and the IGJ entity file are open data on datos.jus.gob.ar (name, CUIT, form, founding date, addresses; the IGJ also names people in an entity's filings without dates or roles), not shareholders or beneficial owners.
- **Sources**: https://datos.jus.gob.ar/dataset/registro-nacional-de-sociedades · https://datos.jus.gob.ar/dataset/entidades-constituidas-en-la-inspeccion-general-de-justicia-igj · https://www.argentina.gob.ar/normativa/nacional/resolución-4697-2020-337045

### Australia (AU) — unverified draft

**Access**: No central BO register.
- **Next FATF/FSRB assessment**: FATF / APG; onsite 2026-11-01; plenary 2027-06-01
- **Notes**: No central BO register; ABR/ASIC publish officers only.

### Austria (AT) — verified 2026-11-06

**Access**: Legitimate-interest access.
- **BO register**: Austria Register of Beneficial Owners — https://wieregms.bmf.gv.at/at.gv.bmf.wiereg-p/wiereg?execution=e1s1
- **How to apply**: https://www.parlament.gv.at/gegenstand/XXVIII/ME/93
- **Access detail**: BGBl. I Nr. 94/2026 (published 29 Oct 2026). USP: the legitimate-interest procedure 'erfüllt die Vorgaben der 6. Geldwäscherichtlinie'; binding decision periods (12 working days), decisions on legitimate-interest access valid EU-wide, automated issue of certificates and decisions. Art. 2 brings the new WiEReG § 10 'Einsicht bei Vorliegen eines berechtigten Interesses' and § 10b into force on 5 Nov 2026 (§ 19 Abs. 12; also applies to applications filed before that date, § 18 Abs. 3); the Wirtschaftliche Eigentümer Registergesetz 2027 follows mainly from 10 Jul 2027. A BMF application route for anyone with a legitimate interest has existed since 1 Sep 2023 (EUR 4 per extract).
- **Pending changes**: BGBl. I Nr. 94/2026 (published 29 Oct 2026): Art. 2 amends the existing WiEReG so that the new § 10 'Einsicht bei Vorliegen eines berechtigten Interesses' and § 10b (procedure) are in force from 5 Nov 2026 (§ 19 Abs. 12; pending applications also covered, § 18 Abs. 3). The Wirtschaftliche Eigentümer Registergesetz 2027 itself is in force mainly from 10 Jul 2027 (USP); which of its provisions take that date not confirmed as of 6 Nov 2026 (authentic RIS text not opened).
- **Notes**: Not on the FATF assessments calendar as of 18 Sept 2026
- **Sources**: https://www.parlament.gv.at/gegenstand/XXVIII/ME/93 · https://www.parlament.gv.at/gegenstand/XXVIII/I/622 · https://www.usp.gv.at/aktuelles/gesetzliche-neuerungen/Bundesgesetzblatt/wiereg-2027.html · https://www.parlament.gv.at/dokument/XXVIII/BNR/216/fnameorig_1783794.html · https://www.bmf.gv.at/services/wiereg/berechtigtes-Interesse.html

### Belgium (BE) — verified 2026-10-21

**Access**: Legitimate-interest access.
- **BO register**: Belgium UBO Register — http://eservices.minfin.fgov.be/ubo/
- **Access detail**: Since the Law and AR of 8 Feb 2023 (Moniteur belge 17 Feb 2023), anyone who can demonstrate a legitimate interest may apply electronically to the Administration de la Trésorerie for access (pre-2024 conditions: a legitimate interest exists only where a person pursues a purpose or carries out activities in a sustained and effective manner connected to preventing money laundering and terrorist financing; Art. 10 §3 of the UBO Royal Decree presumes it for three national categories, not the 6AMLD Art. 12(2) list; no 3-year certificate). Under Art. 16 of the UBO Royal Decree the Treasury may restrict access to a beneficial owner's data on request, where the owner faces a disproportionate risk (e.g. fraud, kidnapping, extortion) or is a minor or legally incapacitated. AR of 12 Jun 2026 (in force 3 Jul 2026) gives obliged entities access to supporting documents. No transposition of 6AMLD Arts 11–13 and 15 found as of 21 Oct 2026. Like Cyprus, Belgium has transposed only Art. 74 of Directive (EU) 2024/1640 (Council of Ministers, 26 Sep 2025: draft AR aligning trust-like arrangements with companies, https://news.belgium.be/fr/precision-des-modalites-de-fonctionnement-du-registre-ubo), not Arts 11, 12, 13 or 15.
- **Notes**: Not on the FATF assessments calendar as of 18 Sept 2026 (5th-round MER adopted 2025).

### Belize (BZ) — verified 2026-11-23

**Access**: Authorities and obliged entities only.
- **How to apply**: https://www.cefilat.org/informes/the-invisible-owners
- **Next FATF/FSRB assessment**: CFATF
- **Notes**: Draft from the CEFILAT/FTC report 'The Invisible Owners' (Aug 2026). Threshold 25%. Companies Act 2022 (amended 2023), Trusts Act (amended 2023), FSC Guidelines on Beneficial Ownership Information (18 Mar 2025). Access by request to authorities only. Bearer shares banned; nominee directors must be declared. Annual filing; the FSC publishes non-compliance. Fines up to BZD 100,000; companies that did not re-register were struck off. 301 ISSUED LEIs (RA000026, RA000693).
- **Sources**: https://www.cefilat.org/informes/the-invisible-owners

### Bermuda (BM) — verified 2026-10-06

**Access**: Legitimate-interest access.
- **BO register**: Bermuda's register of legal persons — https://www.registrarofcompanies.gov.bm/bmroc-master/viewInstance/view.html?id=61bf8f1804cf99999b0cc7bec78e5b6403ce62ccfdcdfa8b&_timestamp=1326746033468619
- **How to apply**: https://www.gov.bm/news/beneficial-ownership-regulations-and-guidance-notes-issued-to-support-implementation
- **Access detail**: Beneficial Ownership Act 2025 in force Nov 2025 (Foster Moore register); LIA introduced from 14th September 2026
- **Next FATF/FSRB assessment**: CFATF; onsite 2027-03-01; plenary 2027-11-01
- **Notes**: LIA from 14th September 2026 https://www.gov.bm/news/beneficial-ownership-regulations-and-guidance-notes-issued-to-support-implementation + https://www.parliament.bm/admin/uploads/bill/d0812ec4a4645bf9a275d3f2808a3dcf.pdf + https://www.gov.bm/theofficialgazette/notices/gn0813/2026
- **Sources**: https://www.gov.bm/news/beneficial-ownership-regulations-and-guidance-notes-issued-to-support-implementation

### Bolivia (BO) — verified 2026-11-23

**Access**: No central BO register.
- **How to apply**: https://www.cefilat.org/informes/the-invisible-owners
- **Next FATF/FSRB assessment**: GAFILAT
- **Notes**: Draft from the CEFILAT/FTC report (Aug 2026): no BO register and no BO obligation. 19 ISSUED LEIs.
- **Sources**: https://www.cefilat.org/informes/the-invisible-owners

### Botswana (BW) — verified 2026-09-30

**Access**: Public.
- **BO register**: Online Business Registration System — https://www.cipa.co.bw/master/ui/start/CIPARegisterSearch
- **How to apply**: https://www.cipa.co.bw/beneficial-ownership
- **Threshold (as worded)**: at least 10 per cent (10%)
- **Company register**: CIPA Register of Companies — https://www.cipa.co.bw/master/ui/start/CIPARegisterSearch; public: Yes
- **Next FATF/FSRB assessment**: ESAAMLG
- **Notes**: Verified by Stephen 30 Sept 2026. Not an OpenCheck source: CIPA refused permission to republish register data (30 Oct 2026). Threshold, in full (CIPA Beneficial Ownership Guidelines 2026): “The legal person must take reasonable steps to identify the natural person(s) who owns or controls it, either through owning or controlling at least 10 per cent (10%) of its shares or voting rights or other ownership interest.” Register pages publish BO names, nationalities, addresses, interest type and share, with start and end dates; no dates of birth seen. Legal basis: Companies Act Cap. 42:01 as amended in 2018 (ss. 21, 345) and 2025 (Act No. 3 of 2025: s. 329(1) substantial-shareholder threshold five to 10 per cent; nominee and nominator defined; s. 329A nominee disclosure); FIA 2022 s. 2; FI Regulations 2022 reg. 7.
- **Sources**: https://www.cipa.co.bw/beneficial-ownership · https://www.cipa.co.bw/wp-content/uploads/2026/02/Beneficial-Ownership-Guidelines-2026.pdf · https://www.cipa.co.bw/wp-content/uploads/2026/02/Companies-Amendment-Act-2025.pdf · https://lawsociety.org.bw/wp-content/uploads/2024/07/2024-lsb-final-guidelines-on-identification-of-beneficial-ownership-information-for-attorneys.pdf

### Brazil (BR) — verified 2026-09-18

**Access**: Not yet recorded.
- **BO register**: National Register of Legal Persons (CNPJ) — https://www.gov.br/pt-br/servicos/consultar-cadastro-nacional-de-pessoas-juridicas
- **Next FATF/FSRB assessment**: FATF / GAFILAT; onsite 2030-02-01; plenary 2030-10-01

### British Virgin Islands (VG) — verified 2026-11-10

**Access**: Legitimate-interest access.
- **BO register**: Beneficial Ownership Secure Search System (BOSSS) — https://publicsearch.bvifsc.vg/publicsearch/user/login
- **How to apply**: https://gov.vg/news/legitimate-interest-access-now-fully-operational-virgin-islands
- **Access detail**: Legitimate interest access fully operational 1 Apr 2026.
- **Company register**: Registry of Corporate Affairs (BVI Financial Services Commission) — https://publicsearch.bvifsc.vg/publicsearch/entity-search; public: Partly
- **Next FATF/FSRB assessment**: CFATF; onsite 2029-03-01; plenary 2029-09-01
- **Notes**: The company register is free to search by name or number at the FSC public search, but the free result shows only the company number, name and previous names. For a fee, a search report gives type, incorporation date, status, registered agent and office, share or capital information, and the name, transaction and certificate histories (FSC page 'Searches (BVI Registered Entities)'). The portal's Terms of Use forbid automated access and republishing without the Commission's written consent. Beneficial ownership is reached by an online 'Request to Inspect Beneficial Ownership Register' on the same portal.
- **Sources**: https://gov.vg/news/legitimate-interest-access-now-fully-operational-virgin-islands · https://www.bvifsc.vg/searches-bvi-registered-entities · https://www.bvifsc.vg/public-search

### Bulgaria (BG) — verified 2026-09-18

**Access**: Legitimate-interest access.
- **BO register**: Bulgaria Commercial Register — https://portal.registryagency.bg/CR/en/Reports/VerificationPersonOrg
- **Pending changes**: Draft law amending the ЗМИП (submitted by ДАНС), stated to be in line with Directive (EU) 2024/1640: three access levels including persons who can prove a legitimate interest (Art. 63д). Public consultation No. 12770 on strategy.bg ran 02.10.2026–02.11.2026 and is closed; no report on comments and no submission to the Narodno sabranie as of 4 Nov 2026. Entry into force reportedly 10.07.2027 (per a consultation comment; not verified in the draft text).
- **Next FATF/FSRB assessment**: MONEYVAL; onsite 2030-04-01; plenary 2030-12-01
- **Notes**: On 4th June 2025, Bulgaria adopted a law (decree no 92) amending its national law on measures against the financing of terrorism which introduces LIA for all entries in the commercial register for “any person or organization that can demonstrate a legitimate interest” (see article 63b). However it doesn’t spell out the categories of organisations which are deemed to have legitimate interest.

### Canada (CA) — verified 2026-09-18

**Access**: Public.
- **BO register**: Individuals with significant control register — https://ised-isde.canada.ca/cc/lgcy/fdrlCrpSrch.html
- **Next FATF/FSRB assessment**: FATF / APG; onsite 2025-11-01; plenary 2026-06-01
- **Notes**: Corporations Canada federal register launched on 1st January 2024

### Cayman Islands (KY) — unverified draft

**Access**: Legitimate-interest access.
- **BO register**: Cayman Islands General Registry — https://www.ciregistry.ky/
- **How to apply**: https://www.ciregistry.ky/wp-content/uploads/dlm_uploads/BOT-Legitimate-Interest-Access-and-Access-Restriction-Guidance.pdf
- **Access detail**: LIA for accredited journalists, academics, certain CSOs since Feb 2025; fees.
- **Next FATF/FSRB assessment**: CFATF; onsite 2027-12-01; plenary 2028-11-01
- **Notes**: Status drafted from Stephen's trackers 18 Sept 2026 — verify.
- **Sources**: https://www.ciregistry.ky/wp-content/uploads/dlm_uploads/BOT-Legitimate-Interest-Access-and-Access-Restriction-Guidance.pdf

### Chile (CL) — verified 2026-11-23

**Access**: No central BO register.
- **How to apply**: https://www.cefilat.org/informes/the-invisible-owners
- **Pending changes**: Bill Boletín 16.475-05 would create a BO register.
- **Company register**: Registro de Empresas y Sociedades (RES, Ley 20.659) — https://datos.gob.cl/dataset/registro-de-empresas-y-sociedades; public: Partly
- **Next FATF/FSRB assessment**: GAFILAT
- **Notes**: Draft from the CEFILAT/FTC report (Aug 2026): no BO register. ChileCompra's supplier sworn declarations under Ley 21.634 name beneficial owners above 10% and administrators (83,700 declarations, 148,000 owners by May 2025); buyers see them on the Ficha Proveedor, the public view is simplified. RES open data (CC BY, monthly) covers simplified-regime companies only, entities only. 891 ISSUED LEIs (RA000787, RUT).
- **Sources**: https://www.cefilat.org/informes/the-invisible-owners

### Colombia (CO) — verified 2026-11-10

**Access**: Authorities and obliged entities only.
- **BO register**: Registro Único de Beneficiarios Finales (RUB), DIAN — https://www.dian.gov.co/impuestos/RUB/Paginas/default.aspx
- **How to apply**: https://www.dian.gov.co/impuestos/RUB/Paginas/default.aspx
- **Threshold (as worded)**: "cinco por ciento (5%) o más del capital o los derechos de voto"
- **Company register**: Registro Único Empresarial y Social (RUES), Confecámaras — https://www.rues.org.co/; public: Yes
- **Notes**: The RUB is read by DIAN and competent authorities. RUES publishes the company's legal representative by name and role, not shareholders or owners; OpenCheck reads it from the datos.gov.co open data and never carries ID numbers or natural-person (sole trader) rows.
- **Sources**: https://www.dian.gov.co/impuestos/RUB/Paginas/default.aspx · https://www.datos.gov.co/d/c82u-588k

### Costa Rica (CR) — verified 2026-11-23

**Access**: Authorities and obliged entities only.
- **How to apply**: https://www.cefilat.org/informes/the-invisible-owners
- **Next FATF/FSRB assessment**: GAFILAT
- **Notes**: Draft from the CEFILAT/FTC report (Aug 2026). Threshold 15%, and all shareholders are declared. Law 9416/2016 ch. II; Decree 41040-H replaced by 44390-H/2024; joint resolutions DGT-ICD. Held encrypted by the Central Bank; only the Ministry of Finance and the ICD may consult it. Annual declaration due 30 July, digitally signed by the legal representative. Legal persons and fideicomisos declare now, others phased in. Fines 3–100 base salaries. 125 ISSUED LEIs.
- **Sources**: https://www.cefilat.org/informes/the-invisible-owners

### Croatia (HR) — verified 2026-09-18

**Access**: Authorities and obliged entities only.
- **BO register**: Croatia Register of Beneficial Owners — https://rsv.fina.hr/RSV-OnLineUnos-web/login
- **Next FATF/FSRB assessment**: MONEYVAL; onsite 2030-04-01; plenary 2030-12-01

### Cyprus (CY) — verified 2026-10-21

**Access**: Authorities and obliged entities only.
- **BO register**: Cyprus Register of Beneficial Owners — https://ubo.meci.gov.cy/
- **Access detail**: Law 25(I)/2026 (Official Gazette No. 5079, 20.3.2026), harmonising with Art. 74 of Directive (EU) 2024/1640, amends s.61A(6) (companies) and s.61B (trusts) so that a person who proves a legitimate interest ('έννομο συμφέρον') may access beneficial ownership information. It transposes only Art. 74, not Arts 11, 12, 13 or 15, so it introduces the concept of legitimate interest but none of the specific 6AMLD access rules. No operating application route confirmed as of 21 Oct 2026 (DRCIP privacy policy of 26/06/2025 still lists only authorities and obliged entities).
- **Next FATF/FSRB assessment**: MONEYVAL; onsite 2028-10-01; plenary 2029-05-01

### Czechia (CZ) — verified 2026-09-18

**Access**: Authorities and obliged entities only.
- **BO register**: Information System of Real Owners — https://esm.justice.cz/ias/issm/rejstrik
- **How to apply**: https://odok.gov.cz/portal/veklep/material/ALBSDNCJXJV7/
- **Access detail**: Government amendments 22 Jun 2026; LIA expected 1 Jan 2027, officials say unlikely before H1 2027 (8 Sept 2026).
- **Next FATF/FSRB assessment**: MONEYVAL; onsite 2026-04-01; plenary 2026-12-01
- **Sources**: https://odok.gov.cz/portal/veklep/material/ALBSDNCJXJV7/

### Denmark (DK) — verified 2026-09-18

**Access**: Legitimate-interest access.
- **BO register**: Centrale Virksomhedsregister (CVR) — https://datacvr.virk.dk/
- **How to apply**: https://erhvervsstyrelsen.dk/vejledning-adgang-til-oplysninger-om-reelle-ejere
- **Access detail**: LIA route live via Erhvervsstyrelsen guidance.
- **Discrepancy route (BO register)**: https://www.virk.dk/myndigheder/stat/ERST/selvbetjening/Indberetning_om_uoverensstemmelse_af_ejerforhold/
- **Next FATF/FSRB assessment**: FATF; onsite 2027-06-01; plenary 2028-02-01
- **Sources**: https://erhvervsstyrelsen.dk/vejledning-adgang-til-oplysninger-om-reelle-ejere · https://www.retsinformation.dk/eli/lta/2025/987#P1

### Ecuador (EC) — verified 2026-11-23

**Access**: Authorities and obliged entities only.
- **How to apply**: https://www.cefilat.org/informes/the-invisible-owners
- **Company register**: Superintendencia de Compañías, Valores y Seguros (Supercias); public: —
- **Next FATF/FSRB assessment**: GAFILAT
- **Notes**: Draft from the CEFILAT/FTC report (Aug 2026). Threshold 10% under Res. NAC-DGERCGC22-00000046 (replacing an all-owners rule; may apply only to non-residents). Ley Orgánica para el Desarrollo Económico y Sostenibilidad Fiscal (2021); SRI resolutions NAC-DGERCGC24-00000033 (17 Sep 2024) and NAC-DGERCGC25-00000046 (31 Dec 2025); LRTI Art. 37. Article 10: the register 'will not be public'. Covers fideicomisos (incl. foreign), autonomous estates, economic units without legal personality. Non-compliance: 3-point corporate tax surcharge. Supercias corporate information shows shareholders (unconfirmed: portals answered 403 from the cloud). A separate SERCOP procurement BO register exists. 73 ISSUED LEIs (RA000178, RUC).
- **Sources**: https://www.cefilat.org/informes/the-invisible-owners

### El Salvador (SV) — verified 2026-11-23

**Access**: No central BO register.
- **How to apply**: https://www.cefilat.org/informes/the-invisible-owners
- **Next FATF/FSRB assessment**: GAFILAT
- **Notes**: Draft from the CEFILAT/FTC report (Aug 2026): no BO register and no BO obligation. 56 ISSUED LEIs.
- **Sources**: https://www.cefilat.org/informes/the-invisible-owners

### Estonia (EE) — verified 2026-11-19

**Access**: Public.
- **BO register**: e-Business Register — https://ariregister.rik.ee/eng
- **How to apply**: https://www.riigiteataja.ee/akt/114032025023
- **Threshold (as worded)**: more than 25 % (üle 25 %)
- **Access detail**: Planned 10 Jul 2026 LIA restriction postponed at the last minute; no new date. The LIA sheet says "Yes" — stale.
- **Pending changes**: Public-access restriction (legitimate-interest regime) drafted for 10 Jul 2026; postponed at the last minute, no new date (re-confirmed 1 Oct 2026). ERR radio news, 2 Nov 2026: the Ministry of Finance still plans to restrict access but will now amend the law instead of using a ministerial regulation (after feedback from the Ministries of Justice and Digital Affairs). No draft or date announced; Latvia's keep-it-public model rejected; the Ministry would vet applications itself, prioritise journalists and aim to answer faster than the 12-working-day maximum (ministry lawyer Revo Krause). Data stays open until a law is passed and in force. EC infringement procedure over AMLD6 register access (opened 25 Sep 2025; letter of formal notice 25 Sep 2026). AMLR ">= 25 %" + chain multiplication from 10 Jul 2027.
- **Verification**: Filed by the management board without a fee or signature; data confirmed at each annual report filing; changes within 30 days. Banks, payment institutions, accountants, notaries and other obliged entities must report discrepancies: the registrar marks the entry doubtful, tells the board (30 days to confirm or correct) and passes the report to the FIU. The open data publishes a per-entry discrepancy flag (lahknevusteade_esitatud) and a company-level 'absence of BO' report flag (lahknevusteade_puudumisest), not the reports.
- **Company register**: Commercial Register (äriregister), part of the e-Business Register (RIK) — https://ariregister.rik.ee/eng; public: Yes
- **Discrepancy route (BO register)**: https://abiinfo.rik.ee/en/node/287
- **Next FATF/FSRB assessment**: MONEYVAL; onsite 2030-10-01; plenary 2031-05-01
- **Notes**: Threshold (RahaPTS § 9): shares or voting rights, direct or indirect; indirect holdings multiplied down the chain and added across chains; control by other means counts at any percentage; Ministry of Finance guidance treats 25 % as an indicator, not a presumption (per eestifirma.ee, unverified). Legal basis: RahaPTS § 9 (definition), §§ 76–77 (duty to submit). BO = natural person only; a company can have several. Fallback where no qualifying person: the management board member(s) who actually run the company (register codes J / C; per the article only the chair when the board has four or more members — unverified). Exempt (register flag esitab_kasusaajad = false): sole proprietors, apartment and building associations, companies listed on a regulated market, foundations holding assets for named beneficiaries, branches of foreign companies; an OÜ under a listed parent still files. Trusts: settlor, trustee, protector, beneficiaries and anyone else in control are BOs of the company; nominees are looked through. Data filed: name, date and place of birth, personal code + issuing country, country of residence, citizenship(s), manner of control (open data carries name, birth date, country of residence, manner of control; not citizenship or place of birth). Public can search by person; data kept 5 years after deletion. Access to an entry can be restricted for a person at real risk of fraud, kidnapping, blackmail or harassment, or a minor — no UK-style protected/super-secure BO type in the data. Penalties per article: board member up to 300 fine units (€1,200); company up to €400,000. Updated by Claude 20 Oct 2026 from the eestifirma.ee article + OpenCheck's regimes module.
- **Sources**: https://www.riigiteataja.ee/akt/114032025023 · https://eestifirma.ee/en/beneficial-owner-estonian-company/ · https://www.err.ee/1610074771/tegelike-kasusaajate-andmete-varjamine-lukkub-edasi · https://news.err.ee/1610074816/estonia-s-regulation-to-hide-beneficial-owners-postponed · https://www.err.ee/1610183528/rahandusministeerium-plaanib-tegelike-kasusaajate-peitmiseks-muuta-seadust · https://abiinfo.rik.ee/en/node/367

### Finland (FI) — verified 2026-09-18

**Access**: Authorities and obliged entities only.
- **BO register**: Finland Register of Companies — https://virre.prh.fi/novus/home?execution=e1s1
- **How to apply**: https://www.prh.fi/en/companiesandorganisations/beneficial_owner_details/information_services_and_details.html
- **Access detail**: Regulations pending (LIA sheet).
- **Next FATF/FSRB assessment**: FATF; onsite 2027-11-01; plenary 2028-06-01
- **Sources**: https://www.prh.fi/en/companiesandorganisations/beneficial_owner_details/information_services_and_details.html

### France (FR) — verified 2026-09-18

**Access**: Legitimate-interest access.
- **BO register**: Registre National des Entreprises (RNE) — https://data.inpi.fr/
- **How to apply**: https://data.inpi.fr/content/editorial/acces_BE
- **Access detail**: INPI acces_BE procedure.
- **Next FATF/FSRB assessment**: FATF; onsite 2029-06-01; plenary 2030-02-01
- **Sources**: https://data.inpi.fr/content/editorial/acces_BE

### Germany (DE) — verified 2026-11-18

**Access**: Legitimate-interest access.
- **BO register**: Transparenzregister — https://api.transparenzregister.de/
- **How to apply**: https://www.transparenzregister.de/
- **Access detail**: Transparenzregister access on application. AMLD6 Arts 11–13 and 15 (Art. 78 deadline 10 Jul 2026) are to be transposed by the Zollfinanzgerechtigkeitsgesetz (passed by the Bundestag 12 Nov 2026; Bundesrat and BGBl pending; planned in force 1 Jan 2027) as §§23/23a GwG; the GwBG draft of 28 Oct 2026 carries them forward as §§25–26 GwBG from 10 Jul 2027.
- **Pending changes**: Zollfinanzgerechtigkeitsgesetz (BT-Drs. 21/8282), which in the government bill transposes AMLD6 Arts 11–13 and 15 as §§23/23a GwG: amended by the Finanzausschuss on 11 Nov 2026 and passed by the Bundestag on 12 Nov 2026 on its recommendation (Drs. 21/9136). Bundesrat and BGBl publication still to come; planned in force 1 Jan 2027. GwBG (Geldwäschebekämpfungsgesetz) Referentenentwurf, BMF, 28 Oct 2026: repeals the GwG and re-enacts Transparenzregister access, including legitimate-interest access, as §§25–26 GwBG; in force 10 Jul 2027 (Art. 19). Cabinet adoption planned 16 Dec 2026; stakeholder consultation closes 19 Nov 2026.
- **Next FATF/FSRB assessment**: FATF; onsite 2029-02-01; plenary 2029-10-01
- **Notes**: https://www.bundesfinanzministerium.de/Content/DE/Gesetzestexte/Gesetze_Gesetzesvorhaben/Abteilungen/Abteilung_III/21_Legislaturperiode/2026-03-03-Zollfinanzgerechtigkeitsgesetz/0-Gesetz.html
- **Sources**: https://www.transparenzregister.de/ · https://www.bundesfinanzministerium.de/Content/DE/Gesetzestexte/Gesetze_Gesetzesvorhaben/Abteilungen/Abteilung_III/21_Legislaturperiode/2026-03-03-Zollfinanzgerechtigkeitsgesetz/0-Gesetz.html · https://www.bundesfinanzministerium.de/Content/DE/Gesetzestexte/Gesetze_Gesetzesvorhaben/Abteilungen/Abteilung_VII/21_Legislaturperiode/2026-10-28-E6EUGWRL/1-Referentenentwurf.pdf?__blob=publicationFile&v=3

### Gibraltar (GI) — verified 2026-10-08

**Access**: Public.
- **BO register**: UBO Public Register — https://ubo.fsc.gi/
- **How to apply**: https://ubo.fsc.gi/
- **Access detail**: Public UBO register; search fees removed Feb 2026.
- **Next FATF/FSRB assessment**: MONEYVAL; onsite 2027-10-01; plenary 2028-05-01
- **Notes**: From 1 October 2026, public UBO register in Gibraltar has moved to https://ubo.fsc.gi/ instead of https://uboregister.egov.gi/
- **Sources**: https://ubo.fsc.gi/

### Greece (GR) — verified 2026-11-18

**Access**: Authorities and obliged entities only.
- **BO register**: Single Digital Portal — https://www.gsis.gr/polites-epiheiriseis/epiheiriseis/mitroo-pragmatikon-dikaioyhon
- **How to apply**: https://www.hellenicparliament.gr/Nomothetiko-Ergo/Anazitisi-Nomothetikou-Ergou?law_id=21cf1a39-09ed-4b79-9fba-b4f0001d94e6
- **Access detail**: Law 5354/2026 (ΦΕΚ Α΄ 184/9.11.2026; passed 5 Nov 2026; Part Θ′ arts 280–285 of the bill, harmonising with Directive (EU) 2024/1640, amending Law 4557/2018). The register moves from the General Secretariat for Information Systems and Digital Governance to AADE. Persons with a specific legitimate interest ('ειδικό έννομο συμφέρον') apply to the AADE Governor; journalists, civil society organisations/NGOs and academics researching these issues are among the categories named. Decision within 12 working days (7 for a repeat applicant); approval valid 3 years; administrative appeal to a three-member AADE committee; the company is not notified. Data: name, month and year of birth, country of residence, nationality, nature and extent of interest (full date of birth, contact details and tax number where needed for identification). Until then, access for others is by prosecutor's order on proof of a specific legitimate interest (art. 20 para. 6α Law 4557/2018; reportedly added by Law 5259/2025, not verified). Details per press reports of the final bill text (Business Daily 29 Oct 2026); ΦΕΚ text not checked.
- **Pending changes**: Ministry of National Economy and Finance omnibus bill submitted 26 Oct 2026, passed by the Hellenic Parliament on 5 Nov 2026 and published as Law 5354/2026 (ΦΕΚ Α΄ 184/9.11.2026). Part Θ′, Chapter B (arts 280–285 of the bill), 'Access to the Central Register of Beneficial Owners and transfer of competence to AADE – measures harmonising with Directive (EU) 2024/1640 – amendments to Law 4557/2018': art. 283 gives access to persons with a specific legitimate interest ('ειδικό έννομο συμφέρον') by reasoned application to the AADE Governor, replacing the prosecutor's-order route; art. 284 covers verification and mutual recognition. Article numbers in the published law not checked. Start date not fixed: in the consultation draft (Oct 2026) the transfer to AADE takes effect only once a joint ministerial decision published in the ΦΕΚ confirms the system is ready, and access fees are set by joint decision; final text not checked on this point.
- **Next FATF/FSRB assessment**: FATF; onsite 2029-06-01; plenary 2030-02-01
- **Sources**: https://www.hellenicparliament.gr/Nomothetiko-Ergo/Anazitisi-Nomothetikou-Ergou?law_id=21cf1a39-09ed-4b79-9fba-b4f0001d94e6 · https://www.hellenicparliament.gr/UserFiles/7b24652e-78eb-4807-9d68-e9a5d4576eff/13464700.pdf · https://www.businessdaily.gr/oikonomia/240629_ti-allazei-sto-kentriko-mitroo-pragmatikon-dikaioyhon-me-polynomoshedio · https://www.taxheaven.gr/news/74991/ti-allazei-sto-mhtrwo-pragmatikwn-dikaioyxwn

### Guatemala (GT) — verified 2026-11-23

**Access**: No central BO register.
- **How to apply**: https://www.cefilat.org/informes/the-invisible-owners
- **Pending changes**: Iniciativa de ley 6486 (2025) would create a BO register.
- **Next FATF/FSRB assessment**: GAFILAT
- **Notes**: Draft from the CEFILAT/FTC report (Aug 2026): no BO register. 81 ISSUED LEIs.
- **Sources**: https://www.cefilat.org/informes/the-invisible-owners

### Guernsey (GG) — verified 2026-11-18

**Access**: Authorities and obliged entities only.
- **How to apply**: https://gov.gg/beneficial-ownership-consultation-launched
- **Access detail**: LIA consultation 27 Feb–10 Apr 2026; response published 18 Nov 2026: case-by-case LIA (purpose + necessity test), at first open only to applicants in the UK and Crown Dependencies; KYC providers excluded for now; per-application fee to be set with the other Crown Dependencies.
- **Pending changes**: LIA agreed in policy on 18 Nov 2026 but not yet legislated. A Policy Letter goes to the States of Deliberation in early 2027, and the arrangements are meant to take effect later in 2027. An approved applicant would get the name, month and year of birth, nationality, country of residence, and the ownership band or the basis of control. There would be no addresses, no exact percentages, no bulk or subscription access, and the beneficial owner would not be notified. Direct access for UK and Crown Dependency law enforcement is also planned.
- **Next FATF/FSRB assessment**: MONEYVAL (4th round); onsite 2032-04-01; plenary 2032-12-01
- **Sources**: https://gov.gg/beneficial-ownership-consultation-launched · https://gov.gg/article/210020/Guernsey-confirms-next-step-in-beneficial-ownership-transparency · https://www.gov.gg/CHttpHandler.ashx?id=205262&p=0

### Honduras (HN) — verified 2026-11-23

**Access**: No central BO register.
- **How to apply**: https://www.cefilat.org/informes/the-invisible-owners
- **Next FATF/FSRB assessment**: GAFILAT
- **Notes**: Draft from the CEFILAT/FTC report (Aug 2026): no BO register and no BO obligation. 41 ISSUED LEIs.
- **Sources**: https://www.cefilat.org/informes/the-invisible-owners

### Hong Kong (HK) — unverified draft

**Access**: Not yet recorded.
- **Next FATF/FSRB assessment**: FATF / APG; onsite 2029-11-01; plenary 2030-06-01
- **Notes**: Significant Controllers Register kept at company level, not central; CR publishes officers/BRN only.

### Hungary (HU) — verified 2026-09-18

**Access**: Authorities and obliged entities only.
- **Next FATF/FSRB assessment**: MONEYVAL; onsite 2026-10-01; plenary 2027-05-01

### Iceland (IS) — verified 2026-09-18

**Access**: Not yet recorded.
- **BO register**: Register of Enterprises — https://www.skatturinn.is/fyrirtaekjaskra/
- **Next FATF/FSRB assessment**: FATF; onsite 2026-06-01; plenary 2027-02-01

### India (IN) — unverified draft

**Access**: Not yet recorded.
- **Next FATF/FSRB assessment**: FATF / APG / EAG; onsite 2030-11-01; plenary 2031-06-01

### Ireland (IE) — verified 2026-11-15

**Access**: Legitimate-interest access.
- **BO register**: Central Register of Beneficial Ownership of Companies and Industrial and Provident Societies (RBO) — https://rbo.gov.ie/
- **How to apply**: https://rbo.gov.ie/faqs/access-to-the-search-facility-on-the-rbo-register/
- **Access detail**: SI 406/2026 (made 4 Aug 2026, notified 7 Aug 2026) introduces LIA from 10 Nov 2026, amending SI 110/2019 Reg. 25. Apply online through the RBO Customer Portal with ID, supporting evidence and the AML/CFT purpose. Deemed to have a legitimate interest (Reg. 25(3A)(b)): journalists and CSOs, including NGOs and academia, connected with preventing AML/CFT; persons likely to transact with the entity; third-country obliged entities and authorities; AML/CFT product providers serving obliged entities or authorities; and certain public bodies. Except for journalists and CSOs, the Registrar weighs the applicant's connection to the specific entity (Reg. 25(3C)(d)). The Registrar answers within 12 working days, extendable by 12 and a further 12 working days in a surge, plus 7 working days if more information is asked for, never more than 43 working days (Reg. 25(3E)-(3G)). Approval gives a certificate valid for 3 years or until revoked, and later inspection requests are answered within 7 working days (Reg. 25(3B)(a)). Another Member State's verification satisfies the occupation check (Reg. 25(3H)). Journalists, CSOs and third-country authorities may also see history for the preceding 5 years, including dissolved entities, and a description of the control or ownership structure (Reg. 25(3)(b)). Refusal or revocation can be appealed to the District Court within 10 working days (Reg. 25(5B)). Fees are limited to cost (Reg. 27(2)); the RBO currently charges €2.50 per report. SI 335/2026 applies the same scheme to the trusts register (CRBOT).
- **Company register**: Companies Registration Office Ireland — https://cro.ie/; public: —
- **Discrepancy route (BO register)**: https://rbo.gov.ie/faqs/reporting-of-discrepancies-and-non-compliance/
- **Next FATF/FSRB assessment**: FATF; onsite 2028-02-01; plenary 2028-10-01
- **Notes**: New access rules kick in from 10 November 2026 https://www.irishstatutebook.ie/eli/2026/si/406/made/en/pdf. The RBO FAQ (10 Nov 2026) also lists the extent of ownership or control among the fields an approved applicant may see, without saying whether it is a band or an exact figure, and says certain approved categories may also see historic beneficial ownership information. Older answers further down the same FAQ page still say beneficial ownership details are only available to designated persons; the legitimate-interest section is the current guidance. The general public sees the entity profile and the number of beneficial owners filed.   Ireland keeps three beneficial ownership registers. This row is the RBO (companies and industrial and provident societies, DETE, SI 110/2019 as amended by SI 406/2026). Trusts are in the Central Register of Beneficial Ownership of Trusts (CRBOT) (https://www.revenue.ie/en/crbot/index.aspx), operated by the Revenue Commissioners; SI 335/2026 (made 16 Jul 2026) gives it the same legitimate-interest scheme from 10 Nov 2026, with the same fields, deadlines and District Court appeal. CRBOT access requests: https://www.revenue.ie/en/crbot/inspecting-the-crbot/when-can-the-crbot-be-accessed.aspx. Certain financial vehicles are in the Register of Beneficial Ownership of Certain Financial Vehicles (CFV) (https://www.centralbank.ie/regulation/anti-money-laundering-and-countering-the-financing-of-terrorism/beneficial-ownership-register), maintained by the Central Bank of Ireland; the 15 Nov 2026 press release says it is covered but names no SI, so its access rules are not yet verified. CFV legitimate-interest access guidance: https://www.centralbank.ie/regulation/anti-money-laundering-and-countering-the-financing-of-terrorism/beneficial-ownership-register/access-the-register. Under both SIs an approved applicant sees name, month and year of birth, country of residence, nationality, and the nature and extent of the beneficial interest.
- **Sources**: https://rbo.gov.ie/faqs/access-to-the-search-facility-on-the-rbo-register/ · https://www.irishstatutebook.ie/eli/2026/si/406/made/en/pdf · https://rbo.gov.ie/faqs/reporting-of-discrepancies-and-non-compliance/ · https://rbo.gov.ie/wp-content/uploads/sites/2/2026/11/How-to-apply-for-Legitimate-Interest.pdf · https://www.irishstatutebook.ie/eli/2026/si/335/made/en/print · https://www.gov.ie/en/department-of-finance/press-releases/t%C3%A1naiste-announces-new-transparency-measures-to-strengthen-irelands-anti-money-laundering-regime/ · https://www.revenue.ie/en/crbot/index.aspx · https://www.revenue.ie/en/crbot/inspecting-the-crbot/when-can-the-crbot-be-accessed.aspx · https://www.centralbank.ie/regulation/anti-money-laundering-and-countering-the-financing-of-terrorism/beneficial-ownership-register · https://www.centralbank.ie/regulation/anti-money-laundering-and-countering-the-financing-of-terrorism/beneficial-ownership-register/access-the-register

### Isle of Man (IM) — verified 2026-09-18

**Access**: Authorities and obliged entities only.
- **How to apply**: https://consult.gov.im/economic-development/updating-the-islands-corporate-laws/
- **Access detail**: Obliged entities can request IOMDBO access from 31 Dec 2024; corporate-law consultation Nov 2025.
- **Next FATF/FSRB assessment**: MONEYVAL; onsite 2026-10-01; plenary 2027-05-01
- **Sources**: https://consult.gov.im/economic-development/updating-the-islands-corporate-laws/

### Israel (IL) — verified 2026-11-11

**Access**: Authorities and obliged entities only.
- **How to apply**: https://data.gov.il/dataset/ica_companies
- **Company register**: Registrar of Companies and Registrar of Partnerships (Israel Corporations Authority) — https://www.gov.il/en/departments/israeli_corporations_authority; public: Yes
- **Notes**: No public central beneficial ownership register was found; the Corporations Authority publishes companies and partnerships (name, number, type, status, address) as open data on data.gov.il, not shareholders or beneficial owners.
- **Sources**: https://data.gov.il/dataset/ica_companies · https://data.gov.il/dataset/ica_partnerships · https://www.gov.il/en/departments/israeli_corporations_authority

### Italy (IT) — verified 2026-11-20

**Access**: Restricted; legitimate-interest route in law but not yet open.
- **BO register**: Registro dei Beneficiari Effettivi delle Società — https://www.registroimprese.it/rebec
- **How to apply**: https://www.dt.mef.gov.it/it/dipartimento/consultazioni_pubbliche/consultazione_20192026.html
- **Access detail**: D.Lgs. 10 giugno 2026, n. 122 (GU Serie generale n. 156, 8 July 2026; in force the fifteenth day after publication) transposes Arts 11, 12, 13 and 15 of Directive (EU) 2024/1640 and inserts art. 21-quater into d.lgs. 231/2007: access for natural or legal persons with a 'legittimo interesse'. Art. 2(4): the access system operates only once MIMIT adopts a measure declaring it operational (due within 60 days, after the technical decree); ItaliaOggi (23 Sep 2026) reports the deadline expired on 21 September with the register still blocked. The full AMLD6 transposition decree, in consultation from 20 Nov 2026 (comments by 14 Dec 2026), would repeal d.lgs. 231/2007 and re-enact legitimate-interest access in its Arts 70–72, applying from 10 Jul 2027 (https://www.dt.mef.gov.it/it/dipartimento/consultazioni_pubbliche/consultazione_20192026.html).
- **Pending changes**: Technical specifications (Fedra 7.20) approved by MIMIT decree of 23 Sep 2026 (GU n. 228, 1 Oct 2026); they take effect only from the MIMIT measure under art. 2(4) D.Lgs. 122/2026 declaring the access system operational, not yet adopted as of 21 Oct 2026. Draft legislative decree transposing Directive (EU) 2024/1640 and adapting national law to Regulations (EU) 2024/1624 and 2024/1620 (delegation: art. 14, legge 13 giugno 2025, n. 91): public consultation by the MEF Dipartimento del Tesoro opened 20 Nov 2026; comments by 14 Dec 2026 to AML.Consultazioni@mef.gov.it. The consultation paper says the decree enters into force 15 days after publication in the Gazzetta Ufficiale and applies from 10 Jul 2027. It repeals d.lgs. 231/2007 (Art. 100), so the register rules D.Lgs. 122/2026 inserted there (art. 21-quater) are re-enacted in Title IV, Arts 64–74. Register: the BO section of the Registro delle Imprese widens from società di capitali to every company registered there (società di persone included), private legal persons, express trusts and similar arrangements, with the content of AMLR Arts 62, 63(4) and 66 (nominees); filing within 30 days of formation, changes within 28 days (Art. 64). Camere di commercio verify (automatic, sample and discrepancy-led checks, with the Guardia di Finanza), annotate open discrepancies and targeted-financial-sanctions designations visibly to everyone with access (Arts 65–66). Legitimate interest (Art. 70): name, month and year of birth, country of residence and nationality, nature and extent of the interest, with no prior notice to the BO. Presumed for (a) giornalisti professionisti and pubblicisti on the albo under L. 69/1963 acting for media purposes connected with AML/CFT; (b) enti del terzo settore including NGOs, university professors and researchers, and public research staff; (c) persons documenting an actual commercial or financial negotiation; also third-country obliged entities and authorities, company-law authorities, EU-funds, PNRR and procurement bodies and ANAC, and AML product providers; others, including carriers of diffuse interests, case by case (Art. 70(4)). Categories (a), (b) and (e) also see historical data (including entities dissolved in the previous five years) and a description of the ownership or control structure (Art. 70(3)). Procedure (Art. 71): reasoned application with supporting documents to the competent Camera di commercio, eID for online access, decision by PEC within 12 working days (extendable twice by 12 for high volumes; no answer counts as refusal); a 3-year accreditation certificate, not limited to named entities for (a) and (b), with category membership re-checked every 18 months; another member state's finding accepted. Fees (diritti di segreteria) apply, public bodies exempt (Art. 70(5)). The BO is told who consulted only on request (GDPR Art. 15), and for journalists and CSOs only their profession or function (Art. 70(6)–(7)). Exemption for exceptional circumstances on the BO's declaration, case by case, with access granted no earlier than 30 days after the BO is told (Art. 72). BO access status unchanged: a draft under consultation. https://www.dt.mef.gov.it/it/dipartimento/consultazioni_pubbliche/consultazione_20192026.html
- **Company register**: Registro delle Imprese — https://www.registroimprese.it/; public: —
- **Sources**: https://www.dt.mef.gov.it/it/dipartimento/consultazioni_pubbliche/consultazione_20192026.html · https://www.dt.mef.gov.it/export/sites/sitodt/modules/documenti_it/regolamentazione_bancaria_finanziaria/consultazioni_pubbliche/Schema_decreto_AML.pdf · https://www.dt.mef.gov.it/export/sites/sitodt/modules/documenti_it/regolamentazione_bancaria_finanziaria/consultazioni_pubbliche/Documento_consultazione_schema_AML_-final.pdf

### Japan (JP) — verified 2026-11-23

**Access**: No central BO register.
- **How to apply**: https://www.cas.go.jp/jp/houan/261023/shiryo00.pdf
- **Pending changes**: Bill on the Grasping of Information on Beneficial Owners of Corporations, etc. (法人等の実質的支配者に係る情報の把握等に関する法律案), Cabinet Bill No. 19, approved by Cabinet and submitted to the 222nd Diet on 23 Oct 2026; not yet passed as of 16 Nov 2026. Domestic corporations other than listed companies, and foreign corporations that trade continuously in Japan, have an office there or own real estate there, would report beneficial owners (natural persons holding more than 25% of voting rights, directly or indirectly: name, address, date of birth, nationality) to the Legal Affairs Bureau at formation and on change. Not public: government agencies for their statutory duties, and obliged entities under the Act on Prevention of Transfer of Criminal Proceeds with the corporation's consent. Trustees must keep information on trust parties. In force on a day set by Cabinet Order within 1 year 6 months of promulgation.
- **Company register**: Commercial and corporate registration (商業・法人登記), Legal Affairs Bureaus, Ministry of Justice — https://www1.touki.or.jp/; public: Yes
- **Next FATF/FSRB assessment**: FATF / APG
- **Notes**: Drafted by Claude on 16 Nov 2026 for the NTA Japan wiring; reviewed and verified on 16 Nov 2026. Japan is the only G7 country without a central register of beneficial owners. Since 31 Jan 2022 a stock company may voluntarily lodge a list of its beneficial owners with the Legal Affairs Bureau, which issues certified copies to the company itself; no register of beneficial owners is open to the public. The company register (fee-based online access) publishes representative directors and directors, not shareholders. OpenCheck reads the National Tax Agency's corporate number register, which publishes identity and standing only. FATF's fifth-round onsite assessment of Japan is expected around summer 2028.
- **Sources**: https://www.cas.go.jp/jp/houan/261023/shiryo00.pdf · https://www.shugiin.go.jp/Internet/itdb_gian.nsf/html/gian/honbun/houan/g22209019.htm · https://www.cas.go.jp/jp/seisaku/beneficial_ownership/dai1/shiryo2.pdf · https://www.japantimes.co.jp/news/2026/10/02/japan/crime-legal/beneficial-owners-information-reporting/

### Jersey (JE) — verified 2026-11-22

**Access**: Authorities and obliged entities only.
- **BO register**: JFSC Registry — https://www.jerseyfsc.org/registry/beneficial-ownership-information/
- **How to apply**: https://www.gov.je/Government/Consultations/Pages/CentralRegisterLegitimateInterest.aspx
- **Access detail**: Obliged-entity access since 20 Feb 2025; LIA consultation Oct 2025 (closed 30 Jan 2026), response paper 18 Nov 2026: legislation to be drafted, no date set; incorporation threshold 10%→25% from 31 Mar 2026.
- **Pending changes**: Consultation response paper 'Access to beneficial ownership information by persons with legitimate interest' (Department for the Economy), published 18 Nov 2026 for the consultation that ran 31 Oct 2025 – 30 Jan 2026 (26 substantive responses). Government will now draft the legislation, with JFSC systems and operational work alongside; no timetable, date or draft law is given. Policy positions: access for natural and legal persons (a legal person names the natural person acting for it, who verifies their identity and makes the declarations) (¶15); purpose is preventing, detecting or investigating ML/TF/PF, now including predicate offences such as corruption, fraud and tax evasion (¶13–14); two-limb test of purpose and necessity, with evidence that reasonable alternative sources have been exhausted expected (¶24–25); no presumed access for any category, every application assessed case by case against the specific enquiry, investigation or research project (¶27, ¶35). Journalists, civil society organisations and academics may qualify, but access 'may initially be limited' to those from the UK and the Crown Dependencies: journalists under the editorial oversight of a media organisation subject to a recognised UK or CD regulator or complaints body; CSOs overseen by a recognised UK or CD regulatory body and established for a public-interest purpose of preventing, investigating, exposing or reporting financial and economic crime; academics employed by a recognised UK or CD higher education institution; applicants elsewhere may 'consider applying through a UK body'; to be reviewed with operational experience (¶36–37, ¶83). Digital KYC providers are not part of the regime: their access is a separate Government/JFSC project (¶39, ¶57, ¶104). Direct access for UK and CD authorities is being explored (¶40). Data disclosed: name, month and year of birth, country of residence, nationality, and nature and extent of the interest (the last subject to the JFSC's disclosable-BO-information work); no historical data (¶41–46). Grouped requests allowed where entities are clearly connected, with no numerical cap; the Registrar may ask for more, remove entities or approve in part; no bulk downloads, unrestricted searching or harvesting (¶53–56). Exemptions on the existing DPI Regulations grounds, case by case and evidenced, with interim protection while an application is assessed and a window before the regime opens for beneficial owners to apply (¶66–70). Declarations, sanctions for misuse or false information (including restrictions on future access), audit trails and onward-transfer limits to adequate jurisdictions (¶81–83). Beneficial owners are not notified of each disclosure; subject-access rights under review (¶84–85). Applications through the JFSC Registry online portal, for a fee whose structure is not yet set (¶87, ¶101). No FIU role in the process (¶102). Access decisions in another Crown Dependency are not recognised in Jersey (¶105). Appeal to the Royal Court on unreasonableness, with a preliminary review step under consideration; written reasons given (¶113–116). BO access status unchanged: policy settled, legislation not yet drafted. https://www.gov.je/SiteCollectionDocuments/Industry%20and%20finance/Access%20To%20Beneficial%20Ownership%20Consultation%20Response%20Paper%20Nov%202026.pdf
- **Next FATF/FSRB assessment**: MONEYVAL (4th round); onsite 2032-04-01; plenary 2032-12-01
- **Sources**: https://www.gov.je/Government/Consultations/Pages/CentralRegisterLegitimateInterest.aspx · https://www.gov.je/SiteCollectionDocuments/Industry%20and%20finance/Access%20To%20Beneficial%20Ownership%20Consultation%20Response%20Paper%20Nov%202026.pdf · https://files.smartsurvey.io/3/0/BSOCABWI/Consultation_Document_Beneficial_Ownership_Information_Access.pdf

### Latvia (LV) — verified 2026-11-19

**Access**: Public.
- **BO register**: Register of Enterprises — https://info.ur.gov.lv/#/data-search
- **How to apply**: https://www.ur.gov.lv/en/explanation-beneficial-owners
- **Threshold (as worded)**: vairāk nekā 25 % (more than 25 %)
- **Access detail**: Register stays public. 3 Dec 2025 amendments (in force 1 Apr 2026) transpose AMLD6 Art 15; from 1 Jul 2026 any BO can request case-by-case restricted-access status on personal-risk grounds (no fee; automatic 1-month temporary concealment within 1 working day; annual reconfirmation required; refusal appealable to Chief State Notary then court). Restriction also conceals the BO's shareholder/owner records where those confer BO status; competent authorities retain access.
- **Pending changes**: By 1 Jan 2027 UR must auto-restrict shareholder/owner records of BOs already restricted as minors/limited-capacity (transitional provision). Apartment owners' associations brought into BO disclosure 5 Jan 2026; transitional filings due 1 Oct 2026. Foreign legal entities must file BO before registering immovable property (Land Register Law s61.2).
- **Verification**: Verified 2026-10-01 against ur.gov.lv/en/explanation-beneficial-owners: definition still 'more than 25%' (cites AMLD4 Art 3(6) + FATF Mar 2023 guidance — no AMLR '25% or more' language yet). Control manner + extent + intermediary person are registered per BO, though not published — consistent with OpenCheck audit finding 3. Threshold source: UR EN explanation, "more than 25% of the capital shares or voting shares", NILLTPFN likums Art 1(5)(a). 1 Jan 2027 minors'-records change kept in Pending changes, not Next change expected (that date drives OpenCheck's 'becoming restricted' footnote).
- **Company register**: Register of Enterprises — https://www.ur.gov.lv/en; public: Yes
- **Discrepancy route (BO register)**: https://www.ur.gov.lv/lv/patieso-labuma-guveju-skaidrojums/zinosana-par-neatbilstosu-informaciju-par-plg/
- **Notes**: Changes made from 5 October 2026 explained in Untitled and should be followed through till EU AML Regulation implementation in July 2027  From 19 Nov 2026 the Register of Enterprises treats information on joint-stock company (AS) shareholders (akcionāri) who are natural persons, and the shareholders' register section, as not generally available: it is in the non-public part of the registration file, following the Constitutional Court (Satversmes tiesa) judgment of 9 Nov 2026 in case No. 2024-01-01. It can be requested with a stated legal basis and purpose. UR says the restriction is in its information system and most data distribution channels, with work continuing on the rest; the data.gov.lv AS shareholders dataset answers HTTP 403 from 19 Nov 2026. The notice does not mention limited-company (SIA) members (dalībnieki) or beneficial owners, which remain public.
- **Sources**: https://www.ur.gov.lv/en/explanation-beneficial-owners · https://www.ur.gov.lv/lv/jaunums/informacija-par-akcionariem-fiziskam-personam-ieklauta-uznemumu-registra-registracijas-lietas-nepubliskaja-dala

### Liechtenstein (LI) — verified 2026-09-18

**Access**: Authorities and obliged entities only.
- **Next FATF/FSRB assessment**: MONEYVAL; onsite 2030-04-01; plenary 2030-12-01

### Lithuania (LT) — verified 2026-09-18

**Access**: Legitimate-interest access.
- **BO register**: Information System of Legal Entities Participants (JADIS) — https://www.registrucentras.lt/savitarna/
- **How to apply**: https://www.e-tar.lt/portal/lt/legalAct/TAR.672DFD353334/asr
- **Access detail**: JADIS; eu_bo_access.json restricted_from null.
- **Next FATF/FSRB assessment**: MONEYVAL; onsite 2027-10-01; plenary 2028-05-01
- **Sources**: https://www.e-tar.lt/portal/lt/legalAct/TAR.672DFD353334/asr

### Luxembourg (LU) — verified 2026-09-18

**Access**: Legitimate-interest access.
- **BO register**: Registre de Bénéficiaires Effectifs (RBE) — https://www.lbr.lu/mjrcs-rbe/jsp/
- **How to apply**: https://legilux.public.lu/eli/etat/leg/loi/2025/01/23/a22/jo#art_36
- **Access detail**: On 27th January 2025, Luxembourg gazetted changes to the access regime for its beneficial ownership register following the passage of 6AMLD and to codify LIA. However the Luxembourg legislation imposes a narrower set of LIA categories than 6AMLD with no mention of providers of AML/CFT products.
- **Next FATF/FSRB assessment**: FATF; onsite 2030-06-01; plenary 2031-02-01
- **Sources**: https://legilux.public.lu/eli/etat/leg/loi/2025/01/23/a22/jo#art_36

### Malta (MT) — verified 2026-10-06

**Access**: Legitimate-interest access.
- **BO register**: Business Automation Registry Online System (BAROS) — https://baros.mbr.mt/app/home
- **How to apply**: https://legislation.mt/eli/ln/2026/184/mlt
- **Access detail**: LN 184/2026 in force 10 Jul 2026 transposes AMLD6 Arts 11-13, 15; case-by-case https://legislation.mt/eli/ln/2026/184/mlt/portalpdf
- **Company register**: Business Automation Registry Online System — https://baros.mbr.mt/app/home; public: Partly
- **Next FATF/FSRB assessment**: MONEYVAL; onsite 2028-04-01; plenary 2028-12-01
- **Sources**: https://legislation.mt/eli/ln/2026/184/mlt · https://www.mbr.mt/post/informative-note-entry-into-force-of-legislation-3

### Mexico (MX) — verified 2026-11-23

**Access**: No central BO register.
- **How to apply**: https://www.cefilat.org/informes/the-invisible-owners
- **Pending changes**: A reform initiative in the Senate would create a national BO register.
- **Next FATF/FSRB assessment**: FATF / GAFILAT
- **Notes**: Draft from the CEFILAT/FTC report (Aug 2026): no national BO register. The Código Fiscal de la Federación requires legal persons to identify and keep BO information (held, not filed). Guadalajara has a subnational registry. datos.gob.mx answered 403 from the cloud. 4,491 ISSUED LEIs (RA000449, RFC).
- **Sources**: https://www.cefilat.org/informes/the-invisible-owners

### Moldova (MD) — unverified draft

**Access**: Not yet recorded.
- **Next FATF/FSRB assessment**: MONEYVAL; onsite 2028-04-01; plenary 2028-12-01

### Netherlands (NL) — verified 2026-11-20

**Access**: Restricted; legitimate-interest route in law but not yet open.
- **BO register**: UBO register — https://www.kvk.nl/ubo/
- **How to apply**: https://www.kvk.nl/en/ubo/who-has-access-to-ubo-data/
- **Access detail**: Public access ended 16 Jul 2025; LIA decree still pending 20 Nov 2026 https://wetgevingskalender.overheid.nl/Regeling/WGK015141. The other AMLD6 UBO-register provisions (Arts 10–15: verification, discrepancies, historical data, notification on request) are in the Implementatiewet ter voorkoming van witwassen en terrorismefinanciering, sent to the Tweede Kamer 20 Nov 2026 https://wetgevingskalender.overheid.nl/Regeling/WGK027204.
- **Pending changes**: Wijzigingsbesluit toegang UBO-registers voor natuurlijke personen en rechtspersonen met een legitiem belang (AMvB, KetenID WGK015141; implements Arts 12–15 Directive 2024/1640; entry into force by Royal Decree). Proposed new Art. 51ab Handelsregisterbesluit 2008 / Art. 6b Implementatiebesluit trusts; categories include journalists and civil society organisations. Internet consultation 28 Nov 2025 – 9 Jan 2026; preparatory documents published 26 Mar 2026; referred to Raad van State 21 May 2026 (listed as pending 1 Jun 2026); RvS advice W06.26.00149/III dated 15 Jul 2026 (published 16 Jul 2026); implementation table published 29 Jul 2026. Awaiting publication in the Staatsblad (status as of 20 Nov 2026: Wetgevingskalender still shows the Raad van State step). RvS dictum: do not adopt unless amended. (1) The draft drops the AMLD6 Art. 12(2) second-paragraph catch-all for 'other persons with a demonstrable legitimate interest' (removed after KvK said it was unworkable without objective criteria); RvS says it must be implemented, and the case-by-case assessment need not be done by KvK. (2) Art. 22a(3) Handelsregisterwet / Art. 7(4) Implementatiewet (from amendment Kamerstukken II 36584, nr. 21) require KvK to notify the UBO of each legitimate-interest consultation and its purpose. These take effect when this decree enters into force and contradict AMLD6 Art. 12(1) (access without alerting the entity). RvS advises aligning them with the directive, e.g. via the pending Implementatiewet ter voorkoming van witwassen en terrorismefinanciering. https://wetgevingskalender.overheid.nl/Regeling/WGK015141 \| https://www.raadvanstate.nl/adviezen/@158603/w06-26-00149-iii/ Implementatiewet ter voorkoming van witwassen en terrorismefinanciering (wet, KetenID WGK027204): bill and nader rapport published 20 Nov 2026 and sent to the Tweede Kamer (RvS advice W06.26.00123/III of 12 Aug 2026). Implements Directive 2024/1640 (AMLD6) and gives effect to Regulation 2024/1624 (AMLR): designates supervisors, sets sanctions and fills member-state options, and repeals the Wwft (Art. 7.5). Entry into force by Royal Decree; the ministry says July 2027. UBO register (Art. 6.3 amends the Handelsregisterwet 2007, Art. 6.4 the trusts Implementatiewet): 'uiteindelijk belanghebbende' becomes 'uiteindelijk begunstigde'; new Art. 15a records BOs as AMLR Art. 62 requires, or where none can be identified a justified statement plus every senior managing official (AMLR Art. 63(3)–(4)); BSN or a foreign tax number as the unique identifier; copies of the documents used to verify; nominee and nominator data (AMLR Art. 66) and the Art. 63(6) contact person; BO information machine-readable. KvK gains verification duties and may withhold or suspend proof of registration (Art. 41b), must resolve reported discrepancies within 30 working days and may correct the register (Art. 41c), flags BOs designated under targeted financial sanctions (Art. 16d) and reports suspicions to FIU-Nederland (Art. 41d). Access: Art. 22a(1) obliged entities established in NL (for CDD) and Sanctiewet 1977 institutions; Art. 22a(2) keeps the legitimate-interest route by AMvB and adds that the persons in AMLD6 Art. 12(2)(a), (b) and (e) may also see historical BO information (including entities dissolved in the previous five years) and a description of the ownership or control structure; Art. 22a(3) changed so KvK tells the UBO about consultations only when the UBO asks, applying AMLD6 Art. 12(4). This answers RvS point (2) above: the government accepted the RvS view and dropped periodic notification. Art. 2.2 forbids an entity that is not an obliged entity from entering the new minimum registration, so it cannot be used to reach the UBO register. The bill does not itself open legitimate-interest access, which still waits for decree WGK015141; BO access status unchanged. https://open.overheid.nl/details/03d15279-75ac-45f9-a936-c946f8ef66a6 \| https://open.overheid.nl/details/5ce40788-af04-4772-ade3-0c180ea5839e \| https://wetgevingskalender.overheid.nl/Regeling/WGK027204
- **Company register**: Handelsregister — https://www.kvk.nl/zoeken/; public: Yes
- **Next FATF/FSRB assessment**: FATF; onsite 2030-02-01; plenary 2030-10-01
- **Notes**: Stb. 2026, 333 (Besluit of 22 Sep 2026, published 23 Oct 2026, in force 24 Oct 2026) — Wijzigingsbesluit toegang UBO-registers voor bestuursorganen en rechtspersonen met een overheidstaak. New Art. 51aa Handelsregisterbesluit 2008 and Art. 6a Implementatiebesluit (trusts) designate public bodies with UBO access for non-AML tasks: RRF and EU cohesion-fund managing authorities, Bibob bodies, DNB/AFM (fit-and-proper and named supervisory tasks), EZ investment screening (BTI), bailiffs, notaries (Art. 2 Wna acts outside the Wwft), BFT, NIWO (Russia/Belarus road-haulage sanctions) and BZK (party financing). Customs inspector added as competent authority. Art. 51b amended so these bodies, Wwft institutions acting under the Sanctiewet 1977 and AMLD6 Art. 11(1)(e)–(h) bodies see shielded data. Does not open the legitimate-interest route: the explanatory note says a separate AMvB for that is still being prepared, so BO access status is unchanged.
- **Sources**: https://www.kvk.nl/en/ubo/who-has-access-to-ubo-data/ · https://wetgevingskalender.overheid.nl/Regeling/WGK015141 · https://zoek.officielebekendmakingen.nl/stb-2026-333.html · https://open.overheid.nl/details/03d15279-75ac-45f9-a936-c946f8ef66a6 · https://open.overheid.nl/details/5ce40788-af04-4772-ade3-0c180ea5839e

### New Zealand (NZ) — verified 2026-09-18

**Access**: No central BO register.
- **Next FATF/FSRB assessment**: FATF / APG; onsite 2029-02-01; plenary 2029-10-01
- **Notes**: No BO register; Companies Office publishes officers and shareholders.

### Nicaragua (NI) — verified 2026-11-23

**Access**: Authorities and obliged entities only.
- **How to apply**: https://www.cefilat.org/informes/the-invisible-owners
- **Next FATF/FSRB assessment**: GAFILAT
- **Notes**: Draft from the CEFILAT/FTC report (Aug 2026). Threshold 25%. Law 1035/2020, Law 1113/2022; Normativa de Funcionamiento del Registro (25 Jul 2023). Private register within the National Registry System. Art. 156 requires the chain of ownership; final fallback is the legal representative. Fines up to USD 1,500; registry entries can be frozen and notaries barred from acting for non-compliers. The report found no evidence of how it works in practice. 4 ISSUED LEIs.
- **Sources**: https://www.cefilat.org/informes/the-invisible-owners

### Nigeria (NG) — verified 2026-09-18

**Access**: Public.
- **BO register**: CAC Beneficial Ownership Register — https://bor.cac.gov.ng/
- **How to apply**: https://bor.cac.gov.ng/
- **Access detail**: CAC BOR public; 5% threshold; v1 API Sept 2026.
- **Next FATF/FSRB assessment**: GIABA; onsite 2028-03-01; plenary 2028-11-01
- **Notes**: CAC BOR is the full-economy register
- **Sources**: https://bor.cac.gov.ng/

### Norway (NO) — verified 2026-09-18

**Access**: Legitimate-interest access.
- **BO register**: Registeret over reelle rettighetshavere — https://www.brreg.no/reelle-rettighetshavere/
- **How to apply**: https://www.brreg.no/bruke-data-fra-bronnoysundregistrene/datasett-og-api/data-om-reelle-rettighetshavere/
- **Access detail**: EEA; joined BORIS April 2026 as 17th jurisdiction.
- **Discrepancy route (BO register)**: https://info.altinn.no/en/forms-overview/bronnoysund-register-centre/notice-of-discrepancy/
- **Next FATF/FSRB assessment**: FATF; onsite 2028-02-01; plenary 2028-10-01
- **Sources**: https://www.brreg.no/bruke-data-fra-bronnoysundregistrene/datasett-og-api/data-om-reelle-rettighetshavere/

### Panama (PA) — verified 2026-11-23

**Access**: Authorities and obliged entities only.
- **How to apply**: https://www.cefilat.org/informes/the-invisible-owners
- **Threshold (as worded)**: 25% of shares, holdings or voting rights
- **Company register**: Registro Público de Panamá; public: —
- **Next FATF/FSRB assessment**: GAFILAT
- **Notes**: Draft from the CEFILAT/FTC report (Aug 2026). Law 129/2020 amended by Law 254/2021; Executive Decree 13 (25 Mar 2022), Art. 10.iii.a for the threshold (wording above is the report's English, not the statute). Filed through resident agents; five authorities have legal access, the banking regulator de facto access; ANTAI cannot consult it. Cross-checked against international lists, sanctions and open sources. Fideicomisos are not covered entities but are identified inside corporate structures. Regulator reports ~85% coverage; a list of fines is published. Registro Público: 763,748 active and 395,159 suspended companies (31 Mar 2021); Circular MEF-2026-15506 (16 Mar 2026): 360,000+ companies dissolved, lists published by the Registro Público. 2,522 ISSUED LEIs (RA000478, folio).
- **Sources**: https://www.cefilat.org/informes/the-invisible-owners

### Paraguay (PY) — verified 2026-11-23

**Access**: Authorities and obliged entities only.
- **How to apply**: https://www.cefilat.org/informes/the-invisible-owners
- **Next FATF/FSRB assessment**: GAFILAT
- **Notes**: Draft from the CEFILAT/FTC report (Aug 2026). Threshold 10% (control 25%; capital from bearer-share jurisdictions means all shares are reported). Law 6446/2019, Decree 3241/2020. Held by the Dirección General de Personas y Estructuras Jurídicas y Beneficiarios Finales. Art. 10 public list: RUC and name of compliant entities only. Open data: 46,482 enrolled, 31,650 filed (68.1%, 24 Jul 2026); covers 14 legal-person types plus fiduciary businesses, mandates, mutual and investment funds. Fines 50–500 minimum daily wages or up to 30% of profits. ~1,600 reports a year to authorities, by request, not online. datos.gov.py was under maintenance on 23 Nov 2026. 111 ISSUED LEIs (RA000480, RUC).
- **Sources**: https://www.cefilat.org/informes/the-invisible-owners

### Peru (PE) — verified 2026-11-12

**Access**: Authorities and obliged entities only.
- **How to apply**: https://contratacionesabiertas.oece.gob.pe
- **Company register**: Registro de Personas Jurídicas (SUNARP) — https://www.sunarp.gob.pe; public: Partly
- **Notes**: Beneficial owners are declared to SUNAT under Decreto Legislativo 1372 (2018) and are not published. OECE's Registro Nacional de Proveedores publishes, as open data, the partners, legal representatives and governing-body members each supplier to the state declares (a self-declaration to a procurement regulator, not an ownership or BO register); OpenCheck reads that file without any person's document number.
- **Sources**: https://contratacionesabiertas.oece.gob.pe · https://www.gob.pe/sunat

### Poland (PL) — verified 2026-11-23

**Access**: Restricted; legitimate-interest route in law but not yet open.
- **BO register**: Centralny Rejestr Beneficjentów Rzeczywistych (CRBR) — https://crbr.podatki.gov.pl/adcrbr/#/wyszukaj
- **How to apply**: https://legislacja.rcl.gov.pl/projekt/12396501/katalog/13120732
- **Access detail**: CRBR restrictions from 1 Jul 2026; UC75 draft bill to amend Poland’s AML / CFT Act approved on 2026-10-16 by Council of Ministers
- **Pending changes**: Government bill amending the AML/CFT Act (UC75; RM-0610-147-26): new art. 68d gives access to the CRBR to anyone who shows 'uzasadniony interes'. Adopted by the Council of Ministers (Rada Ministrów) as a measure to implement EU law and sent to the Sejm (22 Sep 2026 per KAS); Sejm druk nr 3163, dated 28 Sep 2026, delivered 5 Oct 2026. First reading in the Sejm plenary on 9 Oct 2026 (66th sitting, item 43); committee report druk nr 3285 (4 Nov 2026); second reading 5 Nov 2026; passed by the Sejm at third reading on 6 Nov 2026 (281 for, 21 against, 146 abstaining). Senate and Dziennik Ustaw still to come as of 22 Nov 2026. KAS: rules generally in force 1 January 2027.
- **Next FATF/FSRB assessment**: MONEYVAL; onsite 2029-10-01; plenary 2030-05-01
- **Sources**: https://legislacja.rcl.gov.pl/projekt/12396501/katalog/13120732

### Portugal (PT) — verified 2026-09-18

**Access**: Restricted; legitimate-interest route in law but not yet open.
- **BO register**: Central Register of Effective Beneficiaries (RCBE) — https://rcbe.justica.gov.pt/
- **How to apply**: https://diariodarepublica.pt/dr/detalhe/decreto-lei/115-2025-942401303
- **Access detail**: DL 115/2025; regulations still required https://diariodarepublica.pt/dr/detalhe/decreto-lei/115-2025-942401303
- **Next FATF/FSRB assessment**: FATF; onsite 2028-06-01; plenary 2029-02-01
- **Sources**: https://diariodarepublica.pt/dr/detalhe/decreto-lei/115-2025-942401303

### Republic of Korea (KR) — verified 2026-11-10

**Access**: No central BO register.
- **How to apply**: https://fsc.go.kr/eng/pr010101/86222
- **Pending changes**: KoFIU's 2026 AML/CFT policy agenda (5 Feb 2026) plans a database of the ultimate beneficial owners of corporate entities, built first from financial institutions' suspicious transaction reports and used for cross-checking by authorities. It names no public access, no law and no date.
- **Company register**: Commercial register (상업등기), Supreme Court Internet Registry Office (대법원 인터넷등기소) — https://www.iros.go.kr/; public: Yes
- **Next FATF/FSRB assessment**: FATF / APG; onsite 2028-03-01
- **Notes**: No central beneficial ownership register. Beneficial owners (실제소유자) are identified only by financial institutions in customer due diligence, under the Act on Reporting and Using Specified Financial Transaction Information (특정금융정보법) art. 5-2. The CDD rule names a holder of 25% or more of voting shares, then the largest shareholder, then the representative. The commercial register (등기) lists officers, not shareholders. Listed companies and other disclosure filers publish their largest shareholder and related persons, 5% holders and executives in periodic reports on DART (Financial Supervisory Service). These are shareholders as filed, not beneficial owners. FATF follow-up report of Oct 2024: R.24 Partially compliant, R.25 Largely compliant. Open Ownership map: 'Planned' (Summit for Democracy commitment, 29 Mar 2023).
- **Sources**: https://fsc.go.kr/eng/pr010101/86222 · https://www.fatf-gafi.org/en/publications/Mutualevaluations/Korea-fur-2024.html · https://www.openownership.org/en/map/country/republic-of-korea/ · https://opendart.fss.or.kr/ · https://www.iros.go.kr/

### Romania (RO) — verified 2026-09-18

**Access**: Restricted; legitimate-interest route in law but not yet open.
- **BO register**: Registrul Beneficiarilor Reali (RBR) — https://www.onrc.ro/index.php/en/information-rbo
- **Access detail**: On 23 May 2025, Romania gazetted changes to introduce legitimate interest access by transposing article 74 of 6AMLD. But haven’t seen regulations/access procedure yet – and BO register page seems to be offline as of March 2026.
- **Next FATF/FSRB assessment**: MONEYVAL (4th round); onsite 2031-04-01; plenary 2031-12-01

### Serbia (RS) — verified 2026-09-18

**Access**: Not yet recorded.
- **BO register**: Central Records of Beneficial Owners — https://www.apr.gov.rs/registers/the-central-records-of-beneficial-owners.1846.html
- **Notes**: Not on the FATF assessments calendar as of 18 Sept 2026

### Singapore (SG) — verified 2026-09-18

**Access**: Authorities and obliged entities only.
- **Notes**: Not on the FATF assessments calendar as of 18 Sept 2026

### Slovakia (SK) — verified 2026-10-01

**Access**: Legitimate-interest access.
- **BO register**: Register of legal entities, entrepreneurs and public authorities (RPO) — https://rpo.statistics.sk/rpo/#login
- **Access detail**: 6AMLD LIA introduced from 2026-07-10 https://eur-lex.europa.eu/legal-content/SK/TXT/PDF/?uri=CELEX:72018L0843SVK_202604009
- **Next FATF/FSRB assessment**: MONEYVAL; onsite 2028-10-01; plenary 2029-05-01

### Slovenia (SI) — verified 2026-09-18

**Access**: Legitimate-interest access.
- **BO register**: Register of Beneficial Owners (RDL) — https://www.ajpes.si/eRDL/Iskalnik
- **How to apply**: https://www.uradni-list.si/glasilo-uradni-list-rs/vsebina/2025-01-2269
- **Access detail**: From 9th August 2025, access to RDL was shifting to use a LIA test following July amendments to Slovenia’s AML law (see gazette / government website)
- **Next FATF/FSRB assessment**: MONEYVAL; onsite 2025-09-29; plenary 2026-05-01
- **Sources**: https://www.uradni-list.si/glasilo-uradni-list-rs/vsebina/2025-01-2269

### Spain (ES) — verified 2026-09-18

**Access**: Restricted; legitimate-interest route in law but not yet open.
- **BO register**: Registro de Titularidades Reales (RETIR) — https://www.registradores.org/registro-de-titularidades-reales
- **Next FATF/FSRB assessment**: FATF; onsite 2027-02-01; plenary 2027-10-01

### St Helena (SH) — unverified draft

**Access**: Public.
- **How to apply**: https://drive.proton.me/urls/WEC6VHS4DW#GmckfehJ8yk2
- **Access detail**: Public register published via a shared Proton Drive folder.
- **Notes**: Not on the FATF assessments calendar (assessed within the UK)
- **Sources**: https://drive.proton.me/urls/WEC6VHS4DW#GmckfehJ8yk2

### Sweden (SE) — verified 2026-10-14

**Access**: Restricted; legitimate-interest route in law but not yet open.
- **BO register**: Register of Real Principals — https://www.bolagsverket.se/sjalvservice/etjanster/verklighuvudman/sokverklighuvudman.3084.html
- **How to apply**: https://www.riksdagen.se/sv/dokument-och-lagar/dokument/betankande/utlamnande-av-uppgifter-ur-registret-over-verkliga_hd01fiu35/
- **Access detail**: LIA in force 1 Jul 2026; Bolagsverket says LIA search access not before autumn 2026
- **Next FATF/FSRB assessment**: FATF; onsite 2027-11-01; plenary 2028-06-01
- **Sources**: https://www.riksdagen.se/sv/dokument-och-lagar/dokument/betankande/utlamnande-av-uppgifter-ur-registret-over-verkliga_hd01fiu35/ · https://bolagsverket.se/apierochoppnadata/hamtaforetagsinformation/hamtainformationomverklighuvudman.6009.html

### Switzerland (CH) — verified 2026-10-08

**Access**: Authorities and obliged entities only.
- **BO register**: Swiss Transparency Register — https://www.transpareg.admin.ch/en
- **How to apply**: https://www.fedlex.admin.ch/eli/fga/2025/2900/de
- **Next FATF/FSRB assessment**: FATF; onsite 2027-06-01; plenary 2028-02-01
- **Notes**: Federal transparency register (TJPG) legislation adopted; register launched on 1 October 2026 https://www.transpareg.admin.ch/en
- **Sources**: https://www.fedlex.admin.ch/eli/fga/2025/2900/de

### Taiwan (TW) — verified 2026-10-30

**Access**: Authorities and obliged entities only.
- **Company register**: Commerce Industrial Services Portal (GCIS) — https://gcis.nat.gov.tw/mainNew/English/index.jsp; public: Yes

### Turks and Caicos Islands (TC) — unverified draft

**Access**: Legitimate-interest access.
- **BO register**: Turks and Caicos Islands beneficial ownership register — https://kregistry.tcifsc.tc/kregistry/
- **How to apply**: https://kregistry.tcifsc.tc/kregistry/
- **Access detail**: LIA via kregistry, $250 per request; launched mid-2025.
- **Next FATF/FSRB assessment**: CFATF; onsite 2028-03-01; plenary 2028-11-01
- **Sources**: https://kregistry.tcifsc.tc/kregistry/

### Ukraine (UA) — verified 2026-09-18

**Access**: Public.
- **BO register**: Unified State Registry — https://usr.minjust.gov.ua/
- **How to apply**: https://data.gov.ua/dataset/a1799820-195b-4982-8141-6e84f58103e7
- **Notes**: MONEYVAL 5th round: date TBD on the FATF calendar
- **Sources**: https://data.gov.ua/dataset/a1799820-195b-4982-8141-6e84f58103e7

### United Kingdom (GB) — verified 2026-09-18

**Access**: Public.
- **BO register**: Register of People with Significant Control and Register of Overseas Entities — https://find-and-update.company-information.service.gov.uk/
- **How to apply**: https://www.gov.uk/guidance/people-with-significant-control-pscs
- **Access detail**: PSC register public (bands 25/50/75%); Register of Overseas Entities also public. ECCTA identity verification mandatory rollout from 18 Nov 2025.
- **Discrepancy route (BO register)**: https://find-and-update.company-information.service.gov.uk/report-a-discrepancy/discrepancy-category
- **Next FATF/FSRB assessment**: FATF; onsite 2027-06-01; plenary 2028-02-01
- **Sources**: https://www.gov.uk/guidance/people-with-significant-control-pscs

### United States (US) — verified 2026-09-18

**Access**: No central BO register.
- **Access detail**: FinCEN domestic BO reporting ended ~Aug 2026; SEC 13D 5% disclosure for listed issuers only.
- **Next FATF/FSRB assessment**: FATF / APG / CFATF; onsite 2026-02-01; plenary 2026-10-01

### Uruguay (UY) — verified 2026-11-23

**Access**: Authorities and obliged entities only.
- **How to apply**: https://www.cefilat.org/informes/the-invisible-owners
- **Next FATF/FSRB assessment**: GAFILAT
- **Notes**: Draft from the CEFILAT/FTC report (Aug 2026). Threshold 15% (Art. 1). Law 19,484/2017; Decree 166/017 amended by Decree 272/022. Held by the BCU under confidentiality (Art. 23). Covers 12 resident entity types incl. fideicomisos and investment funds, plus non-residents with a permanent establishment or assets over 2.5M UI. Oversight by the Auditoría Interna de la Nación; notarial certification required. 368 ISSUED LEIs (RA000690, RUT).
- **Sources**: https://www.cefilat.org/informes/the-invisible-owners

