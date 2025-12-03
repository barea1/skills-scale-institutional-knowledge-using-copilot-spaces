# Role Definition Template

This template provides a reusable structure for defining any role or persona within OctoAcme projects. Use this template to ensure consistency when documenting new roles.

---

## Template Structure

| Field | Description |
|-------|-------------|
| **Role Name** | The official name of the role/persona |
| **Purpose** | A brief statement describing the role's primary purpose and value to the project |
| **Responsibilities** | 3–6 key responsibilities the role is accountable for |
| **Primary Interactions** | Key roles this persona coordinates with and how they interact |
| **Artifacts Owned** | Documents, plans, or deliverables this role is responsible for creating/maintaining |
| **Decision Authority** | Types of decisions this role can make independently vs. those requiring escalation |
| **Escalation Path** | Who to notify and when, for issues beyond the role's authority |
| **Acceptance Criteria for Handoffs** | Criteria that must be met when transitioning work to/from this role |

---

## Blank Template

Copy and fill in the following template when defining a new role:

```markdown
### [Role Name]

#### Purpose
[Brief description of the role's purpose]

#### Responsibilities
- [Responsibility 1]
- [Responsibility 2]
- [Responsibility 3]
- [Responsibility 4]
- [Responsibility 5]
- [Responsibility 6]

#### Primary Interactions
| Role | Interaction Type |
|------|------------------|
| [Role 1] | [How they interact] |
| [Role 2] | [How they interact] |
| [Role 3] | [How they interact] |

#### Artifacts Owned
- [Artifact 1]
- [Artifact 2]
- [Artifact 3]

#### Decision Authority
- **Can decide independently:** [Types of decisions]
- **Must escalate:** [Types of decisions requiring escalation]

#### Escalation Path
- [Escalation scenario 1]: Notify [who] within [timeframe]
- [Escalation scenario 2]: Notify [who] within [timeframe]

#### Acceptance Criteria for Handoffs
- [ ] [Criterion 1]
- [ ] [Criterion 2]
- [ ] [Criterion 3]
```

---

## Example: Release Manager

### Release Manager

#### Purpose
Oversee the release lifecycle from planning through deployment and post-release validation, ensuring smooth and predictable releases.

#### Responsibilities
- Coordinate release planning, scheduling, and timeline management
- Ensure release gate criteria are met before deployment
- Manage release communications and stakeholder notifications
- Facilitate go/no-go decisions for releases
- Track and resolve release blockers
- Maintain release documentation and runbooks

#### Primary Interactions
| Role | Interaction Type |
|------|------------------|
| Project Manager | Align release schedule with project milestones |
| QA Coordinator | Confirm testing completion and sign-off |
| Developers | Coordinate code freeze and release branches |
| Stakeholder Liaison | Ensure stakeholders are informed of release status |
| Technical Lead | Validate architectural readiness for release |

#### Artifacts Owned
- Release plan and schedule
- Release notes
- Go/no-go decision log
- Release runbook
- Rollback plan

#### Decision Authority
- **Can decide independently:** Release timing adjustments within approved window, minor release note updates, internal team communications
- **Must escalate:** Go/no-go decisions for major releases, timeline changes affecting stakeholders, rollback decisions

#### Escalation Path
- Release blockers: Notify Project Manager and Technical Lead immediately
- Timeline at risk: Notify stakeholders via Stakeholder Liaison within 24 hours
- Critical deployment failures: Escalate to Technical Lead and Project Manager immediately

#### Acceptance Criteria for Handoffs
- [ ] All release gate criteria documented and verified
- [ ] Release notes reviewed and approved by Product Owner
- [ ] Rollback plan tested and documented
- [ ] Stakeholder notification list confirmed
- [ ] QA sign-off received
