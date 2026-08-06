# OctoAcme Project Management Docs

This folder contains OctoAcme's program and project management process documents. The guidance here is intended to make project decisions visible, repeatable, and easy for new team members to find. OctoAcme follows a customer-first, iterative delivery model with clear ownership (a named Project Manager and Product Lead for each project), small testable increments, and data-informed decision making.

OctoAcme runs projects through a lightweight lifecycle: Initiation (one-pager and stakeholder alignment) → Planning (backlog, estimates, Definition of Done) → Execution (sprints, PRs, CI, QA) → Release (pre-release checks and rollback plans) → Retrospective (action items fed back into the backlog). Work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done), and blockers escalate through defined levels (team → PM → Product Lead → Sponsor for business-impacting issues).

Core workflows emphasize small pull requests with acceptance criteria, automated CI (unit/integration tests, linting, security scanning) before review, and a staged verification process including smoke tests and manual QA when needed. Communication cadence includes daily standups for the delivery team, weekly PM+PdM syncs, regular demos at the end of sprints or milestones, and monthly stakeholder updates. Risks are captured in a simple Risk Register and reviewed at weekly syncs; retrospectives produce prioritized action items that are tracked as issues.

Docs (links)
- [Project Management Overview](docs/octoacme-project-management-overview.md) — concise intro to roles, lifecycle, and cadence
- [Project Initiation Guide](docs/octoacme-project-initiation.md) — how to validate and authorize new projects
- [Project Planning](docs/octoacme-project-planning.md) — turning initiatives into plans and backlogs
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md) — day-to-day execution, workflows, and blocker escalation
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md) — maintaining the risk register and stakeholder comms
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md) — release types, pre-release checks, and rollback playbook
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md) — running retros and tracking improvements
- [Roles & Personas](docs/octoacme-roles-and-personas.md) — role summaries and responsibilities

How to use
- Use this README.md as the primary landing page for OctoAcme process documentation.
- Keep the links up to date if files are moved or renamed.
- Add process-specific or project-specific docs into `.copilot/` to surface them to Copilot Spaces.

---

*This change implements the README landing page requested in issue #2.*