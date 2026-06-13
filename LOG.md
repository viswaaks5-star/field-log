# Field Log — AI-Code Assurance Substrate

## Day 1 — 2026-06-13
- Shipped: ai-pr-failure-taxonomy public; 21 evidenced entries; SIGNALS.md rubric; validate.py + Makefile + harvester scripts.
- Oracle: validate.py OK (21 valid); make count = 21; both repo URLs 200. PASS (>=20).
- Failure classes found: closed-by-trust-gate, misfiled-pr, superseded-or-duplicate, closed-by-quality-judgment, none-merged.
- Key finding: dominant AI-PR failure at Ghostty is context-blindness (duplicating or re-solving existing/rejected work), not broken code. curl vein thin; Ghostty rich (mandatory AI disclosure). !vouch = maintainer override of auto-close gate.
- Hours: 6 
- Texture: energizing
