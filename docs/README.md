# OctoAcme Project Management Documentation

## Overview

OctoAcme runs projects using a lightweight, iterative framework focused on customer value, clear ownership, and data-informed decisions. This documentation centralizes our project management processes to help teams execute consistently, reduce onboarding time, and make process artifacts easy to discover.

## Process Summary

Every OctoAcme project follows a simple lifecycle: Initiation, Planning, Execution, Release, and Retrospective. Initiation validates the business need, identifies stakeholders, and sets success metrics. Planning breaks approved work into shippable increments, defines acceptance criteria and a Definition of Done, and captures dependencies and risks. Execution is tracked on a project board with daily standups, CI-verified small pull requests, and regular demos to surface progress and issues. Releases are gated with pre-release checks, staging smoke tests, and rollback plans. Retrospectives after sprints, releases, or incidents capture actionable improvements that feed back into the backlog.

Roles and responsibilities are explicit: Product Managers define outcomes and success metrics; Project Managers coordinate delivery, schedule, and risk tracking; Developers implement and test changes; QA validates acceptance; and Stakeholders provide inputs and approvals. Key artifacts include the Project One-pager/Charter, Release Plan, Acceptance Criteria & Definition of Done, Risk Register, and Retrospective action items.

Quality assurance is layered across unit/integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA where needed. Releases follow a checklist (pre-release verification, rollback plan, staging verification, post-deploy checks) and an incident playbook is available for rollbacks and triage.

## Documentation Index

### Core Guides
- [Project Management Overview](./octoacme-project-management-overview.md) — Roles, principles, and lifecycle overview
- [Roles & Personas](./octoacme-roles-and-personas.md) — Core roles (PM, PdM, Developers, QA)

### By Project Phase
- [Project Initiation](./octoacme-project-initiation.md) — Validate ideas and get stakeholder alignment
- [Project Planning](./octoacme-project-planning.md) — Create backlog, estimate, and plan releases
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Daily execution, standups, quality, and metrics
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify risks, manage dependencies, communicate status
- [Release & Deployment](./octoacme-release-and-deployment.md) — Pre-release checklist, deployment, and rollback
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Run retrospectives and track action items

## Quick Start

- New project: start with [Project Initiation](./octoacme-project-initiation.md)
- Ready to plan: use [Project Planning](./octoacme-project-planning.md)
- In execution: follow [Execution & Tracking](./octoacme-execution-and-tracking.md)
- Preparing a release: consult [Release & Deployment](./octoacme-release-and-deployment.md)
- After a sprint/release/incident: run a [Retrospective](./octoacme-retrospective-and-continuous-improvement.md)

## Contributing to These Docs

To propose updates or add new content, open an issue using the Add Content to Project Management Process Docs template:
https://github.com/bagusnz/skills-scale-institutional-knowledge-using-copilot-spaces/issues/new?template=add-update-content-to-process-docs.yml

Acceptance criteria:
- Content aligns with existing process docs
- Update improves clarity or closes a documented gap
- Proposed content reviewed with stakeholders where needed
