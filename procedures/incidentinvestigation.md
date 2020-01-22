id: "incidentinvestigation"
name: "Incident Investigation"
---

 The ISM on call needs to review the incoming incident alert and quickly assign an initial incident classification based on the following framework:

Category:
a. Unauthorized access of the network
a. Malware
a. Denial of Service
a. Improper Usage by an IT administrator (accidentally or intentionally)
a. Unsuccessful Access Attempt

Type:
a. Targeted vs Opportunistic Threat
a. Advanced Persistent Threat
a. State Sponsored act of Espionage
a. Hacktivism Threat
a. Insider Threat

Severity
a. Critical Impact: Threat to public safety or life
a. High Impact: Threat to sensitive data
a. Moderate Impact: Threat to Computer Systems
a. Low Impact: Disruption of services

The following Incident Taxonomy can be used to help identify the root cause and trends as well as provide metrics for tracking for repeat events.

a. Direct Method:
  i. End User
  i. 3rd Party Service Provider
  i. Law Enforcement such as the FBI
  i. Data Loss Prevention system, Firewall, Anti-Virus, Proxy, and Netflow

a. Attack Vector
  i. Viruses
  i. Email attachments
  i. Web pages
  i. Pop-up windows
  i. Instant messages

a. Impact
  i. Employee Dismissal
  i. HR/ Ethics Violation
  i. Loss of Productivity
  i. Unauthorized Privileges
  i. Brand Image
  i. Lawsuit
  i. Denial of Service

a. Intent
  i. Malicious
  i. Theft
  i. Accidental
  i. Physical Damage
  i. Fraud
  i. Espionage

a. Root Cause
  i. Unauthorized Action
  i. Vulnerability Management
  i. Theft
  i. Security Control Failure/Gap
  i. Disregard of Policy
  i. User Negligence
  i. Non-Compliance to Standards such as PII, PCI, HIPPA
  i. Service Provider Negligence

Incident response should follow these 3 phases:
a. Triage
a. Containment and Neutralization
a. Post Incident

TRIAGE
As the investigation unfolds the ISM should focus on three primary areas:

a. Endpoint Analysis
  i. Determine what tracks may have been left behind by the threat actor.
  i. Gather the artifacts needed to build a timeline of activities.
  i. Analyze a bit-for-bit copy of systems from a forensic perspective and capture RAM to parse through and identify key artifacts to determine what occurred on a device.

a. Binary Analysis
  i. Investigate malicious binaries or tools leveraged by the attacker and document the functionalities of those programs. This analysis is performed in two ways.
    a. Behavioral Analysis: Execute the malicious program in a VM to monitor its behavior
    a. Static Analysis: Reverse engineer

a. Enterprise Hunting
  i. Analyze existing systems and event log technologies to determine the scope of compromise.
  i. Document all compromised accounts, machines, etc. so that effective containment and neutralization can be performed.

CONTAINMENT AND NEUTRALIZATION
This is one of the most critical stages of incident response. The strategy for containment and neutralization is based on the intelligence and indicators of compromise gathered during the analysis phase. After the system is restored and security is verified, normal operations can resume.

a. Coordinated Shutdown: Once you have identified all systems within the environment that have been compromised by a threat actor, perform a coordinated shutdown of these devices. A notification must be sent to all IR team members to ensure proper timing.

a. Wipe and Rebuild: Wipe the infected devices and rebuild the operating system from the ground up. Change passwords of all compromised accounts.

a. Threat Mitigation Requests: If you have identified domains or IP addresses that are known to be leveraged by threat actors for command and control, issue threat mitigation requests to block the communication from all egress channels connected to these domains.

POST-INCIDENT ACTIVITY
There is more work to be done after the incident is resolved. Be sure to properly document any information that can be used to prevent similar occurrences from happening again in the future.

a. Complete an Incident Report: Documenting the incident will help to improve the incident response plan and augment additional security measures to avoid such security incidents in the future.

a. Monitor Post-Incident: Closely monitor for activities post-incident since threat actors will re-appear again. We recommend a security log hawk analyzing SIEM data for any signs of indicators tripping that may have been associated with the prior incident.

a. Update Threat Intelligence: Update the organization’s threat intelligence feeds.

a. Identify preventative measures: Create new security initiatives to prevent future incidents.

a. Gain Cross-Functional Buy-In: Coordinating across the organization is critical to the proper implementation of new security initiatives.


Create an incident response investigation ticket and perform according to Incident Response Policy as well as:
- [ ] Verify and update as needed any incident information from the alert
- [ ] Create an official incident report
- [ ] Assign incident classification
- [ ] Provide details about incident using incident taxonomy
- [ ] Preserve evidence of incident
- [ ] Mitigate incident and notify personnel as needed of status
- [ ] Perform RCA (Root Cause Analysis)
- [ ] Update required personnel
- [ ] Prepare for post mortem