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
```

## 1.4 Explain why the proposed structure is appropriate for a 2,500-employee technology organisation operating across five offices.

- The proposed governance structure is proportionate to TechGlobal’s size and operating model. With approximately 2,500 employees across five global offices, the organization requires stronger governance, accountability and risk oversight without introducing unnecessary bureaucracy. The structure therefore addresses the weaknesses of the existing IT-centric model while remaining practical and scalable.

- The model establishes clear separation between governance oversight, executive accountability, security leadership and technology operations. The Board of Directors provides ultimate oversight, while the Risk & Audit Committee supports focused review of cybersecurity risk and assurance matters. The CEO retains executive accountability, with the CISO, CRO/Risk, Legal/Compliance, Finance, HR and IT/Technology contributing their respective specialist responsibilities. This reduces excessive concentration of security decision-making within IT and establishes clearer accountability across the organization.

- The structure separates security governance from technology implementation. The CISO leads cybersecurity strategy, policy, governance and cyber-risk oversight, while IT/Technology remains responsible for implementing and operating technical controls. The CRO/Risk function provides enterprise-risk integration and independent challenge of significant cyber-risk assessments and acceptance decisions. This separation reduces potential conflicts of interest and strengthens risk-based decision-making.

- The Security Governance/Steering Committee operates as a cross-functional governance forum rather than a separate reporting layer. It brings together the CISO, CRO/Risk, Legal/Compliance, Finance, HR and IT/Technology to review cybersecurity risks, policies, exceptions, control issues and remediation priorities. Business Unit Leaders provide business context, implement enterprise security requirements within their operations and escalate risks that exceed their delegated authority. Specialized Working Groups, such as Incident Response, provide detailed operational analysis and escalate matters requiring broader governance decisions.

- The structure establishes clear two-way communication and escalation. Risk information, incidents, exceptions and unresolved control issues move upward from Business Units and Working Groups through the Security Governance/Steering Committee and, where material, to the CEO, Risk & Audit Committee or Board. Conversely, risk appetite, strategic direction, policies and approved governance decisions flow downward for implementation. This allows routine matters to remain at the appropriate operational level while ensuring significant and material risks receive appropriate executive or Board attention.

- The structure is scalable. As TechGlobal expands, additional Business Unit representatives or specialized Working Groups, such as Cloud Security, Third-Party Risk or Data Governance, can be incorporated without fundamentally redesigning the governance architecture. Overall, the model strengthens accountability, cross-functional participation, independent risk challenge and Board visibility while remaining appropriate for TechGlobal’s current size and complexity.

- 
