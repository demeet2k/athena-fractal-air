# Athena federation contract

This directory makes `demeet2k/athena-fractal-air` a typed participant in the Athena Git Brain.
It does not copy the Athena corpus or grant this repository global authority.

- Resource: `athena.repo.view.fractal-air@contract-proposal-0.1.0`
- Role: `view`
- Authority domain: `projection-fractal-air`
- Base content witness: `3eecf5cab4a8b712705792ad72f44f5e7287c503`
- Control-plane schema commit: `3d33fbcd6248fc2dc2991fbbab5e93a7eb184246`
- State: `GENERATOR_LINEAGE_REQUIRED`

`repo.json` declares the local surface. `exports.jsonl` exposes bounded
identities. `imports.lock.json` pins the control-plane schema. `edges.jsonl`
contains the forward declaration and its explicit return edge. `status.json`
preserves blockers instead of promoting them away.
