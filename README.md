# Elyria Systems — Dual-Gate Showcase

Public dual-gate proof surface for semantic integrity, execution admissibility, commit-boundary refusal, receipts, and replay.

This repository is not the private engine. It is the public-safe proof surface for the dual-gate model.

## Core claim

A valid answer is not the same thing as an admissible action.

Elyria Systems separates:

- Gate A: semantic integrity
- Gate B: execution boundary

Gate A determines whether the proposed meaning, structure, and handoff are coherent enough to be considered.

Gate B determines whether the proposed action is admissible to bind consequence.

## Public proof files

- DUAL_GATE_MODEL.md
- GATE_A_SEMANTIC_INTEGRITY.md
- GATE_B_EXECUTION_BOUNDARY.md
- HANDOFF_CONTRACT_PUBLIC.md
- ONE_DUAL_GATE_PROOF.md
- NON_IMPLEMENTATION_NOTICE.md
- LICENSE
- NOTICE
- dual_gate_register.json

## Non-implementation boundary

This repository does not contain proprietary runtime implementation, evaluator internals, private thresholds, production adapters, signing infrastructure, or customer-specific policy logic.

## Foundation lineage

Elyria Systems is the visible product surface.

VA / Veritas Aegis remains the foundation and enforcement lineage beneath the product surface.