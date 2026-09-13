# OctoAcme Project Management Documentation

## Overview
Welcome to the OctoAcme Project Management Documentation hub. This repository contains comprehensive guidance for managing projects across the organization, from initiation through retrospectives. Our approach is built on principles of customer-first delivery, iterative development, clear ownership, and data-informed decisions.

## Key Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Approach

OctoAcme follows a structured, lifecycle-based approach to project management grounded in clear stakeholder alignment and iterative delivery. The framework spans five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During **Initiation**, the team validates business need and confirms stakeholder buy-in through a lightweight Project One-pager that captures the problem statement, success metrics, and resource needs. Once approved, the **Planning** phase breaks work into shippable increments with prioritized backlogs, acceptance criteria, and a Definition of Done. This dual-ownership model—where a Product Manager (PdM) defines *what* to build and a Project Manager (PM) coordinates *how* and *when* it gets delivered—ensures both customer value and operational execution are prioritized.

Execution and delivery are supported by a regular team rhythm and clear quality standards. OctoAcme emphasizes **daily standups** (15 minutes, focused on progress and blockers), **weekly delivery syncs**, and **sprint/iteration planning** using GitHub Projects with standard columns (Backlog, Ready, In Progress, In Review, QA, Done). Pull requests follow a disciplined workflow: small PRs (≤400 lines when possible) with issue links and acceptance criteria, automated CI tests and linting, and a requirement for at least one approval before merge. Quality is ensured through unit tests, integration tests, end-to-end smoke tests, and security scanning—with manual QA applied for feature acceptance when needed. Risk and dependency management are woven throughout: risks are captured in a Risk Register and reviewed weekly, blockers are escalated through defined levels (team triage → PM escalation → sponsor escalation), and cross-team dependencies are tracked on the project board.

Communication and continuous improvement are foundational to OctoAcme's culture. The organization maintains a weekly PM–PdM sync, twice-weekly delivery standups, and monthly stakeholder updates, with all status shared from a single source of truth (the project README or release doc). **Release and deployment** follow a standardized checklist—including acceptance criteria validation, passing CI/security scans, staged smoke testing, and rollback planning—to reduce production risk. Finally, after each sprint, release, or milestone, the team runs a **retrospective** (45–75 minutes) to capture what went well, what could improve, and to convert learnings into prioritized action items with clear owners and success criteria. This closed-loop approach to continuous improvement, combined with defined roles (Developers, Product Managers, Project Managers, QA/Testing), ensures OctoAcme maintains psychological safety, data-informed decisions, and consistent, repeatable project execution across all cross-functional initiatives.

## Documentation by Phase

### Planning & Initiation
- **[Project Initiation Guide](octoacme-project-initiation.md)**: Initial steps to validate work, align stakeholders, and create a lightweight plan
- **[Project Planning](octoacme-project-planning.md)**: Turn an approved initiative into an actionable plan and backlog for delivery

### Execution
- **[Execution & Tracking](octoacme-execution-and-tracking.md)**: Guidance for managing day-to-day execution and tracking progress toward milestones
- **[Risk Management & Communication](octoacme-risks-and-communication.md)**: Identify, manage, and communicate risks and dependencies

### Release & Retrospectives
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)**: Standardize how OctoAcme releases features to production
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)**: Capture learnings and convert them into actionable improvements

## Reference Materials
- **[Project Management Overview](octoacme-project-management-overview.md)**: Concise introduction to OctoAcme's approach, roles, and key artifacts
- **[Roles and Personas](octoacme-roles-and-personas.md)**: Definitions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities

## Getting Started
1. Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our core approach and roles
2. Follow the phase-specific guides based on where your project is in its lifecycle
3. Refer to [Roles and Personas](octoacme-roles-and-personas.md) to understand responsibilities and communication patterns

## Using These Docs
- Keep the Project Charter updated in your project repo
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Use checklists in each phase guide to ensure nothing is missed
