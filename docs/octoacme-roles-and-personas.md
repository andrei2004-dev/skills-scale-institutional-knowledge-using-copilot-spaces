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

## QA Lead / Quality Assurance Engineer

### Role Summary
QA Leads own quality strategy, define acceptance criteria validation, and ensure products meet quality gates before release. They collaborate with developers, product managers, and stakeholders to define and execute test plans.

### Responsibilities
- Define quality standards and acceptance criteria validation approach
- Create and maintain test plans and test cases
- Execute manual and automated testing across feature acceptance and regression
- Identify quality risks and blockers during execution
- Lead smoke tests and post-deployment verification
- Provide feedback on testability and acceptance criteria clarity

### Goals
- Ensure features meet acceptance criteria before release
- Reduce production defects and customer-impacting issues
- Enable fast, confident deployments through test automation

### Typical Communication
- Sprint planning and backlog refinement
- QA sign-off in PR reviews and code walkthroughs
- Test status updates in daily standups
- Release readiness reports

### Interaction with Other Roles
- **Developers**: Collaborate on test strategy, testability improvements, and acceptance criteria clarification
- **Product Managers**: Validate acceptance criteria and define quality standards aligned with customer expectations
- **Project Managers**: Report on quality metrics and release readiness to inform go/no-go decisions
- **Technical Leads**: Partner on complex test scenarios and automation strategy

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural guidance, evaluate technical trade-offs, and identify risks that impact project success. They ensure code quality, scalability, and alignment with technical standards.

### Responsibilities
- Review technical designs and propose solutions for complex problems
- Identify technical risks and propose mitigations
- Mentor developers on technical best practices
- Oversee code quality standards and design reviews
- Ensure systems are scalable, maintainable, and secure
- Collaborate with product and project teams on technical feasibility

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and prevent architectural bottlenecks
- Build scalable systems that support future growth

### Typical Communication
- Technical design reviews and architecture discussions
- Code review and mentoring feedback
- Risk assessments in planning and weekly syncs
- Technical trade-off discussions with product teams

### Interaction with Other Roles
- **Developers**: Provide architectural direction, code review guidance, and mentoring on technical excellence
- **Product Managers**: Advise on technical feasibility and propose solutions that balance customer needs with technical sustainability
- **Project Managers**: Flag technical risks and blockers that impact timelines and dependencies
- **QA Leads**: Collaborate on testability and automation strategy for complex features

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors provide business vision, priority alignment, and resource authorization. They represent key stakeholder interests and make go/no-go decisions at project gates.

### Responsibilities
- Provide business context and strategic alignment for projects
- Approve resource allocation and timeline commitments
- Make project gate decisions (initiation, planning, release)
- Escalate business-impacting risks and blockers
- Communicate project outcomes to broader organization
- Resolve cross-team dependencies and priority conflicts

### Goals
- Ensure projects deliver measurable business value
- Align delivery with organizational strategy
- Remove barriers to project success

### Typical Communication
- Monthly stakeholder updates
- Project gate reviews and decision points
- Escalation path for critical issues
- Post-release outcome reporting

### Interaction with Other Roles
- **Project Managers**: Receive escalations, approve gate decisions, allocate resources
- **Product Managers**: Align on strategic priorities and business outcomes
- **Development Team**: Communicate project vision and success criteria at project kickoff

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove team blockers, and coach the organization on agile practices. They enable the team to deliver incrementally and continuously improve.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove impediments and blockers that prevent team progress
- Coach team members on agile practices and mindset
- Maintain team velocity and sprint health
- Guide continuous improvement initiatives
- Escalate organizational blockers to appropriate stakeholders

### Goals
- Enable consistent, predictable delivery cadence
- Foster psychological safety and team accountability
- Drive continuous process improvement
- Reduce cycle time from backlog to production

### Typical Communication
- Daily standups and ceremony facilitation
- Retrospective notes and action items
- Coaching conversations and mentoring
- Escalation communication to sponsors

### Interaction with Other Roles
- **Project Managers**: Partner on sprint planning and roadmap communication
- **Developers**: Coach on agile principles and help remove blockers
- **Product Managers**: Facilitate backlog refinement and story readiness
- **All Roles**: Model agile values and encourage transparency and collaboration

---

## DevOps / Release Engineer

### Role Summary
DevOps / Release Engineers design, build, and maintain CI/CD pipelines, deployment infrastructure, and release processes. They enable fast, reliable releases and support production operations.

### Responsibilities
- Design and maintain automated deployment pipelines
- Manage infrastructure, environments, and configuration management
- Implement security scanning and compliance checks in CI/CD
- Execute releases and manage rollback procedures
- Monitor deployment health and post-release verification
- Provide runbooks and support for incident response
- Collaborate on testability and observability improvements

### Goals
- Enable fast, automated, and reliable releases
- Reduce manual effort and human error in deployments
- Maintain infrastructure stability and security
- Support rapid incident response and recovery

### Typical Communication
- Release planning and go/no-go discussions
- Deployment status and incident notifications
- Infrastructure and deployment process documentation
- Post-deployment verification and runbook reviews

### Interaction with Other Roles
- **Project Managers**: Coordinate release windows and deployment timelines
- **QA Leads**: Partner on smoke testing and post-deployment verification
- **Developers**: Support with build pipeline issues and deployment troubleshooting
- **Technical Leads**: Collaborate on infrastructure design and security requirements
- **Product Managers**: Communicate release readiness and rollback capabilities

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference interactions between personas to understand dependencies and communication patterns in real project scenarios.
