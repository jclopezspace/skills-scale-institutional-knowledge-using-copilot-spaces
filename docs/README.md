# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation hub. This folder contains the process guides that define how OctoAcme teams plan, execute, and continuously improve their software delivery. Use the links below to navigate directly to any topic.

## Overview

OctoAcme's project management approach follows a lightweight, iterative lifecycle designed to keep delivery customer-focused and measurable. Work generally moves through five phases: **Initiation** (validate the problem, outcomes, stakeholders, and success metrics), **Planning** (turn the approved idea into an actionable backlog and release plan), **Execution** (build, test, and review in small increments), **Release** (deploy with clear safeguards), and **Close & Retrospective** (capture learnings and feed improvements back into the backlog and process docs). Key artifacts—including a project one-pager/charter, roadmap/release plan, acceptance criteria, Definition of Done, risk register, and retrospective action items—act as the single source of truth throughout delivery.

Roles are explicitly defined to ensure clear ownership and reduce ambiguity. The **Project Manager (PM)** coordinates delivery, schedules, risks, and cross-team communication; the **Product Manager (PdM)** defines outcomes, prioritizes the backlog, and measures success; **Developers** implement features, testing, and documentation while collaborating on estimation and design; and **QA/Testing** validates acceptance criteria and supports release readiness. Stakeholders contribute input and approvals, with ownership reinforced through backlog items that include acceptance criteria, priority, estimates, and a named owner.

Execution is organized around a consistent team rhythm and clear workflow states. Teams use a project board (Backlog → Ready → In Progress → In Review → QA → Done) to visualize work, manage flow, and surface dependencies. Communication is structured via short daily standups, weekly delivery syncs, and regular demos at the end of each sprint or milestone. Stakeholder updates follow a simple weekly status format (progress, next steps, risks/blockers, asks/decisions), while escalation paths are defined from team triage up through PM, Product Lead, and sponsor when business impact requires it.

Quality and release practices emphasize risk reduction and repeatability. OctoAcme expects unit tests for new logic, broader integration tests when relevant, and end-to-end smoke tests for critical flows before release, supported by CI-based testing, linting, and security scanning. Pull requests are kept small and reviewable, include issue links and acceptance criteria, and typically require at least one approval before merge. Releases follow a standard checklist (readiness checks, release notes, rollback plan, staging and smoke tests, production deploy, and post-deploy verification), and teams run retrospectives after sprints, releases, milestones, or incidents to identify a small set of actionable improvements with owners and due dates.

## How to Use These Docs

Each document below covers a specific phase or domain of the OctoAcme delivery process. If you are new to the team, start with the **Overview** and **Roles & Personas** guides, then read the phase-specific documents in the order they appear in the lifecycle.

## Process Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level summary of OctoAcme's end-to-end delivery lifecycle |
| [Project Initiation](octoacme-project-initiation.md) | How to validate a problem, define success metrics, and kick off a project |
| [Project Planning](octoacme-project-planning.md) | Turning an approved idea into a backlog, roadmap, and release plan |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Running sprints, managing the board, and keeping delivery on track |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk identification, escalation paths, and stakeholder communication |
| [Release and Deployment](octoacme-release-and-deployment.md) | Release readiness, deployment checklist, and rollback procedures |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives and feeding improvements back into the process |
| [Roles and Personas](octoacme-roles-and-personas.md) | Responsibilities and expectations for every role on an OctoAcme project |
