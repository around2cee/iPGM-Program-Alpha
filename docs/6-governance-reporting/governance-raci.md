# 6.1 Governance & RACI
> **PGM Role:** Creator & Collaborator | **Phase:** Initiation (established early, referenced throughout)

Defines how decisions are made, who makes them, and how the program is overseen.
Critical to establish during Program Initiation.

---

## Governance Structure

### Decision Authority
| Decision Type | Authority Level | Who Decides | Escalation Path |
|---|---|---|---|
| Scope change (minor) | Program Manager | PGM | Sponsor informed |
| Scope change (major) | Steering Committee | Sponsor + SteerCo | N/A |
| Budget change | Steering Committee | Sponsor + Finance | N/A |
| Technical architecture | Architecture Review Board | Tech Lead + ARB | SteerCo for blockers |
| Priority trade-offs | Program Manager | PGM + Sponsor | SteerCo if unresolved |
| Go/No-Go for Go-Live | Steering Committee | Sponsor + PGM + Leads | N/A |

### When Does Something Go to SteerCo?
- Scope changes that affect timeline by more than 2 weeks
- Budget changes > $X
- Unresolved cross-team escalations
- Red-status risks that require executive action
- Go/No-Go decisions

### Technical Decision Governance
_How are technical decisions made? Who has authority?_

### Issue Escalation Path
1. Issue identified → logged in RAID Log
2. PGM attempts resolution within core team (48 hours)
3. If unresolved → escalated to Program Sponsor
4. If still unresolved → Steering Committee agenda

### Change Acceptance Process
1. Change request submitted (GitHub Issue: Decision / Change Log template)
2. Impact assessed by PGM + tech lead
3. Approved by appropriate authority level (see table above)
4. Baseline updated and communicated

---

## RACI Matrix

**R** = Responsible (does the work)
**A** = Accountable (final authority)
**C** = Consulted (provides input)
**I** = Informed (notified of outcome)

| Work Product / Decision | Program Sponsor | Program Manager | Tech Lead | Engineering Teams | Operations | Steering Committee |
|---|---|---|---|---|---|---|
| Program Charter | A | R | C | I | I | I |
| Vision, Goals & Drivers | A | C | C | I | I | I |
| Program Roadmap | A | R | C | C | I | I |
| Workstream Delivery Plans | I | A/R | R | R | C | I |
| Go-Live Decision | A | R | C | C | C | A |
| Budget Approval | A | C | I | I | I | A |
| Scope Change (major) | A | R | C | I | I | A |
| Status Reports | I | R | C | I | I | I |
| Steering Committee Packs | I | R | I | I | I | A |

---

## Program Roles & Responsibilities

| Role | Name | Responsibilities |
|---|---|---|
| Program Sponsor | TBD | Ultimate accountability; removes blockers; approves major decisions |
| Program Manager | TBD | Day-to-day management; owns this toolkit; drives governance |
| Tech Lead | TBD | Technical decisions; architecture sign-off; team coordination |
| Steering Committee | TBD | Strategic oversight; major approvals; escalation receiver |
| Engineering Teams | TBD | Delivery execution; workstream plans; status updates |
| Operations Lead | TBD | Go-live readiness; BAU handover; post-live monitoring |
