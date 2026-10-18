# Repolex Knowledge Graph of altair-viz/altair

RDF knowledge graph data for [altair-viz/altair](https://github.com/altair-viz/altair), parsed by [repolex](https://repolex.ai).

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
rlex download altair-viz/altair
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e98486cac6dbf8d47092355bf1b535945379c21a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e98486cac6dbf8d47092355bf1b535945379c21a
│           └── chunk-001.nq.gz
└── blob
    ├── 00f47a6f5ffddae52739cb4bf0909b4179953ef6.nq.gz
    ├── 0101cea91ff6ecd9294b49641836922ae7cc7ba8.nq.gz
    ├── 01048af51f8358398eb41bdcfc39d6e1a7c41970.nq.gz
    ├── 0163cb85fd587216df01aa14450ad887360a966e.nq.gz
    ├── 021114a753647ae37afc0a671a0255e9f16cabf4.nq.gz
    ├── 023515e02af92e6a38245d63f586f19e31e88268.nq.gz
    ├── 0243b0ed2c04070cdf863efce1926d81cf935787.nq.gz
    ├── 03023347c4f8991e397373ef7bdd35d3751d23c7.nq.gz
    ├── 035e4cda8132e85340fca89fda16a631061b32c1.nq.gz
    ├── 039fcf7cda20630eb978494e5e7c75445f17f1c4.nq.gz
    ├── 051e6c31e040f4c2f866f8aedfb710d7cab93e9f.nq.gz
    ├── 054bcbfd92472832e91c605ac1f76587113527c6.nq.gz
    ├── 057824cd17eea05604fd0f1f45c13ad9e3e49fe5.nq.gz
    ├── 057d299d84ca81a320c395e9943f4fe7977f400b.nq.gz
    ├── 059698de6202ea2c42bdf64a798aaf770989c369.nq.gz
    ├── 0596a15c85876ec5c912f97fb2ae59735282ce1b.nq.gz
    ├── 068bd2a3ec948112ce87a7f3311d72179ab4559c.nq.gz
    ├── 07c4ed54b60f5e298298201fe9ceb623e7c0098c.nq.gz
    ├── 07ee0e6ff4368909a86a39a22dd53539479d14b2.nq.gz
    ├── 084290afaf8d85887b674bc2218e6016491e4473.nq.gz
    ├── 0b16b67c9e19e242e14cf7f6d44e871e6fd45fdf.nq.gz
    ├── 0b3a9c3c68aa72e4a3a6079747c28d6b9a95112a.nq.gz
    ├── 0b52bcf16fbf9e67a5cf83ddec38c4ddf8d5f081.nq.gz
    ├── 0be6270d53574834e3a176aaee1323936570e791.nq.gz
    ├── 0c68c3b2a67e6dea7e584fd479d1dfb35a3c6510.nq.gz
    ├── 0d1dd27d9bddc17f77a225dc56ff8b011e14e393.nq.gz
    ├── 0d5c038736ff4e31cff370b7c8cda8ff08bcd47a.nq.gz
    ├── 0e290f23c5ff96604bfae8bdbedac3c7cad60784.nq.gz
    ├── 0f153a2ec26ab799000d18390cadb59adc22c248.nq.gz
    ├── 0f573997e516eb2ce0dedcc980f5b68ea693e224.nq.gz
    ├── 0f5a6050d0219b72a58be704248fe4dad5f42bda.nq.gz
    ├── 0f5a800590e570048c42068a05e4bf7405528c9a.nq.gz
    ├── 10140bae83d44725cff36bb35256d2ab4289d3e9.nq.gz
    ├── 1047f03e35bdce0ee8c0eb0a9755fc0ab3d238cc.nq.gz
    ├── 10b5a3af85145a0549cc0c41c6d99b24bf71d551.nq.gz
    ├── 10ca93e351e3de69c50c70a0f54b61c589d55d87.nq.gz
    ├── 11d98e7c0ab654a1957c424cd06e117b3182d618.nq.gz
    ├── 120d57ef2dd244e20b94b99ec36437a0e122c8df.nq.gz
    ├── 128bb9d71b41e54612d95622cfb1301d8c249e56.nq.gz
    ├── 12d1550d734b41f9e6c3736da51244a8d2cf1cf4.nq.gz
    ├── 130022d1ad70537f1be96a7e5374818224904b99.nq.gz
    ├── 141dccbd206463b794be8e3c871ae4872bf06dd9.nq.gz
    ├── 14b4c9af59db6eecc13235b833f62255551c40a5.nq.gz
    ├── 165031d702cbb94325025102ceaf6634875de63e.nq.gz
    ├── 16b2f055824b5f85170f0670b7bdc238e1c49d57.nq.gz
    ├── 1741e6f54c6a097ab506cbc076c17765f682f92c.nq.gz
    ├── 17db1be684b8fb0eba4229e5f22ccabb887e85a0.nq.gz
    ├── 181419fa56e26493f7a0ca410d1f0487e6899216.nq.gz
    ├── 183fc9c36738a9367ec640b443e52281a76af88f.nq.gz
    ├── 186407472a5f4851b120fd54f44613c013412184.nq.gz
    ├── 188a86f8b371c413d9eb3723b390e66d50592394.nq.gz
    ├── 1907bb9eef01987326216cb081cdbdd0c88731ba.nq.gz
    ├── 1916cd9a6239707bb182bd4ee62e4588265407f8.nq.gz
    ├── 198c5521ccb113ca78e9ed3c2eeaa2a023c2e61a.nq.gz
    ├── 1ad1c75fc3c0831588f0d1fc2dabd73ebee9a03e.nq.gz
    ├── 1b7677cbf367f56b05ea9f3f423b7aacc584db99.nq.gz
    ├── 1b7be23ee1e3658b4e98b8577e0ce85517053081.nq.gz
    ├── 1b90b1da2a1afed4dc36e437ecaa53291a99a119.nq.gz
    ├── 1cbfcdb48c0b84d70ed67759b75a1cdfe6f9ec2b.nq.gz
    ├── 1d8c0b753609f40d37f162e230bc14be84f16af6.nq.gz
    ├── 1e135a9b7c610f9c9a4a672d57ea2f82ae7833f7.nq.gz
    ├── 1f04beca8b95225180e6cfcb1c6dde94f493c11f.nq.gz
    ├── 1f844c945270407121bf4211677088395e716ffc.nq.gz
    ├── 208c1682b92336b505fde29a5751f74948e3012b.nq.gz
    ├── 2224f3c25e248ca48756897a02adbbfd5f0e57ae.nq.gz
    ├── 223ef95b2340c0e2a0b1c78d6c995dd4646363cc.nq.gz
    ├── 224716333d3f25304f1f7370bebca7fdd92ed988.nq.gz
    ├── 226482e41a742f8984c1b97d4eb92f6a641d43fc.nq.gz
    ├── 229403e1eda7c0abc6a224e7dc57706f04b0b960.nq.gz
    ├── 235a4ecfc399afc9735eb342096c12bedc62cc5d.nq.gz
    ├── 25fea5388fb2262afd7a82173913fa8f026f09e1.nq.gz
    ├── 2683e74f4443f2474202fdd3e8ce497b2f7547f9.nq.gz
    ├── 26d1ea63deba9b89db3b3289127df8b11a326c8e.nq.gz
    ├── 2739c3ce7f22302ad7adbd7b36ecdb03ea14b1b7.nq.gz
    ├── 279cab9708841bb231771eab9cd0daaecc481355.nq.gz
    ├── 27a5daaf10b9d8cd841def37b6897ec7df507664.nq.gz
    ├── 27b233978281534ca86bc482d66cf31edd56bc04.nq.gz
    ├── 27c3d314f0b5e46e56796fc77824a4be97313251.nq.gz
    ├── 27cf7a87b3c30f061770e737a9d7e5132dd18483.nq.gz
    ├── 285639b68f6d9b9bdead39eb501ca966ce481462.nq.gz
    ├── 288186fa0cb2e30f56b0925780b28c4a4e73c0cc.nq.gz
    ├── 28910b68f33becbc9ba4cc0d071bd0d6aed1439c.nq.gz
    ├── 28ab8e0e766e25d966e2f4195e67a84b9c08bae8.nq.gz
    ├── 28b8299e81082102bf50faeb4029e33b82fc051e.nq.gz
    ├── 290eededc0dee628895d9e5f057bd176c7a555ed.nq.gz
    ├── 29bf1835cab22432a050f88b8193f121df5fd92f.nq.gz
    ├── 2aae874ca7114cc9545bc79b38afa87184e8a5d2.nq.gz
    ├── 2af8859c397055254c3a83cc05aa747beb4e2c26.nq.gz
    ├── 2b016d82968adc5adcc8debb796befae70128684.nq.gz
    ├── 2b355b8bf5a532167b38e616b843a69180ec18ba.nq.gz
    ├── 2b807314c4f8ec47f6a39d9e19fc6ab2b163b4da.nq.gz
    ├── 2c338759f8a1587af893a090139d2344fe318b2e.nq.gz
    ├── 2ce3b9de0b8eec6f7e8f71a922dbf48dd9fb468c.nq.gz
    ├── 2d1a1cfb5a9a7f468ff337518a555fa203be2853.nq.gz
    ├── 2d2b44df7cb261cbffc96f0a1fbb156493ddf062.nq.gz
    ├── 2dab50bf18e5cd65698bb26dd521bd283f3867f8.nq.gz
    ├── 2e1e2fd7a238adf5450f5929e861be2d08f69e9a.nq.gz
    ├── 2e63cc125f11d63ef486a9278ac5f93dd1b018fe.nq.gz
    ├── 2efcb2f434bf9299852f72d9660eaf47fd45e7f7.nq.gz
    ├── 2f063311526ea867149e8b3598ed01e17781e426.nq.gz
    ├── 2f52b10f677e19f5af9269bee4e5f173a4ecbb6c.nq.gz
    ├── 30fdf21053350523655e307a4b878e8f4c48eb25.nq.gz
    ├── 313af8e8258157e4bbf66be38e2a35580ab6fced.nq.gz
    ├── 319dacff7f3eb6a2852c6787b4d734bb1796cfde.nq.gz
    ├── 32c34815358e57d58c91c6f2135ab708e4e4013f.nq.gz
    ├── 32f953124de5b1e46208898b729a4d4e38b024a8.nq.gz
    ├── 33a713af31e317492b6e9fcbfd1d82730a47a4fe.nq.gz
    ├── 3429f67184a093c32c9db1b0d75987cafb76eb36.nq.gz
    ├── 3449142aa274d29766a38e8115209d4f9c138de6.nq.gz
    ├── 35796dffed66d52d3dc9361d785ce34321a51c0c.nq.gz
    ├── 367f7b61186a849b39bea6208f529d95f2f745ad.nq.gz
    ├── 36b786ac02a0bf481e0f33f000ee16123f0365b8.nq.gz
    ├── 36f3f111373de77e0120345928016578db6d8492.nq.gz
    ├── 37171407ad1ef50e76537b4f82f0e2429297302a.nq.gz
    ├── 376a0eeb3f97862cdfa4c058343e8561ff8468f0.nq.gz
    ├── 376df853b55159b7fcb1e95b104921ed5850f8a9.nq.gz
    ├── 387eff70b054130ef08f8478e07dbc40dfce5eed.nq.gz
    ├── 39d27adc262fdd67e3c3feca103d0a626d08d1e7.nq.gz
    ├── 39ec1dfa0667839e68ffa5735bbeb8f3c7de68d9.nq.gz
    ├── 39f1b6cc79efa98bec658338e70ae6fa3317808f.nq.gz
    ├── 3b2afafcb5cf2310b0d554f270e07cbca9360b1e.nq.gz
    ├── 3b53ffd5ac78fab38372e9c0e906fbafcc9be30a.nq.gz
    ├── 3b7eb617f3819bb287f34829fb9431021314548e.nq.gz
    ├── 3c24761c67cdb7d50ca7ab15f1e3943e8006318c.nq.gz
    ├── 3db8d68f334469a63397a2aa1b96bb703650d069.nq.gz
    ├── 3dc5964e8056b06d6bba65a03e64861b6175bbf6.nq.gz
    ├── 3eb1d1f2122fab56a0afb77f74492ac5dac617ce.nq.gz
    ├── 3f5709a3c07aeb1fc2906cda8b45f1c0ce530e76.nq.gz
    ├── 403b7705d82c36f6611634bce7e8ce7795b28829.nq.gz
    ├── 40d7cb4f0aac836bcd169df6e7658c8130b2d6d7.nq.gz
    ├── 4158322eaef254bb2f7957d7781b256a73e6ca57.nq.gz
    ├── 417820082cd9ac68b55c51f6c6dffbb75ec7623f.nq.gz
    ├── 417c8d440e49498877b694b88a5486710b8085e5.nq.gz
    ├── 41c7264cf7799870719e10f8b12d6e994ca30cf1.nq.gz
    ├── 4221f4fdc9bb37cbe75e8e2ff42a9db7f12be484.nq.gz
    ├── 42ab2dab1807e50fdd9beb8a3d58a51d3b97b0bd.nq.gz
    ├── 432117ec03799c79d580222b48c401202164dfb6.nq.gz
    ├── 43282ad8d8d7d8a9ec771cb27482bbce1dee781c.nq.gz
    ├── 4328ff62f863bbb8862daa6ab73f3809e5585bb2.nq.gz
    ├── 432a209eb9893ce8da8b9c84347734f7d34b3fe4.nq.gz
    ├── 43516c7d7a703e984bd2770060204560fcdc1f5b.nq.gz
    ├── 439dda29424ac7da8a8e7a90d80b45ef761b90fc.nq.gz
    ├── 43b7aded2b3f0a659a2142da5f2e80553cac5295.nq.gz
    ├── 43eb055f59422e53d829f6dd238abca504c46119.nq.gz
    ├── 43eb81ece55343059a18da5870f18f2544febb85.nq.gz
    ├── 44bb7d079deb35cab9da39fea6ca9d22d2ae7469.nq.gz
    ├── 44c010ea09fb5df61f516bd9280e18f6ef91aac0.nq.gz
    ├── 44c6f52e593ae1f63ac3243d956a37c40e29049d.nq.gz
    ├── 45100e2d7eacf19d66d18734fb810e898ea1cfad.nq.gz
    ├── 4588d6cdeec66552233ad90668c9d537fce4e0ad.nq.gz
    ├── 46c523ebd63dee06039cb137f0f1bfa31e2a92ec.nq.gz
    ├── 46e34e8dc05006e3c71e67752cfe346c63930be6.nq.gz
    ├── 476332d2904553f5de209e25f79bb416418932c9.nq.gz
    ├── 476d4a05a90ec0742c4400b916c5be633b5ccf1c.nq.gz
    ├── 48a029703d7c9fb198348298972d357dc34e064b.nq.gz
    ├── 492deb976357abcba0cf6295078fefc1b4e80d7f.nq.gz
    ├── 49632cc7d6a1c6f198a1e8e86a62df7ea474fa1f.nq.gz
    ├── 4a00ee9a7745a8c6ab301083d718f8be20207c9c.nq.gz
    ├── 4b2216325c22f9e97f1bc5d6141d8b58c9d6f86b.nq.gz
    ├── 4bbe238076c0d2f7f9300e404c2670eb34bc38a6.nq.gz
    ├── 4bd7c8bf7904f634394d4acd1cbfc826bf7206d0.nq.gz
    ├── 4bf09d2bb0dae697e4d81de1b478353ca32d78f5.nq.gz
    ├── 4c78e70bd4dc0520b02a0538a3b40cf141c3da82.nq.gz
    ├── 4d1fed65a0216f0a1c0694bc1084726e9d6e81f8.nq.gz
    ├── 4d6e96a44298e58237a6a5c0902930d2ee41103f.nq.gz
    ├── 4d919b650526ebd1486229a332ffea6295296a28.nq.gz
    ├── 4e34989b195acdac0a80a2bec47c66b1fe7a25fb.nq.gz
    ├── 4e41b7572ed586964ba5d7d6112a8a32183dd153.nq.gz
    ├── 4eca2bfd87cc7a4798b1aaff6472cd9591c53d6f.nq.gz
    ├── 4fddc46535f64c4e4d260bec266c449d6e7be898.nq.gz
    ├── 4fe85c0588bc74d686b291a87cded0938e23bca6.nq.gz
    ├── 50a195ed1d49b01cf1f6641933dfbf4f3d0047c1.nq.gz
    ├── 51119831cd9659c22412c4a7c616c0cae835eb35.nq.gz
    ├── 511d28932a74655863d250638822e8e696468617.nq.gz
    ├── 511e29ca2ad2104d4cb5160461b6e08231832b9c.nq.gz
    ├── 5176c7c90e702b1b296a113b2561a0ae6b0a7dd6.nq.gz
    ├── 51bac03a08aa6defea688b12737a6c091abf5e21.nq.gz
    ├── 524bea56e97dd11f3247bea9bd7e3bd26df51c42.nq.gz
    ├── 526891ea170b7e36f39a81722f04030b001506f7.nq.gz
    ├── 526e612e5d96f4fe1767f86fe141821fc0a924e9.nq.gz
    ├── 52afdd6600dcaddcc394b35481ef6d4ec3e71b41.nq.gz
    ├── 52fe25662721768172bdb2135fdadfa512c78c6b.nq.gz
    ├── 53a58c986a64a2f3e56b216523bec3c2750d95fa.nq.gz
    ├── 546ab19a8fc9cbabcaf8a97c469117d893eb3763.nq.gz
    ├── 54c0a70c4160db730828fa9eb38e65db997e3a45.nq.gz
    ├── 55e31296c9148b67e187accc1ee73eae8240563d.nq.gz
    ├── 55eb9fc9735f610c04332e50025d1ca2d1a845f9.nq.gz
    ├── 55f64f95aef70083c8ea5351533d0bf0fdc831d5.nq.gz
    ├── 56afda0bc6c39df629006ee6dff9aff459251182.nq.gz
    ├── 56da4691c252171e3ecb6ece0bde9946466c8d9d.nq.gz
    ├── 58271c6a3828b4cbea428b73412d6914e1125f6d.nq.gz
    ├── 584760ceeb612dbcca49db4354f9229fb3d66bb9.nq.gz
    ├── 58f64eee00456e3f876e6e1179f13536b64cf189.nq.gz
    ├── 59fd04f65de9f40141b52db04bdd4f1c11beb9f6.nq.gz
    ├── 5a89c910a8e0b8edf08d43e8e8082324ca4e56c1.nq.gz
    ├── 5b154ae932d353f7aa29202030d88c4148485769.nq.gz
    ├── 5b33157d72437aa7e7aa1bc5df10725ab0559ab9.nq.gz
    └── 5d23881fea2e92bf3bd2adb677dee7a78fe7a5c4.nq.gz

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

[altair-viz/altair](https://github.com/altair-viz/altair)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
