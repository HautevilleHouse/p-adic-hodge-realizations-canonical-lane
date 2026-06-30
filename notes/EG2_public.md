# EG2 Public Note (Capture and Restart)

Mature wording: `transport / local-to-global transfer`.

In-paper anchor: `paper/P_ADIC_HODGE_REALIZATIONS_PREPRINT.md` (`PHR_G2`).

## Goal
Expand the compressed capture/restart language into the local-to-global transport gate for `proving persistence of admissible comparison isomorphisms and period-filtration realization data across a multi-lane p-adic Hodge realization super-architecture`.

## Objects

- transport carrier: the admissible evolution or routed lattice declared in the preprint.
- capture floor: `sigma_comparison`.
- restart law: the normalization/re-entry rule that keeps corrective steps inside the admissible class.
- carried losses: defect, restart, and normalization losses that must remain explicit.

## Closure Criterion

`PHR_G2` closes when `sigma_comparison` survives admissible losses and restart corrections: defect stays above capture floor across admissible losses.
This is the transport contribution to `M_PHR`.

## Lemma Chain and Proof Payload

### Lemma EG2.1 (transport accounting)
Every transport step used by the lane is charged to the declared defect ledger instead of being absorbed into prose.

Payload: verify that the capture constant `sigma_comparison` is present in the constants registry and extraction inputs.

### Lemma EG2.2 (restart preservation)
Restart or normalization preserves the declared admissible class and does not create an untracked remainder.

Payload: inspect the repro script and guard output for the gate tied to `sigma_comparison`.

### Theorem EG2.3 (capture gate closure)
If transport accounting and restart preservation hold, then `PHR_G2` carries the local control forward without breaking admissibility.

## Current Instantiation

- gate: `PHR_G2`
- artifact key: `sigma_comparison`
- mature equivalent: `transport / local-to-global transfer`
- audit surface: `repro/run_repro.sh` and `repro/certificate_runtime.json`
