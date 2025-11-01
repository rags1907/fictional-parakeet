# OctoAcme Project Management Docs

## Introduction
This repository folder contains OctoAcme's program-level project management documentation. Use this README as the single-entry index and landing page for the lifecycle artifacts, templates, and process guidance that help teams plan, execute, and deliver work predictably and safely.

## Process summary
OctoAcme runs projects through a concise, iterative lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Initiation focuses on a lightweight Project One‑pager that captures the problem, measurable goals, stakeholders, and initial risks. Planning turns approved initiatives into a prioritized, estimated backlog, a Definition of Done, and a release/milestone plan. Execution delivers work in short, testable increments with visible progress tracking; closure verifies releases and captures learnings via blameless retrospectives so the team can improve continuously.

Workflows emphasize small, CI-backed pull requests, a visible project board (Backlog → Ready → In Progress → In Review → QA → Done), and clear escalation paths for blockers. Teams follow checklists and templates for releases, risks, and handoffs to make cross-team coordination repeatable. Blocker escalation proceeds from team triage in standups up to sponsor-level notification for business-impacting issues.

Roles and ownership are explicit: Project Managers coordinate delivery, schedules, risks, and communications; Product Managers (PdMs) define outcomes, prioritize the backlog, and validate success; Developers implement and test; and QA owns verification against acceptance criteria. Each key artifact (one-pager, backlog, risk register, release notes, retrospectives) has a named owner to maintain clarity and accelerate decision-making.

Communication and quality assurance are embedded in cadence and CI. Rituals include daily standups, weekly delivery syncs, demos at sprint/milestone end, and monthly stakeholder updates. QA requirements include unit and integration tests, E2E smoke flows for critical paths, automated security scanning in CI, and manual QA when needed. Releases only proceed when CI is green, acceptance criteria are met, and pre-release checklists (rollback plan, smoke tests, release notes) are complete.

## Docs index
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning Guide](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

## How to use this README
- Keep this README up to date as the canonical table of contents for process docs.
- Link to the appropriate doc in this folder from project repos (Project One‑pagers should reference the relevant process docs).
- For Copilot Spaces: add process-specific docs into `.copilot/` if you want Copilot context to include them.

## Contributing
If you'd like to propose edits or additions, open a PR with the new content and reference issue #2 (README request).