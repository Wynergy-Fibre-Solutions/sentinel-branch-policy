# sentinel-branch-policy

**Deterministic branch protection and change-control policy baseline.**

This repository is a Wynergyy incubation asset defining a minimal, enforceable branch policy suitable for governance-first systems.

## Status

- Incubation: active
- Production claims: none
- Certification: none
- Support guarantees: none

## Purpose

This repository exists to:

- define non-negotiable branch protection rules
- prevent unsafe or unreviewed changes
- provide a policy baseline for governed repositories
- support elevation into WFSL enforcement tooling

## What this is not

- Not a GitHub app
- Not a hosted service
- Not a compliance guarantee
- Not a WFSL-certified asset

## Policy principles

- Protected default branch
- No force-push to protected branches
- Deterministic review requirements
- Explicit exceptions only

## Elevation gate

This repository becomes eligible for WFSL elevation only when:

1. Licence is Apache License 2.0
2. Branch rules are explicit and reproducible
3. Policy can be enforced mechanically
4. A tagged elevation baseline exists

## Licence

Apache License 2.0. See `LICENSE`.
