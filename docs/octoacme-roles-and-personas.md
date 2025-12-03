# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

## Changelog

| Date | Change | Author |
|------|--------|--------|
| 2025-12-03 | Added Expanded Personas and Roles section with six new personas: Release Manager, Risk Champion, Technical Lead, Communication Specialist, QA Coordinator, Stakeholder Liaison. Added Role Interaction Matrix. | Process Team |

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Expanded Personas and Roles

This section defines additional personas to improve clarity, accountability, and streamline project management processes.

---

### Release Manager

#### Description
The Release Manager oversees the release lifecycle from planning through deployment and post-release validation. They coordinate across QA, development, and stakeholders to ensure smooth, predictable releases.

#### Primary Responsibilities
- Coordinate release planning, scheduling, and timeline management
- Ensure release gate criteria are met before deployment
- Manage release communications and stakeholder notifications
- Facilitate go/no-go decisions for releases
- Track and resolve release blockers
- Maintain release documentation and runbooks

#### Primary Interactions
- **Project Manager**: Align release schedule with project milestones
- **QA Coordinator**: Confirm testing completion and sign-off
- **Developers**: Coordinate code freeze and release branches
- **Stakeholder Liaison**: Ensure stakeholders are informed of release status
- **Technical Lead**: Validate architectural readiness for release

#### Typical Artifacts Owned
- Release plan and schedule
- Release notes
- Go/no-go decision log
- Release runbook
- Rollback plan

#### Escalation Path
- Escalate release blockers to Project Manager and Technical Lead immediately
- Notify stakeholders via Stakeholder Liaison if release timeline is at risk
- Escalate critical deployment failures to Technical Lead and Project Manager

---

### Risk Champion

#### Description
The Risk Champion proactively identifies, monitors, and escalates project risks. They maintain the risk register and ensure mitigation actions are tracked and executed.

#### Primary Responsibilities
- Maintain and update the project risk register
- Facilitate risk identification sessions with the team
- Track mitigation actions and owners
- Escalate risks when thresholds are crossed
- Report risk status to Project Manager and stakeholders
- Advise on risk-adjusted planning decisions

#### Primary Interactions
- **Project Manager**: Provide regular risk updates and escalations
- **Technical Lead**: Identify technical risks and mitigations
- **Stakeholder Liaison**: Communicate high-impact risks to stakeholders
- **QA Coordinator**: Align on quality-related risks

#### Typical Artifacts Owned
- Risk register
- Risk assessment reports
- Mitigation action tracker
- Risk escalation log

#### Escalation Path
- Escalate high-probability or high-impact risks to Project Manager within 24 hours
- Notify stakeholders through Stakeholder Liaison when risks may affect milestones
- Engage Technical Lead for technical risk mitigation strategies

---

### Technical Lead

#### Description
The Technical Lead provides technical direction and guidance for the development team. They make architectural decisions, mentor developers, and ensure technical quality standards are met.

#### Primary Responsibilities
- Guide architecture and design decisions
- Conduct and facilitate code reviews
- Mentor and support the development team
- Interface with Product Owner on technical feasibility
- Identify and communicate technical debt and risks
- Ensure technical documentation is maintained

#### Primary Interactions
- **Developers**: Provide guidance, review code, mentor team members
- **Product Owner**: Advise on technical feasibility and trade-offs
- **Release Manager**: Validate technical readiness for releases
- **Risk Champion**: Identify and assess technical risks

#### Typical Artifacts Owned
- Architecture decision records (ADRs)
- Technical design documents
- Code review guidelines
- Technical debt backlog

#### Escalation Path
- Escalate critical technical blockers to Project Manager
- Raise technical risks to Risk Champion for tracking
- Engage Product Owner when technical constraints affect scope

---

### Communication Specialist

#### Description
The Communication Specialist manages project communication flows, ensures documentation and updates reach the right audiences, and maintains consistency in project messaging.

#### Primary Responsibilities
- Curate and distribute project bulletins and updates
- Coordinate internal and external communications
- Ensure documentation is current and accessible
- Support Project Manager with communication strategy
- Maintain communication calendar and templates
- Facilitate cross-team information sharing

#### Primary Interactions
- **Project Manager**: Align on communication priorities and messaging
- **Stakeholder Liaison**: Coordinate stakeholder-facing communications
- **All team members**: Gather input for updates and announcements
- **Release Manager**: Coordinate release communications

#### Typical Artifacts Owned
- Communication plan
- Project bulletins and newsletters
- Meeting minutes and action items
- Documentation index

#### Escalation Path
- Escalate communication blockers to Project Manager
- Notify Stakeholder Liaison if stakeholder communications are delayed
- Engage Project Manager for crisis communication needs

---

### QA Coordinator

#### Description
The QA Coordinator leads quality assurance efforts, coordinates testing activities, and ensures quality standards are met before releases.

#### Primary Responsibilities
- Plan and coordinate testing activities
- Define and maintain QA standards and processes
- Review and approve test plans and results
- Track and report on quality metrics
- Coordinate with developers on defect resolution
- Provide testing sign-off for releases

#### Primary Interactions
- **Developers**: Coordinate defect triage and resolution
- **Release Manager**: Provide testing status and sign-off
- **Technical Lead**: Align on quality requirements and test coverage
- **Risk Champion**: Identify quality-related risks

#### Typical Artifacts Owned
- Test plans and test cases
- QA standards and guidelines
- Defect reports
- Testing sign-off documentation
- Quality metrics dashboard

#### Escalation Path
- Escalate critical defects to Technical Lead and Project Manager
- Notify Release Manager if testing cannot be completed on schedule
- Raise quality risks to Risk Champion

---

### Stakeholder Liaison

#### Description
The Stakeholder Liaison serves as the primary point of contact between the project team and external stakeholders. They ensure stakeholder needs are understood and addressed.

#### Primary Responsibilities
- Maintain stakeholder contact list and communication preferences
- Facilitate stakeholder meetings and feedback sessions
- Communicate project status and updates to stakeholders
- Gather and relay stakeholder feedback to the team
- Manage stakeholder expectations and concerns
- Support change management activities

#### Primary Interactions
- **Project Manager**: Align on stakeholder priorities and communications
- **Product Owner**: Relay stakeholder feedback on product direction
- **Communication Specialist**: Coordinate external communications
- **Risk Champion**: Communicate risks affecting stakeholders

#### Typical Artifacts Owned
- Stakeholder register
- Stakeholder communication log
- Meeting agendas and minutes (stakeholder meetings)
- Feedback summaries

#### Escalation Path
- Escalate stakeholder concerns to Project Manager and Product Owner
- Notify Risk Champion if stakeholder issues pose project risk
- Engage Communication Specialist for urgent stakeholder notifications

---

## Role Interaction Matrix

This matrix maps new personas to existing core roles, showing who leads (L), supports (S), or is consulted (C) for common activities.

| Activity | Project Manager | Product Owner | Developers | QA | Release Manager | Risk Champion | Technical Lead | Communication Specialist | QA Coordinator | Stakeholder Liaison |
|----------|-----------------|---------------|------------|-----|-----------------|---------------|----------------|--------------------------|----------------|---------------------|
| **Planning** | L | C | S | S | C | C | C | S | S | C |
| **Release** | C | C | S | S | L | C | S | S | S | S |
| **Risk Escalation** | L | C | S | S | C | L | C | S | C | S |
| **Communication** | L | C | S | S | S | C | S | L | S | L |
| **Quality Assurance** | C | C | S | L | C | C | S | S | L | S |
| **Technical Decisions** | C | C | S | S | C | C | L | S | C | S |

**Legend:**
- **L** = Leads the activity
- **S** = Supports the activity
- **C** = Consulted during the activity
