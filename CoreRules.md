# Core Rules – Savings Vault Protocol

## Basic Concept

This is a digital savings vault.

Users create savings plans with a target amount and duration.

Each savings plan is independent.

A single user can create multiple savings plans.

Each savings plan tracks its balance separately.

---

## Savings Plans

Users can choose:

- 6 Month Plan
- 12 Month Plan

Users define:

- Target amount
- Duration

Users can deposit anytime until the target is reached.

Deposits are flexible.

There is no fixed daily deposit.

---

## Multiple Savings

A user can:

- Open multiple savings plans
- Run multiple plans at the same time

Each plan:

- Has its own balance
- Has its own target
- Has its own duration

---

## Withdrawals

Users cannot withdraw early without penalty.

If a user withdraws early:

Penalty = 20%

Penalty goes to treasury.

---

## Emergency Withdrawal

Emergency withdrawal is allowed only if:

User has reached at least 50% of target.

Penalty still applies.

---

## Maturity

When savings duration is completed:

User can withdraw full balance.

No penalty applies.

---

## Treasury

Treasury collects:

- Early withdrawal penalties
- Protocol fees
- Contribution group maturity fees

Treasury belongs to protocol owner.

Treasury may be used for:

- Development
- Maintenance
- Future upgrades

---

## Deposits

Users can deposit anytime.

Deposits are not fixed.

Users deposit based on their income ability.

---

## Savings Tracking

Each savings vault tracks:

- Owner address
- Target amount
- Total deposited
- Duration
- Start time
- Status

---

## Status Types

Savings plan status:

Active

Completed

Withdrawn Early

---

## Design Philosophy

Flexible savings is better than rigid savings.

Users should save based on their income.

Trust must be enforced by code.
