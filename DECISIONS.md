---
schema: aether.architecture-document/v1
id: athena-decisions
title: Athena Decisions
kind: architecture-document
version: 0.1.0
status: provisional
owners:
  - egohygiene
created: 2026-08-19
updated: 2026-08-19
governed_by:
  - architecture-decisions
depends_on:
  - athena-principles
  - athena-epistemology
  - athena-foundations
  - athena-system
  - athena-architecture
related:
  - athena-purpose
  - athena-vision
  - athena-pillars
  - athena-manifesto
supersedes: []
---

# Athena Decisions

## Purpose

This document preserves significant accepted architectural choices and their rationale. Issues coordinate work, proposals explore alternatives, and this file records decisions that constrain future implementation.

## Governance

Do not rewrite historical context to fit current understanding. Amend a record for corrections that do not change meaning; supersede it with a new record when the decision changes materially.

## Index

- ADR-0001: Require provenance and licensing metadata
- ADR-0002: Treat unclassified material as staged rather than canonical
- ADR-0003: Keep consumer-specific transformations outside the source collection

## ADR-0001: Require provenance and licensing metadata

- **Status:** Accepted as the current architectural direction
- **Date:** 2026-08-19
- **Context:** Repository evidence and ecosystem ownership require an explicit durable boundary.
- **Decision:** Require provenance and licensing metadata.
- **Consequences:** The choice improves ownership and predictability while requiring maintained contracts, validation, and migration discipline.
- **Reconsider when:** New evidence shows that the boundary prevents standalone usefulness, safety, portability, or maintainability.

## ADR-0002: Treat unclassified material as staged rather than canonical

- **Status:** Accepted as the current architectural direction
- **Date:** 2026-08-19
- **Context:** Repository evidence and ecosystem ownership require an explicit durable boundary.
- **Decision:** Treat unclassified material as staged rather than canonical.
- **Consequences:** The choice improves ownership and predictability while requiring maintained contracts, validation, and migration discipline.
- **Reconsider when:** New evidence shows that the boundary prevents standalone usefulness, safety, portability, or maintainability.

## ADR-0003: Keep consumer-specific transformations outside the source collection

- **Status:** Accepted as the current architectural direction
- **Date:** 2026-08-19
- **Context:** Repository evidence and ecosystem ownership require an explicit durable boundary.
- **Decision:** Keep consumer-specific transformations outside the source collection.
- **Consequences:** The choice improves ownership and predictability while requiring maintained contracts, validation, and migration discipline.
- **Reconsider when:** New evidence shows that the boundary prevents standalone usefulness, safety, portability, or maintainability.

## Open decisions

- Release and compatibility policy for the first stable version.
- Exact self-hosted, managed, and organization-integrated deployment boundaries.
- Which target systems must exist before the architecture status may become active.

## Evidence and uncertainty

- **Observed:** The repository README establishes the intended boundary as a shared library for useful assets, references, resources, and miscellaneous preserved collections; significant implementation remains incomplete.
- **Decided for this draft:** The repository owns the bounded concern described here and participates through versioned contracts.
- **Proposed:** Target systems and later roadmap phases remain proposals until accepted and implemented.
- **Open question:** Which parts of this draft should become active in the first independently versioned release?

## Identifier format migration (2026-10-18)

The maintainer selected four-digit numbering in [Hygiene #73](https://github.com/egohygiene/hygiene/issues/73). This padding-only migration changes current labels and anchors; logical numbers, decision content, dates and disposition remain unchanged. Git retains prior versions. New canonical records use `ADR-NNNN` under Hygiene policy v1.2.0.

| Previous ID | Current ID | Record |
| --- | --- | --- |
| `ADR-001` | `ADR-0001` | [DECISIONS.md](DECISIONS.md#adr-0001-require-provenance-and-licensing-metadata) |
| `ADR-002` | `ADR-0002` | [DECISIONS.md](DECISIONS.md#adr-0002-treat-unclassified-material-as-staged-rather-than-canonical) |
| `ADR-003` | `ADR-0003` | [DECISIONS.md](DECISIONS.md#adr-0003-keep-consumer-specific-transformations-outside-the-source-collection) |
