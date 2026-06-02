# OctoAcme — Role Interaction Checklist

This document provides checklists for key cross-functional interactions between roles to ensure smooth collaboration and accountability.

---

## Developer & QA Lead Collaboration

### Pre-Feature Development
- [ ] QA Lead reviews feature requirements and acceptance criteria
- [ ] Developer and QA Lead discuss test strategy and coverage needs
- [ ] Test environment requirements identified and communicated to DevOps
- [ ] Test data requirements documented

### During Development
- [ ] Developer writes unit tests and maintains test coverage (≥80% for new code)
- [ ] Developer adds logging and debugging capabilities for QA verification
- [ ] Developer communicates test coverage status in PR description
- [ ] QA Lead reviews code for testability in PR comments

### Pre-Release
- [ ] Developer ensures all acceptance criteria are met
- [ ] Developer provides QA with test artifacts and documentation
- [ ] QA Lead executes test plan and documents results
- [ ] Developer and QA collaborate on defect resolution
- [ ] QA Lead provides sign-off on quality readiness

---

## Product Manager & UX Designer Collaboration

### Discovery Phase
- [ ] Product Manager defines user problem statement and success metrics
- [ ] UX Designer conducts user research to validate assumptions
- [ ] UX Designer presents research findings to Product Manager
- [ ] Product Manager and UX Designer align on user personas and use cases

### Design Phase
- [ ] UX Designer creates wireframes/prototypes based on requirements
- [ ] Product Manager provides feedback on design solutions
- [ ] UX Designer conducts usability testing with stakeholders
- [ ] Findings from testing incorporated into design iterations
- [ ] Product Manager approves final design direction

### Handoff to Development
- [ ] UX Designer prepares design specifications and asset package
- [ ] Product Manager and UX Designer conduct developer handoff meeting
- [ ] Developers ask clarifying questions on implementation
- [ ] Timeline agreed for design support during development

---

## Project Manager & DevOps Engineer Collaboration

### Release Planning
- [ ] Project Manager identifies release timeline and milestones
- [ ] DevOps Engineer assesses deployment readiness and infrastructure needs
- [ ] Project Manager and DevOps coordinate on deployment window
- [ ] DevOps prepares deployment checklist and runbook

### Pre-Deployment
- [ ] Project Manager confirms all acceptance criteria met
- [ ] DevOps Engineer verifies CI/CD pipeline passing
- [ ] DevOps confirms staging environment stable
- [ ] Project Manager communicates deployment schedule to stakeholders

### Deployment & Monitoring
- [ ] DevOps executes deployment with Project Manager monitoring
- [ ] DevOps performs post-deployment health checks
- [ ] Project Manager monitors user feedback and support channels
- [ ] DevOps alerts Project Manager to any issues immediately
- [ ] Project Manager coordinates communication if rollback needed

---

## Product Manager & Project Manager Collaboration

### Project Initiation
- [ ] Product Manager provides problem statement and success metrics
- [ ] Project Manager assesses scope and timeline feasibility
- [ ] Product Manager and Project Manager align on stakeholders and dependencies
- [ ] Project Manager creates project plan based on Product Manager's roadmap

### Weekly Sync
- [ ] Product Manager updates on business priorities and customer feedback
- [ ] Project Manager reports on schedule, risks, and resource status
- [ ] Product Manager and Project Manager discuss scope adjustments if needed
- [ ] Escalations flagged for steering committee if required

### Release Execution
- [ ] Product Manager confirms feature is production-ready
- [ ] Project Manager coordinates final release activities
- [ ] Product Manager prepares go-to-market communications
- [ ] Project Manager ensures all stakeholders notified

---

## Developer & UX Designer Collaboration

### Design Handoff
- [ ] UX Designer provides design specifications and component documentation
- [ ] Developer asks clarifying questions on implementation details
- [ ] UX Designer explains design rationale and user intent
- [ ] Timeline established for design support during implementation

### Implementation Support
- [ ] Developer implements designs according to specifications
- [ ] Developer shares implementation screenshots/videos with UX Designer
- [ ] UX Designer reviews implementation for visual/interaction correctness
- [ ] UX Designer provides feedback for any needed adjustments

### QA & Launch
- [ ] UX Designer and QA Lead review visual design accuracy
- [ ] Developer and UX Designer discuss responsive design across devices
- [ ] UX Designer validates accessibility implementation
- [ ] UX Designer approves for release

---

## QA Lead & DevOps Engineer Collaboration

### Test Environment Setup
- [ ] QA Lead defines test environment requirements
- [ ] DevOps Engineer provisions test environments
- [ ] QA Lead verifies test environment stability and parity with production
- [ ] DevOps provides test data provisioning assistance

### Testing & Deployment
- [ ] QA Lead executes smoke tests in staging environment
- [ ] DevOps validates deployment readiness in staging
- [ ] QA Lead provides go/no-go on testing
- [ ] DevOps executes production deployment
- [ ] QA Lead monitors post-deployment metrics for issues

### Incident Response
- [ ] QA Lead monitors production for user-reported issues
- [ ] DevOps Engineer alerts QA to any system issues
- [ ] QA Lead and DevOps collaborate on root cause analysis
- [ ] QA Lead determines if rollback needed

---

## Project Sponsor & Project Manager Collaboration

### Monthly Review
- [ ] Project Manager prepares project health report
- [ ] Project Manager presents status, risks, and blockers to Sponsor
- [ ] Project Sponsor provides executive support and removes blockers
- [ ] Project Sponsor approves any major scope or timeline changes

### Escalation
- [ ] Project Manager identifies blockers requiring executive intervention
- [ ] Project Manager presents issue to Project Sponsor
- [ ] Project Sponsor leverages influence to resolve blocker
- [ ] Project Manager follows up on resolution

### Stakeholder Communication
- [ ] Project Sponsor champions project importance internally
- [ ] Project Manager coordinates communications through Sponsor
- [ ] Project Sponsor participates in key stakeholder briefings
- [ ] Project Sponsor provides executive perspective on strategic alignment

---

## All Roles — Communication Protocols

### Daily Standup
- [ ] All team members attend (15 min max)
- [ ] Each person shares: Yesterday's progress, today's plan, blockers
- [ ] Blockers discussed and owners assigned
- [ ] Project Manager captures action items

### Weekly Sync (PM + PdM)
- [ ] Status update (progress, risks, metrics)
- [ ] Backlog prioritization review
- [ ] Scope or timeline adjustments
- [ ] Upcoming dependencies and stakeholder needs
- [ ] Action items assigned with owners and due dates

### Bi-Weekly Delivery Sync
- [ ] All team members present
- [ ] Demo of completed work
- [ ] Review of metrics and progress
- [ ] Risk register update
- [ ] Next steps and priorities

### Monthly Stakeholder Update
- [ ] Project Manager leads presentation
- [ ] Highlight key accomplishments
- [ ] Roadmap for next month
- [ ] Risks and mitigation plans
- [ ] Decisions needed from stakeholders
