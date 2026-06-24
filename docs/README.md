# OctoAcme Project Management Documentation

Welcome to OctoAcme's centralized project management process documentation. This README serves as the canonical entry point for discovering, navigating, and understanding how OctoAcme runs projects.

## Overview: OctoAcme Project Management Approach

OctoAcme follows a structured, lifecycle-based approach to project delivery that emphasizes customer value, iterative execution, and data-driven decision-making. The process spans five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**.

### Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments with clear acceptance criteria
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

### Project Lifecycle at a Glance

1. **Initiation** — Validate business needs, create a lightweight Project One-pager, and secure stakeholder alignment
2. **Planning** — Break work into shippable increments, estimate scope, define dependencies, and establish Definition of Done
3. **Execution** — Build, test, review, and iterate through daily standups, weekly syncs, and a transparent project board
4. **Release** — Deploy to production with pre-release checks, automated pipelines, rollback plans, and release notes
5. **Retrospective** — Capture learnings and convert action items into backlog tasks for continuous improvement

### Execution & Tracking Workflow

Teams execute through a disciplined rhythm:
- **Daily standups** (15 min) — Focus on progress, blockers, and dependencies
- **Weekly delivery sync** — Show progress, updates, and flagged risks
- **Project board** — Backlog → Ready → In Progress → In Review → QA → Done
- **Pull Request workflow** — Small PRs (≤400 lines), automated tests/lint, at least one approval before merge
- **Quality assurance** — Unit tests, integration tests, end-to-end smoke tests, security scanning, and manual QA when needed

### Risk Management & Communication

OctoAcme maintains transparency through:
- **Risk Register** — Captures risk ID, description, impact, likelihood, owner, and mitigation plan
- **Weekly status updates** — Progress, next steps, risks, and decisions needed
- **Three-level escalation** — Team → PM → Product Lead → Sponsor
- **Stakeholder alignment** — Regular updates and clear communication channels

### Continuous Improvement

After each sprint, release, or milestone, teams conduct retrospectives to:
- Reflect on what went well
- Identify areas for improvement
- Define 2–3 prioritized action items with clear owners and due dates
- Track improvements in the backlog and review in weekly PM syncs

---

## Process Documents

Detailed guidance for each phase and function is available in the following documents:

### Phase Guides
- [**Project Management Overview**](octoacme-project-management-overview.md) — Concise introduction to OctoAcme's approach, roles, and key artifacts
- [**Project Initiation Guide**](octoacme-project-initiation.md) — Initial steps to validate business need, align stakeholders, and create a lightweight plan
- [**Project Planning**](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog
- [**Execution & Tracking**](octoacme-execution-and-tracking.md) — Manage day-to-day execution, team rhythm, and progress tracking
- [**Release & Deployment Guide**](octoacme-release-and-deployment.md) — Standardized approach to releasing features and managing deployments
- [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements

### Cross-Functional Guides
- [**Risk Management & Communication**](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies
- [**Roles & Personas**](octoacme-roles-and-personas.md) — Detailed responsibilities and goals for each role in OctoAcme projects

---

## How to Use This Documentation

### For New Team Members
Start here to understand OctoAcme's approach, then refer to phase-specific docs as you enter each stage of a project.

### For Project Managers
Reference the **Initiation**, **Planning**, **Execution**, and **Retrospective** guides. Keep the Risk Register and status templates handy.

### For Product Managers
Focus on **Project Initiation** (One-pager and success metrics), **Planning** (backlog prioritization), and **Execution** (acceptance criteria and metrics tracking).

### For Developers
Consult **Execution & Tracking** for workflow, PR standards, and Definition of Done. Reference **Release & Deployment** before production releases.

### For Stakeholders
Review the **Project Management Overview** for context, and check weekly status updates and retrospective notes for project health.

---

## Best Practices

- **Keep documentation updated** — Reflect process changes and lessons learned back into these docs
- **Use templates** — Leverage the provided templates for One-pagers, Risk Registers, and status updates
- **Link to docs in project repos** — Add links to relevant docs in your project README or `.copilot/` folder
- **Reference in issues and PRs** — Link to process docs when creating issues or PRs to provide context and consistency
- **Share in onboarding** — Include this README in team onboarding materials and Copilot Spaces contexts

---

## Integration with Copilot Spaces

These documents are designed to be used as context in Copilot Spaces. When creating a new Copilot Space for a project:

1. Attach relevant process docs (e.g., Initiation, Planning, Roles & Personas)
2. Reference this README in your Space instructions
3. Use the documents to ground Copilot's responses in OctoAcme's methodology

---

## Questions or Feedback?

If you have questions about these processes or suggestions for improvement:
1. Open an issue using the **"Add Content to Project Management Process Docs"** template
2. Include your feedback in project retrospectives
3. Escalate process blockers through your Project Manager

---

**Last Updated:** June 2026
