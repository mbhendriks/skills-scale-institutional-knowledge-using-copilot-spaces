# OctoAcme Project Management Docs

## Overview

OctoAcme projects move through initiation, planning, execution, release, and retrospective. Initiation validates the business need, success measures, stakeholders, resources, and initial risks before a decision to plan. Planning turns approved work into a prioritized, estimated backlog with acceptance criteria, a Definition of Done, dependencies, and agreed milestones; teams then build, test, review, and release in increments.

Ownership is shared across clear roles: Product Managers or Product Leads define outcomes and priorities; Project Managers coordinate plans, schedules, risks, dependencies, and communication; developers design, build, and test; QA/testing validates acceptance and quality; and stakeholders provide context, input, and approvals. These responsibilities connect product goals to delivery while keeping coordination and decisions visible.

Teams use a shared status source, such as the project README or release document, and communicate through delivery syncs, demos or milestone reviews, and regular stakeholder updates. Cadence is agreed by the team: the overview describes twice-weekly standups or another agreed rhythm, while the execution guide recommends daily standups to surface progress, blockers, and dependencies. Risks are reviewed regularly, triaged by the team, and escalated through the Project Manager and Product Lead to the sponsor when needed.

Quality is built into delivery through clear acceptance criteria and the Definition of Done, small reviewed pull requests, automated tests, CI and security checks, and QA where needed. The execution guide calls for at least one approval before merge or the team-defined policy; release readiness includes staging smoke tests, post-deployment verification, and a documented rollback or mitigation plan. After a sprint, release, milestone, or incident, retrospectives turn learnings into prioritized actions with owners and due dates, which teams track and review.

## Quick Start

New to OctoAcme projects? Start here:

- **Just onboarding?** → Read [Project Management Overview](octoacme-project-management-overview.md)
- **Starting a new project?** → Follow [Project Initiation Guide](octoacme-project-initiation.md)
- **Planning your work?** → Check [Project Planning](octoacme-project-planning.md)
- **Managing day-to-day?** → Review [Execution & Tracking](octoacme-execution-and-tracking.md)
- **Managing risks or updates?** → See [Risk Management & Communication](octoacme-risks-and-communication.md)
- **Testing and validating a change?** → Start with [Project Planning](octoacme-project-planning.md) and [Execution & Tracking](octoacme-execution-and-tracking.md)
- **Deploying to production?** → Use [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **Learning from delivery?** → Use [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## All Documentation

### Core Processes

- [Project Management Overview](octoacme-project-management-overview.md) - High-level introduction to OctoAcme's approach, roles, and lifecycle
- [Project Initiation Guide](octoacme-project-initiation.md) - Steps to validate and authorize new work
- [Project Planning](octoacme-project-planning.md) - Breaking work into actionable increments
- [Execution & Tracking](octoacme-execution-and-tracking.md) - Day-to-day delivery management
- [Release & Deployment Guide](octoacme-release-and-deployment.md) - Standardizing releases to production

### Supporting Processes

- [Risk Management & Communication](octoacme-risks-and-communication.md) - Identifying and managing risks
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Capturing learnings and improvements
- [Roles & Personas](octoacme-roles-and-personas.md) - Role definitions and responsibilities

## By Role

- **Project Manager** → Start with [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md)
- **Product Manager** → Start with [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md)
- **Developer** → Start with [Project Management Overview](octoacme-project-management-overview.md) and [Execution & Tracking](octoacme-execution-and-tracking.md)
- **QA / Testing** → Start with [Project Planning](octoacme-project-planning.md) and [Execution & Tracking](octoacme-execution-and-tracking.md); see [Release & Deployment](octoacme-release-and-deployment.md) for smoke tests and verification
- **Stakeholder** → Start with [Project Management Overview](octoacme-project-management-overview.md), then [Risk Management & Communication](octoacme-risks-and-communication.md) and [Release & Deployment](octoacme-release-and-deployment.md) for updates and release communication

## Repository Structure

```
.
├── docs/
│   ├── README.md (this hub)
│   ├── octoacme-project-management-overview.md
│   ├── octoacme-project-initiation.md
│   ├── octoacme-project-planning.md
│   ├── octoacme-execution-and-tracking.md
│   ├── octoacme-risks-and-communication.md
│   ├── octoacme-release-and-deployment.md
│   ├── octoacme-retrospective-and-continuous-improvement.md
│   └── octoacme-roles-and-personas.md
└── .github/
    └── ISSUE_TEMPLATE/
        └── add-update-content-to-process-docs.yml
```

`docs/` contains the eight project management process documents and this navigation hub. `.github/ISSUE_TEMPLATE/` contains templates for proposing process-document changes, including `add-update-content-to-process-docs.yml`.
