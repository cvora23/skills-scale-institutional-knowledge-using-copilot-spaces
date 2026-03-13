# OctoAcme Project Management Docs

## Overview

OctoAcme's project management approach follows a lightweight, repeatable lifecycle designed for cross-functional delivery: **Initiation → Planning → Execution & Tracking → Release → Close/Retrospective**. Work begins with a clear business need and measurable outcomes captured in a **Project One-pager/Charter** (problem statement, SMART objective, success metrics, stakeholders, timeline, risks, and resourcing). A decision gate—typically involving the Product Lead and sponsor—confirms that success criteria, priority, and team availability are sufficient before moving from exploration into structured planning. Key artifacts maintained throughout the lifecycle include the project backlog, Definition of Done (DoD), risk register, release plan, and retrospective action items.

Roles are intentionally explicit to ensure clear ownership. The **Project Manager (PM)** coordinates delivery mechanics—plans, schedules, risks, communications, and meeting facilitation—while the **Product Manager (PdM)** defines outcomes, prioritizes the backlog, and measures success. **Developers** design and implement features with testability and maintainability in mind, and **QA/Testing** validates acceptance criteria and quality before release. **Stakeholders** provide inputs, approvals, and business context. The process emphasizes psychological safety and data-informed decision-making to encourage feedback and continuous iteration.

Execution is managed through a **project board workflow** with columns: Backlog, Ready, In Progress, In Review, QA, and Done. The PR process favors **small pull requests** explicitly linked to issues and acceptance criteria, with CI-backed checks (tests, linting, and security scanning) required before review, and at least one approval before merge. Quality expectations include unit tests for new logic, integration tests where needed, and end-to-end smoke tests for critical flows—paired with manual QA when appropriate for feature acceptance. Progress is tracked via delivery metrics (velocity/burndown) and operational dashboards (errors, latency, and usage).

Communication is maintained through a consistent team rhythm: **daily standups** for blockers and dependencies, a **weekly delivery sync** for progress and risk surfacing, and **end-of-sprint demos/reviews** for stakeholder alignment. Stakeholder updates follow a standard weekly status template covering progress, next steps, risks/blockers, and decisions needed. Risks and dependencies are tracked in a **risk register** and reviewed weekly, with a defined escalation path (team triage → PM → Product Lead → Sponsor) for business-impacting issues. After sprints, releases, or incidents, OctoAcme closes the loop with structured **retrospectives** that produce a small set of owned, time-bound action items fed back into the backlog for continuous improvement.

---

## Process Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level overview of OctoAcme's PM lifecycle, principles, and key artifacts |
| [Project Initiation](./octoacme-project-initiation.md) | How to start new projects: one-pager/charter template, decision gates, and kick-off checklist |
| [Project Planning](./octoacme-project-planning.md) | Backlog setup, estimation, Definition of Done, risk register, and sprint planning |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Daily standups, project board workflow, PR process, CI checks, and progress reporting |
| [Risks & Communication](./octoacme-risks-and-communication.md) | Risk register maintenance, escalation path, and stakeholder status update template |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Release types, deployment checklists, rollback procedures, and go/no-go criteria |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives, capturing action items, and feeding improvements into the backlog |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Key responsibilities and expectations for PM, PdM, Developers, QA/Testing, and Stakeholders |
