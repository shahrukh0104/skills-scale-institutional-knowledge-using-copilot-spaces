# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.
Roles describe accountabilities, not required job titles. Depending on project size and context, one person may take on multiple roles, provided ownership and decision boundaries remain clear.

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

## Executive Sponsors

### Role Summary
Executive Sponsors provide senior-level direction and organizational support. They are accountable for keeping the project aligned with strategic objectives and resolving decisions or blockers that are outside the project team's authority.

### Responsibilities
- Confirm strategic alignment and expected business outcomes
- Secure organizational support, resources, and timely decisions
- Resolve escalations and cross-team blockers beyond the Project Manager's authority
- Review progress and intervene when scope, funding, or outcomes need executive direction

### Goals
- Ensure the project remains aligned with organizational priorities
- Enable the team to make progress by resolving high-level constraints
- Make clear and timely decisions when trade-offs exceed delegated authority

### Typical Communication
- Project milestone and outcome reviews
- Escalations, decision requests, and resource discussions
- Briefings from the Project Manager and Product Manager

### Interactions with Other Roles
- Align with the Product Manager on strategic outcomes and priority changes while leaving product backlog decisions with the Product Manager.
- Receive delivery risks and escalation requests from the Project Manager, then resolve or route issues that require executive authority.
- Support Developers and technical leads by clearing organizational blockers without directing day-to-day implementation.

---

## Business Analysts / Requirements Leads

### Role Summary
Business Analysts clarify stakeholder needs and translate them into traceable requirements that the team can plan, build, and validate. This role supports shared understanding of scope without taking ownership of product prioritization or project delivery coordination.

### Responsibilities
- Elicit and document stakeholder needs, workflows, and constraints
- Clarify requirements, assumptions, and acceptance criteria with stakeholders
- Trace requirements to intended outcomes and identify gaps or conflicts
- Assess proposed scope changes and communicate their requirements impact

### Goals
- Give the team a shared, testable understanding of what is needed and why
- Reduce avoidable rework caused by ambiguous or conflicting requirements
- Keep requirements aligned with stakeholder needs and agreed outcomes

### Typical Communication
- Stakeholder interviews and requirements workshops
- Refined requirements and acceptance criteria
- Clarifications and change-impact notes shared with the delivery team

### Interactions with Other Roles
- Work with the Product Manager to clarify user needs and prepare backlog items; the Product Manager remains accountable for product vision and prioritization.
- Work with the Project Manager to assess scope changes, dependencies, and schedule impacts; the Project Manager remains accountable for the project plan.
- Collaborate with Developers and Quality / Test Leads to resolve requirement questions and ensure acceptance criteria can be implemented and verified.

---

## Technical Leads / Architects

### Role Summary
Technical Leads / Architects guide technical design and help the team make maintainable implementation choices. They provide technical direction and visibility into engineering risks without replacing the Developers' responsibility for building and maintaining the software.

### Responsibilities
- Guide architecture and technical design decisions
- Help decompose work and identify technical dependencies
- Surface technical risks, constraints, and trade-offs early
- Support consistent engineering practices through design and code reviews

### Goals
- Enable reliable, secure, and maintainable solutions
- Make technical decisions transparent and appropriately documented
- Reduce delivery risk from unresolved technical dependencies or constraints

### Typical Communication
- Technical designs and architecture decision records
- Design reviews and technical planning discussions
- Risk and dependency updates to the delivery team

### Interactions with Other Roles
- Collaborate with Developers on design, implementation, estimates, and technical reviews; Developers retain responsibility for delivering their assigned work.
- Advise the Project Manager about technical dependencies and delivery risks so plans and escalations reflect engineering realities.
- Work with the Product Manager to explain technical trade-offs that affect product outcomes, scope, or sequencing.
- Coordinate with Quality / Test Leads on testability and technical approaches to quality.

---

## Quality / Test Leads

### Role Summary
Quality / Test Leads coordinate the approach to verifying that deliverables meet agreed requirements and quality expectations. They make quality status and release risks visible; quality remains a shared responsibility across the team.

### Responsibilities
- Define a risk-based test approach and coordinate quality activities
- Ensure requirements and acceptance criteria have clear verification approaches
- Track defects, communicate quality trends, and raise unresolved risks
- Provide evidence and recommendations for release readiness

### Goals
- Detect important defects and quality risks early
- Make release readiness decisions informed by clear evidence
- Build quality into delivery rather than relying only on end-stage testing

### Typical Communication
- Test plans, results, and quality status
- Defect reports and risk-based test coverage updates
- Release-readiness assessments and quality gate discussions

### Interactions with Other Roles
- Work with Developers on testability, automated checks, and defect resolution; Developers share responsibility for quality and testing their work.
- Partner with the Business Analyst / Requirements Lead to ensure acceptance criteria are verifiable.
- Inform the Project Manager of quality risks that affect timelines or release plans, and the Product Manager of defects or gaps that affect product outcomes.
- Provide evidence and risks to the relevant decision-makers; the Quality / Test Lead advises on readiness but does not unilaterally change product scope or project commitments.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

