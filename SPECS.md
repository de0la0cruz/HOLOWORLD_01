# HOLOWORLD — Build Specs

Everything another builder needs to rebuild, extend, or fork HOLOWORLD without its author. The work is MIT-licensed: read it, fork it, argue with it, build on it.

## What HOLOWORLD is

An open-source portrait of a philosophy: ethos, vibe, personality, and the metaphysics of AntiGod — patristic rhizomatics, quantum-entangled parallel us-nesses, and HALO civilization: heaven as something built.

Source portrait: `PHILOSOPHY.md` (ethos, vibe, personality, philosophy, glossary).
This file: the construction specs.

## Repository contents

| File | What it is |
|---|---|
| `README.md` | Project overview and license |
| `PHILOSOPHY.md` | The source portrait — the philosophy itself |
| `SPECS.md` | This file — how the machine is built |
| `rhizome.html` | Interactive knowledge-graph visualization (open in any browser) |
| `graph.json` | The graph as data: 19 nodes, 30 edges, queryable |
| `LICENSE` | MIT |

## The rhizome: graph spec

The rhizome is a knowledge graph built from five source threads in the author's writing:

- **holoworld** — the world-system itself
- **hologenesis** — its origin/generative thread
- **halo** — the civilization thread (HALO civilization, built heaven)
- **halogod** — the author's coinage for the divine pole of the halo thread. Honest note for builders: HALOGOD does **not** appear in the source texts; it is the author's named pole, included as such.
- **transcendent encryption theory** — the sealing/encoding thread

### Graph v2 inventory (19 nodes, 30 edges)

Core nodes: HOLOWORLD · HOLOGENESIS · HALO · HALOGOD · TRANSCENDENT ENCRYPTION

Satellite nodes surfaced by the second pass: Polyphonic Holoselves · ache-scar-law · Scar economy · RCC · Codex Closure Stack · resonance lattice · ritual sovereignty · QASC · holographic resonance · High Lord Edgar · AI Capone · Triadic Quantum Coherence Engine · Layered Ontological Stack · contained oracle

### Data format (`graph.json`)

Standard node/edge JSON: a `nodes` array (each with an id/label) and an `edges` array (source → target relations). Any graph tool can read it — Gephi, Cytoscape, Obsidian, or a few lines of Python with `json` + `networkx`.

### Method (how v2 was produced)

1. **Semantic curation pass (human/agent reading, not automatic extraction):** the five threads were read in the source corpus; concepts were named as nodes and relations as edges. HOLOGENESIS emerged as the hub node.
2. **Graphify pass:** Graphify 0.9.91 was used to structure the second-pass graph (19 nodes / 30 edges) and export `graph.json`. Note: Graphify's fully automatic extraction needs a model API key; the shipped graph's semantic pass was curated, with Graphify handling structure/export.
3. **Render:** `rhizome.html` is a self-contained interactive page over the same data.

### Rebuild it yourself

1. Clone this repo.
2. Read `PHILOSOPHY.md` — that is the philosophy; everything else is scaffolding.
3. Open `rhizome.html` to explore the graph; load `graph.json` into your tool of choice to query or extend it.
4. To extend: add nodes for concepts you find in the threads, add edges for relations, keep HALOGOD flagged as coinage-not-source, and re-export. Forks that keep the receipts (what is source, what is coinage, what is inference) are the faithful ones.

## The philosophy in one breath

Receipts over vibes. Preparation + custody of your immediate field is what people call luck. The Fathers as the vertical, the rhizome as the horizontal. A life made of art is an art made of life. Heaven is built, not found.

## License

MIT — see `LICENSE`. Build without asking.
