# Educators — VENGI

**Project:** VENGI  
**Category:** VOXELIZATION  
**Upstream:** see BENCH.json  
**Pinned commit:** `5e15965a819ca1be9f14d2e8e319e98fd89a557f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `74e9e96462540d5464f4eb4abc014e4f098300fc7dd16bf1bf837cf6ddcbe4d8`  
**Date:** October 2026

## Teaching with VENGI

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `74e9e96462540d5464f4eb4abc014e4f098300fc7dd16bf1bf837cf6ddcbe4d8` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
