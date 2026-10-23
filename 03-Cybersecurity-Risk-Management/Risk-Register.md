# Cybersecurity Risk Register

## Project
E-Commerce Cybersecurity Risk Assessment and Mitigation Strategy Implementation

## Assessment Method
This academic simulation applies qualitative likelihood and impact ratings from 1 (Very Low) to 5 (Very High). Risk Score = Likelihood x Impact. Scores 1–5 are Low, 6–10 Moderate, 11–15 High and 16–25 Critical. Ratings are illustrative assumptions, not observed vulnerabilities.

## Risk Register

| ID | Risk | Likelihood | Impact | Score | Level | Proposed Mitigation |
|---|---|---:|---:|---:|---|---|
| R01 | SQL injection | 4 | 5 | 20 | Critical | Parameterised queries, input validation and security testing |
| R02 | Account takeover | 4 | 5 | 20 | Critical | MFA, password controls and login rate limiting |
| R03 | Cross-site scripting | 3 | 4 | 12 | High | Contextual output encoding and content security policy |
| R04 | Sensitive data exposure | 3 | 5 | 15 | High | Encryption, access controls and data minimisation |
| R05 | Payment fraud | 3 | 5 | 15 | High | Payment-provider controls, transaction monitoring and fraud review |
| R06 | DDoS disruption | 3 | 4 | 12 | High | Traffic filtering, rate limiting and incident response planning |
| R07 | Security misconfiguration | 4 | 4 | 16 | Critical | Hardened configurations, access reviews and configuration checks |
| R08 | Third-party vulnerabilities | 3 | 4 | 12 | High | Dependency inventory, patch management and supplier assessment |

## Response and Monitoring
Each risk should be assigned an owner during team allocation. Review risks weekly, update their status when assumptions change and escalate Critical risks to the project lead.

## Disclaimer
This risk register contains hypothetical project planning estimates. No live e-commerce systems have been scanned or tested as part of this document.
