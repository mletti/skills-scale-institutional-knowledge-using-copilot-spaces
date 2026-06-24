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

## Engineering Manager

### Role Summary
Engineering Managers lead engineering teams, manage capacity and career development, and remove technical and organizational blockers. They ensure the team has the resources, clarity, and support needed to deliver high-quality work.

### Responsibilities
- Plan team staffing, capacity, and resource allocation
- Support career development, performance feedback, and team morale
- Escalate and resolve technical resourcing bottlenecks
- Identify and coordinate cross-team technical dependencies
- Advocate for engineering concerns and best practices in planning

### Goals
- Build and retain a high-performing engineering team
- Ensure sustainable pace and healthy work-life balance
- Reduce technical debt and improve system reliability
- Enable engineers to focus on impactful work

### Typical Communication
- 1-on-1s with engineers and skip-level conversations
- Planning sessions with PM and Product Lead on scope vs. capacity
- Technical risk reviews and escalation to leadership
- Cross-team coordination meetings for integration planning

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers ensure that products are usable, accessible, and delightful. They lead user research, create interaction designs, and advocate for user needs throughout the project lifecycle.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and visual designs
- Review designs for accessibility (WCAG compliance, screen reader support)
- Define UX acceptance criteria and design specs
- Collaborate on design reviews and implementation guidance

### Goals
- Deliver products that are intuitive and accessible to all users
- Reduce support burden and user frustration
- Validate design decisions with evidence
- Build a culture of user-centered design

### Typical Communication
- User research findings and personas shared with PM and Developers
- Design critiques and feedback in planning and PR review
- Accessibility checklists and design system guidance
- Collaboration during planning, implementation, and QA phases

---

## Site Reliability Engineer (SRE) / Platform Engineer

### Role Summary
SREs and Platform Engineers own production reliability, scalability, and operational excellence. They define and implement observability, monitoring, and infrastructure best practices that enable sustainable delivery.

### Responsibilities
- Define non-functional requirements (performance, scalability, availability)
- Design observability, alerting, and runbook strategies
- Conduct production readiness reviews before release
- Maintain CI/CD pipelines and deployment infrastructure
- Coordinate incident response and post-incident reviews

### Goals
- Maximize system uptime and reliability
- Reduce mean time to recovery (MTTR) for incidents
- Enable fast, safe deployments with low risk
- Shift left on operational concerns during planning and development

### Typical Communication
- Non-functional requirements workshops during planning
- Production readiness checklists before releases
- Monitoring dashboards and alerting configuration
- Post-deploy verification and incident communication

---

## Security Lead / AppSec

### Role Summary
Security Leads and AppSec engineers ensure that products are secure by design. They embed security practices into the development lifecycle, from threat modeling to code review to incident response.

### Responsibilities
- Conduct threat modeling and define security requirements
- Review architectural and code changes for security implications
- Coordinate security scanning (SAST, DAST, dependency checks) in CI
- Triage and prioritize security vulnerabilities
- Provide security training and best practices guidance

### Goals
- Prevent security breaches and data loss
- Build a security-aware culture
- Ensure compliance with regulatory and organizational policies
- Reduce time to patch vulnerabilities

### Typical Communication
- Security acceptance criteria and threat models in planning
- Code review comments on high-risk changes
- Vulnerability triage and escalation reports
- Security incident coordination and post-mortems

---

## Data Analyst / Product Analytics

### Role Summary
Data Analysts and Product Analytics professionals measure product impact and inform decision-making. They define success metrics, instrument tracking, and provide insights that guide strategy and execution.

### Responsibilities
- Define measurable success metrics aligned with business goals
- Design event instrumentation and tracking strategies
- Build dashboards and reports for stakeholders and teams
- Validate data quality and interpretation
- Analyze post-release impact and provide optimization recommendations

### Goals
- Enable data-driven decision making across the organization
- Accurately measure product adoption, engagement, and impact
- Identify optimization opportunities and areas for improvement
- Support both tactical (sprint) and strategic (roadmap) decisions

### Typical Communication
- Success metrics definition during project initiation and planning
- Measurement plans and instrumentation guidance before launch
- Weekly or post-release dashboards and insights
- Collaborative analysis of failures and learning opportunities

---

## Release Engineer / CI-CD Owner

### Role Summary
Release Engineers manage the automation and orchestration of software releases. They own the build pipeline, deployment processes, versioning conventions, and rollback procedures that make releases safe, repeatable, and auditable.

### Responsibilities
- Build and maintain CI/CD pipelines (build, test, security scan, deploy)
- Define versioning and tagging conventions
- Coordinate release windows and deployment scheduling
- Implement rollback and disaster recovery procedures
- Document release checklists and runbooks

### Goals
- Enable fast, low-risk deployments with minimal manual toil
- Reduce deployment failures and downtime
- Provide audit trails and compliance support
- Facilitate knowledge sharing across teams

### Typical Communication
- Release checklists and deployment coordination with PM and SRE
- Runbook documentation and rollback procedure updates
- CI/CD improvements and infrastructure status reports
- Cross-team alignment on release timing and dependencies

---

## Technical Program Manager (TPM) / Program Lead

### Role Summary
Technical Program Managers coordinate work across multiple teams and projects, managing dependencies, timelines, and risks at the program level. They ensure strategic alignment and enable cross-functional collaboration.

### Responsibilities
- Define program scope, goals, and success metrics
- Identify and manage cross-team dependencies and integration points
- Track program-level timeline, milestones, and critical path
- Consolidate and escalate program-level risks and blockers
- Facilitate communication and alignment across teams and leadership

### Goals
- Deliver complex, multi-team initiatives on time and in sync
- Minimize integration issues and rework
- Enable transparent, proactive risk management
- Accelerate decision-making through clear accountability

### Typical Communication
- Program charter and roadmap aligned with leadership
- Cross-team sync meetings and dependency tracking
- Program-level risk registers and escalation reports
- Executive dashboards and quarterly program reviews

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning projects, consider which roles are relevant to your context and adjust responsibilities and communication accordingly.
- Use cross-functional handoffs and interaction patterns to design realistic workflows and training scenarios.
