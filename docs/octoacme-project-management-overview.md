# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- **Project Manager (PM)**: coordinates delivery, schedules, risk, communications.
- **Product Manager (PdM)**: defines outcomes, prioritizes backlog, and measures success.
- **Scrum Master**: facilitates agile ceremonies, removes impediments, drives continuous improvement.
- **Business Analyst (BA)**: gathers requirements, refines backlog items, bridges stakeholders and technical teams.
- **Developers**: implement features, collaborate on design and testability.
- **QA/Testing**: validate quality and acceptance criteria.
- **UX/UI Designer**: designs user-centric interfaces, defines user journeys, ensures usability.
- **DevOps Engineer**: owns deployment, infrastructure, CI/CD automation, and system reliability.
- **Stakeholders**: provide inputs and approvals.

For detailed role descriptions, responsibilities, and interaction patterns, see [Roles and Personas](octoacme-roles-and-personas.md) and [Role-Responsibility Matrix](role-responsibility-matrix.md).

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
Effective communication is critical for project success. OctoAcme maintains a structured communication rhythm:

**Regular Meetings**:
- **Daily standups**: Twice-weekly or daily for delivery team (Developers, QA, UX/UI, facilitated by Scrum Master)
- **Weekly PM + PdM sync**: Alignment on priorities, risks, and roadmap
- **Weekly backlog refinement**: BA, PdM, and team refine upcoming stories
- **Sprint planning**: Every sprint start (Scrum Master, PdM, team)
- **Sprint review**: Every sprint end to demo completed work
- **Sprint retrospective**: Every sprint end to reflect and improve
- **Monthly stakeholder updates**: Status, milestones, risks, and decisions

**Ad-Hoc Communication**:
- Escalations as needed (clear escalation path in Project Charter)
- Design reviews (UX/UI, Developers, PdM)
- Code reviews (continuous, via pull requests)
- Deployment coordination (DevOps, PM, Developers)

**Communication Channels**:
- Slack/Teams for real-time collaboration
- Email for formal communications and approvals
- Project boards for status visibility
- Documentation (docs/ folder) for persistent knowledge

**Artifact Maintenance Cadence**:
- **Project Charter**: Update when scope, timeline, or team changes; PM reviews monthly
- **Risk Register**: Review weekly in PM/PdM sync; PM updates as new risks emerge
- **Roadmap**: PdM updates after sprint planning or when priorities shift
- **Retrospective Notes**: Scrum Master documents after every retro; PM tracks action item completion
- **Release Notes**: Developers/PM update during sprint; DevOps finalizes before deployment

For communication best practices, see [Risks and Communication](octoacme-risks-and-communication.md).

## Quality Assurance Embedded in Lifecycle
Quality is not a phase—it's integrated throughout the project lifecycle:

**Initiation Phase**:
- Define quality standards and acceptance criteria upfront
- Identify QA resources and testing strategy
- Set quality metrics and success criteria

**Planning Phase**:
- Include QA/Testing in backlog refinement and sprint planning
- Define testability requirements with Developers
- Plan test environments and data needs
- Establish automated testing strategy with DevOps

**Execution Phase**:
- Continuous testing alongside development (unit, integration, functional)
- Code reviews ensure code quality and adherence to standards
- Design reviews validate usability and accessibility
- QA validates acceptance criteria before stories are marked done

**Release Phase**:
- Regression testing before deployment
- Smoke tests post-deployment
- Performance and security validation
- Deployment monitoring and alerting

**Retrospective Phase**:
- Review quality metrics (bug escape rate, test coverage, deployment success rate)
- Identify quality process gaps and create improvement actions
- Celebrate quality wins and learn from defects

**Quality Checkpoints**:
- **Definition of Ready**: Stories meet criteria before entering sprint
- **Definition of Done**: Features meet quality bar before marking complete
- **Code Review Gate**: All code reviewed before merge
- **QA Sign-off**: QA validates acceptance criteria before release
- **Deployment Verification**: Post-deployment smoke tests pass

For detailed quality practices, see [Execution and Tracking](octoacme-execution-and-tracking.md) and [Release and Deployment](octoacme-release-and-deployment.md).

## How to use these docs
- Keep the Project Charter updated in the project repo (review monthly or when scope changes).
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
- Use checklists and templates in docs/ to ensure consistent, repeatable processes.
- Maintain retrospective notes and action items to drive continuous improvement.
- Reference the Role-Responsibility Matrix to clarify ownership and collaboration patterns.
