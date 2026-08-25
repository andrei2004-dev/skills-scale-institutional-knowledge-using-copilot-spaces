# OctoAcme Project Management Processes

Welcome to the OctoAcme Project Management framework. This folder contains comprehensive guides for running projects following OctoAcme principles: **customer-first delivery**, **iterative development**, **clear ownership**, **data-informed decisions**, and **psychological safety**.

## Overview

OctoAcme follows a structured, lifecycle-based approach to project delivery that emphasizes customer value, iterative development, and clear ownership. The process flows through five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. During initiation, teams validate business need and align stakeholders around a lightweight one-pager that captures the problem statement, success metrics, and key milestones. Once stakeholders approve and confirm team availability, the project moves into planning, where work is broken into shippable increments with prioritized backlogs, acceptance criteria, and a documented Definition of Done.

Execution and delivery are coordinated through a consistent team rhythm and well-defined roles. OctoAcme projects operate with a **Project Manager** who handles scheduling, risk management, and cross-team communication; a **Product Manager** who defines outcomes and prioritizes the backlog; **Developers** who implement features and maintain code quality; and **QA/Testing** specialists who validate acceptance criteria. Teams follow daily standups (15 minutes), weekly delivery syncs, and structured sprint planning to maintain momentum. Pull requests are kept small (≤400 lines when possible) and require at least one approval before merging, with all code passing automated tests, linting, and security scans.

Quality and risk management are embedded throughout execution and release. The team maintains a live risk register tracking impact, likelihood, and mitigation plans, with risks reviewed weekly and escalated through clear pathways: team-level triage → PM → Product Lead → Sponsor. Before any release, the team verifies that all acceptance criteria are met, CI/security scans pass, smoke tests are ready, and a rollback plan is documented. Finally, OctoAcme emphasizes continuous improvement through structured retrospectives held after each sprint, release, or milestone, with action items feeding back into the project backlog and tracked in weekly PM syncs.

## Project Lifecycle Overview

Every OctoAcme project follows a structured lifecycle:

```
┌────────────┐     ┌─────────┐     ┌──────────┐     ┌─────────┐     ┌──────────────────────┐
│ Initiation │ --> │ Planning│ --> │ Execution│ --> │ Release │ --> │ Retrospective &      │
│            │     │         │     │          │     │         │     │ Continuous Improve.  │
└────────────┘     └─────────┘     └──────────┘     └─────────┘     └──────────────────────┘
```

## Core Processes

### 1. [Project Management Overview](octoacme-project-management-overview.md)
Start here for a high-level introduction to OctoAcme principles, core roles, key artifacts, and communication cadence.

### 2. [Project Initiation](octoacme-project-initiation.md)
Learn how to validate a new project idea, align stakeholders, and create a lightweight plan with the Project One-pager.

### 3. [Project Planning](octoacme-project-planning.md)
Turn an approved initiative into an actionable plan by creating a prioritized backlog, identifying dependencies, and defining milestones.

### 4. [Execution & Tracking](octoacme-execution-and-tracking.md)
Manage day-to-day execution with standups, PR workflows, quality standards, and blocker escalation processes.

### 5. [Risk Management & Communication](octoacme-risks-and-communication.md)
Identify, manage, and communicate risks and dependencies. Includes risk register templates and escalation paths.

### 6. [Release & Deployment](octoacme-release-and-deployment.md)
Standardize how features ship to production with pre-release checklists, deployment guidance, and rollback playbooks.

### 7. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
Capture learnings and convert them into actionable improvements. Track action items and measure impact.

### 8. [Roles & Personas](octoacme-roles-and-personas.md)
Define typical roles in OctoAcme projects: Developers, Product Managers, and Project Managers.

## Quick Start for New Team Members

1. **Read the [Project Management Overview](octoacme-project-management-overview.md)** (5 min)  
   Understand core principles, key roles, and the project lifecycle.

2. **Review your [role definition](octoacme-roles-and-personas.md)** (3 min)  
   Get familiar with responsibilities and communication expectations for your role.

3. **Bookmark this README for reference**  
   Return here whenever you need to find a specific process guide.

## Key Principles at a Glance

| Principle | What It Means |
|-----------|---------------|
| **Customer-First** | Prioritize customer value and usability in all decisions |
| **Iterative Delivery** | Deliver small, testable increments rather than big releases |
| **Clear Ownership** | Each project has a named PM and Product Lead |
| **Data-Informed** | Measure impact and iterate based on evidence |
| **Psychological Safety** | Encourage feedback, questions, and learning |

## Communication Cadence

- **Daily**: 15-minute team standups
- **Twice Weekly**: Delivery team syncs (or as agreed)
- **Weekly**: PM + Product Lead alignment
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Escalations and incident communication

## Contributing to These Docs

Have feedback on these processes or want to propose an update? Use the issue template: [Add/Update Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)

---

**Last updated:** 2026-08-25  
**Framework:** OctoAcme Project Management
