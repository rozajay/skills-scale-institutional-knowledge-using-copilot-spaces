# OctoAcme — Cross-functional Collaboration & Handoff Checklist

## Purpose
Provide a repeatable checklist for ensuring smooth collaboration and handoffs between roles at key transition points in the project lifecycle. Reduces friction, prevents dropped work, and keeps all parties aligned.

Use this alongside the [RACI Matrix](octoacme-raci-matrix.md) and [Roles & Personas](octoacme-roles-and-personas.md).

---

## Phase 1: Initiation Handoffs

### PM → BA / UX
- [ ] Project One-pager shared and reviewed with BA and UX Designer
- [ ] BA briefed on business goals, success metrics, and known constraints
- [ ] UX Designer briefed on known user needs or existing research findings
- [ ] Initial stakeholder list reviewed with BA for completeness

### BA / UX → PdM
- [ ] Initial requirements gaps or open questions documented
- [ ] UX research needs or design assumptions flagged
- [ ] Stakeholder interviews or discovery workshops scheduled if needed

---

## Phase 2: Planning Handoffs

### PdM + BA → Developers
- [ ] User stories reviewed for clarity and testability before sprint planning
- [ ] Acceptance criteria are complete, unambiguous, and agreed upon
- [ ] Technical dependencies or blockers identified and flagged to PM

### UX → Developers
- [ ] Design files or prototypes shared and linked in the relevant ticket
- [ ] Key interaction patterns and edge cases annotated in designs
- [ ] Design review session held before development begins

### QA Lead → All
- [ ] Test plan drafted and reviewed by PM and Developers
- [ ] Definition of Done updated to include relevant quality gates
- [ ] Automated test coverage expectations documented

### SM → Team
- [ ] Sprint ceremonies scheduled and team availability confirmed
- [ ] Sprint goal agreed upon by PdM and Developers
- [ ] Velocity and capacity considerations communicated to PM

---

## Phase 3: Execution Handoffs

### Developer → QA Lead
- [ ] Feature branch ready for QA review (link included in ticket)
- [ ] Build deployed to test environment and basic smoke check passed
- [ ] Developer available for questions during QA testing
- [ ] Known limitations or deferred work noted in the ticket

### QA Lead → Developer (Bug Cycle)
- [ ] Bug report includes steps to reproduce, environment, and severity rating
- [ ] Bugs linked back to the originating user story or feature ticket
- [ ] Critical bugs escalated immediately with PM informed

### BA → Developer (Mid-sprint Clarification)
- [ ] Clarification requests logged in the issue or ticket (not verbally only)
- [ ] Any scope changes routed through PdM for approval before implementation

### SM → PM (Blocker Escalation)
- [ ] Blockers unresolved after 24 hours escalated to PM with context
- [ ] Impediment log updated with status and resolution notes

---

## Phase 4: Release Handoffs

### QA Lead → PM (Release Readiness)
- [ ] All P1/P2 bugs resolved or have accepted mitigation plans
- [ ] Release test report completed and shared with PM
- [ ] Regression suite passed (or exceptions documented)

### PM → Support Lead (Pre-release)
- [ ] Support Lead notified of release scope and expected user impact
- [ ] Release notes reviewed by Support Lead for accuracy and completeness
- [ ] Support FAQ or runbook updated if applicable
- [ ] Post-release escalation contacts confirmed

### PM → Stakeholders (Release Announcement)
- [ ] Release announcement drafted and reviewed
- [ ] Distribution list confirmed (internal and external where applicable)
- [ ] Rollback plan referenced if the release carries elevated risk

---

## Phase 5: Retrospective Handoffs

### SM → Team (Retro Facilitation)
- [ ] Retrospective format and agenda shared with the team in advance
- [ ] Previous action items reviewed at the start of the session
- [ ] Action items from this retro captured with owners and due dates

### PM → All (Action Item Follow-up)
- [ ] Retro action items added to the project backlog or issue tracker
- [ ] Owners notified directly of assigned items
- [ ] Action item status reviewed in the next weekly PM sync

---

## General Collaboration Reminders
- Always link to relevant docs, tickets, or design files when handing off work—avoid relying on verbal communication alone.
- Escalate blockers early; use the escalation paths defined in [Risk Management & Communication](octoacme-risks-and-communication.md).
- For role ownership questions, refer to the [RACI Matrix](octoacme-raci-matrix.md).
- For role definitions, refer to [Roles & Personas](octoacme-roles-and-personas.md).
