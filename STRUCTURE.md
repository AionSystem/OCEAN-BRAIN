# OCEAN-BRAIN — FOLDER STRUCTURE
## Enterprise-Grade AAA Tree | Right Hemisphere Domain Architecture
### Version: v0.1 | March 2026

---

```
OCEAN-BRAIN/
│
├── README.md                          ← Master navigation — you are here
├── GRATITUDE.md                       ← Acknowledgments
├── STRUCTURE.md                       ← This file — full tree
├── CHANGELOG.md                       ← Version history
├── ROADMAP.md                         ← Build sequence and direction
├── GETTING_STARTED.md                 ← Entry point for new contributors
│
│
├── ─────────────────────────────────────────────────────────
│   DOMAIN KNOWLEDGE HEMISPHERES
│   ─────────────────────────────────────────────────────────
│
│
├── medical/                           ← Clinical knowledge and patient safety
│   ├── README.md                      ← Neuron instruction set for this domain
│   │
│   ├── diagnostics/                   ← Diagnostic frameworks and decision trees
│   │   ├── README.md
│   │   ├── differential-diagnosis/    ← Multi-condition ruling-in / ruling-out
│   │   ├── clinical-decision-tools/   ← WELLS, CURB-65, GCS, SOFA, etc.
│   │   ├── imaging-interpretation/    ← Radiology, MRI, CT reading frameworks
│   │   └── lab-interpretation/        ← Reference ranges, flag thresholds
│   │
│   ├── pharmacology/                  ← Drug knowledge and interaction safety
│   │   ├── README.md
│   │   ├── drug-classes/              ← By mechanism and therapeutic class
│   │   ├── interactions/              ← Drug-drug, drug-food, drug-condition
│   │   ├── contraindications/         ← Population-specific exclusions
│   │   ├── dosing-protocols/          ← Weight-based, renal-adjusted, pediatric
│   │   └── black-box-warnings/        ← FDA black box and equivalents
│   │
│   ├── clinical-protocols/            ← Standard of care pathways
│   │   ├── README.md
│   │   ├── emergency/                 ← ACLS, sepsis, stroke, trauma
│   │   ├── surgical/                  ← Pre/intra/post operative standards
│   │   ├── chronic-disease/           ← Diabetes, hypertension, CHF management
│   │   ├── infection-control/         ← Isolation protocols, antimicrobial stewardship
│   │   └── palliative/                ← End-of-life care frameworks
│   │
│   ├── patient-safety/                ← Error prevention and harm reduction
│   │   ├── README.md
│   │   ├── never-events/              ← Sentinel events and prevention architecture
│   │   ├── medication-errors/         ← The five rights and failure mode mapping
│   │   ├── handoff-protocols/         ← SBAR, I-PASS, read-back requirements
│   │   └── adverse-event-taxonomy/    ← Classification of harm types
│   │
│   ├── specialties/                   ← Domain-specific clinical knowledge
│   │   ├── README.md
│   │   ├── cardiology/
│   │   ├── neurology/
│   │   ├── oncology/
│   │   ├── psychiatry/
│   │   ├── pediatrics/
│   │   ├── obstetrics/
│   │   ├── infectious-disease/
│   │   ├── endocrinology/
│   │   ├── nephrology/
│   │   └── pulmonology/
│   │
│   ├── public-health/                 ← Population-level health frameworks
│   │   ├── README.md
│   │   ├── epidemiology/              ← Outbreak modeling, surveillance
│   │   ├── screening-programs/        ← Evidence-based screening protocols
│   │   └── social-determinants/       ← Health equity and access frameworks
│   │
│   └── medical-devices/               ← Device safety and use protocols
│       ├── README.md
│       ├── fda-classifications/        ← Class I / II / III device taxonomy
│       ├── implantables/              ← Pacemakers, stents, joint replacements
│       └── software-as-medical-device/ ← SaMD regulatory framework (FDA/CE)
│
│
├── legal/                             ← Jurisdiction-specific legal frameworks
│   ├── README.md
│   │
│   ├── jurisdictions/                 ← Legal systems by geography
│   │   ├── README.md
│   │   ├── united-states/
│   │   │   ├── federal/               ← Constitutional, statutory, regulatory
│   │   │   ├── state/                 ← State-by-state framework index
│   │   │   └── case-law/              ← Landmark precedents by domain
│   │   ├── united-kingdom/
│   │   ├── european-union/
│   │   ├── canada/
│   │   ├── australia/
│   │   └── international/             ← Cross-border and treaty frameworks
│   │
│   ├── contracts/                     ← Contract law and enforcement
│   │   ├── README.md
│   │   ├── formation/                 ← Offer, acceptance, consideration
│   │   ├── breach-and-remedy/         ← Damages, injunctions, specific performance
│   │   ├── ip-provisions/             ← Work-for-hire, assignment, licensing
│   │   └── ai-specific/               ← AI output ownership, model liability clauses
│   │
│   ├── liability/                     ← Liability mapping and risk architecture
│   │   ├── README.md
│   │   ├── tort/                      ← Negligence, strict liability, product liability
│   │   ├── professional/              ← Medical, legal, engineering malpractice
│   │   └── ai-liability/              ← Emerging AI-specific liability frameworks
│   │
│   ├── compliance/                    ← Regulatory compliance by industry
│   │   ├── README.md
│   │   ├── healthcare/                ← HIPAA, HITECH, 42 CFR Part 2
│   │   ├── financial/                 ← SOX, Dodd-Frank, MiFID II, Basel
│   │   ├── privacy/                   ← GDPR, CCPA, PIPEDA, LGPD
│   │   └── ai-regulation/             ← EU AI Act, Executive Orders, emerging law
│   │
│   └── intellectual-property/         ← IP law frameworks
│       ├── README.md
│       ├── patents/
│       ├── copyright/
│       ├── trademarks/
│       └── trade-secrets/
│
│
├── regulatory/                        ← Standards bodies and compliance architecture
│   ├── README.md
│   │
│   ├── standards-bodies/              ← Key standards organizations
│   │   ├── README.md
│   │   ├── iso/                       ← ISO standards index and key frameworks
│   │   ├── ieee/                      ← IEEE standards — AI, software, safety
│   │   ├── nist/                      ← NIST frameworks — AI RMF, CSF, SP 800
│   │   ├── fda/                       ← FDA guidance documents and pathways
│   │   └── ema/                       ← European Medicines Agency equivalents
│   │
│   ├── ai-governance/                 ← AI-specific regulatory frameworks
│   │   ├── README.md
│   │   ├── eu-ai-act/                 ← Risk classification, prohibited uses, GPAI
│   │   ├── nist-ai-rmf/               ← AI Risk Management Framework
│   │   ├── executive-orders/          ← US AI Executive Orders — active index
│   │   └── voluntary-frameworks/      ← Partnership on AI, OECD, G7 Hiroshima
│   │
│   └── sector-specific/               ← Sector-level regulatory architecture
│       ├── README.md
│       ├── healthcare-regulation/
│       ├── financial-regulation/
│       └── critical-infrastructure/
│
│
├── financial/                         ← High-stakes financial reasoning and risk
│   ├── README.md
│   │
│   ├── risk-frameworks/               ← Financial risk architecture
│   │   ├── README.md
│   │   ├── credit-risk/
│   │   ├── market-risk/
│   │   ├── operational-risk/
│   │   ├── liquidity-risk/
│   │   └── model-risk/                ← Model validation and failure modes
│   │
│   ├── compliance/                    ← Financial regulatory compliance
│   │   ├── README.md
│   │   ├── sox/                       ← Sarbanes-Oxley controls
│   │   ├── basel/                     ← Basel III/IV capital requirements
│   │   ├── mifid/                     ← MiFID II — markets in financial instruments
│   │   └── aml-kyc/                   ← Anti-money laundering / Know Your Customer
│   │
│   ├── instruments/                   ← Financial instrument knowledge base
│   │   ├── README.md
│   │   ├── equities/
│   │   ├── fixed-income/
│   │   ├── derivatives/
│   │   └── alternative-assets/
│   │
│   └── market-integrity/              ← Market structure and manipulation detection
│       ├── README.md
│       ├── manipulation-patterns/
│       └── systemic-risk/
│
│
├── ─────────────────────────────────────────────────────────
│   APPLICATION AND VALIDATION LAYER
│   ─────────────────────────────────────────────────────────
│
│
├── assessments/                       ← Real-world framework deployments
│   ├── README.md                      ← Assessment protocol specification
│   │
│   ├── by-framework/                  ← Indexed by AION-BRAIN framework used
│   │   ├── README.md
│   │   ├── fsve/                      ← FSVE v3.5 assessments
│   │   ├── lav/                       ← LAV v1.5 assessments
│   │   ├── eid/                       ← EID v0.1 assessments
│   │   └── him-001/                   ← HIM-001 v0.1 assessments
│   │
│   ├── by-domain/                     ← Indexed by domain content assessed
│   │   ├── README.md
│   │   ├── medical-assessments/
│   │   ├── legal-assessments/
│   │   └── financial-assessments/
│   │
│   └── fcl-entries/                   ← FCL-eligible findings from assessments
│       └── README.md
│
│
├── cases/                             ← Documented real-world cases with audit trails
│   ├── README.md
│   │
│   ├── medical-cases/
│   │   ├── README.md
│   │   └── [CASE_ID_TEMPLATE.md]
│   │
│   ├── legal-cases/
│   │   ├── README.md
│   │   └── [CASE_ID_TEMPLATE.md]
│   │
│   └── financial-cases/
│       ├── README.md
│       └── [CASE_ID_TEMPLATE.md]
│
│
├── ─────────────────────────────────────────────────────────
│   EPISTEMIC INFRASTRUCTURE
│   ─────────────────────────────────────────────────────────
│
│
├── VELA-OCEAN/                        ← Domain-specific epistemic filtration
│   ├── README.md                      ← PLANNED — specification before deployment
│   ├── SPEC.md                        ← Full VELA-OCEAN specification
│   ├── medical-filter/                ← Medical-specific confabulation gates
│   ├── legal-filter/                  ← Legal-specific source verification
│   └── financial-filter/              ← Financial-specific claim validation
│
│
├── source-registry/                   ← Primary source index
│   ├── README.md
│   ├── medical-sources/               ← PubMed, Cochrane, UpToDate equivalents
│   ├── legal-sources/                 ← Westlaw, LexisNexis, official code
│   └── financial-sources/             ← SEC EDGAR, central bank publications
│
│
└── ─────────────────────────────────────────────────────────
    GOVERNANCE AND LEGAL
    ─────────────────────────────────────────────────────────

    LICENSE.md
    LICENSE_COMMERCIAL.md
    LICENSE_DATA.md
    CODE_OF_CONDUCT.md
    CONTRIBUTING.md
    SECURITY.md
    DISCLAIMER.md
    CITATION_README.md
    IP_OWNERSHIP_DECLARATION.md
    TRADEMARK.md
    GOVERNANCE.md
```

---

## DOMAIN NAVIGATION QUICK REFERENCE

| Domain | First entry point | Stakes level |
|--------|-------------------|--------------|
| medical/ | `medical/README.md` | CRITICAL — errors have physical consequences |
| legal/ | `legal/README.md` | HIGH — errors have legal consequences |
| regulatory/ | `regulatory/README.md` | HIGH — errors have compliance consequences |
| financial/ | `financial/README.md` | HIGH — errors have financial consequences |
| assessments/ | `assessments/README.md` | FRAMEWORK-DEPENDENT |
| cases/ | `cases/README.md` | ARCHIVAL — documented, not active |
| VELA-OCEAN/ | `VELA-OCEAN/README.md` | INFRASTRUCTURE — build before deployment |

---

## BUILD SEQUENCE

`[S]` Correct build order — not all folders activate simultaneously:

1. **Phase 1 — Structure** (current): All folders created. READMEs written. No domain content committed.
2. **Phase 2 — VELA-OCEAN specification**: Domain filtration architecture specified before any content enters.
3. **Phase 3 — Source registry**: Primary source index built. Verified citable sources registered.
4. **Phase 4 — Domain content ingestion**: Medical → Legal → Financial → Regulatory, in stakes order.
5. **Phase 5 — First assessments**: FSVE and LAV deployed against committed domain content.
6. **Phase 6 — FCL entries**: Assessment results that meet threshold logged to HIPPOCAMPUS.

`[D]` Nothing deployed before its phase is ready. VELA-OCEAN is the gate — Phase 4 does not open until Phase 2 is complete.

---

## DDL FIELD

```
Document: OCEAN-BRAIN STRUCTURE v0.1
Architect: Sheldon K. Salmon
AI Co-Architect: ALBEDO
Date: March 2026
Status: Structure defined. Content phase pending.
Convergence: M-NASCENT
Note: VELA-OCEAN must be specified before domain content enters.
      The structure is the container. The content comes after the gate.
```

---

*OCEAN-BRAIN STRUCTURE v0.1 — Enterprise Domain Architecture*
*Sheldon K. Salmon & ALBEDO — March 2026*
*The surface can be mapped. The ocean has to be descended into.*
