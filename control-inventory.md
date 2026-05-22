# Control Inventory

## Purpose

This control inventory identifies key cybersecurity controls that support audit readiness, compliance documentation, and security governance.

From a GRC analyst perspective, a control inventory helps organize which controls exist, who owns them, what evidence is needed, how often the control should be reviewed, and whether the control is ready for audit or requires remediation.

## Control Inventory Overview

| Control ID | Control Area | Control Description | Suggested Owner | Review Frequency | Evidence Needed | Status |
|---|---|---|---|---|---|---|
| AC-001 | Access Control | User access is granted based on job role and business need. | IT / IAM | Quarterly | Access control policy, user access list, approval records | Needs Review |
| AC-002 | Privileged Access | Administrative accounts are limited, monitored, and reviewed. | Security / IAM | Quarterly | Privileged user list, access review evidence, approval records | Needs Review |
| AC-003 | User Access Reviews | User access is reviewed periodically to confirm continued business need. | IT / Compliance | Quarterly | Access review report, reviewer sign-off, remediation notes | Needs Evidence |
| AC-004 | Offboarding | Access for terminated employees and contractors is removed promptly. | HR / IT | Per termination | Offboarding checklist, deactivation logs, HR termination records | Needs Review |
| IA-001 | Multi-Factor Authentication | MFA is required for sensitive systems and remote access. | IT / Security | Quarterly | MFA configuration screenshot, coverage report, exception list | Needs Evidence |
| IA-002 | Password Security | Password requirements follow documented security standards. | IT / Security | Annually | Password policy, system settings, exception documentation | Needs Review |
| VR-001 | Vendor Risk Management | Critical vendors are reviewed for cybersecurity and privacy risk. | Vendor Management / Compliance | Annually | Vendor inventory, risk questionnaire, SOC 2 report, contract security terms | Needs Evidence |
| VR-002 | Third-Party Incident Notification | Vendor contracts define breach notification and incident communication expectations. | Legal / Compliance | Annually | Contract clauses, vendor security addendum, incident notification terms | Needs Review |
| LOG-001 | Security Logging | Security-relevant events are logged and retained for investigation and audit purposes. | Security Operations | Quarterly | Log retention policy, SIEM screenshots, sample log records | Needs Evidence |
| MON-001 | Security Monitoring | Security events are monitored for suspicious or unauthorized activity. | Security Operations | Quarterly | Alert configuration, monitoring procedures, sample alerts | Needs Review |
| IR-001 | Incident Response Plan | A documented incident response plan defines roles, responsibilities, and escalation procedures. | Security / GRC | Annually | Incident response plan, approval record, communication tree | Needs Review |
| IR-002 | Incident Response Testing | Incident response procedures are tested through tabletop exercises or simulations. | Security / GRC | Annually | Tabletop exercise record, lessons learned, action items | Gap Identified |
| POL-001 | Policy Management | Cybersecurity policies are documented, approved, and reviewed periodically. | GRC / Compliance | Annually | Policy inventory, approval records, review dates | Needs Evidence |
| DP-001 | Data Protection | Sensitive data is protected through access restrictions, encryption, and data handling procedures. | Security / Data Governance | Annually | Data classification policy, encryption evidence, access restrictions | Needs Review |
| AUD-001 | Audit Evidence Management | Control evidence is collected, tracked, and stored in an organized manner. | GRC / Compliance | Quarterly | Evidence tracker, control owner list, evidence repository | Gap Identified |
| REM-001 | Remediation Tracking | Identified gaps and corrective actions are tracked to completion. | GRC / Risk Management | Monthly | Remediation tracker, status updates, owner assignments | Needs Evidence |

## Control Status Definitions

| Status | Meaning |
|---|---|
| Ready | Control appears documented and supported by current evidence. |
| Needs Review | Control exists but requires validation, updated documentation, or owner confirmation. |
| Needs Evidence | Control may exist but supporting evidence is missing or incomplete. |
| Gap Identified | A control weakness or missing process has been identified and should be remediated. |

## Key Control Themes

This inventory highlights several important audit readiness themes:

1. Access control and identity governance  
2. Privileged access management  
3. Multi-factor authentication  
4. Employee offboarding  
5. Vendor risk management  
6. Security logging and monitoring  
7. Incident response readiness  
8. Policy management  
9. Data protection  
10. Evidence and remediation tracking  

## GRC Analyst Takeaway

This control inventory demonstrates how a GRC analyst organizes cybersecurity controls into a structured audit readiness format.

The inventory helps identify:

- Which controls are in scope
- Who owns each control
- What evidence is required
- How often controls should be reviewed
- Which controls need additional evidence or remediation

This type of documentation supports internal audits, external assessments, customer security reviews, and cybersecurity governance maturity.