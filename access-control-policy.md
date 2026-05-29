# Access Control Policy

**Organization:** [Organization Name]
**Policy Owner:** [Name and Title]
**Version:** 1.0
**Effective Date:** [Date]
**Review Date:** [Date + 1 Year]
**Approved By:** [Name and Title]

---

## 1. Purpose

This policy defines the requirements for managing access to
organizational systems, applications, and data. It establishes
the standards for granting, reviewing, modifying, and revoking
access to ensure that only authorized individuals can access
information appropriate to their role.

Access control is the foundational control in any information
security program. A failure in access control is a failure in
every other control that depends on it.

---

## 2. Scope

This policy applies to:
- All organizational systems, applications, databases, and networks
- All full-time and part-time employees
- Contractors, consultants, and temporary staff
- Third-party vendors and service providers with system access
- All access types including physical, logical, remote, and privileged

---

## 3. Policy Statements

### 3.1 Principle of Least Privilege

Access to organizational systems and data must be granted on the
principle of least privilege. Users must receive only the minimum
level of access necessary to perform their assigned job functions.

- Access must never be granted based on convenience or seniority
  alone
- Access to multiple systems must be evaluated independently — access
  to one system does not justify access to another
- Broad or administrative access must be specifically justified and
  approved at an elevated level

### 3.2 Access Request and Approval

All access requests must follow the formal access request process
before access is granted. Access must never be provisioned informally
or without documented approval.

**Access request requirements:**
- Submitted by the requesting user or their direct manager
- Includes the specific system, application, or data set requested
- Includes the business justification for the access
- Approved by the system owner and the requestor's direct manager
- Documented and retained for audit purposes

Access must not be provisioned until all required approvals are
obtained and documented.

### 3.3 User Account Management

**Account provisioning:**
- User accounts must be created using the organization's standard
  account provisioning process
- Default accounts and guest accounts must be disabled unless
  specifically required and approved
- Shared accounts are prohibited except where technically unavoidable
  and must be documented and approved as an exception

**Account modification:**
- Access changes resulting from role changes must be processed within
  3 business days of the role change
- Access that is no longer required due to a role change must be
  revoked — not simply left inactive

**Account termination:**
- All access must be revoked within 24 hours of employee termination
  or contractor offboarding
- HR must notify IT and the security team of terminations on or before
  the termination date
- Termination access revocation must be documented and verified

### 3.4 Privileged Access Management

Privileged access — including administrator accounts, root access,
service accounts, and any access that can modify security controls —
requires elevated controls beyond standard user access.

- Privileged accounts must be separate from standard user accounts.
  Administrators must use their standard account for non-privileged
  activities
- Privileged access must be approved by the system owner and the
  security team
- All privileged access activity must be logged and logs must be
  retained for a minimum of 12 months
- Privileged access must be reviewed monthly
- Just-in-time access is preferred over standing privileged access
  where technically feasible
- Shared privileged accounts are prohibited. Each privileged user
  must have an individually attributed account

### 3.5 Remote Access

Remote access to organizational systems introduces additional risk
and requires additional controls.

- Remote access is only permitted through approved and managed
  solutions — VPN, approved remote desktop tools, or equivalent
- Multi-factor authentication is required for all remote access
  without exception
- Remote access sessions must time out after 15 minutes of inactivity
- Remote access from unmanaged or personal devices requires prior
  written approval and must use endpoint isolation controls where
  available
- Remote access activity must be logged and reviewed monthly

### 3.6 Access Reviews

Access must be reviewed on a regular cadence to ensure it remains
appropriate and necessary.

| Access Type | Review Frequency | Reviewer |
|---|---|---|
| Standard user access — Confidential systems | Quarterly | System owner |
| Standard user access — Internal systems | Semi-annually | System owner |
| Privileged access — all systems | Monthly | Security team |
| Third-party and vendor access | Quarterly | System owner |
| Remote access | Monthly | IT and security team |
| Service account access | Quarterly | System owner |

During each access review, reviewers must certify that each account
reviewed is:
- Still required for the user's current role
- Assigned the appropriate level of access
- Active and in use — dormant accounts must be disabled

Access review results must be documented and retained for audit
purposes for a minimum of 3 years.

### 3.7 Multi-Factor Authentication

Multi-factor authentication (MFA) is required for:
- All remote access to organizational systems
- All privileged accounts
- All systems containing Confidential information
- All cloud-based systems and SaaS applications
- All email systems accessible externally

MFA must use an approved second factor — authenticator application,
hardware token, or SMS where no stronger option is available. SMS
is the least preferred option and must be replaced with stronger
factors where feasible.

### 3.8 Password Standards

Where passwords are used as an authentication factor they must meet
the following minimum standards:

- Minimum length of 12 characters
- Must include at least one uppercase letter, one lowercase letter,
  one number, and one special character
- Must not include the user's name, username, or common dictionary words
- Must not be reused within the last 12 password cycles
- Must not be shared with any other person under any circumstances
- Must be changed immediately upon any suspicion of compromise

Systems must enforce account lockout after 5 consecutive failed
login attempts. Lockout duration must be a minimum of 15 minutes
or require administrator intervention to unlock.

### 3.9 Third-Party and Vendor Access

Third-party access to organizational systems requires the same
controls as internal access plus additional oversight.

- Third-party access must be scoped to the minimum systems and data
  required to deliver the contracted service
- Third-party access must be time-limited where possible and reviewed
  at contract renewal or quarterly, whichever is sooner
- Third-party access must be individually attributed — shared vendor
  accounts are prohibited
- All third-party access activity must be logged
- Third-party access must be fully revoked at contract termination
  within 24 hours

---

## 4. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| Security Team | Maintain access control standards, conduct privileged access reviews, investigate access violations |
| System Owners | Approve access requests for their systems, conduct quarterly access reviews, report violations |
| IT Team | Provision and deprovision access per approved requests, maintain access logs |
| HR | Notify IT and security of new hires, role changes, and terminations on or before effective date |
| Managers | Approve access requests for their direct reports, notify HR and IT of role changes |
| All Personnel | Use access only for authorized purposes, report suspected unauthorized access immediately |

---

## 5. Exceptions

Exceptions to this policy must be submitted in writing to the
policy owner and the security team. Exception requests must include:

- The specific access control requirement for which an exception
  is requested
- The system or data affected
- The business justification
- The compensating controls in place to mitigate the risk
- The requested duration — exceptions are not permanent

Exceptions must be reviewed at least quarterly. Any exception that
cannot be supported by adequate compensating controls must be denied.

---

## 6. Enforcement

Violations of this policy — including unauthorized access attempts,
sharing of credentials, failure to complete access reviews, or
failure to revoke access upon termination — may result in
disciplinary action up to and including termination. Violations
involving unauthorized access to Confidential information will be
escalated to legal and law enforcement as appropriate.

---

## 7. Review Cycle

This policy must be reviewed annually and following any significant
access control incident, audit finding related to access management,
or major change in organizational systems or structure.

---

## 8. Related Documents

- Information Security Policy
- Acceptable Use Policy
- Privileged Access Management Standard
- Vendor Management Policy
- Incident Response Policy

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
