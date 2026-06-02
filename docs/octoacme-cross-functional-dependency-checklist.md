# OctoAcme — Cross-Functional Dependency Checklist

This checklist helps project managers and team leads identify, manage, and track dependencies between roles, ensuring smooth project execution and timely escalation.

---

## Dependency Discovery Process

### During Project Planning
- [ ] List all features and major work items
- [ ] For each item, identify which roles must contribute
- [ ] Map dependencies between roles and work items
- [ ] Identify external dependencies (other teams, vendors, etc.)
- [ ] Document dependency type (blocks, requires input, etc.)
- [ ] Assign dependency owner (typically Project Manager)

### Dependency Documentation Template
```
Dependency ID: [ID]
Description: [What depends on what]
From Role: [Role providing input/deliverable]
To Role: [Role waiting for input/deliverable]
Delierable: [What is being delivered]
Due Date: [When needed]
Owner: [Who is accountable]
Status: [Not Started / In Progress / On Track / At Risk / Blocked / Complete]
Risk Level: [High / Medium / Low]
Mitigation Plan: [If at risk]
```

---

## Common Cross-Functional Dependencies

### Developer ↔ QA Lead
**Dependency**: Code ready for testing
- [ ] Definition of Done met (unit tests, code review, etc.)
- [ ] Code merged to staging branch
- [ ] Test environment ready
- [ ] QA Lead notified of code readiness
- [ ] Testing timeline established
- [ ] Defect resolution SLA agreed

**Dependency**: QA sign-off for release
- [ ] All acceptance criteria verified
- [ ] No critical/high defects outstanding
- [ ] Performance acceptable
- [ ] QA Lead provides formal sign-off
- [ ] Release notes include QA findings

### Product Manager ↔ UX Designer
**Dependency**: Requirements for design
- [ ] Product requirements documented
- [ ] Success metrics defined
- [ ] User personas provided
- [ ] Design brief completed
- [ ] Timeline and milestones agreed

**Dependency**: Design specifications for development
- [ ] Wireframes and prototypes completed
- [ ] Design specifications documented
- [ ] Assets and design tokens provided
- [ ] Accessibility review completed
- [ ] Developer handoff scheduled

### Project Manager ↔ DevOps Engineer
**Dependency**: Release coordination
- [ ] Release date confirmed with DevOps
- [ ] Infrastructure requirements identified
- [ ] Deployment checklist prepared
- [ ] Rollback plan documented
- [ ] On-call coverage arranged
- [ ] Post-deployment monitoring plan established

### Developer ↔ UX Designer
**Dependency**: Design implementation
- [ ] Design specifications clear and detailed
- [ ] Design assets provided (SVGs, fonts, etc.)
- [ ] Component library available
- [ ] Designer available for questions
- [ ] Implementation timeline agreed

**Dependency**: Visual correctness verification
- [ ] Implementation screenshots shared
- [ ] Visual accuracy review completed
- [ ] Responsive design validated
- [ ] Designer approval obtained

### QA Lead ↔ DevOps Engineer
**Dependency**: Test environment setup
- [ ] Environment requirements defined
- [ ] Test data requirements documented
- [ ] Environment provisioned and verified
- [ ] Database populated with test data
- [ ] Access credentials provided to QA

**Dependency**: Production deployment readiness
- [ ] Smoke tests executed in staging
- [ ] DevOps verifies deployment readiness
- [ ] Post-deployment health checks defined
- [ ] Monitoring and alerts configured
- [ ] Go/no-go decision confirmed

---

## Dependency Status Tracking

### Weekly Dependency Review (Part of Weekly PM + PdM Sync)
- [ ] Review all active dependencies
- [ ] Update status for each dependency
- [ ] Identify any newly at-risk or blocked dependencies
- [ ] Escalate high-risk dependencies
- [ ] Confirm mitigation plans are being executed

### Dependency Status Levels
- **Not Started**: No work has begun
- **In Progress**: Work is underway, on schedule
- **On Track**: No concerns, expected to complete on time
- **At Risk**: Potential delay identified, mitigation plan in place
- **Blocked**: Unable to progress, requires immediate action
- **Complete**: Deliverable provided/received, dependency resolved

### At-Risk or Blocked Dependency Protocol
1. **Immediate**: Notify dependent role and Project Manager
2. **Within 24 hours**: Document issue, impact, and proposed mitigation
3. **Within 48 hours**: Execute mitigation plan or escalate to Project Manager
4. **Weekly**: Review status in project sync until resolved
5. **Resolution**: Close dependency and document learnings

---

## Dependency Management Checklist

### Initial Setup
- [ ] All major dependencies identified
- [ ] Dependency map created and visualized
- [ ] Owners assigned for each dependency
- [ ] Timeline and milestones aligned
- [ ] Communication plan established

### Ongoing Monitoring
- [ ] Dependencies reviewed weekly
- [ ] Status updated in tracking system (Jira, GitHub Projects, etc.)
- [ ] At-risk dependencies escalated immediately
- [ ] Blocked dependencies unblocked within 24 hours
- [ ] New dependencies identified and added as they arise

### Risk Mitigation
- [ ] For each at-risk dependency: document impact if missed
- [ ] Mitigation plan created for high-impact dependencies
- [ ] Contingency plan identified (if dependency cannot be met)
- [ ] Stakeholders informed of risks and plans
- [ ] Progress toward resolution tracked daily

### Resolution & Closure
- [ ] Deliverable provided and verified
- [ ] Dependent team member confirms receipt and quality
- [ ] Dependency marked as "Complete"
- [ ] Any learnings captured for retrospective
- [ ] Similar future dependencies considered in planning

---

## Dependency Communication Template

**Subject**: [Dependency Status] - [Feature/Project Name]

**For Upcoming Dependencies**:
We need [deliverable] from [role] by [date] to support [work]. Please confirm:
- [ ] You can deliver by this date
- [ ] Estimated effort and resources needed
- [ ] Any blockers or concerns

**For At-Risk Dependencies**:
[Dependency] is at risk of missing the [date] deadline due to [reason]. Impact: [what breaks]. Proposed mitigation: [plan]. Please confirm feasibility.

**For Blocked Dependencies**:
[Work] is blocked waiting for [deliverable] from [role]. We need this by [date] to maintain schedule. Can you help unblock?

---

## Dependency Types & Escalation

### Type 1: Blocking Dependency
**Definition**: Work cannot start without deliverable
**Example**: Development can't start until design specs complete
**Escalation**: If 3+ days late → escalate to Product Manager

### Type 2: Input Dependency
**Definition**: Input needed but work can start in parallel
**Example**: Testing can start before all features complete
**Escalation**: If more than 1 week impact → escalate to Project Manager

### Type 3: Information Dependency
**Definition**: Information needed for context or decisions
**Example**: Decisions needed from stakeholder
**Escalation**: If blocking progress → escalate to Project Sponsor

### Type 4: Resource Dependency
**Definition**: Shared resource allocation needed
**Example**: Designer needed for multiple projects
**Escalation**: If conflict → escalate to Project Sponsor

---

## Dependency Retrospective

After project completion, review:
- [ ] Which dependencies were managed well?
- [ ] Which dependencies caused delays or issues?
- [ ] What early warning signs were missed?
- [ ] What processes could improve dependency management?
- [ ] How can we communicate dependencies better?
- [ ] Are there patterns in dependency issues?
- [ ] What preventive measures can we take?
