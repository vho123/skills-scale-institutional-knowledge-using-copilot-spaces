# OctoAcme Project Management Documentation

## Overview
OctoAcme runs projects using a structured, customer-first approach that emphasizes iterative delivery, clear ownership, and data-informed decisions. This documentation folder is the central index for our program management processes and provides quick navigation to each phase of the project lifecycle, role responsibilities, and key artifacts used to plan, execute, and improve our work.

Our lifecycle moves from Initiation (validate business need, align stakeholders) to Planning (break work into shippable increments and identify risks), through Execution & Tracking (manage day-to-day delivery, PR-driven workflow, and CI gating), to Release & Deployment (standardized release process, rollback playbook), and finally Retrospective & Continuous Improvement (capture learnings and drive action). These guides are intended to be the single source of truth for how OctoAcme runs projects end-to-end.

Execution emphasizes a lightweight board-driven workflow (Backlog → Ready → In Progress → In Review → QA → Done), small focused pull requests, CI checks, and a clear PR approval policy. Quality is enforced through unit and integration tests, smoke tests for critical flows, security scanning in CI, and manual QA where appropriate. Risks and blockers are tracked in a simple risk register and escalated through a documented path (team → PM → Product Lead → Sponsor) so issues receive the right attention quickly.

## Process Documentation
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Personas](octoacme-roles-and-personas.md)

## Quick Reference

Core Roles
- Project Manager (PM): coordinates delivery, schedules, risks, and communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Developers: implement features, tests, and reviews.
- QA/Testing: validate acceptance criteria and quality.

Key Artifacts
- Project One-pager / Charter
- Roadmap and Release Plan
- Sprint / Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## How to use this folder
Keep the Project One-pager and process-specific artifacts updated in this docs/ folder. Use these files as the authoritative reference for process expectations, checklists, and templates. If you want to propose changes to these docs, open a process-doc update issue using the templates in .github/ISSUE_TEMPLATE/.
