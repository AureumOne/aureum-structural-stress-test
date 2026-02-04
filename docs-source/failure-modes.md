---
id: failure-modes
title: Failure Modes
sidebar_position: 4
---

# 4. FAILURE MODES & STRESS SCENARIOS

This section describes what happens when things go wrong, not how they are prevented.

## FM-1: Custody / Record Divergence

If recorded balances exceed physical custody confirmation:

- No correction is permitted.
- An immutable exception event is generated.
- Visibility is granted to relevant scopes.
- Resolution requires a new event, not modification.

The system does not "heal" discrepancies.

## FM-2: Governance Pressure or Override Attempt

If governance attempts to authorize an action conflicting with recorded evidence:

- The action is rejected at protocol level.
- Authority cannot supersede evidence.
- Governance decisions remain recorded but ineffective.

Governance cannot validate reality.

## FM-3: Erroneous or Malicious Price Feed

If external price input is incorrect:

- Economic valuation may be distorted.
- Asset existence is unaffected.
- Evidence of quantity and custody remains intact.

Price integrity is explicitly out of scope.

## FM-4: Custodian Fraud or Misconduct

If the custodian acts fraudulently:

- The system does not prevent fraud.
- Divergence becomes visible through reconciliation failure.
- Legal and contractual remedies exist outside the system.

The architecture exposes failure; it does not insure against it.

## FM-5: Human Error in Event Submission

If incorrect data is submitted:

- The error is preserved immutably.
- Correction occurs only via compensating event.
- Historical trace remains intact.

No silent correction exists.

## FM-6: Evidence Unavailability or Delay

If evidence becomes temporarily unavailable or delayed:

- No inferred state is assumed.
- Absence is recorded as absence.
- Decisions cannot rely on inferred continuity.

Lack of evidence is treated as a first-class state.
