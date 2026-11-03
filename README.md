# Sealed Pool Analyzer: design documents

Design work for an Android app that takes the cards a player opens at a Magic: The Gathering prerelease and recommends ranked 40-card decks, with a written rationale and a sideboard plan.

This repository holds the design documents only. Code for the app lives elsewhere once the development pipeline is planned.

## Documents

- [Design brief](docs/design-brief.md): overview, domain constraints, system architecture, the ten-step development pipeline, the fifteen-agent roster, orchestration, data sources, evaluation, risks, decisions, and roadmap. Snapshot of 2026-11-03.
- [Agentic development pipeline](docs/agentic-development-pipeline.md): how the app gets built. A central Architect agent writes tickets, Developer agents implement them in their own worktrees, an automated gate runs lint, types, unit, Compose, and snapshot tests before any model reads the branch, and two Testing agents inspect what passes. Includes the ticket contract, gating rules and budgets, feedback loops, tooling, metrics, and the nine decisions taken. Snapshot of 2026-11-03.

Both documents are maintained as living Claude Docs; this repository carries dated snapshots of them.
