# OctoAcme Role-to-Artifact Ownership Matrix (RACI-Lite)

This document provides a lightweight RACI-lite reference that maps key project artifacts and cross-functional handoffs to the roles defined in [`octoacme-roles-and-personas.md`](./octoacme-roles-and-personas.md).

**Legend**
| Code | Meaning |
|------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome, approves or signs off |
| **C** | Consulted — provides input before or during |
| **I** | Informed — notified of progress or decisions |

---

## Project Lifecycle Artifact Ownership

| Artifact / Activity | Project Manager | Product Manager | Developers | Scrum Master | UX Designer | Tech Lead | QA Automation Engineer | Business Analyst |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Project Charter / One-pager | **A** | **C** | I | I | I | I | I | **C** |
| Product Roadmap | I | **A** | C | I | **C** | **C** | I | **C** |
| Sprint Backlog | **C** | **A** | **C** | **R** | **C** | **C** | **C** | **C** |
| User Stories & Acceptance Criteria | I | **A** | **C** | I | **C** | **C** | **C** | **R** |
| UX Designs & Wireframes | I | **C** | **C** | I | **A/R** | **C** | I | **C** |
| Architecture Decision Records (ADRs) | I | **C** | **C** | I | I | **A/R** | **C** | I |
| Test Plan & Automated Test Suites | **C** | I | **C** | I | I | **C** | **A/R** | **C** |
| Risk Register | **A/R** | **C** | **C** | **C** | I | **C** | **C** | **C** |
| Release Checklist / Go-No-Go | **A** | **C** | **R** | I | **C** | **R** | **R** | I |
| Sprint Retrospective Notes | **C** | **C** | **C** | **A/R** | **C** | **C** | **C** | **C** |
| Status Reports & Stakeholder Updates | **A/R** | **C** | I | **C** | I | **C** | I | **C** |
| Definition of Done | **C** | **C** | **R** | **A** | **C** | **R** | **R** | **C** |
| Requirements Traceability Matrix | **C** | **C** | I | I | I | **C** | **C** | **A/R** |

---

## Cross-Functional Handoff Checklist

Use the following checklist at key handoff points to maintain accountability and reduce rework.

### Discovery → Planning Handoff
- [ ] Business Analyst has documented requirements, use cases, and acceptance criteria
- [ ] Product Manager has reviewed and approved user stories
- [ ] UX Designer has provided wireframes or design specs for in-scope features
- [ ] Tech Lead has assessed technical feasibility and flagged constraints
- [ ] Project Manager has updated the project plan with scope, milestones, and dependencies

### Planning → Execution Handoff
- [ ] Sprint backlog is prioritized and user stories are sprint-ready (no open blockers)
- [ ] Acceptance criteria are clear and agreed upon by Product Manager, Business Analyst, and QA Automation Engineer
- [ ] UX designs have been reviewed by Developers; handoff questions are resolved
- [ ] QA Automation Engineer has drafted a test plan aligned with acceptance criteria
- [ ] Scrum Master has confirmed team capacity and removed any planning impediments

### Execution → Release Handoff
- [ ] All acceptance criteria have been met and verified by QA Automation Engineer
- [ ] Tech Lead has approved code through review and confirms no critical technical debt was introduced
- [ ] UX Designer has verified the built features match design specifications
- [ ] Business Analyst has confirmed business rules are implemented correctly
- [ ] Project Manager has completed the release checklist and confirmed go/no-go readiness
- [ ] Product Manager has validated the release against success metrics

### Release → Retrospective Handoff
- [ ] Release notes and deployment outcomes have been documented
- [ ] Defects and incidents from the release have been logged
- [ ] Scrum Master has scheduled and facilitated the retrospective
- [ ] Action items from retrospective are assigned owners and added to the next sprint backlog
- [ ] Project Manager has shared the post-release status update with stakeholders

---

## Role Interaction Summary

The table below summarizes the most important day-to-day interactions between the new and existing roles.

| Initiating Role | With | Primary Interaction |
|---|---|---|
| Scrum Master | Developers | Impediment removal, agile coaching, daily standup |
| Scrum Master | Product Manager | Backlog refinement facilitation, sprint readiness |
| Scrum Master | Project Manager | Cross-team dependency coordination, velocity reporting |
| UX Designer | Developers | Design handoff, spec clarification, feature review |
| UX Designer | Product Manager | Requirements → design translation, research insights |
| UX Designer | Project Manager | Design task estimates, timeline risk communication |
| Tech Lead | Developers | Code review, mentorship, architecture guidance |
| Tech Lead | Product Manager | Feasibility assessment, technical trade-offs |
| Tech Lead | Project Manager | Technical estimates, risk register contributions |
| QA Automation Engineer | Developers | Testable code practices, shared test utilities, PR review |
| QA Automation Engineer | Product Manager | Acceptance criteria alignment, quality risk reporting |
| QA Automation Engineer | Project Manager | Release readiness report, quality gate status |
| Business Analyst | Developers | Requirements clarification, acceptance criteria, UAT support |
| Business Analyst | Product Manager | Backlog refinement, prioritization input |
| Business Analyst | Project Manager | Requirements risk flagging, estimation support |
