---
Document: ADR-0001
Title: Doctrine Before Software
Version: 1.0
Status: Accepted
Classification: Internal
Owner: Operator Systems
Date: July 12, 2026
---

# ADR-0001 — Doctrine Before Software

## Context

Software organizations often accumulate product, design, and engineering decisions without preserving the reasoning behind them.

When decisions remain in conversations, meeting notes, or individual memory, the organization becomes inconsistent over time. New contributors may understand what was built without understanding why it was built that way.

Operator is intended to become a long-lived operational intelligence platform. Its founding principles, product philosophy, architecture, and significant decisions must therefore exist independently of any individual founder, employee, conversation, or implementation.

## Decision

Operator Systems will establish and maintain the Operator Canon before expanding the software platform.

The Canon will serve as the version-controlled source of truth for:

- Founding principles
- Product doctrine
- Architecture
- Engineering standards
- Design standards
- Significant decisions
- Institutional history
- Long-term vision

Major product and engineering decisions should reference the relevant doctrine and, when appropriate, receive their own Architecture Decision Record.

## Rationale

This approach:

- Preserves institutional knowledge
- Creates consistency across future teams
- Makes significant decisions traceable
- Reduces architectural drift
- Improves onboarding
- Protects the founding philosophy
- Separates enduring principles from replaceable implementations

## Consequences

### Positive

- Product and engineering work remain aligned with first principles.
- Future contributors can understand the reasoning behind the system.
- The company develops institutional memory from its beginning.
- Major decisions become reviewable and reversible when necessary.

### Negative

- Documentation requires additional time before implementation.
- Early development may feel slower.
- Doctrine can become excessive if every minor choice is formalized.

## Guardrails

Doctrine should guide execution, not delay it indefinitely.

Only enduring principles and significant decisions belong in the Canon. Daily tasks, minor implementation choices, and temporary experiments belong in issues, commits, or project boards.

## Outcome

Accepted.

Operator will be built doctrine-first, with the Canon serving as the enduring source of institutional truth.
