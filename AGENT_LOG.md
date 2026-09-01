# Agent Log

Append-only record of automated and agent-assisted changes to this repository.
Newest entry first. No participant data, committee or faculty names, credentials,
or tokens.

---

## 2026-09-01 - Adopt the paper ground, and repair ten contrast failures

**Token adoption, with one deliberate rescue.** `--muted` (`#6b7280`) measured 4.62 on the
old cool ground but only **4.23** on the warmer shared one - adopting the ground alone would
have broken it. It now takes the shared muted (5.43) instead of being left to fail.

**Ten pre-existing failures repaired.**

- `--blue` (`#3b82f6`) was label text on both grounds, measuring 3.22 on paper and 3.70 on
  the dark hero. It keeps its fill and border roles; text now uses `--blue-text` (5.11) on
  paper and `--blue-on-dark` (5.75) in the hero.
- A `rgba(255,255,255,.35)` span measured **3.16**; lifted to `.62` for 5.77.

**Verified.** 99 elements probed: 10 failures to **zero**; tightest pair 4.79.
