# Introduction 

For this assignment, I was tasked to create an internal security audit based on the following fictional company and scenario. Next, I was tasked to clearly and concisely communicate my findings to the IT manager and stakeholders. 


# Tasks

“Your task is to review the IT manager’s scope, goals, and risk assessment. Then, perform an internal audit to complete a controls assessment and compliance checklist.”

“Your task is to clearly and concisely communicate your findings and recommendations to the IT manager and other stakeholders, so they can implement the necessary controls and create appropriate documentation, processes, and procedures to ensure business continuity, the safety of critical assets, and compliance.” 


# Scenario 

“Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location. However, its online presence has grown, attracting customers in the U.S. and abroad. Their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, and completing a risk assessment. The goal of the audit is to provide an overview of the risks the company might experience due to the current state of their security posture. The IT manager wants to use the audit findings as evidence to obtain approval to expand his department. 

Your task is to review the IT manager’s scope, goals, and risk assessment. Then, perform an internal audit to complete a controls assessment and compliance checklist.”


# Controls Assessment 


## Current assets

Assets managed by the IT Department include: 



* On-premises equipment for in-office business needs  
* Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
* Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
* Internet access
* Internal network
* Vendor access management
* Data center hosting services  
* Data retention and storage
* Badge readers
* Legacy system maintenance: end-of-life systems that require human monitoring_ _

<table>
  <tr>
   <td colspan="4" >
<strong>Administrative Controls</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Control Name</strong>
   </td>
   <td><strong>Control type and explanation</strong>
   </td>
   <td><strong>Needs to be implemented (X)</strong>
   </td>
   <td><strong>Priority</strong>
   </td>
  </tr>
  <tr>
   <td>Least Privilege
   </td>
   <td>Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Disaster recovery plans
   </td>
   <td>Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Password policies
   </td>
   <td>Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Access control policies
   </td>
   <td>Preventative; increase confidentiality and integrity of data
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Account management policies
   </td>
   <td>Preventative; reduce attack surface and limit overall impact from disgruntled/former employees
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Separation of duties
   </td>
   <td>Preventative; ensure no one has so much access that they can abuse the system for personal gain
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
</table>



<table>
  <tr>
   <td colspan="4" ><strong>Technical Controls</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Control Name</strong>
   </td>
   <td><strong>Control type and explanation</strong>
   </td>
   <td><strong>Needs to be implemented</strong>
<p>
<strong>(X)</strong>
   </td>
   <td><strong>Priority</strong>
   </td>
  </tr>
  <tr>
   <td>Firewall
   </td>
   <td>Preventative; firewalls are already in place to filter unwanted/malicious traffic from entering internal network
   </td>
   <td>NA
   </td>
   <td>NA
   </td>
  </tr>
  <tr>
   <td>Intrusion Detection System (IDS)
   </td>
   <td>Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Encryption
   </td>
   <td>Deterrent; makes confidential information/data more secure (e.g., website payment transactions)
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Backups
   </td>
   <td>Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Password management system
   </td>
   <td>Corrective; password recovery, reset, lock out notifications
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Antivirus (AV) software
   </td>
   <td>Corrective; detect and quarantine known threats
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Manual monitoring, maintenance, and intervention
   </td>
   <td>Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
</table>



<table>
  <tr>
   <td colspan="4" ><strong>Physical Controls</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Control Name</strong>
   </td>
   <td><strong>Control type and explanation</strong>
   </td>
   <td><strong>Needs to be implemented</strong>
<p>
<strong>(X)</strong>
   </td>
   <td><strong>Priority</strong>
   </td>
  </tr>
  <tr>
   <td>Time-controlled safe
   </td>
   <td>Deterrent; reduce attack surface/impact of physical threats
   </td>
   <td>X
   </td>
   <td>Medium/
<p>
Low
   </td>
  </tr>
  <tr>
   <td>Adequate lighting
   </td>
   <td>Deterrent; limit “hiding” places to deter threats
   </td>
   <td>X
   </td>
   <td>Medium/
<p>
Low
   </td>
  </tr>
  <tr>
   <td>Closed-circuit television (CCTV) surveillance
   </td>
   <td>Preventative/detective; can reduce risk of certain events; can be used after event for investigation
   </td>
   <td>X
   </td>
   <td>High/
<p>
Medium
   </td>
  </tr>
  <tr>
   <td>Locking cabinets (for network gear) 
   </td>
   <td>Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear
   </td>
   <td>X
   </td>
   <td>Medium
   </td>
  </tr>
  <tr>
   <td>Signage indicating alarm service provider
   </td>
   <td>Deterrent; makes the likelihood of a successful attack seem low
   </td>
   <td>X
   </td>
   <td>Low
   </td>
  </tr>
  <tr>
   <td>Locks
   </td>
   <td>Preventative; physical and digital assets are more secure
   </td>
   <td>X
   </td>
   <td>High
   </td>
  </tr>
  <tr>
   <td>Fire detection and prevention (fire alarm, sprinkler system, etc.)
   </td>
   <td>Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc.
   </td>
   <td>X
   </td>
   <td>Medium/
<p>
Low
   </td>
  </tr>
</table>



# Compliance Checklist



1. **General Data Protection Regulation (GDPR)**

    GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. citizens’ data and their right to privacy in and out of E.U. territory. Additionally, if a breach occurs and a E.U. citizen’s data is compromised, they must be informed within 72 hours of the incident.


    **Explanation: **Botium Toys needs to adhere to GDPR because they conduct business and collect personal information from people worldwide, including the E.U.

1. **Payment Card Industry Data Security Standard (PCI DSS)**

    PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment. 


    **Explanation: **Botium Toys needs to adhere to PCI DSS because they store, accept, process, and transmit credit card information in person and online.

1. **System and Organizations Controls (SOC type 1, SOC type 2)**

    The SOC1 and SOC2 are a series of reports that focus on an organization's user access policies at different organizational levels. They are used to assess an organization’s financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.


    **Explanation: **Botium Toys needs to establish and enforce appropriate user access for internal and external (third-party vendor) personnel to mitigate risk and ensure data safety.



# Stakeholder memorandum

TO: IT Manager, stakeholders

FROM: Mark Gonzalez

DATE: 8/9/2023

SUBJECT: Internal IT audit findings and recommendations

Dear Colleagues,

Please review the following information regarding the Botium Toys internal audit scope, goals, critical findings, summary, and recommendations.

Scope:



* The following systems are in scope: accounting, endpoint detection, firewalls, intrusion detection system, security information, and event management (SIEM) tool. The systems will be evaluated for:
    * Current user permissions
    * Current implemented controls
    * Current procedures and protocols
* Ensuring current user permissions, controls, procedures, and protocols in place align with GDPR, PCI DSS, and compliance requirements
* Ensure current technology and assets are accounted for both hardware and system access.

Goals:



* Adhere to the NIST CSF.
* Establish a better process for their systems to ensure they are compliant
* Fortify system controls
* Implement the concept of least permissions when it comes to user credential management
* Establish their policies and procedures, which include their playbooks

Critical findings (must be addressed immediately):

Multiple controls need to be developed and implemented to meet the audit goals, including



* Principle of Least Privilege and Separation of duties
* Disaster recovery plans
* Password, Access control, and Account management policies
* Intrusion Detection System (IDS)
* Encryption (secure website transactions wand disk drive(s) containing sensitive information)
* Backups
* Implementation of a Password management system
* Antivirus (AV) software
* Manual monitoring, maintenance, and intervention for legacy systems
* Closed-circuit television (CCTV) surveillance
* Locks
* Locking cabinets (for network gear)
* Fire detection and prevention (fire alarm, sprinkler system, etc.)
* Policies need to be developed and implemented for the following:
    * To meet PCI DSS and GDPR compliance requirements.
    * To meet SOC1 and SOC2 guidance related to user access policies and overall data safety.

Findings (should be addressed, but no immediate need):

The following physical controls should be considered in the future once the critical findings have been resolved:



* Time-controlled safe
* Adequate lighting
* Signage indicating alarm service provider for restricted areas

Summary/Recommendations:

It is recommended that the critical findings relating to compliance with PCI and GDPR be promptly addressed as Botium Toys accepts online payments is expanding to offer services and handle the data of customers abroad including the European Union. SOC1 and SOC2 guidance related to user access policies should be used to align with the audit goal to adapt to the concept of least permissions to develop the policies and procedures needed to be compliant.

Disaster recovery plans and backups are recommended as they will support business continuity in the event of an incident occurring ranging from a physical disaster such as a fire, to or worst-case scenario of a cyber attack or technical issue impacting business productivity as a part of a data and system resilience strategy. A method of fire detection and prevention systems is worth consideration for protecting against physical attacks.

Integrating IDS and AV software into current systems will give the ability to assist with intrusion detection and spot and mitigate potential risks while taking into account the existing legacy systems that need manual monitoring and intervention.

To secure assets at Botium Toys' physical location, locks, and CCTV should be used to secure physical assets and to monitor for potential threats. Having a time-controlled safe, adequate lighting, and signage indicating the alarm service provider will further improve Botium Toys' security posture.


Integrating IDS and AV software into current systems will give the ability to assist with intrusion detection and spot and mitigate potential risks while taking into account the existing legacy systems that need manual monitoring and intervention.

To secure assets at Botium Toys' physical location, locks, and CCTV should be used to secure physical assets and to monitor for potential threats. Having a time-controlled safe, adequate lighting, and signage indicating the alarm service provider will further improve Botium Toys' security posture.
