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
Engineering Managers support engineering teams through people leadership, capacity planning, and delivery health oversight. They help teams work effectively while balancing technical sustainability with product commitments.

### Responsibilities
- Plan team capacity and support staffing decisions
- Coach Developers and support their professional growth
- Monitor delivery health and help resolve team-level blockers
- Coordinate cross-team dependencies and raise resource constraints
- Partner with technical leads to sustain engineering quality

### Goals
- Build a healthy, effective engineering team
- Make delivery commitments realistic and sustainable
- Reduce blockers and improve collaboration across teams

### Typical Communication
- Regular one-to-ones and team health discussions
- Capacity and dependency reviews with Project Managers
- Scope and delivery trade-off discussions with Product Managers

### Interaction with Existing Roles
- **Developers:** Coach and support the team, clarify capacity, and help remove blockers without taking over implementation decisions.
- **Product Managers:** Align team capacity and delivery health with product priorities; discuss scope trade-offs when commitments are at risk.
- **Project Managers:** Coordinate staffing constraints, dependencies, and schedule risks while keeping delivery plans realistic.
- **QA/Testing:** Partner on sustainable quality practices and address team capacity needs for testing.
- **Stakeholders:** Communicate team-level delivery risks and capacity constraints through the appropriate project channels.

---

## Technical Leads / Solution Architects

### Role Summary
Technical Leads and Solution Architects guide technical design and architecture. They help translate product needs into secure, reliable, and maintainable solutions while enabling Developers to make informed implementation decisions.

### Responsibilities
- Define and communicate architecture and technical standards
- Evaluate design options and document significant decisions
- Identify technical risks and non-functional requirements
- Facilitate design reviews and resolve technical questions
- Coordinate technical dependencies across teams

### Goals
- Deliver solutions that meet functional and non-functional needs
- Keep systems secure, scalable, reliable, and maintainable
- Enable consistent implementation without unnecessary constraints

### Typical Communication
- Technical design documents and architecture decision records
- Design reviews and implementation discussions with Developers
- Risk and dependency updates with Product Managers and Project Managers

### Interaction with Existing Roles
- **Developers:** Collaborate on designs, clarify standards, and support implementation while leaving day-to-day coding ownership with Developers.
- **Product Managers:** Translate product requirements into technical options, constraints, and trade-offs.
- **Project Managers:** Share estimates, architectural risks, and dependencies that affect sequencing or delivery plans.
- **QA/Testing:** Define testability needs and collaborate on coverage for system behavior and non-functional requirements.
- **Stakeholders:** Explain technical implications and options in terms that support informed decisions.

---

## DevOps / Platform Engineers

### Role Summary
DevOps and Platform Engineers provide the tools and operational practices that help teams build, test, deploy, and operate software reliably.

### Responsibilities
- Maintain CI/CD pipelines and development environments
- Automate deployment and routine operational tasks
- Establish observability, reliability, and rollback practices
- Define release guardrails and support operational readiness
- Identify platform risks and improve developer workflows

### Goals
- Make delivery pipelines reliable and repeatable
- Reduce deployment risk and time to recovery
- Provide secure, dependable platforms that enable product teams

### Typical Communication
- Pipeline, environment, and operational documentation
- Release readiness coordination and incident channels
- Platform status and risk updates with engineering and project leads

### Interaction with Existing Roles
- **Developers:** Provide platform guidance, tooling, and deployment support; coordinate on application requirements and operational ownership.
- **Product Managers:** Explain platform constraints and operational considerations that may affect launch plans.
- **Project Managers:** Coordinate deployment windows, readiness milestones, and operational risks.
- **QA/Testing:** Ensure test environments and pipelines support reliable validation before release.
- **Stakeholders:** Share service health and release-impact information through agreed operational communications.

---

## UX Designers / UX Researchers

### Role Summary
UX Designers and UX Researchers help teams understand user needs and create clear, accessible, and usable product experiences.

### Responsibilities
- Research user needs, behaviors, and pain points
- Design user journeys, interactions, and interface specifications
- Validate concepts and designs through usability research
- Provide accessibility guidance and design assets
- Share research findings to inform product decisions

### Goals
- Make products useful, intuitive, and accessible
- Reduce usability risks before implementation
- Ground design decisions in user evidence

### Typical Communication
- Research plans, findings, and usability reports
- Design prototypes and specifications
- Design reviews and planning discussions with product and engineering teams

### Interaction with Existing Roles
- **Developers:** Clarify design intent, discuss implementation constraints, and review the resulting experience.
- **Product Managers:** Frame user problems, inform prioritization with research, and align designs with product outcomes.
- **Project Managers:** Identify research and design dependencies, milestones, and review needs during planning.
- **QA/Testing:** Collaborate on usability and accessibility checks as part of validation.
- **Stakeholders:** Present user evidence and design options to support decisions without substituting opinion for research.

---

## Customer Support / Success Representatives

### Role Summary
Customer Support and Success Representatives connect project teams with customers' questions, feedback, and experiences before and after release.

### Responsibilities
- Share recurring customer questions, needs, and pain points
- Report product feedback and post-release issue patterns
- Help prepare support materials and customer communications
- Coordinate customer-impact information during incidents
- Contribute customer context to retrospectives and improvement work

### Goals
- Help customers adopt and use products successfully
- Ensure teams act on relevant customer feedback
- Improve readiness for customer-facing releases and incidents

### Typical Communication
- Customer feedback summaries and support trends
- Release notes, knowledge-base content, and support briefings
- Incident updates and post-release review discussions

### Interaction with Existing Roles
- **Developers:** Provide reproducible customer issue details and help validate that fixes address reported problems.
- **Product Managers:** Share customer needs and recurring feedback to inform priorities and product decisions.
- **Project Managers:** Coordinate customer-facing milestones, communications, and incident or release updates.
- **QA/Testing:** Share customer scenarios and help ensure important workflows are represented in validation.
- **Stakeholders:** Relay customer impact and readiness needs through agreed communication channels.

---

## Security / Compliance Representatives

### Role Summary
Security and Compliance Representatives help teams identify security and regulatory obligations and incorporate appropriate safeguards throughout delivery.

### Responsibilities
- Identify applicable security, privacy, and compliance requirements
- Support risk assessments and threat analysis
- Review designs and controls at appropriate project checkpoints
- Advise on evidence, remediation, and escalation needs
- Help teams understand security or compliance-related release conditions

### Goals
- Reduce security and compliance risks early
- Protect customer and organizational information
- Make required controls and evidence clear to delivery teams

### Typical Communication
- Risk assessments, review findings, and remediation tracking
- Security and compliance requirements in project documentation
- Escalations and release readiness discussions when needed

### Interaction with Existing Roles
- **Developers:** Explain secure implementation requirements and review proposed mitigations.
- **Product Managers:** Clarify compliance-driven scope, customer commitments, and trade-offs.
- **Project Managers:** Track security risks, review dependencies, and communicate required checkpoints or escalations.
- **QA/Testing:** Coordinate security and compliance validation, including evidence needed for release.
- **Stakeholders:** Communicate material risks, obligations, and decisions to the appropriate owners.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
