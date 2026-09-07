# OctoAcme Project Management Documentation

Welcome to OctoAcme's project management process documentation. This folder contains the framework and guidance for how we run cross-functional projects to deliver product value.

Quick overview
--------------
OctoAcme follows a structured project lifecycle organized into five key phases:
1. Initiation — validate the business need, align stakeholders, and decide whether to proceed.
2. Planning — define scope, break work into shippable increments, and establish release plans.
3. Execution — build, test, and iterate with regular team synchronization and quality standards.
4. Release — deploy to production with pre-release verification and rollback readiness.
5. Retrospective — capture learnings and drive continuous improvement.

Brief summary of our processes
-----------------------------
OctoAcme runs projects with a lightweight, outcome-driven lifecycle that moves teams from initiation through planning, execution, release, and retrospective. Work begins with a Project One-pager to capture the problem, objectives, success metrics, stakeholders, and a high-level timeline, then progresses to planning where backlog items are created, estimated, and mapped to milestones. Delivery is iterative: small, shippable increments are prioritized and tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done), and decisions to move between phases are gated by clear acceptance criteria and a Definition of Done.

Workflows emphasize disciplined execution and predictable handoffs. The pull request workflow asks for small PRs (target ≤ 400 lines), an issue link and acceptance criteria in the description, automated tests and linting in CI before review, and at least one approval before merging. Team rhythm reinforces coordination with daily 15-minute standups for blockers and progress, a weekly delivery sync to highlight progress and risks, and a demo/review at the end of each sprint or milestone. Defined escalation paths (team → PM → Product Lead → Sponsor) and stakeholder communication templates keep updates consistent and traceable.

Roles and communication
-----------------------
Roles and responsibilities are clearly called out so ownership and collaboration are explicit: Product Managers define the what and why (vision, success metrics, prioritization), Project Managers coordinate delivery (plans, risks, communications), Developers implement and test features, QA validates acceptance criteria and quality, and Stakeholders provide approvals and inputs. These persona definitions guide who does what across planning, execution, and follow-up activities and are used directly in exercises and process documentation.

Quality assurance and continuous improvement
-------------------------------------------
QA practices include unit, integration, and end-to-end smoke testing, security scans in CI, and manual QA where needed; release readiness is enforced with checklists (pre-release requirements, rollback plans, smoke tests) and a deployment checklist. Risks are tracked in a simple register (impact, likelihood, owner, mitigation) and reviewed regularly; retrospectives capture learnings with prioritized action items that feed back into the backlog so the team can measure and close improvement loops.

Documentation index
-------------------
Getting started
- Project Management Overview: octoacme-project-management-overview.md
- Roles & Personas: octoacme-roles-and-personas.md

By project phase
- Initiation: octoacme-project-initiation.md
- Planning: octoacme-project-planning.md
- Execution & Tracking: octoacme-execution-and-tracking.md
- Release & Deployment: octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement: octoacme-retrospective-and-continuous-improvement.md

Cross-cutting
- Risks & Communication: octoacme-risks-and-communication.md

How to use these docs
---------------------
- Starting a new project? Begin with the Project Initiation Guide.
- Looking for role clarity? Check Roles & Personas.
- Need to manage risks or stakeholders? See Risk Management & Communication.
- Want to understand the complete framework? Read the Project Management Overview.

Contributing
------------
These documents are living artifacts. To propose updates, please use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/. If you open an issue, include which document to update, a summary of the change, rationale, and suggested content.

Acceptance criteria (for README)
-------------------------------
- README provides a concise overview of OctoAcme processes and links to each process document
- README improves discoverability and reduces onboarding time
- README includes quick guidance on which document to consult at each project phase
