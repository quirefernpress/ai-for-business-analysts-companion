# Northstar completed examples

These examples show one defensible outcome. They are not the only acceptable wording.

## Example analysis frame

| Area | Completed example |
| --- | --- |
| Situation | A prospective multi-site customer may require differentiated urgent-fault handling. |
| Business concern | Northstar must know whether it can make and meet any service commitment before sales includes it in a proposal. |
| Desired outcome | A decision on service model, information needed, and conditions for an offer. |
| Decision owner | Service director, confirmed through GOV-01. |
| Evidence | SLS-01 through SLS-04, GOV-01, POL-01. |
| Constraint | Proposal deadline is next week. No nonstandard commitment is approved. |
| Open question | What does "handled differently" mean in measurable terms? |

## Example extraction and question log

| Item | Artifact type | Knowledge status | Source | Follow-up |
| --- | --- | --- | --- | --- |
| C-01 | Candidate business rule | Evidence from stakeholder statement | INT-02 | Confirm against POL-01 |
| C-02 | Contract claim | Evidence from stakeholder statement | INT-02 | Read the contract and check eligible tiers |
| C-03 | Process claim | Evidence from stakeholder statement | INT-03 | Check visibility and handoffs |
| C-04 | Candidate need | Evidence of need, incomplete design | INT-04 | Define audit fields and authority |
| C-05 | Data claim | Evidence from stakeholder statement | INT-05 | Profile parent-account links |
| C-06 | Stated constraint | Evidence from stakeholder statement | INT-06 | Confirm the scope and record approval |
| C-07 | Proposal | Evidence that a proposal was made | INT-07 | Confirm purpose and whether to proceed |
| C-08 | Data risk | Inference | INT-05 | Verify the failure path and define a fallback |
| Q-PR-01 | Open question | Unknown | INT-04 | Assign decision owner |

## Example approved pilot decisions

| ID | Decision |
| --- | --- |
| DEC-11 | Service supervisor may change priority before technician assignment. |
| DEC-12 | Technician records a recommendation; supervisor sees it in the priority-review worklist; technician cannot change priority directly. |
| DEC-13 | Missing parent-account link triggers "Contract context unavailable" and duty-supervisor review; no automated contract-tier treatment applies. |
| DEC-14 | During the pilot, priority changes after technician assignment are blocked; follow-up goes to service-manager review. |

## Example traceability rows

| Requirement | Sources | Decision or rule | Test |
| --- | --- | --- | --- |
| REQ-PR-12 | INT-04 | DEC-11, DEC-12, DEC-14, BR-04 | UAT-PR-03 through UAT-PR-06 |
| REQ-PR-13 | INT-05 | DEC-13 | UAT-DATA-02 |

## Example conditional pilot decision

> Approve an internal account-manager alert after commercial approval of customer eligibility, confirmation of the account-manager fallback, approval of the internal channel, and agreement on how to identify repeat events for a request. Send a single alert to staff after supervisor verification. Review the pilot after four weeks before considering any customer notification commitment.

