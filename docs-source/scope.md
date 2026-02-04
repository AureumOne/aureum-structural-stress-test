---
id: scope
title: Scope & Assumptions
sidebar_position: 2
---

# 2. SCOPE, NON-SCOPE & STRUCTURAL ASSUMPTIONS

## 2.1 Scope

This document evaluates architecture, not operations.

Specifically:

- segregation of roles
- authority boundaries
- evidence generation
- reconciliation logic
- failure containment

The analysis is deliberately structural and static. No claims are made about execution quality, counterpart behavior or commercial viability.

Time dynamics, scale effects and adversarial coordination between actors are considered only insofar as they impact structural boundaries.

## 2.2 Explicit Non-Scope

This document does not evaluate or represent:

- regulatory compliance in any jurisdiction
- suitability for any investor profile
- financial performance or returns
- operational readiness
- counterparty creditworthiness
- fraud resistance beyond architectural limits

Absence of discussion does not imply mitigation.

## 2.3 Structural Assumptions

The architecture relies on the following explicit assumptions, which are not proven by the system:

**S1.**  
Physical gold custody is performed by an independent professional custodian under contract.

**S2.**  
The custodian does not rehypothecate or reuse the asset.

**S3.**  
Contractual enforcement exists outside the system.

**S4.**  
External price feeds reflect market reality within acceptable tolerance.

**S5.**  
Jurisdictional enforcement remains available for contractual disputes.

Violation of any assumption degrades guarantees but does not retroactively alter architectural boundaries.
