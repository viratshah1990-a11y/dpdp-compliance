# DPDP Breach Notification — India's Dual Reporting Requirements
> This guide is part of the [DPDP Compliance resource hub](../README.md) maintained by [ComplyZero](https://www.complyzero.com).
India is one of the few countries that requires breach reporting to **two separate government authorities** within different timeframes. This guide explains what to report, to whom, and by when.
---
## The Two Reporting Obligations
```
                    ┌─────────────────────┐
                    │   BREACH DETECTED    │
                    └──────────┬──────────┘
                               │
                    ┌──────────┴──────────┐
                    │                     │
                    ▼                     ▼
          ┌─────────────────┐   ┌─────────────────┐
          │    CERT-In       │   │      DPBI        │
          │    6 HOURS       │   │    72 HOURS      │
          │                 │   │                 │
          │  All cyber      │   │  Personal data  │
          │  security       │   │  breaches only  │
          │  incidents      │   │                 │
          └─────────────────┘   └─────────────────┘
                    │                     │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │  NOTIFY AFFECTED     │
                    │  DATA PRINCIPALS     │
                    │  Without             │
                    │  unreasonable delay  │
                    └─────────────────────┘
```
### Why Two Authorities?
India's dual-reporting system stems from two separate legal frameworks:
1. **CERT-In Directions (April 2022)** — Under the IT Act, the Indian Computer Emergency Response Team requires notification of all cybersecurity incidents within **6 hours**. This applies to any entity with IT infrastructure, regardless of whether personal data is involved.
2. **DPDP Act Section 8(6) + Rule 7** — The Data Protection Board of India requires notification of personal data breaches within **72 hours**. This applies specifically to Data Fiduciaries and specifically to breaches involving personal data.
If a cybersecurity incident involves personal data (which most breach scenarios do), **both obligations are triggered simultaneously.**
---
## Obligation 1: CERT-In — Within 6 Hours
| | |
|---|---|
| **Authority** | Indian Computer Emergency Response Team (under MeitY) |
| **Legal basis** | CERT-In Directions dated April 28, 2022 |
| **Deadline** | **6 hours** from detection/awareness of the incident |
| **Applies to** | Any entity with IT infrastructure in India |
| **Scope** | All cybersecurity incidents — not limited to personal data |
### What Triggers CERT-In Reporting
Any "cyber security incident," including:
- Unauthorised access to systems or data
- Data breaches and data leaks
- Ransomware attacks
- Malware deployment
- DDoS attacks
- Phishing attacks
- Website defacement
- Identity theft or spoofing
- Attacks on critical infrastructure
- Data loss
### What to Report to CERT-In
- Nature and classification of the incident
- Date and time of occurrence and detection
- Systems, networks, and data affected
- Scope and severity assessment
- Root cause (initial assessment)
- Remediation actions taken or planned
### How to Report
- Email: incident@cert-in.org.in
- Portal: [cert-in.org.in](https://www.cert-in.org.in/)
---
## Obligation 2: DPBI — Within 72 Hours
| | |
|---|---|
| **Authority** | Data Protection Board of India |
| **Legal basis** | DPDP Act 2023, Section 8(6) + DPDP Rules 2025, Rule 7 |
| **Deadline** | **72 hours** from becoming aware of the breach |
| **Applies to** | Data Fiduciaries only |
| **Scope** | Personal data breaches — unauthorised processing, disclosure, acquisition, sharing, use, alteration, destruction, or loss of access |
### What to Report to DPBI
- Nature of the personal data breach
- Approximate number of Data Principals affected
- Categories of personal data involved
- Likely consequences of the breach
- Measures taken or proposed to address the breach
- Measures taken to mitigate adverse effects on individuals
- Contact details of DPO or designated point of contact
### Penalty for Failure
Up to **₹200 crore** for non-notification.
---
## Obligation 3: Notify Affected Individuals
| | |
|---|---|
| **Legal basis** | DPDP Act 2023, Section 8(6) |
| **Deadline** | "Without unreasonable delay" |
| **Applies to** | Every personal data breach (not just "high risk," unlike GDPR) |
### What to Communicate
- Description of the breach in plain, clear language
- What personal data was affected
- What the individual can do to protect themselves
- Steps the organisation is taking
- Contact details of DPO or point of contact
### How to Communicate
Via whatever contact channels are available: email, SMS, in-app notification, phone call, or written letter. Use the most reliable channel available for each affected Data Principal.
**ComplyZero note:** Unlike GDPR — which only requires individual notification when a breach poses "high risk to the rights and freedoms" of a Data Subject — DPDP requires notification for **all personal data breaches**, regardless of risk level. This is a significantly higher bar.
---
## CERT-In vs DPBI: Side-by-Side Comparison
| Dimension | CERT-In | DPBI |
|---|---|---|
| **Time limit** | **6 hours** | **72 hours** |
| **Legal basis** | IT Act / CERT-In Directions 2022 | DPDP Act 2023, Section 8(6) |
| **Scope** | All cybersecurity incidents | Personal data breaches only |
| **Who reports** | Any entity with IT infrastructure | Data Fiduciaries |
| **Focus** | Technical — systems, networks, attack vectors | Data-centric — individuals affected, data categories, impact |
| **Penalty** | Under IT Act provisions | Up to ₹200 crore under DPDP |
| **Alternative?** | No — both required | No — both required |
---
## Breach Response Timeline
### Phase 1: Immediate (0–6 hours)
- [ ] **Contain the breach** — isolate affected systems, revoke compromised access
- [ ] **Activate incident response team** — security, legal, DPO, communications
- [ ] **Report to CERT-In** within 6 hours
- [ ] **Begin documentation** — timestamps, actions taken, personnel involved
- [ ] Start **root cause analysis**
### Phase 2: Assessment and Notification (6–72 hours)
- [ ] **Assess scope** — what data was affected, how many individuals impacted
- [ ] **Classify the breach** — nature, categories of data, likely consequences
- [ ] **Report to DPBI** within 72 hours with full details
- [ ] **Notify affected Data Principals** without unreasonable delay
- [ ] **Preserve all evidence** — forensic images, logs, communications
### Phase 3: Recovery (72 hours – 30 days)
- [ ] **Patch vulnerabilities** and implement technical fixes
- [ ] **Complete forensic investigation**
- [ ] **Update DPBI** with additional findings if scope changes
- [ ] **Review and strengthen security safeguards** based on lessons learned
- [ ] Conduct **post-incident review** with all stakeholders
### Phase 4: Post-Incident (30+ days)
- [ ] **Retain all breach documentation** — incident records, response actions, outcomes
- [ ] **Update Incident Response Plan** based on findings
- [ ] **Conduct staff training** on revised procedures
- [ ] **Monitor for secondary attacks** or misuse of compromised data
---
## Penalties Reference
| Violation | Maximum Penalty |
|---|---|
| Failure to implement security safeguards (Section 8(5)) | **₹250 crore** |
| Failure to notify DPBI and individuals (Section 8(6)) | **₹200 crore** |
| Non-compliance with Board directions | **₹500 crore** (cumulative) |
The DPBI considers: nature and gravity of the breach, whether it was repeated, the type and sensitivity of data involved, gains/losses, and mitigation actions taken.
---
## Preparing for a Breach Before It Happens
The most effective breach response starts **before a breach occurs.** ComplyZero recommends every Data Fiduciary have these components in place:
| Component | Purpose |
|---|---|
| **Incident Response Plan** | Documented procedures for detection, containment, notification, and recovery |
| **Breach Notification Templates** | Pre-drafted templates for CERT-In, DPBI, and Data Principal communications — ready to customise |
| **Designated Response Team** | Named individuals with defined roles (security lead, legal counsel, DPO, communications) |
| **Detection and Monitoring** | Continuous monitoring, intrusion detection, and anomaly alerting systems |
| **Contact Registry** | Up-to-date contact details for CERT-In, DPBI, and all Data Principals |
| **Periodic Drills** | Tabletop exercises to test the response plan and identify gaps |
**ComplyZero note:** ComplyZero's platform includes pre-configured breach notification workflows with built-in templates for CERT-In reporting, DPBI notification, and Data Principal communication. This ensures your response meets both deadlines even under pressure. Learn more at www.complyzero.com.
---
## Learn More
For detailed guides on related compliance topics:
- [The 72-Hour Rule: CERT-In vs DPBI Explained](https://www.complyzero.com/blog/data-breach-notification-india)
- [DPDP Act 2023: Complete Guide](https://www.complyzero.com/blog/dpdp-act-2023-complete-guide)
- [DPDP Compliance Checklist](https://www.complyzero.com/blog/dpdp-compliance-checklist)
## Official Sources
- [DPDP Act 2023 — MeitY](https://www.meity.gov.in/data-protection-framework)
- [CERT-In Directions 2022](https://www.cert-in.org.in/Directions70B.jsp)
- [CERT-In Incident Reporting](https://www.cert-in.org.in/)
- [Data Protection Board of India](https://www.dpbi.gov.in/)
---
*This resource is maintained by [ComplyZero](https://www.complyzero.com) — www.complyzero.com — India's first self-serve DPDP compliance platform. Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).*
