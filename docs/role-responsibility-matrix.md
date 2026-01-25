# Role-Responsibility Matrix (RACI)

This matrix defines who is **Responsible**, **Accountable**, **Consulted**, and **Informed** for key project activities at OctoAcme.

## RACI Legend

- **R** (Responsible): The person(s) who perform the work to complete the task
- **A** (Accountable): The person ultimately answerable for the correct and thorough completion of the task (only one A per task)
- **C** (Consulted): People whose opinions are sought; two-way communication
- **I** (Informed): People who are kept up-to-date on progress; one-way communication

---

## Project Initiation Phase

| Activity | PM | PdM | BA | Scrum Master | Dev | QA | UX/UI | DevOps | Stakeholders |
|----------|----|----|----|--------------|----|----|----|--------|--------------|
| Create project one-pager | R | A | C | I | I | I | I | I | C |
| Define problem statement & goals | C | A | R | I | C | I | C | I | C |
| Identify stakeholders | R | C | C | I | I | I | I | I | C |
| Initial risk assessment | R | C | C | C | C | C | C | C | I |
| Approve project initiation | I | C | I | I | I | I | I | I | A |
| Create repository/project workspace | R | I | I | C | C | I | I | C | I |

## Planning Phase

| Activity | PM | PdM | BA | Scrum Master | Dev | QA | UX/UI | DevOps | Stakeholders |
|----------|----|----|----|--------------|----|----|----|--------|--------------|
| Define project scope | R | A | R | C | C | C | C | I | C |
| Prioritize backlog | C | A | C | C | C | I | C | I | C |
| Create user stories | C | C | R | C | C | C | C | I | I |
| Define acceptance criteria | C | C | R | C | C | R | C | I | I |
| Estimate effort | C | C | I | R | R | C | C | C | I |
| Create project timeline | R | C | I | C | C | I | I | C | I |
| Resource planning | R | C | I | C | C | I | I | C | C |
| Identify dependencies | R | C | C | C | R | C | C | R | I |
| Sprint planning | C | C | I | R | R | C | C | C | I |
| Design user journeys | C | C | C | I | I | I | A | I | C |
| Create wireframes/mockups | C | C | I | I | C | I | R/A | I | C |

## Execution Phase

| Activity | PM | PdM | BA | Scrum Master | Dev | QA | UX/UI | DevOps | Stakeholders |
|----------|----|----|----|--------------|----|----|----|--------|--------------|
| Daily standups | I | I | I | R/A | R | R | R | C | I |
| Implement features | I | C | C | C | R/A | C | C | C | I |
| Code reviews | I | I | I | I | R/A | C | I | C | I |
| Design reviews | C | C | I | I | R | I | R/A | I | C |
| Create test plans | I | C | C | I | C | R/A | C | I | I |
| Execute tests | I | I | I | I | C | R/A | C | C | I |
| Bug triage | C | C | C | C | R | R/A | C | C | I |
| Track sprint progress | R | C | I | R | C | I | I | I | I |
| Update project status | R/A | C | I | C | C | I | I | I | I |
| Remove blockers | C | C | C | R/A | C | C | C | C | C |
| Refine backlog | C | R | R | C | C | C | C | I | I |
| Maintain CI/CD pipeline | I | I | I | I | C | C | I | R/A | I |

## Quality Assurance & Testing

| Activity | PM | PdM | BA | Scrum Master | Dev | QA | UX/UI | DevOps | Stakeholders |
|----------|----|----|----|--------------|----|----|----|--------|--------------|
| Define quality standards | C | C | C | C | C | R/A | C | C | C |
| Functional testing | I | I | I | I | C | R/A | C | I | I |
| Regression testing | I | I | I | I | C | R/A | I | C | I |
| Usability testing | C | C | C | I | C | R | R/A | I | C |
| Accessibility testing | I | I | I | I | C | R | R/A | I | I |
| Performance testing | C | I | I | I | C | R/A | I | R | I |
| Security testing | C | I | I | I | C | R | I | R/A | I |
| Acceptance sign-off | C | C | C | I | I | R/A | C | I | C |

## Release & Deployment Phase

| Activity | PM | PdM | BA | Scrum Master | Dev | QA | UX/UI | DevOps | Stakeholders |
|----------|----|----|----|--------------|----|----|----|--------|--------------|
| Create release plan | R | C | I | C | C | C | I | R | I |
| Approve release | C | C | I | I | I | C | I | C | A |
| Prepare deployment | C | I | I | I | R | C | I | R/A | I |
| Execute deployment | C | I | I | I | C | C | I | R/A | I |
| Verify deployment | C | C | I | I | R | R | I | R | I |
| Smoke testing | I | I | I | I | C | R/A | I | C | I |
| Monitor post-deployment | C | I | I | I | C | C | I | R/A | I |
| Rollback (if needed) | C | C | I | I | C | C | I | R/A | I |
| Release announcement | R | R | I | I | I | I | I | I | I |
| Update documentation | C | C | C | I | R | C | C | R | I |

## Communication & Reporting

| Activity | PM | PdM | BA | Scrum Master | Dev | QA | UX/UI | DevOps | Stakeholders |
|----------|----|----|----|--------------|----|----|----|--------|--------------|
| Weekly PM/PdM sync | R | R | I | I | I | I | I | I | I |
| Stakeholder status updates | R/A | C | C | I | I | I | I | I | I |
| Sprint reviews | C | C | I | R/A | R | R | R | C | I |
| Risk reporting | R/A | C | C | C | C | C | C | C | I |
| Escalation management | R/A | C | C | C | C | C | C | C | C |
| Documentation maintenance | R | C | C | C | C | C | C | C | I |

## Retrospective & Continuous Improvement

| Activity | PM | PdM | BA | Scrum Master | Dev | QA | UX/UI | DevOps | Stakeholders |
|----------|----|----|----|--------------|----|----|----|--------|--------------|
| Facilitate retrospective | C | C | C | R/A | C | C | C | C | I |
| Gather feedback | C | C | C | R | R | R | R | R | I |
| Identify improvements | C | C | C | R | R | R | R | R | I |
| Create action items | C | C | C | R/A | R | R | R | R | I |
| Track improvement metrics | R | C | I | C | I | I | I | I | I |
| Implement process changes | C | C | C | R | C | C | C | C | C |

---

## Role-Specific Ownership Areas

### Project Manager (PM)
**Primary Accountability**:
- Project timeline and schedule management
- Cross-team coordination and communication
- Risk and dependency management
- Stakeholder status reporting
- Project artifact maintenance (charter, plans, status reports)

### Product Manager (PdM)
**Primary Accountability**:
- Product vision and strategy
- Backlog prioritization
- Success metrics and outcome measurement
- Customer/user value delivery
- Feature requirements and acceptance

### Business Analyst (BA)
**Primary Accountability**:
- Requirements gathering and documentation
- User story creation and refinement
- Stakeholder needs translation
- Acceptance criteria definition
- Business process analysis

### Scrum Master
**Primary Accountability**:
- Agile ceremony facilitation
- Team impediment removal
- Process improvement and coaching
- Sprint health and velocity tracking
- Team psychological safety and productivity

### Developers
**Primary Accountability**:
- Feature implementation
- Code quality and reviews
- Technical design and architecture
- Unit and integration testing
- Technical documentation

### QA/Testing
**Primary Accountability**:
- Test planning and execution
- Quality standards and validation
- Defect identification and tracking
- Acceptance criteria verification
- Test automation

### UX/UI Designer
**Primary Accountability**:
- User experience design
- Interface design and prototyping
- User research and validation
- Design system maintenance
- Usability and accessibility standards

### DevOps Engineer
**Primary Accountability**:
- CI/CD pipeline management
- Infrastructure and deployment
- System monitoring and reliability
- Deployment automation
- Security and compliance

### Stakeholders
**Primary Accountability**:
- Strategic direction and approvals
- Business requirements validation
- Resource allocation support
- Project prioritization decisions
- Adoption and change management

---

## Using This Matrix

### For Project Managers:
- Use this matrix during project kickoff to clarify roles and expectations
- Reference during planning to ensure all activities have clear ownership
- Review when delegation or escalation questions arise

### For Team Members:
- Understand your responsibilities (R) and what you're accountable for (A)
- Know when you need to be consulted (C) or just informed (I)
- Identify your key collaboration points with other roles

### For New Team Members:
- Quickly understand role expectations and boundaries
- Identify who to collaborate with for specific activities
- Learn the communication patterns and touchpoints

### Customization:
- This matrix represents typical responsibilities at OctoAcme
- Adjust based on team size, project complexity, and organizational needs
- Document any deviations in the Project Charter

---

## Related Resources

- [Roles and Personas](octoacme-roles-and-personas.md) - Detailed role descriptions
- [Project Kickoff Checklist](project-kickoff-checklist.md) - Kickoff planning and execution
- [Handoff Checklist](handoff-checklist.md) - Role transition and handoff processes
- [Project Management Overview](octoacme-project-management-overview.md) - Core principles and workflow
