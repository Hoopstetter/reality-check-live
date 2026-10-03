# Reality Check: Live

A browser-based construction decision-game prototype built around the Capture → Analyze → Create → act loop.

## Repository status

**Current repo release:** visual prototype v0.3 alignment patch.

This repository is intentionally small: `Index.html` contains the working prototype. The currently implemented gameplay is the **Hospital / Healthcare** close-in scenario.

### Approved public scenario portfolio

1. Hospital / Healthcare — implemented in this repository.
2. Data Center / Mission Critical — approved direction; not yet implemented in this repository.
3. Advanced Manufacturing — approved direction; not yet implemented in this repository.
4. Airport / Aviation — approved direction; not yet implemented in this repository.

Fire Station is not part of the public portfolio.

## What is actually implemented here

- Role entry points for VDC Manager, Superintendent, and Project Manager.
- A static hospital close-in decision loop:
  - choose capture priority;
  - judge an observed deviation against tolerance;
  - respond to a close-in risk;
  - decide what verified field reality belongs in the as-built record;
  - turn an OAC dashboard into an action;
  - reach an illustrative result/score screen.
- Responsive single-file HTML/CSS navigation.
- Illustrative progress, variance, cost, schedule, as-built, and scoring values.

## Later requirements not yet implemented in this repository

Later Reality Check work established requirements beyond this prototype. They should not be treated as present here until code lands in this repo. Those include:

- playable Data Center, Advanced Manufacturing, and Airport scenarios;
- broader role coverage such as Owner and Trade paths;
- typed gameplay/Core state as the sole authority;
- role fog, persistent consequences, replay/persistence, authored project phases, and scenario-specific causality;
- protected gameplay interaction regions and presentation-only animation;
- mobile visual-comprehension gates and explicit scene-layer contracts;
- evidence-gated tuning based on real play sessions;
- automated lane/contract validation and cross-project learning from other game builds.

## Patch intent

v0.3 does not fabricate those later systems. It makes the approved four-scenario direction visible while preserving the known-working hospital tap-through and explicitly records the boundary between implemented code and later requirements.

The next substantive implementation should add one complete non-hospital scenario end-to-end rather than sprinkling generic scenario labels across hospital-specific screens.
