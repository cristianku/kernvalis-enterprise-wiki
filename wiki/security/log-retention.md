# Security audit logging (SEC-06)

Owner: Security. Approved revision 1.0; effective 2026-01-01 unless a separate historical record states otherwise. Current at 2026-11-26.

## Scope and rule

Retain authentication and privileged-change audit records for at least 12 months unless longer legal hold applies. Protect logs against unauthorized modification. Incident evidence must preserve timestamps and source identifiers.

## Operating evidence

Capture the business identifier, triggering event, decision date, approving function, cited source and any exception scope. Keep rejected, deferred and expired decisions in the historical record. The record of execution must distinguish the requested action from authorization and from the actual outcome.

## Worked example

Restoring a service does not authorize deletion of the original incident logs.

## Related controls

[Corporate decision rights](../governance/decision-rights.md) and [document authority](../governance/records-authority.md).
