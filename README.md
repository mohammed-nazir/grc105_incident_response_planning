# GRC105 Incident Response Planning Assignment

**Student:** Mohammed Nazir  
**Course:** GRC105 — Incident Management and Business Continuity  
**Case study:** Suspected ransomware incident at Northbridge Skills Institute

## Overview

This repository packages my GRC105 Incident Response Planning assignment as a professional, review-friendly project. The scenario evaluates a suspected ransomware incident affecting a finance workstation, shared file services, backups, identity activity, and the learning portal.

The response is deliberately evidence-led: scenario observations are separated from hypotheses, proposed evidence collection is not presented as completed forensic work, and recovery is gated on clean validation rather than the examination deadline.

## Assignment coverage

- **Task 1 — Incident classification and initial assessment:** evidence-linked timeline, severity, CIA impact, priorities, and investigation questions.
- **Task 2 — Incident response plan and responsibilities:** policy outline, CSIRT roles, RACI matrix, and readiness improvements.
- **Task 3 — Response playbook and evidence preservation:** first-hour and first-24-hour actions, evidence register, containment trade-offs, eradication, and recovery criteria.
- **Task 4 — Communication and escalation:** stakeholder matrix, executive briefing, learner notice, and notification considerations.
- **Task 5 — Tabletop exercise:** injects, measurable success criteria, simulated decisions, and corrective actions.
- **Task 6 — Case study reflection:** healthcare ransomware lessons and their application to Northbridge.

## Key response principles

1. Treat the event as a **Critical suspected ransomware incident** while preserving uncertainty about malware family, attacker identity, and data theft.
2. Prioritise containment of active encryption and lateral movement while preserving evidence where feasible.
3. Protect backup infrastructure and privileged identities before restoration.
4. Use out-of-band communications while corporate email trust is uncertain.
5. Never restore an unverified backup simply to meet the 11:00 examination deadline.
6. Restore services only after isolated testing, security validation, functional acceptance, and documented approval.

## Repository structure

```text
.
├── README.md
├── LICENSE
├── CITATION.cff
├── SECURITY.md
├── CONTRIBUTING.md
├── .gitignore
├── docs/
│   ├── GRC105_IRP_Assignment_StudentID.docx
│   └── assignment-overview.md
├── templates/
│   ├── evidence-register.csv
│   └── incident-decision-log.csv
└── assets/
    └── .gitkeep
```

## Academic and evidence integrity

This is an academic incident-response plan based on a fictional scenario. Names, systems, evidence IDs, schedules, and proposed collections belong to the case study. Planned evidence collection, hashes, forensic findings, notifications, and recovery outcomes must not be represented as completed real-world actions unless actually performed and documented.

The source document includes an AI-assistance/authorship note. Before academic submission, replace the Student ID, official email, and submission date placeholders and verify the academy's current AI-use requirements.

## References

- CISA, MS-ISAC, NSA & FBI (2023), *#StopRansomware Guide*.
- ICDFA, *GRC105 Incident Response Planning* teaching material and assignment brief.
- NIST SP 800-61 Rev. 3 (2025), *Incident Response Recommendations and Considerations for Cybersecurity Risk Management*.

## Licence

The repository uses a restricted academic-use notice in `LICENSE`. The assignment remains the student's work and is not intended for redistribution as another learner's submission.
