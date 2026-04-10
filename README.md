# Repolex Knowledge Graph of gotwarlost/istanbul

RDF knowledge graph data for [gotwarlost/istanbul](https://github.com/gotwarlost/istanbul), parsed by [repolex](https://repolex.ai).

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
lexq download gotwarlost/istanbul
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eecc799dc3a78db50a39b1f51f31c1517858c3ae
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── eecc799dc3a78db50a39b1f51f31c1517858c3ae.nq.gz
│   └── repolex
│       └── eecc799dc3a78db50a39b1f51f31c1517858c3ae
│           └── chunk-001.nq.gz
├── blob
│   ├── 02242fe8ff343902bf88c887665662b5f25479ad.nq.gz
│   ├── 0384459b59e783a5ad2afd26d444f51d08882166.nq.gz
│   ├── 03c3bce1ea36d0ea6ae4d74a09ea605943e6e694.nq.gz
│   ├── 08a5239d8d2e05e89f57904aa59f5719a74e1c0c.nq.gz
│   ├── 08c4f076497669eeca657ea840d22d9f359b0a64.nq.gz
│   ├── 0e908f5ef954a4f2e6d06dcdaee7957b960c6ed4.nq.gz
│   ├── 10cf07e9f0afcfcb588d5c1c5b1fabfbb0b227d8.nq.gz
│   ├── 13b754114bc102dea41fb5d7da1825a7794683a3.nq.gz
│   ├── 1754edbdd6fc0959ea27d92f3a9497a81be1d483.nq.gz
│   ├── 1a41e6e7311c2a70d118454c7125509379c4b767.nq.gz
│   ├── 1a6e5172bdd4e432ba4c9133894e9e0fd4e05bd6.nq.gz
│   ├── 1d35f382aa800e6c50b8227d780c192da51ddd1a.nq.gz
│   ├── 28ce2860f17596f3ad4ca5b47398338aad86a9b0.nq.gz
│   ├── 2ed1250d9af3d7b0ed3a007970035c8e19e63f19.nq.gz
│   ├── 2ef267e25bd6c6a300bb473e604b092b6a48523b.nq.gz
│   ├── 301566e7f3deb23f6435611d74ea3322a878dc00.nq.gz
│   ├── 3be24e938de86f95d03604c7f02c767eed4f9a05.nq.gz
│   ├── 41d0f12f7dae9f03720ef14d9b27fe04558117d4.nq.gz
│   ├── 44acae2335f340e8e993e1b85fd57053711cf00a.nq.gz
│   ├── 45a650b051e6d0fe169f58291c93227144a7ebc8.nq.gz
│   ├── 488b71a0d3e8a5adcfe920dd6c736d5340859efc.nq.gz
│   ├── 4ee09297caf30a69779ff3a445b1c746339b4b96.nq.gz
│   ├── 51b9e1a41add94af3e517abcfee2c9aa164747bb.nq.gz
│   ├── 525ff3f6b23183996d19bb16ff68374bbf47232e.nq.gz
│   ├── 5a8f1bfca5cb73743976cb7b9c03865620a74e3c.nq.gz
│   ├── 5e6b0a6bf2ebfb0eafcaebe712b43b8e397994bb.nq.gz
│   ├── 644617edfca84439c8bac7203560952eccd2ad62.nq.gz
│   ├── 68ef3e525880b570fd292a08e28708ff40fc6a50.nq.gz
│   ├── 69269a92f2a3af0423850dc0b280909dc6491c0e.nq.gz
│   ├── 6a7f5c08d2fe8d115b6084aba1f67d75a62002eb.nq.gz
│   ├── 754cf1d0da13a321d80a59e8c94110a4e4da7b03.nq.gz
│   ├── 7711fc17d8825bb915e5eff4c95a7c225e46ea59.nq.gz
│   ├── 7d683f02fc286941aaa388b2feebfc00b1e5a818.nq.gz
│   ├── 7f3002c5557aafba305fd03c9d82be1c6ea359b2.nq.gz
│   ├── 819f54262dc5b8b081d307c6fc30c8bccfdbf715.nq.gz
│   ├── 86862ba5146a33a4d02e644121c22c508f7d5e81.nq.gz
│   ├── 89de43d270d29bb262345275444d3670ea9632ea.nq.gz
│   ├── 8cd590cd0890badc1d315b0de6ee521ff93d4573.nq.gz
│   ├── 8d9136acfc9aff7deb904b4c1a2a08a2cdc18d7a.nq.gz
│   ├── 8ed33a888f3a35632279d9b309b611f70fe79264.nq.gz
│   ├── 9ebda93e259dacd38acd74d11eba400475659cf5.nq.gz
│   ├── 9ef34a975294f25f9623c1e2429d1b9ea21b8029.nq.gz
│   ├── 9f3d6f36faaca9cca09b4edd8deba95f3be8be91.nq.gz
│   ├── b00a7d5143cc142573eefed6579f41fe00a9f77b.nq.gz
│   ├── b177d88907e5bd07899c686bb99790cfd44de6e4.nq.gz
│   ├── b3c086e6557bae2510c3e92c573ee8e303e524a9.nq.gz
│   ├── b3d914b4e1970831bf1a1afa8a48b99f0436c648.nq.gz
│   ├── b89c0319842efd485cc7ae67cf6cbbc138418142.nq.gz
│   ├── bb0cc2ea4a171ab819d379b7488c73a0ce965a69.nq.gz
│   ├── be85fea47b4974e477e007ccc56f8202a1a8d32a.nq.gz
│   ├── bed3a5c5248bd257e42b11cb9fd346880fc197bd.nq.gz
│   ├── c190b4008691e1d8c8cd5ce5ee27d26bb0ea651f.nq.gz
│   ├── c1ae51ffe09184197f2c56ecde10031e48769198.nq.gz
│   ├── c2db3a3f300fa49d6366b2cdbed059319041d1c8.nq.gz
│   ├── cef02c6b3a16e89c76e4257ca99a109a398e030d.nq.gz
│   ├── d282bc9e74ebb8dafacb658d84586b6ffe780ff2.nq.gz
│   ├── d81fa29bb8816ff14f2b9d73bff2ecfbfd590494.nq.gz
│   ├── dcafdcd0557ecf9e8e7187054562390ef1ee9eb5.nq.gz
│   ├── ddf342489be2ef0e67b8b779b1cbb83eeaa0fde8.nq.gz
│   ├── de2e7a3326b20ae30cf1ee711bd58cd4ad4b74e2.nq.gz
│   ├── e1cc6a7d0c4b34663ffb5e31896202648efe6b92.nq.gz
│   ├── e32eaf1862587cd4ed82b2df78b5660180d8685d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e83feb0b28810f3a27af2e821a22cc0a3f3be620.nq.gz
│   ├── eb61900be89698eae7a6fe69a61a7b2f88befa64.nq.gz
│   ├── f1f24efe7bd8eed0db2ac05c9a0830c144d297df.nq.gz
│   ├── f2f85c90ca47b4272a8abd94a1cd6f291da2f859.nq.gz
│   ├── fa750a0a82af0804aae639a1d1affa3769724110.nq.gz
│   └── fedf1498e1e17fc32711fdc7964d90097727a78b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── eecc799dc3a78db50a39b1f51f31c1517858c3ae.nq.gz
├── filetree
│   └── eecc799dc3a78db50a39b1f51f31c1517858c3ae.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 79 files
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

[gotwarlost/istanbul](https://github.com/gotwarlost/istanbul)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
