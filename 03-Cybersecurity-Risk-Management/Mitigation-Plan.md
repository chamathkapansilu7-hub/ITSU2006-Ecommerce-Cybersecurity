# Proposed Cybersecurity Risk Mitigation Plan

This is a planning deliverable for a hypothetical e-commerce platform. Priorities reflect the qualitative risk register; no live vulnerability testing is claimed.

| Risk | Preventive measures | Detective / responsive measures | Proposed acceptance evidence |
|---|---|---|---|
| SQL injection | Parameterised SQL and server-side validation | Code review and authorised test scenarios | Secure query review checklist |
| Account takeover | MFA, rate limits, password policy | Suspicious-login monitoring and account recovery | Authentication test plan |
| Cross-site scripting | Contextual encoding, sanitisation and CSP | Security scanning on authorised test environment | XSS test cases |
| Sensitive data exposure | TLS, encryption at rest, least privilege | Access logs and incident response runbook | Privacy and configuration review |
| Payment fraud | Outsourced payment handling and transaction controls | Fraud pattern alerts, manual review | Payment workflow checklist |
| DDoS | CDN/WAF, rate limiting and scalability plan | Availability monitoring and incident escalation | Resilience planning document |
| Misconfiguration | Baseline hardening, least privilege, secure defaults | Periodic compliance checks | Configuration checklist |
| Third-party vulnerabilities | Software bill of materials, dependency updates | Advisories monitoring and remediation tracker | Dependency inventory |

## Prioritisation
1. Address critical risks first (score >= 16).
2. Assign every mitigation to a proposed role and an acceptance test.
3. Review residual risk assumptions before hypothetical handover.
4. Escalate residual critical risks for project sponsor decision.

## Limitations
The measures are proposals only and do not establish that any controls were deployed.
