# Application ownership and dependency inventory (IT-04)

Owner: IT. Approved revision 1.0; effective 2026-01-01 unless a separate historical record states otherwise. Current at 2026-11-26.

## Scope and rule

Every application requires business and technical owners, tier, interfaces and recovery dependencies. Changes to interface behavior require affected owners' review. Inventory dependencies are directional: an upstream failure may affect downstream services, but does not prove all downstream data was lost.

## Operating evidence

Capture the business identifier, triggering event, decision date, approving function, cited source and any exception scope. Keep rejected, deferred and expired decisions in the historical record. The record of execution must distinguish the requested action from authorization and from the actual outcome.

## Worked example

A CoreLedger incident can affect OrderDesk; verify actual transaction evidence before claiming loss.

## Related controls

[Corporate decision rights](../governance/decision-rights.md) and [document authority](../governance/records-authority.md).
