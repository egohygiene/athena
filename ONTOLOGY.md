---
schema: aether.architecture-document/v1
id: athena-ontology
title: Athena Ontology
kind: architecture-document
version: 0.1.0
status: provisional
owners:
  - egohygiene
created: 2026-08-19
updated: 2026-08-19
governed_by:
  - architecture-ontology
depends_on:
  - athena-purpose
  - athena-vision
  - athena-principles
  - athena-epistemology
related:
  - athena-pillars
  - athena-manifesto
  - athena-ai-constitution
  - athena-personal-model
supersedes: []
---

# Athena Ontology

## Domain scope

Athena models the concepts needed for preserve reusable material with enough provenance, classification, and licensing context to make later use safe and discoverable. The ontology names conceptual entities and relationships; it is not a source-code class model, API schema, or database design.

## Canonical concepts

| Concept | Meaning |
| --- | --- |
| Collection | A canonical concept in the Athena domain whose exact fields belong to specifications or schemas, not this ontology. |
| Asset | A canonical concept in the Athena domain whose exact fields belong to specifications or schemas, not this ontology. |
| Reference | A canonical concept in the Athena domain whose exact fields belong to specifications or schemas, not this ontology. |
| Source | A canonical concept in the Athena domain whose exact fields belong to specifications or schemas, not this ontology. |
| License | A canonical concept in the Athena domain whose exact fields belong to specifications or schemas, not this ontology. |
| Provenance | A canonical concept in the Athena domain whose exact fields belong to specifications or schemas, not this ontology. |
| Classification | A canonical concept in the Athena domain whose exact fields belong to specifications or schemas, not this ontology. |
| Quality state | A canonical concept in the Athena domain whose exact fields belong to specifications or schemas, not this ontology. |
| Consumer | A canonical concept in the Athena domain whose exact fields belong to specifications or schemas, not this ontology. |
| Retention decision | A canonical concept in the Athena domain whose exact fields belong to specifications or schemas, not this ontology. |

## Core relationships

- A repository or person provides source context to one or more domain artifacts.
- A specification constrains how an artifact is interpreted or produced.
- A plan separates proposed action from execution.
- Evidence supports a claim; a decision authorizes a durable direction.
- Provenance connects derived artifacts to their inputs and processing context.
- A consumer integrates through an explicit interface rather than internal structure.

## Boundaries

- Conceptual identity is distinct from filesystem path, database identifier, or display label.
- Observed state is distinct from desired state.
- Proposed relationships are not accepted facts.
- Neighboring repositories retain ownership of their domain concepts.

## Evidence and uncertainty

- **Observed:** The repository README establishes the intended boundary as a shared library for useful assets, references, resources, and miscellaneous preserved collections; significant implementation remains incomplete.
- **Decided for this draft:** The repository owns the bounded concern described here and participates through versioned contracts.
- **Proposed:** Target systems and later roadmap phases remain proposals until accepted and implemented.
- **Open question:** Which parts of this draft should become active in the first independently versioned release?
