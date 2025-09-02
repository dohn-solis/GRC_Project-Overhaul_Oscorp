# Project Overhaul Maturity Assessment

---

## Asset Management

| Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|---|---|---|---|---|
| Identify/manage data, personnel, devices, systems, and facilities by importance to business/risk. | Physical device inventory. | 1. Is there an updated CMDB/asset list of all hardware? 2. Is periodic review done to keep the CMDB accurate? | Pass | IT team keeps a spreadsheet of laptop serials; SOE is used for imaging; periodic CMDB reviews needed. |
|  | Software inventory. | 1. Is there an updated CMDB/asset list of all software? 2. Is periodic review done to keep the CMDB accurate? | Fail |  |
|  | Map org communication and data flows. | 1. Are up-to-date network diagrams (including cloud) maintained? | Pass | Network diagrams are current and include cloud. |
|  | Catalogue external info systems. | 1. Are SaaS instances catalogued/classified in CMDB? 2. Is there an updated inventory of third-party suppliers? | Fail | No sensitivity/criticality classification in inventory. |
|  | Prioritize resources by classification, criticality, business value. | 1. Are CMDB assets classified by sensitivity/criticality? | Fail | Assets not classified by sensitivity/criticality. |
|  | Establish cyber roles/responsibilities for workforce/third-parties. | 1. Are cyber roles defined? 2. Is there a security policy for roles/responsibilities (including suppliers)? | Fail | Roles undefined; no security policy for cyber roles/responsibilities. |

---

## Business Environment

| Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|---|---|---|---|---|
| Understand/prioritize mission/objectives/stakeholders for cyber roles/risk management. | Identify org role in supply chain. | 1. Is supply chain role documented for cyber risk (mapping/classification of suppliers)? | Fail | No documentation or classification of supply chain cyber roles; no supplier risk process. |
|  | Identify org place in critical infrastructure/sector. | 1. Is org considered 'critical infrastructure'? If yes, document in security policy and inform stakeholders. | N/A | Not a critical infrastructure org. |
|  | Set/communicate priorities for mission/objectives/activities. | Does org have a clear business strategy and mission? | Pass | Strategy and mission statement exist. |
|  | Establish dependencies/critical functions for service delivery. | 1. Are key services/applications inventoried/classified? 2. Are BCP/DR plans in place for key services? | Fail | No classification of key services/applications; assets not classified; critical assets list missing. |
|  | Set resilience requirements for critical services. | 1. Do BCP/DR plans support critical service resilience? 2. Is due diligence (BCP, SLA, SOC) reviewed for third-party service resilience? | Pass | BCP/DR plans and due diligence support resilience for critical services and third-parties. |

---

## Governance

| Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|---|---|---|---|---|
| Manage/monitor compliance, legal, risk, and operational requirements for cyber risk. | Information security policy established. | Does org have a security policy? | Fail | No security policy exists. |
|  | Align info security roles/responsibilities with internal/external partners. | Are roles documented/communicated with stakeholders/suppliers? | Fail | Roles/responsibilities undefined; no cyber strategy. |
|  | Understand/manage legal/regulatory cyber/privacy requirements. | Are legal/regulatory responsibilities documented (privacy, cyber)? | Fail | No documentation of legal/regulatory cyber/privacy responsibilities. |
|  | Address cyber risk in governance/risk management processes. | 1. Are cyber risk processes/procedures established? 2. Does board oversee info security risks? | Fail | No cyber risk processes; no policies; board lacks visibility. |

---

## Risk Assessment

| Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|---|---|---|---|---|
| Understand cyber risks to operations/assets/people. | Document asset vulnerabilities. | Are vulnerability scans conducted, analyzed, and documented? | Fail | No formal vulnerability program; scans are ad-hoc with unclear coverage. |
|  | Receive threat/vulnerability intel. | Does vulnerability program include threat intel sources? | Fail | No program or threat intel subscriptions; no security team/function. |
|  | Identify/document internal/external threats. | 1. Are threat assessments done? 2. Are threat actors identified and documented? | Fail | No threat assessments or actor identification due to lack of strategy. |
|  | Identify business impacts/likelihoods. | Are impact/likelihood included in cyber risk assessments? | Fail | No cyber risk process. |
|  | Use threats, vulnerabilities, likelihoods, impacts to determine risk. | Does risk assessment identify threats/vulnerabilities, likelihood/damage, and control sufficiency? | Fail | No risk process. |
|  | Prioritize risk responses. | Are assessment recommendations prioritized by business impact? | Fail | No risk process. |

---

## Risk Management Strategy

| Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|---|---|---|---|---|
| Set priorities, constraints, tolerances, and assumptions for risk decisions. | Stakeholders agree/manage risk processes. | Has risk management process been endorsed by senior management? | Fail | No cyber strategy in place, so not endorsed. |
|  | Express organizational risk tolerance. | Is there a defined/approved cyber risk appetite statement? | Fail | No strategy/risk process; no statement exists. |
|  | Determine risk tolerance based on critical infrastructure/sector. | If critical infrastructure, is risk tolerance factored in? | N/A | Org is not critical infrastructure. |

---

## Response Planning

| Sub-Category | Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|---|---|---|---|---|---|
| Response Planning | Timely execution and maintenance of response processes/procedures. | Response plan executed during/after event. | 1. Are incident response plans in place and used during incidents? | Fail | No cyber response at Oscorp. |
| Communications | Coordinate response with internal/external stakeholders incl. law enforcement. | Staff know response roles/order. | 1. Do plans include contacts/escalation points? Are they tested? | Fail | No plans, contacts, escalation, or testing. |
|  |  | Events reported per criteria. | 1. Are incidents reported per threshold? How mature is process? | Fail | No incident reporting due to lack of response capability. |
|  |  | Info shared per response plans. | 1. Do plans include escalation, law enforcement involvement? | Fail | No incident response plans. |
|  |  | Coordination with stakeholders per plans. | 1. Do plans detail team coordination for escalated incidents? | Fail | No cyber response/plans. |
|  |  | Voluntary info sharing with external stakeholders. | 1. Is security intelligence shared with community/industry? | Fail | No strategy/process for sharing. |
| Analysis | Ensure adequate response and support recovery. | Investigate alerts from detection systems. | 1. Is there a process to respond to alerts? 2. Is there 24/7 coverage? | Fail | No SIEM or cyber strategy; only ad-hoc IT response. No 24/7 coverage. |
|  |  | Incident impact understood. | 1. Is impact/criticality documented during analysis? | Fail | No roles/strategy, so no documentation of impact. |
|  |  | Forensic capability. | 1. Can team perform digital forensics? | Fail | No cyber strategy, tools, or skills for forensics. Ad-hoc vulnerability scans only. |
|  |  | Incidents categorized per response plans. | 1. Are incidents prioritized by criticality in response plans? | Fail | No detection/response capability. |
| Mitigation | Prevent event expansion, mitigate effects, eradicate incident. | Incidents contained. | 1. Do plans ensure containment (e.g., SANS template)? | Fail | No response plans. |
|  |  | Incidents mitigated. | 1. Do plans ensure incident mitigation (e.g., SANS template)? | Fail | No mitigation standards/plans. |
|  |  | New vulnerabilities managed/documented as accepted risk. | 1. Is there a program for new vulnerabilities incl. zero-days? | Fail | No vulnerability management program. |
| Improvements | Incorporate lessons learned into response activities. | Plans include lessons learned. | 1. Do plans include 'lessons learned'? | Fail | No response plans, thus no lessons learned step. |
|  |  | Response strategies updated. | 1. Are plans periodically tested/updated? | Fail | No incident response plans to test/update. |

---

## Recovery Planning

| Sub-Category | Control Objective | Control Description | Questions to Ask | Pass/Fail | Comments |
|---|---|---|---|---|---|
| Recovery Planning | Timely restoration of affected systems/assets. | Recovery plan executed during/after event. | 1. Is there a disaster recovery plan? Has it been tested? | Pass | Disaster recovery is tested regularly. Backups are taken and tested periodically. |
| Improvements | Plans/processes improved by lessons learned. | Recovery plans include lessons learned. | 1. Do recovery plans include 'lessons learned'? | Pass | No 'lessons learned' step included in DR plans. |
|  |  | Recovery strategies updated. | 1. Is disaster recovery tested/updated regularly? | Pass | Testing and regular updates occur for DR plans. |
|  |  | Reputation repaired after event. | 1. Are reputation mitigation steps included? | Fail | No mitigating steps for reputation in DR plans. |
| Communications | Coordinate restoration activities with internal/external parties. | Public relations managed. | 1. Is communication improved during DR testing? | N/A |  |
|  |  | Internal comms/escalation for recovery. | 1. Are there clear comms/escalation points in DR plans? | Fail | No clear communication/escalation points in DR plans.