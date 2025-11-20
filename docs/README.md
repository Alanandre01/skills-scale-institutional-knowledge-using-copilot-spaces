```markdown
# OctoAcme Project Management Documentation — README

This folder centralizes OctoAcme project management process documents used by the team and by Copilot Spaces.

## Purpose
- Centralize project management process knowledge for all team members
- Turn tacit insights into searchable, versioned docs
- Standardize workflows and reduce single-person dependency risk
- Make it easy to find, use, and update process guidance

## Brief overview of OctoAcme project management processes
OctoAcme runs projects iteratively and with clear ownership, focusing on customer value and data-informed decisions. Projects typically progress through these stages:

- Initiation — validate the problem, stakeholders, and measurable outcomes (Project One-pager).
- Planning — create a prioritized backlog, estimate scope, map milestones, and document dependencies and tests.
- Execution & Tracking — run the delivery cadence (standups, weekly syncs), use a project board (Backlog → Ready → In Progress → In Review → QA → Done), follow PR and CI rules, and track velocity and blockers.
- Release & Deployment — prepare release notes, run pre-release checks and smoke tests, and follow rollback/playbook steps if needed.
- Retrospective & Continuous Improvement — capture learnings, create action items, and measure impact.

Core principles: customer-first, iterative delivery, clear ownership (PM + Product Lead), psychological safety, and data-informed decisions.

Team rhythm & workflows (high level)
- Standups: daily, focused on progress, blockers, and dependencies.
- Weekly delivery sync: progress, risks, and cross-team escalations.
- Demos: at the end of sprints/milestones.
- PR guidance: small PRs when possible, link the issue and acceptance criteria, run CI and security scans before requesting review, require at least one approval.

## Links to process documents
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## How to use & contribute
- These are living artifacts. Suggest edits via Issues or Pull Requests.
- Use the `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` template when requesting updates.
- Add new process docs to this folder (`docs/`) and link them from this README.

## Acceptance criteria for this README
- Content aligns with existing process docs.
- README improves discoverability and onboarding.
- README points to each process document stored in `docs/`.

```