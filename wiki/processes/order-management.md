# Order management (OM-01)

Owner: Sales Operations. Effective 2025-07-01.

A sales order is entered in the fictional CoreLedger ERP with customer ID, currency, destination, product SKUs and requested ship date. Sales Operations checks contract pricing and forwards the order for credit evaluation under [FIN-CR-01](../finance/credit-policy.md). A passed credit check permits inventory allocation under [LOG-AL-01](../logistics/inventory-allocation.md), but does not itself authorize shipment.

Orders failing credit checks enter CREDIT_HOLD. Orders with inadequate available stock enter BACKORDER. The two conditions can coexist; neither is cleared merely because the other is resolved. Shipment requires valid credit clearance, allocation and applicable quality release.

For orders amended after clearance, increases in exposure trigger credit re-evaluation. Changes to delivery date trigger a new allocation check. The audit record retains both original and revised decisions.