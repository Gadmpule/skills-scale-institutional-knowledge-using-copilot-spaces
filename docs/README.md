# OctoAcme Project Management Documentation

This folder contains the end-to-end project management documentation used by OctoAcme. The guides below cover every phase of the project lifecycle — from the first idea through retrospective — and define the roles, communication standards, and quality practices that keep delivery predictable and sustainable.

## Overview

OctoAcme follows an **iterative, customer-first delivery model**. Every project begins with a lightweight initiation phase: a Project One-pager captures the problem statement, measurable goals, stakeholders, and an initial risk list. Once a project is approved, a planning kickoff breaks work into shippable increments, defines the Definition of Done, maps dependencies, and produces a release plan with clear milestones. During execution, the team maintains a steady rhythm of daily standups, weekly delivery syncs, and end-of-sprint demos tracked on a GitHub Projects board — keeping progress visible and blockers surfaced early.

Quality is built into every stage rather than added at the end. Pull Requests are kept small (≤ 400 lines when possible), include an issue link and acceptance criteria, and must pass automated CI pipelines — unit tests, integration tests, linting, and security scanning — before requesting at least one human review. End-to-end smoke tests gate every release, and manual QA is performed for feature acceptance when automated coverage is insufficient. Deployments follow a structured checklist that includes staging validation, a drafted rollback plan, release notes, and a post-deploy stakeholder announcement.

Roles are clearly assigned so that ownership is never ambiguous. The **Project Manager (PM)** coordinates schedules, risks, and cross-team communication. The **Product Manager / Product Lead (PdM)** owns the backlog, defines outcomes, and measures success. **Developers** implement and test features while contributing to design and planning. **QA/Testing** validates acceptance criteria and signs off on releases. **Stakeholders** provide business inputs and approvals throughout the lifecycle. Communication cadences, status templates, and a single source of truth (the project README or release doc) ensure that every stakeholder group receives timely, consistent information regardless of their level of technical involvement.

After each sprint, release, or significant milestone, the team runs a **retrospective** (45–75 minutes) structured around what went well, what could be improved, and 2–3 concrete action items with owners and due dates. Improvements feed back into the backlog, and outstanding actions are reviewed in the weekly PM sync — creating a continuous improvement loop that strengthens processes over time.

---

## Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, and key artifacts for all cross-functional projects |
| [Project Initiation](octoacme-project-initiation.md) | Steps to validate and authorize new work, including the Project One-pager template |
| [Project Planning](octoacme-project-planning.md) | Turning an approved initiative into an actionable backlog and release plan |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day delivery workflows, quality practices, and progress reporting |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register lifecycle, stakeholder communication cadence, and status templates |
| [Release & Deployment](octoacme-release-and-deployment.md) | Standardized release types, deployment checklist, and rollback playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives and tracking improvement action items |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication patterns for each team role |
