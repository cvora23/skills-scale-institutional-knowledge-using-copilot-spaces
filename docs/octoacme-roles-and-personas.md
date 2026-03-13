# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## UX/UI Designer

### Role Summary
UX/UI Designers create user-centered interfaces and experiences. They translate product requirements into visual designs and ensure solutions are usable, accessible, and consistent.

### Responsibilities
- Design wireframes, mockups, and interactive prototypes
- Conduct user research and synthesize insights into actionable recommendations
- Maintain design systems and ensure visual consistency across the product
- Collaborate on acceptance criteria that include usability and accessibility standards
- Participate in sprint reviews to evaluate design fidelity in implemented features

### Goals
- Deliver intuitive, accessible experiences that satisfy user needs
- Reduce design rework through early alignment with Product and Engineering
- Establish and maintain a coherent visual language across the product

### Typical Communication
- Design reviews and critique sessions with Product Managers and Developers
- Annotated design files (e.g., Figma) linked from issues or PRs
- User research summaries shared with the broader team

### Interactions with Existing Roles
- **Works with Product Managers (PdM):** Translates product requirements and user stories into design concepts; provides early design feedback to help PdMs refine priorities.
- **Works with Developers:** Hands off finalized design specs for implementation; reviews in-progress builds for design fidelity and flags deviations.
- **Provides to Project Managers (PM):** Design completion status and flags on scope changes that may affect timelines.

---

## QA Lead

### Role Summary
The QA Lead owns the quality strategy for the project. They define test plans, manage testing execution, and act as the quality gate before release.

### Responsibilities
- Develop and maintain test plans, test cases, and test environments
- Manage manual and automated testing across feature and regression cycles
- Track, prioritize, and drive resolution of defects
- Define and enforce quality gates and Definition of Done criteria
- Coordinate with Developers and the PM on test readiness and sign-off timelines

### Goals
- Prevent defects from reaching production
- Establish repeatable, efficient testing processes
- Ensure features meet acceptance criteria defined by the Product Manager

### Typical Communication
- Test plans and defect reports shared with the team
- QA sign-off communicated to PM before release
- Daily standup participation to surface blocking defects early

### Interactions with Existing Roles
- **Works with Developers:** Reviews implementation against acceptance criteria; collaborates on automated test coverage and defect triage.
- **Works with Product Managers (PdM):** Validates acceptance criteria completeness; escalates ambiguous requirements before testing begins.
- **Provides to Project Managers (PM):** Test status updates, defect metrics, and go/no-go recommendations for release gates.
- **Works with DevOps Engineer:** Requests stable test environments and coordinates CI pipeline integration for automated tests.

---

## DevOps Engineer

### Role Summary
DevOps Engineers own the CI/CD pipelines, infrastructure automation, and deployment reliability. They bridge development and operations to enable fast, safe, and repeatable delivery.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and build automation
- Manage infrastructure-as-code, environment provisioning, and configuration
- Monitor application health, performance, and availability
- Implement rollback, recovery, and incident response procedures
- Enforce security and compliance policies in the delivery pipeline

### Goals
- Enable reliable, repeatable deployments with minimal manual intervention
- Reduce deployment lead time and mean time to recovery (MTTR)
- Ensure infrastructure and pipeline changes are reviewed and version-controlled

### Typical Communication
- Pipeline status and deployment notifications shared with the team
- Infrastructure change proposals reviewed via PRs
- Incident post-mortems and reliability reports

### Interactions with Existing Roles
- **Works with Developers:** Collaborates on build automation, branching strategy, and CI integration; reviews infrastructure requirements for new features.
- **Works with QA Lead:** Provides and maintains stable test environments; integrates automated tests into CI pipelines.
- **Provides to Project Managers (PM):** Deployment readiness status, environment availability, and risk flags for release windows.
- **Escalates to Project Managers (PM):** Infrastructure incidents or pipeline failures that may affect delivery timelines.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between stakeholder needs and technical solutions. They gather, document, and validate requirements to ensure the team builds the right thing.

### Responsibilities
- Elicit and document business requirements, use cases, and process flows
- Translate stakeholder needs into clear, actionable user stories and acceptance criteria
- Analyze current workflows and identify improvement opportunities
- Support the Product Manager in backlog refinement and prioritization
- Validate that delivered solutions meet the original business requirements

### Goals
- Ensure stakeholder needs are fully understood and clearly represented in project artifacts
- Reduce ambiguity and rework caused by incomplete or misunderstood requirements
- Facilitate shared understanding between business and technical teams

### Typical Communication
- Requirements documents, use cases, and process diagrams shared with PM and PdM
- Refinement sessions with Product Manager and Developers
- Stakeholder interviews and workshop summaries

### Interactions with Existing Roles
- **Works with Product Managers (PdM):** Provides detailed requirements and use-case documentation to support backlog prioritization and feature definition.
- **Works with Project Managers (PM):** Flags scope changes and requirement gaps that may affect timelines or deliverables.
- **Works with Developers:** Clarifies requirements during implementation; reviews delivered solutions against documented acceptance criteria.
- **Provides to Stakeholder/Executive Sponsor:** Summarized requirement validation and traceability reports.

---

## Stakeholder / Executive Sponsor

### Role Summary
The Executive Sponsor is the senior leader accountable for the project's strategic alignment and business outcomes. They champion the project, secure resources, and remove organizational blockers.

### Responsibilities
- Align the project to organizational strategy and business objectives
- Secure funding, headcount, and executive support
- Remove high-level blockers that cannot be resolved by the delivery team
- Provide go/no-go decisions for major milestones and releases
- Review and approve key deliverables (e.g., project charter, release plan)

### Goals
- Ensure the project delivers the intended business value
- Maintain executive visibility and confidence in the project
- Enable the team by removing political or resource-related impediments

### Typical Communication
- Monthly or milestone-based briefings from the Project Manager and Product Manager
- Executive status summaries (written or presented)
- Escalation conversations for critical decisions or risks

### Interactions with Existing Roles
- **Receives briefings from Project Managers (PM):** Regular status updates, risk summaries, and escalation requests.
- **Receives briefings from Product Managers (PdM):** Product strategy updates, outcome metrics, and strategic trade-off recommendations.
- **Escalation point for Project Managers (PM):** Final escalation tier for business-impacting blockers and go/no-go decisions.
- **Provides to all roles:** Strategic direction, priority guidance, and resource authorization.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [`octoacme-cross-functional-handoff-checklist.md`](./octoacme-cross-functional-handoff-checklist.md) for role interaction checkpoints across delivery phases.
- See [`octoacme-roles-raci-template.md`](./octoacme-roles-raci-template.md) for a RACI matrix mapping key process decisions to roles.

