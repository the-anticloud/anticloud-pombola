# Students — POMBOLA

**Project:** POMBOLA  
**Category:** GOVERNMENT  
**Upstream:** https://github.com/mysociety/pombola  
**Pinned commit:** `cb0f4a75aea91a471bb8b64921c80f19adf1a9f1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c0849158a2a9d1cab39a7eec12035d7e4a040901c9d08a3827d4d0dd86efea10`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `cb0f4a75aea91a471bb8b64921c80f19adf1a9f1`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `c0849158a2a9d1cab39a7eec12035d7e4a040901c9d08a3827d4d0dd86efea10`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
