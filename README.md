# Repolex Knowledge Graph of privatenumber/tsx

RDF knowledge graph data for [privatenumber/tsx](https://github.com/privatenumber/tsx), parsed by [repolex](https://repolex.ai).

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
lexq download privatenumber/tsx
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f6284cd50575ce6e8d110f63266d66cb9cde3b88
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── f6284cd50575ce6e8d110f63266d66cb9cde3b88.nq.gz
│   └── repolex
│       └── f6284cd50575ce6e8d110f63266d66cb9cde3b88
│           └── chunk-001.nq.gz
├── blob
│   ├── 0192e39e13417cc1ead36f22f523b4070f633762.nq.gz
│   ├── 029ab451e330be8013ad14cc8fb65e7a05e9fb30.nq.gz
│   ├── 0486bcba4ef16e798362679fe359acb24a4e4e69.nq.gz
│   ├── 0a2622967194df9c108ad23e251ee8e00c43ecf4.nq.gz
│   ├── 0a2ccc9970513d63c7348b27efb3b6a1a18a92f5.nq.gz
│   ├── 0c66f17174eed08e46e6e051b765c52877e69dcb.nq.gz
│   ├── 0cdb58df7be3b367637f38409e55aaa0250e876b.nq.gz
│   ├── 0cf95a403da47ad8f8ad6bf531ed15b5f538e1a4.nq.gz
│   ├── 1113e8d5b386e7d5ba46d49e7ce85bed37a85c9c.nq.gz
│   ├── 1579aa4ae17b955fd27d3e24532517f8c1ade84f.nq.gz
│   ├── 15b87c3b2c46b84831ff016831ab55f1f44ea6d8.nq.gz
│   ├── 16767136d87016a12f319a85988baca24b8f3c06.nq.gz
│   ├── 1b7a85fb386b6361a7c2689c7b5234e2512be00d.nq.gz
│   ├── 1c6314a31833395fd5ff016a6506bdd51860657c.nq.gz
│   ├── 1e2e6698d14515f095066ae963793e12576c1a8b.nq.gz
│   ├── 1ed78b9f285e49678da63ce6644e25b40ac78157.nq.gz
│   ├── 2209cd35fe7792cefab6327b15dc2d107dbb8860.nq.gz
│   ├── 224f72944288051e1338793442fd925e515d7e58.nq.gz
│   ├── 228c13e16350e51e09d2aca757133928b13e0477.nq.gz
│   ├── 24696ffdc7be5b1c82cb51328b6ec25e1553fb1a.nq.gz
│   ├── 2478d76df6615c0c4a2cfccc81cc75ec57900aba.nq.gz
│   ├── 24b8f4fb5d5053d604b499155750a6860b4a6c47.nq.gz
│   ├── 255cd02bf533f1aa4b55d5c0bda864266c480b02.nq.gz
│   ├── 28756faeface6226e2980c5dc07e861c1a8013d3.nq.gz
│   ├── 29675aa82effd22434077be62c0e126a2c0f39a9.nq.gz
│   ├── 2af3d841426e436759789ede3b63a03aa400a0fe.nq.gz
│   ├── 2d6a5ebdcc5ed0f67dfda24979e10f9a6bbc8814.nq.gz
│   ├── 2d943e66ebfb146297a7f1df2ff31d32731af4ba.nq.gz
│   ├── 2f6c812c9e8486a2a3b4adf4f6f61edaa7813d67.nq.gz
│   ├── 31f0b1a79f926dae357ebb69fa2b15f1a9bd9eab.nq.gz
│   ├── 348b0ec066e51141dcad63784cfb61c01e9a47d7.nq.gz
│   ├── 34f3a68c66716c6ab37c5b8e9aaf01943f6c2ae1.nq.gz
│   ├── 3566de9c8c9da8f0413545de46238093a51ed436.nq.gz
│   ├── 3670e1b667a3d3bf414905d0d6bd32fb2860e1d1.nq.gz
│   ├── 36d7b02b2914cde0298786dbc20de5c212b0bd1b.nq.gz
│   ├── 39b272a1d537a6ed9f2a8d5b54bea1e2ab6cb991.nq.gz
│   ├── 39e1921da481f2c9027cd1c1dff9ccbd33b98b96.nq.gz
│   ├── 3b3548ad20330fadabe11414483cff185f82400c.nq.gz
│   ├── 3e99d3d6442651572a425844d5ca8cd42776cf12.nq.gz
│   ├── 3f4747365adaa313fe0df1369cb8946b47548f83.nq.gz
│   ├── 414a32a8679a7beefceadac624e0bd305ff595df.nq.gz
│   ├── 419ac167334c762babce35ce9fc4c9e926273e2a.nq.gz
│   ├── 42b230de1e1db24ef8e3c3768e88147141875f8a.nq.gz
│   ├── 43ba22cf470307255dfbabc47eea7d39aad3bc14.nq.gz
│   ├── 4592c9b87d833494124d90e61c367601c1194e05.nq.gz
│   ├── 45d553ecbef88d8c7a47551db8489a05e5fd7aa1.nq.gz
│   ├── 462706706c70beca1708766624e6d16028bc0ae1.nq.gz
│   ├── 47c222a6a10d988893236656c59535580087d7aa.nq.gz
│   ├── 482bb38ed657d6f78ebcb34a35654f73fb743175.nq.gz
│   ├── 48ca009da12c56adb0cd796dffc7e8dedce4c684.nq.gz
│   ├── 48cd7540e8a113bb26878ac5db9ee2400b0307e2.nq.gz
│   ├── 49f1c2150964717f1dd5728d01adb59303e04ffc.nq.gz
│   ├── 4b0fa4e7b7bf11ad63efb4b616e29b721c27b6fb.nq.gz
│   ├── 4c3393f2157aab50919d2b535fa4cc4c6076e7eb.nq.gz
│   ├── 4d360cbc8a1050eb7b33e974339676f2f0b8dd9f.nq.gz
│   ├── 50245ade348f995231b94b262e1a625099117787.nq.gz
│   ├── 51ae30a2ea75cf9e94d8d4e785463c25e7571955.nq.gz
│   ├── 541d80684cc8e7d5a96657f11b02c029c7c6e5c9.nq.gz
│   ├── 54d628af5fa6a70eb67b34aa20ccaa0c9e1efb9e.nq.gz
│   ├── 556347e9fba85596524fb9f483f937164b0d5b51.nq.gz
│   ├── 579b6367e013f25c3f5728ec521212998d54731e.nq.gz
│   ├── 588f95cfca956da7b7c9cfcb204fb6ab301b6c41.nq.gz
│   ├── 5891746206d115ed835a020cacc1718a0267e8c4.nq.gz
│   ├── 5a710ed532f861ac90968f9ec8919ed1e81aa492.nq.gz
│   ├── 5af36b8af483b87edbf6a45367699c5d2935b1f4.nq.gz
│   ├── 5e45139cb2507b31b7a0e7b58eefe492808cadfa.nq.gz
│   ├── 5e9451338ed0b9632dfed25ac96a2dab6f6be4e8.nq.gz
│   ├── 6212a0b2258c41eca16ce6d9fa305dd23f4126c0.nq.gz
│   ├── 6482c9f7784d55a8eb822782b97e8e9c8b6e9f5b.nq.gz
│   ├── 64f2d667bc1cd674a6101f64a0c61dcf58aefbd7.nq.gz
│   ├── 6518af7ca728ec0c910d606fdebd88dc83195678.nq.gz
│   ├── 651a7153dfe1c7bda3a38e0bca0d3558902969fd.nq.gz
│   ├── 6661521a87ac518fcde0d85d0864b25a3e4a1f70.nq.gz
│   ├── 6741be1bb840a27256832d1a9c674d63c163d74d.nq.gz
│   ├── 69caa5de975214f771d7b35caa44050e404f601a.nq.gz
│   ├── 69dea2a4c2d742ee104ea580907d08ba6d377731.nq.gz
│   ├── 6b053a8d98d759cbbb9476620a04b8e382dc71dd.nq.gz
│   ├── 6b1018ea8cb33f759a312e5f1e1422f75451a998.nq.gz
│   ├── 6c8e014c9b6ab6dbf8b2ee93ad0655f5da640424.nq.gz
│   ├── 6e3fe41d7cf1ea0e58287226e5b329a3d28e225c.nq.gz
│   ├── 788231a6857b168ba988078402531d82d59c5104.nq.gz
│   ├── 7add1bf730504308f80e69e358cdc780e852704e.nq.gz
│   ├── 7b75c83aff1c05e0e0e315638e07a22314603d4d.nq.gz
│   ├── 7c365a8b224c57bf2e90af953d26710b7f665834.nq.gz
│   ├── 826bce1c3ffe06ae80dc9561188c0ba61d57b626.nq.gz
│   ├── 852f74aa8188e54ee60fc1e9db21147c04ac2667.nq.gz
│   ├── 86215b0b8700dfc6336474e3319d3305eb950bd3.nq.gz
│   ├── 86c7ab3706169be40ac9d1b37ee0de04c6925697.nq.gz
│   ├── 887f042a4158fa42c337d5df03223d8075716539.nq.gz
│   ├── 8948eaa8d9925064a37206c121eeb8bc5614d9b8.nq.gz
│   ├── 8c0e26a11d6e014e23be16ce83d6169b945f4095.nq.gz
│   ├── 8e03b0f514f2d0ea928a72f4f14b9f3996819318.nq.gz
│   ├── 8e7d439c52d3d0ee3c10245853bf907e26e5ab27.nq.gz
│   ├── 902292b676e11cd154f0f296534f3d578bb79046.nq.gz
│   ├── 963030e24488f0cc8ecc19172676adb24ad85d40.nq.gz
│   ├── 99a3c1ff8f79a233a815e82170eb3360b9ffea85.nq.gz
│   ├── 9b70a64a581a77f9ad32c27f56c7c4566384a981.nq.gz
│   ├── 9c3eee216924ec261eb8d8bdf88037f4170c3597.nq.gz
│   ├── 9c9ec8ee63622845902fd7fed70103ef7a02b883.nq.gz
│   ├── 9db5bd38fe26f121413deb412a46e38c677f015b.nq.gz
│   ├── 9ecd88ffbf3681621015007807f1597994b488ff.nq.gz
│   ├── 9ff9320178d2a49db0e7d96ecd1284997baa0fe6.nq.gz
│   ├── a02c16d94608beb990a70acf027999b351f17f07.nq.gz
│   ├── a125e76899adf15ab54ada2ab7408cf1e459df3a.nq.gz
│   ├── a14771ce4822caf89a7b9c4e17b1cbfdb87d7de2.nq.gz
│   ├── a19909993967f7015df5d423a1953f857eee3df2.nq.gz
│   ├── a62dbba40e22da9cf247130a9bd677d7c35b2af5.nq.gz
│   ├── a8e06323857bce5b759e87b939743ff495d3196e.nq.gz
│   ├── a9f69355e866ddaaadb10cb3b1a2ab79ff20dd7b.nq.gz
│   ├── aab26b7c4a349887a8fbdd730b976fc543f2a8f5.nq.gz
│   ├── ac12d5f841af4a93536413861916ffa478490d0b.nq.gz
│   ├── ada27db4fe580e297659c8df62645ec6efe43b81.nq.gz
│   ├── af730bc9f2e8dff9e5fe513370c74144aa77ae20.nq.gz
│   ├── b156deb99971f6f7fc356c70f966ed530dbbf9c6.nq.gz
│   ├── b1e2a4602891c9b91f1cfa065a075259b51ae35a.nq.gz
│   ├── b223d4f958781445c2e9ce7c9f1c397111ea7b7a.nq.gz
│   ├── b269d1cc39597c03c43a6c84437fff0034b18f13.nq.gz
│   ├── b34c871bd332c6ddbbb42f1bec0adcac7b4b3a22.nq.gz
│   ├── b5bcf8893bbb271d223922223efc4831f3b7f3e6.nq.gz
│   ├── b6a6dc37ec086daaa240b72af0f80f7a832861e9.nq.gz
│   ├── b7abdb1cc8b03daffbe3298f9adae323d9be9fef.nq.gz
│   ├── bbd350f75e3eb0c80542afe59093ee4f5954bb22.nq.gz
│   ├── bcc289ccc19664e2e6f1e261d9bb33188009e5a0.nq.gz
│   ├── bd73f5acc0d2609a8e73df6bceb490f4070e436e.nq.gz
│   ├── bd7a1204fcbf17d2ed11c018081810c1b38f9d30.nq.gz
│   ├── bf183d2f5a0346035cc7a502c69cfd984e0a0be1.nq.gz
│   ├── bf4db29997695baa42e1a2f18fae0e201b432583.nq.gz
│   ├── c1b504c2d5d889534987ef1c7e03b4e7ee83fe8f.nq.gz
│   ├── c4c46a8b70b1674ab4fcca0b24faee775165df91.nq.gz
│   ├── c4f07e50c97da45ffeaff79d1257789461c78941.nq.gz
│   ├── c6df8938c53872a7559249a7baa1a29836d32ca0.nq.gz
│   ├── c6e1dd2f1fc70692f796bc6ee54e3736ec662e23.nq.gz
│   ├── c71a24f5c5467b0b825bc6acaa63eac1225b2e24.nq.gz
│   ├── c8228b757edd1ffd93008876cdf4dde8b9e00047.nq.gz
│   ├── cf39c0d4945731f819596c7766c8c0309974f8f1.nq.gz
│   ├── d188102b164365ecfde95586f247fd9ebb910009.nq.gz
│   ├── d44fbb74d82dd9e8e3bab18be926f3135e720c8a.nq.gz
│   ├── d662053e4396515d126f494151017ad02a0799bc.nq.gz
│   ├── d9901163ebdffacbbf9ed1dbe559a1ed732b0ad5.nq.gz
│   ├── da3a71849c5c9bb91f1e365a9ab36b269704690a.nq.gz
│   ├── da4ea6179acf6adb5811181def323353a9e4c879.nq.gz
│   ├── dbaedadc259ae0e5197be0cd8f9ff4a647ebe244.nq.gz
│   ├── de1468db3a0a31a64544ab9e9998aabfccfc04c7.nq.gz
│   ├── de405c70749aa7c712bcbd31f8261c42317f114d.nq.gz
│   ├── dec05193ae5cda38a3efaf647e28c105321f2ed8.nq.gz
│   ├── e14bfcd59cc88175f6c58e46b25da32168f4a023.nq.gz
│   ├── e1a90d98f1e55e7dbbb75b6173d171717465ea2b.nq.gz
│   ├── e2c9b15a69668696448d9b0a9146a119cfdb604b.nq.gz
│   ├── e84a0b5705b13f48f7fffb662bb05d2fe5385eba.nq.gz
│   ├── e9199ed9795079e98ae418d2a7bfbeef5e3acd4a.nq.gz
│   ├── e97ee7b0c3a0de263deb5b58a1a13e19db63c6c1.nq.gz
│   ├── e99e0f778691c27c7474d05941659990a0fc3eff.nq.gz
│   ├── ea8c31fc50b3911c2eed196e698f848f7577f589.nq.gz
│   ├── ed8c487524b0c7b78b6ff488c33e5563fca5ce0a.nq.gz
│   ├── ee3646da89c29a65dca08959ae84a3ee281d1b30.nq.gz
│   ├── ef2c39d20cd1ad66f9798f4ef5e48fbb03fe5624.nq.gz
│   ├── ef55e3df9dabdcfaab5a740b60ce2badd2737e1c.nq.gz
│   ├── f074b2581eea8f7140ce006cb14b4edf5640a874.nq.gz
│   ├── f212d5622b2682fd22aa7b0e2eea3d537b700495.nq.gz
│   ├── f234c57bc4b15503251b800ffee2a04dd9b76058.nq.gz
│   ├── f25bfcff899f83d0392e9abf5676dc9401c74496.nq.gz
│   ├── f33c6fab79406e203b39b942cd4502431dd59e52.nq.gz
│   ├── f34d1528b55ef37a205cabf295354e9733c319f2.nq.gz
│   ├── f5d56541a63f0636fea0b510308096dd04d3428e.nq.gz
│   ├── fc81d3def050f38013a710f162d23fc7fdeadf5e.nq.gz
│   ├── fca3dfc406dcb215cca7aa20f137bd7bb235b9a2.nq.gz
│   └── ff9bb4a0f85fe2f51389fdbcfdb1b868f99d3033.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── f6284cd50575ce6e8d110f63266d66cb9cde3b88.nq.gz
├── filetree
│   └── f6284cd50575ce6e8d110f63266d66cb9cde3b88.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 177 files
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

[privatenumber/tsx](https://github.com/privatenumber/tsx)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
