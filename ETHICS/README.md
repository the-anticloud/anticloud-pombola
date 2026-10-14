# Ethics — POMBOLA

**Project:** POMBOLA  
**Category:** GOVERNMENT  
**Upstream:** https://github.com/mysociety/pombola  
**Pinned commit:** `cb0f4a75aea91a471bb8b64921c80f19adf1a9f1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c0849158a2a9d1cab39a7eec12035d7e4a040901c9d08a3827d4d0dd86efea10`  
**Date:** October 2026

## Position

POMBOLA is packaged for offline deployment with a verifiable audit trail. The
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
