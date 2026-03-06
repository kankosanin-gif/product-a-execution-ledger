# Product A — Agent Execution Ledger

Evidence-first execution ledger for work-item governance.

## Scope
- Work-item tracking with contract linkage
- Gate decisions (G1..G5) with rationale
- Escalation SLA visibility
- Proof-of-work references (Issue/PR/log/report)

## Minimal model
| Field | Purpose |
|---|---|
| work_item_id | Unique execution unit |
| contract_id | Links to task contract |
| owner | Current accountable owner |
| gate_state | Current lifecycle gate |
| risk | low/med/high |
| escalation | active/none + SLA clock |
| evidence | List of canonical links |

## Next
- Add JSON/TOML schema draft
- Add CLI validator prototype
- Add sample ledger entries

## Governance templates
- Gate Decision Log: \n- Escalation SLA: \n- Proof-of-Work template: \n