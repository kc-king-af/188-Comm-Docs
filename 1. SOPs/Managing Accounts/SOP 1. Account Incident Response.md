# Account Privilege Escalation Incident Response Plan

## Purpose

The purpose of this Incident Response Plan (IRP) is to provide a structured approach for detecting, responding to, and mitigating incidents involving user account privilege escalation within our organization.

## Scope

This plan covers incidents related to unauthorized or inappropriate privilege escalation on accounts within the organization's information systems.

## Roles and Responsibilities

System Administrators: Responsible for monitoring and managing user accounts, recognizing possible incidents, escalation to the Incident Response Team (IRT) and assisting in the investigation.

Incident Response Team (IRT): responsible for verifying the incident and coordinating the response. 
- IT security experts (SSOs & IA)
- Senior system administrators (supervisors)
- Management (shop supervisor & operations supervisor on shift)
- Senior/executive leadership and legal representatives

### Summary of Steps
1. Incident detection, identification, and notification/escalation to IRT
2. Initial assessment of incident, impact and risk
3. Containment and mitigation 
4. Deeper investigation and analysis
5. Communication and reporting
6. Recovery and remediation
7. Documentation, lessons learned, final report to stakeholders
8. Training and process improvement 


## Incident Response Step Details

Possible incidents involving account escalation must be treated with the utmost urgency and concern. A privileged user is capable of exponentially greater impact than a typical standard user account.

### Incident Detection, Identification, and Notification/Escalation to IRT
- Any personnel who suspect or identify a user account privilege escalation incident (or any security incident for that matter) should report it immediately to the IT helpdesk or designated incident reporting channel.
- The IT helpdesk will escalate the incident to the Incident Response Team (IRT), beginning with their immediate supervisor. 
- If the supervisor is not available, the next member of the chain of command will be notified. 
- Any suspected security incidents should be reported through chain of command to the shop supervisor at minimum. 

### Initial Assessment of Incident, Impact and Risk
- The reporting member will assist the IRT as they conduct an initial assessment of the incident to determine its scope and impact.
- If the incident is confirmed, it will be assigned a severity level and escalated.
- If the incident is related to a privileged account, ALL privileged accounts related to the incident, member or service should be immediately <u>disabled</U> and systems potentially impacted by the member or service should be quarantined.
- <mark>NOTE: in general, the account should not be deleted until an investigation has been completed by the IRT team.</mark>


### Containment and Mitigation 

- The IRT will take immediate steps to contain the incident and prevent further privilege escalation. 
- If the issue is related to account access, the account (and any other related accounts) will be immediately disabled and quarantined. 
- Other mitigation actions may include revoking elevated privileges, removal from the SCIF and notifying Security Forces to secure any suspected members for questioning.

### Deeper Investigation and Analysis
- The IRT will conduct a detailed investigation to identify the root cause of the incident and determine the extent of the compromise.
- All findings will be documented for analysis.

### Communication and Reporting
- Internal and external stakeholders will be informed according to the severity level.
- Legal and regulatory obligations will be considered when reporting incidents to authorities or affected parties.

### Recovery and Remediation
- Once the incident is contained, the IRT will develop a plan for system recovery and remediation.
- This may include restoring affected systems from backups, reverting systems to last-known-good states, patching vulnerabilities, and reevaluating access controls.

### Documentation, lessons learned, final report to stakeholders
- All incident details, actions taken, and lessons learned will be documented.
- A post-incident review will be conducted to improve future incident response efforts.

### Training and process improvement 
* Regular training and awareness programs will be conducted to educate employees about the risks of privilege escalation and how to report suspicious activities.
* The IRP will be periodically tested through tabletop exercises and real-world simulations.
* Reviews and updates to the plan will be conducted after each incident and on a regular basis.

### Remember
If you see something, say something.