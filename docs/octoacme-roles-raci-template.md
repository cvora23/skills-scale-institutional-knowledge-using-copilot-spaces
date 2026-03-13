# OctoAcme — Roles RACI Template

## Purpose
This RACI matrix maps key project process activities and decisions to the roles defined in [`octoacme-roles-and-personas.md`](./octoacme-roles-and-personas.md).

Use this template to align the team at project kickoff or when onboarding a new role.

## RACI Key
| Code | Meaning |
|------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; approves deliverables |
| **C** | **Consulted** — provides input before decisions are made |
| **I** | **Informed** — notified of decisions or outcomes |

---

## RACI Matrix

> **Roles abbreviation key:**
> - **PM** = Project Manager
> - **PdM** = Product Manager
> - **Dev** = Developer(s)
> - **UX** = UX/UI Designer
> - **QA** = QA Lead
> - **DevOps** = DevOps Engineer
> - **BA** = Business Analyst
> - **Sponsor** = Stakeholder / Executive Sponsor

| Activity / Decision | PM | PdM | Dev | UX | QA | DevOps | BA | Sponsor |
|---|---|---|---|---|---|---|---|---|
| **Initiation** | | | | | | | | |
| Define project charter / one-pager | A | C | I | I | I | I | C | A |
| Identify stakeholders and communication needs | R | C | I | I | I | I | R | I |
| Confirm project scope and objectives | A | R | C | | | | C | C |
| Secure funding and executive sponsorship | I | I | | | | | | A/R |
| **Planning** | | | | | | | | |
| Create project plan and milestones | R/A | C | C | C | C | C | C | I |
| Prioritize and groom backlog | C | R/A | C | C | I | I | C | I |
| Document requirements and use cases | C | A | C | C | I | I | R | I |
| Define UX/design scope and deliverables | C | A | C | R/A | I | I | C | I |
| Define test strategy and quality gates | C | C | C | | R/A | C | C | I |
| Plan CI/CD pipeline and environments | I | I | C | | C | R/A | | I |
| Identify and document risks | R | C | C | C | C | C | C | I |
| **Execution** | | | | | | | | |
| Implement features | C | I | R/A | C | I | C | I | |
| Create and deliver design specs | I | C | C | R/A | I | I | I | |
| Build and maintain CI/CD pipelines | I | I | C | | C | R/A | | |
| Write and execute test cases | I | C | C | C | R/A | C | I | |
| Clarify requirements during development | C | A | C | C | | | R | I |
| Manage defects and triage | C | C | R | C | R/A | C | | |
| Update risk register | R/A | C | C | C | C | C | C | I |
| **Release** | | | | | | | | |
| QA sign-off / release gate approval | A | C | C | C | R | C | | I |
| Deploy to production | A | I | C | | I | R | | I |
| Rollback execution (if needed) | A | I | C | | C | R | | I |
| Write release notes / changelog | C | R | C | C | I | I | C | I |
| Communicate release to stakeholders | R/A | C | I | I | I | I | I | I |
| **Closure & Retrospective** | | | | | | | | |
| Facilitate retrospective | R/A | C | C | C | C | C | C | I |
| Document lessons learned | R | C | C | C | C | C | C | I |
| Provide final project status to sponsor | R/A | C | I | I | I | I | I | I |
| Archive project artifacts | R/A | C | C | | | | C | I |

---

## How to customize this template
1. Copy this file into your project's `docs/` or `.copilot/` folder.
2. Update role abbreviations if your project uses different titles.
3. Adjust R/A/C/I assignments to match your team's actual working agreements.
4. Review this matrix at project kickoff and revisit when scope changes.

---

## Related Documents
- [Roles & Personas](./octoacme-roles-and-personas.md)
- [Cross-Functional Handoff Checklist](./octoacme-cross-functional-handoff-checklist.md)
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation](./octoacme-project-initiation.md)
