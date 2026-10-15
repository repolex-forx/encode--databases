# Repolex Knowledge Graph of encode/databases

RDF knowledge graph data for [encode/databases](https://github.com/encode/databases), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download encode/databases
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ae3fb16f40201d9ed0ed31bea31a289127169568
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ae3fb16f40201d9ed0ed31bea31a289127169568
│           └── chunk-001.nq.gz
├── blob
│   ├── 040a4346c972afb6050f69de2fe875ee7a8463fb.nq.gz
│   ├── 07bd188068ee420f68563ce7b23df3c258c87994.nq.gz
│   ├── 0b4d95a318736b08010bbd9f18907949e7bae144.nq.gz
│   ├── 0f4150ee07e58c08112a0d740546a1ae252bcbf9.nq.gz
│   ├── 139f8ffe546a546f4697ffc2a0faf2bbeec6adbf.nq.gz
│   ├── 16e17e9efdd94c9d284e4ea4bb1f1f1fde271f26.nq.gz
│   ├── 1c47d2cc2a5c9de1de2ceed00f1ae3819d579c4f.nq.gz
│   ├── 24158d1dab7426758642b9289a2322b3549b5652.nq.gz
│   ├── 2b8f6b68db2e217132cd79648439deebf50c37eb.nq.gz
│   ├── 2dbabde8a41ac0110b17b6a3488d1fb85e5e05ba.nq.gz
│   ├── 41c0c584d3f809a401885cf728a68f1a821d6dd8.nq.gz
│   ├── 4ac3beb7a6248488589ae932e29b2d291ca1d55f.nq.gz
│   ├── 642629afd0d6ecc61d39c0507eb4b03647a2fe77.nq.gz
│   ├── 654c22a115d7e9a2ff670e67e85e4a6915a6082d.nq.gz
│   ├── 65885a7208961207ed34c9659c21ac5ef0b90314.nq.gz
│   ├── 66201089fa1e015aa2a109489957742bf1b0b989.nq.gz
│   ├── 75c8ac707bd867c8d81170f0d82f3f6b954ae3eb.nq.gz
│   ├── 792f3685a1b1a97187c10d7c0256f6cf12d2b324.nq.gz
│   ├── 7aa15926dc8ffad9a4796f5603010dc705dfcee8.nq.gz
│   ├── 7c3cebf27a6006e7d62f7ed06430934df5ce336a.nq.gz
│   ├── 81a348819256927f8bbcf79a6fb0878766d56458.nq.gz
│   ├── 81ce2ac77641cd7c88e3d805a591aeeee0f1f9c7.nq.gz
│   ├── 8963b9f219aedbc1bfa78a0b4300764db95abe76.nq.gz
│   ├── 8b05a46e03ac7260d3738d27b7ca398d66ebb1d6.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 92ab3b3ce0bdf23a53fe31727494e670ffcc3695.nq.gz
│   ├── 943d48a3e12b7b974cbc4d2e2ec48f39e7e7d1d4.nq.gz
│   ├── 9c70a0747fb41c814ea18fb4eb1cdf0e50ddd80f.nq.gz
│   ├── a8dd50fe3855fadb425b5462e29ddd4726aa60b8.nq.gz
│   ├── b003e559250b225da0e350ff143024737a4a6290.nq.gz
│   ├── b4182c83698c7be325722694f78f9140e4cbd825.nq.gz
│   ├── b9038ca113b22b96ace2812d6412914a3541eed7.nq.gz
│   ├── c1b56e3f81e541555d44e2c67bcd7c4981a75ba1.nq.gz
│   ├── c42688e1ca1a6295e7f88fb0442e502c26aaa168.nq.gz
│   ├── d55dd3c87dd97f9ddc61333aa19a4985d66ab72b.nq.gz
│   ├── d7388629ec2fb5399151348df6aa22b4c99d68b6.nq.gz
│   ├── d9d9e4d63f8b5f70038c40e3209fe47cb6829b30.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e739098449f43637081d8ea0d5805d3a6e9f9283.nq.gz
│   ├── e871360d1642bc3ac222718fa735b9daee6dd0fa.nq.gz
│   ├── e8ef017464af1dc3dbc500985d3301ddc34b069a.nq.gz
│   ├── e963af500c5fa52743f93f5aa3beeab469e3dc13.nq.gz
│   ├── f40cd173574e9d789057c05829f4ff03ae5139ba.nq.gz
│   ├── f680782ef7ab570c838a60ccc3fbf1322bca0d9a.nq.gz
│   ├── f85ca99af2d77f8ba151d1587c67e912373ee0a7.nq.gz
│   └── fd6a24ee823c663f76fe73d97924152a280d4625.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ae3fb16f40201d9ed0ed31bea31a289127169568.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[encode/databases](https://github.com/encode/databases)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
