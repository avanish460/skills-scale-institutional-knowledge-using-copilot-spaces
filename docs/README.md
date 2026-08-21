# OctoAcme Project Management Documentation

Welcome — this folder contains OctoAcme's project management process guidance from initiation through delivery and continuous improvement. The documents are intended to be a single source of truth for how we plan, execute, and improve projects so new team members and stakeholders can find consistent, actionable guidance.

## Overview

OctoAcme follows a customer-first, iterative delivery approach with clear ownership and data-informed decisions. Work starts with lightweight validation (a Project One-pager) and moves through planning, execution, release, and retrospective stages. Teams use small, testable increments; well-defined acceptance criteria and a Definition of Done; and structured communication and escalation paths to keep stakeholders aligned and risks visible.

## Key workflows and quality practices

- Project board workflow: Backlog → Ready → In Progress → In Review → QA → Done.
- Backlog items and PRs include acceptance criteria and links to the related issue; PRs should be small, run CI/lint/security checks, and require approvals.
- Testing and QA: unit/integration tests, end-to-end smoke tests for critical flows, CI security scanning, and manual QA when needed.
- Release process: pre-release checklist (passing CI, release notes, rollback plan), staged deploys with post-deploy verification, and a rollback/incident playbook.

## Table of contents

- Getting started
  - [Project Management Overview](./octoacme-project-management-overview.md) — high-level approach, roles, lifecycle, and core artifacts
- Project lifecycle
  - [Project Initiation](./octoacme-project-initiation.md) — one-pager, stakeholder alignment, decision gate
  - [Project Planning](./octoacme-project-planning.md) — backlog, estimation, release plans, DoD
  - [Execution & Tracking](./octoacme-execution-and-tracking.md) — day-to-day delivery, boards, PR workflow, reporting
  - [Release & Deployment](./octoacme-release-and-deployment.md) — release types, deployment checklist, rollback playbook
  - [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — retrospectives and tracking improvements
- Cross-cutting
  - [Risk Management & Communication](./octoacme-risks-and-communication.md) — risk register, templates, escalation
  - [Roles & Personas](./octoacme-roles-and-personas.md) — role summaries and responsibilities

## Quick reference

- New team members: Start with the Project Management Overview, then read Roles & Personas to understand responsibilities. Use the lifecycle docs as your project progresses.
- Project Managers: Follow Initiation → Planning → Execution → Release and track risks in the Risk Register; surface blockers at weekly syncs.
- Product Managers: Define success metrics in Initiation, prioritize in Planning, and validate via Execution & Tracking and Retrospectives.
