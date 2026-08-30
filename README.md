# CampusCart

> A streamlined command-line ledger and point-of-sale system ensuring financial accuracy for campus enterprises.

---

## Overview

CampusCart is a terminal-based application built to help student entrepreneurs maintain airtight transaction records, track inventory in real-time, and generate audit-ready receipts without the overhead of heavy commercial software.

## Problem Statement

Campus vendors frequently rely on mental math or unorganized paper ledgers during high-traffic periods between lectures. This manual approach leads to revenue leakage, inaccurate daily reconciliation, and broken inventory tracking. CampusCart eliminates these discrepancies by enforcing a structured, automated flow for logging sales and updating stock quantities.

## Target Users

- Student-led meal and retail startups
- Pop-up vendors at university fairs and departmental events
- Volunteer treasurers managing temporary campus sales

## Core Features

- Maintain a real-time inventory ledger
- Automatically compute cart totals and apply predefined tax or discount rates
- Generate standardized, itemized receipts for clear transaction trails
- Log daily sales data for easier end-of-day financial reconciliation

## Value Proposition

- **Financial Integrity** — eliminates calculation errors and revenue leakage during busy hours
- **Audit-Ready Records** — standardizes receipt output for accurate daily sales tracking
- **Lightweight Deployment** — runs instantly in any basic terminal with zero infrastructure costs
- **Intuitive Workflow** — designed for fast data entry via keyboard

## User Personas

| Persona | Role | Core Need |
| :--- | :--- | :--- |
| **Vendor** | Pop-up shop operator | A foolproof system to accurately tally sales and reconcile the day's revenue against remaining stock |
| **Customer** | Student shopper | Fast service and a clear, itemized breakdown of their purchase |

## Proposed CLI Interface

```
=================================
        CAMPUS CART
=================================
1. View Inventory Ledger
2. Register New Stock Item
3. Adjust Stock Quantities
4. Process Sale & Generate Receipt
5. Export Daily Reconciliation
6. Exit

Select an operational code: _
```