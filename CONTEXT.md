# gatling/gatling context
> refreshed 2026-09-03 | upstream default: main @ 116f4b2c336fb9b0c4fbc937f58ace12947b4cf8

## Identity & policies
- upstream: gatling/gatling, default branch main, primary language Scala (Java/Kotlin/JS mix), English-first (yes — README/CONTRIBUTING in English)
- CLA/DCO: none (CONTRIBUTING.md has no CLA/DCO/signup requirement)
- AI-assisted PR policy: unstated (no AI ban, no AI disclosure requirement)
- signed commits required: no
- PR template: none (no .github/PULL_REQUEST_TEMPLATE.md, no org default) — use pipeline fallback body
- external tracker: github

## Conventions (verified from merged PRs)
- branch naming: no dominant pattern (recent merged: `sse-decoder-multidata-fix`, `patch-2`) — fall back to `type/desc`
- commit style: Conventional Commits (`feat:`, `fix:`, `chore:`, `build:`, `nit:`) with `close #NNNN` issue refs
- test command: sbt (repo is an sbt multi-module build); CI = GitHub Actions `build.yml` + Travis historically
- CONTRIBUTING requires: docs for API changes (src/sphynx), tests, formatting (auto on compile), commit referencing issue, Apache 2.0 header

## Maintainer picture
- active maintainers: Stephane Landelle, Sébastien BREVET, tpetillot, tcadoret (regular commits Aug 2026)
- external PR merges are RARE (only 2 in last 100 closed PRs: 2026-02, 2024-04) — low external-merge-rate repo; trivial PRs may sit

## Issue-area health
- active development on core (hooks, WebSocket logging, netty deps)
- no obvious contested/redesign areas in docs

## Gap ledger (dedupe — READ FIRST, never re-pick)
- (none yet for gatling)

## Mined gaps (discovered, not yet attempted)
- (pending trivial-fix hunt)
