---
title: Change Management and Control Policy
description: Data Migrators' Change Management and Control Policy
keywords: 'change,control,management,policy'
---

<PageDescription>

This page describes Data Migrators’ policy on change management and control.

</PageDescription>

<AnchorLinks>
  <AnchorLink>Overview</AnchorLink>
  <AnchorLink>Purpose</AnchorLink>
  <AnchorLink>Scope</AnchorLink>
  <AnchorLink>Policy</AnchorLink>
  <AnchorLink>Operational Procedures</AnchorLink>
  <AnchorLink>Documented Change</AnchorLink>
  <AnchorLink>Risk Management</AnchorLink>
  <AnchorLink>Change Classification</AnchorLink>
  <AnchorLink>Testing</AnchorLink>
  <AnchorLink>Changes Affecting SLA‘s</AnchorLink>
  <AnchorLink>Version Control</AnchorLink>
  <AnchorLink>Approval</AnchorLink>
  <AnchorLink>Communicating Changes</AnchorLink>
  <AnchorLink>Implementation</AnchorLink>
  <AnchorLink>Fall Back</AnchorLink>
  <AnchorLink>Documentation</AnchorLink>
  <AnchorLink>Business Continuity Plans (BCP)</AnchorLink>
  <AnchorLink>Change Monitoring</AnchorLink>
  <AnchorLink>Roles And Responsibilities</AnchorLink>
  <AnchorLink>Policy Compliance</AnchorLink>
  <AnchorLink>Exceptions</AnchorLink>
  <AnchorLink>Non-compliance</AnchorLink>
  <AnchorLink>Related Documents</AnchorLink>
  <AnchorLink>Definitions and Terms</AnchorLink>
</AnchorLinks>

## Overview

Operational change management brings discipline and quality control to IS. Attention to governance and formal policies and procedures will ensure its success. Adopting formalised governance and policies for operational change management delivers a more disciplined and efficient infrastructure. This formalisation requires communication; the documentation of important process workflows and personnel roles; and the alignment of automation tools, where appropriate. Where change management is non-existent, it is incumbent on IS’s senior management to provide the leadership and vision to jump-start the process. By defining processes and policies, IS organisations can demonstrate increased agility in responding predictably and reliably to new business demands.

Data Migrators' management has recognised the importance of change management and control and the associated risks with ineffective change management and control and have therefore formulated this Change Management and Control Policy in order to address the opportunities and associated risks.

## Purpose

The purpose of this policy is to establish management direction and high-level objectives for change management and control. This policy will ensure the implementation of change management and control strategies to mitigate associated risks such as:

- Information being corrupted and/or destroyed;
- Computer performance being disrupted and/or degraded;
- Productivity losses being incurred; and 
- Exposure to reputational risk.

## Scope

This policy applies to all parties operating within the company’s network environment or utilising Information Resources.  It covers the data networks, LAN servers and personal computers (stand-alone or network-enabled), located at company offices and company production related locations, where these systems are under the jurisdiction and/or ownership of the company or subsidiaries, and any personal computers, laptops, mobile device and or servers authorised to access the company’s  data networks. No employee is exempt from this policy.

## Policy

Changes to information resources shall be managed and executed according to a formal change control process.  The control process will ensure that changes proposed are reviewed, authorised, tested, implemented, and released in a controlled manner; and that the status of each proposed change is monitored.

In order to fulfil this policy, the following statements shall be adhered to:

### Operational Procedures

The change control process shall be formally defined and documented. A change control process shall be in place to control changes to all critical company information resources (such as hardware, software, system documentation and operating procedures).  This documented process shall include management responsibilities and procedures.  Wherever practicable, operational and application change control procedures should be integrated.

At a minimum the change control process should include the following phases:

- Logged Change Requests;
- Identification, prioritisation and initiation of change;
- Proper authorisation of change;
- Requirements analysis;
- Inter-dependency and compliance analysis;
- Impact Assessment;
- Change approach;
- Change testing;
- User acceptance testing and approval;
- Implementation and release planning;
- Documentation;
- Change monitoring;
- Defined responsibilities and authorities of all users and IT personnel;
- Emergency change classification parameters.

### Documented Change

All change requests shall be logged whether approved or rejected on a standardised and central system. The approval of all change requests and the results thereof shall be documented. 
A documented audit trail, maintained at a Business Unit Level, containing relevant information shall be maintained at all times.  This should include change request documentation, change authorisation and the outcome of the change.  No single person should be able to effect changes to production information systems without the approval of other authorised personnel.

### Risk Management

A risk assessment shall be performed for all changes and dependant on the outcome, an impact assessment should be performed.
The impact assessment shall include the potential effect on other information resources and potential cost implications. The impact assessment should, where applicable consider compliance with legislative requirements and standards. 

### Change Classification

All change requests shall be prioritised in terms of benefits, urgency, effort required and potential impact on operations. 

### Testing

Changes shall be tested in an isolated, controlled, and representative environment (where such an environment is feasible) prior to implementation to minimise the effect on the relevant business process, to assess its impact on operations and security and to verify that only intended and approved changes were made. 

### Changes Affecting SLA‘s

The impact of change on existing SLA’s shall be considered. Where applicable, changes to the SLA shall be controlled through a formal change process which includes contractual amendments. 

### Version Control

Any software change and/or update shall be controlled with version control using the Git versioning system. Older versions shall be retained in accordance with corporate retention and storage management policies. 

### Approval

All changes shall be approved prior to implementation. Approval of changes shall be based on formal acceptance criteria i.e. the change request was done by an authorised user, the impact assessment was performed, and proposed changes were tested. 

### Communicating Changes

All users, significantly affected by a change, shall be notified of the change.  The user representative shall sign-off on the change. Users shall be required to make submissions and comment prior to the acceptance of the change.

### Implementation

Implementation will only be undertaken after appropriate testing and approval by stakeholders. All major changes shall be treated as new system implementation and shall be established as a project. Major changes will be classified according to effort required to develop and implement said changes.

### Fall Back

Procedures for aborting and recovering from unsuccessful changes shall be documented. Should the outcome of a change be different to the expected result (as identified in the testing of the change), procedures and responsibilities shall be noted for the recovery and continuity of the affected areas. Fall back procedures will be in place to ensure systems can revert back to what they were prior to implementation of changes.

### Documentation

Information resources documentation shall be updated on the completion of each change and old documentation shall be archived or disposed of as per the documentation and data retention policies.
Information resources documentation is used for reference purposes in various scenarios i.e. further development of existing information resources as well as ensuring adequate knowledge transfer in the event of the original developer and/or development house being unavailable.  It is therefore imperative that information resources documentation is complete, accurate and kept up to date with the latest changes. Policies and procedures, affected by software changes, shall be updated on completion of each change. 

### Business Continuity Plans (BCP)

Business continuity plans shall be updated with relevant changes, managed through the change control process. Business continuity plans rely on the completeness, accuracy and availability of BCP documentation.  BCP documentation is the road map used to minimise disruption to critical business processes where possible, and to facilitate their rapid recovery in the event of disasters.  


### Change Monitoring

All changes will be monitored once they have been rolled-out to the production environment. Deviations from design specifications and test results will be documented and escalated to the solution owner for ratification.  


## Roles And Responsibilities

+------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Role                         | Functional Responsibilities                                                                                                                                                                  |
+==============================+==============================================================================================================================================================================================+
| Members of the Board         | - Members of the Board shall ensure that the necessary information security controls are implemented and complied with as per this policy.                                                   |
+------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Information Security Manager | - Establish and revise the information security strategy, policy and standards for change management and control with input from interest groups and subsidiaries;                           |
|                              | - Facilitate and co-ordinate the necessary counter measures to change management and control initiatives and evaluate such policies and standards;                                           |
|                              | - Establish the security requirements for change management and control directives and approval of the change management and control standards and change control/ version control products; |
|                              | - Co-ordinate the overall communication and awareness strategy for change management;                                                                                                        |
|                              | - Acts as the management champion for change management and control;                                                                                                                         |
|                              | - Provide technical input to the service requirements and co-ordinate affected changes to SLA’s where applicable.                                                                            |
|                              | - Establish and co-ordinate appropriate interest group forums to represent, feedback, implement and monitor change management and control initiatives; and                                   |
|                              | - Co-ordinate the implementation of new or additional security controls for change management.                                                                                               |
+------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Operations Manager           | - Implement, maintain and update the change management and control strategy, baselines, standards, policies and procedures with input from all stakeholders;                                 |
|                              | - Approve and authorise change management and control measures on behalf of the Data Migrators;                                                                                              |
|                              | - Ensure that all application owners are aware of the applicable policies, standards, procedures and guidelines for change management and control;                                           |
|                              | - Ensure that policy, standards and procedural changes are communicated to applicable owners and management forums;                                                                          |
|                              | - Appoint the necessary representation to the interest groups and other forums created by each company for Information Security Management relating to change management and control;        |
|                              | - Establish and revise the information security strategy, policy and standards for change management and control;                                                                            |
|                              | - Facilitate and co-ordinate the necessary change management and control initiatives within each company;                                                                                    |
|                              | - Report and evaluate changes to change management and control policies and standards;                                                                                                       |
|                              | - Co-ordinate the overall communication and awareness strategy for change management and control;                                                                                            |
|                              | - Co-ordinate the implementation of new or additional security controls for change management and control                                                                                    |
|                              | - Review the effectiveness of  change management and control strategy and implement remedial controls where deficits are identified;                                                         |
|                              | - Provide regular updates on change management and control initiatives and the suitable application;                                                                                         |
|                              | - Evaluate and recommend changes to change management/ version control solutions; and                                                                                                        |
|                              | - Co-ordinate awareness strategies and rollouts to effectively communicate change management and control mitigation solutions in each company.                                               |
|                              | - Establish and implement the necessary standards and procedures that conform to the Information Security policy;                                                                            |
|                              | - Responsible for approving, authorising, monitoring and enforcing change management initiatives and related security controls within all Data Migrators companies and divisions;            |
|                              | - Ensure that all solution owners are aware of policies, standards, procedures and guidelines for change management and control.                                                             |
|                              | - Ensure the compliance of this policy and report deviations to the Information Manager                                                                                                      |
+------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| IT Service Providers         | - Shall provide support for all change management and control statements of this policy.                                                                                                     |
+------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Solution Owners              | - Shall comply with all information security policies, standards and procedures for change management and control; and                                                                       |
|                              | - Report all deviations.                                                                                                                                                                     |
+------------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+


## Policy Compliance

See Policy.


## Exceptions

Specific procedures to ensure the proper control, authorisation, and documentation of emergency changes shall be in place. Specific parameters will be defined as a standard for classifying changes as Emergency changes.

## Non-compliance

Any person, subject to this policy, who fails to comply with the provisions as set out above or any amendment thereto, shall be subjected to appropriate disciplinary or legal action in accordance with the Data Migrators Disciplinary Code and Procedures. Company Information Security policies, standards, procedures and guidelines shall comply with legal, regulatory and statutory requirements.


## Related Documents

The following documents contain provisions that, through reference in the text, constitute requirements of this policy.  At the time of publication, the editions indicated were valid.  All standards and specifications are subject to revision, and parties to agreements based on this policy are encouraged to investigate the possibility of applying the most recent editions of the documents listed below.  

- [Disaster Recovery Plan Policy](disaster_recovery_plan_policy)
- [Information Lifecycle Management Policy](information_lifecycle_management_policy)
- [Server Security Poplicy](server_security_policy)
- [Software Installation Policy](software_installation_policy)

## Definitions and Terms

#### Audit Trail

A record or series of records which allows the processing carried out by a computer system to be accurately identified, as well as verifying the authenticity of such amendments.

#### Information Resources

All data, information as well as the hardware, software, personnel and processes involved with the storage, processing and output of such information.  This includes data networks, servers, PC's, storage media, printer, photo copiers, fax machines, supporting equipment, fall-back equipment and back-up media.

#### Abbreviations

- PC:  Personal Computer
- BCP: Business Continuity Plan
- SLA: Service Level Agreement

