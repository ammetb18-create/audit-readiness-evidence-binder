# Audit Gap Analysis

## Purpose

This audit gap analysis identifies areas where cybersecurity control documentation, evidence, or operating procedures may be incomplete or not yet audit-ready.

From a GRC analyst perspective, a gap analysis helps compare expected control requirements against available evidence and current documentation.

## Gap Analysis Overview

| Gap ID | Control Area | Expected Control / Evidence | Current Gap | Risk Level | Recommended Action | Suggested Owner |
|---|---|---|---|---|---|---|
| G-001 | Access Reviews | Quarterly user access reviews should be documented and approved. | Access review evidence is missing or incomplete. | High | Create a recurring access review process and retain reviewer sign-off. | IT / Compliance |
| G-002 | MFA Evidence | MFA enforcement should be documented for sensitive systems. | MFA configuration evidence or coverage report is missing. | High | Generate MFA coverage report and maintain exception list. | IT / Security |
| G-003 | Privileged Access | Privileged accounts should be reviewed and monitored. | Privileged access review evidence is not available. | High | Create privileged user list and perform quarterly review. | Security / IAM |
| G-004 | Offboarding | Access removal should be documented after employee or contractor termination. | Offboarding checklist exists inconsistently or is not centrally stored. | Medium to High | Standardize offboarding checklist and retain deactivation evidence. | HR / IT |
| G-005 | Vendor Due Diligence | Critical vendors should have completed security reviews. | Vendor questionnaires or SOC 2 reports are missing for some vendors. | High | Build vendor inventory and request security documentation for critical vendors. | Vendor Management / Compliance |
| G-006 | Incident Response Testing | Incident response plan should be tested periodically. | No tabletop exercise evidence is available. | High | Conduct annual tabletop exercise and document lessons learned. | Security / GRC |
| G-007 | Security Logging | Security logs should be retained and available for investigation and audit. | Log retention evidence is incomplete. | Medium to High | Document log retention policy and collect sample log evidence. | Security Operations |
| G-008 | Policy Review | Cybersecurity policies should be reviewed and approved periodically. | Policy review dates or approvals are not consistently documented. | Medium | Create policy inventory with review dates and approval records. | GRC / Compliance |
| G-009 | Evidence Management | Audit evidence should be centrally tracked and organized. | No centralized evidence tracker is in place. | Medium to High | Maintain an evidence request tracker with owners, status, and review notes. | GRC / Compliance |
| G-010 | Remediation Tracking | Audit gaps and corrective actions should be tracked to closure. | No formal remediation tracker is available. | Medium to High | Create remediation plan with owners, due dates, status, and priority. | GRC / Risk Management |

## Highest Priority Gaps

The most important gaps to address first are:

1. Missing access review evidence  
2. Missing MFA enforcement evidence  
3. Missing privileged access review evidence  
4. Incomplete vendor due diligence documentation  
5. Missing incident response tabletop exercise evidence  
6. Lack of centralized audit evidence management  
7. Lack of formal remediation tracking  

## Business Impact

If these gaps are not addressed, the organization may face:

- Weak audit readiness
- Delayed compliance responses
- Limited evidence of control effectiveness
- Increased unauthorized access risk
- Increased vendor and third-party risk
- Reduced incident response maturity
- Difficulty demonstrating cybersecurity governance to customers, auditors, or leadership

## Recommended Remediation Approach

The organization should address gaps using a phased approach:

| Phase | Focus |
|---|---|
| Phase 1 | Collect high-priority access control and MFA evidence. |
| Phase 2 | Complete vendor due diligence and incident response testing documentation. |
| Phase 3 | Build centralized evidence management and remediation tracking processes. |

## GRC Analyst Takeaway

A gap analysis helps a GRC analyst identify where controls may exist but are not yet supported by sufficient documentation or evidence.

This analysis demonstrates the ability to:

- Compare expected controls against available evidence
- Identify audit readiness weaknesses
- Prioritize remediation
- Communicate business impact
- Support control owners
- Improve compliance documentation maturity