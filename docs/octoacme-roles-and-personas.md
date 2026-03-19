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
The Scrum Master is a servant-leader who facilitates agile ceremonies, shields the team from interruptions, and continuously coaches the team toward better ways of working. They hold no direct authority over team members but are accountable for the health of the agile process.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Remove impediments and escalate blockers that cannot be resolved at the team level
- Coach the team on agile principles and help establish healthy team norms
- Track velocity and help the team forecast deliveries
- Shield the team from scope creep and context-switching

### Goals
- Keep the team productive, focused, and continuously improving
- Ensure ceremonies are valuable, time-boxed, and outcome-oriented
- Foster a psychologically safe environment for open communication

### Typical Communication
- Daily standup facilitation and follow-up on blockers
- Sprint retrospective notes and improvement action items
- Impediment log maintained and shared with Project Manager and leadership

### Interactions with Existing Roles
- **Developers:** Day-to-day coaching on agile practices; removes their blockers so they can focus on delivery.
- **Product Managers:** Coordinates backlog refinement sessions; ensures user stories are sprint-ready before planning.
- **Project Managers:** Collaborates on cross-team dependencies and escalations; shares velocity data to inform project-level timelines.

---

## UX Designer

### Role Summary
The UX Designer is responsible for understanding user needs, translating them into intuitive experiences, and ensuring design quality throughout the product lifecycle. They own wireframes, prototypes, and design documentation that guide implementation.

### Responsibilities
- Conduct user research, usability tests, and synthesize findings into actionable insights
- Create user flows, wireframes, high-fidelity mockups, and interactive prototypes
- Define and maintain a design system or component library where applicable
- Validate designs with users and iterate based on feedback
- Document design decisions and acceptance criteria for visual/interaction specs

### Goals
- Deliver a consistent, usable, and accessible user experience
- Reduce re-work by aligning design and engineering expectations early
- Advocate for the end user in all product decisions

### Typical Communication
- Design review sessions and handoff notes in design tooling (e.g., Figma)
- Participation in sprint planning to align on design readiness
- Usability test reports shared with Product Manager and stakeholders

### Interactions with Existing Roles
- **Developers:** Provides detailed design specs and is available to answer implementation questions during development; reviews built features against designs before release.
- **Product Managers:** Collaborates on translating requirements into user-centered designs; shares research insights that inform backlog prioritization.
- **Project Managers:** Communicates design task estimates and flags risks to timelines when additional research or iteration is needed.

---

## Tech Lead

### Role Summary
The Tech Lead provides technical leadership to the engineering team, ensuring architectural coherence, code quality, and alignment with long-term technical strategy. They bridge the gap between engineering execution and product/project planning.

### Responsibilities
- Define and document technical architecture and design decisions (ADRs)
- Lead and coordinate technical design discussions and code reviews
- Mentor developers and promote engineering best practices
- Identify and address technical debt and security considerations
- Provide technical estimates and feasibility assessments for new work
- Coordinate with external teams on integrations and shared infrastructure

### Goals
- Maintain a healthy, scalable, and maintainable codebase
- Reduce unplanned technical work through proactive risk identification
- Grow the technical capabilities of the team

### Typical Communication
- Architecture decision records (ADRs) and technical design docs
- Code review feedback and engineering-wide tech sync meetings
- Technical risk items added to the project risk register

### Interactions with Existing Roles
- **Developers:** Provides technical guidance and mentorship; pair programs on complex areas; leads code reviews and approves PRs for high-risk changes.
- **Product Managers:** Advises on technical feasibility and trade-offs when scoping features; raises technical constraints that affect the product roadmap.
- **Project Managers:** Contributes technical estimates to project plans; surfaces technical risks early; communicates status of critical technical workstreams.

---

## QA Automation Engineer

### Role Summary
The QA Automation Engineer designs, builds, and maintains automated test suites that verify quality throughout the delivery pipeline. They establish quality gates and partner with developers to embed testing into every stage of development.

### Responsibilities
- Design, implement, and maintain automated test frameworks (unit, integration, end-to-end)
- Define and enforce quality gates in CI/CD pipelines
- Investigate and triage failures in automated test runs
- Create and maintain test plans and test case documentation
- Contribute to Definition of Done criteria with measurable quality standards
- Report on test coverage, defect trends, and release readiness

### Goals
- Shift quality left by catching defects early and cheaply
- Increase confidence in releases through consistent automated coverage
- Reduce manual testing overhead and release cycle time

### Typical Communication
- Test coverage and defect reports shared before sprint reviews
- Quality gate status communicated in CI/CD dashboards and release checklists
- Participation in sprint planning to estimate and plan test automation work

### Interactions with Existing Roles
- **Developers:** Partners on writing testable code and shared test utilities; reviews test coverage as part of the PR process; coordinates on flaky test remediation.
- **Product Managers:** Aligns automated test scenarios with acceptance criteria; surfaces quality risks that may affect release scope or timelines.
- **Project Managers:** Provides release readiness assessments; flags quality-related blockers that could affect go/no-go decisions.

---

## Business Analyst

### Role Summary
The Business Analyst bridges business stakeholders and the delivery team by eliciting, documenting, and validating requirements. They ensure that what is built aligns with business needs and that acceptance criteria are clear and testable.

### Responsibilities
- Elicit and document business requirements, use cases, and business rules
- Facilitate requirements workshops and stakeholder interviews
- Translate business needs into well-structured user stories and acceptance criteria
- Identify gaps, conflicts, and ambiguities in requirements and resolve them with stakeholders
- Support UAT planning and validation activities
- Maintain a requirements traceability matrix where applicable

### Goals
- Ensure the team builds the right thing by making requirements unambiguous and testable
- Improve handoffs between business stakeholders and the delivery team
- Reduce mid-sprint scope changes through thorough upfront analysis

### Typical Communication
- Requirements documents, user stories, and process flow diagrams
- Stakeholder review sessions and requirements sign-off meetings
- Participation in backlog refinement and sprint planning

### Interactions with Existing Roles
- **Developers:** Clarifies requirements and acceptance criteria during development; answers functional questions to unblock implementation; validates that built features meet specified business rules.
- **Product Managers:** Collaborates on backlog refinement and ensures user stories reflect business intent; provides detailed analysis to support prioritization decisions.
- **Project Managers:** Flags requirements risks and scope changes early; provides input on estimation for analysis and documentation tasks; supports stakeholder communication planning.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [`octoacme-role-artifact-ownership.md`](./octoacme-role-artifact-ownership.md) for a RACI-lite matrix that maps roles to key project artifacts and cross-functional handoffs.

