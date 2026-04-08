# 4.3 Cutover & Backout Plan
> **PGM Role:** Creator & Collaborator | **Phase:** Go-Live

The Cutover Plan is the time-sequenced execution script for go-live.
The Backout Plan is the controlled escape hatch from a failed cutover.

---

## Cutover Overview
| Field | Value |
|---|---|
| Go-Live Date | |
| Cutover Window Start | |
| Cutover Window End | |
| Cutover Lead | |
| Communications Lead | |

## Pre-Cutover Tasks
| # | Task | Owner | Start Time | Complete By | Status |
|---|---|---|---|---|---|
| 1 | Final go/no-go decision | Program Sponsor + PGM | T-24h | T-24h | |
| 2 | Comms sent to all users | Comms Lead | T-4h | T-4h | |
| 3 | Freeze changes to current system | Engineering Lead | T-2h | T-2h | |

## Cutover Steps (Time-Sequenced)
| # | Step | Owner | Time | Validation |
|---|---|---|---|---|
| 1 | | | | |

## Post-Cutover Validation
| Check | Owner | Pass Condition | Status |
|---|---|---|---|
| System is accessible | | | |
| Core workflows functional | | | |
| Monitoring / alerts active | | | |

---

## Backout Triggers
_Under what conditions do we invoke the backout plan? Who makes the call?_

| Trigger | Decision Maker | Max Time to Decide |
|---|---|---|
| Critical functionality broken | Program Sponsor + Eng Lead | 30 minutes |
| Data integrity issue | Eng Lead | Immediate |

## Backout Steps
| # | Step | Owner | Estimated Time |
|---|---|---|---|
| 1 | Declare backout — notify all teams | PGM | 5 min |
| 2 | | | |

## Backout Communication
_Who is notified, by what channel, in what order if we roll back?_
