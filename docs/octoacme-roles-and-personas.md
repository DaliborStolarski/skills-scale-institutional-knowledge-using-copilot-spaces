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

## QA / Testing Lead

### Role Summary
QA / Testing Leads ensure product quality by defining test strategy, validating acceptance criteria, and identifying defects early enough to reduce delivery risk.

### Responsibilities
- Define and maintain the testing strategy and quality gates
- Coordinate automated and manual test execution across sprint or release scope
- Validate user stories against acceptance criteria and business intent
- Escalate quality risks or release blockers to PMs, Product Leads, and stakeholders
- Partner with Developers on testability, defect triage, and regression prevention

### Goals
- Reduce escaped defects and production issues
- Improve confidence in release readiness
- Align testing efforts with customer impact and risk

### Typical Communication
- Test plans, defect triage, and release readiness reviews
- Daily or sprint-level quality checkpoints with engineering and PMs
- Status updates for risk, defects, and regression coverage

### Interaction with Existing Roles
- Works closely with Developers to review quality risks and validate fixes.
- Provides Product Managers and Project Managers with readiness signals and release confidence.
- Helps the Project Manager maintain timelines by identifying testing bottlenecks early.

---

## Technical Architect

### Role Summary
Technical Architects guide the long-term technical direction of a project and ensure that product decisions are feasible, scalable, and aligned with platform standards.

### Responsibilities
- Review architectural trade-offs, platform choices, and technical dependencies
- Define design guardrails for maintainability, scalability, and security
- Identify technical risks and mitigation strategies early in the lifecycle
- Support major design decisions and integration planning across teams
- Mentor Developers and help resolve complex technical blockers

### Goals
- Keep the solution aligned with architectural standards and business constraints
- Reduce rework caused by poor design decisions
- Support sustainable delivery at scale

### Typical Communication
- Architecture reviews, design discussions, and technical decision records
- Dependency tracking with PMs and cross-functional stakeholders
- Alignment with Product and Engineering leads on feasibility and trade-offs

### Interaction with Existing Roles
- Works with Developers to shape design decisions and technical quality.
- Advises Product Managers on feasibility, sequencing, and risk trade-offs.
- Supports Project Managers by surfacing dependencies, delivery risks, and escalation needs.

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, funding, strategic alignment, and executive decision-making support for project priorities and milestones.

### Responsibilities
- Define business priorities, success outcomes, and strategic intent
- Approve major milestones, scope changes, and business trade-offs
- Sponsor cross-team decisions and help remove organizational blockers
- Communicate project value and progress to broader leadership or business groups
- Provide input on risk tolerance, timeline expectations, and priority shifts

### Goals
- Ensure the project stays aligned with business goals
- Maintain executive awareness of delivery outcomes and risks
- Support a clear path for decision-making and investment

### Typical Communication
- Steering meetings, milestone reviews, and status updates
- Decision logs, business approvals, and escalation communications
- Sponsor briefings on progress, risks, and strategic impact

### Interaction with Existing Roles
- Aligns with Product Managers on priority, business value, and outcomes.
- Relies on Project Managers for status reporting and risk communication.
- Provides direction to the team without replacing implementation accountability owned by Developers and PMs.

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters or Agile Coaches help teams work effectively, remove process friction, and improve the quality of delivery rituals and collaboration.

### Responsibilities
- Facilitate sprint ceremonies such as standups, planning, retrospectives, and reviews
- Help the team identify and resolve blockers, process issues, and work friction
- Coach teams on agile practices, continuous improvement, and healthy collaboration
- Track team health indicators and highlight opportunities to improve flow and predictability
- Support alignment between Product, Engineering, and Project Management across the delivery cycle

### Goals
- Improve team effectiveness and delivery consistency
- Reduce process waste and friction in the work system
- Support a sustainable and psychologically safe working environment

### Typical Communication
- Retrospectives, team coaching sessions, and facilitator-led planning meetings
- Weekly team health updates and process improvement follow-ups
- Coordination with Project Managers around team capacity and delivery patterns

### Interaction with Existing Roles
- Supports Developers by improving team rituals and reducing blockers.
- Partners with Product Managers to help manage backlog flow and refinement quality.
- Works with Project Managers to improve predictability and communication rhythms without taking ownership of delivery decisions.

---

## DevOps / Release Engineer

### Role Summary
DevOps or Release Engineers ensure that software can be built, deployed, monitored, and recovered reliably in production and lower environments.

### Responsibilities
- Maintain CI/CD pipelines, deployment automation, and release readiness checks
- Support environments, infrastructure provisioning, and operational stability
- Coordinate pre-deploy and post-deploy validation activities
- Document runbooks, rollback procedures, and incident response support
- Partner with developers and PMs to reduce release risk and improve deployment confidence

### Goals
- Increase release reliability and deployment velocity
- Improve operational visibility and recovery readiness
- Reduce handoff friction between engineering and operations

### Typical Communication
- Deployment windows, release readiness reviews, and operational status updates
- Incident communication and rollback coordination
- Coordination with QA and PMs ahead of release milestones

### Interaction with Existing Roles
- Works with Developers to ensure delivery is deployable and observable.
- Supports Project Managers and Stakeholders with clear release readiness and rollback information.
- Collaborates with QA to confirm smoke tests, validation criteria, and release gates.

---

## Customer Success / Support Representative

### Role Summary
Customer Success and Support representatives connect the team to real user needs, service quality, and post-deployment customer experience.

### Responsibilities
- Share customer feedback, pain points, and usage patterns with the product and delivery team
- Validate whether released features meet customer expectations and support needs
- Identify service, usability, and workflow issues that require product or process changes
- Coordinate communication between customer-facing teams and engineering stakeholders
- Help assess adoption, feature impact, and customer readiness before or after launch

### Goals
- Improve customer satisfaction and retention
- Ensure the product supports real operational needs
- Close the feedback loop between delivery and customer experience

### Typical Communication
- Customer feedback reviews, support input sessions, and release follow-up check-ins
- Escalation of critical issues or usage challenges to Product or Engineering leads
- Cross-functional updates between support teams and delivery stakeholders

### Interaction with Existing Roles
- Provides Product Managers with customer insights and prioritization input.
- Helps Project Managers identify operational risk, rollout concerns, and stakeholder communication needs.
- Supports Developers by surfacing edge cases, usability gaps, and real-world scenarios for testing and improvement.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these roles create a more complete picture of accountability across product, delivery, quality, operations, and stakeholder alignment.

