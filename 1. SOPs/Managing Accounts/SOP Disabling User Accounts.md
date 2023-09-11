# NIST-Compliant User Account Disabling Procedure

## Objective
To establish a secure and standardized process for disabling user accounts while complying with NIST Special Publication 800-53.

## Scope
This procedure applies to all personnel responsible for disabling user accounts on military information systems.

## Responsibilities

Account Administrator: The individual responsible for disabling user accounts and ensuring adherence to security policies.

## Procedure

1. Account Request:

Account disabling requests can originate from various sources, including security incidents, supervisor requests, or automated processes.
Requests must be documented and include the reason for disabling the account.

2. Authentication:

Verify the authenticity of the account disabling request, ensuring that it is legitimate and authorized.

3. Access Control Review:

Perform an access control review to assess the impact of disabling the account on system security and access permissions.
Consider the principle of least privilege (POLP) and NIST SP 800-53 requirements.

4. Notification:

Notify the user, or their supervisor if applicable, of the account's impending disabling, including the reason for the action.
Provide guidance on any steps the user needs to take to address the issue or request reactivation if necessary.

5. User Account Disabling:

Disable the user account promptly following these steps:
- Disable login access to the system by changing the account status.
- Make a note of the reason for the disabled account in the appropriate system, such as Active Directory: Users and Accounts
- If applicable, revoke all system privileges and access permissions associated with the account.
- Securely archive or backup user data as required by data retention policies.


6. Change Passwords:

If the disabling is due to a security incident or breach, change the account's password to prevent unauthorized access.

7. Documentation:

Maintain accurate records in the MSL (or other log as applicable) of all user account disabling activities, including the request, access control review, notifications, and actions taken.
Document the date and time of the disabling.

8. Record Keeping:

All records related to user account disabling must be retained in accordance with applicable record retention policies.

9. Audit:

Regularly audit the user account disabling process to ensure compliance with NIST standards and organizational security policies.
Conduct post-mortem reviews of security incidents involving account disabling to identify areas for improvement.

## References

NIST Special Publication 800-53 - "Security and Privacy Controls for Federal Information Systems and Organizations."
