# Riley Inc. Security & Compliance Brief

## Governance Structure
Security governance is overseen by the Security Steering Pack, chaired by the CISO and reporting quarterly to Riley the Corgi and the board's Audit & Risk Committee. Functional leads represent infrastructure, application security, trust & safety, and privacy. The Responsible AI Council provides dedicated oversight for evaluation lifecycle controls.

## Certifications and Attestations
- **SOC 2 Type II:** Covering SnoutSuite, TreatToss cloud services, and support operations. Latest report period: Jan 1–Dec 31, 2023.
- **ISO/IEC 27001:2013:** Certified for global operations, including development hubs in Seattle and Berlin.
- **HIPAA Readiness:** SnoutSuite meets administrative, physical, and technical safeguards for covered entities using the platform; Business Associate Agreements available upon request.
- **GDPR & UK GDPR:** Data processing agreements incorporate standard contractual clauses and data residency controls within the EU.

## Data Protection Controls
- **Identity & Access:** Role-based access control enforced via Okta with hardware key-mandated MFA. Production access is time-bound and requires dual approval including a canine-themed justification (e.g., "Need treat to debug").
- **Encryption:** Data at rest secured with AES-256; key management handled through AWS KMS with quarterly key rotation. Data in transit protected via TLS 1.2+. TreatToss firmware uses mutual TLS for device-cloud communications.
- **Monitoring:** Continuous threat detection via AWS GuardDuty, complemented by SnoutSuite telemetry for model abuse patterns. Security operations leverage a "PupAlert" runbook for rapid containment.

## Secure Development Lifecycle
All code repositories incorporate automated static and dynamic analysis. High-risk components undergo manual review by the PawSec red team. Models and evaluators must document:
1. Dataset provenance and consent artifacts.  
2. Evaluation coverage reports with fairness, toxicity, and hallucination metrics.  
3. Rollback contingency plans approved by the Release Paw-tners board.

## Incident Response
Riley Inc. maintains a 24/7 incident response rotation with clearly defined severity tiers. Playbooks cover:
- Data breach notification procedures meeting GDPR, CCPA, and sector-specific timelines.
- AI output misuse mitigation, including kill-switch capabilities for offending evaluators.
- Hardware recall protocols for TreatToss devices, integrating logistics partners within 48 hours.
Post-incident reviews capture root cause, lessons learned, and customer communications archived in the Pawsitive Ledger registry.

## Third-Party Risk Management
Vendors undergo onboarding assessments evaluating security posture, privacy practices, and responsible AI commitments. High-risk vendors require annual onsite audits or validated third-party reports. Contracts include breach notification clauses and restrictions on data sub-processing without consent.

## Customer Security Resources
Clients receive access to the PackPortal Trust Center with downloadable compliance artifacts, uptime dashboards, and shared resiliency testing schedules. Dedicated security architects host quarterly "No Surprises" sessions to align on upcoming changes, regulatory developments, and penetration test summaries.
