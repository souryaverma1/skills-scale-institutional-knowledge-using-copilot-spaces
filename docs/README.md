# OctoAcme Project Management Docs

## Overview

This README provides a summary of the project management processes used by OctoAcme and direct links to all major process documents in this repository. Use this as a starting point to understand our project management approach and to quickly access detailed guidance for each phase of project delivery.

## Project Management Process Summary

OctoAcme follows a structured five-phase project lifecycle designed to balance customer value delivery with clear ownership and iterative progress. The process begins with **Initiation**, where new ideas are validated through a lightweight Project One-pager that confirms business need, identifies stakeholders, and establishes success metrics before moving forward. Once approved, projects enter the **Planning** phase, where work is broken into shippable increments with clear acceptance criteria, dependencies are mapped, and release timelines are established.

The **Execution** phase emphasizes daily standups, regular demos, and disciplined pull request workflows (preferably under 400 lines), supported by comprehensive testing and CI automation. Following delivery, teams conduct **Release & Deployment** with pre-release checklists, smoke tests, and rollback plans to minimize production risk. Finally, **Retrospectives & Continuous Improvement** capture learnings and convert them into actionable improvements, reinforcing a culture of psychological safety and data-informed decision-making.

### Core Principles

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments rather than monolithic releases
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

### Key Roles & Responsibilities

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validates quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic guidance

### Communication & Cadence

OctoAcme maintains a disciplined communication rhythm to keep all stakeholders aligned:

- **Daily standups** (15 min): Team focuses on progress, blockers, and dependencies
- **Weekly PM + PdM sync**: Alignment on priorities, risks, and strategic decisions
- **Twice-weekly delivery standups**: Engineering-focused progress reviews
- **Monthly stakeholder updates**: High-level status and roadmap visibility
- **Ad-hoc escalations**: Clear escalation paths for urgent issues (team → PM → Product Lead → Sponsor)

### Quality & Risk Management

Quality is embedded throughout execution rather than deferred to the end. Teams implement unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows. CI pipelines enforce automated testing and security scanning before PRs can be approved. A formal **Risk Register** captures all identified risks with impact, likelihood, owner, and mitigation plans, reviewed weekly during syncs. Pre-release requirements include passing all CI checks, security scans, drafted release notes, and a documented rollback plan.

### Key Artifacts

- **Project Charter / One-pager**: Problem statement, goal, success metrics, stakeholders, timeline
- **Sprint/Iteration Backlog**: Prioritized work with acceptance criteria and estimates
- **Definition of Done**: Shared checklist for what "complete" means
- **Risk Register**: Ongoing risk tracking with mitigation plans
- **Retrospective Notes**: Learnings and action items for continuous improvement
- **Release Notes**: Standardized format for communicating changes to stakeholders

---

## Process Documents

Click any link below to access detailed guidance for each phase:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, artifacts, and lifecycle
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — How to validate new ideas, align stakeholders, and create a Project One-pager
- **[Project Planning](./octoacme-project-planning.md)** — Breaking work into shippable increments, estimating, defining DoD, and managing dependencies
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day workflows, PR standards, testing requirements, and metrics
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk identification, escalation paths, and stakeholder communication templates
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Pre-release requirements, deployment checklists, rollback procedures, and release notes
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Running retrospectives, capturing learnings, and tracking action items
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Detailed descriptions of key personas (PMs, Developers, Product Managers) and their responsibilities

---

## Quick Links

- **For new team members**: Start with [Project Management Overview](./octoacme-project-management-overview.md) and [Roles and Personas](./octoacme-roles-and-personas.md)
- **Starting a new project**: Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **Managing ongoing work**: Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Preparing for release**: Use the [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Improving processes**: See [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

---

## Getting Help

If you have questions about these processes or need clarification:

1. Check the relevant process document first
2. Reach out to your Project Manager or Product Lead
3. Bring questions to the weekly PM + PdM sync
4. File a GitHub issue using the [Process Doc Update template](./.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to suggest improvements
