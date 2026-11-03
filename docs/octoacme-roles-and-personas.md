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

## Engineering / Technical Leads

### Role Summary
Engineering or Technical Leads guide technical direction and coordinate implementation across the delivery team. They make technical trade-offs visible without replacing the ownership of individual developers or product decisions.

### Responsibilities
- Guide architecture and technical design within agreed product scope
- Coordinate implementation across developers and surface technical dependencies
- Identify technical risks and propose mitigation options
- Support estimation and help keep technical work aligned with acceptance criteria
- Coordinate with QA/Testing on testability and technical quality

### Goals
- Deliver maintainable solutions that meet product and quality needs
- Make technical decisions and risks clear to the team
- Reduce avoidable integration issues and rework

### Typical Communication
- Technical design discussions and code reviews
- Planning and dependency discussions with developers and the Project Manager
- Scope and trade-off discussions with the Product Manager

### Collaboration with Existing Roles
- Works with the Product Manager to assess technical trade-offs against user outcomes and scope.
- Works with the Project Manager to identify dependencies, effort, and schedule risks.
- Guides Developers on implementation choices and coordinates with QA/Testing to ensure the solution can be verified.

---

## UX / Product Designers

### Role Summary
UX or Product Designers translate user needs into coherent, usable, and accessible experiences, and validate design decisions with users and stakeholders.

### Responsibilities
- Research user needs and map key journeys
- Create and validate interaction, visual, and accessibility designs
- Identify usability risks and clarify design requirements
- Collaborate on acceptance criteria for user-facing behavior

### Goals
- Deliver intuitive and accessible experiences
- Validate assumptions early and reduce usability rework
- Keep product decisions grounded in user needs

### Typical Communication
- Research findings, prototypes, and design reviews
- Design handoffs and implementation discussions
- Product planning and acceptance-criteria reviews

### Collaboration with Existing Roles
- Partners with the Product Manager to connect user research and design choices to product outcomes and priorities.
- Works with Developers and the Engineering / Technical Lead to make designs feasible and resolve implementation questions.
- Works with QA/Testing to ensure usability and accessibility expectations are included in validation.
- Shares research and design risks with the Project Manager when they affect scope, dependencies, or milestones.

---

## Data / Analytics Leads

### Role Summary
Data or Analytics Leads define how project outcomes will be measured and help teams collect and interpret reliable evidence.

### Responsibilities
- Translate success metrics into measurement and instrumentation requirements
- Advise on data quality, privacy-aware collection, and analysis methods
- Establish baselines and reporting for agreed outcome measures
- Interpret results and communicate limitations or emerging insights

### Goals
- Make project outcomes measurable and decision-useful
- Provide trustworthy evidence for iteration and prioritization
- Identify measurement gaps before release

### Typical Communication
- Metric definitions and analytics plans
- Instrumentation requirements with Developers
- Outcome reports and recommendations with product and project leads

### Collaboration with Existing Roles
- Works with the Product Manager to define success measures and use evidence to inform prioritization.
- Coordinates with Developers and the Engineering / Technical Lead to implement and validate instrumentation.
- Works with the Project Manager to include measurement dependencies and reporting milestones in the plan.

---

## Security / Privacy Leads

### Role Summary
Security or Privacy Leads advise teams on security and privacy requirements, help assess risks, and coordinate appropriate review and escalation.

### Responsibilities
- Identify applicable security and privacy requirements and review relevant designs
- Assess risks and recommend mitigations or additional validation
- Help define security and privacy acceptance criteria
- Coordinate escalation through the established incident and security processes

### Goals
- Address security and privacy risks early in delivery
- Ensure controls and data practices are reviewed and verifiable
- Make risk decisions and escalation paths clear

### Typical Communication
- Risk reviews and design consultations
- Requirements and findings shared with Developers and QA/Testing
- Escalations and status updates through established project channels

### Collaboration with Existing Roles
- Advises Developers and the Engineering / Technical Lead on secure designs and mitigations, and QA/Testing on relevant verification.
- Works with the Product Manager to understand user and product impacts, and with the Project Manager to record risks, owners, and escalation needs.
- Follows the security incident runbook for security incidents rather than replacing its escalation process.

---

## Operations / Service Owners

### Role Summary
Operations or Service Owners are accountable for the operational readiness and ongoing health of a service, including monitoring, support handoff, and incident ownership.

### Responsibilities
- Define operational readiness requirements, including monitoring and alerting
- Review deployment, rollback, and service support plans
- Coordinate handoff and clarify post-release ownership
- Identify operational risks and preparedness gaps before release

### Goals
- Operate reliable services and detect issues quickly
- Ensure teams are prepared to support changes after release
- Reduce release risk through clear readiness and ownership

### Typical Communication
- Readiness reviews and deployment coordination
- Monitoring, support, and incident procedures
- Operational risks and handoff expectations with project teams

### Collaboration with Existing Roles
- Works with Developers and the Engineering / Technical Lead on service design, observability, and operational requirements.
- Coordinates with QA/Testing on release verification and with the Project Manager on readiness checkpoints, dependencies, and communications.
- Works with the Product Manager to understand service impact and customer priorities.

---

## Customer Support / Enablement Representatives

### Role Summary
Customer Support or Enablement Representatives prepare customer-facing teams and materials for changes, and bring customer issues and feedback into project decisions.

### Responsibilities
- Identify support, training, and documentation needs for a change
- Prepare support teams with release information and troubleshooting guidance
- Surface recurring customer issues and feedback to the project team
- Help assess customer impact and readiness for launch

### Goals
- Enable accurate, timely customer support
- Reduce customer confusion during and after releases
- Ensure customer feedback informs product improvements

### Typical Communication
- Release briefings and support documentation
- Customer feedback summaries and issue trends
- Coordination with Product Managers and Project Managers on launch readiness

### Collaboration with Existing Roles
- Shares customer needs and feedback with the Product Manager to inform priorities and product decisions.
- Coordinates with the Project Manager on release timing, stakeholder communications, and readiness milestones.
- Works with Developers and QA/Testing to clarify customer-impacting issues and validate support guidance.

---

## Applying These Roles
- Assign roles according to project size and context; one person may hold multiple roles.
- Keep each responsibility explicitly owned, even when roles are combined or a specialist is consulted as needed.
- Validate role assignments and decision boundaries with stakeholders during initiation and planning.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
