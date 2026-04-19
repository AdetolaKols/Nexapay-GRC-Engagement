# NexaPay Financial Services Ltd. - GRC Engagement

> Frameworks: ISO/IEC 27001:2022 · PCI-DSS v4.0 · NIST CSF 2.0  
> Status: 🟡 In Progress

---

##  Executive Brief

**NexaPay Financial Services Ltd.** is a UK-headquartered international Fintech with 1,200+ employees across offices in London, Amsterdam, and Singapore. The company processes card payments for over 4 million customers and operates a complex hybrid IT estate spanning on-premise data centres, AWS cloud infrastructure, and third-party SaaS platforms.

In Q1 2025, NexaPay's Qualified Security Assessor (QSA) issued a **PCI-DSS v4.0 audit report with 14 non-conformities**, including critical gaps in access control, encryption key management, and vulnerability management processes. Simultaneously, the Board of Directors approved a strategic mandate to achieve **ISO/IEC 27001:2022 certification within 12 months** to strengthen market position ahead of a planned Series C funding round.

The CISO engaged an **external GRC Consultant** to conduct a full assessment of the current GRC posture, identify and prioritise risks, and build the ISMS programme from the ground up.

This repository documents the full engagement, from initial scoping through to a remediation roadmap and certification readiness evidence pack.

---

## Engagement Overview

| Item | Detail |
|---|---|
| **Consultant Role** | External GRC Consultant |
| **Client** | NexaPay Financial Services Ltd. |
| **Engagement Trigger** | PCI-DSS v4.0 audit failure · ISO 27001:2022 certification mandate |
| **Frameworks** | ISO/IEC 27001:2022 · PCI-DSS v4.0 · NIST CSF 2.0 |
| **Methodology** | ISO/IEC 27005 risk management, aligned to ISO 27001:2022 Annex A |
| **Engagement Duration** | 12 weeks |

---

## Engagement Objectives

1. **Identify** all information security risks, vulnerabilities, and threats across NexaPay's IT estate
2. **Assess** current ISMS maturity and produce a Statement of Applicability (SOA) gap analysis
3. **Build** a structured Risk Register aligned to ISO 27001:2022 and NIST CSF 2.0
4. **Produce** a Configuration Management Database (CMDB) with classified asset inventory
5. **Deliver** an executive remediation roadmap addressing PCI-DSS findings and ISO 27001 gaps

---

##  Repository Structure

```
nexapay-grc/
│
├── README.md                          ← Consultant brief & engagement overview
│
├── 01-Risk-and-Vulnerabilities/
│   ├── vulnerability-scan-report.xlsx ← CVE findings mapped to assets and business impact
│   ├── threat-register.md             ← Threat catalogue (internal, external, environmental)
│   └── risk-identification-methodology.md
│
├── 02-ISMS-and-SOA/
│   ├── isms-gap-assessment.md         ← Current vs required ISMS maturity
│   ├── statement-of-applicability.xlsx← ISO 27001:2022 Annex A control applicability
│   └── policies/
│       ├── cryptographic-policy.md
│       ├── remote-working-policy.md
│       ├── asset-owner-roles.md
│       └── isms-roles-responsibilities.md
│
├── 03-Risk-Register/
│   ├── risk-register.xlsx             ← Full risk register with scoring and treatment plans
│   └── risk-scoring-methodology.md    ← Likelihood × Impact matrix and risk appetite
│
├── 04-CMDB/
│   ├── cmdb-asset-inventory.xlsx      ← Asset inventory with classification and owners
│   └── asset-classification-policy.md
│
└── 05-Evidence-and-Reporting/
    ├── executive-summary.md           ← Board-ready summary of findings and recommendations
    └── remediation-roadmap.xlsx       ← Prioritised action plan with owners and timelines
```

---

##  Client Profile: NexaPay Financial Services Ltd.

| Attribute | Detail |
|---|---|
| **Sector** | Financial Services / Fintech |
| **Headquarters** | London, United Kingdom |
| **Offices** | London · Amsterdam · Singapore |
| **Employees** | ~1,200 |
| **Customers** | 4 million+ (card payment processing) |
| **IT Environment** | Hybrid — on-premise DC (London), AWS (eu-west-1, ap-southeast-1), M365, Salesforce, Workday |
| **Annual Revenue** | £180M |
| **Regulatory Context** | FCA regulated · GDPR in-scope · PCI-DSS Level 1 merchant |

### Key Stakeholders

| Name | Title | GRC Responsibility |
|---|---|---|
| Lucca Skyes | Chief Information Security Officer (CISO) | ISMS Owner · Engagement Sponsor |
| James Hartley | Chief Risk Officer (CRO) | Risk Appetite · Risk Register Signoff |
| Priya Nair | Head of Compliance | PCI-DSS · Regulatory Liaison |
| Tom Vasquez | IT Director | Asset Owner · CMDB · Vulnerability Management |

---

## Engagement Phases

### Phase 1 - Assess (Weeks 1–4)
- Kickoff with CISO and key stakeholders
- Vulnerability scan review and CVE triage
- ISMS maturity gap assessment against ISO 27001:2022
- Threat and risk identification workshops
- Asset inventory review and CMDB baseline

### Phase 2 - Document (Weeks 5–8)
- Risk Register population and scoring
- Statement of Applicability (SOA) completion
- Policy gap analysis and policy drafting
- CMDB formalisation and asset classification

### Phase 3 - Remediate & Report (Weeks 9–12)
- Remediation roadmap with prioritised actions
- Executive summary for Board presentation
- ISO 27001:2022 certification readiness evidence pack
- PCI-DSS finding remediation tracking

---

## Frameworks Applied

| Framework | Version | Application |
|---|---|---|
| ISO/IEC 27001 | 2022 | ISMS structure · Annex A controls · SOA |
| ISO/IEC 27005 | 2022 | Risk management methodology |
| PCI-DSS | v4.0 | Payment security controls · audit finding remediation |
| NIST CSF | 2.0 | Risk identification and control categorisation (Identify · Protect · Detect · Respond · Recover) |

---
