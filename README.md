
# SAP S/4HANA — Integrated Business Process Simulation

Hands-on SAP S/4HANA simulation of end-to-end integrated business processes completed as part of coursework at the University of Tampa, using the Global Bike Inc. (GBI) training environment.

> **Disclosure:** Exercises and process frameworks developed by Simha R. Magal and Jeff Word (*Integrated Business Processes with ERP Systems*, Epistemy Press). Transactions executed independently in a live SAP S/4HANA 1709 system.

---

## What Was Covered

### Chapter 09-01 — Integrated Process Execution
Executed a full make-to-order and procure-to-order cycle for Rocky Mountain Bikes ordering 40 Red Deluxe Touring Bikes ($2,800/unit) from GBI:

| Step | SAP Process |
|---|---|
| Master Data Setup | Vendor, customer, material, and pricing conditions |
| Fulfillment — Start | Sales quotation → Sales order with availability check |
| Procurement | Purchase order creation and execution |
| Production | MRP run → Production order → Goods issue |
| Inventory Management | Stock Transport Order (STO) Dallas → San Diego |
| Fulfillment — End | Outbound delivery → Billing → Account settlement |

### Chapter 09-02 — Integrated Warehouse Management Process
Extended the integrated cycle with Warehouse Management (WM) steps including inbound and outbound WM processing within the fulfillment and procurement flows.

---

## Key Concepts Demonstrated

- Make-to-order and procure-to-order production/procurement strategies
- How financial account balances update at each step of the process cycle
- Stock valuation changes after external procurement and production completion
- Integration between SD, MM, PP, FI, and WM modules in a single transaction cycle

---

## Files

| File | Description |
|---|---|
| `_.pptx` | Process flow lecture slides covering the full integrated cycle |
| `Ch_09-01_Integrated_Process.docx` | Step-by-step exercise guide for integrated procurement, production, and fulfillment |
| `Ch_09-02_Integrated_WM_Process.docx` | Extended exercise guide including warehouse management steps |

---

## Skills Demonstrated

`SAP S/4HANA` `ERP` `Procure-to-Pay` `Order-to-Cash` `Production Planning` `Inventory Management` `Warehouse Management` `Financial Accounting` `Integrated Business Processes`
