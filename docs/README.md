# OctoAcme Project Management Documentation

## Overview

OctoAcme operates a structured, lifecycle-based project management approach that emphasizes customer value, iterative delivery, and clear ownership. Our framework consists of five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. This documentation serves as the central hub for accessing OctoAcme project management guidance and best practices.

### Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme projects follow a structured lifecycle:

1. **Initiation** - Validate business need, align stakeholders, and define success metrics. Teams create a lightweight Project One-pager that establishes the problem statement, measurable outcomes, and initial timeline.

2. **Planning** - Break approved work into a prioritized, estimated backlog with clear acceptance criteria. Teams identify dependencies, define Definition of Done, and create a release plan aligned with business milestones.

3. **Execution** - Teams build and iterate using a disciplined pull request workflow, daily standups, weekly delivery syncs, and regular demos. Work flows through GitHub Projects stages: Backlog → Ready → In Progress → In Review → QA → Done.

4. **Release** - Standardize deployment with pre-flight checklists, smoke tests, security scanning, and rollback plans. Release notes and stakeholder communications ensure transparency and traceability.

5. **Close & Retrospective** - Capture learnings, celebrate wins, and convert feedback into actionable improvements tracked in the project backlog.

## Core Roles

OctoAcme defines clear role separation to reduce friction and ensure accountability:

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability, identify technical risks
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic direction

## Communication Cadence

- **Daily standups** (15 min) - Focus on progress, blockers, and dependencies
- **Weekly PM/PdM sync** - Alignment and decision-making
- **Twice-weekly delivery standups** - Team coordination
- **Monthly stakeholder updates** - Status reporting and alignment
- **Ad-hoc escalations** - Risk and blocker resolution

## Quality & Risk Management

Quality is embedded throughout the lifecycle:

- **Unit and integration tests** for new logic
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** in CI/CD
- **Manual QA** for feature acceptance when needed
- **Formal Risk Register** tracking impact, likelihood, ownership, and mitigation
- **Peer code review** (minimum one approval before merge)

## Documentation Index

### Getting Started

- **[Project Management Overview](octoacme-project-management-overview.md)** - Foundational guide covering core roles, artifacts, lifecycle, and communication cadence
- **[Roles and Personas](octoacme-roles-and-personas.md)** - Detailed definitions of typical roles and their responsibilities

### Execution Phases

- **[Project Initiation](octoacme-project-initiation.md)** - Steps to validate and authorize work, align stakeholders, and create a lightweight Project One-pager
- **[Project Planning](octoacme-project-planning.md)** - How to turn an approved initiative into an actionable plan, backlog, and release timeline
- **[Execution and Tracking](octoacme-execution-and-tracking.md)** - Guidance for managing day-to-day execution, team rhythm, progress tracking, and quality standards
- **[Release and Deployment](octoacme-release-and-deployment.md)** - Standards for releasing features to production, deployment checklists, and incident response

### Cross-Cutting Concerns

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** - How to identify, manage, and communicate risks, dependencies, and stakeholder updates
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Capturing learnings and converting them into actionable improvements

## How to Use This Documentation

1. **New team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md) and [Roles and Personas](octoacme-roles-and-personas.md)
2. **Starting a new project**: Follow the progression: Initiation → Planning → Execution → Release → Retrospective
3. **Looking for specific guidance**: Use the Documentation Index to find the phase or concern that matches your need
4. **Process improvements**: Submit updates or new content via the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template

## Contributing

To propose updates or additions to these process documents, please use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml). This ensures all changes align with OctoAcme principles and are reviewed by the team.
