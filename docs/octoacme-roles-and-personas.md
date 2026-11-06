# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A person may take on more than one role in a small project, but responsibilities and decision ownership should remain explicit. Teams should adapt these roles to the project's size, domain, and governance needs.

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
- Weekly alignment with Project Managers and engineering leads
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

## Product Owner / Business Owner

### Role Summary
The Product Owner or Business Owner represents the intended business outcomes and ensures the team delivers value. This role may be held by the Product Manager where the organization combines product strategy and day-to-day backlog ownership.

### Responsibilities
- Clarify business needs and define or validate outcome and acceptance criteria
- Order and refine work priorities with the Product Manager and delivery team
- Make timely scope and requirement decisions within delegated authority
- Review completed work and confirm whether it meets agreed acceptance criteria

### Interactions with Existing Roles
- Partners with the Product Manager to align backlog decisions with product vision, customer evidence, and success measures
- Works with the Project Manager to assess scope changes and their schedule, dependency, and risk impacts
- Clarifies requirements for Developers, the Business Analyst, and QA / Test Lead; resolves questions and acceptance decisions
- Consults the Executive Sponsor when a decision exceeds delegated authority or changes strategic commitments

---

## Business Analyst

### Role Summary
The Business Analyst translates stakeholder needs into clear, verifiable requirements and process descriptions. This role helps ensure that the problem and expected outcomes are understood before and during delivery.

### Responsibilities
- Elicit and document business needs, workflows, constraints, and requirements
- Develop user stories, acceptance criteria, and process models with stakeholders
- Trace requirements to planned work and help manage changes to them
- Identify ambiguity, assumptions, and gaps, and facilitate their resolution

### Interactions with Existing Roles
- Works with the Product Manager and Product Owner / Business Owner to understand desired outcomes and refine priorities
- Coordinates with the Project Manager to schedule discovery, track requirements dependencies, and surface scope changes
- Answers Developers' questions and collaborates with the QA / Test Lead to make requirements testable
- Engages affected stakeholders and shares decisions and changes through the Project Manager's communication approach

---

## Technical Lead / Solution Architect

### Role Summary
The Technical Lead or Solution Architect guides the technical design and integration of the solution, ensuring that implementation choices meet agreed requirements and technical standards.

### Responsibilities
- Define or coordinate architecture, technical approach, and integration boundaries
- Identify technical dependencies, constraints, and risks; recommend mitigations
- Guide technical estimates and sequencing, and support design and code reviews
- Ensure relevant quality attributes, such as reliability, maintainability, and security, are considered

### Interactions with Existing Roles
- Works with Developers to decompose work, resolve technical questions, and maintain implementation consistency
- Provides the Project Manager with estimates, dependency information, and early notice of technical risks or changes
- Partners with the Product Manager and Product Owner / Business Owner on feasibility and trade-offs without owning product priority decisions
- Coordinates with the Security / Compliance Lead and Operations / Release Manager on controls, deployment, and operational readiness

---

## QA / Test Lead

### Role Summary
The QA / Test Lead coordinates quality practices and provides evidence about whether the delivered work meets requirements and release expectations. Testing remains a shared responsibility across the team.

### Responsibilities
- Define a risk-based test approach, coverage, and quality checkpoints
- Coordinate test planning, execution, defect triage, and reporting
- Ensure requirements and acceptance criteria can be verified
- Communicate quality risks and readiness evidence; recommend improvements to prevent recurring defects

### Interactions with Existing Roles
- Works with Developers and the Technical Lead to integrate testing into delivery and resolve defects
- Partners with the Business Analyst and Product Owner / Business Owner to clarify expected behavior and acceptance criteria
- Shares test status, defects, and release risks with the Project Manager so plans and stakeholders stay informed
- Coordinates readiness criteria and evidence with the Operations / Release Manager

---

## Security / Compliance Lead

### Role Summary
The Security / Compliance Lead identifies applicable security, privacy, and regulatory obligations and coordinates assurance activities. The role advises and tracks required reviews; formal approval authority remains with the designated governance or control owner.

### Responsibilities
- Identify relevant security, privacy, and compliance requirements early in planning and design
- Advise on controls, threat and privacy risks, and evidence needed for reviews
- Coordinate assessments, track findings and owners, and communicate unresolved issues
- Escalate material risks or missing approvals through established governance channels

### Interactions with Existing Roles
- Advises the Technical Lead and Developers on controls and secure implementation practices
- Works with the Project Manager to plan reviews, track remediation dependencies, and communicate risk or approval status
- Partners with the Product Manager and Product Owner / Business Owner to explain impacts of requirements and risk trade-offs
- Coordinates with the QA / Test Lead and Operations / Release Manager on security testing, release conditions, and operational controls

---

## Operations / Release Manager

### Role Summary
The Operations / Release Manager coordinates deployment and service readiness, including the handoff from project delivery to ongoing operation. In some teams, these responsibilities are shared with service owners or other operations staff.

### Responsibilities
- Plan release activities, deployment dependencies, and operational handoffs
- Confirm monitoring, support ownership, rollback or recovery plans, and runbooks are prepared
- Coordinate release readiness checks and communicate operational constraints
- Capture operational feedback and follow-up actions after deployment

### Interactions with Existing Roles
- Works with the Project Manager to include release milestones, dependencies, and operational handoff in the project plan
- Coordinates with the Technical Lead and Developers on deployment design and with the QA / Test Lead on test and readiness evidence
- Engages the Security / Compliance Lead on required operational controls and approvals
- Confirms service ownership and support arrangements with relevant stakeholders and informs the Product Manager and Product Owner / Business Owner about release constraints or outcomes

---

## Executive Sponsor / Steering Group

### Role Summary
The Executive Sponsor or Steering Group provides strategic direction, secures organizational support, and makes decisions that exceed the project team's delegated authority. A Steering Group is a governance body; the sponsor may represent the project within it.

### Responsibilities
- Confirm strategic alignment, intended business outcomes, and high-level success measures
- Provide sponsorship, resolve escalated cross-team issues, and help address major resource or organizational barriers
- Make or obtain decisions on material changes to funding, scope, priorities, or risk acceptance within governance authority
- Review progress at agreed checkpoints and ensure accountable decision owners are available

### Interactions with Existing Roles
- Receives concise status, risks, options, and decision requests from the Project Manager
- Aligns with the Product Manager and Product Owner / Business Owner on strategic outcomes and material priority or scope decisions
- Enables the Project Manager to coordinate across teams but does not replace the Project Manager's day-to-day delivery coordination
- Consults relevant technical, security, and operations leads when decisions require their expertise; delegates detailed execution to the project team

---

## Role Boundaries and Collaboration

- Product Managers own product vision and value prioritization; Product Owners / Business Owners make or coordinate day-to-day business and acceptance decisions within their authority. These responsibilities may be combined, but the decision owner should be explicit.
- Project Managers coordinate the plan, delivery risks, dependencies, and communication. They facilitate decisions and escalation but do not automatically own product, technical, quality, security, or operational decisions.
- Technical, QA, security, and operations roles provide specialist ownership and evidence in their domains. They should raise material risks early and coordinate dependencies through the Project Manager and relevant decision owners.
- The Executive Sponsor or Steering Group resolves escalations and decisions reserved for governance, not routine delivery details.
- Teams should identify who is accountable for each significant decision and handoff (using RACI or an equivalent when useful). One person may hold multiple roles, but combining roles does not remove the need to make conflicts of interest, approval boundaries, and accountability clear.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
