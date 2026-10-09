# Ethics — LLAMA_CPP

**Project:** LLAMA_CPP  
**Category:** FRONTIER_HARNESSES  
**Upstream:** see BENCH.json  
**Pinned commit:** `71ad0590f4808b6202f9213d166913858c73b1bc`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `42c37957b4c019bf568ba26098de6d0b3a6dd714f9e1c062fc02d28efc026056`  
**Date:** October 2026

## Position

LLAMA_CPP is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
