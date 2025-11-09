# OctoAcme Role RACI Matrix

## Purpose

This RACI matrix maps common project activities to the roles defined in [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md). It clarifies who is **R**esponsible, **A**ccountable, **C**onsulted, and **I**nformed for each activity.

## RACI Legend

- **R — Responsible:** The person(s) who perform the work to complete the task.
- **A — Accountable:** The person who is ultimately answerable for the completion and approval of the task. Only one A per activity.
- **C — Consulted:** People who provide input and are consulted before decisions or actions are taken.
- **I — Informed:** People who are kept up-to-date on progress and decisions.

## RACI Matrix

| Activity | Project Sponsor | Product Owner | Product Manager | Project Manager | Developer | Technical Lead | Business Analyst | QA Lead | Release Manager | Security & Compliance | Change Manager | Stakeholder Rep | Steering Committee |
|----------|----------------|---------------|-----------------|-----------------|-----------|----------------|------------------|---------|-----------------|----------------------|----------------|-----------------|-------------------|
| **Project Initiation** |
| Authorize project | **A** | C | C | R | I | I | I | I | I | I | I | C | I |
| Define business objectives | C | R | **A** | C | I | I | C | I | I | I | I | C | I |
| Create project charter | C | C | C | R/**A** | I | I | I | I | I | I | I | I | C |
| Identify stakeholders | C | C | C | R/**A** | I | I | I | I | I | I | R | R | I |
| Initial risk assessment | C | C | C | R/**A** | C | C | C | C | C | C | C | C | I |
| **Requirements Gathering** |
| Elicit business requirements | I | C | C | C | I | I | R/**A** | I | I | C | C | R | I |
| Define acceptance criteria | I | R/**A** | C | C | C | C | C | C | I | C | I | C | I |
| Document functional specs | I | C | C | I | I | I | R/**A** | I | I | I | I | C | I |
| Prioritize backlog | I | R/**A** | C | C | I | I | C | I | I | I | I | C | I |
| **Planning** |
| Create project plan | C | C | C | R/**A** | C | C | C | C | C | C | C | I | I |
| Estimate effort | I | C | C | C | R | R/**A** | C | I | I | I | I | I | I |
| Define sprint/iteration scope | I | R | C | R/**A** | C | C | I | C | I | I | I | I | I |
| Identify dependencies | I | C | C | R/**A** | R | R | C | C | R | C | C | C | I |
| Create test strategy | I | C | C | C | C | C | C | R/**A** | C | C | I | I | I |
| Define security requirements | I | C | I | C | I | C | I | I | I | R/**A** | I | I | I |
| **Execution & Development** |
| Implement features | I | C | I | I | R/**A** | C | I | I | I | I | I | I | I |
| Conduct code reviews | I | I | I | I | R | R/**A** | I | I | I | C | I | I | I |
| Write unit tests | I | I | I | I | R/**A** | C | I | C | I | I | I | I | I |
| Technical design decisions | I | C | I | C | C | R/**A** | I | I | I | C | I | I | I |
| Resolve technical issues | I | C | I | C | R | R/**A** | C | I | I | C | I | I | I |
| Update documentation | I | C | I | C | R/**A** | C | I | I | I | I | I | I | I |
| **Quality Assurance** |
| Create test cases | I | C | I | I | I | I | C | R/**A** | I | I | I | I | I |
| Execute testing | I | C | I | C | C | I | I | R/**A** | I | I | I | I | I |
| Log and track defects | I | C | I | C | R | C | I | R/**A** | I | I | I | I | I |
| Validate acceptance criteria | I | R | C | C | C | I | C | R/**A** | I | I | I | C | I |
| Quality gate approval | I | C | I | C | I | I | I | R/**A** | C | C | I | I | I |
| Security testing | I | I | I | C | C | C | I | C | I | R/**A** | I | I | I |
| **Release & Deployment** |
| Plan release schedule | I | C | I | C | C | C | I | C | R/**A** | C | I | I | I |
| Prepare deployment artifacts | I | I | I | C | R | C | I | C | R/**A** | I | I | I | I |
| Execute deployment | I | I | I | C | R | C | I | C | R/**A** | I | I | I | I |
| Smoke test post-deployment | I | C | I | C | R | C | I | R | R/**A** | I | I | I | I |
| Create release notes | I | C | C | C | R | C | C | C | R/**A** | I | C | I | I |
| Approve release go-live | **A** | C | C | C | I | I | I | C | R | C | C | C | I |
| **Change Management** |
| Assess change impact | I | C | I | C | I | I | C | I | I | I | R/**A** | C | I |
| Develop communication plan | C | C | C | C | I | I | I | I | I | I | R/**A** | C | I |
| Coordinate training | I | C | I | C | I | I | C | I | I | I | R/**A** | C | I |
| Monitor adoption metrics | I | C | C | C | I | I | I | I | I | I | R/**A** | C | I |
| Manage stakeholder resistance | C | C | C | C | I | I | C | I | I | I | R/**A** | C | C |
| **Communications & Reporting** |
| Daily standup updates | I | C | C | C | R | R/**A** | C | C | C | I | I | I | I |
| Weekly status reports | C | C | C | R/**A** | I | I | I | I | I | I | I | I | I |
| Sprint/milestone demos | C | R | C | R/**A** | R | R | C | C | I | I | I | C | I |
| Executive status updates | C | I | C | R/**A** | I | I | I | I | I | I | I | I | C |
| Risk escalation | **A** | C | C | R | C | C | C | C | C | C | C | C | C |
| Stakeholder engagement | C | C | C | C | I | I | C | I | I | I | R | R/**A** | I |

## Notes and Guidelines

1. **Single Accountable:** Each activity should have only one **A** (Accountable) to ensure clear ownership and decision-making authority.

2. **Responsible may be multiple:** Multiple roles can be **R** (Responsible) when work is collaborative or distributed.

3. **Flexibility:** This matrix represents typical responsibilities. Actual assignments may vary based on:
   - Project size and complexity
   - Organizational structure
   - Availability of specialized roles

4. **Role combinations:** In smaller projects, one person may fill multiple roles. Ensure accountability remains clear when combining roles.

5. **Escalation paths:** When conflicts arise, refer to the **A** (Accountable) person for final decisions. Major issues should be escalated to the Project Sponsor or Steering Committee.

6. **Customization:** Use the [role responsibility template](templates/role-responsibility-template.md) to adapt this matrix for specific projects and add project-specific activities.

## See Also

- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md) — Detailed role descriptions
- [Role Responsibility Template](templates/role-responsibility-template.md) — Customize roles for specific projects
- [Role Onboarding Checklist](templates/role-onboarding-checklist.md) — Onboard team members to their roles
