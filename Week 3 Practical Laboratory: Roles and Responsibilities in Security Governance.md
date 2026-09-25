# INTERNATIONAL CYBERSECURITY AND DIGITAL FORENSICS ACADEMY

## GRC102: INFORMATION SECURITY GOVERNANCE

### Week 3 Practical Laboratory: Roles and Responsibilities in Security Governance

| Field | Details |
|---------|---------|
| Full Name | Venesha Adhiambo Ochieng |
| Registration Number | C11/26/CGRCE/17566 |
| Email Address | c11.cgrce2617566@icdfa.edu.ng |
| Cohort / Batch | Cohort11 |
| Date Submitted | 25th September 2026 |

---

# Executive Summary

TechGlobal's security governance has not matured at the same pace as its growth. Security ownership, risk approval and operational decision-making are concentrated around the IT Director, business units make inconsistent local security decisions, formal governance committees and reliable escalation paths are absent and the CEO and Board have limited visibility into cyber risk.

This report, prepared in the role of Lead Security Governance Consultant, redesigns TechGlobal's governance model to separate oversight, executive accountability, security leadership, enterprise-risk challenge and technology delivery while preserving practical cross-functional decision-making. It establishes Board oversight, CEO accountability, CISO-led security governance, CRO-led enterprise-risk integration, a formal committee ecosystem, explicit role profiles and RACI assignments, three-level cyber-risk escalation, and segregation-of-duties controls scalable across TechGlobal's five offices.

The report is organized into six evidence bundles, matching the structure of the laboratory brief:

- Task 1 - Governance Architecture and Stakeholder Map.
- Task 2 - Governance Responsibility Matrix and Role Profiles.
- Task 3 - Security Governance Committee Ecosystem.
- Task 4 - RACI Accountability Matrix and Implementation Guide.
- Task 5 - Cyber-Risk Escalation Workflow and Thresholds.
- Task 6 - Segregation-of-Duties Register and Assurance Note.

Recognised governance references informing this design include COBIT 2019 (governance/management objective separation), ISO/IEC 27001:2022 Clause 5 (leadership and roles), the NACD Director's Handbook on Cyber-Risk Oversight, and the Three Lines Model (IIA, 2020), used throughout to justify the separation between operational security (first line), risk and compliance oversight (second line) and independent assurance (third line).

# Task 1 Governance Architecture and Stakeholder Map

The Board has asked you to replace the current informal model with a governance structure that connects operational security decisions to executive and Board oversight.

## 1.1 Identify at least five weaknesses in the current governance model and explain the business or risk consequence of each.

| Governance Weakness | Current-State Evidence / Description | Business / Risk Consequence | Recommended Governance Response |
|---------------------|--------------------------------------|-----------------------------|---------------------------------|
| 1. Concentration of authority in the IT Director | The IT Director effectively acts as security owner, operational decision-maker and risk approver, concentrating multiple governance and management responsibilities within one function. | Creates a segregation-of-duties conflict because the function implementing and operating controls may also influence the assessment and acceptance of the resulting risk. This reduces independent challenge and increases the possibility that material risks are overlooked or understated. | Establish a CISO-led security governance function and separate security oversight, technology implementation, independent risk challenge and formal risk acceptance. |
| 2. Absence of formal security governance committees | Security decisions are made through informal arrangements rather than defined cross-functional governance forums. | Decisions may be inconsistent, insufficiently documented or made without appropriate input from Risk, Legal, Finance, HR and Business Units. This can delay decision-making and weaken accountability, particularly during significant incidents. | Establish an Executive Security Council, a cross-functional Security Governance Committee, and appropriate specialized working groups with defined membership, authority, escalation routes and Terms of Reference. |
| 3. Weak executive and Board visibility and escalation | The CEO and Board receive limited visibility into cyber risk, and TechGlobal has no reliable escalation path or defined thresholds for material cyber-risk issues. | Material risks may not reach decision-makers with authority to challenge management, allocate resources or determine whether exposure exceeds risk appetite. This may also delay executive action during significant incidents. | Establish formal Operational → Executive → Material/Board escalation levels supported by defined thresholds, KRIs, dashboards, regular Board reporting and event-driven escalation for material risks. |
| 4. Inconsistent security governance across Business Units and offices | Business Unit leaders make local security decisions without a consistent enterprise-wide governance baseline. | Different offices may apply controls inconsistently, creating security gaps, fragmented ownership and difficulty establishing a reliable enterprise-wide view of cyber risk. It may also complicate consistent compliance with organizational and regulatory requirements. | Establish enterprise-wide security policies, standards and minimum control requirements, while retaining Business Unit ownership for local implementation and risks within delegated authority. |
| 5. Absence of independent risk challenge and assurance | Cybersecurity operations, control ownership and risk-related authority are heavily concentrated within IT, with no clearly established independent challenge mechanism. | Risks may be assessed primarily from an operational IT perspective without sufficient independent challenge. Control weaknesses may therefore remain unidentified or unresolved, reducing management and Board confidence in the organization’s risk position. | Strengthen the CRO/Risk function to provide independent risk challenge, separate operational control ownership from risk acceptance, and use Internal Audit for independent assurance over governance and control effectiveness. |

## 1.2 Create a stakeholder map showing the interests, authority, information needs and expected contribution of the Board, CEO, CISO, CRO/Risk, Legal, Finance, HR, IT and Business Units.

| Stakeholder | Authority | Interest | Information Needs | Expected Contribution |
|------------|-----------|----------|------------------|----------------------|
| Board of Directors | High - provides ultimate governance oversight and approves enterprise risk appetite and reserved material-risk decisions. | Regulatory exposure, reputation, resilience, material cyber risk and assurance. | Enterprise cyber-risk posture, KRIs, material incidents, risk-appetite breaches and significant assurance findings. | Sets risk appetite, provides oversight and challenges, holds executive management accountable and reviews material cyber risks. |
| CEO | High - holds overall executive accountability for implementation of the organization’s strategy and governance direction. | Strategic alignment, growth, acceptable risk, resilience and business performance. | Enterprise risk profile, material incidents, unresolved risks, major investment requirements and Executive Security Council decisions. | Ensures cybersecurity aligns with business strategy, holds executives accountable and resolves material issues within delegated executive authority. |
| CISO | High (delegated) - leads enterprise security governance. | Security strategy, policy, cyber-risk oversight, control effectiveness and programme performance. | Threat and risk trends, incident information, control performance, vulnerabilities, exceptions, remediation status and assurance findings. | Leads cybersecurity strategy and governance, develops security policies and standards, challenges control weaknesses, chairs the Security Governance Committee and reports cyber risk to executive management and the Board. |
| CRO / Risk | High (delegated) - leads enterprise risk integration and independent risk challenge. | Risk methodology, risk appetite, treatment, acceptance criteria and enterprise risk aggregation. | Cyber-risk assessments, residual risk, exceptions, loss exposure, treatment plans and assurance results. | Integrates cybersecurity into enterprise risk management, maintains appropriate risk governance processes and independently challenges material cyber-risk assessments and acceptance decisions. |
| Legal / Compliance | Medium–High - provides authoritative legal, regulatory and compliance advice. | Regulatory obligations, privacy, contracts, evidence preservation and breach notification. | Incident facts, affected data, jurisdiction, contractual obligations and regulatory exposure. | Advises on legal and regulatory requirements, determines applicable notification obligations, supports evidence handling and coordinates regulatory engagement. |
| Finance | Medium–High - exercises financial governance and significant influence over security investment. | Budget, financial exposure, investment prioritization and financial controls. | Security investment cases, quantified risk exposure, incident financial impact and remediation costs. | Evaluates financial impact, supports risk-based security investment and ensures security expenditure is aligned with approved organizational priorities. |
| Human Resources | Medium - leads people-related governance and workforce controls. | Joiner/mover/leaver controls, security awareness, employee conduct and disciplinary processes. | Awareness metrics, personnel-related risk cases, access lifecycle exceptions and disciplinary trends. | Governs workforce security processes, coordinates awareness and training, supports insider-risk investigations and manages appropriate disciplinary actions. |
| IT / Technology | Medium–High (operational) - responsible for technology delivery and operation of technical controls. | Secure technology operations, system availability, control implementation and service continuity. | Approved security policies and standards, architecture requirements, vulnerability information, incidents and remediation priorities. | Implements and operates technical security controls, remediates vulnerabilities, supports incident response and maintains technology resilience and continuity. |
| Business Unit Leaders | Medium–High (business/local) - own operational activities and associated business risks within delegated authority. | Business performance, customer/service delivery, local risk and effective control implementation. | Applicable policies and standards, risk thresholds, local risk exposure, control requirements and approved exceptions. | Provide business context for risk decisions, implement enterprise controls within their operations, own local business risks and escalate risks exceeding delegated authority. |

## 1.3 Design a Security Governance Organisation Chart showing reporting lines, oversight relationships and communication paths.

**Legend**

- **────────** Direct reporting / accountability line
- **- - - - -** Oversight, escalation or coordination line

```text
                         BOARD OF DIRECTORS
                                  │
                                  │
                                  ▼
                     RISK & AUDIT COMMITTEE
                                  │
                    - - - - - - - - - - - -
                                  │
                                  ▼
                       CHIEF EXECUTIVE OFFICER
                                  │
        ┌─────────────────────────┼──────────────────────────┐
        │                         │                          │
        ▼                         ▼                          ▼
      CISO                     CRO / RISK            LEGAL / COMPLIANCE
        │                         │                          │
        │                         │                          │
        └──────────────┬──────────┴──────────┬──────────────┘
                       │                     │
                       ▼                     ▼
          SECURITY GOVERNANCE / STEERING COMMITTEE
                       │
      ┌────────────────┼────────────────┬─────────────────┐
      │                │                │                 │
      ▼                ▼                ▼                 ▼
  FINANCE             HR          IT / TECHNOLOGY   BUSINESS UNITS
                                                │
                                                │
                                                ▼
                                  OPERATIONAL SECURITY TEAMS
                                                │
                                                ▼
                                   SPECIALISED WORKING GROUPS
                                   • Incident Response
                                   • Cloud Security
                                   • Third-Party Risk
                                   • Data Governance
```

### Communication and Escalation Paths

```text
Operational Teams
        │
        ▼
Business Units / IT / Working Groups
        │
        ▼
Security Governance Committee
        │
        ▼
CISO / CRO
        │
        ▼
CEO
        │
        ▼
Risk & Audit Committee
        │
        ▼
Board of Directors

```

### 1.4 Explain why the proposed structure is appropriate for a 2,500-employee technology organisation operating across five offices.

The proposed governance structure is proportionate to TechGlobal’s size and operating model. With approximately 2,500 employees across five global offices, the organization requires stronger governance, accountability and risk oversight without introducing unnecessary bureaucracy. The structure therefore addresses the weaknesses of the existing IT-centric model while remaining practical and scalable.

The model establishes clear separation between governance oversight, executive accountability, security leadership and technology operations. The Board of Directors provides ultimate oversight, while the Risk & Audit Committee supports focused review of cybersecurity risk and assurance matters. The CEO retains executive accountability, with the CISO, CRO/Risk, Legal/Compliance, Finance, HR and IT/Technology contributing their respective specialist responsibilities. This reduces excessive concentration of security decision-making within IT and establishes clearer accountability across the organization.

The structure separates security governance from technology implementation. The CISO leads cybersecurity strategy, policy, governance and cyber-risk oversight, while IT/Technology remains responsible for implementing and operating technical controls. The CRO/Risk function provides enterprise-risk integration and independent challenge of significant cyber-risk assessments and acceptance decisions. This separation reduces potential conflicts of interest and strengthens risk-based decision-making.

The Security Governance/Steering Committee operates as a cross-functional governance forum rather than a separate reporting layer. It brings together the CISO, CRO/Risk, Legal/Compliance, Finance, HR and IT/Technology to review cybersecurity risks, policies, exceptions, control issues and remediation priorities. Business Unit Leaders provide business context, implement enterprise security requirements within their operations and escalate risks that exceed their delegated authority. Specialized Working Groups, such as Incident Response, provide detailed operational analysis and escalate matters requiring broader governance decisions.

The structure establishes clear two-way communication and escalation. Risk information, incidents, exceptions and unresolved control issues move upward from Business Units and Working Groups through the Security Governance/Steering Committee and, where material, to the CEO, Risk & Audit Committee or Board. Conversely, risk appetite, strategic direction, policies and approved governance decisions flow downward for implementation. This allows routine matters to remain at the appropriate operational level while ensuring significant and material risks receive appropriate executive or Board attention.

The structure is scalable. As TechGlobal expands, additional Business Unit representatives or specialized Working Groups, such as Cloud Security, Third-Party Risk or Data Governance, can be incorporated without fundamentally redesigning the governance architecture. Overall, the model strengthens accountability, cross-functional participation, independent risk challenge and Board visibility while remaining appropriate for TechGlobal’s current size and complexity.

# Task 2 Governance Responsibility and Authority Matrix

A governance chart only becomes effective when decision rights and accountabilities are explicit.

## 2.1 Develop a responsibility profile for the Board, CEO, CISO, CRO/Risk, Legal, Finance, HR and IT.

| Role | Purpose | Key Governance Responsibilities | Decision Authority | Reporting Obligations | KPIs |
|------|---------|---------------------------------|-------------------|----------------------|------|
| **Board** | Provide ultimate oversight of enterprise cybersecurity risk and ensure alignment with organizational strategy and risk appetite. | Set and oversee cyber-risk appetite, challenge management on material cyber risks, oversee significant incidents and assurance findings, monitor major remediation actions, hold executive management accountable. | Approves risk appetite and matters reserved for Board authority, including risks exceeding executive authority. | Receives regular and event-driven reporting on material cyber risks, incidents, assurance findings and risk-appetite breaches. | • Material cyber risks outside appetite.<br>• Percentage of Board cyber actions completed by due date. |
| **CEO** | Provide executive accountability for cybersecurity governance and ensure security supports business objectives. | Translate Board direction into enterprise priorities, ensure adequate resources, oversee execution of security strategy, resolve significant cross-functional issues, ensure appropriate escalation of material risks and incidents. | Approves enterprise security policies, major security investments and risk acceptance within delegated executive authority. | Reports material cyber risks, incidents and significant governance matter to the Board. | • Percentage of executive cyber-risk actions completed on time.<br>• Number of overdue material risk-treatment actions. |
| **CISO** | Lead enterprise cybersecurity governance, strategy and cyber-risk oversight. | Develop security strategy, policies and standards, oversee cyber risk and control effectiveness, coordinate security governance, oversee security architecture and incident-response governance, provide cybersecurity reporting. | Approves security standards and architecture within delegated authority, recommends risk treatment or acceptance, authorises security actions within mandate, escalates material risk. | Reports cybersecurity posture, significant incidents, control weaknesses and material risks to the CEO and Board as appropriate. | • Percentage of critical/high-risk remediation completed within agreed timelines.<br>• Percentage of security policies reviewed within the approved cycle. |
| **CRO/Risk** | Integrate cybersecurity risk into enterprise risk management and provide independent risk challenge. | Maintain risk methodology and the enterprise risk register, challenge cyber-risk assessments and treatment decisions, monitor risk appetite, aggregate cyber risk into the enterprise risk profile and monitor accepted risks. | Establishes risk methodology and criteria, challenges risk assessments and treatment decisions, escalates risks exceeding appetite or delegated authority. | Reports significant cyber-risk exposure, appetite breaches and unresolved risks to the CEO and Board. | • Percentage of material cyber-risk reviews completed on schedule.<br>• Number and age of risks outside appetite or overdue for review. |
| **Legal** | Ensure cybersecurity decisions consider applicable legal, regulatory and contractual obligations. | Interpret applicable legal requirements, assess notification obligations, advise on evidence handling and regulatory engagement, review relevant contractual requirements, support incident and compliance matters. | Provides authoritative legal interpretation and determines applicable legal obligations. | Reports significant legal and regulatory exposure to the CEO and escalates material matters through established governance channels. | • Notification assessments completed within required timelines.<br>• Percentage of significant legal/compliance actions completed by due date. |
| **Finance** | Provide financial governance for cybersecurity investment and cyber-risk decisions. | Coordinate security budgeting, assess investment proposals, quantify financial exposure from cyber risks and incidents, monitor approved expenditure and support financial assessment of significant risks. | Approves expenditure within delegated financial authority and provides financial challenge to security investment proposals. | Reports significant budget variances, investment requirements and material financial exposure to the CEO. | • Security expenditure variance against approved budget.<br>• Percentage of approved priority security investments tracked to completion. |
| **HR** | Integrate cybersecurity requirements into workforce governance and people processes. | Coordinate joiner/mover/leaver processes, manage security awareness and training, oversee employee conduct and disciplinary processes and support insider-risk investigations. | Approves HR and disciplinary actions within established policies and employment procedures. | Reports significant workforce-related security risks, awareness performance and personnel-control issues to the CEO and relevant governance forums. | • Mandatory security-awareness completion rate.<br>• Percentage of joiner/mover/leaver security actions initiated within required timelines. |
| **IT** | Implement and operate technology services and technical security controls in accordance with approved security requirements. | Implement technical controls and security architecture, operate infrastructure and access provisioning, remediate vulnerabilities, support incident response and execute technical continuity and recovery activities. | Makes operational technology decisions within approved architecture, security policies and change-management authority and escalates risks outside its authority. | Reports significant vulnerabilities, control failures, incidents and unresolved security risks to the CISO and executive management as appropriate. | • Percentage of critical vulnerabilities remediated within SLA.<br>• Service availability and recovery performance against approved targets. |

## 2.2 Identify at least three areas where authority could overlap or conflict and explain how the governance model should resolve those conflicts.

| Overlap Area | Nature of the Conflict | Resolution Principle |
|-------------|-----------------------|---------------------|
| **CISO vs IT - Security architecture and control implementation** | The CISO defines security requirements and oversees cyber risk, while IT is responsible for implementing and operating technical controls. Conflict may arise when security requirements affect cost, system performance, technical feasibility or service delivery. | The CISO defines security requirements and approves security architecture within delegated authority, while IT designs, implements and operates the controls. IT may propose exceptions but cannot independently waive security requirements. Unresolved material risks are escalated through the established governance process. |
| **CISO vs CRO/Risk - Cyber-risk assessment and acceptance** | Both functions participate in cyber-risk management, creating potential overlap between technical risk assessment, independent challenge and formal risk acceptance. | The CISO assesses cybersecurity exposure and recommends appropriate treatment, while CRO/Risk maintains the enterprise risk methodology and independently challenges the assessment and proposed treatment. Final risk acceptance rests with the authorized business, executive or Board-level risk owner according to delegated authority. |
| **Legal vs CISO - Regulatory notification** | Legal determines applicable legal and regulatory obligations, but relies on technical information from the CISO to understand the scope, impact and circumstances of a cybersecurity incident. | The CISO establishes and provides the technical facts and security impact, while Legal determines the applicable notification obligations. Any material disagreement is escalated to the CEO through the established escalation process. |
| **Finance vs CISO - Security investment and budget prioritization** | The CISO may identify security investments required to reduce significant cyber risk, while Finance must consider affordability, budget constraints and competing organizational priorities. | The CISO documents the risk exposure, proposed treatment and expected risk reduction, while Finance assesses affordability and financial implications. Where agreement cannot be reached, the matter is escalated to the CEO for a decision within delegated authority, or to the Board where required. |

# Task 3 Security Governance Committee Ecosystem (20 marks)

Security governance requires formal forums where risk, investment, compliance and technology decisions can be reviewed and resolved collectively rather than by one department.

## 3.1 Design an Executive Security Council for strategic oversight.

Executive Security Council (ESC) is established as the senior management forum responsible for strategic cybersecurity oversight and executive-level decision-making. The Council focuses on material cyber risks, major security investments, significant incidents and unresolved governance matters that exceed the authority of the Security Governance/Steering Committee. It provides the principal management-level link between cybersecurity governance and the Board/Risk Committee.

| Element | Executive Security Council Design |
|----------|----------------------------------|
| **Purpose** | Provide executive-level strategic oversight of cybersecurity and ensure significant security risks and decisions are aligned with TechGlobal’s business objectives and risk appetite. |
| **Chair** | CEO |
| **Membership** | CEO, CISO, CRO/Risk, IT, Legal, Finance and HR. Business Unit leaders may attend when matters affecting their operations are considered. |
| **Core Responsibilities** | Review cybersecurity strategy and performance; review material cyber risks and incidents; consider major security investments; resolve significant cross-functional issues; monitor risks approaching or exceeding appetite; oversee significant remediation actions; and escalate Board-reserved matters. |
| **Decision Authority** | Makes cybersecurity decisions within executive delegated authority, including prioritization of resources and risk-treatment decisions. Matters exceeding executive authority or Board-approved risk appetite are escalated to the Board/Risk Committee. |
| **Meeting Cadence** | Quarterly, with emergency or ad hoc meetings for material incidents, significant risk exposure or urgent decisions. |
| **Inputs** | Cyber-risk reports, KRIs/KPIs, material incident reports, significant policy exceptions, major investment proposals, risk-treatment updates and matters escalated by the Security Governance/Steering Committee. |
| **Outputs** | Executive decisions, approved priorities, assigned actions, risk-treatment directions, resource decisions and matters formally escalated to the Board/Risk Committee. |
| **Escalation** | Receives matters requiring executive authority from the Security Governance/Steering Committee and escalates material, appetite-breaching or Board-reserved matters to the Board/Risk Committee. |
| **Records / Evidence** | Meeting agendas, attendance records, minutes, decision logs, assigned action owners, target dates and documented escalation decisions. |

---

## 3.2 Design a Security Governance / Steering Committee for cross-functional governance decisions.

Security Governance / Steering Committee (SGC) is established as the primary forum for cross-functional cybersecurity governance decisions which focuses on strategic and material matters, the SGC focuses on coordinating security governance across Risk, IT, Legal, Finance, HR and Business Units. It reviews enterprise security issues, resolves matters within its delegated authority and escalates significant or unresolved matters to the Executive Security Council.

| Element | Detail |
|----------|--------|
| **Purpose** | Provide a cross-functional forum for reviewing and coordinating cybersecurity risk, policy, compliance, control, exception and remediation matters across TechGlobal. |
| **Chair** | CISO. |
| **Membership** | CISO (Chair), CRO/Risk, IT, Legal, Finance, HR and Business Unit Security Liaisons. Relevant specialists participate when required by the agenda. |
| **Cross-Functional Responsibilities** | Review cyber risks and treatment actions; review and recommend security policies; assess significant policy/control exceptions; monitor critical remediation; review third-party and technology-related risks; review significant incidents and lessons learned; monitor governance KPIs/KRIs; coordinate Business Unit participation; and direct relevant Working Group activities. |
| **Decision Authority** | Makes cross-functional governance decisions within delegated Committee authority; assigns action owners and due dates; reviews recommendations from Working Groups; and recommends or escalates matters requiring executive authority. Formal risk acceptance remains with the appropriately authorized risk owner. |
| **Meeting Frequency** | Monthly, with ad hoc meetings for urgent or time-sensitive governance matters. |
| **Receives From** | Business Unit Security Liaisons, Incident Response Working Group, Third-Party Risk Working Group, IT and other operational or specialist functions. |
| **Escalates To** | Executive Security Council when risks, investments, conflicts or decisions exceed the Committee’s delegated authority or require executive action. |
| **Key Outputs** | Governance decisions, policy recommendations, approved action plans, remediation priorities, Working Group assignments, documented exceptions and recommendations for executive consideration. |
| **Records / Evidence** | Agendas, attendance records, evidence packs, minutes, decisions and rationale, action owners, due dates, exception records and escalation records maintained in the governance repository. |
| **Review Cycle** | Committee effectiveness and Terms of Reference are reviewed annually or following significant governance changes or material cybersecurity events. |

---

## 3.3 Define one specialised Working Group appropriate to TechGlobal (for example Incident Response, Cloud Security or Third-Party Risk).

| Element | Detail |
|----------|--------|
| **Purpose** | Provide specialized operational coordination for cybersecurity incident preparedness, response, recovery and post-incident improvement across TechGlobal. |
| **Scope** | Covers cybersecurity incident readiness, triage, containment, investigation support, recovery, evidence preservation, post-incident review and corrective-action tracking across all TechGlobal Business Units and offices. |
| **Membership** | Security/Incident Response Lead (Chair), IT representative, Legal representative, HR representative, Communications representative and representatives from affected Business Units. Other specialists participate when required by the nature of an incident. |
| **Frequency** | As needed during cybersecurity incidents, with periodic readiness exercises and reviews to test incident-response plans and procedures. |
| **Responsibilities** | Maintain and test incident-response plans and playbooks; coordinate incident triage, containment and recovery; assess incident scope and business impact; support investigations; preserve relevant evidence; conduct post-incident reviews; document lessons learned; and track corrective actions. |
| **Decision Rights** | Coordinates operational incident-response actions within approved procedures and delegated authority. The Working Group does not independently accept material business risk or make executive-level, regulatory-notification or Board-reserved decisions. |
| **Escalation** | Significant incidents, unresolved control weaknesses and governance actions are escalated to the Security Governance/Steering Committee. Matters requiring executive authority or involving material risk are escalated through the Committee to the Executive Security Council. |
| **Reporting Line** | Reports incident status, significant findings, lessons learned and remediation recommendations to the Security Governance/Steering Committee. Urgent or material matters are escalated immediately through the established governance structure. |
| **Records / Evidence** | Maintains incident logs, response timelines, evidence records, decisions and rationale, action owners, due dates, recovery records and post-incident review reports. |
| **Review Cycle** | The Working Group’s mandate, membership, incident-response procedures and effectiveness are reviewed annually and following significant cybersecurity incidents or major organizational changes. |

---

## 3.4 Define how Business Units will participate in governance without creating separate security silos.

Business Unit Security Liaison model is used to ensure that all Business Units and offices participate in cybersecurity governance while remaining within a single enterprise-wide governance framework. Each Business Unit or office will nominate a Security Liaison to represent its operational needs, risks and implementation challenges within the Security Governance / Steering Committee (SGC).

| Element | Approach |
|----------|----------|
| **Representation** | Each Business Unit or office nominates a Business Unit Security Liaison to represent it in the Security Governance / Steering Committee and relevant Working Groups when required. |
| **Governance Alignment** | All Business Units follow the same enterprise cybersecurity policies, standards, risk methodology, escalation thresholds and governance processes rather than creating separate local security governance structures. |
| **Local Risk Identification** | Business Unit Security Liaisons identify and communicate local cybersecurity risks, control weaknesses, exceptions and operational concerns to the SGC. |
| **Decision Participation** | Business Unit representatives provide business context and contribute to cross-functional discussions and decisions that affect their operations. |
| **Implementation** | Business Unit leaders remain responsible for implementing approved security requirements and remediation actions within their areas of responsibility. |
| **Risk and Exception Escalation** | Risks and exceptions that cannot be resolved within the Business Unit’s delegated authority are submitted through the established governance process to the SGC and, where necessary, escalated to the Executive Security Council. |
| **Communication** | Security Liaisons communicate enterprise security decisions, policies and assigned actions back to their Business Units and provide progress updates to the SGC. |
| **Accountability** | Business Unit leaders retain accountability for business risks and implementation within their areas, while the CISO maintains enterprise cybersecurity governance and oversight. |
| **Avoiding Silos** | Business Units do not establish independent security policies, risk methodologies or decision-making structures. Their participation is embedded within TechGlobal’s central governance forums, ensuring consistency while preserving local business input. |

---

## 3.5 Show how decisions and risk information move from operational forums to executive management and, where material, to the Board.
![TechGlobal Major Cyber-Risk Escalation Workflow](Task%203.5.png)        



```

