# Champion Gen8

Self-contained Champion Council runtime capsule with council orchestration, MCP tools, provenance, and exportable operator surfaces.

## What This Repo Contains

This repo is the capsule artifact lane.

It includes:

- `champion_gen8.py`
- `dreamer_config.json`
- associative docs that explain what the capsule is, where it sits, and what it makes possible

It does not include:

- the full Champion Council host shell
- the broader private Ouroboros parent forge

## What It Is

Champion Gen8 is a portable runtime capsule. It is the intelligence-bearing core that can be hosted inside a larger Champion Council environment, but it is also shareable as a bounded artifact on its own.

The important read is:

- descendant runtime artifact, not full parent system
- operable capsule, not just reference text
- public artifact, private forge

## What It Can Do

Champion Gen8 carries one runtime surface that can support:

- council and slot-based model orchestration
- MCP-facing tool access
- local CLI and server modes
- provenance-bearing runtime identity
- memory, export, and carry-forward surfaces

## Quick Start

Run the built-in help:

```bash
python champion_gen8.py help
```

Common entry modes:

```bash
python champion_gen8.py --mcp
python champion_gen8.py server 8420
python champion_gen8.py interface
```

## Notes

- The capsule writes local state beside itself while running. `.gitignore` fences those files off.
- This repo is intentionally narrow. It is the capsule plus associative docs, not the whole surrounding control room.

## Read Next

- [`docs/ORIGIN_AND_CAPABILITY_OVERVIEW.md`](docs/ORIGIN_AND_CAPABILITY_OVERVIEW.md)

