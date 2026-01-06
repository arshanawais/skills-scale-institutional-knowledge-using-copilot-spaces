# OctoAcme Project Management Docs

This README centralizes OctoAcme's project management processes and provides direct links to the process documents stored in this repository's docs/ folder. Use this as the single source of truth for project artifacts, cadence, roles, and checklists.

OctoAcme follows a lifecycle approach (Initiation → Planning → Execution → Release → Retrospective). Projects start with a lightweight Project One-pager to capture the problem, goal, success metrics, stakeholders, and initial risks. Planning turns approved initiatives into prioritized backlogs with acceptance criteria, estimates, a Definition of Done, and a release plan. During execution teams work in predictable cadences with a project board to move work through Backlog → Ready → In Progress → In Review → QA → Done, and follow a disciplined PR and CI workflow to protect quality.

Workflows emphasize clear ownership and escalation paths. Project Managers coordinate timelines, risks, and stakeholder communications; Product Managers own outcomes and prioritization; Developers implement and test; QA validates acceptance and release readiness. Communication uses daily standups for immediate triage, weekly delivery syncs to surface risks and dependencies, demos at sprint/milestone ends, and regular stakeholder updates. Blockers escalate from team triage up through PM and sponsor when needed.

Quality assurance and release practices are layered: CI runs unit, integration, and security checks; teams run smoke and end-to-end tests for critical flows; manual QA is used for acceptance where needed; and releases are gated by passing checks, release notes, and rollback plans. Retrospectives and post-release verifications capture learnings and feed improvements back into the backlog.

Process documents
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](docs/octoacme-roles-and-personas.md)

How to use this README
- Link this README from your project README or project board to give stakeholders a single reference.
- Keep links and the list of artifacts up to date; add new process documents under docs/ so they are discoverable.
- If you want this README expanded (e.g., include templates or code snippets), add a follow-up PR that includes those assets.