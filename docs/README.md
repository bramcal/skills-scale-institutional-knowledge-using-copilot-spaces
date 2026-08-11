# OctoAcme Project Management Process Docs

This folder collects OctoAcme's project management process guidance for cross-functional product, service, and integration work. Use this README as a starting point for the full process set.

## Document index

- [OctoAcme Project Management Process Docs](README.md) — this index and summary.
- [Project Management Overview](octoacme-project-management-overview.md) — principles, core roles, key artifacts, lifecycle, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — one-pager, stakeholder alignment, initial risks, resource needs, and the planning decision gate.
- [Project Planning](octoacme-project-planning.md) — kickoff, backlog, estimates, Definition of Done, dependencies, release planning, and planning checklist.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — team rhythm, project board workflow, PR expectations, quality practices, metrics, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — risk register, risk lifecycle, stakeholder updates, communication templates, and escalation paths.
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — release types, pre-release requirements, deployment checklist, rollback, and release notes.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — retrospective cadence, structure, action item tracking, and improvement culture.
- [OctoAcme Personas](octoacme-roles-and-personas.md) — developer, product manager, and project manager responsibilities and communication patterns.

## Process overview

OctoAcme manages cross-functional projects through a lightweight lifecycle that emphasizes customer value, iterative delivery, clear ownership, data-informed decisions, and psychological safety.

### Initiation

Projects begin with validation and authorization. Teams confirm the business need, measurable outcomes, stakeholders, success criteria, initial timeline, quick risks and dependencies, resource needs, and a proposed team. The project moves into planning when success metrics are clear, stakeholders agree on priority, and team availability is confirmed.

### Planning

Approved initiatives are turned into actionable plans and backlogs. The team holds kickoff, creates prioritized backlog items with acceptance criteria, estimates scope, defines the Definition of Done, identifies dependencies and integration points, and maps releases and milestones. Risks and cross-team dependencies are captured and escalated through the agreed syncs and project board.

### Execution and tracking

Delivery teams use regular standups, weekly delivery syncs, and sprint or milestone demos to track progress. Work is managed through a project board from backlog through done, with small pull requests, issue links, acceptance criteria, automated CI checks, and review before merge. Teams monitor velocity, burndown, success metrics, and operational dashboards while escalating blockers from the team level through PM, Product Lead, and sponsor paths as needed.

### Risk management and communication

Risks are identified during planning and execution, assessed for impact and likelihood, assigned owners and mitigations, and reviewed in weekly syncs. Stakeholder communication uses regular weekly or milestone-based updates and a single source of truth, such as a project README or release document. Escalations flow from the team to the PM, Product Lead, and sponsor, with security incidents following the security incident runbook and Security on-call notification.

### Release and deployment

Release planning distinguishes patch, minor, and major releases. Before release, teams ensure acceptance criteria are met, PRs are merged, CI and security scans pass, release notes are drafted, rollback or mitigation plans are documented, and smoke tests are ready. Deployment proceeds through staging, smoke tests, production deployment, post-deploy verification, and stakeholder/support announcements, with rollback and incident response available for failures or critical issues.

### Retrospectives and continuous improvement

Teams run retrospectives after each sprint, release, important milestone, and incident. Retrospectives capture what went well, what could improve, action items with owners and due dates, and follow-up on previous actions. Improvement work is tracked in the backlog or issues, reviewed in weekly PM syncs, measured for impact, and kept iterative by focusing on a small number of top actions.

### Roles and personas

OctoAcme documents the responsibilities of developers, product managers, and project managers. Developers build, test, document, review, estimate, and help manage technical risk. Product managers define outcomes, prioritize work, collaborate on trade-offs, and validate solutions through research and metrics. Project managers coordinate plans, schedules, risks, meetings, documentation, and stakeholder communication so the team can deliver transparently and efficiently.
