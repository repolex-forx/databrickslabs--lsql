# Repolex Knowledge Graph of databrickslabs/lsql

RDF knowledge graph data for [databrickslabs/lsql](https://github.com/databrickslabs/lsql), parsed by [repolex](https://repolex.ai).

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
rlex download databrickslabs/lsql
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1c2eb7a185816890820124a5d7d8e388f53f7ddd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1c2eb7a185816890820124a5d7d8e388f53f7ddd
│           └── chunk-001.nq.gz
├── blob
│   ├── 00509c93aae1bc29165f9e74df910454e84142db.nq.gz
│   ├── 00580903f0a4829b27d2514e665f07273eb930f6.nq.gz
│   ├── 0070e6d5fa4f40d8172158f699361adf33c28d93.nq.gz
│   ├── 027449f9cd9b23f040f3966cb0fb7b215ed764f9.nq.gz
│   ├── 02ab905749923184cebd1a972d6cf85a2dbb7e0b.nq.gz
│   ├── 060b3ec97cafad359cb7824105d2f98ed31fef96.nq.gz
│   ├── 09b0eab27d2df09f033d1c3494908ab8f72f2eb4.nq.gz
│   ├── 0fbc313118b78bd5020be38c6a959a565d63df13.nq.gz
│   ├── 10c90570126804c53694189ab6b0da7d4cc726f7.nq.gz
│   ├── 12bffeda80514781a61a573350bf3b590bfb7ed8.nq.gz
│   ├── 192dbd3f115dbd8acab0bc7872c6f4ea0e62a090.nq.gz
│   ├── 1a8bb2d6afb06e3255c527c51b23b61b9447ee14.nq.gz
│   ├── 1b2c8ce2b0eb98d2c4a4c04f4ab7cad105b79f95.nq.gz
│   ├── 1b644946d4e507b3f78caadbc62cc48c8d0a90ab.nq.gz
│   ├── 1e369423320a5e99ace58389ad81f1b602cc6438.nq.gz
│   ├── 1feabe07b8ff69136aafd753bb13783442e854e7.nq.gz
│   ├── 2aa90b7ec67c5c3696cc3da0fc6e8e6a2bbada3d.nq.gz
│   ├── 2bb2cfafcb7df5674a915d37a765ddcf4935e40b.nq.gz
│   ├── 2ec33da3dd2410a6e7bd4a3c936848fe81fd6a85.nq.gz
│   ├── 2f1c01f935023c4b925ec2c9930f7ac626e72949.nq.gz
│   ├── 368c7c1db17858b572896cc62032cd128f5b6b86.nq.gz
│   ├── 36a1beac2ae702cc8b77d9208320fe2ef6b08550.nq.gz
│   ├── 36d0eed7dade41c3c8ed3f65e69e72e8e3fc1e73.nq.gz
│   ├── 4204b2abdf6bd10ee90a53d13c84e2715d910637.nq.gz
│   ├── 44e010410eabcfb1799d9ed165c900a0b9ecec5f.nq.gz
│   ├── 4547458e2c5b72b6f333bfe43c26d5a6709269a4.nq.gz
│   ├── 5b4e5411be260594ca022b87dedc3485a22a1fe8.nq.gz
│   ├── 605bb201b1f608ce507c013e3708baf13569dfc7.nq.gz
│   ├── 687d652052e3e901d01d7440ba61db8153fd5956.nq.gz
│   ├── 6a5ab856a4217409898f5cfedf119990069a5dc8.nq.gz
│   ├── 6fdd37ea6f3fa5a4348c09c2386ad8fb929b84f5.nq.gz
│   ├── 731adc9416ab6f1bed306b9c46eab56a6a34bce7.nq.gz
│   ├── 7a1098b2e56b0ac3f7410da2847966a187deeeef.nq.gz
│   ├── 8179235bbb83735d64c06c45a034d265997a8d0a.nq.gz
│   ├── 8752d5379ada0a24bd1ab83357bb60c3c8206e3b.nq.gz
│   ├── 884945c078022c2a8d4983eb309ab19c4d4507df.nq.gz
│   ├── 88908df848d014a14691660a948dafe069425ca8.nq.gz
│   ├── 898bee3c0ff6f836df2e97435c5b53142ae74cdb.nq.gz
│   ├── 8c8e26224cbcd9e82ecf0d40b4e4452701b836a1.nq.gz
│   ├── 90c4472751df3a9f2d57fb9b215cbb8326a6db59.nq.gz
│   ├── 91c72d8b10047303e1388e1e8dd3ccb97f467bd7.nq.gz
│   ├── 92b617ebd22ea139c2ec4029f9191c056464d71e.nq.gz
│   ├── 93d9a5a013c94bc52c50de13a97ecccd3bf941e2.nq.gz
│   ├── 94f85f0a9bfa42077797a39e05186ccd4b823205.nq.gz
│   ├── 96c449df133687dbe93c6d669511ae89750aeb10.nq.gz
│   ├── 9f5ce7176add0ec094f051a4c2145abb9e6b7d62.nq.gz
│   ├── a03e0197e89caf1aa213c34542dab2888cc080bc.nq.gz
│   ├── a4fb64e288cf1d3d72a6477ba5eae16abefe7816.nq.gz
│   ├── a70468b0cf7d0a1fdc7b65b2bb446d50cfa2e24a.nq.gz
│   ├── aadd0b47c0ee4a868bc2e9090bfa1921783cd307.nq.gz
│   ├── b03a616f67adf7f8f28c96ccea9c75514d7fec7a.nq.gz
│   ├── b315b71b91847531c79f5781f00e66810713b7ac.nq.gz
│   ├── b82ccc5d401702b4ac8b588870b8dd2cc57e18bb.nq.gz
│   ├── c6d1d3d0ef0a1b40f2e822efa6a06e2375170b06.nq.gz
│   ├── c76c45a0b5c4788bbe6f868a612a698501b76c96.nq.gz
│   ├── c7a608b81d3706965990d2fcf61153151afb9447.nq.gz
│   ├── c8cfe3959183f8e9a50f83f54cd723f2dc9c252d.nq.gz
│   ├── c8d0d24aec8da7edfec0dcde50871dd27240e031.nq.gz
│   ├── ca9dc16211b001279d03472601351789269e6a9d.nq.gz
│   ├── cca62bc1a777097c31baa85364cdf137de0d6a57.nq.gz
│   ├── d15ef9aaf42c041389fa645f37a36a4ddb258b4b.nq.gz
│   ├── da16c7501ef173ab0ac4d7255ac3f34991402b7f.nq.gz
│   ├── dbf79adf27857232a5e0c96e38a3998c12236101.nq.gz
│   ├── df9bd5e59317a9dfa8b0dbac788c95da8cf2be14.nq.gz
│   ├── e0a0d76e37aaad33441e6596f537f14bfce6383a.nq.gz
│   ├── e45f625c1e7ae90759678c014fe964a776ebf92e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ec3bc61a821be7c03044663d9620f5b428e3af44.nq.gz
│   ├── ef1eb5cbc1fa399e8021b83c8a499f7d3e4fa2c6.nq.gz
│   ├── efd86d727508ec76a8ce7fd6ed929763102bbc1c.nq.gz
│   ├── f05642e93624980cdd0a719df5bc99032d8798d8.nq.gz
│   ├── f758d0ed4ab565ea18f4f4ede33d6836c604f503.nq.gz
│   ├── f9e8318912430c0f822c27ce9a89a12af220ee0c.nq.gz
│   ├── fc50fe567a760319319b58c934e946aaa2c1434f.nq.gz
│   └── fd86b3ee9151335d2cfaf2f581bb4c9fc96e0838.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1c2eb7a185816890820124a5d7d8e388f53f7ddd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 83 files
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

[databrickslabs/lsql](https://github.com/databrickslabs/lsql)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
