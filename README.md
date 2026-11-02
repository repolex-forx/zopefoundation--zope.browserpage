# Repolex Knowledge Graph of zopefoundation/zope.browserpage

RDF knowledge graph data for [zopefoundation/zope.browserpage](https://github.com/zopefoundation/zope.browserpage), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/zope.browserpage
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c71bcd592c426096ea7bca790a17833a0e0529e6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c71bcd592c426096ea7bca790a17833a0e0529e6
│           └── chunk-001.nq.gz
├── blob
│   ├── 064a6fe195889fa90a73621206818352aaa69608.nq.gz
│   ├── 09e2f0f50e397ed49b16ad9a35992095608808f1.nq.gz
│   ├── 0ab12fe1e0c8eb6cb0d68fce1b14a2209cdb0def.nq.gz
│   ├── 0dc101b533592aaded3daf80d36952771f1f821f.nq.gz
│   ├── 100377d684ee682f484cb3131e8b16c710943c42.nq.gz
│   ├── 12edc3e20c8bcec708ecbd279b0107cb4ef1ee3f.nq.gz
│   ├── 16d3b0606e03b3a50b86147d9c67ba243da050ff.nq.gz
│   ├── 1f321f52abb7db6f79c285bab56e2852dc575699.nq.gz
│   ├── 2080bd6c02c74140712426f5bc5eca012567357d.nq.gz
│   ├── 2cbe9455a8c4eb0e1e44d7e326406651e901d40c.nq.gz
│   ├── 3b510a735687fb87918c56d8b3e8367f393f49b5.nq.gz
│   ├── 4a0d10aa9faa209996665a023b46165f5c68f8b1.nq.gz
│   ├── 51b3fb826b5aaef41ad9667d8545cd3c1e8e890b.nq.gz
│   ├── 539cfd8756e82be74f80703403cf1476972022e5.nq.gz
│   ├── 548e245b9cd4b4d1cf7e24b31f480f02ea077e61.nq.gz
│   ├── 605e21405702e8c1638fd02ffe664dc11129ffbe.nq.gz
│   ├── 6d88f0671bf82c5f17845eb62cf88d9176d12d18.nq.gz
│   ├── 7358b1055366a48b30e07534f680308d5d681939.nq.gz
│   ├── 7540be1cca3f4ae88e5cbef51319feaa2ae5a7a9.nq.gz
│   ├── 756cbe027540b6a1db0a80425e67cd768a756f49.nq.gz
│   ├── 792d6005489ebee62cde02066f19c5521e620451.nq.gz
│   ├── 798532def0c2f38d3994f812006b2cf157701a62.nq.gz
│   ├── 79859e06010bf4967c5b4b044afea6ef39742938.nq.gz
│   ├── 967307f74a0c9ac5cd0f33f9c147600aaaf9d28c.nq.gz
│   ├── a433cd2d7961efffbbf28eaaacbe171a0b3ff087.nq.gz
│   ├── a4579f51e838f11525215313f9850e4208609ba1.nq.gz
│   ├── b6b2e15e1fbecd2527520a7fef33367b1e0785c8.nq.gz
│   ├── bce82ae87e6f8b16d23160a871dc30fe57a30ce4.nq.gz
│   ├── c031f67a638a8257f9a86c05ad13ab10611c0e4a.nq.gz
│   ├── c0bc55cba79b0c8d6afc5205d5613f760ba45c74.nq.gz
│   ├── c3e10f4a8b75f4e4e721301bf35afe30868394cf.nq.gz
│   ├── c3eb524467bd819a56b25d1393f40a7081db9cfa.nq.gz
│   ├── c5508b9f083362a81185d598327e7801d837cb18.nq.gz
│   ├── cfec5c9ab5c4943cd501ee55b132f62dbb3ee428.nq.gz
│   ├── d1ba5ff79fce4adc8436dfef56984b2c33a14f11.nq.gz
│   ├── d32bd0e67df74c1a8a8f80a2d41e1e768567008e.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e2f465116c2faa231ab9024f777f6e995a3e86ca.nq.gz
│   ├── e86fc9aec1c24084963422a17bee84be31c2ec18.nq.gz
│   ├── fc020d17f83072b9a3dc58831febfcb3a6c6100e.nq.gz
│   ├── fc1cff2f84549e683f6c9e51226a30c6c00545e0.nq.gz
│   └── ff77ae62e5f620bc7cd67b23c157a050bd380320.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c71bcd592c426096ea7bca790a17833a0e0529e6.nq.gz
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[zopefoundation/zope.browserpage](https://github.com/zopefoundation/zope.browserpage)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
