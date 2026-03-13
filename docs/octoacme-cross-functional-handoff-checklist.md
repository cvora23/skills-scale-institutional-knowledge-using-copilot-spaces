# OctoAcme — Cross-Functional Handoff Checklist

## Purpose
This checklist ensures that key information and expectations are clearly communicated at each transition point in the delivery process. Use it at the relevant handoff to prevent gaps, rework, and delays.

---

## 1. UX/UI Designer → Developer Handoff

Before a Developer begins implementation of a designed feature, the following should be confirmed:

- [ ] Final design files (e.g., Figma) are linked from the relevant issue or PR
- [ ] Design annotations explain interactive states, edge cases, and responsive behavior
- [ ] Component specifications (spacing, colors, typography) match the design system
- [ ] Accessibility requirements (WCAG level, keyboard navigation, ARIA labels) are documented
- [ ] UX Designer is available to answer implementation questions during the sprint
- [ ] Developer has reviewed the design and flagged any technical constraints or concerns
- [ ] Acceptance criteria include design fidelity checkpoints (reviewed by UX Designer before QA)

---

## 2. Developer → QA Lead Handoff

Before a feature moves into the QA column on the project board, the following should be confirmed:

- [ ] Feature branch is merged (or ready for review) and deployed to a stable test environment
- [ ] Developer has completed self-review and unit/integration tests pass in CI
- [ ] PR description includes a summary of changes, linked issue, and acceptance criteria
- [ ] Known limitations or deferred items are documented in the issue or PR
- [ ] Test environment URL or deployment details are shared with QA Lead
- [ ] QA Lead has a clear list of acceptance criteria and test cases to validate
- [ ] Automated tests are integrated into the CI pipeline and passing

---

## 3. QA Lead → Release (DevOps Engineer / PM) Handoff

Before a release is approved and deployed, the following should be confirmed:

- [ ] All acceptance criteria are verified and documented as passing
- [ ] No open critical or high-severity defects remain (or exceptions are documented and accepted)
- [ ] Regression test suite has been executed and results are available
- [ ] QA sign-off is communicated to the Project Manager (PM)
- [ ] DevOps Engineer confirms the deployment plan, release window, and rollback procedure
- [ ] Release notes or changelog entry is prepared (PdM or BA can own this)
- [ ] Stakeholder / Executive Sponsor (if required) has approved the release milestone
- [ ] Post-release monitoring criteria and alerting are confirmed with DevOps Engineer

---

## 4. Business Analyst → Product Manager / Developer Handoff (Requirements)

Before requirements are handed off for development, the following should be confirmed:

- [ ] Requirements are documented as user stories with clear acceptance criteria
- [ ] Use cases and process flows are attached or linked from the relevant epic/issue
- [ ] Stakeholder sign-off on requirements is documented
- [ ] Ambiguities and open questions are resolved (or explicitly flagged)
- [ ] Product Manager has reviewed and approved the requirements for inclusion in the backlog
- [ ] Developers have had a chance to ask clarifying questions (e.g., in a refinement session)
- [ ] Scope boundaries are clearly defined to prevent scope creep

---

## Related Documents
- [Roles & Personas](./octoacme-roles-and-personas.md)
- [RACI Template](./octoacme-roles-raci-template.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
