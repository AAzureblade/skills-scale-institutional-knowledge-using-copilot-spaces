# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. These docs centralize how OctoAcme plans, executes, and delivers product work — helping new teammates and contributors quickly find the processes, roles, and artifacts used across projects.

OctoAcme uses a lightweight, iterative lifecycle: Initiation → Planning → Execution → Release → Retrospective. Initiation captures the problem, goals, stakeholders, and success metrics in a Project One‑pager. Planning turns approved initiatives into prioritized, estimated backlog items with clear acceptance criteria, a Definition of Done, and a release plan. Execution uses a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done), small PRs linked to issues, CI-driven tests and security scans, and a layered QA approach that includes unit, integration, and smoke tests. Releases require passing CI, release notes, a rollback plan, and smoke tests in staging before production deployment.

Roles are explicit: Product Managers (define outcomes and prioritize), Project Managers (coordinate delivery, risk, and communication), Developers (build and test), and QA (validate acceptance). Team communication combines daily standups, weekly delivery syncs, sprint demos, and regular PM+PdM alignment and stakeholder updates. Risk and escalation paths are documented (team → PM → Product Lead → Sponsor), incident communication templates are provided, and retrospectives convert learnings into tracked action items.

Quality assurance is enforced through small PRs with acceptance criteria, automated CI tests and security scanning, manual QA when needed, and pre-release smoke tests and rollback plans. The docs below contain templates, checklists, and checkboxes to help teams follow the process and capture decisions.

## Documentation Links
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to use these docs
- Keep the Project One-pager and decision logs in the project repo under docs/ or .copilot/
- Follow the checklists in each doc when initiating, planning, executing, and releasing work
- Add or propose edits using the repository's issue template for process docs (see .github/ISSUE_TEMPLATE)

## Acceptance Criteria
- [ ] README is located at docs/README.md
- [ ] Content aligns with existing process docs in docs/
- [ ] README improves discoverability and provides links to all process docs
- [ ] PR references issue #2 and adds AAzureblade as a reviewer
