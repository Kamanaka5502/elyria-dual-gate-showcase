# URK Connection — Dual Gate to Resolving Kernel

This document connects the public dual-gate model to the underlying Universal Resolving Kernel (URK) proof spine.

## Relationship

The dual-gate structure is the application surface.

The URK is the governing proof substrate.

- Gate A (semantic integrity) ensures a candidate is structurally coherent.
- Gate B (execution boundary) ensures a candidate is admissible to bind consequence.

## URK spine (public-safe form)

The resolving field is defined by invariant preservation and admissibility constraints.

Invariant families:

- I_T — truth integrity
- I_C — conservation
- I_P — policy integrity

Capacity relation:

Phi(x) = C(x) - M(x)

Admissible region:

R = { x : A(x) >= 0, Phi(x) >= 0, U(x) = 1 }

Where:

- A(x) is admissibility
- Phi(x) is remaining capacity after burden
- U(x) is authority validity

## Breach behavior

If invariants fail:

Breach → Halt → Judgement → Restart

No silent continuation is permitted.

## Replay law

same state + same governing field + same admissibility geometry = same outcome

## Dual-gate mapping

Gate A prevents unstable or ambiguous meaning from entering the execution layer.

Gate B prevents semantically valid outputs from binding consequence unless the URK conditions hold.

## Public boundary

This document does not expose:

- kernel implementation
- evaluator internals
- thresholds
- private proof machinery

It exposes only the public mapping between the dual-gate structure and the resolving proof field.
