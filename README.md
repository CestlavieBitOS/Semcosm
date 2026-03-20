# Semcosm

Semcosm is organized as a layered repository for stream processing, event abstraction, entity-state modeling, semantic compression, and narrative or self-model reasoning.

## Repository Layout

```text
Semcosm/
├─ docs/
│  ├─ architecture/
│  ├─ layers/
│  │  ├─ L0_raw_stream/
│  │  ├─ L1_event_segmentation/
│  │  ├─ L2_entity_state/
│  │  ├─ L3_relational_causal/
│  │  ├─ L4_semantic_compression/
│  │  └─ L5_narrative_self_model/
│  ├─ adr/
│  ├─ glossary/
│  ├─ protocols/
│  └─ notes/
├─ specs/
│  ├─ tla/
│  └─ mappings/
├─ src/
├─ tests/
├─ examples/
├─ tools/
├─ schemas/
├─ configs/
├─ artifacts/
├─ bench/
└─ .github/
```

## Top-Level Directories

- `docs/`: human-readable documentation, architecture, design, and roadmap material
- `specs/`: formal and semi-formal specifications
- `specs/tla/`: TLA+ models and related material
- `specs/mappings/`: mapping definitions between specs, code, and artifacts
- `src/`: source code and runtime assets
- `tests/`: automated tests
- `examples/`: runnable or illustrative examples
- `tools/`: development and maintenance tooling
- `schemas/`: data schemas and interface contracts
- `configs/`: project and environment configuration files
- `artifacts/`: generated outputs and packaged deliverables
- `bench/`: benchmarks and performance experiments
- `.github/`: GitHub workflows and repository metadata

## Layer Model

- `docs/layers/L0_raw_stream/`: raw stream layer notes and design material
- `docs/layers/L1_event_segmentation/`: event segmentation layer notes and design material
- `docs/layers/L2_entity_state/`: entity-state layer notes and design material
- `docs/layers/L3_relational_causal/`: relational and causal layer notes and design material
- `docs/layers/L4_semantic_compression/`: semantic compression layer notes and design material
- `docs/layers/L5_narrative_self_model/`: narrative and self-model layer notes and design material

## Documentation Areas

- `docs/architecture/`: system architecture diagrams, module boundaries, structural views, and project-wide design standards such as SOSP
- `docs/adr/`: Architecture Decision Records
- `docs/glossary/`: project terminology such as stream, record, ref, and owner
- `docs/protocols/`: external interfaces, protocol definitions, and serialization conventions
- `docs/notes/`: drafts, derivations, and research notes

## Key Documents

- `docs/architecture/SOSP.md`: Structured Object Specification Paradigm (SOSP), the project-wide object specification and documentation governance standard

## Working Rules

Keep new project content inside the existing top-level directories unless there is a strong structural reason to add another root entry.
Write human-readable design intent under `docs/` and keep formal or executable specifications under `specs/`.
Place implementation code in `src/`, validation in `tests/`, and operational helpers in `tools/`.

## License

This project is licensed under the GNU Affero General Public License v3.0. See `LICENSE` for the full text.
