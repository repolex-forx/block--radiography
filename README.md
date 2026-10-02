# Repolex Knowledge Graph of block/radiography

RDF knowledge graph data for [block/radiography](https://github.com/block/radiography), parsed by [repolex](https://repolex.ai).

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
rlex download block/radiography
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 48c0b66369482e3830262a8720518291f1a60790
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 48c0b66369482e3830262a8720518291f1a60790.nq.gz
│   └── repolex
│       └── 48c0b66369482e3830262a8720518291f1a60790
│           └── chunk-001.nq.gz
├── blob
│   ├── 001ba28eabfa25d921638827c4280d74668825e2.nq.gz
│   ├── 02a5c729060b383258ae937418608c4866772f49.nq.gz
│   ├── 059758bba6a63a5aa9986c8596e950338e9fb240.nq.gz
│   ├── 0b2d336531248d90526f1d45e1683664302b46be.nq.gz
│   ├── 0c72361be71be389b8e0f3950410eb829593933e.nq.gz
│   ├── 0c8badc66391b215e517983c5ab1d023401d2eab.nq.gz
│   ├── 0ee9714940f0d0f897db59e27042afaaf31a8432.nq.gz
│   ├── 166f083238dd434e68c25883026c396aae7a7dee.nq.gz
│   ├── 1e5a2a74e2d3176db14c2cb4d4d99d4cb9e2097e.nq.gz
│   ├── 21976b5560625fd1ec1485b3a37e79dde70217fa.nq.gz
│   ├── 249d6389447d5ac4b4d63d24450bfbc7d490fed7.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2bbf553e0c9b8a6b2e4f382b199c776610014c39.nq.gz
│   ├── 2c65cf42e17cb614523113a9b375498676bb80c8.nq.gz
│   ├── 2c7146e9222c31d026bb844b26e17babe0b29a71.nq.gz
│   ├── 35d09dc07b9c51aaeb354e524cbeab4cb7fc0d43.nq.gz
│   ├── 364645d5355a91310862787d6fb6a856e92d89c0.nq.gz
│   ├── 366d85dc6a06aa895b7d189367812b2bbff9fd67.nq.gz
│   ├── 42678ed62ffcbeb97b05794dfd95ee720edceac6.nq.gz
│   ├── 48b109be51c387d29b466d1884862d2a961d2131.nq.gz
│   ├── 48fae94d34e038276368186848f09b24da2374de.nq.gz
│   ├── 497b003313080813112eb21a6113692168c08ff3.nq.gz
│   ├── 49a2fe19812fd0399b4cf775607dd58eb57dbc6a.nq.gz
│   ├── 4d1fc26ff5abec9561b71ee3eb3e53dfd7ca2420.nq.gz
│   ├── 4e4e083f7c56e226dc67fddb487301aab3476ea6.nq.gz
│   ├── 4e7e3694a6fe8a534ed6c63380c7745c5619e273.nq.gz
│   ├── 4f48712f6e86ba19fc096a496c4840675beb9357.nq.gz
│   ├── 53241cd32569a5cf8f795860da1dcae98b7d7413.nq.gz
│   ├── 545f04f30e94e8011159ad8d884763080481274e.nq.gz
│   ├── 555aa56fe2e61a144571042cccec5aed6201a26b.nq.gz
│   ├── 5808865146b763172c940258c9d7563e5e1fe981.nq.gz
│   ├── 59032f768a5677c5ee1335281853ada0066633dd.nq.gz
│   ├── 5b4e0ed666de78b329983e55cc161bded5808bf3.nq.gz
│   ├── 5e300f758bb5396a7d68fb85bb8080e2fd96c823.nq.gz
│   ├── 611f8819605dc2b4cc10ec1fa546c0aaceb5818e.nq.gz
│   ├── 61b08feb786d678c5524fd3f7c7e8a08f2b70f90.nq.gz
│   ├── 61c21f5ab08830970cf525c9fbe9fa8fb5de308a.nq.gz
│   ├── 6215ad183e3d85acf23a3a8b22b5745453d7be84.nq.gz
│   ├── 624092898d2341692879477f7a0488ae77ed6f33.nq.gz
│   ├── 6421043f0e79366debc58566b2b402a0d6fef365.nq.gz
│   ├── 64845f2e4494020421715484df2c8dbf00c7b95b.nq.gz
│   ├── 66ff32f81c42740ffafb0e6f5081e65fda22102c.nq.gz
│   ├── 67a0e53952c34ff66f950c8b66eb058008efef2a.nq.gz
│   ├── 6a9ac83da45d3067fb1e5a9225fab6df170a2f65.nq.gz
│   ├── 6b970fa641b1e774cd93e1cd7c8810634b2340e0.nq.gz
│   ├── 6d6eab7aa8ad3329d3489302acad0baf672b123e.nq.gz
│   ├── 7047556848ff8c0927fe74b6afcc9b8bb838a9af.nq.gz
│   ├── 744e882ed57263a19bf3a504977da292d009345f.nq.gz
│   ├── 7454180f2ae8848c63b8b4dea2cb829da983f2fa.nq.gz
│   ├── 79c982726d96fc954b8636dd1f96b9c5ae88222c.nq.gz
│   ├── 7c49fdac4e22a13aad89e8d3829820fd8a17af4b.nq.gz
│   ├── 7ea3c08f27da64cd71256117e128b4960c49522b.nq.gz
│   ├── 7f518922afcd50bb5a2740e39b901fb68a790724.nq.gz
│   ├── 810a6b5a4bff553fc3b4f1ee01e0547ad8c6264c.nq.gz
│   ├── 83b1a87a1a4a1294a93c8175ce9911d68838a28b.nq.gz
│   ├── 8e03690be14a753c181d4219b6c5478b6146c680.nq.gz
│   ├── 9114394ba219677406cb2b839e7f89661d7e564b.nq.gz
│   ├── 94a13daa72e5e9afc80c0abe6f367412a1258647.nq.gz
│   ├── 9df089df72d5a51b7e0045de65ccf5753b12c30e.nq.gz
│   ├── a3cbe3a0002bc350827024d8f6df219c5e5c6f0e.nq.gz
│   ├── a78b9e14ae3f8815d606796abb84d19145132903.nq.gz
│   ├── abac8e869e6792fe11799947277f835cc7735884.nq.gz
│   ├── ac1b06f93825db68fb0c0b5150917f340eaa5d02.nq.gz
│   ├── b1a3013b7b41775699eeb22f92970f075a784ef3.nq.gz
│   ├── b1b16da17fc19c69fa9c247c7b87165b8cee058e.nq.gz
│   ├── b8e52afa349ebbd1b57d34f31c7abb2db5aac6a3.nq.gz
│   ├── baa4414253880761f61e90161389abd565720679.nq.gz
│   ├── bcf4ffc8ab071f77c4037f10d8cd3192965a1e89.nq.gz
│   ├── c12ef688719fa037ab563f96099bad35da33ff24.nq.gz
│   ├── c3abcd383a6642be0a7cf58ec052247f742e46a0.nq.gz
│   ├── c72f84a42c9880e43b6249d398f68620c38b9080.nq.gz
│   ├── c83634ba068b4ed0b362083b5dc037cb02f44b5f.nq.gz
│   ├── ca28e20bb2263e1055fa7ceda683d571ce823b22.nq.gz
│   ├── cb22542a3c4f4c980d3347e3079f7797f25f26b2.nq.gz
│   ├── cc947c56799598205b8fb518f3ba95843c1bab71.nq.gz
│   ├── d3c89c198c25e7e99963ea65074fbbc7205685c1.nq.gz
│   ├── d69893726257d29017ac1acd03022a94072a3ff9.nq.gz
│   ├── dd983cba75db7dd297aed5291fd4a903b08c7245.nq.gz
│   ├── df374c15eb52ffdb5d9141b0a95429ea39c25a06.nq.gz
│   ├── df4342dd9df621036af15878e46cff913eb23da7.nq.gz
│   ├── e1203ebcdf584929c3eaf4a2b5ab76fc1b69ec1f.nq.gz
│   ├── e45152da063a75bc25f4dc3ac2abec9e12a6e839.nq.gz
│   ├── e492b916b1e3894f02c006363cc417f2a4ef5b88.nq.gz
│   ├── e69d0402a876a2d9dec9c39a4159aca4a099774a.nq.gz
│   ├── e6c31627c7bfe7f99a15181eba1939c81d09e8ee.nq.gz
│   ├── e7316583b35f8a02bae1829400fb4dae37a5d1e4.nq.gz
│   ├── eb3c9b010532ec23489ee181b4c35cd7a1718160.nq.gz
│   ├── ec569681f66a4f41aca0fcc783f878c3066faff3.nq.gz
│   ├── f1ee14a276c18c06e15c91a9c32f1f14655b9fc2.nq.gz
│   ├── f21bb67f92dbff8fe38020d38f64db3244ab6f19.nq.gz
│   ├── f8232ee44d4bba6cc77cde1ce0ca1af2c526c183.nq.gz
│   ├── fc2c22ff50b4c27c125052019a3206b1df3c52d0.nq.gz
│   ├── fdae22245055c7c31fdbc350c6f5e34333ba47b1.nq.gz
│   └── fe00bf60a14ce926b2debb790c20ba55168ff1c7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 48c0b66369482e3830262a8720518291f1a60790.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 103 files
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

[block/radiography](https://github.com/block/radiography)

---
*Parsed on 2026-10-02 by [repolex](https://repolex.ai)*
