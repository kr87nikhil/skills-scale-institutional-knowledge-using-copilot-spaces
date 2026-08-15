# OctoAcme Project Management Documentation

## Overview
OctoAcme follows a structured, iterative project management approach that emphasizes customer value, clear ownership, and continuous improvement. This documentation is the central entry point for our project management processes and provides guidance for the full delivery lifecycle—from initiation through retrospectives—helping teams onboard quickly and work consistently.

## Brief summary of processes
Initiation focuses on validating the problem and outcomes with a lightweight Project One-pager that captures success metrics and stakeholders. Planning turns approved initiatives into a prioritized, estimated backlog with clear acceptance criteria and a Definition of Done. Execution uses a project board (Backlog → Ready → In Progress → In Review → QA → Done), small pull requests, CI checks, and disciplined reviews to deliver small, testable increments. Releases follow a checklist-driven process with staging smoke tests, rollback plans, and post-deploy verifications. Retrospectives and a tracked action-item process ensure continuous improvement and learning.

## Key workflows & quality practices
- Pull Request workflow: keep PRs small where possible, include issue links and acceptance criteria, run automated tests, linting, and security scans in CI, and require review approvals before merging.
- Testing & QA: unit tests for new logic, integration tests when applicable, end-to-end smoke tests for critical flows, CI security scans, and manual QA for final acceptance as needed.
- Risk & escalation: maintain a Risk Register (ID, impact, likelihood, owner, mitigation) and use clear escalation paths (team → PM → Product Lead → Sponsor) for blockers and incidents.

## Where to find process docs
- Project Management Overview: docs/octoacme-project-management-overview.md
- Project Initiation Guide: docs/octoacme-project-initiation.md
- Project Planning: docs/octoacme-project-planning.md
- Execution & Tracking: docs/octoacme-execution-and-tracking.md
- Risk Management & Communication: docs/octoacme-risks-and-communication.md
- Release & Deployment Guide: docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement: docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas: docs/octoacme-roles-and-personas.md

## Quick navigation by role
- Project Managers (PM): start with the Project Initiation and Planning docs, maintain the Risk Register, and run weekly PM+PdM syncs.
- Product Managers (PdM): use the One-pager template, own success metrics, and work with PM to prioritize the backlog.
- Developers: follow the PR workflow and testing guidance in Execution & Tracking and the Release Guide for deployment prep.
- QA: consult Testing & QA practices and the Release checklist to plan verification and smoke tests.

## Issue templates
- Add/Update process doc issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

## Maintaining these docs
Keep process documents in docs/ and update them via the repository PR process so changes are versioned and reviewed. If you'd like to propose updates to these process docs, use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/.
