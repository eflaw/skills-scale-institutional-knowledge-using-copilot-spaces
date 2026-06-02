# OctoAcme Project Management Processes

Welcome to the OctoAcme project management documentation. This folder contains comprehensive guides for running projects at OctoAcme, designed to scale institutional knowledge and ensure consistent execution across teams.

## Overview

OctoAcme operates a structured, iterative project management approach grounded in customer value, clear ownership, and data-driven decision-making. The organization follows a five-phase lifecycle—Initiation, Planning, Execution, Release, and Retrospective—with distinct deliverables and gate reviews at each stage. 

### Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

### 1. Initiation
Projects begin with lightweight one-pagers that validate business need and stakeholder alignment before advancing to formal planning. Key deliverables include a problem statement, success metrics, stakeholder identification, and a high-level timeline.

**Document**: [Project Initiation Guide](octoacme-project-initiation.md)

### 2. Planning
Once approved, the Project Manager and Product Manager collaborate to break work into prioritized backlog items with clear acceptance criteria, establish release timelines, and identify risks and dependencies that are continuously monitored throughout execution.

**Document**: [Project Planning Guide](octoacme-project-planning.md)

### 3. Execution & Tracking
During execution, OctoAcme maintains a disciplined team rhythm centered on daily standups, weekly delivery syncs, and regular demos to track progress against milestones. The organization emphasizes quality through multiple testing strategies—unit tests, integration tests, smoke tests, and security scanning in CI—while keeping pull requests lean and requiring peer review before merge.

**Document**: [Execution & Tracking Guide](octoacme-execution-and-tracking.md)

### 4. Release & Deployment
Release management is standardized with pre-release checklists, deployment verification, rollback playbooks, and post-release communication to support, ensuring quality and minimizing production risk.

**Document**: [Release & Deployment Guide](octoacme-release-and-deployment.md)

### 5. Retrospective & Continuous Improvement
OctoAcme embeds continuous improvement into its culture through retrospectives held after each sprint, release, or incident. These sessions capture what went well, identify improvements, and generate actionable items with clear owners and due dates.

**Document**: [Retrospective & Continuous Improvement Guide](octoacme-retrospective-and-continuous-improvement.md)

## Core Roles & Personas

OctoAcme defines clear personas and responsibilities across three core roles:

- **Developers**: Build and test features collaboratively, participate in design and code reviews, help identify technical risks
- **Product Managers**: Define customer value and prioritize the roadmap, validate solutions through user research and metrics
- **Project Managers**: Coordinate delivery, manage schedules and risks, ensure stakeholder alignment and transparency

**Document**: [Roles & Personas](octoacme-roles-and-personas.md)

## Risk Management & Communication

Risk management is proactive, with a centralized Risk Register identifying threats, likelihood, and mitigations reviewed weekly. Escalation paths are defined to ensure timely resolution from team level through sponsor level. Communication is structured through weekly PM-PdM syncs, twice-weekly standups, and monthly stakeholder updates using standardized templates.

**Document**: [Risk Management & Communication Guide](octoacme-risks-and-communication.md)

## Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Communication Cadence

- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## Using These Documents

1. **For onboarding**: Start with [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction
2. **For process guidance**: Navigate to the specific lifecycle phase you're working on
3. **For role clarity**: Review [Roles & Personas](octoacme-roles-and-personas.md) to understand responsibilities
4. **For templates and checklists**: Each guide includes practical templates you can adapt for your project
5. **For Copilot Spaces**: Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context

## Contributing to Process Documentation

To request updates or add new content to these process documents, use the issue template:
- [Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)

This Copilot Space serves as a centralized hub for project management knowledge, helping to:
- Scale institutional knowledge across teams
- Convert tacit team insights into searchable, versioned artifacts
- Give all team members equal access to processes, decisions, and rationale
- Accelerate onboarding and reduce single-person dependency risk
- Enable consistent, repeatable project execution
