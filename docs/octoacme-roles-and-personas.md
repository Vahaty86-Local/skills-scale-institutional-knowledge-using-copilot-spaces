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

## Release Manager

### Role Summary
Release Managers coordinate the people, plans, and readiness checks required to deliver a release safely and consistently.

### Responsibilities
- Schedule releases and coordinate deployment windows
- Confirm that acceptance criteria, CI, security scans, release notes, and rollback plans are complete
- Coordinate staging and production verification with engineering and QA
- Communicate release status, changes, and operational impacts to stakeholders and support teams
- Drive post-deployment verification and coordinate rollback or incident escalation when needed

### Goals
- Reduce deployment risk and release uncertainty
- Deliver releases predictably with clear communications
- Improve release repeatability and operational readiness

### Typical Communication
- Release planning and readiness reviews with Project Managers, Developers, QA, and Support/Operations
- Release announcements and status updates for Stakeholders
- Go/no-go decisions, deployment coordination, and rollback updates

### Interactions with existing roles
- Works with **Project Managers** to align release timing, dependencies, and risk mitigation with the project plan.
- Works with **Developers** to confirm that code is merged, deployable, documented, and observable.
- Works with **Product Managers** to confirm scope and communicate notable changes or trade-offs.
- Works with **QA/Testing** to complete smoke and acceptance verification before deployment.
- Works with **Support/Operations** on rollout, rollback, support readiness, and incident handling.

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects provide technical direction, design guidance, and architecture oversight for delivered solutions.

### Responsibilities
- Define technical approaches and implementation guardrails
- Review architecture, integration points, and major design trade-offs
- Identify technical dependencies, scalability concerns, and risk
- Establish code quality, maintainability, and reliability expectations
- Support estimation and planning with technical context

### Goals
- Create coherent, maintainable, and scalable implementations
- Make technical trade-offs explicit and aligned with product priorities
- Reduce integration and production risk

### Typical Communication
- Design reviews and technical planning sessions
- Architecture and decision records
- Sprint planning and code review participation

### Interactions with existing roles
- Works with **Developers** to provide implementation direction and support design and code reviews.
- Works with **Product Managers** to explain feasibility, trade-offs, sequencing, and technical constraints.
- Works with **Project Managers** to identify cross-team dependencies and inform estimates and risks.
- Works with **Release Managers** to assess deployment complexity and backward compatibility.
- Works with **Security Leads** to integrate security requirements into architecture and implementation.

---

## UX / Design Lead

### Role Summary
UX and Design Leads represent users in planning and delivery by shaping useful, usable, and accessible experiences.

### Responsibilities
- Lead user research and translate findings into design direction
- Create interaction designs, prototypes, and accessibility requirements
- Validate usability and the clarity of user journeys
- Maintain design patterns and consistency across features
- Provide feedback against acceptance criteria and implemented experiences

### Goals
- Improve usability, accessibility, and customer value
- Reduce avoidable rework through early validation
- Ensure product decisions reflect real user needs

### Typical Communication
- Discovery sessions and usability reviews
- Design critiques and product specifications
- Demos and feedback sessions with delivery teams and stakeholders

### Interactions with existing roles
- Works with **Product Managers** to turn customer needs and success metrics into prioritized experience requirements.
- Works with **Developers** to communicate interaction constraints and review implemented designs.
- Works with **QA/Testing** to define usability, accessibility, and experience acceptance checks.
- Works with **Project Managers** to identify design dependencies and incorporate research or review milestones in plans.
- Works with **Stakeholders** to validate direction and communicate user research findings.

---

## Security Lead

### Role Summary
Security Leads establish security requirements and help teams identify, assess, and remediate risks throughout the project lifecycle.

### Responsibilities
- Define security requirements, threat models, and review priorities
- Advise on secure design and implementation practices
- Coordinate security scans and remediation
- Assess security incidents and escalation needs
- Maintain security documentation and lessons learned

### Goals
- Reduce security exposure across delivered features
- Embed security reviews into normal delivery workflows
- Improve the team's ability to respond to security incidents

### Typical Communication
- Threat modeling and security reviews
- Security risk updates and remediation plans
- Incident triage and escalation coordination

### Interactions with existing roles
- Works with **Technical Leads / Architects** to integrate controls into system design and architecture decisions.
- Works with **Developers** to define secure implementation requirements and support remediation.
- Works with **QA/Testing** to clarify security test coverage and verify fixes.
- Works with **Project Managers** to record security risks, ownership, and escalation needs.
- Works with **Release Managers** to confirm required security checks are complete before release.

---

## Support / Operations Lead

### Role Summary
Support and Operations Leads prepare the team and customer-facing organization for production use, ongoing operations, and incident response.

### Responsibilities
- Assess operational readiness and support requirements
- Maintain runbooks, on-call readiness, escalation paths, and known-issue documentation
- Coordinate support training and communications for upcoming releases
- Monitor operational health and lead or support incident triage
- Capture operational feedback and recurring issues for backlog or mitigation work

### Goals
- Improve production readiness and supportability
- Minimize incident impact and recovery time
- Ensure customer-facing teams can operate and support releases effectively

### Typical Communication
- Operational readiness reviews
- Support briefings and release notes
- Incident triage, status updates, and post-incident reviews

### Interactions with existing roles
- Works with **Release Managers** to verify rollout, rollback, monitoring, and support procedures.
- Works with **Developers** to define observability, diagnostics, and maintainable runbooks.
- Works with **Technical Leads / Architects** to assess operational dependencies and failure modes.
- Works with **Project Managers** to escalate operational risks and ensure support milestones are included in plans.
- Works with **Stakeholders** to communicate operational impacts and incident status.

---

## Data / Analytics Lead

### Role Summary
Data and Analytics Leads define how project outcomes are measured, collected, validated, and interpreted.

### Responsibilities
- Develop measurement plans and success metric definitions
- Define telemetry, event, dashboard, and reporting requirements
- Validate data quality and instrumentation
- Analyze experiments or releases and communicate findings
- Recommend metric refinements based on evidence

### Goals
- Ensure decisions are based on reliable and understandable evidence
- Improve traceability from delivered features to outcomes
- Detect adoption, quality, and performance issues early

### Typical Communication
- Metric planning and data reviews
- Dashboard demonstrations and experiment reports
- Feedback on instrumentation, data quality, and interpretation

### Interactions with existing roles
- Works with **Product Managers** to define success metrics, experiments, and outcome hypotheses.
- Works with **Developers** to specify telemetry implementation and data-quality requirements.
- Works with **QA/Testing** to validate events and reporting behavior.
- Works with **Project Managers** to surface measurement dependencies and ensure reporting milestones are planned.
- Works with **Stakeholders** to explain evidence, trends, and the implications of results.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
