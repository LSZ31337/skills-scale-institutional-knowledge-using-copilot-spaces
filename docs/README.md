# OctoAcme Project Management Docs

## Project Management Process Summary

OctoAcme runs projects through a lightweight, outcome-focused lifecycle that moves initiatives from Initiation through Planning, Execution, Release, and Retrospective. Initiation captures the problem, objective, success metrics, stakeholders, and a high-level timeline (Project One-pager). Planning turns approved initiatives into a prioritized backlog with clear acceptance criteria, estimates, a Definition of Done, and a risk register to guide execution.

Day-to-day workflows rely on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a pull-request pipeline that emphasizes small, reviewable PRs linked to issues and acceptance criteria. CI runs automated tests, linting, and security scans; PRs require review before merge. Timeboxed sprint/iteration planning and capacity-aware pulls keep work predictable and manageable. Release guidance covers pre-release checks, smoke tests, rollback playbooks, and release notes.

Roles and responsibilities are explicit: Product Managers define outcomes and prioritize work; Project Managers coordinate delivery, manage risks and stakeholder communications; Developers implement, test, and document; QA validates acceptance criteria and runs tests. Role clarity enables clear ownership, escalation paths, and consistent handoffs across design, build, and release.

Quality assurance and communication are integrated into the team cadence. The rhythm includes daily standups, weekly delivery syncs, sprint demos, and monthly stakeholder updates. QA combines unit/integration tests, end-to-end smoke tests for critical flows, CI security scans, and manual QA as needed. Retrospectives capture actionable improvements and feed them back into the backlog to continuously improve the process.

## Key Process Docs (in this folder)

- octoacme-project-management-overview.md
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-risks-and-communication.md
- octoacme-release-and-deployment.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-roles-and-personas.md