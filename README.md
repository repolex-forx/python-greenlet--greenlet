# Repolex Knowledge Graph of python-greenlet/greenlet

RDF knowledge graph data for [python-greenlet/greenlet](https://github.com/python-greenlet/greenlet), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download python-greenlet/greenlet
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c78342e6231a3f97633a5f0a39de9bb9bcaf8a99.nq.gz
│   ├── lsp
│   │   └── c78342e6231a3f97633a5f0a39de9bb9bcaf8a99.nq.gz
│   └── repolex
│       └── c78342e6231a3f97633a5f0a39de9bb9bcaf8a99.nq.gz
├── blob
│   ├── 0d8f53574d365b0756e580d9e41c3e5c2ecce2ef.nq.gz
│   ├── 106dcf61d6a6f4d2dc4695f02cdc3d7d27cee3fc.nq.gz
│   ├── 11cf5421399c25b04f7708b1e30c8f1e59149df0.nq.gz
│   ├── 125435f382ac1e5745b224d14ed5f7eb075121ed.nq.gz
│   ├── 150ec8be002236a06c609140864fcdb8a8d7acd2.nq.gz
│   ├── 1c9c70b045abf70e430d68a9314075d3c5108801.nq.gz
│   ├── 2773571426fd094615b3f3a67520dd81e860c6a8.nq.gz
│   ├── 2aa35f27e96c47165533f167fbb584495c3ef571.nq.gz
│   ├── 38b7ef4a502d459760cb3a4f07afca3dbfb7289b.nq.gz
│   ├── 38d6e391f91105771a59b157cd268f098b49b43c.nq.gz
│   ├── 46e330d504c287a34e09eb3d8dd95178989d418b.nq.gz
│   ├── 48111b781bc84e67aa1749e9871a55425b612d9d.nq.gz
│   ├── 4f3272876bb95c5ee7035655dcf8454d76b0c506.nq.gz
│   ├── 526a5040f6b35dd549c7a8a505c2fc549e530c88.nq.gz
│   ├── 547bdf62f6c7cec679b213f3c03264e7391f8053.nq.gz
│   ├── 57c497172971a932961f4b31b4b5097da30ff147.nq.gz
│   ├── 5ddebbcad5984f4be488a157e9ec73a301e27800.nq.gz
│   ├── 638343de16b32710299fa728c16b06e44f4a820c.nq.gz
│   ├── 63e5df984515d4968291d09aeb4c9215c24e284b.nq.gz
│   ├── 6e1286a9844531eea28a1dac608158b86ac1b6a6.nq.gz
│   ├── 6e8d0bacda4da0dca7e7ef9989a94a96eef61e06.nq.gz
│   ├── 75faf922ed639a238d8494ab5bc2e38fb699918d.nq.gz
│   ├── 7986125055299c84c0234c4b88ccd9b5f70abb0d.nq.gz
│   ├── 8d30e74391b09b4f0918f8782058bff1809e4081.nq.gz
│   ├── 8e18e7fcca17b3cb268973bc00ed9c3e2e4dd9c0.nq.gz
│   ├── 94b5489177db42b7fdea4105dd33aef719797d0e.nq.gz
│   ├── 9594e6247b10db3fb7116569c49b8b02ce82d59d.nq.gz
│   ├── 997adb0184fb05c53bd21f7500cc9b7250da95e5.nq.gz
│   ├── 9d911a103e7f9a93b8aa630643942d3e3ca3b78b.nq.gz
│   ├── a1e9855ef18552ff3ac736e3d324719d75ac5e0e.nq.gz
│   ├── a96c741e778dd5a4da3c7b2bcea17dd73190466c.nq.gz
│   ├── b5919c19de3bf99dd587ce1c6320c6ac116b6d12.nq.gz
│   ├── badae7fa2546703ec6a20b95cc69a793bfa6b940.nq.gz
│   ├── c7d2b4a66caef039c169fa7ba969f106cc5be4ac.nq.gz
│   ├── e6c7337bd18bfffde84e896efc1a70b63fb07b4a.nq.gz
│   ├── e80bb7edb047c2425af346878622318a558134e0.nq.gz
│   ├── eb1dc22c52ac4a67e9f60a954336e9183d24168f.nq.gz
│   ├── f1b1af083886bb35ac7403d7511c6ff23c81af8f.nq.gz
│   └── f34a0880b4fd8cc9d5b6c161e047083a2fe520e4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── c78342e6231a3f97633a5f0a39de9bb9bcaf8a99.nq.gz
├── filetree
│   ├── 475f83f05adf3bcd3d6a748ca812a6222ef2eecd.nq.gz
│   └── c78342e6231a3f97633a5f0a39de9bb9bcaf8a99.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |

## Source repository

[python-greenlet/greenlet](https://github.com/python-greenlet/greenlet)

---
*Parsed on 2026-04-01 by [repolex](https://repolex.ai)*
