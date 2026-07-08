# OctoAcme Project Management Docs

This README serves as the central index for OctoAcme project management process documentation. Use it as a starting point to navigate the full lifecycle of how work gets done at OctoAcme — from the first idea through delivery and continuous improvement.

## Overview

OctoAcme uses a lightweight but structured project management approach designed to move work from idea to delivery through a clear lifecycle: initiation, planning, execution, release, and retrospective. Projects begin with a one-pager that defines the problem, goal, success metrics, stakeholders, timeline, risks, and resource needs. Once approved, the team creates a prioritized backlog, estimates work, defines acceptance criteria and Definition of Done, and maps milestones and dependencies. This creates a repeatable process that keeps teams aligned while still emphasizing iterative delivery and small, testable increments.

The documentation defines several core personas with distinct responsibilities. Project Managers coordinate delivery, timelines, risks, communications, and cross-team alignment. Product Managers focus on outcomes, prioritization, problem statements, and measuring customer and business value. Developers implement features, maintain tests and documentation, participate in reviews, and help surface technical risks. QA and testing contributors validate acceptance criteria and overall quality, while stakeholders provide inputs, feedback, and approvals throughout the project lifecycle. Together, these roles reinforce OctoAcme's principles of clear ownership, customer focus, and data-informed decision-making.

Communication is treated as a core delivery function. OctoAcme recommends regular cadences such as PM–PdM syncs, delivery-team standups, weekly status updates, milestone demos, and monthly stakeholder communications. Teams maintain a single source of truth for status, use project boards to track work through stages like Backlog, In Progress, In Review, QA, and Done, and escalate blockers through defined paths. Risk management is embedded into this communication model, with risks tracked in a register and reviewed routinely during planning and execution.

Quality assurance is built into both delivery workflows and release practices. The process calls for unit tests on new logic, integration tests where appropriate, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed. Execution guidance promotes small pull requests linked to issues and acceptance criteria, requiring tests, linting, and approvals before merge. Before release, teams confirm that acceptance criteria are met, CI and security checks pass, rollback plans are documented, and post-deployment verification is completed. Retrospectives after sprints, releases, or incidents then turn lessons learned into concrete backlog items for continuous improvement.

## Documentation Index

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [OctoAcme — Project Initiation Guide](octoacme-project-initiation.md)
- [OctoAcme — Project Planning](octoacme-project-planning.md)
- [OctoAcme — Execution & Tracking](octoacme-execution-and-tracking.md)
- [OctoAcme — Risk Management & Communication](octoacme-risks-and-communication.md)
- [OctoAcme — Release & Deployment Guide](octoacme-release-and-deployment.md)
- [OctoAcme — Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Roles & Personas](octoacme-roles-and-personas.md)
