# OctoAcme Project Management Docs

This folder contains OctoAcme's program-level project management process documents. These docs are a single source of truth for how we initiate, plan, execute, release, and continuously improve cross-functional projects. They accelerate onboarding, reduce single-person knowledge risk, and provide teams with practical templates and checklists to run work consistently.

OctoAcme follows a lightweight, iterative lifecycle:

- Initiation — validate the problem and set measurable success metrics (Project One-pager).
- Planning — prioritize and estimate a backlog, define the Definition of Done, and map releases and milestones.
- Execution — deliver small, testable increments tracked on a project board and delivered via disciplined PR workflows.
- Release — staged deployments with smoke tests, rollback plans, and post-release verification.
- Close & Retrospective — capture learnings and convert them into prioritized action items tracked in the backlog.

Key workflows and conventions

- Project board flow: Backlog → Ready → In Progress → In Review → QA → Done.
- Pull Request conventions: keep PRs small, link the issue and acceptance criteria, run CI (tests, linters, security scans), and require approvals per team policy.
- Risk management: maintain a lightweight Risk Register and review it during weekly syncs.

Roles & responsibilities

- Product Managers (PdM): define outcomes, prioritize the backlog, and set success metrics.
- Project Managers (PM): coordinate schedules, risks, and stakeholder communications.
- Developers: implement, test, and document features.
- QA/Testing: validate acceptance criteria and run manual/automated tests as required.
- Stakeholders: provide input, approvals, and business context.

Communication cadence

- Daily standups for the delivery team to surface progress and blockers.
- Weekly PM–PdM syncs for alignment, risk review, and cross-team coordination.
- Demos or reviews at the end of each sprint or milestone.
- Monthly stakeholder updates and ad-hoc escalations as needed.

Quality assurance & release practices

- Automated checks: unit and integration tests, linters, and security scanning in CI.
- Manual QA: targeted exploratory or acceptance testing when required.
- Pre-release checklist: passing CI, release notes, rollback/mitigation plan, and staging smoke tests.
- Post-release verification and a rollback plan or incident playbook for critical failures.

Docs index

- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md
