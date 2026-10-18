# Repolex Knowledge Graph of thombashi/DateTimeRange

RDF knowledge graph data for [thombashi/DateTimeRange](https://github.com/thombashi/DateTimeRange), parsed by [repolex](https://repolex.ai).

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
rlex download thombashi/DateTimeRange
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7ddde34a09ad6e5432e27b4bea6171c39edb4792
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7ddde34a09ad6e5432e27b4bea6171c39edb4792
│           └── chunk-001.nq.gz
├── blob
│   ├── 02e5c185c5127c4ef67141caa276afa78523e1a5.nq.gz
│   ├── 0458649c0ef9c7e530307fbd4886a1fdf5960415.nq.gz
│   ├── 0886aa7ed9cc6b1605b7a965baa87dcdc3f742c6.nq.gz
│   ├── 11ecc9bb0ad3a78908bf81532f9016f2093429e9.nq.gz
│   ├── 1826cc07643aab04da7bee0c8647e6a47019a775.nq.gz
│   ├── 18ae94b9e116c0f52f18fc2a7d0050faf7b9b772.nq.gz
│   ├── 1daf61beb5f402a2321b3bd9d6d99d75919877ed.nq.gz
│   ├── 1e4148ab2397b9912d20a63c8625da4b8dad291c.nq.gz
│   ├── 204d9c0f5934a1a607a46a3b4c5c1fc1560cac26.nq.gz
│   ├── 22990d3a2d7c7df4c72c2b9105f2a101c4cd07f2.nq.gz
│   ├── 2825597e8fb3b6e3d99b9d033aded9fecfcdff58.nq.gz
│   ├── 282e98bad9cf185e172ec35a48e2db08b5860e32.nq.gz
│   ├── 2e02162a4b7eeeb0c8032e7a2212940e6100a0f1.nq.gz
│   ├── 2ebf5eccf21c91d0dbeaceb55bcd7a8efb738a34.nq.gz
│   ├── 3175260bca7da4ddbdc4cc58eab8b68e59d7efef.nq.gz
│   ├── 320c34693aad238b5f7d721ded532cabee1be749.nq.gz
│   ├── 3221974521de67f843121f8367f1f137ea5a3e0e.nq.gz
│   ├── 3502b74a380cf231e1c9085b281de9337aae7f9f.nq.gz
│   ├── 3e3c2f9d5e2bc9c160cda612c58f5fb61df672d0.nq.gz
│   ├── 3f27c9b21277cc8a5c29a0d2644fdd23d1f26a97.nq.gz
│   ├── 3f4d8bc54e35b161a0ba11b3a9bc544b381e9a95.nq.gz
│   ├── 4296962f71ce89a5ccc9581a18eabe6938eddff5.nq.gz
│   ├── 4e3eccdf2199d9866ee502d61fde1dc9eb247c0e.nq.gz
│   ├── 4e4f84b6c29037306cdb56e03e6c0172ed95719c.nq.gz
│   ├── 56e1747bffdee8b5a554326b22645c051cac7767.nq.gz
│   ├── 576b747f8703f1b99b5eda377f6908db7f9dc4c8.nq.gz
│   ├── 58fdc335f3924ab7acd316c8334eb531916075de.nq.gz
│   ├── 5c2067af0ee422c548e38ecc6ed1a838282661ec.nq.gz
│   ├── 5ecf844c74a01c954d6c03cfdf3074a58613f44b.nq.gz
│   ├── 6532c7e1fc3a419ae3e333768f0146c63c4c2b17.nq.gz
│   ├── 67d5665319ad2ed546572c64879439c1973897bc.nq.gz
│   ├── 6ae7668a174f735af6c973ae88d4ea4298ac9a36.nq.gz
│   ├── 6dd08416cb11100c3c023ceea8e44554b72cad2f.nq.gz
│   ├── 76cb8cb2741c2a9569d45793d505da296bc2de71.nq.gz
│   ├── 77d8ab536f11858e06e29d9d30f8f303cc940a60.nq.gz
│   ├── 79b0b8f4989e8b57332b1f604d8c0a28fb39871e.nq.gz
│   ├── 7cb44748a9429146ff6226b282731dce18604d56.nq.gz
│   ├── 7eb5c7d9fab8d030b7f11e88be54404944cfe9ab.nq.gz
│   ├── 7ed1fa79a0003e93b43deaf99ba6a5d3a2b8d899.nq.gz
│   ├── 7fc79a39ca9637f4d109656cd1fd3d97dbe94a4b.nq.gz
│   ├── 82f589592e796d19acc7d9ff99e5b9ae2b819520.nq.gz
│   ├── 864843172578946ed8b026966ba17a1145d20430.nq.gz
│   ├── 90e0d8f4e102cec6c26ab8293d76ea52e79744fe.nq.gz
│   ├── 95163a6aad2899e7141dc493f28ea3817e424ce3.nq.gz
│   ├── a437a6243c06ca509f3ee5ea478f5ba436ab593d.nq.gz
│   ├── a5d716cb1f05b9cfc912ba1d60df4cde55ecd55c.nq.gz
│   ├── a64099fd66867ba89d0d51e0b16b266cc282a25c.nq.gz
│   ├── aef509dc7396c5e3cf507eccc466ae55e2a8fe54.nq.gz
│   ├── b2964b911d347d09540318e456cb54f6fa604f7b.nq.gz
│   ├── b838d796e9dd8fcc7e2a15732e30d04bbfb1058c.nq.gz
│   ├── b849c942cc14919edbe890b7634b1a70a7b9eb6a.nq.gz
│   ├── b9883f90070861b08215b265b0ab8e9a57d17475.nq.gz
│   ├── c456af7054a90eb641908031259dfefe8b77ddbe.nq.gz
│   ├── c678d631e619a108f8c0ed2cdfea48e9c70ddf84.nq.gz
│   ├── c8616998dd0baf7d29f15da56118effcd348f17e.nq.gz
│   ├── c8a47b2a74be7c30b65902bc79ca8f4e2a8e56f0.nq.gz
│   ├── ced09e4c37958f8afe0f463ff3e5b197f8ab88a8.nq.gz
│   ├── d436c53fd64acec5804012992f51f27586e62682.nq.gz
│   ├── d92f948e3889b88ef0e7984b45154cd1eff80a8f.nq.gz
│   ├── db8e83c0af50baecf5e93b65f89db4f9cebc40db.nq.gz
│   ├── e33629049b8ce0ab38218f2b40330613b65efa0b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e76fdfbe4d6e684927d037c6a0f2ad05c507ba4a.nq.gz
│   ├── e9bf9b9f1ade15c9296d87381c4dea41d33d1d64.nq.gz
│   ├── f5a37babff4ae14ad0ce8ed0f60c3441c4b5b341.nq.gz
│   ├── ff0337c777c794a33c17bb39ba1ccec2c18bd5dc.nq.gz
│   ├── ff3fffe1960444d0bdeb5a88908f92011506ebe2.nq.gz
│   └── ffb4046012d124e90e730be7e25f1267021863f0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7ddde34a09ad6e5432e27b4bea6171c39edb4792.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 76 files
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

[thombashi/DateTimeRange](https://github.com/thombashi/DateTimeRange)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
