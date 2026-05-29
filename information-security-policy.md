# Information Security Policy

**Organization:** [Organization Name]
**Policy Owner:** [Name and Title]
**Version:** 1.0
**Effective Date:** [Date]
**Review Date:** [Date + 1 Year]
**Approved By:** [Name and Title]

---

## 1. Purpose

This policy establishes the organization's commitment to protecting
the confidentiality, integrity, and availability of its information
assets. It defines the requirements that all personnel must follow
to safeguard organizational information against unauthorized access,
disclosure, alteration, and destruction.

---

## 2. Scope

This policy applies to:
- All full-time and part-time employees
- Contractors, consultants, and temporary staff
- Third-party vendors with access to organizational systems or data
- All information assets owned, leased, or managed by the organization
- All systems, networks, and devices used to process organizational data

---

## 3. Policy Statements

### 3.1 Information Classification

All organizational information must be classified according to its
sensitivity and the potential impact of unauthorized disclosure.

- **Confidential:** Information whose unauthorized disclosure would
  cause significant harm to the organization, its customers, or its
  partners. Includes personally identifiable information (PII),
  financial records, authentication credentials, and proprietary
  business data.
- **Internal:** Information intended for internal use only. Not
  authorized for public disclosure but whose unauthorized release
  would cause limited harm.
- **Public:** Information authorized for public distribution. No
  restrictions on disclosure.

Information owners are responsible for classifying information assets
under their control and reviewing classifications annually.

### 3.2 Access Control

Access to organizational information and systems must be granted on
the principle of least privilege — users receive the minimum access
necessary to perform their job functions.

- All access requests must be formally submitted and approved by the
  relevant system owner and the user's direct manager
- Access must be reviewed quarterly for all systems containing
  Confidential information
- Access must be revoked within 24 hours of employee termination or
  role change that eliminates the need for access
- Shared accounts and generic credentials are prohibited
- Privileged access must be reviewed monthly and justified in writing

### 3.3 Authentication Requirements

All systems and applications must enforce the following minimum
authentication standards:

- Passwords must be a minimum of 12 characters and include uppercase,
  lowercase, numbers, and special characters
- Multi-factor authentication (MFA) is required for all remote access,
  privileged accounts, and systems containing Confidential information
- Passwords must not be reused within the last 12 cycles
- Account lockout must be enforced after 5 failed login attempts
- Default vendor credentials must be changed before any system is
  placed into production

### 3.4 Data Handling and Transmission

- Confidential information must be encrypted in transit using TLS 1.2
  or higher
- Confidential information must be encrypted at rest using AES-256
  or equivalent
- Confidential information must not be transmitted via unencrypted
  email or stored on personal devices without prior written approval
- Removable media containing Confidential information must be encrypted
  and tracked in an asset inventory
- Confidential information must not be stored in unapproved cloud
  services or personal accounts

### 3.5 Incident Reporting

All personnel must report actual or suspected security incidents
immediately upon discovery. Reporting delays increase organizational
risk and may result in disciplinary action.

- Security incidents must be reported to the designated security team
  within 2 hours of discovery
- Incident reports must include: date and time of discovery, nature
  of the incident, systems or data potentially affected, and actions
  already taken
- Personnel must preserve evidence and must not attempt to remediate
  incidents independently without authorization from the security team

### 3.6 Acceptable Use

Organizational systems and information assets must be used for
legitimate business purposes. Personnel must not:

- Access, copy, or transmit information beyond the scope of their
  job responsibilities
- Attempt to bypass, disable, or test security controls without
  written authorization
- Install unauthorized software on organizational systems
- Use organizational systems to access, store, or transmit illegal,
  offensive, or inappropriate content

### 3.7 Physical Security

- Unattended workstations must be locked when not in active use
- Confidential documents must not be left unattended in common areas
- Clean desk standards apply to all personnel handling Confidential
  information — sensitive materials must be secured at end of day
- Visitors must be escorted in areas where Confidential information
  is processed or displayed

### 3.8 Third-Party and Vendor Security

- All third-party vendors with access to organizational systems or
  data must sign a security agreement or data processing agreement
  before access is granted
- Vendors handling Confidential information must provide evidence of
  security controls — SOC 2 report, ISO 27001 certificate, or
  completed security questionnaire — prior to onboarding and annually
- Vendor access must be limited to the minimum necessary and
  reviewed quarterly

---

## 4. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| Executive Leadership | Approve policy, ensure adequate resources for security program |
| Policy Owner | Maintain and update this policy, track compliance |
| IT and Security Team | Implement technical controls, monitor for incidents, manage access |
| Managers | Ensure team members complete training, enforce policy within their teams |
| All Personnel | Read, understand, and comply with this policy; report incidents promptly |
| Third-Party Vendors | Comply with security requirements defined in vendor agreements |

---

## 5. Exceptions

Exceptions to this policy must be submitted in writing to the policy
owner. Exception requests must include:

- The specific policy requirement for which an exception is requested
- The business justification for the exception
- The compensating controls that will be implemented to mitigate risk
- The requested duration of the exception

Exceptions must be approved by the policy owner and reviewed at least
quarterly. Unapproved exceptions are policy violations.

---

## 6. Enforcement

Violations of this policy may result in disciplinary action up to and
including termination of employment or contract. Violations involving
criminal activity will be reported to appropriate law enforcement
authorities.

---

## 7. Review Cycle

This policy must be reviewed annually by the policy owner and updated
to reflect changes in the organizational environment, threat landscape,
or regulatory requirements. Reviews must also be triggered by:

- A significant security incident
- A major change in organizational structure or technology
- A new regulatory requirement affecting information security
- An audit finding related to information security governance

---

## 8. Related Documents

- Access Control Policy
- Acceptable Use Policy
- Incident Response Policy
- Data Classification Standard
- Vendor Management Policy

---

## 9. Version History

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | [Date] | [Author] | Initial release |

---

*This template is part of the
[GRC Policy Library](https://github.com/neviarrawlinson/grc-policy-library)
maintained by Neviar Rawlinson at
[GRC Explained](https://grcexplained.com).
Free to use, adapt, and share.*
