---
Document: ADR-0002
Title: Experience Before Features
Version: 1.0
Status: Accepted
Classification: Internal
Owner: Operator Systems
Date: July 12, 2026
---

# ADR-0002 — Experience Before Features

## Context

Early-stage software teams often attempt to validate a product by building many features at once.

This commonly produces a broad but fragmented application with inconsistent workflows, unfinished capabilities, and excessive cognitive load.

Operator's differentiation depends less on the number of features it contains and more on whether the entire experience feels coherent, calm, intelligent, and useful.

The first release must demonstrate the product philosophy through a complete user journey rather than a collection of disconnected functions.

## Decision

Operator Systems will prioritize a cohesive end-to-end experience before expanding the product's feature set.

The initial experience will focus on:

1. Arrival
2. Commissioning
3. Building the user's operation
4. Operational briefing
5. Decision Surface

These experiences should be polished and connected before broad capabilities such as collaboration, marketplaces, advanced integrations, or enterprise federation are added.

## Rationale

A complete experience:

- Demonstrates the product vision more clearly
- Creates stronger user trust
- Produces better feedback
- Reduces feature creep
- Improves demo quality
- Establishes reusable interaction patterns
- Validates whether Operator feels meaningfully different

## Consequences

### Positive

- The initial product will feel more coherent.
- Engineering effort remains focused.
- The team can test the central product thesis quickly.
- Users evaluate a meaningful workflow rather than isolated features.

### Negative

- Some requested features will be delayed.
- The initial release may appear narrow.
- Additional discipline is required to prevent premature expansion.

## Guardrails

A feature should not enter the initial release unless it directly strengthens the core journey.

The core journey is:

```text
Arrival
→ Commissioning
→ Operational Understanding
→ Briefing
→ Decision Surface
