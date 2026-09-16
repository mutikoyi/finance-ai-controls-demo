# Finance AI Controls Demo

A small AI-assisted finance-controls prototype using entirely fictional data.

## Purpose

This prototype demonstrates how practical accounting requirements and control rules can be translated into working software with AI assistance.

My background is finance rather than software engineering. I defined the accounting requirements, expected outcomes and control behaviour, and used AI to help structure and implement the browser-based prototype.

This is **not production accounting software**. It is a demonstration of finance logic, product thinking, testing and iterative development.

## What the prototype demonstrates

- Double-entry journal validation
- Prevention of unbalanced journal posting
- Account-code validation
- Period-lock controls
- Accruals and accrual reversals
- Prepayments and monthly releases
- General ledger generated from posted journals
- Trial balance generated from ledger movements
- Sequential journal references
- Basic audit trail for posted journals

## Finance requirements and testing

The prototype was designed around accounting outcomes rather than code first.

Examples of requirements tested include:

- total debits must equal total credits before a journal can post;
- postings must use valid nominal-ledger accounts;
- journals cannot be posted into a locked accounting period;
- accruals and prepayments must produce the expected P&L and balance-sheet treatment;
- reversing entries must correctly unwind the original accounting effect;
- posted journals must flow consistently into the ledger and trial balance;
- posting history must remain visible through the audit trail.

## AI-assisted development approach

**Finance requirement → control rule → prototype → test scenario → review → refinement**

AI was used to help translate the finance requirements into code and refine the prototype. The accounting logic and expected outcomes were defined and tested from a finance-practitioner perspective.

## Sample scenarios

The demonstration includes fictional examples for:

- month-end professional-fees accrual;
- accrual reversal;
- annual insurance prepayment;
- monthly prepayment release.

## Scope and limitations

This is intentionally a small demonstration rather than a complete accounting application.

It does not include authentication, persistent database storage, tax engines, bank feeds, payment processing, production security, multi-company consolidation or user permissions. Posted journals are held only for the current browser session and reset when the page is refreshed.

The purpose is to demonstrate the method: **understand the accounting requirement first, define the controls, then use AI-assisted development to build and test the feature.**
