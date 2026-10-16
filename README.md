# Repolex Knowledge Graph of glue-viz/echo

RDF knowledge graph data for [glue-viz/echo](https://github.com/glue-viz/echo), parsed by [repolex](https://repolex.ai).

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
rlex download glue-viz/echo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 63265a279fc388ddbe44d67e5dce48d77bd086a6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 63265a279fc388ddbe44d67e5dce48d77bd086a6
│           └── chunk-001.nq.gz
├── blob
│   ├── 01e355ff9324778218de326afea6f50dc73c1c05.nq.gz
│   ├── 02e0b0c93b7b6ae5c83d33da8d60f75db4a5aba9.nq.gz
│   ├── 03ae3da90a5a6bacb3551174d303901be2dabc2d.nq.gz
│   ├── 06e69dcc61c578e3d2893829314b0bcf32ba5175.nq.gz
│   ├── 0e9be2576f0c4f0cf5c90f1650b03a693306c1e6.nq.gz
│   ├── 103a53e56f8bd8d1f16790e1664e6b9501ae77e8.nq.gz
│   ├── 1589a08a864d498b56d082cfa8f8c763be6da133.nq.gz
│   ├── 1715c953e0bc05bdf6a120e4dc3171e39c4bf681.nq.gz
│   ├── 1be4345e99dd9eefd14b3b1e73a435ed29b683c9.nq.gz
│   ├── 1caddbd5ee3b28d9687c20fa05c81977ebd00e62.nq.gz
│   ├── 29406a64dbf84ecf166dcb58f5ffbc52d2cee7e1.nq.gz
│   ├── 319b246def9d5f1ed8c346384f5a8b319ee85498.nq.gz
│   ├── 3bb2c601bb5a063d85494e479d35797d0731ddc5.nq.gz
│   ├── 423eaf7a33dc9a113554cbfb44ad1c13b674db1b.nq.gz
│   ├── 5451769072db37a23d1e37c4b6e24e969f2f614c.nq.gz
│   ├── 5530a0226d31c29e58510ed6b177b5df7afc2de2.nq.gz
│   ├── 565f136ce135a5d554d9bfde647783729b7a82fd.nq.gz
│   ├── 59d9f56cd7436ec83c5801d05a63c2734370df8f.nq.gz
│   ├── 5aa408e7493f01f52f1cfd00898be7e88be5cdd2.nq.gz
│   ├── 5ac1defbd301b665a638002b3bf026dc13e53b0b.nq.gz
│   ├── 69412a7a168fc8e23d1e34989443e0ff148fecad.nq.gz
│   ├── 6a47ca4abe84924ee06e6864be421aefc65256aa.nq.gz
│   ├── 6e94bd308f23f53d13ec823886d87e9e637f827c.nq.gz
│   ├── 71211a7bdf963ad3e622b7d1ec9c23a17df6e582.nq.gz
│   ├── 74f03a3314ff05d027a25611d80ef7125cebf0b0.nq.gz
│   ├── 764be2874b3632ee1118fcc66e3652824e14e65b.nq.gz
│   ├── 7a0994b6fda21900a42f1560499507928faade30.nq.gz
│   ├── 7dd30506e56adcb3b782a999023651823756c4a9.nq.gz
│   ├── 8070aa3d91975b8d867c6d1ea47f0979421c8b90.nq.gz
│   ├── 83641f31e48c4d343c9f8f747e61debbe40d2533.nq.gz
│   ├── 84d8edd1c185b1c156b7d0636d9b28681d226dde.nq.gz
│   ├── 8ce94d7c5384abd58c8b2db762b48192b56a774e.nq.gz
│   ├── 9309724cef54d6cc392c03df02f00a223ec4477a.nq.gz
│   ├── 981c753bb3115cc2c9bac7dcc16ed97bc7b44707.nq.gz
│   ├── aee5752d633bb85f3aba9b4e011a42b128f583a9.nq.gz
│   ├── b8702d894f2066015f4fa506b49702b88c41f819.nq.gz
│   ├── bd2095748303617aeb7813b65bf7da22f84e148a.nq.gz
│   ├── bf65e40bc2b1370be5b84f557edc3f669cbeee3a.nq.gz
│   ├── c0e1a2cf1236b82864d27e51d893712be373cb16.nq.gz
│   ├── c4a22169c0322cbad8d1ab197aeca41e255ff7d3.nq.gz
│   ├── c4dcd8da30d5133dbb5d9e106d9a957c140b04bf.nq.gz
│   ├── c4e6efbd25d70241e5c0cbcd37e00f2779747270.nq.gz
│   ├── cec72deb7effa612538a00c211ebe361e9b82e95.nq.gz
│   ├── dee1ee2e1d4b873ffec548db22388f61c7ede860.nq.gz
│   ├── e42ad955bc6c40e26cbf63ca93e024ffa8026ff6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e716ba6da53052b321fa950da09828eabb2226ca.nq.gz
│   ├── e89ebb177d73914cc203b0373ae3b6dcc8618913.nq.gz
│   ├── eb680006127d3be3329079d63ff6e0fa73912bfe.nq.gz
│   ├── f724d73bd6c63ebd6ad75d15a3f435b3a865649e.nq.gz
│   └── f839cb3807c9df0366bbc8527daf0488d17fbbb3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 63265a279fc388ddbe44d67e5dce48d77bd086a6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[glue-viz/echo](https://github.com/glue-viz/echo)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
