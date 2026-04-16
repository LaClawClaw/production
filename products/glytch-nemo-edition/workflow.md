# Manufacturing Workflow — Glytch: Nemo Edition

Five phases from design handoff to mass production. Each phase lists what
we deliver TO the factory, what the factory delivers back, and the
acceptance criteria. When each phase completes, we publish a build-log
entry at [laclawclaw.com/build](https://laclawclaw.com/build).

## Phase 1 — Design Handoff

**We provide:** Reference STL + 2D drawings + spec sheet
**Factory delivers:** DFM (design-for-manufacturing) feedback
**Acceptance:** Written DFM review covering material, wall thickness,
draft angles, gate/parting line choices.

## Phase 2 — CAD Development

**Duration:** 2 weeks
**Factory delivers:** Production STEP file
**Acceptance:** STEP file renders cleanly in Fusion 360; no spurious
geometry; parting lines match our design intent (hidden at cap-to-fur joint).

## Phase 3 — CAD Sign-off

**We do:** Full review in Fusion 360; verify parting lines, socket
dimensions, wall thickness, draft angles.
**Factory delivers:** (none — awaiting our approval)
**Acceptance:** Written approval message: "**STEP approved for tooling**".
At this moment the factory cuts steel.

## Phase 4 — T1 Sample

**Factory delivers:** First-shot sample (unpainted PVC pull from the cut
tool).
**We do:** Physical inspection — fit, feel, parting-line seam, socket tolerances.
**Acceptance:** T1 pass or a written T1-rework list.

## Phase 5 — Production

**We do:** Give final approval based on T1 (or iterated T2/T3).
**Factory delivers:** Mass production (Founders Edition: 200 units).
**Acceptance:** Final QC pass before packing; serial numbering 1/200 …
200/200; packing list matches pre-order roster.

## Post-production (on the roadmap)

- Packing & logistics (ocean vs air freight choice to be published)
- QC sampling methodology
- Customer unboxing documentation
