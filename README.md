# Repolex Knowledge Graph of pelletier/go-toml

RDF knowledge graph data for [pelletier/go-toml](https://github.com/pelletier/go-toml), parsed by [repolex](https://repolex.ai).

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
lexq download pelletier/go-toml
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f36a3ece9e3adf0efaf9f9bd3591c3001f17602b
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f36a3ece9e3adf0efaf9f9bd3591c3001f17602b.nq.gz
│   └── repolex
│       └── f36a3ece9e3adf0efaf9f9bd3591c3001f17602b
│           └── chunk-001.nq.gz
├── blob
│   ├── 031b1f6271fd13e0aaed7a414df9665b030114ab.nq.gz
│   ├── 0512181d287a178d633188174c9c414e89e75291.nq.gz
│   ├── 07f8b39e550da86d59802ea2ac864d037b2381f1.nq.gz
│   ├── 0885720a8f2d177ad2b3dc91b3e92639f4ef26d5.nq.gz
│   ├── 0e3ee8fa5ecf6116b5414838e879bda661407e2c.nq.gz
│   ├── 12165c8baac4801bb5ce4a7afae8ef035b46e32a.nq.gz
│   ├── 12821a2f47c7deac41746c3e77f8491c8edb9dd5.nq.gz
│   ├── 1e54e074e56ad51116a181da3cf7cc60d49bdcea.nq.gz
│   ├── 20623580012cbf2d664bfcbafb3267274359d250.nq.gz
│   ├── 240e996c3b2909de04710ddd65fdb762f25f40e4.nq.gz
│   ├── 28b88ec334b7cd1ea08189d2610fe3efe7706091.nq.gz
│   ├── 297b0a5837540d1713e0874983fe88ed7bc4e300.nq.gz
│   ├── 2a147c0260939c0fce8bd534c693283c4cfd6600.nq.gz
│   ├── 2ae3a71fd796b45b85a9a39943390097bd5bc9ba.nq.gz
│   ├── 30c23d1a176b54e8b78c9728579e42508a81a00e.nq.gz
│   ├── 34a0a21a3603c3a3889d9897c96e6f9cf81de085.nq.gz
│   ├── 3703bd0ed272de1c3bccd502dac959aa1b01e124.nq.gz
│   ├── 3a9f1e423456f340da6a19335e5efc0d818f75dd.nq.gz
│   ├── 3e19ea710a98d1d125e2b8b2ea42a02ee4387bf3.nq.gz
│   ├── 4543f4d8db3268098d97a3955eef5cd7e77a4713.nq.gz
│   ├── 4635619fc13a59383950db741b15d027f768d643.nq.gz
│   ├── 473f3749e8b08a7a442bb7c2304dd83e942bd935.nq.gz
│   ├── 4d4f3cc31fbfd6a716ef06518f54ebaf4da8d836.nq.gz
│   ├── 502ef2f2f1167a34fc9e18a542ed5631281d20ea.nq.gz
│   ├── 50a6d170298a4c27686333a11badf50a1eae4d91.nq.gz
│   ├── 51b9b816c432f39473c471e0d6386dab32181734.nq.gz
│   ├── 5617e74f2c6d2d0da3a9803981f130553f0ed4e0.nq.gz
│   ├── 57890d4d97cb66ab09e4683beaa88f19e35812e7.nq.gz
│   ├── 5a79da88e8663418da8e04f4ed2c437e32abc6ba.nq.gz
│   ├── 5b67c3c2ada0021e803d79285e84dd54e76f4c36.nq.gz
│   ├── 5cbcee36e256c9ab1b8d100ecf58714337ecbe70.nq.gz
│   ├── 5fe5c777227bfcb9956d359a517742900bdf2087.nq.gz
│   ├── 619cb0cf1b8551f4a041d9ce15076443a3aa41e3.nq.gz
│   ├── 61cdd181f3af18c46b66ff2128dfa432a5aa62d0.nq.gz
│   ├── 6344fd047de9a3c37c880e60801b1f5fcc2df47b.nq.gz
│   ├── 654dc163af7b05d1343c98974cf108438150f6b1.nq.gz
│   ├── 6b21592d6e66acc64a22f4cb1a610c2d28561bc9.nq.gz
│   ├── 6c35a4fcc883e631ab06209622714ffd26f16df2.nq.gz
│   ├── 6d12fe5802c231edb52cedbb8bfe5c9d95bfc1c7.nq.gz
│   ├── 72efa67a5ff96dba1029851fa13ac68363084da7.nq.gz
│   ├── 73770384cd3bb4300163c2e28476e694ebd1de49.nq.gz
│   ├── 7412bfcd45e9cadc970d2ee190cf878fac8622c9.nq.gz
│   ├── 742c17bbfba19aaacacd26f1a471346801d2ec38.nq.gz
│   ├── 7b5883475dfa4e0a0143a1d02c163645547e3dbd.nq.gz
│   ├── 7c5cb55e42931fac907c2f32e96ac427b80a09c6.nq.gz
│   ├── 7d2e5b04cf86d75ab6ad240e131d53c033aa4f43.nq.gz
│   ├── 7d410159f6021eb505ea569aa1a7fbe0fb981ae2.nq.gz
│   ├── 7d9b136f37a5a99cc80d2d57191684d8f165a10b.nq.gz
│   ├── 7fa7a771bd8f012a98e2ec9c84d4980126fb7dbc.nq.gz
│   ├── 7ff26c53c7b45ba30a93e9372815f491ba816b5d.nq.gz
│   ├── 812e68666d26be310e1af8c5fcd2b8a6e49928bb.nq.gz
│   ├── 815b604178f610eda010d4f158e5107f09ddd0cd.nq.gz
│   ├── 868fb7d715e4fa35632c95a3dd202906e34de68c.nq.gz
│   ├── 8b188a775414483e519ee4f5c8d66ae7bbebf96c.nq.gz
│   ├── 8b8fd608dc241609c2f5611c8dfd8b2e0e8f891c.nq.gz
│   ├── 8c95e92fb2d86a00872ff8149dd495c3ef23e97f.nq.gz
│   ├── 8e4f10e5cf80eb1ae7a7d7b226a4e317c6e4dbdf.nq.gz
│   ├── 91869df7f48797ad8cf23592c07f6f9549289148.nq.gz
│   ├── 9510a9adbe4be0d2145ab85ccc46c000e92e73e8.nq.gz
│   ├── 9726915c814e443a6c8b2177ee98be7008db8e26.nq.gz
│   ├── 991e2ae966e5ff931aa96091893ac69fb73af2c2.nq.gz
│   ├── 9987722abb1e22435fea8501e3c2b14d97cad212.nq.gz
│   ├── a0384ad66d5787544dcb055f246a2b624107bc9e.nq.gz
│   ├── a1a168df72b36faee660e217622555a303c9d58c.nq.gz
│   ├── a28b720ce2f2680707b266cde553322bf816125a.nq.gz
│   ├── ab2cf4317b0b6fa948dfed8312e2af26bade6940.nq.gz
│   ├── b2a76e256b526beabd1831fe8644c0fe7a484ab1.nq.gz
│   ├── b709369d6721d2df6a75be6bd50e027f41400328.nq.gz
│   ├── b7bc599bde45a2de33a13a89895e9ed295776d50.nq.gz
│   ├── b9e93323794958bdbe93a5b226ed0bd1f4c5542f.nq.gz
│   ├── c3e75517c31dfa8d45de63514bcc87f630a7a964.nq.gz
│   ├── c4c27ae51e78e10a7b3b5353eafbab3904775c54.nq.gz
│   ├── c9102a02cce77ddcda8e282cce8a38e3f859b8fa.nq.gz
│   ├── ca462d40e039cdd21061f2bab63aedacbf58d208.nq.gz
│   ├── d4d554fda9d1e6f31a205795acd82db78f2a9bd2.nq.gz
│   ├── d554d5a453301810405d823cc044ef0d093ec16f.nq.gz
│   ├── d68835dfa6001ddfbbed0a75511eb0c5fa42656f.nq.gz
│   ├── d940bc1832ff5b913f0c9de66b59b361ebbd6890.nq.gz
│   ├── dafe44d764b95441c823ef570077b27c43ac135a.nq.gz
│   ├── db2d4e20ed17a98899b54c29439dad8c4b0addab.nq.gz
│   ├── e33cc3e6e69c5bb68da782862aeab7892d3fa5d8.nq.gz
│   ├── e4354985be29043757f114f147f2353134285e80.nq.gz
│   ├── e4865de819ec0d8635a97f8dfaaace16749a895a.nq.gz
│   ├── e604f40584144c2d468b459afba2a3c3b216ac72.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7c68dc5c26030fe70fa2d987456a155e48122a5.nq.gz
│   ├── e7db8128cebcbbd7e3bf55a0d6391a6a2585f97a.nq.gz
│   ├── eaf580dfd8fb61d77efe605cb430cb8365e83a86.nq.gz
│   ├── eb895baba66ed2e926850d343809964c34e382d0.nq.gz
│   ├── ebead59c8f05badb1aa60298390e8369073ffb55.nq.gz
│   ├── ec119752d21ded69ee322bd18d8e3445aa709ef2.nq.gz
│   ├── ed510382c06f1d5b396a6849baa1c5f7d1b89504.nq.gz
│   ├── ee23b3c3235c49e62cce87af12b8bc39dd30ca76.nq.gz
│   ├── f1cb4cf52a3f99772c35a38c5a00f7fd125e6641.nq.gz
│   ├── f3f14eff18898ed609d9bdb133a876cc4f9205eb.nq.gz
│   ├── f7083b7a4c6fefb418991489449b50b723beb119.nq.gz
│   ├── f87a95a78d6cbb8d54efbbfad3e05a2dcdca06e6.nq.gz
│   ├── fd9e0ccb1a5508be575aa52fff88c5979271b4ea.nq.gz
│   └── fdd875d517b1cadca88d54831098cff2746a78b0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f36a3ece9e3adf0efaf9f9bd3591c3001f17602b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 108 files
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

[pelletier/go-toml](https://github.com/pelletier/go-toml)

---
*Parsed on 2026-09-16 by [repolex](https://repolex.ai)*
