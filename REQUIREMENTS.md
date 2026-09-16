# Finance Requirements and Acceptance Criteria

## Journal posting
A journal must not post unless:
- at least two lines exist;
- every line uses a valid account code;
- every line contains either a debit or a credit, not both;
- total debits equal total credits;
- the narrative is populated;
- the journal date is later than the configured period-lock date.

## General ledger
Every posted journal line must appear in the ledger with journal reference, date, account, description, debit and credit.

## Trial balance
The trial balance is derived from posted ledger movements by account.

## Sample accounting scenarios
Accrual:
- Dr Professional Fees
- Cr Accruals

Accrual reversal:
- Dr Accruals
- Cr Professional Fees

Prepayment:
- Dr Prepayments
- Cr Bank

Monthly prepayment release:
- Dr Insurance Expense
- Cr Prepayments

## Audit trail
Each posted journal receives a sequential reference, posting timestamp, source, narrative and total value.

The demo deliberately has no delete function for posted journals.
