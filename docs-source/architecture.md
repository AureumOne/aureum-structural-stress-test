---
id: architecture
title: Architecture
sidebar_position: 3
---

# 3. LAYERED ARCHITECTURE & AUTHORITY BOUNDARIES

Aureum One is structured as non-custodial infrastructure with explicit separation between:

- Physical Custody
- Operational Governance
- Settlement & Event Recording
- Evidence & Verifiability Layer

No layer has unilateral authority to override another.

## 3.1 What Each Layer Can Do

**Custody** can hold assets, not register ownership.

**Governance** can authorize actions, not validate facts.

**Settlement** can record events, not interpret them.

**Evidence** can expose states, not assert conclusions.

## 3.2 What No Layer Can Do

No layer can retroactively modify history.

No layer can certify sufficiency of backing.

No layer can override evidence through decision.

No human actor can "fix" inconsistencies silently.

All authority is forward-only and event-bound.

## Authority vs Responsibility

Architectural authority in Aureum One defines what the system can or cannot do.

Legal and fiduciary responsibility remains external to the system and is not substituted or mitigated by architectural constraints.
