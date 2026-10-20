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

## Engineering Managers

### Role Summary
Engineering Managers turn strategy into delivery by aligning engineering capacity, technical execution, and team health with project goals. They act as the operational bridge between Product, Project Management, and engineering teams.

### Responsibilities
- Manage team capacity, sprint planning, and workload balancing
- Coordinate technical dependencies and team-level execution risk
- Support engineering health, delivery quality, and continuous improvement
- Partner with Product and PM to translate priorities into actionable work for developers
- Help resolve cross-team delivery issues while maintaining focus on scope and quality

### How they interact with existing roles
- With Developers: provide coaching, prioritization support, and technical resource alignment
- With Product Managers: clarify feasibility, trade-offs, and sequencing of work
- With Project Managers: coordinate execution milestones, blockers, and staffing decisions
- With Stakeholders: communicate engineering readiness and delivery risks without over-committing the team

### Goals
- Deliver predictable execution for engineering work
- Improve team throughput and shared accountability
- Reduce friction between roadmap planning and implementation

---

## Security / Compliance Lead

### Role Summary
The Security / Compliance Lead ensures that project work follows security, privacy, and policy requirements throughout planning, implementation, and release.

### Responsibilities
- Review projects for security, privacy, and compliance requirements
- Identify controls, approvals, and review gates needed for delivery
- Partner with engineering and PM to mitigate delivery risks related to security concerns
- Support incident readiness, vulnerability triage, and compliance reporting

### How they interact with existing roles
- With Developers: review technical designs, secure coding practices, and remediation plans
- With Product Managers: assess risk trade-offs and help prioritize secure-by-default decisions
- With Project Managers: align review gates, compliance checkpoints, and escalation paths
- With Stakeholders: communicate policy obligations and risk posture when needed

### Goals
- Reduce preventable security and compliance risk
- Embed security considerations early in the project lifecycle
- Maintain confidence in safe, compliant delivery

---

## UX Researcher / Design Partner

### Role Summary
UX Researcher / Design Partner focuses on user needs, usability, and experience quality so product decisions are grounded in customer evidence and feedback.

### Responsibilities
- Gather user insights and validate assumptions through research and testing
- Define usability goals and accessibility considerations
- Collaborate with Product and engineering on solution design and iteration
- Help translate feedback into clear experience requirements and acceptance criteria

### How they interact with existing roles
- With Product Managers: validate opportunity areas, user value, and solution direction
- With Developers: clarify interaction requirements and usability constraints
- With Project Managers: align research milestones and stakeholder expectations
- With Stakeholders: communicate user needs and impact on customer experience

### Goals
- Improve product usability and customer satisfaction
- Ensure decisions are informed by evidence, not opinion alone
- Reduce rework caused by unclear experience requirements

---

## Data / Analytics Lead

### Role Summary
The Data / Analytics Lead defines the metrics and measurement strategy needed to understand product performance, adoption, and business outcomes.

### Responsibilities
- Define success metrics, dashboards, and instrumentation requirements
- Help interpret usage, quality, and performance data for decision-making
- Partner with Product, PM, and stakeholders on measurable outcomes
- Identify gaps in reporting and propose follow-up analysis

### How they interact with existing roles
- With Product Managers: translate business goals into measurable outcomes and KPI tracking
- With Developers: define instrumentation needs and data quality expectations
- With Project Managers: connect progress and release outcomes to reporting cadence
- With Stakeholders: share evidence of value, risk, and performance trends

### Goals
- Make outcomes measurable and visible
- Support evidence-based decision-making
- Improve accountability for adoption and impact

---

## Release Manager / Deployment Lead

### Role Summary
The Release Manager / Deployment Lead coordinates deployment readiness, release timing, and rollback preparation to reduce operational risk.

### Responsibilities
- Coordinate release windows, staging validation, and production readiness checks
- Align release communications with stakeholder and support teams
- Support rollback planning and post-deploy verification
- Maintain readiness for launch, recovery, and incident communication

### How they interact with existing roles
- With Developers: validate release readiness, deployment risks, and rollback quality
- With Project Managers: align milestones, dependencies, and communications
- With Product Managers: ensure business launch readiness and message consistency
- With Stakeholders: communicate scope, timing, and impact of releases

### Goals
- Lower deployment risk and release-related disruption
- Improve predictability and confidence in shipping changes
- Ensure a clear plan for rollback or mitigation when needed

---

## Customer Success / Support Liaison

### Role Summary
The Customer Success / Support Liaison connects delivery teams with the customer-facing reality of adoption, bugs, and operational friction.

### Responsibilities
- Capture customer feedback, escalation patterns, and recurring support issues
- Identify product quality issues that may require prioritization or follow-up
- Help translate customer pain points into backlog items or improvement requests
- Support post-release monitoring and stakeholder communication

### How they interact with existing roles
- With Product Managers: provide evidence from customer conversations and support data
- With Developers: surface user pain points and prioritize bug or usability follow-up
- With Project Managers: highlight risks, dependencies, and communication needs
- With Stakeholders: provide customer sentiment and operational impact summaries

### Goals
- Improve customer confidence and retention
- Reduce friction between delivery work and real-world customer experience
- Ensure customer feedback influences planning and iteration

---

## Architecture Owner

### Role Summary
The Architecture Owner guides technical direction, design consistency, and system-level trade-offs so projects remain maintainable and aligned with broader platform needs.

### Responsibilities
- Review architectural decisions and technical trade-offs
- Define standards for integration patterns, scalability, and maintainability
- Identify cross-system risks and dependency concerns early
- Support governance for platform, data, and infrastructure decisions

### How they interact with existing roles
- With Developers: guide design choices, technical constraints, and solution trade-offs
- With Product Managers: help assess feasibility and sequencing of roadmap initiatives
- With Project Managers: surface architecture dependencies and delivery risks
- With Stakeholders: explain technical implications of strategic priorities and platform choices

### Goals
- Preserve architectural integrity as the product grows
- Balance delivery speed with long-term maintainability
- Reduce technical debt and avoid avoidable integration complexity

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These additional roles help teams document accountability, communication flows, and cross-functional ownership more clearly in project work.

























































































































































































































































































































a