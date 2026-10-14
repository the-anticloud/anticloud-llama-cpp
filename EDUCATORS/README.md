# Educators — LLAMA_CPP

**Project:** LLAMA_CPP  
**Category:** FRONTIER_HARNESSES  
**Upstream:** see BENCH.json  
**Pinned commit:** `71ad0590f4808b6202f9213d166913858c73b1bc`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `42c37957b4c019bf568ba26098de6d0b3a6dd714f9e1c062fc02d28efc026056`  
**Date:** October 2026

## Teaching with LLAMA_CPP

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `42c37957b4c019bf568ba26098de6d0b3a6dd714f9e1c062fc02d28efc026056` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
