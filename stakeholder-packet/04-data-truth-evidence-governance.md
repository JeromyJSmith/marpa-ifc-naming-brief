# Data Truth, Evidence, And Governance

The most important architecture decision is the truth model. Graftkit separates operational truth, data truth, source-code truth, and design truth so the system does not collapse into one fragile app.

## Design Truth

Vectorworks is the design and spatial authority.

It owns:

- geometry;
- design layers;
- classes;
- sheets;
- symbols;
- plant records;
- object context;
- the live design state.

## Evidence And Enrichment Truth

Pixeltable is the multimodal evidence and enrichment authority.

It owns:

- source artifacts;
- extracted text, images, tables, and metadata;
- embeddings;
- enrichment outputs;
- receipts;
- lineage from source to derived evidence.

Pixeltable is not just a database. It is where source evidence and computed enrichments remain traceable.

## Analytical Serving Truth

DuckDB and DuckLake are the analytical and snapshot authority.

They own:

- serving tables;
- analysis snapshots;
- reporting marts;
- model-ready datasets;
- reproducible financial and project baselines.

This keeps heavy analysis separate from raw evidence and live design files.

## Review And Modeling Surface

Marimo and AnyWidget are the review and modeling surfaces.

They support:

- what-if modeling;
- financial review;
- data quality review;
- operator approval flows;
- scenario controls.

They are not the source of truth. They are where humans inspect and steer the system.

## Repo And Work Truth

GitHub is the repository and project operations authority.

It owns:

- commits;
- branches;
- pull requests;
- issues;
- reviews;
- CI;
- project board status;
- templates;
- required checks.

## Source Intelligence Truth

opensrc is the local source-code intelligence authority.

Before the team adopts, integrates, or changes a third-party tool, agents must read local cached source and documentation first. This keeps the system grounded in real APIs, licenses, and behavior instead of guesses.

## Governance Pattern

Every important operation should have:

- a source manifest row;
- a lane owner;
- a schema or contract;
- a validation rule;
- a receipt;
- a review path.

This is how agent work becomes trustworthy enough for real project operations.
