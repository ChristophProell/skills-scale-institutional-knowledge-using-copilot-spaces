# OctoAcme — Role Interactions & RACI

## Purpose
Provide a lightweight ownership reference for common project activities and a quick checklist for when to engage each role across the project lifecycle.

For full role descriptions see [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md).

---

## RACI Key

| Symbol | Meaning |
|--------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome; approves |
| **C** | Consulted — provides input before action |
| **I** | Informed — kept up-to-date on decisions/outcomes |

---

## RACI Matrix — Common Lifecycle Activities

| Activity | PM | PdM | Dev | Scrum Master | UX Designer | DevOps | QA Lead | Tech Writer | BA |
|---|---|---|---|---|---|---|---|---|---|
| **Initiation** | | | | | | | | | |
| Define problem statement & success metrics | C | A/R | I | I | C | I | I | I | C |
| Identify stakeholders & champions | A/R | C | I | I | I | I | I | I | C |
| Draft Project One-pager | A/R | C | I | I | I | I | I | I | C |
| Approve go/no-go to planning | A | R | I | I | I | I | I | I | I |
| **Planning** | | | | | | | | | |
| Backlog creation & prioritization | C | A/R | C | C | C | I | C | I | R |
| Define acceptance criteria | C | A | C | C | C | I | C | I | R |
| Create release plan & milestones | A/R | C | C | C | I | C | C | I | I |
| Initial test plan | C | C | C | I | I | C | A/R | I | C |
| UX discovery & wireframes | I | C | C | I | A/R | I | I | I | C |
| Infrastructure & environment planning | I | I | C | I | I | A/R | C | I | I |
| **Execution** | | | | | | | | | |
| Sprint facilitation | C | I | R | A/R | I | I | I | I | I |
| Feature implementation | I | C | A/R | C | C | C | I | I | I |
| Design review & sign-off | I | C | C | I | A/R | I | I | I | I |
| CI/CD pipeline management | I | I | C | I | I | A/R | C | I | I |
| Test execution & defect tracking | I | C | C | I | C | C | A/R | I | C |
| Documentation of features | I | C | C | I | C | I | C | A/R | C |
| Blocker escalation | A/R | C | C | C | I | I | I | I | I |
| **Release** | | | | | | | | | |
| Release readiness sign-off | A | R | C | I | I | C | C | I | I |
| Deployment execution | I | I | C | I | I | A/R | C | I | I |
| Release notes | C | C | C | I | I | I | C | A/R | I |
| Post-deploy verification | C | I | C | I | I | C | A/R | I | I |
| Stakeholder announcement | A/R | C | I | I | I | I | I | C | I |
| **Retrospective** | | | | | | | | | |
| Facilitate retrospective | A | I | I | R | I | I | I | I | I |
| Capture action items | C | I | C | R | I | I | I | C | I |
| Update process documentation | C | I | I | I | I | I | I | A/R | C |
| Track & close action items | A/R | I | C | C | I | I | I | I | I |

> **Note:** A/R indicates the same person is both Accountable and Responsible for that activity.

---

## Role Engagement Checklist

Use this checklist to decide which roles to involve and when during a project.

### Initiation Phase
- [ ] **Business Analyst** — engage early to facilitate stakeholder interviews and document requirements
- [ ] **Product Manager (PdM)** — define problem statement and success metrics
- [ ] **Project Manager (PM)** — lead initiation activities and create One-pager

### Planning Phase
- [ ] **UX Designer** — involve as soon as user-facing features are in scope; begin discovery and wireframing
- [ ] **QA Lead** — engage during backlog refinement to review acceptance criteria and draft test plan
- [ ] **DevOps Engineer** — consult on environment strategy, pipeline readiness, and infrastructure needs
- [ ] **Business Analyst** — drive requirements elaboration and acceptance criteria definition
- [ ] **Scrum Master** — facilitate planning ceremonies and confirm team capacity

### Execution Phase
- [ ] **Scrum Master** — runs daily standups and sprint ceremonies; removes blockers
- [ ] **UX Designer** — available for design review and to answer implementation questions
- [ ] **QA Lead** — begins testing as features are completed; reports defect metrics each sprint
- [ ] **DevOps Engineer** — maintains CI/CD pipelines and test environments throughout execution
- [ ] **Technical Writer** — starts drafting documentation for features delivered in the sprint

### Release Phase
- [ ] **DevOps Engineer** — owns deployment execution and post-deploy monitoring
- [ ] **QA Lead** — confirms release readiness; validates smoke tests pass in production
- [ ] **Technical Writer** — finalises release notes and publishes updated user documentation
- [ ] **Project Manager (PM)** — approves release go/no-go and coordinates stakeholder announcement

### Retrospective Phase
- [ ] **Project Manager (PM)** or **Scrum Master** — facilitates the retrospective
- [ ] **Technical Writer** — documents action items and updates relevant process docs
- [ ] **All roles** — participate and contribute improvement suggestions

---

## Quick Reference: Who to Call

| Need | Primary contact | Secondary |
|---|---|---|
| Clarify a business requirement | Business Analyst | Product Manager (PdM) |
| Review UX or design decision | UX Designer | Product Manager (PdM) |
| Pipeline or deployment issue | DevOps Engineer | Project Manager (PM) |
| Quality risk or test coverage gap | QA Lead | Project Manager (PM) |
| Process doc update | Technical Writer | Project Manager (PM) |
| Sprint blocker | Scrum Master | Project Manager (PM) |
| Scope change | Product Manager (PdM) | Project Manager (PM) |
