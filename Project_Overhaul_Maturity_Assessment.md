# Asset Management
*Identify and manage assets critical to business objectives and risk strategy.*

| Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|-------------------|--------------------|------------------|-----------|----------|
| Physical devices and systems inventoried | Are all physical (hardware) devices tracked in an up-to-date CMDB or asset inventory? | 1. Is the CMDB/spreadsheet current? 2. Are periodic reviews done? | Pass | IT team maintains laptop inventory and SOE imaging; CMDB needs regular reviews. |
| Software platforms inventoried | Are software assets tracked in CMDB? | 1. Is software asset inventory current? 2. Are periodic reviews done? | Fail |  |
| Communication/data flows mapped | Are network diagrams (including cloud) clear and current? | 1. Are diagrams up to date? | Pass | Yes, diagrams are up to date. |
| External information systems catalogued | Are SaaS instances and third-party suppliers inventoried/classified? | 1. Is SaaS catalogued/classified? 2. Are suppliers inventoried? | Fail | No classification for sensitivity/criticality. |
| Resources prioritized by classification/criticality/value | Are assets classified by sensitivity/criticality? | 1. Are assets classified? | Fail | Not classified in CMDB. |
| Cybersecurity roles/responsibilities established | Are roles/responsibilities defined and policy in place (including third parties)? | 1. Are roles defined? 2. Is policy in place? | Fail | Roles undefined; no policy for roles/responsibilities. |

# Business Environment
*Understand mission, objectives, stakeholders, and use this to inform cyber roles and risk.*

| Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|-------------------|--------------------|------------------|-----------|----------|
| Role in supply chain identified | Is there documentation of the organization's supply chain role and supplier classification? | 1. Is supply chain role documented? | Fail | No documentation or classification; no supplier risk process. |
| Critical infrastructure/sector identified | Is the organization 'critical infrastructure'? | 1. Is this documented and communicated to stakeholders? | N/A | Not a critical infrastructure organization. |
| Priorities/mission/objectives communicated | Are strategy and mission statement clear? | 1. Is business strategy clear? | Pass | Clear strategy and mission statement. |
| Critical services dependencies established | Are critical services/applications inventoried/classified; BCP/DRP in place? | 1. Are critical services classified? 2. Are plans in place? | Fail | No inventories/classification; assets should be classified. |
| Resilience requirements for critical services | Do BCP/DRP support resilience? Is due diligence on third parties done? | 1. Do plans support resilience? 2. Is due diligence done? | Pass | Yes, BCP/DRP and due diligence are in place. |

# Governance
*Policies, procedures, processes to manage and monitor risk requirements.*

| Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|-------------------|--------------------|------------------|-----------|----------|
| Information security policy established | Is there an information security policy? | 1. Is policy in place? | Fail | No information security policy. |
| Security roles/responsibilities coordinated | Are roles documented/communicated internally and externally? | 1. Are roles documented and communicated? | Fail | Roles not defined; no cyber strategy. |
| Legal/regulatory requirements understood | Are legal/regulatory responsibilities documented? | 1. Is documentation in place? | Fail | No documentation. |
| Governance/risk processes address cyber risk | Are processes mature? Does board have oversight? | 1. Are processes mature? 2. Does board oversee? | Fail | No processes/policy; board has no visibility. |

# Risk Assessment
*Understand risk to operations, assets, and individuals.*

| Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|-------------------|--------------------|------------------|-----------|----------|
| Asset vulnerabilities identified/doc'd | Are vulnerability scans performed and documented? | 1. Are scans regular and documented? | Fail | No formal program; scans ad-hoc. |
| Threat/vulnerability info received | Is threat intelligence received via subscriptions/forums? | 1. Are subscriptions active? | Fail | No program or subscriptions; no cyber team. |
| Threats identified/doc'd | Have threat assessments/actor identification been performed? | 1. Are threats/actors assessed/documented? | Fail | No threat assessments or documentation. |
| Business impacts/likelihoods identified | Are impact/likelihood included in risk assessments? | 1. Are impacts/likelihood assessed? | Fail | No cyber risk process. |
| Threats/vulnerabilities/likelihood/impact used for risk | Does risk assessment process consider these factors? | 1. Are factors considered in risk assessment? | Fail | No risk process. |
| Risk responses identified/prioritized | Are recommendations prioritized by criticality/impact? | 1. Are outcomes prioritized? | Fail | No risk process. |

# Risk Management Strategy
*Organization’s priorities, constraints, risk tolerances support operational decisions.*

| Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|-------------------|--------------------|------------------|-----------|----------|
| Risk management process endorsed | Is process endorsed by senior management? | 1. Is process endorsed? | Fail | No cyber strategy. |
| Risk tolerance expressed | Is cyber risk appetite statement defined/approved? | 1. Is risk appetite statement approved? | Fail | No strategy or statement. |
| Risk tolerance informed by infrastructure/sector analysis | If critical infrastructure, is risk tolerance adjusted? | 1. Is sector considered in risk tolerance? | N/A | Not a critical infrastructure. |

# Response Planning
*Response processes and procedures are executed and maintained to ensure timely response to detected cybersecurity events.*

| Sub-Category | Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|--------------|------------------|--------------------|------------------|-----------|----------|
| Response Planning | Response plan is executed | Incident response plans exist and are used during incidents? | Fail | No cyber security response in place at Oscorp. |

# Response Communications
*Response activities coordinated with stakeholders, including law enforcement.*

| Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|------------------|--------------------|------------------|-----------|----------|
| Personnel roles known for response | Clear contact details and escalation points in incident plans? Tested? | Fail | No incident response plans; no contact details, escalation, or testing. |
| Events reported per criteria | Incidents reported as per threshold? Response maturity? | Fail | Incidents not reported per threshold; no response capability. |
| Information shared per plans | Do plans include escalation and law enforcement involvement? | Fail | No incident response plans exist. |
| Stakeholder coordination | Do plans detail how teams coordinate for escalated incidents? | Fail | No response plans in place. |
| Voluntary info sharing | Is info security intelligence shared with peers/community? | Fail | No strategy or risk process; no sharing. |

# Response Analysis
*Analysis ensures adequate response and supports recovery activities.*

| Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|------------------|--------------------|------------------|-----------|----------|
| Notifications investigated | Clear process to respond to alerts? 24/7 coverage? | Fail | No SIEM, no strategy, only ad-hoc AV responses; no 24/7 coverage. |
| Impact understood | Is incident impact/criticality documented? | Fail | No roles defined, no strategy, no documentation. |
| Forensics performed | Team has forensics capability/tools? | Fail | No strategy, no proper tools, only ad-hoc vulnerability scans. |
| Incidents categorized | Are response plans structured to prioritize incidents? | Fail | No detection or response capabilities. |

# Response Mitigation
*Prevent event expansion, mitigate effects, eradicate incidents.*

| Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|------------------|--------------------|------------------|-----------|----------|
| Incidents contained | Do response plans ensure containment (e.g., SANS template)? | Fail | No response plans at Oscorp. |
| Incidents mitigated | Do plans ensure incident mitigation as needed? | Fail | No response plans or standards. |
| Vulnerabilities managed | Is there a program to handle new/zero-day vulnerabilities? | Fail | No formal vulnerability management program. |

# Response Improvements
*Response activities improved using lessons learned.*

| Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|------------------|--------------------|------------------|-----------|----------|
| Lessons learned | Do plans include a "lessons learned" step? | Fail | No response plans; no lessons learned step. |
| Response updated | Are plans periodically tested and updated? | Fail | No plans to test or update. |

# Recovery Planning
*Processes and procedures for restoration of systems/assets after cybersecurity events.*

| Sub-Category        | Control Objective                      | Control Description                | Questions to Ask                                                                 | Pass/Fail | Comments                                                                                           |
|---------------------|----------------------------------------|------------------------------------|----------------------------------------------------------------------------------|-----------|----------------------------------------------------------------------------------------------------|
| Recovery Planning   | Recovery plan is executed              | Are disaster recovery plans in place and tested?                                | Pass      | Disaster recovery testing is conducted regularly. DR is in place and tested; backups taken/tested. |

# Recovery Improvements
*Recovery planning/processes are improved using lessons learned.*

| Control Objective                      | Control Description        | Questions to Ask                         | Pass/Fail | Comments                                                      |
|----------------------------------------|---------------------------|------------------------------------------|-----------|---------------------------------------------------------------|
| Recovery plans incorporate lessons learned | Lessons learned in DR plans | Is there a "lessons learned" step?         | Pass      | No "lessons learned" step is included in DR plans.            |
| Recovery strategies updated            | DR plans tested/updated   | Are plans periodically tested and updated? | Pass      | Yes, periodic testing for DR plans; regularly updated.         |

# Recovery Communications
*Restoration activities coordinated with parties (ISPs, vendors, PR, CSIRTs).* 

| Control Objective                        | Control Description       | Questions to Ask                                     | Pass/Fail | Comments                                      |
|------------------------------------------|--------------------------|------------------------------------------------------|-----------|-----------------------------------------------|
| Public relations managed                 | PR improved in DR testing | Is communication improved as part of DR testing?      | N/A       |                                               |
| Reputation after event is repaired       | Crisis reputation steps   | Do DR plans include steps for reputation crisis?      | Fail      | No mitigating steps included in DR plans.      |
| Recovery activities communicated         | DR activities to execs    | Are communication/escalation points in DR plans?      | Fail      | No clear communication/escalation in DR plans. |