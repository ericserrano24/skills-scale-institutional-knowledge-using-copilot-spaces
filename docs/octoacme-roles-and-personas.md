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

## Technical Lead

### Role Summary
Technical Leads guide architecture, implementation quality, and technical decision-making across a project. They serve as the bridge between product intent and engineering execution.

### Responsibilities
- Define technical direction and architectural guardrails for the project
- Review implementation decisions for maintainability, scalability, and quality
- Support developers with technical guidance, trade-off analysis, and problem solving
- Partner with Product and Project Managers to assess feasibility and sequencing
- Flag technical debt, dependencies, and risks early

### Goals
- Deliver a robust and maintainable solution
- Keep engineering work aligned with business priorities and constraints
- Reduce rework by clarifying technical decisions before implementation expands

### Typical Communication
- Architecture discussions and design review sessions
- Technical risk reviews with PM and leadership
- Coordination with developers on implementation patterns and standards

### Interaction with Existing Roles
- Works closely with Developers to align implementation decisions with architecture and quality standards
- Supports Product Managers by translating business goals into feasible technical plans
- Coordinates with Project Managers on milestones, dependencies, and risk tracking
- Collaborates with QA Lead on testability and release readiness criteria

---

## Security / Compliance Lead

### Role Summary
Security and Compliance Leads protect the project from operational and regulatory risk by defining security expectations, verifying controls, and supporting safe delivery.

### Responsibilities
- Review project work for security risks, compliance requirements, and data-handling concerns
- Define security controls, validation steps, and remediation expectations
- Coordinate with engineering and stakeholders on secure design and incident response readiness
- Maintain awareness of policy, legal, or compliance obligations relevant to the project

### Goals
- Reduce security and compliance risk without slowing product delivery unnecessarily
- Ensure the project meets required control expectations and governance standards
- Improve confidence in production readiness and incident preparedness

### Typical Communication
- Security reviews, compliance checkpoints, and policy discussions
- Risk briefings with PM and executive stakeholders
- Coordination with Release Manager on deployment and rollback safeguards

### Interaction with Existing Roles
- Works with Developers to validate secure coding practices and sensitive data handling
- Advises Product and Project Managers on risk trade-offs, scope implications, and escalation paths
- Collaborates with QA Lead on security validation and release criteria
- Supports Technical Lead on secure architecture and dependency management

---

## QA Lead

### Role Summary
QA Leads define quality expectations, validate acceptance criteria, and ensure the project is ready for release with confidence.

### Responsibilities
- Define test strategy, quality gates, and release-readiness criteria
- Coordinate manual and automated testing across features and workflows
- Help prioritize defects and validate fixes against acceptance criteria
- Partner with engineering and product stakeholders on quality trade-offs

### Goals
- Catch issues early and reduce defect escape to production
- Improve confidence in product quality and user experience
- Support predictable and low-risk delivery milestones

### Typical Communication
- Test planning and triage meetings
- Defect review and acceptance validation with product and engineering
- Release readiness updates to PM and stakeholders

### Interaction with Existing Roles
- Works with Developers on test coverage, bug triage, and regression prevention
- Aligns with Product Managers on user acceptance and measurable quality outcomes
- Coordinates with Project Managers on release timing and QA dependencies
- Partners with Technical Lead to validate architecture-related quality concerns

---

## Business Analyst / Stakeholder Liaison

### Role Summary
Business Analysts and Stakeholder Liaisons connect business needs, stakeholder input, and delivery teams so requirements remain clear, prioritized, and actionable.

### Responsibilities
- Translate business goals into clear requirements and decision-ready summaries
- Capture stakeholder feedback, dependencies, and approval needs
- Clarify scope, assumptions, and trade-offs between teams
- Support prioritization and communication around upcoming change

### Goals
- Improve requirement clarity and stakeholder alignment
- Reduce misunderstanding between business needs and delivery execution
- Support better decision-making with clearer evidence and context

### Typical Communication
- Requirement workshops and stakeholder interviews
- Status updates for business and leadership audiences
- Alignment sessions with PM, Product, and delivery teams

### Interaction with Existing Roles
- Works closely with Product Managers to shape problem statements and feature details
- Supports Project Managers by clarifying dependencies, stakeholder needs, and decision owners
- Helps Developers and QA teams interpret requirements with examples and acceptance context
- Keeps communication consistent across business stakeholders and delivery teams

---

## Release Manager / Delivery Coordinator

### Role Summary
Release Managers coordinate deployment readiness, communication, and operational execution so releases happen smoothly and with clear accountability.

### Responsibilities
- Prepare release plans, sequencing, and communication milestones
- Verify readiness across code, testing, documentation, and stakeholder approval
- Coordinate deployment timing, rollback readiness, and post-release verification
- Communicate changes and operational impacts to support teams and stakeholders

### Goals
- Reduce release risk and shorten recovery time when issues arise
- Maintain confidence in production readiness and communication quality
- Support smooth delivery across complex or multi-team initiatives

### Typical Communication
- Release readiness reviews and deployment checklists
- Stakeholder notices, launch updates, and rollback coordination
- Follow-up syncs after release with PM, support, and leadership

### Interaction with Existing Roles
- Coordinates with Project Managers on schedule, dependencies, and decision checkpoints
- Works with Developers and QA Lead on release criteria and deployment confidence
- Partner with Security / Compliance Lead on risk and rollback safeguards
- Communicates product impact with stakeholders and Customer Success partners

---

## Customer Success / Enablement Partner

### Role Summary
Customer Success and Enablement partners connect delivery work to user adoption, support readiness, and stakeholder experience after launch.

### Responsibilities
- Prepare support and enablement materials for new or updated capabilities
- Gather customer feedback and relay adoption or usability issues to the team
- Support stakeholder education, rollout planning, and communication readiness
- Help identify friction in adoption and post-launch experience

### Goals
- Improve customer confidence and adoption of delivered solutions
- Ensure support teams and users are prepared for change
- Close feedback loops between product delivery and real-world usage

### Typical Communication
- User feedback summaries and enablement planning discussions
- Stakeholder updates on rollout readiness and support status
- Collaboration with Product and Release teams around launch readiness

### Interaction with Existing Roles
- Works with Product Managers to validate that delivered value meets customer needs
- Supports Project Managers and Release Managers with communication plans and readiness checks
- Brings customer realities back to Developers and QA for follow-up improvements
- Coordinates with stakeholders to align on adoption, training, and change management needs

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These expanded roles help teams model realistic cross-functional accountability across delivery, product, quality, security, and stakeholder communication.

