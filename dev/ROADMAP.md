# synth-lang - Roadmap

> Path from scaffold to a stable 1.0. Hard parts are front-loaded; each phase has hard exit criteria.
>
> **Anti-deferral rule:** no listed hard task moves to a later phase unless this file records the move and the reason.

## v0.1.0 - Scaffold (DONE)
Compiles, CI green, structure correct, no domain logic.
- [x] Manifest, README, CHANGELOG, REPS, dual license, CI, deny, clippy, rustfmt, DIRECTIVES, ROADMAP.

## v0.2.0 - Foundation
- [ ] Generation over lang-forge grammars (rules, Pratt levels, token classes), size/depth budgets, seeded determinism, readable mode.

## v0.5.0 - Implementation
- [ ] Semantic filters via HIR hooks (well-typed programs), coverage-guided generation.

## v0.9.0 - Hardening
- [ ] Scale benches; corpus quality metrics.

## v1.0.0 - Stable
- [ ] Frozen after Studio previews and tier differential tests use it (D18).
