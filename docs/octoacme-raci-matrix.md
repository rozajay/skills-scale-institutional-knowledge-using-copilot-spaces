# OctoAcme — RACI Matrix

## Purpose
Clarify ownership and participation for key activities and decisions across each phase of the project lifecycle.

## Legend
- **R** = Responsible (performs the work)
- **A** = Accountable (single owner; approves or signs off)
- **C** = Consulted (input required before action)
- **I** = Informed (notified of outcomes)

## Role Abbreviations

| Abbreviation | Role |
|---|---|
| PM | Project Manager |
| PdM | Product Manager |
| Dev | Developer(s) |
| BA | Business Analyst |
| UX | UX Designer |
| SM | Scrum Master |
| SL | Support Lead |
| QA | QA Lead |

For full role definitions, see [Roles & Personas](octoacme-roles-and-personas.md).

---

## Matrix

| Activity / Artifact | PM | PdM | Dev | BA | UX | SM | SL | QA |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Initiation** | | | | | | | | |
| Project One-pager | A/R | C | I | C | I | I | I | I |
| Stakeholder list & communication plan | A/R | C | I | C | I | I | C | I |
| Initial risk list | A/R | C | C | C | I | I | I | I |
| Go/no-go for planning decision | A | R | I | C | I | I | I | I |
| **Planning** | | | | | | | | |
| Requirements elicitation & user stories | C | A | C | R | C | I | C | I |
| Backlog prioritization | C | A | C | R | C | I | C | C |
| UX design & prototypes | I | C | C | C | A/R | I | I | C |
| Test plan & QA approach | C | I | C | I | I | I | I | A/R |
| Definition of Done | C | C | C | I | I | A/R | I | C |
| Release plan & milestones | A/R | C | C | I | I | C | C | C |
| **Execution** | | | | | | | | |
| Sprint ceremonies (planning, standup, review) | C | I | R | I | I | A/R | I | I |
| Feature development | I | I | A/R | C | C | I | I | I |
| QA & acceptance testing | I | C | R | C | C | I | I | A/R |
| Blocker escalation | A/R | C | C | I | I | C | I | I |
| Risk register updates | A/R | C | C | I | I | I | I | C |
| **Release** | | | | | | | | |
| Release go/no-go decision | A | C | C | I | I | I | C | C |
| Release notes & stakeholder comms | R | C | C | C | I | I | C | I |
| Post-deploy smoke tests | C | I | R | I | I | I | I | A/R |
| Support & incident readiness | C | I | I | I | I | I | A/R | C |
| Stakeholder announcement | R | C | I | I | I | I | A/R | I |
| **Retrospective** | | | | | | | | |
| Retrospective facilitation | C | I | I | I | I | A/R | I | I |
| Action item documentation | R | C | C | I | I | C | I | I |
| Action item follow-up | A/R | C | C | I | I | C | I | I |

---

## Related Docs
- [Roles & Personas](octoacme-roles-and-personas.md) — full definitions for each role
- [Cross-functional Collaboration Checklist](octoacme-cross-functional-collaboration-checklist.md) — handoff checklists per lifecycle phase
