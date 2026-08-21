# OctoAcme Project Management Documentation

Welcome — this folder contains OctoAcme's project management process guidance, from initiation through delivery, releases, and continuous improvement. Use this README as your single entry point to discover role definitions, lifecycle phases, checklists, and templates that help teams deliver predictable, customer‑focused outcomes.

## Brief overview of OctoAcme's project management processes

OctoAcme follows a lightweight, stage-gated lifecycle that starts with Initiation and moves through Planning, Execution, Release, and Close/Improve. Initiation captures the problem, stakeholders, success metrics, and a one‑pager to validate the idea and decide whether to proceed. Planning turns approved work into a prioritized backlog, defines the Definition of Done, identifies dependencies and risks, and sets milestones and release plans.

Execution emphasizes iterative delivery, small pull requests, and rigorous CI gates. Teams track work on a project board (Backlog → Ready → In Progress → In Review → QA → Done), use acceptance criteria attached to issues and PRs, and run unit/integration tests plus security scans in CI. Releases require pre‑release checks, smoke tests, and rollback plans; post‑deploy verifications and communications are standard. Finally, retrospectives capture learnings and convert them into tracked action items to continuously improve processes and outcomes.

Roles are explicit: Product Managers define the vision and success metrics; Project Managers coordinate delivery, risk, and communications; Developers implement and test; QA validates acceptance criteria; Stakeholders provide inputs and approvals. Regular cadences (daily standups, weekly delivery syncs, sprint demos, and milestone stakeholder updates) keep communication predictable, surface risks, and enable timely escalation.

## Table of contents (process documents)

- [Project Management Overview](./octoacme-project-management-overview.md) — Introduction to principles, lifecycle, core artifacts, and communication cadence.  
- [Project Initiation](./octoacme-project-initiation.md) — How to validate ideas, create a one‑pager, identify stakeholders, and gate go/no‑go decisions.  
- [Project Planning](./octoacme-project-planning.md) — Backlog creation, estimation, Definition of Done (DoD), sprint planning, and dependency management.  
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Day‑to‑day workflows: project board, PR conventions, CI requirements, testing expectations, and reporting.  
- [Risks & Communication](./octoacme-risks-and-communication.md) — Maintaining the Risk Register, stakeholder updates, incident comms, and escalation paths.  
- [Release & Deployment](./octoacme-release-and-deployment.md) — Release types, pre‑release requirements, deployment checklist, rollback playbook, and release notes template.  
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure, action‑item tracking, and measuring improvement impact.  
- [Roles & Personas](./octoacme-roles-and-personas.md) — Role definitions and responsibilities for Developers, Product Managers, Project Managers, QA, and Stakeholders.

## Quick reference

For new team members:
1. Read the [Project Management Overview](./octoacme-project-management-overview.md).  
2. Check [Roles & Personas](./octoacme-roles-and-personas.md) to find your responsibilities.  
3. Follow the lifecycle docs as your project moves from Initiation → Planning → Execution → Release → Retrospective.

For Project Managers:
- Follow: [Initiation](./octoacme-project-initiation.md) → [Planning](./octoacme-project-planning.md) → [Execution & Tracking](./octoacme-execution-and-tracking.md) → [Release & Deployment](./octoacme-release-and-deployment.md).  
- Use the Risk Register and weekly syncs to manage cross‑team dependencies and escalations.

For Product Managers:
- Lead success‑metric definition in [Project Initiation](./octoacme-project-initiation.md).  
- Drive prioritization in [Project Planning](./octoacme-project-planning.md).  
- Validate outcomes through demos and metrics reviewed in [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).

## How to use / update these docs

- Use the existing issue template (/.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose edits or new process docs.  
- Keep the Project One‑pager and release docs updated in the project repo as the single source of truth.  
- When adding or changing process guidance, capture rationale and acceptance criteria per the issue template.
