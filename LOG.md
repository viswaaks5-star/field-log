# Field Log — AI-Code Assurance Substrate

## Day 1 — 2026-06-13
- Shipped: ai-pr-failure-taxonomy public; 21 evidenced entries; SIGNALS.md rubric; validate.py + Makefile + harvester scripts.
- Oracle: validate.py OK (21 valid); make count = 21; both repo URLs 200. PASS (>=20).
- Failure classes found: closed-by-trust-gate, misfiled-pr, superseded-or-duplicate, closed-by-quality-judgment, none-merged.
- Key finding: dominant AI-PR failure at Ghostty is context-blindness (duplicating or re-solving existing/rejected work), not broken code. curl vein thin; Ghostty rich (mandatory AI disclosure). !vouch = maintainer override of auto-close gate.
- Hours: 6 
- Texture: energizing

# Day 2 - 2026-06-14
-Shipped: pull_prs.py (raw/label split, offline byte-identical rebuild); schema v1; 27 Day-1 entries repaired (title/created_at now populated from API); dateset = 40, now CROSS-REPO (Ghostty + Godot orbit); CSV export + CI; migrate_to_labels.py.
-Oracle: fresh-clone 'rebuild' -> 40 rows. sha256 MATCH (BYTE-IDENTICAL); make count = 40; validate OK. PASS(>=40)
-48 hour commitment: met and exceeded (20 required, 40 logged).
-Hours : 8 hours
-Texture : Neutral with excitment to dig in and find the truth
#DAY 3 - 2026-06-16
-Shipped: scripts/stactic_check.py (static-verification harness; correctness aware CI + apply assymetry fixes); 12 machine verdicts over policy-class dead PRs; repro_status written into labels FROM verdicts (script, never hand); make repro-check (re-derives + assert hash).
Oracle: 12 verdicts (>=10); distribution 2 claim-reproduced / 10 provenance-confirmed; make repro-check -> MATCH; CI green. PASS.
Hours: 6 hours 
Texture: Energizing
