# Post-recovery transaction reconciliation (IT-05)

Owner: IT and Finance. Approved revision 1.0; effective 2026-01-01 unless a separate historical record states otherwise. Current at 2026-11-26.

## Scope and rule

After recovery, identify incomplete, duplicated or delayed transactions across interfaces. Preserve original identifiers and verify business totals before declaring reconciliation complete. Do not replay messages without checking idempotency and business state.

## Operating evidence

Capture the business identifier, triggering event, decision date, approving function, cited source and any exception scope. Keep rejected, deferred and expired decisions in the historical record. The record of execution must distinguish the requested action from authorization and from the actual outcome.

## Worked example

A restored invoice queue may contain already-posted messages; compare posting identifiers before replay.

## Related controls

[Corporate decision rights](../governance/decision-rights.md) and [document authority](../governance/records-authority.md).
