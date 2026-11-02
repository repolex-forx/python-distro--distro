# Repolex Knowledge Graph of python-distro/distro

RDF knowledge graph data for [python-distro/distro](https://github.com/python-distro/distro), parsed by [repolex](https://repolex.ai).

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
rlex download python-distro/distro
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3fba7d3e19c84e5bb1f15c22b1a5a6db6e8f07c7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3fba7d3e19c84e5bb1f15c22b1a5a6db6e8f07c7
│           └── chunk-001.nq.gz
├── blob
│   ├── 0131ba6e4ed144ebf806e096b9e31321a958daa0.nq.gz
│   ├── 030200a6702d13a4e9f516681b24c98ff9bd54f6.nq.gz
│   ├── 0335cd487ce587c1bbf3d38a44f71021e3113cce.nq.gz
│   ├── 05b34c79028d5d053d63579f1d035cd6bd23b848.nq.gz
│   ├── 08d9428363cf3ca615be6a557eda3980ed492b0d.nq.gz
│   ├── 08de9fb4c59a157cb4e43a30dbe8db4d2d140942.nq.gz
│   ├── 099de71cb167690494f75d3648f952f8e6116f8d.nq.gz
│   ├── 09d42abcfc46d383ccfd9fc24056507390cefd51.nq.gz
│   ├── 0c01d5b08b6b44379b931d54d7fcf5221fdc9fde.nq.gz
│   ├── 0dc0f32d56ef955c7930af55a02817e621aea81d.nq.gz
│   ├── 0dd55f2153eec925fdbddf8324a9a9ccb68ae2cf.nq.gz
│   ├── 1147d2973a15b96e8692e7984db8b1a1caf25598.nq.gz
│   ├── 1494bc552b377e8c9c237c2e2588690d68a3be2b.nq.gz
│   ├── 18483dd5e44c1d56bf97dcd2fda2f12fba37fcc7.nq.gz
│   ├── 1a3157c0501983ae5e181e482f7257728e8f1a20.nq.gz
│   ├── 1fbd004f73443556daa6c4603286f3f3b0f387d9.nq.gz
│   ├── 1fe6ce06fb3b8490b80f073162332b008cadcfb2.nq.gz
│   ├── 201ac208619167c2d526772b93acb305897d2a43.nq.gz
│   ├── 21ab2c1f84d1b6cba04d418af827222db4aa9c64.nq.gz
│   ├── 261d32c7b8938f7bf46f9db92a83513ffbb679bb.nq.gz
│   ├── 262469adf0bc8315e6314eb5f87343c6af0f9676.nq.gz
│   ├── 2a82709bfe4f876d96f2cd7c4a8ec6d1704da293.nq.gz
│   ├── 2e44b2ef2c463c3ba5cef6b5b324fa9956ee3acd.nq.gz
│   ├── 2ea1358a4cb95187e2a329ed7f3a3aea06d4ba6c.nq.gz
│   ├── 2f4fd3494f9e0b087e3f68823a5710a1b5471416.nq.gz
│   ├── 2f64cbf7ce6686a92759f3aeff0cb82ec08c9ade.nq.gz
│   ├── 2f770a5b03b8cf2c71bc1ce601f55e9dab81f920.nq.gz
│   ├── 30219340036057e4548d6d5181d7155a6c02b5ca.nq.gz
│   ├── 32cbfd26edffbf331dea7ce2ba0752aa41d64927.nq.gz
│   ├── 32f86967c62c9d8ae6c309175b6de1b19a337f58.nq.gz
│   ├── 3325e8741897ee99bdc05b4b27e70222de745b94.nq.gz
│   ├── 342a882d9e156a7f51c5f6a1ec441aafc2e7b91d.nq.gz
│   ├── 353f6ac0f221cef126a6e61195c6e55092d591b9.nq.gz
│   ├── 3568c8fd7a788f328a51f74d5eb22c0daa449bd4.nq.gz
│   ├── 377c32eb6603d2b36922e82bbb85e5a4b632bb9d.nq.gz
│   ├── 37a3d9d291fe807157c7ae06ada2fb26840bd2bc.nq.gz
│   ├── 3aeb53176b11f51e1987ff01422a2c9908cbcf00.nq.gz
│   ├── 3b2c96aacc94924e5aef0064d56bff3134ef579a.nq.gz
│   ├── 3b6c9d4888ad211c121327e579acffee0539319c.nq.gz
│   ├── 3b823c3f559973a0e5e3803943bbca483456c256.nq.gz
│   ├── 3c8b112f638744d488f6b95acafeb59970fe94a2.nq.gz
│   ├── 3ed2a152c41a44bc888e18afe8bad2a328a56460.nq.gz
│   ├── 40b0a880dc909800514386a5a42391085b8be837.nq.gz
│   ├── 41cb96ddc3a465af7ad396a019d874668c04662a.nq.gz
│   ├── 428ee09bcbfd65d1b6838513889da681bd5142ba.nq.gz
│   ├── 43c31455bcaf97fa4e0a7b9644e416adabffd754.nq.gz
│   ├── 4436a0d3a67c4ee4dd97271843c0aa59713ff38c.nq.gz
│   ├── 44ce5c22cd77d0f73247da61dd7be796b50fed19.nq.gz
│   ├── 44ff8fbdc11acfc0f026fdb48591f5c192277ce8.nq.gz
│   ├── 4690cfe1940fd2625f41288cab511421139213a8.nq.gz
│   ├── 47804496694bf757a56e6552f0eb0e009a07415f.nq.gz
│   ├── 4842beb3793faaa3c3dd6f25d8721f8767b2bf73.nq.gz
│   ├── 485cb52a4704642b89288e3d812fefdf32ee29f4.nq.gz
│   ├── 4a1d76f28bfcf6213b10be13ea6872b54ff9cb4d.nq.gz
│   ├── 4d95f6ce8e8b3e2bb085445a0d5a3393c5204fc7.nq.gz
│   ├── 4e863d82fc6191e864579abb068dcbdc405b7cc0.nq.gz
│   ├── 4f4379be95a6315c64c0e30ede0e4664c62cfe9f.nq.gz
│   ├── 51cfaebb881f530061974ca1d8cb155c91c753ec.nq.gz
│   ├── 53d352fc379ed4303dcc93721e63aa3d3369ef86.nq.gz
│   ├── 549b6912afdce3dcb259a087d511740b5f23391e.nq.gz
│   ├── 553092225696283a6a71055fdf94098bc8c32c3f.nq.gz
│   ├── 58a448458dd72eb70c3ce5affaa752f738016802.nq.gz
│   ├── 5c3ae5af3bdba84947dc0d3222eeebc444275860.nq.gz
│   ├── 5d042b20e315afb805e91bc074d1deeb7632d87b.nq.gz
│   ├── 5d7b28289a7752c25e4227805b1e4cb3a5d0a158.nq.gz
│   ├── 5dfbfd268e7721c9b7d409d500645797005e01d0.nq.gz
│   ├── 5ea7e3bf13730519dc966425575655aa666be605.nq.gz
│   ├── 615382df2cd2bd4677e78f1c3960fe1355743c75.nq.gz
│   ├── 616953936da0322e6ebb4b950f748b991618043a.nq.gz
│   ├── 6254a91755f561bdb73ccbe7b07686ee1d1f8577.nq.gz
│   ├── 63f7c550ae3ac246c4620c29d89201264f312c8e.nq.gz
│   ├── 69be7bb1fd791549055c582d792eda289906fac0.nq.gz
│   ├── 6d57a2328f7a9c8091f21fb417bbe628f343d01d.nq.gz
│   ├── 6f280c39e0d42c325927b955cb869999fc039bd1.nq.gz
│   ├── 7037a940fa41a4f8415ffc86fc31eec76bc611c4.nq.gz
│   ├── 741db580d3a810460108cb0c40d8c3432923de73.nq.gz
│   ├── 75a40c1e1e2da4b5e7cbd5893e05db540aefec79.nq.gz
│   ├── 7686fe85a7cc94188da76bfb1c10ad2a10821256.nq.gz
│   ├── 780b78a58a8a773fabcf5572a8a4518284317284.nq.gz
│   ├── 7941c73ba594722a7d7028d097eabdbe0d26bf2e.nq.gz
│   ├── 7aade1d08aa530657cea2175e04a15147097424b.nq.gz
│   ├── 7ac9df1f1726db550eb70b8ee1297f20728cd727.nq.gz
│   ├── 7d1748f929870c23c3f1139a616b9f5971073b2a.nq.gz
│   ├── 7d269dcceaaffd02f3f2c037f083018349cb3588.nq.gz
│   ├── 7d7f60f5bd3be9f4f4b97863381817f53d4361a6.nq.gz
│   ├── 7f0c091eb85f48c2ac6382550afdc61dfcb2c4f4.nq.gz
│   ├── 7f43596f6b6f26d108ce8d72abb14993e132d466.nq.gz
│   ├── 81fb0fa50938c4b01569ea621386e4c0f67bcbde.nq.gz
│   ├── 82443000f770d73a2aa765494ba8d5a81e843e78.nq.gz
│   ├── 83ee3db5addefe51add4cd1c6f58824d10cfe67a.nq.gz
│   ├── 83f3fa374044ebb1f47669ac95d121a708eb8cc4.nq.gz
│   ├── 8662a54df9e302ce390b95523aedcd1ff5e88277.nq.gz
│   ├── 88caaa804cddce04851ff63bfc5c77800605139a.nq.gz
│   ├── 892d5e6016960a1560058639e0c4b02ce6586b96.nq.gz
│   ├── 8948e12f4a02a4d3d2a0374b4dd9b97a122f557c.nq.gz
│   ├── 8a9e09edf6cc255cc809fa46ee282eee55fe2a4d.nq.gz
│   ├── 8aa5b73d1aeef36a017725b2ed4614052f289b3a.nq.gz
│   ├── 8ac16ee1bb1c29c856671c2fc628f57585e782de.nq.gz
│   ├── 8c20bfc18bbb43638f1829df1cfcb4019d9f3e18.nq.gz
│   ├── 914489dcdd710619e10224621d7dd51abcd455a0.nq.gz
│   ├── 9363b09a25550654551667dbcf7b2101b4c1cb81.nq.gz
│   ├── 94401217fa69d744c327d6d5ebee8e25404e01ac.nq.gz
│   ├── 944c9b44efc76ebe57f43d03d4e1c5f5f69dcdcd.nq.gz
│   ├── 945706a8ab0d8ff17585fea596253aed806a348b.nq.gz
│   ├── 958cd9576d5c0cdad81963ffb631fd12465c99bb.nq.gz
│   ├── 96854bd0a5318c87b9daf014568a1a35e4ecef86.nq.gz
│   ├── 986084f369cdd72198bda27d08ffb790677da8ae.nq.gz
│   ├── 998353e2e72287f86940f0b546cf26acc79d0718.nq.gz
│   ├── 9a5939cc669b5e72c70c14ca74ef67ed0bc35213.nq.gz
│   ├── 9b07673bbf1003b34e0c21aee81ffacc8ca1988b.nq.gz
│   ├── 9b5419df8bfb3ee0266ea3f6b46b6d349c06ce97.nq.gz
│   ├── 9dca9236c6cce5470eaf5c60ef66391283b4adda.nq.gz
│   ├── 9dec234a498c8b495178ce18ff8a72d1af31c8c8.nq.gz
│   ├── a385c9ee6b4d48b72a20c95c913d79b1229e6e25.nq.gz
│   ├── a581d99822be1bab638a8812e7a698ee07255605.nq.gz
│   ├── a7d60f5228b6db36d03a7bbf0749997aa7689516.nq.gz
│   ├── a82f56a418c03a9cd7f8463a4538aebdb025107d.nq.gz
│   ├── a8948ae8cf6df92ade841cadeef13223f9102960.nq.gz
│   ├── a8e9e38e72dc65de624b5c7dbab2228692198bc5.nq.gz
│   ├── a969ec0c0e51950a7fb554988f85908b36e77803.nq.gz
│   ├── aaf4d329b14f9e8b39aed24d0bfca087964f0503.nq.gz
│   ├── ad4a1f17f296cc391d0e77a9efce35968742bfac.nq.gz
│   ├── aff9d1f417ae5feffac3f61c31b40d102a4536df.nq.gz
│   ├── b0b57ed4ac7e21bf42c78a783eb8ea3f8b65bc90.nq.gz
│   ├── b2325b67faa8011aa883dab847998dd992397d19.nq.gz
│   ├── b293f64d6c00265420a5a985544f5047248fe64b.nq.gz
│   ├── b3f589f69e98be1c96c9d928a41ed08513cd2be5.nq.gz
│   ├── b7323215505900ae6d50125e3d9db3301df6fd00.nq.gz
│   ├── b9b95ffd4c613522a97677238b5e33ab17b056fd.nq.gz
│   ├── ba7213d306a05df8fa60efec0acf8592ca91ec3f.nq.gz
│   ├── bbcb294c21c576b8306a3da2923276967e94da34.nq.gz
│   ├── bcbf5ac9170323eb4afd04bf62428a0ea2cfcd38.nq.gz
│   ├── bebc20bc9a9c730772bcfa9a7d2eaf23980170c1.nq.gz
│   ├── c028fdaba4f59e5dee3e8fe6e0a3d0d5e4c8a250.nq.gz
│   ├── c0d752d51838a51db3d9e80c6831032d09aa143c.nq.gz
│   ├── c1ec08834bfd9d35484de18e0b41fa5240035307.nq.gz
│   ├── c3d37f87b9b9ea57d696ca191469b2487892d511.nq.gz
│   ├── c3dd6c22ab317f349985a9b1609cc08f0a2523a2.nq.gz
│   ├── c4b5944b9f91a59d4802bf5c6126d294bba712b8.nq.gz
│   ├── c4c75b419cfd1a831f48769e8b4ac8680f728654.nq.gz
│   ├── c4f321eda353ec65fa2bf8c63810cc67d1d3ce5a.nq.gz
│   ├── c5c8e6203b32bd5dedf90bbed184369105c49d2b.nq.gz
│   ├── c6ce0c4fba5f918b26990adf2f6337a7ac7a11d2.nq.gz
│   ├── c8e449d202ca8db2e84be17315ccdfdb4d941a2b.nq.gz
│   ├── c90ee5f66b419fd98329417a8a7b22612cf4c90d.nq.gz
│   ├── c963e3c8bbffb2f5a55e7dfa779c284c1ca323df.nq.gz
│   ├── cb7ff85fce1dd677e73bf4b1577c3f80eb182532.nq.gz
│   ├── cc0c515536560dca34f0ecc69839bd39ccc3288e.nq.gz
│   ├── cd67ce8dc7c814e093e8a766338c151bbdc598d4.nq.gz
│   ├── cdb4ac4096a80449351681bce80022dc550da1d9.nq.gz
│   ├── cf644190565441655b82af4e9df9cb44bbc9638b.nq.gz
│   ├── d04960642cbd6eb94814d591411019829ca7bb55.nq.gz
│   ├── d4f6e4bc2903497d71eafe9311319d6132de76d0.nq.gz
│   ├── d6d27672c66bffc027223c59d1e6c4c58c83b9f2.nq.gz
│   ├── d72d28486235ffb3d903ee7ac04d2c31d5a8c645.nq.gz
│   ├── d739e01011d61b4bb5a4be54d085a166e28919b5.nq.gz
│   ├── d8528ec31f52d1b2c5b7aec4125a4d238cf1d60c.nq.gz
│   ├── db53bd7b536de9a14e3d415c5c4d78259d3c04b6.nq.gz
│   ├── dc48160da4bcbc45ca35c794cfde9584111977e4.nq.gz
│   ├── e06d2081865a766a8668acc12878f98b27fc9ea0.nq.gz
│   ├── e0d81db777f56ec6ce771fa073929b52c93341b7.nq.gz
│   ├── e2f1dcf0883779f7b9a215c10b575b0a36b61f52.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e89ba5478cc425a4d6175b0737ba4e093cffe8df.nq.gz
│   ├── ebf38ac1870d3836e3072074cdbfce212abcb562.nq.gz
│   ├── ee65c7fc63d92c5c703c8d78ed38f7c2444a4f13.nq.gz
│   ├── eefa5c168001e60562ae0479a54284e4cbe19e82.nq.gz
│   ├── ef1051b4c1cac4401a9ee1068e6cc527f9364c22.nq.gz
│   ├── ef10e5afcf3fae8ba8eaf14ad360cf01c5f6807f.nq.gz
│   ├── f177df6d090c8fc08e052f6bcc6f38bff844f9f9.nq.gz
│   ├── f3b1fc32c8ab12749f2582b266143af15b4adcc6.nq.gz
│   ├── f52456e3addcbcb345b0f5892a9be52dcab722c1.nq.gz
│   ├── f57b5fd6dafbba77bc60bc47e6265eb9b7bdcb8e.nq.gz
│   ├── f66a7787bd5b456b3f677e8aef4e7c43152c4ef6.nq.gz
│   ├── f6d921f82d61727b37a8a4c384766b7759881b42.nq.gz
│   ├── f753b059c02fd5f3cb1fdb581a1c6b14974725c0.nq.gz
│   ├── f79e870e4af88ab1e388b40a2ad007c73e8c8fc3.nq.gz
│   ├── fa82ab8bb066eca7994ab2e1c3471adff20b41d2.nq.gz
│   ├── fc49fa68a16e85554daf4f1859eb13d0f6a2e9bb.nq.gz
│   ├── fcf643122bba0e44bc2f6ed4ebb19be285b24c38.nq.gz
│   └── fe9897effd35614d3823620c39c925a655e78fb1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3fba7d3e19c84e5bb1f15c22b1a5a6db6e8f07c7.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 189 files
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

[python-distro/distro](https://github.com/python-distro/distro)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
