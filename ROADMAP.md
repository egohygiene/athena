---
schema: aether.architecture-document/v1
id: athena-roadmap
title: Athena Roadmap
kind: architecture-document
version: 0.1.0
status: provisional
owners:
  - egohygiene
created: 2026-08-19
updated: 2026-08-24
governed_by:
  - architecture-roadmap
depends_on:
  - athena-vision
  - athena-pillars
  - athena-architecture
  - athena-decisions
related:
  - athena-purpose
  - athena-principles
  - athena-manifesto
  - athena-epistemology
supersedes: []
---

# Athena Roadmap

<!-- BEGIN ROADMAP EXECUTION SNAPSHOT -->
<!-- roadmap-manifest
schema: hygiene.roadmap/v1alpha1
repository: egohygiene/athena
visibility: public
publication: central
route: /roadmap/athena/
updated: 2026-08-24
-->
## 2026-08-24 execution snapshot

> This evidence-reconciled snapshot is the issue-generation and visual-roadmap handoff. The longer-horizon strategy below remains canonical context; generated HTML, JSON, progress, issue plans, and commit lists are projections.

**Lifecycle:** asset collection foundation  
**Current gate:** Produce a machine-readable inventory and rights/provenance ledger before packaging or encouraging reuse.  
**North-star outcome:** A rights-aware, deduplicated, discoverable, and versioned asset library for the organization.

### Visual roadmap publication

**Mode:** `central`  
**Route:** `/roadmap/athena/`  
**Current publication evidence:** Raw GitHub asset collection; no generated catalog, CI, Pages, package, or release observed.

Publish the public-safe projection through egohygiene.io at /roadmap/athena/. This repository owns intent and acceptance evidence; it does not add a second site deployment.

### Quest line

<!-- roadmap-step
id: ATH-Q01
status: complete
depends_on: []
issues: []
-->
#### ATH-Q01 — Import the initial asset collection

**State:** `complete`  
**Depends on:** None

**Outcome:** A substantial collection of badges, emojis, gitignore files, licenses, research assets, and themes exists.

**Exit criteria:**

- [x] Asset classes are present in the repository.
- [x] The architecture records the intended library role.

**Current evidence:**

- Initial import commit 96074441b8848aa8856d138b7f3c151b1998e8f1 landed on 2026-07-29.
- Architecture PR #1 merged at bfa0d871f42daa71a63ae15b5280ee7ebae23314 on 2026-08-20.

<!-- roadmap-step
id: ATH-Q02
status: active
depends_on: [ATH-Q01]
issues: []
-->
#### ATH-Q02 — Generate the asset inventory

**State:** `active`  
**Depends on:** `ATH-Q01`

**Outcome:** Every asset has a stable identifier, class, path, format, size, digest, and source where known.

**Exit criteria:**

- [ ] The complete collection is represented in machine-readable inventory.
- [ ] CI rejects missing files, duplicate identifiers, and digest drift.

**Current evidence:**

- The repository is approximately 91.9 MB, but no generated inventory or CI was observed.

<!-- roadmap-step
id: ATH-Q03
status: blocked
depends_on: [ATH-Q02]
issues: []
-->
#### ATH-Q03 — Establish rights and provenance

**State:** `blocked`  
**Depends on:** `ATH-Q02`

**Outcome:** Every distributable asset has a documented source, license, attribution, and allowed-use classification.

**Exit criteria:**

- [ ] Unknown or incompatible rights block distribution.
- [ ] Attribution files can be generated per package.

**Current evidence:**

- Asset-level rights and provenance were not observed.

<!-- roadmap-step
id: ATH-Q04
status: planned
depends_on: [ATH-Q02, ATH-Q03]
issues: []
-->
#### ATH-Q04 — Classify and deduplicate the collection

**State:** `planned`  
**Depends on:** `ATH-Q02`, `ATH-Q03`

**Outcome:** Searchable taxonomy and duplicate decisions make the collection maintainable.

**Exit criteria:**

- [ ] Exact and perceptual duplicates have recorded dispositions.
- [ ] Taxonomy and tags cover all distributable assets.

**Current evidence:**

- No automated classification or deduplication evidence was observed.

<!-- roadmap-step
id: ATH-Q05
status: planned
depends_on: [ATH-Q04]
issues: []
-->
#### ATH-Q05 — Publish versioned asset packages and discovery

**State:** `planned`  
**Depends on:** `ATH-Q04`

**Outcome:** Consumers can discover, preview, pin, and attribute safe asset subsets.

**Exit criteria:**

- [ ] Tagged packages include manifests, licenses, checksums, and previews.
- [ ] A Pages or portal view filters and links every published asset.

**Current evidence:**

- No Pages site or release was observed.

### Roadmap-to-issue handoff

- A step is complete only when its exit criteria and required evidence are satisfied; commit count never determines progress.
- Ready or planned steps without an issue are candidates for the private, duplicate-aware roadmap.issue-plan.json dry run.
- Issue creation or reconciliation requires human approval or an explicitly authorized Pace operation and returns issue references through a reviewable roadmap pull request.
- Pull requests and commits should include Roadmap-Step: <ID>; historical evidence may be linked through existing issue and pull-request relationships.
- Public rendering uses only allowlisted build-time evidence and never places a GitHub token or private issue plan in the browser artifact.

<!-- END ROADMAP EXECUTION SNAPSHOT -->

## Strategic context

This roadmap describes capability evolution, not promised dates or an issue queue. Sequence follows architecture dependencies and may change when evidence or risk changes.

## Phase 1: Inventory current holdings

**Outcome:** A bounded capability advances from documented intent to validated, independently usable behavior.

**Exit signals:**

- The owning contract and acceptance criteria are versioned.
- Implementation and documentation agree.
- Relevant tests and safety checks pass.
- Downstream consumers and migration impact are understood.
- Remaining uncertainty is visible.

## Phase 2: Define metadata and rights contracts

**Outcome:** A bounded capability advances from documented intent to validated, independently usable behavior.

**Exit signals:**

- The owning contract and acceptance criteria are versioned.
- Implementation and documentation agree.
- Relevant tests and safety checks pass.
- Downstream consumers and migration impact are understood.
- Remaining uncertainty is visible.

## Phase 3: Classify and deduplicate collections

**Outcome:** A bounded capability advances from documented intent to validated, independently usable behavior.

**Exit signals:**

- The owning contract and acceptance criteria are versioned.
- Implementation and documentation agree.
- Relevant tests and safety checks pass.
- Downstream consumers and migration impact are understood.
- Remaining uncertainty is visible.

## Phase 4: Publish discovery projections

**Outcome:** A bounded capability advances from documented intent to validated, independently usable behavior.

**Exit signals:**

- The owning contract and acceptance criteria are versioned.
- Implementation and documentation agree.
- Relevant tests and safety checks pass.
- Downstream consumers and migration impact are understood.
- Remaining uncertainty is visible.

## Phase 5: Integrate approved consumer workflows

**Outcome:** A bounded capability advances from documented intent to validated, independently usable behavior.

**Exit signals:**

- The owning contract and acceptance criteria are versioned.
- Implementation and documentation agree.
- Relevant tests and safety checks pass.
- Downstream consumers and migration impact are understood.
- Remaining uncertainty is visible.

## Cross-cutting tracks

- Security, privacy, accessibility, licensing, and provenance.
- Documentation, architecture portals, examples, and onboarding.
- Packaging, release, compatibility, and self-hosting.
- Organization integration through explicit contracts.
- Observatory evidence and Pace conformance when those systems exist.

## Deferred direction

Optional managed services, enterprise controls, marketplaces, and the conversational organization compiler remain later architecture work. Current choices should preserve portability and avoid foreclosing them.

## Evidence and uncertainty

- **Observed:** The repository README establishes the intended boundary as a shared library for useful assets, references, resources, and miscellaneous preserved collections; significant implementation remains incomplete.
- **Decided for this draft:** The repository owns the bounded concern described here and participates through versioned contracts.
- **Proposed:** Target systems and later roadmap phases remain proposals until accepted and implemented.
- **Open question:** Which parts of this draft should become active in the first independently versioned release?
