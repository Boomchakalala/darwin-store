# Catch-Up Bookkeeping Quote Kit

Scope, price and contract catch-up and cleanup projects so the fixed fee still pays you when the work turns out messier than the client said.

The kit is currency-neutral. Wherever you see **R**, use your hourly rate. It works with QuickBooks Online, Xero or any ledger that has bank feeds.

---

## 1. The 12-question intake (send before any call)

Send this as a form. Do not quote until all 12 questions are answered.

1. Which period needs doing? Give the first month and the last month.
2. What software are the books in now, if any? Who has admin access?
3. List every account the business used in that period. Include bank accounts, credit cards, loans, PayPal, Stripe, Square and Shopify payouts, **including closed accounts**.
4. For each account, can you download statements back to the first month? (yes / partial / no)
5. Roughly how many lines are on one recent monthly statement for your busiest account?
6. Were books kept for any of this period? By whom? Do you trust them?
7. Have business accounts paid personal expenses, or personal cards paid business expenses?
8. Do you run payroll? Through which provider?
9. Do you collect sales tax or VAT?
10. Do you hold inventory?
11. Is there a hard deadline, such as a tax filing, loan application, sale or audit? What date?
12. Who will answer my questions, and how fast do they usually reply?

**What each answer changes:** Q1, Q3 and Q5 set your volume. Q4, Q6, Q7 and Q12 drive the Mess Score. Q8 to Q10 add fixed work. Q11 decides whether a rush premium applies.

---

## 2. Time one sample month before quoting

The default throughput numbers below are starting points. Your own speed is better data.

- Ask for read-only access, or statements, for **one month from the middle of the period** for every account.
- Time yourself categorizing the first 100 transactions. Then divide 100 by the minutes taken and multiply by 60. That is your transactions per hour. Use it instead of the defaults.
- For projects over 6 months or with a Mess Score of 16 or more, sell this as a **paid diagnostic**: 2 hours x R, credited against the project if the client signs within 14 days.

---

## 3. The Mess Score (0 to 24)

Score each factor from 0 to 3.

| Factor | 0 | 1 | 2 | 3 |
|---|---|---|---|---|
| Bank data | Feeds cover the whole period | Feeds for most; PDF/CSV for under 25% | PDF/CSV for most | Paper only, or statements missing |
| Receipts/documents | Organized and digital | Mostly there | Scattered across email, phone and paper | None |
| Prior books | None, or reliable | Minor errors | Widespread miscategorization | Wrong, and tax returns were filed from them |
| Commingling | None | Under 5% of transactions | 5 to 20% | Over 20%, or client does not know |
| Number of accounts | 1-2 | 3-4 | 5-7 | 8+ |
| Payroll / sales tax | Neither | One, via a provider | Both, via providers | Either done manually |
| Inventory | None | Simple, counted periodically | SKU tracking | Inventory exists, but COGS was never recorded |
| Client responsiveness | Same day | Within 2 days | Within a week | Disappears |

### Score to action

| Total | Multiplier | Rule |
|---|---|---|
| 0-5 | x1.0 | Quote a fixed fee |
| 6-10 | x1.2 | Quote a fixed fee |
| 11-15 | x1.4 | Fixed fee with milestone billing (mandatory) |
| 16-19 | x1.7 | Paid diagnostic first, then quote |
| 20-24 | none | Decline, or work hourly against a prepaid retainer |

Two factors justify a 3 on their own, whatever the total. If **Prior books = 3** or **Commingling = 3**, never quote a fixed fee without a diagnostic.

---

## 4. The hours formula

```
H = (Categorization + Reconciliation + Setup + Correction + Payroll)
    x 1.10 (communication)
    x Mess multiplier

Price = H x R, rounded UP to the nearest 50
```

**Categorization** = transactions divided by throughput. Use your timed number. Otherwise use these defaults:

| Data source | Transactions/hour |
|---|---|
| Live bank feed, rules possible | 80 |
| Imported PDF/CSV statements | 40 |
| Manual entry from paper | 20 |

**Reconciliation** is counted per account-month. One account for one month counts as 1 account-month.
- 0.3 h when a statement is available
- 0.75 h when the statement is missing, or the opening balance is unknown

**Setup:** 3 h for chart of accounts, rules, opening balances and access. Use 5 h if you are migrating from another ledger.

**Correction** applies only if prior books exist:
- Prior books score 2: add 30% of categorization hours
- Prior books score 3: add 60% of categorization hours (and diagnostic first)

**Payroll:** add 0.5 h per month if payroll is not integrated with the ledger and needs journal entries. Add 0 if it is integrated.

**Communication x1.10** covers question lists, follow-ups and the handover call. Do not drop it. Clients on catch-up jobs ask more questions than monthly clients.

---

## 5. Worked example

**Client:** a cafe, 14 months behind. It has 2 checking accounts and 1 credit card, about 320 transactions per month combined. Bank feeds go back 12 months; the oldest 2 months are only available as PDFs. Two statements are missing for one account, for 2 months, so 4 account-months have no statement. The owner did some entry in QuickBooks with minor errors. Payroll and sales tax run through providers. The cafe holds simple inventory and replies within a week.

**Mess Score**

| Factor | Score |
|---|---|
| Bank data | 1 |
| Documents | 2 |
| Prior books | 1 |
| Commingling | 1 |
| Accounts (3) | 1 |
| Payroll/sales tax | 2 |
| Inventory | 1 |
| Responsiveness | 2 |
| **Total** | **11, so x1.4** |

**Hours**

| Line | Calculation | Hours |
|---|---|---|
| Categorization (feeds) | 12 x 320 = 3,840 / 80 | 48.0 |
| Categorization (PDF) | 2 x 320 = 640 / 40 | 16.0 |
| Reconciliation (with statements) | 38 account-months x 0.3 | 11.4 |
| Reconciliation (missing) | 4 account-months x 0.75 | 3.0 |
| Setup | fixed | 3.0 |
| Correction | prior books = 1 | 0 |
| Payroll | integrated | 0 |
| **Subtotal** | | **81.4** |
| x1.10 communication | | 89.5 |
| x1.4 Mess multiplier | | **125.3** |

At R = 60: 125.3 x 60 = 7,518, rounded up to **7,550**.

### Two sanity checks before sending

1. **Per-month-behind check.** 7,550 / 14 = 539 per month behind. Compare it with what you would charge this client for ongoing monthly work. Say that is 350. The catch-up month should be **at least 1.5x** the ongoing monthly fee, because every catch-up month has no rules yet, no fresh memory and more questions. Here 539 / 350 = 1.54x, so it passes. Below 1.5x, recheck your throughput or Mess Score.
2. **Per-transaction check.** 7,550 / 4,480 transactions = 1.69 per transaction. Keep this number. It becomes your overage rate in the change-order clause (Section 8).

---

## 6. Structuring the fee

- **Fixed fee, three milestones:** 40% to start, 30% when the first half of the months is reconciled, and 30% on completion. Final reports are released after the last payment.
- **Example:** 3,020 to start, 2,265 at the halfway point, 2,265 on delivery.
- **Rush premium:** if the client's deadline is less than 3 weeks from the start date, add 25%. If it is less than 10 business days, decline unless you can clear your calendar.
- **Don't discount up front. Credit instead.** Offer to credit 10% of the catch-up fee across the first 3 months of ongoing service if the client signs a monthly agreement before delivery. In the example, that is 755, or about 252 off each of the first 3 invoices. You keep full price if they leave, and you reward the ones who stay.
- **Score 20+ or no records:** work hourly against a prepaid retainer of 20 x R. Top it up when the balance falls below 5 x R.

---

## 7. Scope statement (paste into your proposal)

> **Scope of work.** [Business name] engages [Your business] to bring the books current for the period [first month] to [last month] in [software]. This includes categorizing transactions and reconciling the following accounts: [list each account with its last 4 digits]. The fee is based on approximately [N] transactions and [N] account-months.
>
> **Deliverables.** A reconciled ledger for every listed account for every month in the period. A Profit and Loss and a Balance Sheet for the period and for each calendar year in it. A list of open questions and assumptions made.
>
> **Not included.** Preparing or filing tax returns. Amending prior returns. Payroll filings. Sales tax or VAT filings. Physical inventory counts. Recovering statements the client cannot download. Accounts not listed above. Any representation to lenders, buyers or authorities.
>
> **Client responsibilities.** Provide access and documents requested within 10 business days. Answer question lists within 5 business days. Designate one decision-maker for categorization questions.
>
> **Uncategorizable items.** Transactions the client cannot explain after one follow-up will be posted to an 'Ask My Accountant' or suspense account and listed in the handover report.

---

## 8. Change-order triggers (put these in the proposal)

State each trigger in numbers. Vague clauses get argued.

| Trigger | What happens |
|---|---|
| Transactions exceed the estimate by more than 15% | Excess billed at the per-transaction rate (fee / estimated transactions) |
| An unlisted account is discovered | Billed per account-month: (categorization hours for that account + 0.3 h) x R x multiplier |
| Documents not received within 10 business days of a request | Work pauses. Restart is scheduled within 5 business days of receipt |
| Project dormant 30 days because of the client | Deposit applied to work completed, project closed, restart requires a new quote |
| Prior-period errors that affect filed returns are found | Flagged in writing and referred to the client's tax preparer. Not fixed under this fee |
| Client requests a different period or extra reports | Written change order before work starts |

The 15% buffer matters. Clients estimate transaction counts badly, and small misses aren't worth the friction of a change order. Large misses are.

---

## 9. Scripts

### Quote email

> Subject: Your catch-up quote, [first month] to [last month]
>
> Hi [Name],
>
> Thanks for the details and the sample month. Here is what bringing your books current involves:
>
> - [N] months across [N] accounts, about [N] transactions
> - Reconciling every account to its bank statement, month by month
> - A clean Profit and Loss and Balance Sheet for each year, plus a list of anything we couldn't resolve
>
> Fixed fee: **[amount]**, paid in three parts ([40%] to start, [30%] at the halfway point, [30%] on completion). Based on your deadline of [date], I can start [date] and deliver by [date], provided documents arrive within 10 business days of each request.
>
> The attached proposal lists exactly what is and isn't included. To book your start date, sign and pay the first invoice by [date, 7 days out].
>
> [Your name]

### Objection: 'That's way more than I expected.'

> I understand. The fee comes from three things: [N] transactions, [N] account-months to reconcile, and the gaps we found, such as [missing statements or personal spending on the business card]. If budget is the constraint, there are two levers. First, you can reduce the work: download all statements yourself and pre-sort personal transactions, and I'll requote. Second, you can change the scope: start with the period your [lender/tax preparer] actually needs. I'd rather adjust the scope than the rate, because cutting the rate on the same work means corners get cut.

### Objection: 'Can you just do the last 3 months?'

> I can, if the last 3 months are all that's needed. One thing to know first: the opening balance for those 3 months depends on everything before them. If earlier months are wrong, the 3 months will be reconciled but the Balance Sheet won't be reliable. Who is asking for the books, and for which dates? Let's confirm with them before we narrow it.

### Objection: 'My last bookkeeper quoted half that.'

> That's possible. Quotes differ mostly in what they include. Mine includes reconciliation of every account for every month and a written list of unresolved items. I'm happy to compare: if their quote lists the same scope and the same accounts, send it over and I'll tell you honestly where the difference is.

### Objection: 'Can I pay at the end?'

> For catch-up work I bill in three parts so neither of us carries the full risk. The first part reserves your start date. The second comes once half the months are reconciled, so you'll already see progress before you pay it.

### Objection: 'Start now, I'll send everything later.'

> I'll start the day the deposit and the first batch of documents arrive. Starting without documents means I'd bill setup time twice. The fastest path is to send the account list and statement access this week.

### Question list template (send in batches, not one by one)

> Hi [Name], [N] questions from [month range]. Please reply in this document by [date]. A one-word answer is fine.
>
> | Date | Amount | Payee as shown | My guess | Your answer |
> |---|---|---|---|---|

Send one batch per milestone, never more than one per week. Unanswered lines after one reminder go to suspense, per the scope.

---

## 10. Red flags and what to do

| Red flag | Action |
|---|---|
| 'It should be quick, there isn't much.' | Insist on the sample month. Never quote from this sentence. |
| Client will not give read-only access or statements before the quote | Paid diagnostic or decline |
| Deadline is less than 10 business days away and the period is over 6 months | Decline, or hourly with retainer and no promised date |
| Third bookkeeper in two years | Diagnostic first; ask why the others left |
| Wants the books to 'show' a particular profit for a lender | Decline |
| Cannot name all accounts | Add 2 account-months of contingency per vague answer, or require a bank list from the client |
| Tax returns already filed from the books you're fixing | Prior books = 3. Diagnostic, and the referral clause in writing |

---

## 11. Pre-send checklist

- [ ] All 12 intake answers received
- [ ] Sample month timed and your throughput replaces the defaults
- [ ] Mess Score totaled; diagnostic required if 16+ or Prior books / Commingling = 3
- [ ] Account-months counted, missing statements counted separately
- [ ] x1.10 communication and Mess multiplier both applied
- [ ] Rounded up to the nearest 50
- [ ] Per-month-behind is at least 1.5x the ongoing monthly fee
- [ ] Per-transaction rate written into the change-order clause
- [ ] Every account listed by name and last 4 digits in the scope
- [ ] Exclusions list included
- [ ] Milestone amounts written out in currency, not just percentages
- [ ] Rush premium checked against the client's deadline
- [ ] Quote expires in 7 days

---

## Quick reference card

```
Categorization: feed 80/h | PDF 40/h | manual 20/h
Reconciliation: 0.3 h per account-month | 0.75 h if missing
Setup: 3 h (5 h migration)
Correction: +30% (prior=2) | +60% (prior=3)
Payroll not integrated: +0.5 h/month
Communication: x1.10
Mess: 0-5 x1.0 | 6-10 x1.2 | 11-15 x1.4 | 16-19 x1.7 | 20+ decline/hourly
Rush (<3 weeks): +25%
Billing: 40 / 30 / 30
Overage trigger: >15% transactions
Per-month-behind floor: 1.5x ongoing monthly fee
```
