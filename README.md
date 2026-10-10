# Repolex Knowledge Graph of pypa/pyproject-hooks

RDF knowledge graph data for [pypa/pyproject-hooks](https://github.com/pypa/pyproject-hooks), parsed by [repolex](https://repolex.ai).

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
rlex download pypa/pyproject-hooks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 184c9f56a87ede1276a5b33f5024204adb792cd2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 184c9f56a87ede1276a5b33f5024204adb792cd2
│           └── chunk-001.nq.gz
├── blob
│   ├── 015f38987970e251e213906872b87a0648364cd2.nq.gz
│   ├── 01703d62e18d830769a01e53e48c655cc6ecd4b6.nq.gz
│   ├── 03e8d8acd1832851c60cd38059eeaf2a502e16bf.nq.gz
│   ├── 1612133227dab90a075b521cc9dd141511405014.nq.gz
│   ├── 17c923233267e58d2773014ea4b32afca748170b.nq.gz
│   ├── 1b7eb83261fe1a3aba8e5b459a5eb5e18f7f0c71.nq.gz
│   ├── 22d558825c8e67800d16fd09c762ef0f79187098.nq.gz
│   ├── 31e56a9387225da7bd9490d83194a5d7dcfa653e.nq.gz
│   ├── 39f163ead6a9d308eb0c31c96fe090671ae8a57d.nq.gz
│   ├── 3cf0848203a388a7c81797b4af96d96140b41a83.nq.gz
│   ├── 3f5b51fca9a76c030eb0813c07494805852cbcdf.nq.gz
│   ├── 45d3dbd3e7cc86615472812a926a1fe57e196f58.nq.gz
│   ├── 4a8c47a652c2492470ec4bd496dbebca4fe36ec8.nq.gz
│   ├── 4db6d0b231bab0f2303dca9f779d2e108910f5b7.nq.gz
│   ├── 58c03f3ef4d1a4604e0c2434c1c1c4760bfaccfb.nq.gz
│   ├── 5d8336a60bbafe00b8bc475ac2ea1fea1ba7de41.nq.gz
│   ├── 662121ee2838a58dc5c50481c5e94b72b898307e.nq.gz
│   ├── 696e21509178202aef99498957b832317f17acb5.nq.gz
│   ├── 74e8cbff989eed66f7a389384f872b1303caea78.nq.gz
│   ├── 7bf2758af90c685ac54c8d9868806a4af2c9148b.nq.gz
│   ├── 80a0de7a6d060b56238d9c9460c6af8b4d02ed89.nq.gz
│   ├── 8d6acd89e3cb9276cb3436ae310b1a1dbf91b689.nq.gz
│   ├── 8e6e0f487a9dc42b93d4903ce5df9d96d4f2f02d.nq.gz
│   ├── 906d0ba20e1f3e10b35456c2db1f207a071ce246.nq.gz
│   ├── 9285903b13f2cd9e0017bf400cb5074f6a06be93.nq.gz
│   ├── 966aef5b7ac1a5c1553149b228124d7be0629adb.nq.gz
│   ├── 9748082f6a1e672e8e5d382c5541d19159e151c3.nq.gz
│   ├── 9787c3bdf008a57ae3cb2e27a8261eb3f134ff73.nq.gz
│   ├── 9b9d43a1514f2250b198b13ee81687aff7c2f282.nq.gz
│   ├── 9d03f0ac1bda3d3f5bb08ed8f39a7d4691eda94b.nq.gz
│   ├── 9f359b8c227828233f730b089b1aa85451344879.nq.gz
│   ├── a10e1e27213ff6c0ba6c2f154675c1ff4a7ca6e2.nq.gz
│   ├── a44147ba5a873e96e7641e0083b9c01a06cb643b.nq.gz
│   ├── a6245de71035b6e209b841d575914df9c7e81831.nq.gz
│   ├── aaf174be5266871a83ceec7cc525eb24c57e2e86.nq.gz
│   ├── abbbff7df4dec63344d42eac3876dde6aa1309ea.nq.gz
│   ├── ac7c1d8cfdab05b005e383bc8ea0634d286b1bd3.nq.gz
│   ├── b0ae9dbc262b5f7ed4cb6f964cfb5eb5c0d0b0be.nq.gz
│   ├── b8e37ac584c4e2a6dabc55ba6deef1d2fede296b.nq.gz
│   ├── ba6439cd564942980674d2a3ad9ea9545b400e91.nq.gz
│   ├── bbc5c145609f4413cd9987e037e78820e3fcc9c3.nq.gz
│   ├── c06d7fe292283f27aae989ab8fda4e48ac90e721.nq.gz
│   ├── c0d1a0b25d414819d9fb4ce26e3b143270249816.nq.gz
│   ├── c60ebaae95af526ca4439fc40feb9c35fbae6a79.nq.gz
│   ├── cda18b2ddc56e73f4cd6b07b97480b389bf7a2bc.nq.gz
│   ├── d54d9863d6f28be2b983fd380436266ce012bffc.nq.gz
│   ├── d62a9c9464ce156316ae211f0b58160071c434d9.nq.gz
│   ├── d8b9816335735fe0dffd48dd150b71fcf9b58f92.nq.gz
│   ├── d8cd97708a8b01b922cbb20e1d7834882beecce9.nq.gz
│   ├── dc4bd765b8d8df7e88522881f344005f44a0d452.nq.gz
│   ├── e122de19b71ca19307a2ecd0d4b2ffece414be02.nq.gz
│   ├── e4d3d2e8e541d600bed5fe2fca74d084cb2e8869.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9e45dda233464c19b9a837f4f98450597926998.nq.gz
│   ├── f1b3de5d742a2d7a45639fdb1cda38f07f5e9f27.nq.gz
│   ├── f6e8598da076303070c9b09615c8ebb8ff4d9769.nq.gz
│   ├── fd16f4b345f359bf15d2af47bd96ee2454608737.nq.gz
│   ├── fd1a503069cc0e4e9bd5872bc16c126ed2871607.nq.gz
│   ├── fd4e8cba7d49d08d2aa981508054f42dac12c456.nq.gz
│   └── fdd977350ce2add199e816c90d20ca38728c89d1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 184c9f56a87ede1276a5b33f5024204adb792cd2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 68 files
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

[pypa/pyproject-hooks](https://github.com/pypa/pyproject-hooks)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
