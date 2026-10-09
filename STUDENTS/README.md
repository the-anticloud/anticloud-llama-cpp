# Students — LLAMA_CPP

**Project:** LLAMA_CPP  
**Category:** FRONTIER_HARNESSES  
**Upstream:** see BENCH.json  
**Pinned commit:** `71ad0590f4808b6202f9213d166913858c73b1bc`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `42c37957b4c019bf568ba26098de6d0b3a6dd714f9e1c062fc02d28efc026056`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `71ad0590f4808b6202f9213d166913858c73b1bc`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `42c37957b4c019bf568ba26098de6d0b3a6dd714f9e1c062fc02d28efc026056`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
