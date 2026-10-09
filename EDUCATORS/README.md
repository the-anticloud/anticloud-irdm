# Educators — IRDM

**Project:** IRDM  
**Category:** ACADEMIA_RD  
**Upstream:** see BENCH.json  
**Pinned commit:** `see BENCH.json`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `ec3ce9bc621e4bb5a34c4eec390565347165aa915337b6184147f5b87001c94e`  
**Date:** October 2026

## Teaching with IRDM

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `ec3ce9bc621e4bb5a34c4eec390565347165aa915337b6184147f5b87001c94e` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
