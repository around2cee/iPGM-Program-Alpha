# 4.1 Go-Live Readiness Checklist
> **PGM Role:** Creator & Collaborator | **Phase:** Go-Live

Final, objective confirmation that all required conditions are met before entering production.
Answers one question only: "Are we actually ready to go live — right now?"

This is the last gate between "we think we're ready" and "we are going live."

---

## Sign-Off Required
| Role | Name | Signed Off | Date |
|---|---|---|---|
| Program Sponsor | | Yes / No | |
| Engineering Lead | | Yes / No | |
| QA / Test Lead | | Yes / No | |
| Operations Lead | | Yes / No | |
| Program Manager | | Yes / No | |

---

## Readiness Checklist

### Code & Technical
- [ ] All planned features developed and code-reviewed
- [ ] All critical and high-severity defects resolved
- [ ] Performance testing completed and results accepted
- [ ] Security review completed and sign-off received
- [ ] Implementation guides / runbooks finalized (docs/3-delivery-execution/implementation-guides.md)

### Testing & Acceptance
- [ ] Acceptance testing criteria defined (docs/4-go-live-closure/acceptance-testing.md)
- [ ] UAT completed with sign-off from business stakeholders
- [ ] Regression testing passed

### Infrastructure & Operations
- [ ] Production environment provisioned and validated
- [ ] Monitoring and alerting configured
- [ ] On-call / support runbook distributed to ops teams
- [ ] Rollback procedure documented and tested (docs/4-go-live-closure/cutover-backout-plan.md)

### Communications & Training
- [ ] Go-live communications drafted and scheduled
- [ ] User training completed or scheduled
- [ ] Support team briefed

### Governance
- [ ] Steering Committee has been notified of go-live date
- [ ] Change Advisory Board (CAB) approval obtained (if required)
- [ ] All program risks reviewed and accepted by sponsor

---

## Outstanding Items (must be empty before go-live)
| Item | Owner | Resolution | Target Date |
|---|---|---|---|
| | | | |
