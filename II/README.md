# Independent Insurance — POMBOLA

**Project:** POMBOLA  
**Category:** GOVERNMENT  
**Upstream:** https://github.com/mysociety/pombola  
**Pinned commit:** `cb0f4a75aea91a471bb8b64921c80f19adf1a9f1`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c0849158a2a9d1cab39a7eec12035d7e4a040901c9d08a3827d4d0dd86efea10`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | POMBOLA with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `c0849158a2a9d1cab39a7eec12035d7e4a040901c9d08a3827d4d0dd86efea10`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
