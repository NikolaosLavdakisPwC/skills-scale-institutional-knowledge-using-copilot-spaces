# OctoAcme Project Management Docs

## Overview

OctoAcme organizes work around a clear lifecycle—initiation, planning, execution, release, and retrospective—starting with a lightweight Project One‑pager to capture problem, goal, success metrics, stakeholders and an initial risk list. Planning converts approved initiatives into a prioritized backlog, estimates, a Definition of Done, and a release/milestone map; decision gates require clarity on success metrics, stakeholder alignment, and team availability before moving into execution.

Workflows emphasize small, incremental delivery and traceability: teams use a project board (Backlog, Ready, In Progress, In Review, QA, Done), a PR workflow with small pull requests (guideline ≤ 400 lines), PR descriptions that include issue links and acceptance criteria, and a policy of passing CI/linting and at least one approval before merge. Backlog items follow a template (title, description, acceptance criteria, estimate, owner) and risk/dependency management is captured in a simple Risk Register with owners, mitigation plans, and regular reviews. Checklists support repeatable handoffs and artifacts like release notes and rollback plans.

Personas and responsibilities are explicit: Project Manager (coordinates delivery, schedules, risks and communications), Product Manager (defines outcomes, prioritizes backlog, measures success), Developers (design, implement, test), QA/Testing (validate acceptance), and Stakeholders (inputs/approvals). Communication and quality practices are built into the cadence and CI pipeline: daily standups, weekly delivery syncs, monthly stakeholder updates, blocker escalation paths, unit/integration tests, end-to-end smoke tests, security scanning, manual QA where needed, post-deploy verifications, and a rollback/incident playbook for production risk mitigation.

## Docs Index

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [OctoAcme Project Initiation](octoacme-project-initiation.md)
- [OctoAcme Project Planning](octoacme-project-planning.md)
- [OctoAcme Execution and Tracking](octoacme-execution-and-tracking.md)
- [OctoAcme Risks and Communication](octoacme-risks-and-communication.md)
- [OctoAcme Release and Deployment](octoacme-release-and-deployment.md)
- [OctoAcme Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)

## How to use these docs

- Keep the project charter updated in the project repo
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context

## Acceptance Criteria

- [x] Content aligns with existing process docs
- [x] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders
