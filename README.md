# Repolex Knowledge Graph of strawlab/iana-time-zone

RDF knowledge graph data for [strawlab/iana-time-zone](https://github.com/strawlab/iana-time-zone), parsed by [repolex](https://repolex.ai).

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
rlex download strawlab/iana-time-zone
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c6fe5ec58eb6989860c8ce137bc5b566c7232d9e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c6fe5ec58eb6989860c8ce137bc5b566c7232d9e
│           └── chunk-001.nq.gz
├── blob
│   ├── 0298321641aa3bb815e6d8a0897718a74970ccfd.nq.gz
│   ├── 0f5119f5669135092a21c5579dbd199fce6b91d5.nq.gz
│   ├── 14e8cf428a23bbf409a5e5539b30e80521904dd1.nq.gz
│   ├── 1740851de95bdec1cfc19ed143ad528ac7eb073c.nq.gz
│   ├── 17b099b10a7f657e6658333b010af5190ab1282a.nq.gz
│   ├── 17f1b974725b569d9abc036ed8539bde54f8acd4.nq.gz
│   ├── 18af3f6fe37a52d87b664fda93ba753c6cb91ac8.nq.gz
│   ├── 1a17f17f1d709fd450b1ef0435952c04be116611.nq.gz
│   ├── 1e6d707701021262111ca4130cbca9dc136e47c7.nq.gz
│   ├── 20b700316019b63ad632ad68824b947a2b8ef706.nq.gz
│   ├── 20e6d19f9f1dc7eb1828edd131895e8307bf608c.nq.gz
│   ├── 2566bdaf30aa614336ca3b40ef4663eebb4843af.nq.gz
│   ├── 27255b52f9ea1350d8f75977a821c00be4dbf66c.nq.gz
│   ├── 2988d9d23dd77134bdd743e0e2f4715dd8750159.nq.gz
│   ├── 309906c2c85f3e4c7b81236d50f0258081fa7999.nq.gz
│   ├── 39ebb02605c614447877c7c504206fcf7d7b56bc.nq.gz
│   ├── 444c17fd48a8891247292b652414110850cabeb8.nq.gz
│   ├── 4608be4c61411fc5c5cdcf981d34a6ae9ce4421a.nq.gz
│   ├── 4641c62ec49d39b06546954571318df79bb2e541.nq.gz
│   ├── 4d55e153698e5f0a9083507a3169962682e250e8.nq.gz
│   ├── 4fcc15c5d86607b524fdabb5d5bad8006198853c.nq.gz
│   ├── 57e233938a04797095ecc200aadafa87006a5e6d.nq.gz
│   ├── 69c36b5532a38d60c629dbd3166f16c7ffe77e7d.nq.gz
│   ├── 6c93d04a489fe0c343bd57b8d7378b20446cd649.nq.gz
│   ├── 6cd2193df19c1a217e797fdaf73e272dad53c724.nq.gz
│   ├── 73df86f51b6fd345a16d8d47b2e952dd0994d24f.nq.gz
│   ├── 76219eb72e8524f15c21ec93b9b2592da49b5460.nq.gz
│   ├── 7ef5d933900b3c696b8f917f7a35d6d5e709c890.nq.gz
│   ├── 84cf8b05ec71a1e174ca036cbe17bdc84a29b6f8.nq.gz
│   ├── 87450cdb901653fe0913f5870ec947db3ad000d0.nq.gz
│   ├── 8f0f4520ecdb1d8387ffada954d7a7e21987be40.nq.gz
│   ├── 8f8dd90d887c771cd77b3bc508d84892092a479b.nq.gz
│   ├── 965b606f331b51d566b46025f9ff311a7aad0c12.nq.gz
│   ├── a8b6f5906eee8c5e3ad93ac2c5fd60d754ee1e73.nq.gz
│   ├── a9d37c560c6ab8d4afbf47eda643e8c42e857716.nq.gz
│   ├── b032f33ffbe65bdd660f5147e8b6eef9ac851850.nq.gz
│   ├── b865579bcc18bcf8ff38dd6f0794f2e2a5d72146.nq.gz
│   ├── cc628be688d52e004c0bbb4eabbcd4e0237034ac.nq.gz
│   ├── d1c92cd3b7486889da348bae22d3591e0abc1963.nq.gz
│   ├── d78372b6d93f386d3cf861e5918d0d80ff826127.nq.gz
│   ├── ec783eba72e072c6a461ba1a265528109e762ec1.nq.gz
│   ├── ec9fdf1384ac02b80c4569aed76f0ee76eb2b25d.nq.gz
│   └── f974c2720be234c79f112be60187763ce09194f2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c6fe5ec58eb6989860c8ce137bc5b566c7232d9e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[strawlab/iana-time-zone](https://github.com/strawlab/iana-time-zone)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
