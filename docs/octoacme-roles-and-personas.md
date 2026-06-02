# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

### Key Interactions
- **With QA Lead**: Share test requirements, review test plans, participate in QA reviews
- **With UX Designer**: Implement design specifications, provide technical feasibility feedback
- **With DevOps Engineer**: Coordinate deployments, debug production issues, optimize CI/CD pipelines

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

### Key Interactions
- **With UX Designer**: Collaborate on user research, define feature requirements, validate prototypes
- **With QA Lead**: Define acceptance criteria, review test plans, validate quality gates
- **With Project Sponsor**: Present roadmap and business impact, seek approval for scope changes

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

### Key Interactions
- **With DevOps Engineer**: Coordinate release schedules, manage deployment timelines
- **With QA Lead**: Schedule testing phases, track quality metrics, manage test resource allocation
- **With Project Sponsor**: Escalate risks and blockers, request executive decisions, report project health

---

## QA Lead

### Role Summary
QA Leads oversee quality assurance activities, ensure comprehensive testing, and validate that deliverables meet acceptance criteria and quality standards before release.

### Responsibilities
- Develop and maintain test plans aligned with project requirements
- Coordinate test execution (unit, integration, end-to-end, security testing)
- Validate acceptance criteria are met before features move to production
- Identify, track, and manage quality issues and defects
- Collaborate with developers on test coverage and automation
- Create and maintain test automation frameworks
- Report quality metrics and testing progress to stakeholders

### Goals
- Ensure high-quality deliverables reaching production
- Reduce production defects and post-release issues
- Improve testing efficiency through automation and best practices
- Maintain stakeholder confidence in product quality

### Typical Communication
- Daily communication with developers on test status
- Weekly QA reports and quality metrics to Project Manager
- Test plan reviews with Product Manager and stakeholders
- Incident post-mortems and quality improvement discussions

### Key Interactions
- **With Developers**: Collaborate on test requirements, review code for testability, participate in code reviews
- **With Product Manager**: Clarify acceptance criteria, validate feature completeness, assess quality readiness
- **With DevOps Engineer**: Coordinate test environment setup, manage test data, execute smoke tests in CI/CD
- **With Project Manager**: Provide testing timelines, escalate quality risks, track test progress

---

## UX Designer

### Role Summary
UX Designers research user needs, design intuitive interfaces and workflows, and validate usability. They bridge customer needs with technical implementation.

### Responsibilities
- Conduct user research and gather user feedback
- Create wireframes, prototypes, and design specifications
- Validate design solutions through user testing
- Define user flows and information architecture
- Collaborate with developers on design implementation
- Iterate on designs based on feedback and usability metrics
- Maintain design systems and accessibility standards

### Goals
- Deliver intuitive, user-centered product experiences
- Reduce user friction and support tickets
- Improve user satisfaction and adoption metrics
- Ensure accessible design for all users

### Typical Communication
- Design review sessions with stakeholders and developers
- Weekly design sync with Product Manager
- User research findings and usability test reports
- Design specifications and hand-off documentation to developers

### Key Interactions
- **With Product Manager**: Validate user requirements, present design solutions, iterate based on business priorities
- **With Developers**: Provide design specifications, address technical feasibility questions, collaborate on implementation
- **With QA Lead**: Define usability test cases, review UI acceptance criteria, validate visual/interaction correctness
- **With Stakeholders**: Present design concepts, gather feedback, communicate design decisions and rationale

---

## DevOps Engineer

### Role Summary
DevOps Engineers design and maintain CI/CD pipelines, manage deployment environments, and ensure system reliability, performance, and security. They enable rapid, safe delivery.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage development, staging, and production environments
- Implement and monitor security scanning and vulnerability checks
- Coordinate and execute production deployments
- Monitor system performance, uptime, and reliability metrics
- Manage infrastructure, databases, and deployment configurations
- Support incident response and rollback procedures
- Document deployment procedures and runbooks

### Goals
- Enable fast, reliable, and safe deployments
- Minimize deployment failures and production incidents
- Improve system reliability and performance
- Reduce manual, error-prone deployment activities

### Typical Communication
- Release coordination with Project Manager and Developers
- CI/CD pipeline status and deployment readiness reports
- Performance and reliability metrics to Project Manager
- Incident response coordination during production issues

### Key Interactions
- **With Developers**: Manage CI/CD pipeline feedback, troubleshoot deployment issues, optimize build times
- **With QA Lead**: Provide test environments, manage test data, execute smoke tests post-deployment
- **With Project Manager**: Coordinate release schedules, communicate deployment readiness, report infrastructure risks
- **With Security/Compliance**: Implement security scanning, manage access controls, coordinate security patches

---

## Project Sponsor

### Role Summary
Project Sponsors provide executive-level support and oversight. They remove high-level blockers, approve major decisions, and ensure strategic alignment with organizational goals.

### Responsibilities
- Champion the project and secure executive support
- Approve major scope, timeline, and budget changes
- Remove high-level blockers and organizational barriers
- Ensure project aligns with strategic business objectives
- Escalate critical issues requiring executive decision-making
- Provide stakeholder communication and support
- Conduct periodic project reviews and gate approvals

### Goals
- Ensure project success and business value realization
- Maintain strategic alignment and organizational buy-in
- Enable quick resolution of executive-level blockers
- Drive accountability and clear ownership

### Typical Communication
- Monthly or milestone-based project status reviews
- Executive steering committee meetings
- Escalation communication for critical decisions
- Post-project retrospectives and lessons learned

### Key Interactions
- **With Project Manager**: Receive status reports, escalate blockers, approve critical decisions
- **With Product Manager**: Review business value and strategic alignment, approve roadmap changes
- **With Stakeholders**: Communicate project importance, gather stakeholder buy-in, manage organizational dependencies
- **With Executives**: Report on project health, business impact, and strategic value

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand the interconnected nature of roles and the importance of clear communication and collaboration.
