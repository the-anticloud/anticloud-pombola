# Educators — POMBOLA

**Project:** POMBOLA  
**Category:** GOVERNMENT  
**Upstream:** https://github.com/mysociety/pombola  
**Pinned commit:** `cb0f4a75aea91a471bb8b64921c80f19adf1a9f1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c0849158a2a9d1cab39a7eec12035d7e4a040901c9d08a3827d4d0dd86efea10`  
**Date:** October 2026

## Teaching with POMBOLA

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `c0849158a2a9d1cab39a7eec12035d7e4a040901c9d08a3827d4d0dd86efea10` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
