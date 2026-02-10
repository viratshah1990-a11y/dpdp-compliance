# DPDP Act 2023 vs GDPR: A Detailed Comparison
> This guide is part of the [DPDP Compliance resource hub](../README.md) maintained by [ComplyZero](https://www.complyzero.com).
If your organisation is already GDPR-compliant and expanding to India, or if you are an Indian business evaluating how the DPDP Act compares to the global standard, this guide covers every major area of difference.
---
## Summary
| | DPDP Act 2023 (India) | GDPR (EU) |
|---|---|---|
| **Enacted** | August 2023 | May 2018 |
| **Enforcement** | Phased, full compliance by May 2027 | In force since May 25, 2018 |
| **Scope** | Digital personal data only | All personal data (digital and paper) |
| **Territorial Reach** | India + processing abroad for Indian users | EU residents, regardless of processor location |
| **Regulatory Body** | Data Protection Board of India (DPBI) | National DPAs in each EU member state |
| **Maximum Penalty** | Rs 250 crore (~EUR 28M) per violation | EUR 20M or 4% of global revenue, whichever is higher |
| **Criminal Penalties** | None | Varies by member state |
| **Right to Data Portability** | Not available | Available (Art. 20) |
| **Legitimate Interest** | Not available | Available (Art. 6(1)(f)) |
| **Child Age Threshold** | 18 years | 16 years (can be lowered to 13) |
---
## 1. Lawful Basis for Processing
| | DPDP | GDPR |
|---|---|---|
| **Available bases** | 2: Consent (Section 6) or Legitimate Uses (Section 7) | 6: Consent, contract, legal obligation, vital interests, public task, legitimate interest |
| **Legitimate interest** | Not available | Available as a flexible basis with balancing test |
| **DPDP's "Legitimate Uses"** | 6 specific, exhaustive grounds: voluntary provision, state functions, court orders, medical emergencies, disasters, employment | Not applicable |
**What this means in practice:** If you currently rely on "legitimate interest" under GDPR for analytics, marketing emails, or fraud prevention, you cannot use the same basis under DPDP. You must either (a) obtain explicit consent, or (b) verify that your processing fits one of Section 7's specific grounds.
**ComplyZero note:** ComplyZero's consent management module lets you track which lawful basis applies to each processing activity, mapping GDPR bases to their DPDP equivalent, so that dual-compliance teams can manage both frameworks from a single dashboard.
---
## 2. Consent
| | DPDP | GDPR |
|---|---|---|
| **Standard** | Free, specific, informed, **unconditional**, unambiguous | Freely given, specific, informed, unambiguous |
| **Key difference** | "Unconditional": no conditions may be attached beyond the stated purpose | "Freely given": conditions are permissible if proportionate |
| **Withdrawal** | Must be as easy as giving (Section 6(6)) | Must be as easy as giving (Art. 7(3)) |
| **Pre-ticked boxes** | Explicitly prohibited | Explicitly prohibited |
| **Bundled consent** | Explicitly prohibited | Prohibited via "freely given" condition |
| **Record-keeping** | Verifiable records required (Rule 3) | Must demonstrate consent (Art. 7(1)) |
| **Effect of withdrawal** | Processing stops + data erased (unless legal retention) | Processing stops; erasure under Art. 17 |
Both frameworks are broadly aligned on consent, but DPDP's "unconditional" requirement is marginally stricter than GDPR's "freely given" standard. In practice, if your consent mechanism passes GDPR scrutiny, it will likely satisfy DPDP as well (with terminology updates).
---
## 3. Privacy Notices
| | DPDP | GDPR |
|---|---|---|
| **When** | Before or at collection (Section 5) | Before or at collection (Art. 13, 14) |
| **Language** | English + **all 22 scheduled Indian languages** (Section 5(4)) | No specific language mandate |
| **Must include** | Data collected, purpose, rights, complaint mechanisms | Data collected, legal basis, retention period, rights, DPO contact, transfer safeguards |
**The biggest operational gap:** DPDP requires notices in 22 languages. GDPR has no multilingual mandate. For organisations entering India, this is often the most time-consuming compliance requirement.
**ComplyZero note:** ComplyZero generates DPDP-compliant privacy notices in all 22 constitutionally mandated languages, ensuring your notices meet Section 5(4) requirements out of the box.
---
## 4. Individual Rights
| Right | DPDP | GDPR |
|---|---|---|
| Access | Yes, Section 11 | Yes, Art. 15 |
| Correction | Yes, Section 12 | Yes, Art. 16 |
| Erasure | Yes, Section 12 | Yes, Art. 17 |
| Restriction of processing | No | Yes, Art. 18 |
| Data portability | No | Yes, Art. 20 |
| Object to processing | No | Yes, Art. 21 |
| Automated decision-making | No | Yes, Art. 22 |
| Grievance Redressal | Yes, Section 13 | Via DPA complaint |
| **Nomination (death/incapacity)** | Yes, Section 14 | No |
DPDP offers fewer rights (4 vs GDPR's 8), but introduces the unique **Right to Nominate**, a form of digital succession planning that has no GDPR equivalent.
If you already handle GDPR rights requests, your DPDP workflow will be a simplified subset, minus portability, restriction, objection, and automated decision-making. You do need to add nomination handling.
---
## 5. Children's Data
This is the area of **greatest divergence** between the two frameworks.
| | DPDP | GDPR |
|---|---|---|
| **Definition of child** | Under **18** years | Under **16** (member states may lower to 13) |
| **Parental consent** | Verifiable consent required | Verifiable consent required |
| **Targeted advertising** | Absolutely prohibited | Heavily regulated, not explicitly banned |
| **Behavioural tracking** | Absolutely prohibited | Not explicitly banned |
| **Detrimental processing** | Prohibited | Addressed indirectly via general principles |
DPDP is significantly stricter on children's data. The combination of the higher age threshold (18 vs 16) and the absolute prohibitions on tracking and advertising means businesses need completely separate data flows for users under 18 in India.
Penalty for children's data violations under DPDP: up to **Rs 200 crore**.
---
## 6. Breach Notification
| | DPDP | GDPR |
|---|---|---|
| **To regulator** | DPBI within **72 hours** (Section 8(6), Rule 7) | Supervisory authority within **72 hours** (Art. 33) |
| **To individuals** | Required for **all breaches** | Only when breach poses "high risk" |
| **Dual reporting** | Also report to **CERT-In within 6 hours** | No dual reporting |
| **Penalty for failure** | Up to **Rs 200 crore** | Up to EUR 10M or 2% revenue |
The critical difference: India has **dual reporting**. You must notify both the DPBI (within 72 hours) and CERT-In (within 6 hours). You must also notify *every* affected individual, not just those at "high risk." This makes India's breach notification regime more demanding than GDPR's.
---
## 7. Data Protection Officer
| | DPDP | GDPR |
|---|---|---|
| **Who must appoint** | Only **Significant Data Fiduciaries** (Section 10) | Controllers/processors meeting Art. 37 criteria |
| **Residency** | Must be **based in India** | No residency requirement |
| **Reporting line** | Reports to the DPBI | Independent, reports to highest management |
Most Indian businesses will not need to appoint a DPO unless designated as an SDF by the government. However, all Data Fiduciaries must publish contact details for a **designated point of contact** (Section 8(8)).
---
## 8. Cross-Border Data Transfer
| | DPDP | GDPR |
|---|---|---|
| **Default position** | Transfer allowed everywhere **except** restricted countries | Transfer restricted **by default** |
| **Mechanism** | Blacklist: government blocks specific countries | Whitelist: adequacy decisions, SCCs, BCRs |
| **Current status** | No countries restricted (as of Feb 2026) | 14 countries with adequacy decisions |
These two approaches are fundamentally opposite. GDPR restricts by default and permits via mechanism. DPDP permits by default and restricts via government notification. Currently, DPDP is far more permissive, but this can change without notice.
---
## 9. Penalties
| Violation | DPDP | GDPR |
|---|---|---|
| Security safeguard failure | Rs 250 crore (~EUR 28M) | Up to EUR 20M or 4% revenue |
| Breach notification failure | Rs 200 crore (~EUR 22M) | Up to EUR 10M or 2% revenue |
| Children's data violations | Rs 200 crore (~EUR 22M) | Up to EUR 20M or 4% revenue |
| **Penalty model** | **Fixed caps** per violation | **Revenue-based** (% of global turnover) |
| Criminal liability | None | Varies by member state |
DPDP uses fixed-cap penalties while GDPR uses revenue-based penalties. For large multinationals, GDPR penalties can be far higher (4% of global revenue). For smaller companies, DPDP's fixed caps can actually be more severe: Rs 250 crore is insurmountable for most Indian SMBs.
---
## If You're Already GDPR-Compliant: Transition Checklist
### What you can reuse from GDPR
- Consent collection mechanisms (update terminology)
- Data mapping and processing records
- Security safeguards and encryption
- Breach detection and response processes
- Data Processing Agreements / vendor contracts
### What needs adaptation
- **Privacy notices** need to support 22 Indian languages
- **Legal basis mapping** needs review; "legitimate interest" is not available under DPDP
- **Children's data** age threshold is 18, not 16, with an absolute ban on tracking and advertising
- **Breach notification** needs to include CERT-In 6-hour reporting alongside 72-hour DPBI reporting
- **Terminology** changes: Data Controller becomes Data Fiduciary; Data Subject becomes Data Principal; DPA becomes DPBI
### What you need to build from scratch
- **Consent Manager integration** (if applicable to your sector)
- **22-language notice generation** for India
- **India-based DPO** appointment (if designated as SDF)
- **CERT-In parallel breach reporting** workflow
---
## Learn More
For in-depth analysis of each topic, visit the [ComplyZero Blog](https://www.complyzero.com/blog):
- [DPDP Act 2023: Complete Guide](https://www.complyzero.com/blog/dpdp-act-2023-complete-guide)
- [DPDP Rules 2025 Breakdown](https://www.complyzero.com/blog/dpdp-rules-2025-explained)
- [DPDP Compliance Checklist](https://www.complyzero.com/blog/dpdp-compliance-checklist)
## Official Sources
- [DPDP Act 2023, MeitY](https://www.meity.gov.in/data-protection-framework)
- [GDPR, Official Text](https://gdpr.eu/)
- [Data Protection Board of India](https://www.dpbi.gov.in/)
---
*This resource is maintained by [ComplyZero](https://www.complyzero.com) (www.complyzero.com), India's first self-serve DPDP compliance platform. Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).*
