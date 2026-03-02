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

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They elicit, analyze, and document requirements to ensure development work delivers measurable business value.

### Responsibilities
- Elicit and document requirements from stakeholders and product leads
- Translate business needs into clear user stories, acceptance criteria, and feature specs
- Validate proposed solutions against business objectives
- Facilitate requirements workshops and review sessions
- Maintain traceability between business goals and delivered features

### Goals
- Ensure development work is grounded in validated business requirements
- Reduce rework caused by unclear or misunderstood requirements
- Improve alignment between stakeholder expectations and delivered outcomes

### Typical Communication
- Requirements workshops and review sessions with stakeholders
- User story refinement sessions with Product Managers and Developers
- Written requirements documents and acceptance criteria

### Typical Interactions
- **Product Managers**: Collaborates to define and prioritize features; translates product vision into detailed requirements
- **Developers**: Provides clarification on requirements during sprint planning and execution; reviews implemented features against acceptance criteria
- **Project Managers**: Coordinates requirements status and flags gaps that may impact scope or timeline
- **UX Designers**: Partners on user flows and usability requirements to ensure feature designs meet business needs

---

## UX Designer

### Role Summary
UX Designers advocate for users by creating intuitive, accessible experiences. They define user flows, produce wireframes and prototypes, and partner with product and engineering to validate usability throughout delivery.

### Responsibilities
- Design user flows, wireframes, and interactive prototypes
- Conduct usability testing and incorporate feedback into designs
- Advocate for accessibility and inclusive design standards
- Partner with Product Managers to refine customer needs and feature priorities
- Maintain design system or component guidelines for consistency

### Goals
- Deliver user experiences that are intuitive, accessible, and aligned with product goals
- Reduce UX-related rework by involving design early in the lifecycle
- Ensure consistent visual and interaction patterns across the product

### Typical Communication
- Design reviews and critique sessions with Product Managers and Developers
- Prototypes and annotated wireframes shared via design tools
- Usability testing reports and findings summaries

### Typical Interactions
- **Product Managers**: Collaborates to define user needs, journey maps, and feature priorities
- **Developers**: Works closely during implementation to clarify design intent and resolve feasibility constraints
- **Business Analysts**: Partners on user flow requirements to align usability with business objectives
- **QA Lead**: Coordinates on accessibility and UI acceptance criteria for test coverage

---

## Scrum Master

### Role Summary
Scrum Masters facilitate Agile ceremonies, coach the team on iterative delivery practices, and actively remove impediments. They foster a culture of continuous improvement and help the team maintain a sustainable pace.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify and remove blockers, escalating to the Project Manager when needed
- Coach team members on Agile/Scrum best practices
- Track sprint health metrics (velocity, burndown) and surface trends
- Support continuous improvement by ensuring retrospective actions are followed up

### Goals
- Maintain a predictable, sustainable team delivery cadence
- Reduce impediments and minimize interruptions to the delivery team
- Embed a culture of reflection and continuous improvement

### Typical Communication
- Daily standup facilitation and async blocker updates
- Sprint ceremony notes and team health summaries
- Retro action item tracking with Project Managers

### Typical Interactions
- **Project Managers**: Shares sprint status and escalates blockers that require external coordination
- **Developers**: Coaches on process adherence and helps unblock technical or organizational impediments
- **Product Managers**: Coordinates backlog readiness and sprint goal alignment
- **QA Lead**: Ensures quality gates are reflected in the Definition of Done and sprint ceremonies

---

## Support Lead

### Role Summary
Support Leads manage post-launch feedback loops, triage incoming bugs and incidents, and ensure customer-facing issues are resolved promptly. They provide field intelligence back to the product and engineering teams.

### Responsibilities
- Triage and prioritize incoming bug reports and support requests
- Escalate critical incidents to the on-call engineering team
- Maintain communication with affected users or customers during incidents
- Track support trends and synthesize feedback for Product Managers
- Participate in release planning to prepare support documentation and FAQs

### Goals
- Minimize customer impact from post-release issues
- Provide a fast, transparent communication channel between users and internal teams
- Feed actionable product feedback back to Product Managers and Developers

### Typical Communication
- Incident updates and post-mortems with engineering and project leads
- Support trend reports for Product Manager review cycles
- Release notes review and FAQ authoring before major releases

### Typical Interactions
- **Developers**: Escalates reproducible bugs and works with engineering to confirm fix scope and timelines
- **Product Managers**: Shares aggregated feedback trends to inform roadmap prioritization
- **Project Managers**: Provides incident status updates and flags risks to delivery timelines
- **QA Lead**: Coordinates on bug severity classification and regression test coverage

---

## QA Lead

### Role Summary
QA Leads own the test strategy across the project lifecycle. They coordinate manual and automated testing, define acceptance standards, and ensure quality is built in—not bolted on—throughout delivery.

### Responsibilities
- Define and maintain the overall test strategy and test plans
- Coordinate manual and automated test coverage across features
- Validate that features meet acceptance criteria and the Definition of Done
- Maintain the defect tracking process and ensure consistent bug reporting quality
- Report test results and quality signals to stakeholders

### Goals
- Prevent defects from reaching production by embedding quality into the delivery process
- Provide clear, timely quality signals to the team and stakeholders
- Continuously improve test coverage and automation

### Typical Communication
- Test plan and results summaries shared with Project Managers and Developers
- Bug triage sessions with Developers and Support Lead
- Release readiness reports prior to deployment

### Typical Interactions
- **Developers**: Partners on testability requirements and reviews PRs from a quality perspective; coordinates bug fixes
- **Project Managers**: Communicates quality status, test progress, and any release blockers
- **Product Managers**: Confirms acceptance criteria are testable and accurately reflect product intent
- **Support Lead**: Aligns on post-release bug severity and regression priorities
- **UX Designers**: Collaborates on UI and accessibility acceptance criteria

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For a view of ownership across lifecycle phases, see the [RACI Matrix](octoacme-raci-matrix.md).
- For handoff and collaboration guidance between roles, see the [Cross-functional Collaboration Checklist](octoacme-cross-functional-collaboration-checklist.md).

