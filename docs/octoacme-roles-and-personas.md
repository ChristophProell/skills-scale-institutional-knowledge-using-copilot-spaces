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

## Scrum Master

### Role Summary
The Scrum Master facilitates Agile ceremonies, removes process impediments, and coaches the team on Agile practices. They protect the team's focus and foster a culture of continuous improvement.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers and process impediments
- Coach team members on Agile principles and practices
- Shield the team from external distractions and scope creep
- Track and communicate team velocity and sprint health

### Goals
- Maximize team effectiveness and throughput
- Ensure Agile ceremonies deliver value and stay timeboxed
- Foster psychological safety and continuous improvement

### Typical Communication
- Daily standups and sprint ceremonies
- Blocker escalation to PM when needed
- Retrospective action items and team health updates

### Interactions with existing roles
- **Project Manager (PM):** Partners closely to coordinate planning, escalate impediments beyond the team's control, and align on delivery timelines.
- **Product Manager (PdM):** Ensures backlog items are ready for sprint planning and acceptance criteria are clearly defined.
- **Developers:** Coaches on Agile practices, facilitates standups, and actively unblocks technical impediments.

---

## UX Designer

### Role Summary
The UX Designer shapes the user experience by conducting research, creating wireframes and prototypes, and ensuring that features are usable and meet customer needs.

### Responsibilities
- Conduct user research, usability tests, and synthesize insights
- Create wireframes, mockups, and interactive prototypes
- Define interaction patterns and maintain design systems
- Validate designs with users and iterate based on feedback
- Ensure accessibility and usability standards are met

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce rework by validating designs before development begins
- Align product vision with real user needs

### Typical Communication
- Design reviews and critique sessions with developers and PdM
- Usability test reports and design specs
- Collaboration via design tools (e.g., Figma) and PR comments

### Interactions with existing roles
- **Product Manager (PdM):** Collaborates to understand requirements, success metrics, and user personas; translates product goals into design solutions.
- **Developers:** Works closely on design hand-off, reviews implementation for fidelity, and resolves implementation constraints.
- **QA Lead:** Partners on usability validation and acceptance criteria that include UX considerations.
- **Project Manager (PM):** Keeps PM informed of design dependencies and timeline impacts.

---

## DevOps Engineer

### Role Summary
The DevOps Engineer maintains CI/CD pipelines, manages deployment processes, and monitors infrastructure to ensure reliable, repeatable delivery.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure, environments, and configuration as code
- Monitor system health, set up alerting, and respond to incidents
- Enforce security and compliance controls in the pipeline
- Support development and QA teams with environment provisioning

### Goals
- Enable fast, safe, and repeatable software delivery
- Minimize deployment risk and recovery time
- Maximize system reliability and observability

### Typical Communication
- Deployment status updates and incident reports to PM
- Pipeline documentation and runbooks
- On-call coordination and post-incident reviews

### Interactions with existing roles
- **Developers:** Partners on build automation, branching strategy, and release readiness; reviews infrastructure-as-code changes.
- **QA Lead:** Provisions and maintains test environments; supports test automation integration in CI/CD.
- **Project Manager (PM):** Communicates deployment windows, incident status, and environment risks.
- **Product Manager (PdM):** Provides visibility into release readiness and deployment constraints.

---

## QA Lead

### Role Summary
The QA Lead develops the testing strategy, coordinates the QA team, and ensures sufficient test coverage and acceptance criteria are met before release.

### Responsibilities
- Define and maintain the overall testing strategy and test plan
- Coordinate QA team activities across sprints and releases
- Review and contribute to acceptance criteria with PdM and Developers
- Track and report quality metrics (defect rates, test coverage, escape rates)
- Partner with DevOps to integrate automated testing into CI/CD
- Approve release readiness from a quality perspective

### Goals
- Prevent defects from reaching production
- Ensure acceptance criteria and non-functional requirements are validated
- Continuously improve test automation coverage and efficiency

### Typical Communication
- Quality metrics and release readiness reports to PM
- Test plans and defect triage meetings
- Collaboration with Developers on failing tests and coverage gaps

### Interactions with existing roles
- **Developers:** Aligns on test scope, reviews acceptance criteria, and collaborates on automated test implementation.
- **Product Manager (PdM):** Clarifies acceptance criteria and participates in usability and edge-case discussions.
- **DevOps Engineer:** Integrates test suites into CI/CD pipelines and coordinates test environment management.
- **Project Manager (PM):** Reports quality status and release risk; flags blockers that affect the release timeline.
- **UX Designer:** Validates usability and accessibility aspects of delivered features.

---

## Technical Writer

### Role Summary
The Technical Writer creates and maintains documentation for internal and external audiences, ensuring content is accurate, accessible, and aligned with the product.

### Responsibilities
- Author and update process documentation, user guides, and API references
- Maintain documentation repositories and ensure content is versioned and discoverable
- Gather input from developers, PM, and PdM to document features accurately
- Coordinate documentation reviews and sign-offs before releases
- Identify and close documentation gaps discovered during projects

### Goals
- Ensure users and team members can find accurate, up-to-date information
- Reduce support burden through comprehensive, self-service documentation
- Align documentation cadence with the release cycle

### Typical Communication
- Documentation review requests to Developers, PM, and PdM
- Release notes and changelog drafts
- Documentation update tickets in the project backlog

### Interactions with existing roles
- **Project Manager (PM):** Aligns documentation deliverables with project milestones and timelines.
- **Developers:** Gathers technical details and reviews documentation for accuracy.
- **Product Manager (PdM):** Aligns content with product goals, user personas, and feature specifications.
- **QA Lead:** Validates that documented behaviors match tested and accepted functionality.

---

## Business Analyst

### Role Summary
The Business Analyst gathers and documents requirements, maps business processes, and identifies gaps and improvement opportunities to ensure solutions deliver intended business value.

### Responsibilities
- Elicit and document business and functional requirements
- Map current and future-state business processes
- Facilitate requirements workshops and stakeholder interviews
- Define and validate acceptance criteria alongside PdM and QA Lead
- Identify process gaps, redundancies, and improvement opportunities
- Support PM in solution validation and scope management

### Goals
- Ensure delivered solutions meet business needs and stakeholder expectations
- Reduce ambiguity in requirements before development begins
- Bridge the gap between business stakeholders and the delivery team

### Typical Communication
- Requirements documents, user stories, and process maps
- Stakeholder interview summaries and workshop outputs
- Regular check-ins with PM and PdM on scope clarity

### Interactions with existing roles
- **Product Manager (PdM):** Collaborates closely on translating business needs into prioritized backlog items and feature specifications.
- **Project Manager (PM):** Supports scope management, validates that delivered solutions meet requirements, and flags gaps.
- **Developers:** Provides detailed functional requirements and answers clarification questions during implementation.
- **QA Lead:** Collaborates on defining acceptance criteria and participates in acceptance testing.
- **Stakeholders:** Primary liaison for gathering, documenting, and validating business requirements.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For a cross-role collaboration reference, see [octoacme-role-interactions-and-raci.md](octoacme-role-interactions-and-raci.md).

