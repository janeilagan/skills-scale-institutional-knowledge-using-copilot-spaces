# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management framework. This directory contains standardized processes and guidance for managing projects across our organization.

## OctoAcme Framework Overview

OctoAcme is a lightweight, iterative project management approach built on the following principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named leaders and clear roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

Our projects follow a consistent lifecycle: **Initiation → Planning → Execution → Release → Close & Retrospective**

## Core Roles
- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features and collaborate on design
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## OctoAcme Project Management Process Summary

OctoAcme follows a structured, five-phase lifecycle approach to project delivery: **Initiation, Planning, Execution, Release, and Close & Retrospective**. During initiation, teams validate business needs and align stakeholders around a lightweight Project One-pager that captures the problem statement, success metrics, and resource requirements. Once approved, the project moves into planning, where work is broken into prioritized, estimated backlog items with clear acceptance criteria and a Definition of Done. This front-loaded rigor ensures teams start execution with shared understanding and minimal rework.

The core delivery model emphasizes **iterative, small-batch delivery** supported by clear role definition and accountability. Three primary roles drive each project: the **Project Manager** (who coordinates schedules, risks, and communications), the **Product Manager** (who defines outcomes and prioritizes), and the **Developer/Delivery Team** (who implement and test). Teams operate on a regular cadence of daily standups, weekly delivery syncs, and milestone-based demos, using GitHub Projects as a single source of truth. Pull requests are kept small (≤400 lines where possible), require at least one approval before merging, and all code passes automated testing and security scanning before review.

Quality and risk management are woven throughout execution and release. Teams commit to unit tests, integration tests, and smoke tests for critical flows, supported by a documented Risk Register that tracks issues by impact, likelihood, and mitigation strategy. Risks are reviewed weekly, and escalation paths are clearly defined—from team-level triage to Product Lead to Sponsor-level involvement. Pre-release checklists confirm all acceptance criteria are met, CI passes, rollback plans are documented, and staging smoke tests succeed before production deployment.

Finally, OctoAcme closes each project or milestone with a structured retrospective, capturing what went well, what could improve, and tracking 2–3 prioritized action items with clear owners and timelines. This continuous improvement cycle feeds learnings back into the process docs themselves, ensuring the team's institutional knowledge evolves and remains aligned with real-world execution. Stakeholder communication is consistent throughout—weekly status updates, a shared project charter, and clear escalation channels—keeping all parties informed and reducing surprises at delivery time.

## Process Documentation

### Getting Started
- [Project Management Overview](octoacme-project-management-overview.md) - High-level framework and key artifacts
- [Roles & Personas](octoacme-roles-and-personas.md) - Definitions of team roles and responsibilities

### Project Lifecycle
1. **[Project Initiation](octoacme-project-initiation.md)** - Validate business need, align stakeholders, create lightweight plan
2. **[Project Planning](octoacme-project-planning.md)** - Break work into shippable increments, identify dependencies and risks
3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** - Manage day-to-day execution and track progress
4. **[Release & Deployment](octoacme-release-and-deployment.md)** - Standardize releases to production
5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Capture learnings and improvements

### Cross-Cutting Concerns
- [Risk Management & Communication](octoacme-risks-and-communication.md) - Identify, manage, and communicate risks throughout the project lifecycle

## How to Use These Docs
- Use the Project Management Overview as an introduction if you're new to OctoAcme
- Reference specific process documents as needed during each phase of your project
- Keep your project charter updated in your project repo
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to reference them as context
- Use the issue template in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to request updates or additions to these process documents
