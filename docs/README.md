# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This folder collects the team's core processes, templates, and checklists for running cross-functional projects. Use this README as a starting point to find the guides you need for initiation, planning, execution, release, and continuous improvement.

OctoAcme follows a pragmatic, iterative project management approach that emphasizes clear lifecycle stages: initiation, planning, execution, release, and retrospective. Work begins with a Project One‑pager that aligns stakeholders on the problem, objective, success metrics, timeline, and key risks. Approved initiatives move into planning where scope is broken into shippable backlog items with acceptance criteria, estimates, a Definition of Done, and a release plan.

Execution is organized around a simple project board and disciplined Pull Request practices (small PRs, linked issues and acceptance criteria, CI checks, required approvals). Quality assurance is built into the lifecycle: unit and integration tests, end‑to‑end smoke tests for critical flows, CI security scans and linters, plus manual QA where necessary. Releases follow a documented checklist (pre‑release verification, staging smoke tests, rollback plan, and post‑deploy validation) to reduce risk and improve observability.

Roles and communication are explicit: Product Managers define outcomes and prioritize the roadmap; Project Managers coordinate delivery, risks, and stakeholder communications; Developers implement features, tests, and docs; QA validates acceptance criteria. The team uses a structured communication cadence (daily standups, regular delivery syncs, and periodic stakeholder updates) and maintains a visible risk register and retrospective action items to drive continuous improvement.

Core Process Documents
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

How to contribute
- Use the "Add Content to Project Management Process Docs" issue template (.github/ISSUE_TEMPLATE) to propose additions or edits.
- Add new process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context for exercises or automated prompts.