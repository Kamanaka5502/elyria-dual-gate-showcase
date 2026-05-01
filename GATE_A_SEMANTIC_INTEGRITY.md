# Gate A — Semantic Integrity

Gate A evaluates whether a proposed meaning is coherent enough to hand off.

## Evaluates

- structural coherence
- ambiguity
- contradiction
- completeness
- scope clarity
- handoff readiness

## Outcomes

- PASS — candidate may proceed to Gate B
- REDIRECT — meaning can be repaired before handoff
- REFUSE — meaning is unstable or contradictory

## Boundary rule

Gate A does not authorize consequence.

It only determines whether the semantic candidate is stable enough to be evaluated by the execution boundary.

## Private layer not exposed

- semantic evaluator internals
- scoring thresholds
- model prompts
- private classifiers
