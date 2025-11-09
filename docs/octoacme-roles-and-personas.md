# OctoAcme Roles and Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

## Introduction

**Why these additions improve clarity and accountability:**

This enhanced roles and personas document addresses gaps identified in project governance by clearly defining who does what, when, and how across the project lifecycle. By expanding from the core trio of Developers, Product Managers, and Project Managers to include specialized roles like Project Sponsor, Technical Lead, QA Lead, Release Manager, and others, we achieve:

- **Clear accountability:** Each role has explicit responsibilities and reporting relationships, reducing confusion about who owns key decisions.
- **Better collaboration:** Defined interaction patterns help team members know whom to consult, collaborate with, and keep informed.
- **Improved onboarding:** New team members can quickly understand their role and how they fit into the broader project organization.
- **Scalability:** As projects grow in complexity, these additional roles ensure critical functions (security, change management, stakeholder engagement) are explicitly assigned and managed.

This document should be used in conjunction with the [RACI matrix](octoacme-role-raci.md) to map specific activities to roles, and the [role templates](templates/role-responsibility-template.md) for project-specific customization.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Project Sponsor

### Role Summary
The Project Sponsor is a senior stakeholder who champions the project, provides strategic direction, and secures necessary resources. They have ultimate accountability for project success and alignment with organizational goals.

### Key Responsibilities
- Authorize the project and commit funding and resources
- Define or validate high-level success criteria and business objectives
- Remove organizational or political blockers
- Review major milestone outcomes and approve scope changes
- Provide executive-level communication and advocacy

### Typical Interactions
- **Reports to:** Executive leadership or steering committee
- **Collaborates with:** Product Owner, Project Manager, Steering Committee
- **Escalation point for:** Major scope, budget, or timeline decisions

### Example Deliverables
- Project charter or authorization memo
- Executive briefings and status updates
- Go/no-go decisions at key gates

### Suggested Meeting Cadence
- Monthly project review or at major milestones
- Ad-hoc escalation meetings as needed
- Quarterly steering committee reviews

---

## Product Owner

### Role Summary
The Product Owner represents the customer and business needs, owns the product backlog, and ensures the team delivers maximum value. They make trade-off decisions and maintain the product vision.

### Key Responsibilities
- Define and prioritize the product backlog
- Write user stories with clear acceptance criteria
- Make scope and feature trade-off decisions
- Accept or reject completed work based on acceptance criteria
- Communicate product vision and roadmap to the team

### Typical Interactions
- **Reports to:** Product Manager or Project Sponsor
- **Collaborates with:** Developers, Business Analyst, QA Lead, Stakeholder Representatives
- **Provides direction to:** Delivery team on priorities and acceptance

### Example Deliverables
- Prioritized product backlog
- User stories with acceptance criteria
- Sprint goals and release objectives
- Product demos

### Suggested Meeting Cadence
- Daily or frequent availability for backlog refinement and clarifications
- Sprint planning, review, and retrospective participation
- Weekly sync with Product Manager and Project Manager

---

## Change Manager

### Role Summary
The Change Manager ensures organizational readiness for project outcomes, plans change adoption activities, and mitigates resistance. They coordinate training, communication, and stakeholder engagement to ensure smooth transitions.

### Key Responsibilities
- Assess change impact and stakeholder readiness
- Develop change management and communication plans
- Coordinate training and knowledge transfer activities
- Monitor adoption metrics and address resistance
- Work with stakeholders to ensure buy-in and engagement

### Typical Interactions
- **Reports to:** Project Sponsor or Program Manager
- **Collaborates with:** Stakeholder Representative, Communications lead, Project Manager, Training teams
- **Consults with:** Business units affected by the change

### Example Deliverables
- Change impact assessment
- Stakeholder engagement plan
- Training materials and session schedules
- Adoption metrics and readiness reports

### Suggested Meeting Cadence
- Weekly sync with Project Manager
- Bi-weekly stakeholder engagement sessions
- Training events as scheduled
- Monthly readiness reviews

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They elicit, analyze, and document requirements, ensuring that solutions meet business needs and align with organizational processes.

### Key Responsibilities
- Conduct requirements gathering sessions with stakeholders
- Document functional and non-functional requirements
- Create process flows, use cases, and data models
- Validate that solutions meet business requirements
- Support testing by defining test scenarios and expected outcomes

### Typical Interactions
- **Reports to:** Product Owner or Project Manager
- **Collaborates with:** Stakeholders, Developers, QA Lead, Product Owner
- **Provides requirements to:** Technical Lead and development team

### Example Deliverables
- Business requirements document (BRD)
- Functional specifications
- Process flow diagrams
- Requirements traceability matrix
- Test scenarios

### Suggested Meeting Cadence
- Weekly requirements review sessions
- Daily or frequent availability for clarifications during development
- Sprint planning and backlog refinement participation

---

## Technical Lead

### Role Summary
The Technical Lead provides technical direction, makes architectural decisions, and ensures engineering best practices. They mentor developers, review technical designs, and resolve complex technical challenges.

### Key Responsibilities
- Define technical architecture and design patterns
- Review code and technical designs for quality and consistency
- Make technical trade-off decisions (performance, scalability, maintainability)
- Mentor developers and conduct technical knowledge sharing
- Identify and mitigate technical risks

### Typical Interactions
- **Reports to:** Engineering Manager or Project Manager
- **Collaborates with:** Developers, Security & Compliance Officer, QA Lead
- **Provides guidance to:** Development team on technical decisions

### Example Deliverables
- Technical design documents
- Architecture decision records (ADRs)
- Code review feedback
- Technical risk assessments
- Proof-of-concept implementations

### Suggested Meeting Cadence
- Daily standups with development team
- Weekly architecture review sessions
- Sprint planning participation
- Ad-hoc design discussions as needed

---

## QA Lead

### Role Summary
The QA Lead ensures quality standards are met throughout the project lifecycle. They define the test strategy, coordinate testing activities, and verify that deliverables meet acceptance criteria and quality gates.

### Key Responsibilities
- Develop test strategy and test plans
- Coordinate manual and automated testing efforts
- Define quality metrics and exit criteria
- Review test results and defect trends
- Ensure test coverage aligns with risk areas
- Sign off on release readiness from a quality perspective

### Typical Interactions
- **Reports to:** Project Manager or Engineering Manager
- **Collaborates with:** Developers, Product Owner, Business Analyst, Release Manager
- **Provides quality gates for:** Release Manager before deployments

### Example Deliverables
- Test strategy and test plans
- Test cases and test scripts
- Defect reports and metrics
- Quality gate sign-offs
- Testing summary reports

### Suggested Meeting Cadence
- Daily standups or testing sync meetings
- Sprint planning and review participation
- Weekly quality metrics review
- Pre-release quality gate meetings

---

## Release Manager

### Role Summary
The Release Manager coordinates and orchestrates software releases across environments. They ensure releases are planned, tested, documented, and deployed safely with minimal disruption to operations.

### Key Responsibilities
- Plan and schedule releases across environments
- Coordinate deployment activities with technical teams
- Ensure release documentation and runbooks are complete
- Manage release risks, dependencies, and rollback plans
- Verify post-deployment smoke tests and validation
- Communicate release status to stakeholders

### Typical Interactions
- **Reports to:** Project Manager or Engineering Manager
- **Collaborates with:** Developers, QA Lead, Technical Lead, Operations/DevOps teams
- **Coordinates with:** Stakeholders on release timing and communication

### Example Deliverables
- Release schedule and calendar
- Deployment runbooks and checklists
- Release notes and change logs
- Rollback and contingency plans
- Post-release reports

### Suggested Meeting Cadence
- Weekly release planning meetings
- Daily during release windows
- Sprint review participation for release readiness
- Post-release retrospectives

---

## Security & Compliance Officer

### Role Summary
The Security & Compliance Officer ensures that project deliverables meet security standards, regulatory requirements, and organizational policies. They conduct security reviews, threat modeling, and compliance assessments.

### Key Responsibilities
- Conduct security and privacy reviews of designs and implementations
- Perform threat modeling and risk assessments
- Ensure compliance with regulations (GDPR, HIPAA, SOC2, etc.)
- Review code for security vulnerabilities
- Define security requirements and controls
- Coordinate security testing and penetration testing activities

### Typical Interactions
- **Reports to:** Chief Information Security Officer (CISO) or Compliance lead
- **Collaborates with:** Technical Lead, Developers, QA Lead, Legal/Compliance teams
- **Provides sign-off to:** Project Manager and Release Manager on security readiness

### Example Deliverables
- Security requirements and controls
- Threat models and risk assessments
- Security review findings and recommendations
- Compliance checklists and attestations
- Security incident response plans

### Suggested Meeting Cadence
- Security review sessions at design and pre-release stages
- Weekly or bi-weekly sync with Technical Lead
- Ad-hoc consultations during development
- Quarterly compliance reviews

---

## Stakeholder Representative

### Role Summary
Stakeholder Representatives act as the voice of specific business units, user groups, or customer segments. They provide input on requirements, validate solutions, and ensure project outcomes meet their constituency's needs.

### Key Responsibilities
- Represent the interests and needs of their stakeholder group
- Participate in requirements gathering and validation
- Review and provide feedback on prototypes and deliverables
- Communicate project progress back to their stakeholders
- Raise concerns or risks from their stakeholder perspective

### Typical Interactions
- **Reports to:** Project Sponsor or business unit leadership
- **Collaborates with:** Product Owner, Business Analyst, Change Manager
- **Provides feedback to:** Project Manager and delivery team

### Example Deliverables
- Stakeholder feedback and requirements input
- User acceptance testing (UAT) results
- Communication updates to stakeholder groups
- Change impact and readiness assessments

### Suggested Meeting Cadence
- Sprint reviews and demo sessions
- Bi-weekly or monthly stakeholder sync meetings
- UAT sessions as scheduled
- Ad-hoc consultations as needed

---

## Steering Committee

### Role Summary
The Steering Committee is a governance body of senior leaders who provide oversight, strategic direction, and decision-making authority for the project. They review progress, resolve escalations, and ensure alignment with organizational strategy.

### Key Responsibilities
- Provide strategic direction and priority alignment
- Review project progress against objectives and key results
- Approve major scope, budget, or timeline changes
- Resolve escalated issues and remove organizational barriers
- Ensure cross-project coordination and resource allocation

### Typical Interactions
- **Reports to:** Executive leadership
- **Collaborates with:** Project Sponsor, Project Manager, Product Owner
- **Provides governance for:** Major decisions and escalations

### Example Deliverables
- Strategic guidance and direction
- Decision logs for major approvals or changes
- Escalation resolution and action items
- Quarterly or milestone-based project reviews

### Suggested Meeting Cadence
- Monthly or quarterly steering committee meetings
- Ad-hoc meetings for major decisions or escalations
- Milestone-based reviews at key project gates

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the [RACI matrix](octoacme-role-raci.md) to understand how these roles interact across project activities.
- Use the [role templates](templates/role-responsibility-template.md) to customize roles for specific projects.

