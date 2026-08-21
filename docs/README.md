# OctoAcme Project Management Processes

## Brief Overview
OctoAcme organizes work around a lightweight, repeatable lifecycle that moves initiatives from initiation through planning, execution, release, and continuous improvement. Projects begin with a concise Project One-pager that captures the problem, objective, success metrics, stakeholders, and a high-level timeline. That one-pager and a simple decision gate determine whether an idea moves into planning, where work is decomposed into a prioritized, estimated backlog with a Definition of Done and release milestones.

Work is delivered in small, testable increments. The team tracks day-to-day execution on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and follows disciplined pull request practices: keep PRs small when possible, include linked issues and acceptance criteria in PR descriptions, and require automated tests, linting, and security scans to pass in CI before requesting review.

Roles and communication are explicit to reduce ambiguity. Product Managers define outcomes and prioritize the backlog; Project Managers coordinate schedules, risks, and stakeholder updates; Developers implement and test features; and QA validates acceptance criteria and performs manual checks when needed. The regular communication cadence includes daily standups, a weekly delivery sync, weekly PM+PdM alignment, and monthly stakeholder updates. Retrospectives after sprints or releases capture action items that are tracked back into the backlog for continuous improvement.

Quality and release discipline are baked into the process. New logic should include unit and integration tests where applicable, with smoke tests for critical flows. CI enforces testing, linting, and security scans before review. Releases follow a checklist (staging verification, automated production deployment where possible, post-deploy checks) and a rollback/incident playbook for production issues.

## Process Documents (docs/)
1. Project Initiation Guide — ./octoacme-project-initiation.md
2. Project Planning — ./octoacme-project-planning.md
3. Execution & Tracking — ./octoacme-execution-and-tracking.md
4. Risk Management & Communication — ./octoacme-risks-and-communication.md
5. Release & Deployment — ./octoacme-release-and-deployment.md
6. Retrospective & Continuous Improvement — ./octoacme-retrospective-and-continuous-improvement.md
7. Roles & Personas — ./octoacme-roles-and-personas.md
8. Project Management Overview — ./octoacme-project-management-overview.md

## Getting started
- New to OctoAcme? Start with the Project Management Overview (./octoacme-project-management-overview.md).
- Planning a new project? Follow the Project Initiation Guide and create a Project One-pager.
- Want to propose changes to these docs? Use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/.
