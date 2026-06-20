# Incident Response Policy

**Organization:** [Organization Name]
**Policy Number:** IRP-001
**Policy Owner:** [Name and Title]
**Version:** 1.0
**Classification:** Internal
**Effective Date:** [Date]
**Review Date:** [Date + 1 Year]
**Approved By:** [Name and Executive Title]

---

## 1. Purpose

This policy establishes the organization's requirements for
preparing for, detecting, containing, eradicating, recovering
from, and learning from security incidents. It defines the
roles, responsibilities, and procedures that ensure the
organization can respond to incidents in a consistent,
coordinated, and timely manner that minimizes impact to
operations, customers, and stakeholders.

Effective incident response is not a reactive capability.
It is a designed system. Organizations that respond well
to incidents are those that prepared before the incident
occurred — not those that improvised during it.

---

## 2. Scope

This policy applies to:

- All full-time and part-time employees
- All contractors, consultants, and temporary staff
- All third-party vendors and service providers with
  access to organizational systems or data
- All information systems, networks, devices, and
  cloud environments owned, leased, or managed by
  the organization
- All actual or suspected security incidents regardless
  of origin, severity, or the system affected

---

## 3. Definitions

**Security Incident:** Any actual or suspected event that
compromises the confidentiality, integrity, or availability
of organizational information or systems. Includes but is
not limited to: unauthorized access, malware infection,
data exfiltration, denial of service, insider threat
activity, and physical security breaches affecting
information systems.

**Incident Severity:** A classification of the potential
or actual impact of a security incident used to determine
the appropriate response urgency and escalation path.

**Incident Response Team (IRT):** The designated group of
individuals responsible for executing the incident response
process. Membership includes IT security, IT operations,
legal counsel, communications, and executive leadership
as appropriate to the severity of the incident.

**Root Cause Analysis (RCA):** A structured investigation
into the underlying cause of an incident, conducted after
containment and recovery, to identify the conditions that
allowed the incident to occur and prevent recurrence.

---

## 4. Incident Severity Classification

All incidents must be classified by severity upon initial
identification. Severity determines the response timeline,
escalation requirements, and notification obligations.

| Severity | Definition | Response Target |
|---|---|---|
| Critical | Confirmed breach of Confidential data, active ransomware, complete system compromise, or incident affecting safety | Immediate — within 1 hour |
| High | Suspected data exfiltration, significant malware infection, compromise of privileged accounts, or major service disruption | Within 4 hours |
| Medium | Unauthorized access attempt, isolated malware, policy violation with potential data exposure, or moderate service degradation | Within 24 hours |
| Low | Minor policy violations, failed attack attempts, anomalous activity with no confirmed impact | Within 72 hours |

Severity classifications must be reviewed and updated as
the incident evolves. An incident that begins as Medium
may escalate to Critical as investigation reveals greater
impact.

---

## 5. Incident Response Lifecycle

This policy follows the six-phase incident response
lifecycle defined in NIST SP 800-61 Revision 2.

### 5.1 Preparation

The organization must maintain a state of readiness to
respond to security incidents before they occur.
Preparation requirements include:

- Maintaining a current and tested Incident Response Plan
  that operationalizes this policy
- Designating and training an Incident Response Team with
  clearly defined roles and contact information
- Establishing and testing communication channels for
  incident notification including out-of-band communication
  methods in the event primary systems are compromised
- Maintaining documented and tested playbooks for the
  incident types most likely to affect the organization
  including ransomware, data breach, insider threat, and
  cloud environment compromise
- Conducting tabletop exercises at minimum annually to
  validate response procedures and team readiness
- Ensuring logging and monitoring controls are in place
  and configured to generate the evidence necessary to
  detect and investigate incidents
- Maintaining relationships with external resources
  including legal counsel, cyber insurance providers,
  forensic vendors, and law enforcement contacts

### 5.2 Detection and Analysis

Incidents may be detected through automated monitoring
alerts, employee reports, external notifications from
third parties or law enforcement, or discovery during
routine operations.

Upon detection of a potential incident the following
actions must be taken:

- The detecting party must report the potential incident
  to the designated security team within two hours of
  discovery regardless of perceived severity
- The security team must perform initial triage to
  determine whether the event constitutes a security
  incident and assign an initial severity classification
- The security team must document all available
  information about the incident including: date and time
  of detection, detection method, systems and data
  potentially affected, indicators of compromise
  observed, and actions already taken
- Evidence must be preserved in its original state.
  Personnel must not attempt to remediate, delete, or
  modify any system or data potentially involved in an
  incident without explicit authorization from the
  Incident Response Team
- The Incident Response Team must be activated for
  any incident classified as Medium or above

### 5.3 Containment

Containment limits the spread and impact of an active
incident. Containment strategy must be selected based
on the nature and severity of the incident and must
balance the need to stop the incident with the need to
preserve evidence for investigation.

Containment actions may include:

- Isolating affected systems from the network while
  preserving their current state for forensic analysis
- Disabling compromised user accounts and revoking
  associated access tokens and credentials
- Blocking malicious IP addresses, domains, or file
  hashes at the network perimeter and endpoint level
- Engaging cloud provider security controls to restrict
  access to affected cloud environments
- Activating backup systems or failover environments
  where primary systems must be taken offline

All containment actions must be documented with the
rationale, the person who authorized the action, and
the time the action was taken.

### 5.4 Eradication

After containment, the root cause of the incident must
be identified and eliminated before systems are returned
to production.

Eradication requirements include:

- Identifying and removing all malicious code, files,
  and unauthorized access points from affected systems
- Identifying the initial attack vector and addressing
  the vulnerability or weakness that allowed the
  incident to occur
- Resetting all credentials and access tokens for
  any accounts that were or may have been compromised
- Validating that affected systems are clean and that
  no persistence mechanisms remain before proceeding
  to recovery
- Documenting all eradication actions taken

### 5.5 Recovery

Recovery restores affected systems and services to normal
operation in a controlled and verified manner.

Recovery requirements include:

- Restoring systems from known-good backups or clean
  builds where system integrity cannot be confirmed
- Validating system integrity and security configuration
  before returning systems to production
- Monitoring restored systems closely for a minimum of
  30 days following recovery for signs of reinfection
  or re-compromise
- Returning systems to production only with explicit
  authorization from the Incident Response Team and
  documented sign-off from the system owner
- Communicating the recovery status and timeline to
  affected stakeholders throughout the recovery process

### 5.6 Post-Incident Activity

Every incident classified as Medium or above must be
followed by a formal post-incident review conducted
within 14 days of incident closure.

Post-incident review requirements include:

- Documenting a complete incident timeline from first
  indicator to full recovery
- Conducting a root cause analysis that identifies the
  underlying conditions that allowed the incident to
  occur — not just the immediate cause
- Identifying specific actions to prevent recurrence
  with named owners and target completion dates
- Updating incident response procedures, playbooks, and
  controls based on lessons learned
- Distributing a post-incident report to the appropriate
  stakeholders including executive leadership and the
  audit function
- Tracking all remediation actions to completion and
  verifying effectiveness

---

## 6. Notification and Reporting Requirements

### 6.1 Internal Notification

| Incident Severity | Notify | Timeline |
|---|---|---|
| Critical | Executive Leadership, Legal, IT Security, Communications | Within 1 hour of classification |
| High | IT Security Manager, Legal, IT Leadership | Within 4 hours of classification |
| Medium | IT Security Manager, System Owner | Within 24 hours of classification |
| Low | IT Security Manager | Within 72 hours of classification |

### 6.2 External Notification

External notification obligations depend on the nature
of the incident and applicable regulatory and contractual
requirements. External notification may be required to:

- Affected individuals whose personal data was or may
  have been compromised
- Regulatory bodies as required by applicable law
  including state breach notification requirements,
  HIPAA, GDPR, and sector-specific regulations
- Cyber insurance providers as specified in the
  organization's policy
- Third-party vendors or partners whose systems or
  data may have been affected
- Law enforcement where the incident involves criminal
  activity

Legal counsel must be involved in all external
notification decisions. Notification timelines and
content must comply with applicable legal requirements.
External notifications must not be made without prior
approval from legal counsel and executive leadership.

---

## 7. Evidence Preservation

Evidence preservation is critical to both effective
investigation and potential legal proceedings. The
following requirements apply to all incident evidence:

- All logs, system images, network captures, and other
  digital evidence must be preserved in their original
  unmodified state from the point of detection
- Evidence must be collected using forensically sound
  methods that maintain chain of custody
- Physical and digital evidence must be stored securely
  with access limited to authorized IRT members and
  any engaged forensic vendors
- Evidence must be retained for a minimum of three years
  following incident closure or longer if required by
  applicable law or active litigation
- Personnel must not delete, modify, or attempt to
  remediate evidence without explicit written
  authorization from the IRT

---

## 8. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| All Personnel | Report actual or suspected incidents within 2 hours of discovery; preserve evidence; do not attempt independent remediation |
| IT Security Team | Lead incident detection, triage, containment, eradication, and recovery; maintain incident documentation; activate the IRT |
| Incident Response Team | Execute the incident response lifecycle; make containment and recovery decisions; coordinate internal and external communication |
| Legal Counsel | Advise on external notification obligations; manage legal hold requirements; support law enforcement engagement |
| Executive Leadership | Authorize major containment and recovery decisions; approve external notifications; ensure adequate resources for response |
| System Owners | Support incident investigation for systems under their ownership; authorize containment actions affecting their systems; participate in post-incident review |
| Communications | Manage internal and external communications; develop stakeholder messaging; coordinate with legal on public statements |
| People Operations | Support insider threat investigations; manage personnel actions arising from incident investigation |

---

## 9. Exceptions

Exceptions to this policy must be submitted in writing
to the Policy Owner and approved prior to implementation.
Exception requests must include the specific requirement
for which an exception is requested, the business
justification, the compensating controls in place, and
the requested duration. Unapproved exceptions are policy
violations.

---

## 10. Enforcement

Failure to comply with this policy — including failure
to report incidents, unauthorized remediation of evidence,
or failure to participate in post-incident activities —
may result in disciplinary action up to and including
termination. Violations involving criminal activity will
be referred to law enforcement.

---

## 11. Policy Review and Maintenance

This policy must be reviewed annually and following any
significant security incident, material change in
organizational systems or structure, or new regulatory
requirement affecting incident response obligations.

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | [Date] | [Author] | Initial release |

---

## 12. Related Documents

- Information Security Policy (ISP-001)
- Access Control Policy (ACP-001)
- Acceptable Use Policy (AUP-001)
- Business Continuity Policy
- Data Classification Standard
- Vendor Management Policy
- NIST SP 800-61 Rev. 2 — Computer Security Incident
  Handling Guide

---

*This template is part of the
[GRC Policy Library](https://github.com/neviarrawlinson/grc-policy-library)
maintained by Neviar Rawlinson at
[GRC Explained](https://grcexplained.com).
Free to use, adapt, and share.*
