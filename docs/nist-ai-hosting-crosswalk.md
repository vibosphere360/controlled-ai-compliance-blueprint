# NIST AI Hosting and Inference Crosswalk

| Notice Requirement | Operational Implication | Example Control Theme | Example Evidence |
|---|---|---|---|
| Quick-turn hosting | New models need intake and deployment workflow | Model onboarding governance | Intake checklist, approval log |
| Accurate inference | Serving config must be validated | Inference validation and QA | Validation checklist, test records |
| Rapid scaling | Capacity growth cannot bypass controls | Secure autoscaling and change control | Change records, architecture review |
| No data retention | Requests and outputs must not persist beyond approved scope | Data minimization and retention control | Retention config, deletion policy |
| Direct GPU access | Strong workload isolation required | Compute segmentation and tenancy control | Environment diagrams, access logs |
| NIST 800-171 Rev. 3 for CUI | CUI handling controls must be implemented | CUI safeguarding program | Boundary definition, SSP excerpts |
| FIPS 140-3 validated crypto | Approved cryptographic boundary required | Cryptographic module governance | Module inventory, validation references |
| Phishing-resistant MFA | Strong identity assurance required | Identity hardening | MFA configuration evidence |
| U.S.-only infrastructure | Geographic and provider restrictions must be enforced | Residency and sovereignty control | Region restrictions, provider attestations |
