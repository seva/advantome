# Implementation Plan

---

## Phase 0 — Define Unfair Advantage

Research what unfair advantage means before applying it to genome research.

- [x] Create `docs/phase-0-what-is-unfair-advantage.md`
  - Define unfair advantage.
  - Distinguish asymmetric advantage from generic improvement.
  - Cluster advantage types in a RAROC 2x2.

**Verification:** Phase 0 research artifact exists and contains cited online sources.

---

## Phase 1 — Select Asymmetry Target

**Input:** `docs/phase-0-what-is-unfair-advantage.md` in full (working definition, 5 genome-specific gates, asymmetry source table, RAROC 2x2, ethical boundary).

**Output:** `docs/phase-1-genome-asymmetries.md` containing exactly one selected asymmetry class with a clear rationale for why it survives where others don't.

- [ ] Create `docs/phase-1-genome-asymmetries.md`
  - List candidate asymmetry classes that could be genome-derived
  - For each: score against 5 gates (Signal integrity, Actionability without gatekeeper, Measurement redundancy, Effect size, Net benefit)
  - Map remaining candidates onto RAROC 2x2 (Self-actionability x Effect size)
  - **Select exactly one.** Reject all others with explicit reasoning per candidate.
  - Include: what makes this asymmetry unfair, how knowledge of it changes the bearer's outcomes, and who the "comparable actor without it" is.

**Verification:** Artifact exists with cited sources, scored candidates with rejections, and a single selected class with a specific statement of the asymmetry.

---

## Dependencies

```
Phase 0 (genome-specific asymmetry framework) — complete.
```
