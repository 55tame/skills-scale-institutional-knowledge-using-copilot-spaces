# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Role model and adaptability

Project teams do not always have a separate person for every role described here. In practice, one person may serve multiple personas depending on project size, risk, maturity, and operating model. The personas below are intended as a flexible guide for identifying responsibilities, decision rights, communication needs, and handoffs.

Use the roles that are relevant to the project context. A small, low-risk effort may need only a project manager, product owner, and technical lead, while a larger transformation may require explicit executive sponsorship, business analysis, change management, operations readiness, and security/compliance involvement.

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

## Executive Sponsor / Steering Committee Representative

### Purpose
Provide strategic sponsorship and decision authority for the broader initiative. This role ensures organizational support, resourcing, and alignment with strategic priorities.

### Responsibilities and decision boundaries
- Set strategic direction and business outcome expectations
- Secure sponsorship, funding, and cross-functional support
- Resolve escalated issues that exceed the authority of the project manager or delivery team
- Confirm priorities when there are trade-offs between scope, schedule, and value
- Sponsor governance reviews and major milestone decisions

### Key deliverables
- Executive sponsorship briefings and escalation path
- Approved scope, investment, or priority adjustments
- Governance decisions for cross-team dependencies or policy issues

### Interactions and handoffs
- Works with the project manager to review status, risks, and readiness
- Receives escalations from the project manager when decisions require senior sponsorship
- Aligns with the product owner or business owner on strategic outcomes and expected value
- Coordinates with technical, operations, and compliance stakeholders when enterprise concerns must be addressed

### When this persona is needed
Use this role when the project has multiple stakeholders, strategic funding implications, or issues that require senior-level decision making beyond day-to-day delivery management.

---

## Business Owner / Product Owner

### Purpose
Own the business outcomes, prioritization decisions, and acceptance of delivered value. This role bridges stakeholder needs and delivery execution.

### Responsibilities and decision boundaries
- Define desired outcomes, business value, and prioritization
- Clarify requirements, acceptance criteria, and scope trade-offs
- Make decisions on value, sequencing, and product readiness
- Accept delivered work when it meets the agreed outcomes and criteria
- Partner with the project manager to balance scope, schedule, budget, and quality

### Key deliverables
- Prioritized backlog or decision log
- Business requirements and acceptance criteria
- Outcome validation and release acceptance inputs

### Interactions and handoffs
- Collaborates closely with the project manager on planning, dependency management, and stakeholder communications
- Works with the business analyst or requirements lead to refine needs and traceability
- Coordinates with the delivery team and technical lead to ensure implementation aligns with outcomes
- Provides decision support to the executive sponsor when strategic priorities shift

### When this persona is needed
Use this role whenever business value, prioritization, or requirement clarity are central to delivery. A small project may combine this role with project management or product leadership.

---

## Technical Lead / Solution Architect

### Purpose
Own the technical approach, architecture, and engineering coordination needed to deliver a solution safely and sustainably.

### Responsibilities and decision boundaries
- Define technical direction, architecture constraints, and integration patterns
- Coordinate technical dependencies across engineering, infrastructure, and platform teams
- Review estimates, sequencing, and technical feasibility with the project manager
- Identify risks, design trade-offs, and implementation options
- Partner with security, operations, and implementation contributors on readiness

### Key deliverables
- Solution design and architecture decisions
- Technical dependencies and risk register inputs
- Deployment and implementation readiness guidance

### Interactions and handoffs
- Works with the project manager on estimates, milestones, and technical risk management
- Coordinates with developers and other delivery contributors on implementation decisions
- Handoffs architecture and operational concerns to the operations/service owner before release
- Escalates technical or compliance concerns to the risk/compliance/security representative or executive sponsor when required

### When this persona is needed
Use this role for projects with multiple integrations, platform dependencies, significant design decisions, or technical complexity that require explicit architecture ownership.

---

## Business Analyst / Requirements Lead

### Purpose
Translate stakeholder needs into clear requirements, traceability, and acceptance criteria so the delivery team can build the right thing.

### Responsibilities and decision boundaries
- Elicit and document stakeholder needs and constraints
- Maintain requirements traceability and prioritize clarification questions
- Define acceptance criteria and validation criteria for scope items
- Work with business and technical stakeholders to resolve requirement ambiguity
- Support change impact assessment and requirement governance

### Key deliverables
- Business and functional requirements
- Requirements traceability matrix or equivalent documentation
- Acceptance criteria and stakeholder alignment artifacts

### Interactions and handoffs
- Connects business stakeholders and the product owner to the delivery team
- Helps the project manager confirm scope, assumptions, and dependencies
- Provides the technical lead and developers with clear requirements and examples
- Identifies impacts for change management and operational readiness when adoption or processes are affected

### When this persona is needed
Use this role when the project has complex or changing requirements, multiple stakeholder groups, or a need for clear documentation of business intent and acceptance criteria.

---

## Change Manager / Adoption Lead

### Purpose
Prepare the organization for change by planning communications, training, adoption activities, and stakeholder readiness.

### Responsibilities and decision boundaries
- Assess stakeholder impact and change readiness
- Plan communications, training, and enablement activities
- Coordinate adoption milestones with project delivery activities
- Identify people, process, and policy gaps that could affect success
- Partner with the business owner and project manager to ensure adoption work is included in the plan

### Key deliverables
- Stakeholder impact assessment and communication plan
- Training, adoption, or transition plan
- Readiness checks for operational and user adoption activities

### Interactions and handoffs
- Works with the project manager to sequence change activities with project milestones
- Aligns with the business owner on stakeholder priorities and expected outcomes
- Coordinates with the operations/service owner to prepare support and handoff for ongoing use
- Escalates organizational risks, such as low adoption or stakeholder resistance, to governance or leadership when needed

### When this persona is needed
Use this role for projects that change workflows, tools, roles, or user behaviors, or when implementation success depends on adoption and operational readiness as much as technical delivery.

---

## Operations / Service Owner

### Purpose
Ensure the solution can be supported, monitored, and transitioned successfully into normal operations.

### Responsibilities and decision boundaries
- Define support model, service expectations, and operational readiness requirements
- Validate monitoring, ownership, and reliability expectations before release
- Confirm dependencies for support, handover, and ongoing service management
- Coordinate operational acceptance or readiness checks with the technical lead and project manager

### Key deliverables
- Service handover and support model
- Operational readiness criteria and support ownership plan
- Runbook, monitoring, or support transition guidance

### Interactions and handoffs
- Partners with the technical lead to validate architecture, deployment readiness, and supportability
- Works with the project manager to align release readiness and operational dependencies
- Coordinates with the change manager on communication and training for operational teams
- Confirms business continuity, support ownership, and release readiness before go-live

### When this persona is needed
Use this role for production-facing services, customer-impacting changes, or any initiative requiring a defined support model after launch.

---

## Risk, Compliance, or Security Representative

### Purpose
Provide specialist review and advice on security, compliance, controls, and risk mitigation so the project can meet policy and governance expectations.

### Responsibilities and decision boundaries
- Review risk, controls, and policy impacts relevant to the project
- Advise on required evidence, testing, and approvals
- Raise issues, exceptions, and mitigation actions for governance review
- Support secure design, data handling, and compliance readiness decisions
- Escalate unresolved issues through established governance channels

### Key deliverables
- Security, privacy, or compliance review outcomes
- Risk mitigation actions or exception requests
- Evidence or signoff artifacts required by policy or governance

### Interactions and handoffs
- Coordinates with the technical lead on design, dependencies, and mitigation planning
- Supports the project manager in tracking risks and readiness actions
- Works with the executive sponsor or steering committee if policy, control, or risk decisions require escalation
- Provides input to operations and adoption planning where security or compliance affects support, access, or controls

### When this persona is needed
Use this role for regulated environments, privileged data, public or customer-facing systems, and projects with significant operational or policy risk.

---

## Role interaction matrix

| Persona | Primary responsibility | Key collaboration points | Typical decision or handoff |
| --- | --- | --- | --- |
| Executive Sponsor / Steering Committee Representative | Strategic direction and escalation authority | Project manager, business owner, senior leadership | Approves major trade-offs, escalations, and governance decisions |
| Business Owner / Product Owner | Outcomes, prioritization, and acceptance | Project manager, business analyst, delivery team | Prioritizes scope and accepts delivered value |
| Technical Lead / Solution Architect | Architecture, technical feasibility, and engineering coordination | Developers, project manager, operations, security | Owns technical approach and dependency resolution |
| Business Analyst / Requirements Lead | Requirements clarity and traceability | Product owner, project manager, delivery team | Clarifies scope and acceptance criteria |
| Change Manager / Adoption Lead | Communications, stakeholder readiness, and training | Business owner, project manager, operations | Ensures adoption and readiness are integrated into the plan |
| Operations / Service Owner | Supportability, readiness, and service handover | Technical lead, project manager, change manager | Confirms operational readiness before release |
| Risk, Compliance, or Security Representative | Controls, risk, and specialist review | Technical lead, project manager, executive sponsor | Escalates policy or security issues for decision |
| Project Manager | Coordination, planning, and governance support | All roles | Keeps schedule, risk, and communication aligned |
| Developers | Delivery of solution components | Product owner, technical lead, project manager | Implements and validates work against requirements |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When project context is complex, include only the personas that are relevant to the initiative and clarify who holds multiple roles.

---
