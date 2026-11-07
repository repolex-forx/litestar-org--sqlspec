# Repolex Knowledge Graph of litestar-org/sqlspec

RDF knowledge graph data for [litestar-org/sqlspec](https://github.com/litestar-org/sqlspec), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/sqlspec
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 78a00b9b89ba604d0e64784e6c877121c2be2b3f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 78a00b9b89ba604d0e64784e6c877121c2be2b3f
│           └── chunk-001.nq.gz
└── blob
    ├── 01ac6640f111187dbe2780e5ad1305aa9aa747d4.nq.gz
    ├── 01e90ca15e646efd579296bb47261d9cb932ded0.nq.gz
    ├── 01ef2b56114b648c48a7f2b3d4c27269767a21ad.nq.gz
    ├── 01faf3a68993f5b96aa3b9ac306a248cf54c16d1.nq.gz
    ├── 02e716668dc883bbc6cef4a77274ccdc5a8a3b26.nq.gz
    ├── 032e699e2f28551767e6b70f8fa56ebb6a935b92.nq.gz
    ├── 0341d49148b34d0e0c917c92b4af12ca7a154996.nq.gz
    ├── 03f02755511a3de89db7410a63a1c439d32f94f3.nq.gz
    ├── 04a8902f2839dba993d2f0ffbd5598b35d059d4d.nq.gz
    ├── 05405f292ee5fc5a5954bd564e5e3cd9200dadeb.nq.gz
    ├── 06241c73f96edd8f60d6d1d1f06225c71b7500a1.nq.gz
    ├── 0658286b3a7bb3fa93c8cb44dbee42ec2846be7e.nq.gz
    ├── 08fab252d71103807bd068560bc4bbdddbbec3e8.nq.gz
    ├── 0a3d262593dc324554aa8e417f13f1087552401b.nq.gz
    ├── 0a5cca62a583cf823aeae804f01e5e8e8820c9e2.nq.gz
    ├── 0af956dc2fe3e757b407752655482b14b0ddda5f.nq.gz
    ├── 0b3148b3e9d1e1249578c017bf132ca1d4bdf7b5.nq.gz
    ├── 0b6170049f7b2eedfd8fc2065c9cd4d7bc035f0d.nq.gz
    ├── 0b9971c7bd2e6b06718141aab4d4d8f800ba0c99.nq.gz
    ├── 0c128957a52f3f2e72a815c4e120d08ee65464c1.nq.gz
    ├── 0d40492b3ea2f1a47a95bf5076dc2372fcede591.nq.gz
    ├── 0e99bb255349b8e508772c4c1af49e266ebbc69e.nq.gz
    ├── 0fcd4d5185a03575cff1410c184021d00d367f3e.nq.gz
    ├── 103ee1dd3299f0dca1e756d8ebc357b82cb55194.nq.gz
    ├── 10a0a1f6615e22bb57cc7a22af467ce7795da676.nq.gz
    ├── 10db86fe2f7b7b82c0d2426521b0bac7b9dd48af.nq.gz
    ├── 11389cbbe9f44e0ac5e78664f6680ee6a9799f61.nq.gz
    ├── 12fa9cf0a137efef3931c4edf10273de2629d02d.nq.gz
    ├── 1479c7fc990562940138fa89bc34f9d209573984.nq.gz
    ├── 14a45dd54bc7b10636b981f78cd1acd77dcd9349.nq.gz
    ├── 14e53d27d497c293a0bb34cd8134379a0ee2e86e.nq.gz
    ├── 14f8fad5cb68f2fb4d017252ec47e19c245075cb.nq.gz
    ├── 152c83b642de0e94bea1b86e4fc2088a5775129c.nq.gz
    ├── 15e61dd106160cd1c6c67bff5336861e0b7855c7.nq.gz
    ├── 1680b951bc5a088d25f5c1e2ed1f0b54334724d9.nq.gz
    ├── 16c2bf0c87139131588fc2903c17f62d077c9f2f.nq.gz
    ├── 1740ca562b09ad8b2a9fe9ba4ae9526b386509aa.nq.gz
    ├── 17b558fbcd6feb7b1f6d4349fa13e9cf2e9fc88d.nq.gz
    ├── 18386438795529b26c83429ee9b6b331a191d628.nq.gz
    ├── 190a4908fc7c7635c16d6cbf4614c9090f0055c5.nq.gz
    ├── 1932bd3ded97fd970c9204ea35801a7b5716b92f.nq.gz
    ├── 1968d84a497f541d1687f7cd6f54e8d7bc1090d2.nq.gz
    ├── 19c65fb07b4475dd718270566610f849e4e47b37.nq.gz
    ├── 1a2c2907ce4a3e42d08467fca090aad739eff7c8.nq.gz
    ├── 1a78ac877671c91369001e5984134f83b42682ac.nq.gz
    ├── 1aa253efc20d5515ca533f9430d83517c12ae063.nq.gz
    ├── 1aeb6ad89e862c983e4dc7aadc50af0a385a9ba5.nq.gz
    ├── 1b91d715298140406b495998b830fdcc7d97fa00.nq.gz
    ├── 1c64adf7a798a9263da27f3e151560be9b465575.nq.gz
    ├── 1c85c9c4d26f5d92d124f15670ff3870fd997f3e.nq.gz
    ├── 1cf99de46a2f570fc1421d75ce11bf2f69d74467.nq.gz
    ├── 1d5d21238ca25a2c4c42f7509c39b21617a3fdb3.nq.gz
    ├── 1d72318343f7255ed3d3170ef62077fe358a6a77.nq.gz
    ├── 1e47768048c3a92735c0bd736fc3ce5a439e1df4.nq.gz
    ├── 1ea70b6740cb9802e6be338a8e42a7c359afed0d.nq.gz
    ├── 1f61784fd08884a944ef7aa2985ab5c2b16de729.nq.gz
    ├── 1fa53b1f6dc547c127872539e6003db689f864be.nq.gz
    ├── 1fe1352a81f7d823789d9d34b090781759adfdbb.nq.gz
    ├── 2007c0d4e576725ba6392e874c3587c01b91fd78.nq.gz
    ├── 201e1ccd2264ff9aebe4ac9b9faa373b4d3f9ea3.nq.gz
    ├── 204b71ec7f9cb7dfb9c08f42ddc638f31e37d0db.nq.gz
    ├── 207e751ac2015255bee983005cecaf2363030730.nq.gz
    ├── 21e32c3eaf266a24e195edace4612a191a88807d.nq.gz
    ├── 225856a49941bc14c1e5be3d0cd0c35c10abed62.nq.gz
    ├── 22cdf182f877784f2af12761383e8a7fb61cc577.nq.gz
    ├── 234459113f9fba3ccf56f41c23bd0f5e9fc316f7.nq.gz
    ├── 244f265da6ec8f2b5f12e018c74c12c476ae0445.nq.gz
    ├── 24d39650f2285d732aeac07139f463c7c5c1ce22.nq.gz
    ├── 264749dfae798bdc2a72ebf65a220df6d9c8ebdd.nq.gz
    ├── 26475b6e4bc83fe463c5bcf77df9d23950684eeb.nq.gz
    ├── 26e1bee0a764a20b0874ee361e79d544514e62c9.nq.gz
    ├── 2831a57bc878300d10e2c35abd07424f6b9a2b05.nq.gz
    ├── 2931b2c4a1c4432e99481543b9408a95eab2dccd.nq.gz
    ├── 2980454dbd5a7f2b998e9daa21a7dd9e90b703cb.nq.gz
    ├── 2a56dae14697594bf0f130c26ad27ca27289f704.nq.gz
    ├── 2ac373a0625e50d40b521991c77593957212ea2a.nq.gz
    ├── 2bc82f53dcf6399514801a1444341a3061ec9300.nq.gz
    ├── 2bf75f899660afb883944a1c4a36115063f10304.nq.gz
    ├── 2c3769d802cd08244dc58b2e7f6e14fa56533978.nq.gz
    ├── 2cf7503f67f4285a21fb63b9d0884f269b43c846.nq.gz
    ├── 2d01ae0744371934db63de069af4d3ca05fe539d.nq.gz
    ├── 2d70cd699d36d44b642430dec61d64d7f90240ee.nq.gz
    ├── 2d9b3998af2f67eb924f41659345ff3322f88f94.nq.gz
    ├── 2dec4e1ed17b63ea2ac2822fa00d68145b71453e.nq.gz
    ├── 2eb4d98f3045bf2652accb80a3af4c7e613a9535.nq.gz
    ├── 2eeff146cc2879f55368e83eee85241524b56d19.nq.gz
    ├── 304625c4f8e8550ac987d45935b7743cdae0b90b.nq.gz
    ├── 308338d7e0028cf1082fff6be2fbcfd7376926f4.nq.gz
    ├── 30fd90df69368d332265edf5849cadf64e83bfe2.nq.gz
    ├── 312a91db7f524bca9eb00ad8bbce8791d50e1002.nq.gz
    ├── 31faf6adb93a44a14933b1f14f6c3b18e4c071df.nq.gz
    ├── 333de99e71e92db7a32e91f410850efa194382fe.nq.gz
    ├── 34afb8c438f084ab0b23e2648f76674f29061d19.nq.gz
    ├── 35cdf6547b380ae3517dff4a63f7630a05901525.nq.gz
    ├── 365fb5aa0514a68b27a0eb6540935be2b2948c9c.nq.gz
    ├── 371fd8886fb9e057c4ca984e354a6fa10303a9c0.nq.gz
    ├── 377975b9aa0f77cac698c8823e85b1ddd4b4d400.nq.gz
    ├── 37dce84fbb70d64f1afedae83435be3d638e1658.nq.gz
    ├── 38f7344a4b7ea6775d9938b242be1d4281934e00.nq.gz
    ├── 38fe549ff55dca79d0584a6f1eb9ebf1963e9c30.nq.gz
    ├── 3922ffc416a3accb0dd7c5f125b03272e83f3331.nq.gz
    ├── 396671ec7aed8017b45f86725a50dfc22a307cb7.nq.gz
    ├── 39bbc665e14b9682e2e7dc82264269329abcfcb3.nq.gz
    ├── 39bcb663fc193c9b4858c4fa7629d5662d79eb55.nq.gz
    ├── 3bf254c2cfd2401b25fd5d98693f94ac1c4fff83.nq.gz
    ├── 3c67ef1ca9f516f7e22e15a8cd5733d347c4d5b5.nq.gz
    ├── 3cd98c4669dec66993641201723180a6152d310b.nq.gz
    ├── 3defb7b4994f587632eaa955ed29e3258bae9128.nq.gz
    ├── 3e4fafd65ba1d105d63d71192c992ef3017684d7.nq.gz
    ├── 3e61988baf3c4f95e531a70d1ed4fff5d19de797.nq.gz
    ├── 3e96af5c7df698d1a2d6749f6edef9128fc574cb.nq.gz
    ├── 3eec2c74424b9852e9a0043e43f0437a78f4b008.nq.gz
    ├── 3f069a44971f5e97e8fac5721ef50c916d66850b.nq.gz
    ├── 3f5bb7dc4d92eed02c515c766e3784f65ca0a749.nq.gz
    ├── 409d2bf2d3c4d7da72e5a43fdae8ea1d2342340e.nq.gz
    ├── 40d9dad780a3cf9ca149202d090e48307cb339b7.nq.gz
    ├── 415a8d956132ba76d0e503722d1d9945a1eac836.nq.gz
    ├── 41e7b4704213627c62fb0c9eccf25fc7b627b78a.nq.gz
    ├── 421584be8521b68bf3d894d1df16bd47dfcca60d.nq.gz
    ├── 421aacf91f6d2562cfc0f8f14f8e9553048bbf7f.nq.gz
    ├── 42342cb5b20872d7c801c315aabfd812aba5961a.nq.gz
    ├── 42b08de67b092cd0c3d10b687808f6e76a35c84e.nq.gz
    ├── 431dea3af0464cb58b4aad7d8187ac979231779d.nq.gz
    ├── 44c324f1b181af083cb14489f77c8848fd8825fb.nq.gz
    ├── 455be0c379be18013b1c6d877ede3f75e33439ce.nq.gz
    ├── 4594d0bddbb9a3ee1429355aaa9830e498170c7c.nq.gz
    ├── 462f7475740cb5f3a8b74cd0ab0604e1addd4643.nq.gz
    ├── 4650836f6b4aebf86850109f64aac4a5eebaeb93.nq.gz
    ├── 473c031d309ca84fb2d48add1a65b08b8c82c24f.nq.gz
    ├── 47c2462fedb5c7bcff10692b53f142ba8b0f0f4e.nq.gz
    ├── 47eddc227670adce21f6dc3a7a3184c40fbbe463.nq.gz
    ├── 482fa60dcaab0bd17496b3914804c1d491dfce16.nq.gz
    ├── 48d6bc0952cfb14f1aecf026ff4c6e8ca3f3801d.nq.gz
    ├── 48fc64dbbe0f0363fd8f57b28d376a1413945cdd.nq.gz
    ├── 491bb353322a2dc7f5dd7f5f435203d4c505a454.nq.gz
    ├── 498518fd56968e0408b1bcbe353cf50db0cb038d.nq.gz
    ├── 4c20493c2b02006507774723659d741f963ed733.nq.gz
    ├── 4dd797397f2ad4f326ca8f4ebebf90295739e33a.nq.gz
    ├── 4dec2403dd8824d3019b79edb9a15298e5cc1ebc.nq.gz
    ├── 4e9d29cbd5b730e0e587101fb1b21ad75c15c473.nq.gz
    ├── 4ef9cc1b30faf56e25741437ab1569a6c63b3347.nq.gz
    ├── 4f1f2d34ca4f2a94fce9d36ad4788ad9859e3930.nq.gz
    ├── 4f2843e240fdfb42d31cbaa9dd4af9012ff0b583.nq.gz
    ├── 4ff1cd7eef6b6bd017d3111e3461e00008bfe152.nq.gz
    ├── 505426c139d836b8778ddd25abc22fa91a1094c6.nq.gz
    ├── 506d991fbf9cd092fcd60863a9f47a74ded268a6.nq.gz
    ├── 50d49d02c296eb819a2b1eb895cd51265227e009.nq.gz
    ├── 50edaad36d395194fb5c696db9c458f6cc22b77f.nq.gz
    ├── 5161946b7ab4ea2521770cbc5a57173c1d608c2a.nq.gz
    ├── 51802ffbe0b3b73ecdf33cba1a5c01a332426bf2.nq.gz
    ├── 519c1a5628b3b5a1eb2f85974464b530c49b385d.nq.gz
    ├── 51a4d93799037f0867400fd4ed90e09c34dc4614.nq.gz
    ├── 51de2f98769de56f7c808b53d26a76e5521f0d31.nq.gz
    ├── 51e286f0030a059d40b084c88752bc599178d139.nq.gz
    ├── 53b0ce6981b30b937eb5c1babc8107aa2b9ddec7.nq.gz
    ├── 53f5745324303565d0a1002f841db98df2c4395b.nq.gz
    ├── 5458aae6e8e74fcd50a965e0f72777012e18fb30.nq.gz
    ├── 5482d1976343be1b1faa685ff42a02084105fb6f.nq.gz
    ├── 54a6420e1a982b12119744e2e7c34dac448fb801.nq.gz
    ├── 55384313a236e6b7333712959f6f18d298e50ae8.nq.gz
    ├── 5668a1d57a4ee5961cc1a6ae6c75aa7ad2aebf33.nq.gz
    ├── 56bcecfc48619f77733111b963067ce84df35b80.nq.gz
    ├── 57896377d689b25d5d5a0ed2845642ff4d57b728.nq.gz
    ├── 5828fde9d45f66dcae3fa18c46c2ba6c66ec1241.nq.gz
    ├── 59041cb2be316e5ce78dff00a09ecc4efbb11b3a.nq.gz
    ├── 5934b13b0fb77e28fa774d5a4fcab56f0a43f28a.nq.gz
    ├── 597c4e8a3043ab8d830138b9db4fff2510f0ac26.nq.gz
    ├── 598525e307910ef4136582637e4402fba785e085.nq.gz
    ├── 59dcd38491c8e2f4b29327521ece53065d8c777d.nq.gz
    ├── 5a1f4c70f9b39cee03de4b17bdb7e803d5b97e8f.nq.gz
    ├── 5addb9ad5f563dd50b0e40d1b15678b3dd90ff2c.nq.gz
    ├── 5c87678ef955eda71a38a5b21b3b35c94dbd55f3.nq.gz
    ├── 5d05f6a0d28cc0d7c85ab8f00b059fcac72282fe.nq.gz
    ├── 5dd1df37518bdb2158a136d3872e05911cd784fa.nq.gz
    ├── 5ec5fe6fee31f737b84b469d77f0581e41ead8af.nq.gz
    ├── 5ed2c9e4553f23c3f1ddf7b9fd8d191520305979.nq.gz
    ├── 5f1fc3eb1b90decd7da74d01dc62ab117529f2d1.nq.gz
    ├── 5fa72e9f0c66d682c8f6e925f6ac473e60dafed8.nq.gz
    ├── 5fe06fa189eb595b48cfbd37559dd2774e31b312.nq.gz
    ├── 608cb5a3cd565039e308576794d5cf7b40674edc.nq.gz
    ├── 60b221f2e525ebe2cba20f1c07f231f8e41965b8.nq.gz
    ├── 616edc03760b5a08f65902fb162a5d47b3741e00.nq.gz
    ├── 63d3fe48408dc3e8c0f0d907598d80edae96dead.nq.gz
    ├── 64ca4f192ddd50aab492a8788d3d2d5dd66a1b78.nq.gz
    ├── 654f82e9935cc2f459e8643369c5dfb1af347335.nq.gz
    ├── 65508f5fa53e2e1dfe7d4b28a2b8c7fb7a66e9cd.nq.gz
    ├── 669b14c5822278820d132b6731c8ffb9c62ca4e6.nq.gz
    ├── 66bce50fa2aee774d323c1d447c6fa683d2bfa35.nq.gz
    ├── 66bf53248174c8dc9a78dfaa247d5e215f96bd7a.nq.gz
    ├── 67a158cd38daeee8ccd398ca705a7240bc9fa469.nq.gz
    ├── 67a3e4a89a8f0cdfdfe5a28f7396ede4634affda.nq.gz
    ├── 67a9a523cf7eefde4739558660e45be7c1b126df.nq.gz
    ├── 681753192232524c12025e38bff16e82b750ae08.nq.gz
    ├── 696f9b01bfa87f03fa9a4c691c1081dcc3a9b1d5.nq.gz
    ├── 6981a49a30004ee7961ef28f7ecfc6f32fbdcbf0.nq.gz
    ├── 6a061aa6786b3f2b633798254ceb10b9629ca66e.nq.gz
    ├── 6a65d0111f2482db9976ebaf5f5cba1a5065443d.nq.gz
    └── 6a75a99350087d7e112b662a3a3977d84e2b819a.nq.gz

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

[litestar-org/sqlspec](https://github.com/litestar-org/sqlspec)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
