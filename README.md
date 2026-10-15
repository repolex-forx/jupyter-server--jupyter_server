# Repolex Knowledge Graph of jupyter-server/jupyter_server

RDF knowledge graph data for [jupyter-server/jupyter_server](https://github.com/jupyter-server/jupyter_server), parsed by [repolex](https://repolex.ai).

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
rlex download jupyter-server/jupyter_server
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f8169d721a0e0abb9ca27266c83db5a3a09e29d7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f8169d721a0e0abb9ca27266c83db5a3a09e29d7
│           └── chunk-001.nq.gz
└── blob
    ├── 0007656dac60eab5694062f3092e9dcb8f3bfd51.nq.gz
    ├── 0203d1896a4fc68d4b572457207e6f0b9449f777.nq.gz
    ├── 0257ce071a8de5d62d91622e539de5d52bbf6c3f.nq.gz
    ├── 04ef5c46fa804f7831649d15929f1083d5121617.nq.gz
    ├── 050f734eb4269d7ddadcaa12391f6a63e863bee2.nq.gz
    ├── 0559a09e0c2db88f256ca5190f5a29b3f122634c.nq.gz
    ├── 05621e55064ecc2281086c2115bda1389a3fb781.nq.gz
    ├── 05ba92732ff4dca5e860c0af6db4d65ba3e2d59a.nq.gz
    ├── 05e3dc3db2b03a2d01624fd6ee071826cc535ab2.nq.gz
    ├── 076177a497fae1482179137af028465c4f6b9c94.nq.gz
    ├── 07de3d97820380639398e48d76416134916b3b72.nq.gz
    ├── 081816a4017fb5322a4f2294e5767e78f25bb7e1.nq.gz
    ├── 08af0fd1110640bfad5161572d750278a1c08ecb.nq.gz
    ├── 08ea9a76505ab3a4179754c63efe6a910621f69c.nq.gz
    ├── 09c96f0c768abc6151c8311bff75c88f2538fb5b.nq.gz
    ├── 0bb59824d7ad082679c6738ae53c76fe842ae071.nq.gz
    ├── 0e8b62c75c36458a6f5dba30ac30bf99be91114d.nq.gz
    ├── 105be78362333e465feea8d91af52462d1ca14ec.nq.gz
    ├── 1077c5f4d388f0cfaaece57078bf34b1695a9ed7.nq.gz
    ├── 107c1b5bd2b99f7f871d76d917536305569a1985.nq.gz
    ├── 13f6a762edc069e8c461e0d3d1012532024534ce.nq.gz
    ├── 1494fb3c25c58ecd7e93aae010e180053081273d.nq.gz
    ├── 1515ef2943bd25a7beec2df5d7898068e1c2f0e0.nq.gz
    ├── 189cc4cd957da18e1828ff1abb8997ce1314311d.nq.gz
    ├── 1911bf6b17943c5a9282c241e381be1db1fde363.nq.gz
    ├── 196c046763e2aa2279b67cd0121f24e8aa80de47.nq.gz
    ├── 1b8607cc213d758335d39573e38d3b5fe8e611ad.nq.gz
    ├── 1b887459996b9d41dd1437381972fd3a2a40a2ea.nq.gz
    ├── 1bba4f547725e00d33a149817d2202f7af3c575f.nq.gz
    ├── 1be3002bfe4afc4333af5d57890e77140d14c1b7.nq.gz
    ├── 1c07bec0d3c0ad53c226b10e99488b47aa8f76e4.nq.gz
    ├── 1d3b19020532f11163d4eadaf2f24ba76a27bda1.nq.gz
    ├── 1d9d27814b526d4d0390ebadb4831215abdd0127.nq.gz
    ├── 1e946e92c594a7dc355a841b07fa91a2f069cc7e.nq.gz
    ├── 1f1ea64ef7d014c5d14566c0181fbebcbeee44d9.nq.gz
    ├── 1fd10387c5ea61dbd7ba6d7d2395abfe72fbcee6.nq.gz
    ├── 20561a1d19b82efb8ca13d2279cff1c1bfc5c599.nq.gz
    ├── 20dd16c3522670ea9d9e5858dfab5180ab0fac52.nq.gz
    ├── 21c5eb796ebdf0f65ca544e6c4c967fc7e8d806a.nq.gz
    ├── 223d4fed2c2243cc9c63fdde92fdb7a404d0f76d.nq.gz
    ├── 2265770d8c208c18daa78eabf6dd03e21c57c1db.nq.gz
    ├── 24486a84321596a496ce0c93b7fcc269fae50dcc.nq.gz
    ├── 24f948d4c83cae82b13d2cd7de664fc71aac1005.nq.gz
    ├── 26bac5ba4e59f52516423ad44e9c41ecc9809205.nq.gz
    ├── 27452c12468f0b16c0b5397a3d0109beeaad756d.nq.gz
    ├── 27616bf67f44a5329c28d1f9d3e170d171cdb4bf.nq.gz
    ├── 276cefc6d3669441697703e5812cb744bb149a3b.nq.gz
    ├── 28562c2748695dcb7951c1a3bc7dc2d776973824.nq.gz
    ├── 287a167bda9be8a09a1ec5074ef78e7d98b36c89.nq.gz
    ├── 2a0765d5936a56a905ac582d2c9794e22dc4781e.nq.gz
    ├── 2c01cfe266435c52818a0d065bc0b2bd39066ed7.nq.gz
    ├── 2d1bcff7ca0ed6c77fdf1b016986f9137a43d31a.nq.gz
    ├── 2da9cc1925a19f7599b5294c658a789e7d13ffd7.nq.gz
    ├── 2dca22a1596b1b398e4441e67da1f6bf361fcac8.nq.gz
    ├── 31021a53ce5ffa85ddcada31e4d7eb42f3838b09.nq.gz
    ├── 3237ddf0873efd7cf64051ecba54a666a1bf207f.nq.gz
    ├── 326e1e7c7037839fa67ace91e30b009af7a3dcc8.nq.gz
    ├── 329f8b77ea11a37aafb90792e0d1c0035f5b6277.nq.gz
    ├── 33683b45e9631402558859003fa5491898e13c78.nq.gz
    ├── 348d628d13cc567031a14e2eb6dbb032209dbcf2.nq.gz
    ├── 34da0a267f59a33237adf73a80aaed4c57a25c62.nq.gz
    ├── 351a95304bcd68231ac06527c9dda210ea88dbdc.nq.gz
    ├── 353194426daac3bba6566ab79c9e647fa1606e71.nq.gz
    ├── 35aa66a07890974bf95617aa7e7caf3544ca6b07.nq.gz
    ├── 35bb60daa116c4d1cd259ea173dccb28d60ff2ef.nq.gz
    ├── 36418f214b8ba3b1e9714619ff72f665d2e73f39.nq.gz
    ├── 36dd88b8c48bc3c7fb3ecbf41400acabd5414048.nq.gz
    ├── 36faaa922f89b1344793025e97b906f174299f01.nq.gz
    ├── 37f14edbf31556ca9f02bde8e453f739332a5179.nq.gz
    ├── 385a35bd1dbb86d0ad1eb9cda427b762888e6f87.nq.gz
    ├── 388be8b12af6d9a6c9ac729368f5396405bdfc9b.nq.gz
    ├── 39bb60ea59810ee94f0d07fcda5c816cb48f2f8c.nq.gz
    ├── 3ac2ea8f57cf2c6dd059335d228d3681237d5824.nq.gz
    ├── 3d166cffd961fc86dc46a5c513954213b94f192f.nq.gz
    ├── 3da8285874a8bf0461168b25cac7e515d1099eeb.nq.gz
    ├── 3df85bd930ea2348d35589d89322763d16e13002.nq.gz
    ├── 3e50941cf523799b79c69fa9b5134b7ed0d50d7f.nq.gz
    ├── 3f3f57ff39432a80c15dabceb99141bc7ec4318e.nq.gz
    ├── 3f97e84f40e19ba2f5c86da20a009517c576c975.nq.gz
    ├── 3fc66296eb92af0789c4cbf43eab0fc136d3222a.nq.gz
    ├── 41a331a78e0d4f96db6a55241e252a80240beb19.nq.gz
    ├── 4284b4f9dfd552d766b7621569ace275475fa30c.nq.gz
    ├── 440bcf9c09fc8608cfecfe1761b6c8bfd875a593.nq.gz
    ├── 44d6174b78e54f6ae4a15d7a2bb5116218c8747d.nq.gz
    ├── 4537e2d989843ae1a96a0548aa0a7066a22e2698.nq.gz
    ├── 4927c2243a906c1baa4a9079c2cd76ce4fdde627.nq.gz
    ├── 4a3b68c3c64a14872e8acb2e6235658888502ed9.nq.gz
    ├── 4a466ef830d7afa43c6a446b5177f48dd3b4528d.nq.gz
    ├── 4a8b841c2bb765c731c7d8d53bd954d642712b49.nq.gz
    ├── 4f0ca4934ce94eba52aaf92429d8cf53d6b8198a.nq.gz
    ├── 4f95513e558e23db7cbf3f6d2e5db0a3a8b9fb26.nq.gz
    ├── 4fc2efc86d9673d506e4abf50ec7bbef13d18c7c.nq.gz
    ├── 503ed5c1a7d1b1f566e57fe0b4d1e15e7987e4c4.nq.gz
    ├── 50c7ecde60f7a164c971226f926327544e7059da.nq.gz
    ├── 511a8d319be18b989e2cc3990641e727db36d903.nq.gz
    ├── 51fe76f1ba8d0b43fd50405653913f09031a545c.nq.gz
    ├── 5329ca82c63f50f64102d0e81b71f8f3562d9e4d.nq.gz
    ├── 53d4b3df0b2ac3c578e3332a787acf3f403ec31a.nq.gz
    ├── 5581c29e1f34910edafb1cd0b3cca39d1c1e68a2.nq.gz
    ├── 55db0ce4beb889cd336259e5a9e7bf0694876e2d.nq.gz
    ├── 5667c3efaea972ba612f41c92d8e8377c5e2c397.nq.gz
    ├── 5710534f5121901599b205b19c9529816e78321b.nq.gz
    ├── 575093c6e172168df0f855fee99d3a7a45e7a7c0.nq.gz
    ├── 586c16b0b9cad83f215f17778ec51c23c28baf2c.nq.gz
    ├── 59707e8aa9885087f1a9e1868a61914ab0baa9a0.nq.gz
    ├── 5a6fca5186a76f35e940e49f9cc5e34bfb706134.nq.gz
    ├── 5acc57fa89bc1ae5b2c38c35c8aac63e6b9bcc45.nq.gz
    ├── 5b46a822610b0f49bad2579cbd0ff8bfbb80d0fd.nq.gz
    ├── 5b5dc9fb976eb82356341ed7f6066d932ee320ee.nq.gz
    ├── 5b83a5ff8e88d258822f825ebbbf06e41725cc7f.nq.gz
    ├── 5bf500ba12f47aa20bb160286e8a07c5e8586342.nq.gz
    ├── 5c77da70496f84536ac26f563d5a21f696459011.nq.gz
    ├── 5e194547c916a440e497697256dfba013ad1ac14.nq.gz
    ├── 5e4893f508f41a9b9cde73f2d2b3f0e65c1bcee9.nq.gz
    ├── 5f05ba0d7ad5d7ecee4257e89a6db2154e00ef24.nq.gz
    ├── 5f41dbc4107594c7f28d5670666efdb540ff7d51.nq.gz
    ├── 600e52e9fa73e75718725b284def565b79dcb035.nq.gz
    ├── 605b94e158a0c030c4bbbde3822c3d3a73549305.nq.gz
    ├── 6181345aa3c2eabb212006e207c0997caab89838.nq.gz
    ├── 61c9d10826e8aa91a2f95cb783e875c96395a938.nq.gz
    ├── 61e11a948e7273da4c1685f7570861e25cb8b62e.nq.gz
    ├── 65baa81466fb683f264c488e2f74c5fcc6b96990.nq.gz
    ├── 65fab14f9b8e303bacc2982e51e0151011d02671.nq.gz
    ├── 66c13802c2563ba0f1d21c9b054b9adfbf8de24c.nq.gz
    ├── 683e340a761a4a06832366ca2736fef33b062b8f.nq.gz
    ├── 6857ee2c6328a6ec85faca16c1834238ed4dc7fd.nq.gz
    ├── 68e9e4f2b9c2db4b00288717ccb172de556f38e3.nq.gz
    ├── 696cba7292f49fbe480c1af3c49e02ab955fedcb.nq.gz
    ├── 6a7243333ce1c250375646fb923316b2ba1bc147.nq.gz
    ├── 6ac99f64a418659c2c1874510f566acef0587253.nq.gz
    ├── 6b9f5afc4a91ed0d54d0fb244eff5eac25fb1a6b.nq.gz
    ├── 6faf19d81313f9a9e4a1687267834f0de3c26544.nq.gz
    ├── 70a8ef34bd97ab6425f1a63857c21594efc95bcc.nq.gz
    ├── 7191b86592d19174b81e202a06e336ed9bdef426.nq.gz
    ├── 725feab5ce652dc39f3f2c77b9fd3c90bf049c65.nq.gz
    ├── 7322bd1b82dfa58cb602907e7abf9a243a40654c.nq.gz
    ├── 7354d6a0949a423d85aea97317ce2c69260cd74c.nq.gz
    ├── 73b5527177600a7e1b519341c6fad90a8dc46dd6.nq.gz
    ├── 73f66396e27f027e9114341112520d79d5149257.nq.gz
    ├── 7414e681515a8c447159bf3b9f56134886907008.nq.gz
    ├── 741c9f6eb24addb45011fcb1d0181e38b59c4797.nq.gz
    ├── 7496d8fb51dde4b282a72cc64a49560ab0329c67.nq.gz
    ├── 76f03643897358eb7a58831346ac21292943b044.nq.gz
    ├── 7769acffee7ec1752ff5d549fdcbb82128ad989a.nq.gz
    ├── 77f5bac685bfb1b1640eff3dfa5f93bb959783b4.nq.gz
    ├── 78c0dce49a3c7a5e023172b8e6fcbd3fe4b5931b.nq.gz
    ├── 7910e447105e33170b38c838678bd749624f2d61.nq.gz
    ├── 792c200586808da19840903f025e59ead87891e8.nq.gz
    ├── 79c9b268d37ad368145b0071657109ce012f0283.nq.gz
    ├── 7acec8ae590e1a10f37a900ae802465654f222e9.nq.gz
    ├── 7c13c7cd363017b879524c18cadb35ad0aa4776b.nq.gz
    ├── 7d3d4b909908b96659b8759e4a7f7bc452065b4f.nq.gz
    ├── 7da320ebca3ac0cd605c235a68e9a28a8c061283.nq.gz
    ├── 8167018cd005ff4a24d8287c620539e23c69aac9.nq.gz
    ├── 81c8aed5b9dcb39a84b818853501ba6e6aedc9d0.nq.gz
    ├── 81d2df9479d16c3e206f56a27adf2eade408bb02.nq.gz
    ├── 846aa2cd05bdcd88e4a10e5c14d97369d312a2a9.nq.gz
    ├── 848740e0677296eb026dcd65f147cb3e7d5b6529.nq.gz
    ├── 84d63b934c43884abc46d802953cf266b1484e09.nq.gz
    ├── 85714f4a524428660685a7b3590c10171edf32fa.nq.gz
    ├── 865d6edae1a060ceb7c8b768995b49a3f6abe18d.nq.gz
    ├── 876b968a35f416402b7c5efc23a3d672e30f9285.nq.gz
    ├── 879779522bfbefc53c6bd7598ab1b48325ad1465.nq.gz
    ├── 882b57c07999cc68fd6de808b9f9acf6470e6260.nq.gz
    ├── 88c78e545308448885194d571d8dce340ae56ca4.nq.gz
    ├── 894f98b011250dea0daba3bcea47ce6655776b99.nq.gz
    ├── 8aa05c2251b364477483ee3743c093214777d4d4.nq.gz
    ├── 8af22caa9ae3e62350c241f58d1f792c338de5f3.nq.gz
    ├── 8af608b46c071e775a70bdeb6d4de34fedd0415e.nq.gz
    ├── 8bb2356478572f3730f33bddc4c5d704b0762af7.nq.gz
    ├── 8f0162f7fe76d4127df7dadc1aff947a5523a0f2.nq.gz
    ├── 8f49cb7bd648392ca2f8e9a13a9c56944c159f81.nq.gz
    ├── 8f65bd35bfd342bba13b332ffc166894967385df.nq.gz
    ├── 912e81881779a72fb47bb2e10309cb4e816f75f7.nq.gz
    ├── 91ba97933b4427e6e6bde3089f61ee72485d88af.nq.gz
    ├── 91f7da334052877a648d793bd6850941c0201f1d.nq.gz
    ├── 92b991efad3edbf6757f02ce1dc3f45193c6127a.nq.gz
    ├── 95574f649d795861136e13be492cd4f8440f8bdc.nq.gz
    ├── 96b1fe04a7f4c86ad97d0ed9b163af2ff2365fb2.nq.gz
    ├── 973a200d819673446b64ea2efa40eacc83335838.nq.gz
    ├── 9895de39a3d6069b9bc26cb17945625e9e8b4dba.nq.gz
    ├── 99dd1c262fe38e8a1ef88661f165197304a78818.nq.gz
    ├── 99f0c9d7a75af57acdd6f02d2b7ef57c14c53f90.nq.gz
    ├── 9a3a6233d2a4c79dce00752e4edd97710cba437c.nq.gz
    ├── 9baa2e4c66a3900ecb1a8b2ead3514606c1a103e.nq.gz
    ├── 9bdfb03672d7dbf62a407a78bed79521d9ee7803.nq.gz
    ├── 9cf0d476b19fba6ba10e1a1430444cbb2a0b8850.nq.gz
    ├── 9f69958f4beb9b7cdc20f06cde9fcaf89f1cef68.nq.gz
    ├── a0a2e9d3f0e1af28bba4adbd8a107325fa8c6ae1.nq.gz
    ├── a13cb48a23aeb57c0ae1f2d1986c67be5ea95fcd.nq.gz
    ├── a24b0539f4b52f4e3ccc28d86d7d94768026fba5.nq.gz
    ├── a263a46a3ef2646100bb1ab3419495f46f85a2a7.nq.gz
    ├── a28f60a2b33aeefb20b23fb4a35bc3eabc1a5d4b.nq.gz
    ├── a344095ed641e1caa4f4ea08698ef9f6335f0714.nq.gz
    ├── a4064a80b4111a397d43ee5135bd33bbcdea9399.nq.gz
    ├── a4b72826db22cab763bce4156bc53b2d02e8e710.nq.gz
    ├── a56fd91c11489c830c928f0a2ea035723a81b9c9.nq.gz
    └── a6079ddcb31b5d6a2b7ef12535455a7d276d4c6e.nq.gz

7 directories, 200 files
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

[jupyter-server/jupyter_server](https://github.com/jupyter-server/jupyter_server)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
