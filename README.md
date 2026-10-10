# Repolex Knowledge Graph of sgl-project/SpecForge

RDF knowledge graph data for [sgl-project/SpecForge](https://github.com/sgl-project/SpecForge), parsed by [repolex](https://repolex.ai).

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
rlex download sgl-project/SpecForge
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fdcc2eddf1b56b5b24a5a15d3abcb366adfeb5aa
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fdcc2eddf1b56b5b24a5a15d3abcb366adfeb5aa
│           └── chunk-001.nq.gz
└── blob
    ├── 0022ddc0a01b61b3426104661ef8f6ed9417e44c.nq.gz
    ├── 0088b62ec20cd20ad941cf70ee3e0ebc0906cc86.nq.gz
    ├── 00e88bbe6df080543c50b50a938abf8b9d09431c.nq.gz
    ├── 016998598cd429153eca49ad0cf1e6e3274beb8f.nq.gz
    ├── 01f5f2a46c74bc269d45f1dbc1a12dcfb42475d7.nq.gz
    ├── 023d896ac3a85257c76f18c3653113347e3de9aa.nq.gz
    ├── 030a7293dcb6294d1ac26f262c761a9ac0a91052.nq.gz
    ├── 030e5388ff2d7ab2ada2302d7d7806b4f1e8ed22.nq.gz
    ├── 035f0977c53af7986d9a207ed3435e5218c33772.nq.gz
    ├── 0366bcf51ecb6dd8293274dcbe4744c47f634b7f.nq.gz
    ├── 03ea33914805461f6c11c45e37b7e7094d785f0f.nq.gz
    ├── 04524018f5fcc22027e03b7b71f004ccb1b3b302.nq.gz
    ├── 0468e115aa7faa16586b382e1c4e6fa0c1557d9d.nq.gz
    ├── 04a8640e05921d984326a3d41b205395ee3e3c90.nq.gz
    ├── 04e894dc3fbc3819b357b11882d67d4e95892373.nq.gz
    ├── 05456a0d239653cdc898413860c6822d8a7cdec5.nq.gz
    ├── 05c9301118b4ab3c963c182cdc323d201aa683d2.nq.gz
    ├── 068f413e308907a4e5adb548acb4be217fb5a8f1.nq.gz
    ├── 07e63405cd17c24f8b3bdf06ba73ec0afc6abb1b.nq.gz
    ├── 07f05b6874fd4d8669aa65f7de2c8582b4a0a2c1.nq.gz
    ├── 090398f2cb01cf8c317bdacc7b2f2d4400ac5d71.nq.gz
    ├── 090aacf94d403ab4046fc085f60fa050d3b4f192.nq.gz
    ├── 09848f929b7a16a83fef40e03e1b92975c7bc26b.nq.gz
    ├── 098a5550c673f678c9a8a1a96bb1dd2dd9e471ed.nq.gz
    ├── 09e37fe066eee0a44e6bc74199bd6a64798d8f15.nq.gz
    ├── 0a9bea37c06ae29010eade7cd4b70cdf4e9e0316.nq.gz
    ├── 0ea3a944b399d25f7e1b8fe684d754eb8da9fe7f.nq.gz
    ├── 0eb271c1708ab77d05b6804ad8fecd66ac9178a4.nq.gz
    ├── 1039fda04242845610a4d1ebd05f521ae873ac89.nq.gz
    ├── 10f8dbae82381cb1cc1a9e7ade454ea58a9da6c7.nq.gz
    ├── 113ecf1697dadd3737a2ca4afd1bb6f1a4fdbd4a.nq.gz
    ├── 1189ed6cf2790ca1df96aa0da0802a32fba4d132.nq.gz
    ├── 11b156d27a60a12bf8f3efb2e843738579c85dc3.nq.gz
    ├── 13257f77a9d2e8109bd9537c9f59c889a2534df6.nq.gz
    ├── 13f02b4f7e6ca1344c98dfdb7c607f80b60e989b.nq.gz
    ├── 147a5fdcd32c7ccd83248eec16dc709ed34e8bce.nq.gz
    ├── 14d6a7817dc9358d64e4b93465e1b1f33d870923.nq.gz
    ├── 1558f211246a3d979ff48c29783eb5491814699e.nq.gz
    ├── 160d7f2cb74a11b0ababc5aad8b0192b17126f07.nq.gz
    ├── 16a2274d3f00bb83a00066e41254dc222e65de1b.nq.gz
    ├── 16dfcca1b300d0f58fc7e35dba889ee965ec33f2.nq.gz
    ├── 17a28c9e3700460c38c305d51c5a6648c4d8619a.nq.gz
    ├── 18de973548f23a6833b2945140e7fd0666946b08.nq.gz
    ├── 1a37de6e8fd4234079e9fa4dacfc11b2a91a8fb4.nq.gz
    ├── 1a8f1ac9671e7bd917c826ddaae036ae89e0b31f.nq.gz
    ├── 1acd248fe8481400533994b7f45c21b03c629bc5.nq.gz
    ├── 1ae776d66cb6ccbc2f6b4f3245a40c2c3b3c4b75.nq.gz
    ├── 1baa4af9c04e1a38a191a633f8105811759b3d67.nq.gz
    ├── 1be6e71cec8977e16c88369b390533ff227efd68.nq.gz
    ├── 1cd87b334b4c236e4adb18443203f9fc21619f58.nq.gz
    ├── 1d000a9c901c4e41550064029a53283d393e5c6a.nq.gz
    ├── 1d2b289dcab20441e0d2e76e860af2d4d9179be0.nq.gz
    ├── 1d4f474fcd15bd9a891b8f8977465aaa233c9fd1.nq.gz
    ├── 1d759a83637eba8dab677fbe4773ed2277519076.nq.gz
    ├── 1d967a1a0ba191dfa41d5ce1dac5be990ab4d6ba.nq.gz
    ├── 1e809f5912477d06931947b4ff45615c6bd0d34b.nq.gz
    ├── 1eee6f24d989cf24fd7e0f70fff8e165a7f40057.nq.gz
    ├── 2025346b774edbbd1d7577ea1cfe0ca3116b4d25.nq.gz
    ├── 20d04f4d0dc09fe2894a7a35673b3a8afdaa8e32.nq.gz
    ├── 21566a0c623aaf0f0f95baf8f8b5b82f041f7b0f.nq.gz
    ├── 216beeb93ee71e9dc1016ead0db9375d110d9ba1.nq.gz
    ├── 217fb8d08113566a7ab90a77ef9954ea888f283d.nq.gz
    ├── 21ee0ed263be5ba3bae7b3ef5923f50ffcfe70f2.nq.gz
    ├── 2323b65252712ca4e4e9684162c4eb9abe2d4867.nq.gz
    ├── 23665bcdb99ad1efaf298192971d6fc2e962652e.nq.gz
    ├── 247ff044073740496a8654a69d5653526edf7198.nq.gz
    ├── 2593fcb025d912d6719cf0da5c561f52117b2fdb.nq.gz
    ├── 25a3d238a9725a3fa9f4f5dc6f05ec496cf84aa6.nq.gz
    ├── 263cebb26fed05e1b6326bde74dedc8cd00b004a.nq.gz
    ├── 2658fda9e5a29aead1e931f83423191f9e92dd3b.nq.gz
    ├── 26e17d848ee2bad889b5026942eee653997e0642.nq.gz
    ├── 2777f4e677fde24344d96d9791d6f4dc3bcb6c38.nq.gz
    ├── 27a68f8c66c47fd95d867993aa49a30707be9937.nq.gz
    ├── 283ba36516c6e3649866ef72cadec356b983c6a3.nq.gz
    ├── 28d59cb7c17d8d43f075828a4451cafa8476dbe5.nq.gz
    ├── 2960c86673f9faaa90cf9bd547876bb1f8082829.nq.gz
    ├── 29a3858db3e919af882c6bdfcb82a944a44c127a.nq.gz
    ├── 2a70036449fc2c52a08cae058a8a11d5ce008852.nq.gz
    ├── 2aa4d332265822eeb3e4470fb7e269e0f0bca764.nq.gz
    ├── 2b409daf005175d34ee1320bc5b8af3f50d3ed8f.nq.gz
    ├── 2bf86885370695dacce7fd853a61f56a45906a8b.nq.gz
    ├── 2cafc0c1497be3dbd22fb20096004053b5d10f55.nq.gz
    ├── 2d1b7c536a8819bbbf2bef104b9ba96d6caed7b1.nq.gz
    ├── 2d5bd4fe81293352395447d0b5f72a2b04e53826.nq.gz
    ├── 2f27c80cc017e811f8846f2161a977725e669086.nq.gz
    ├── 2fe9bfbc53e1b4cb774a1ce7635e61b0216316c3.nq.gz
    ├── 2ffb1b1f3b9451ee278f363ed033c66ae1c091e3.nq.gz
    ├── 30135a8d50d7a4fea1397867aa58a50c2e802b23.nq.gz
    ├── 30dec273ca3ff490db62dafcadca07bd137aa5f8.nq.gz
    ├── 31eb92e362efc50ac504dbf36af3caa710068c2a.nq.gz
    ├── 32d0e7f04d13273a9f3e654b88998fb0060f1143.nq.gz
    ├── 32eed42cfd0a7482bfd2d8beb587c8cf8ef934f8.nq.gz
    ├── 336d5776c5d1585a0a8ec0f3a24d2458d77703aa.nq.gz
    ├── 339320edab6cf7d7e0a72ef32b7ec9845fb68142.nq.gz
    ├── 35a866b5a24b30c02fe0d5dec3fe4a1a6e9eceeb.nq.gz
    ├── 371121e3296bb97a1e84e4279944fed22cd40f4d.nq.gz
    ├── 3985f45e36a0c913eaaadaed42be1d57f95de94c.nq.gz
    ├── 398b17b0ebaf501ecb9fbc41bf0724958ccfe0bf.nq.gz
    ├── 3aadda5a94d02c25626d394173a7d587400c57b7.nq.gz
    ├── 3b008ccae44dba97cbed63c20e3eeb1e88ee5eff.nq.gz
    ├── 3b21cb0c49e251a1809feb8d0fe21aca61e6f0fb.nq.gz
    ├── 3c431c21d70c8430694d4f6f8ef83ddd7670ec0d.nq.gz
    ├── 3c89b7e4a33431b83d4abe7bb64fd7b52a396523.nq.gz
    ├── 3cf35a6be5986ecd8e9f90cef12a75438e8401d6.nq.gz
    ├── 3d1b2c1aeccb0e55f419de3af2b02754b830dbe9.nq.gz
    ├── 3d282915b6c9648d5f8b4ac4587883622c287846.nq.gz
    ├── 3d40f9b2cdc5cd7d9bbd7297953c44aa71422fbf.nq.gz
    ├── 3d578a404d27bc114412841af0728d8912e46aff.nq.gz
    ├── 3e154e9486d817890cc683309e460100606902a7.nq.gz
    ├── 3e1ebc5ee3293ca1094c26bd620b741cb0849db3.nq.gz
    ├── 3eb3d7db061a673cb0f927496a870be59c88535d.nq.gz
    ├── 3ee600b3c1fc978e3f1d1078804000fc3d9e7204.nq.gz
    ├── 3f117fc8ef7e4de93598ed3bc2800a99f9b89a3c.nq.gz
    ├── 3f91e504ab071a78d146fcb17d95b27583d516f2.nq.gz
    ├── 407339a82e2f1d86d8829a33ededb2201f3b2ee2.nq.gz
    ├── 4158aa78f37ba458152106b43c1cf52ffa11dbfc.nq.gz
    ├── 41ae128fdcd532f1e31c6251819d29aedfa9d3e6.nq.gz
    ├── 41b631448078e57addac09d3e1d3f704e6cea83d.nq.gz
    ├── 41dbb899e2746837d42bff3586034206b4d384c1.nq.gz
    ├── 41fa058c4aff03bdeb9e04b06e5d2129fd2e57f1.nq.gz
    ├── 43656c2b1d76011b7a0c1db85b77e35d6e9546bb.nq.gz
    ├── 44acb80f6190cf55e918e4aa5376fd7fcf2857ae.nq.gz
    ├── 44c1b9eb000276369955a9f68b81428654328741.nq.gz
    ├── 44f506225d34cbd416c23fae7d7791afddcd984d.nq.gz
    ├── 45d084d14aa59afc2758564c75f08deec30eedb4.nq.gz
    ├── 46f2d1d611c8065219d65b221c1c15ae9409e21f.nq.gz
    ├── 476a8ecb98e9ec2e5a2d44a584cfb8a2802cdff9.nq.gz
    ├── 48715ba55e6ae5ec14e3fbfc9b30fec66b6cd07d.nq.gz
    ├── 48738156edafc31baafa387a0f14ed0ed74d9980.nq.gz
    ├── 4909e06efb479a01e44e67265074c726796f4959.nq.gz
    ├── 490ba2b20349ecd68a3edc468d38ef377c6e8d05.nq.gz
    ├── 497209d12d69997d089edd38ffc24ef683867842.nq.gz
    ├── 49a665066bb7171db94e12114830d8d59fb578a1.nq.gz
    ├── 4a41b9433313d8b25fea6bc85c063936b437f925.nq.gz
    ├── 4cb2fe82353f8cd591dfb04d03a3ede89e06f171.nq.gz
    ├── 4d1c39d31ccb514412e99929be01b7c147fedcea.nq.gz
    ├── 4d323a128806eb0ce25ce3cb8faa8d6103c90cdc.nq.gz
    ├── 4e23a14233c22ceebda83afe1778427a6d4c4dd7.nq.gz
    ├── 4f2e406a09f65ac030f3059d49dbea200075c855.nq.gz
    ├── 4f6a7a2ba6fda959fe8dacd39b49c157e817103a.nq.gz
    ├── 4fce78ead5424da1be94d810495824649a847ca3.nq.gz
    ├── 506c54208c9a742ff439a1c2fe848bffa4e328c3.nq.gz
    ├── 50a2979eef0c27840de26d2210708dc49f961f99.nq.gz
    ├── 50ca5f54dc658106c22d7a8a95553bf346b33525.nq.gz
    ├── 50da59284c4fed41a750e67d2fab9b65924b76d4.nq.gz
    ├── 50de1e3ca8705be46cf291f3283d68d8512e1e4f.nq.gz
    ├── 518860725a65bae6674c0af60643394ef174f2d9.nq.gz
    ├── 51e3e9a646bf66ba2dddfaf2f57eac9061f64026.nq.gz
    ├── 5301aaf9bd147b63f00b76148ac0009865f7f916.nq.gz
    ├── 53a577f50c8b412b1b11f3131dd45f1b0d9c55d2.nq.gz
    ├── 549522f67ca033f890ebbbbd3ed03fddc7ccd210.nq.gz
    ├── 558cb18043a5bd182497536203de90a4a7672f35.nq.gz
    ├── 55b7ee280f3a4f9573d15670934a37b87a2d9601.nq.gz
    ├── 55c883067256de3d4c4aa68d158a859507f6e06f.nq.gz
    ├── 5688218f5ac82961ede231262ab642f30ceaf5a5.nq.gz
    ├── 56ce6887922ff622d71677d23632c5252291615b.nq.gz
    ├── 56d9ea74088438a646da72f939190dbc343781e7.nq.gz
    ├── 5702f0ffb9f42b6d01efe8a08d5f8a6c0fd248ca.nq.gz
    ├── 57492af0bfcd9e7600e13a54d40e6c5bf8f208d6.nq.gz
    ├── 579289d2c31005e3bd595f4286007ac7fac746d5.nq.gz
    ├── 581a1e0f30a076972bbd8515020fb99ca41914cc.nq.gz
    ├── 58d35385ac0dc4d6cfa4655acaddae0cf9fd0de8.nq.gz
    ├── 59789e055e116e144cd56395675c358e2dee18ba.nq.gz
    ├── 5acdce322add173ea7b0682142f73d7e5809f3c5.nq.gz
    ├── 5b8d23612f11149f6ed8d253b3ce8d30ff654911.nq.gz
    ├── 5bb22bc0069c73ed39c3489f2acc8f48c27c12c2.nq.gz
    ├── 5c031bf73959f4a7024ae754c9f9f9041056ecb6.nq.gz
    ├── 5c19134ab78b703dc63f4abf84e7797413d14bbc.nq.gz
    ├── 5d625e7a135db20a2d7d6b2327e9ac3651010192.nq.gz
    ├── 5d6de19d0682e8a5bf62c496d210d02b597dc45f.nq.gz
    ├── 5dc653afe02c6cafa926097738043bae1541812d.nq.gz
    ├── 5f4c0ce66258472f58ee272cc4b33866f7f12384.nq.gz
    ├── 5facab00d719d6d235a8cb50d161679ebe28f6a0.nq.gz
    ├── 6048ad87db22b43bc29c659b06a228f7fe34410c.nq.gz
    ├── 61885ced3006f2cdc6334656511caf373361bb0a.nq.gz
    ├── 61dd1717cd067a20b7fd395ba25c98f8099dc1f1.nq.gz
    ├── 62997b5730909e211693733619498605e36c5729.nq.gz
    ├── 62e941c05b66b61548d39c1f7c1b8b6aadb8cfe9.nq.gz
    ├── 63dac6063065f916ba749cebf7875176bc5f47fb.nq.gz
    ├── 6446cccc0ccf2bef7c0b20d08beb130e311fb0c1.nq.gz
    ├── 64a5f104828ad62b9eac76b8eb96031a1601e563.nq.gz
    ├── 6595e86023d109099b698c55c63dadf915893fa5.nq.gz
    ├── 6617a8da7182321e18555edf97b2c7b794269628.nq.gz
    ├── 672193e3b1284badcb747356f1cbfcd402e19ccf.nq.gz
    ├── 67276ec5c1bb00558191215e66dbc6689c81625f.nq.gz
    ├── 678ce7a257b8bddb2a44373a4eba1ff77595813a.nq.gz
    ├── 67d456f738b1819c65a7f2814d8f550f52383221.nq.gz
    ├── 687615d1c654bb76253e658f0b100a43d5717874.nq.gz
    ├── 69d457dc11d974ff793668d595f2a9efc105eac2.nq.gz
    ├── 6badddbe0823986733fbc41bbcdabcab7fb11b2a.nq.gz
    ├── 6c9cb0f4a4f7df9ee003f6988ea212d930cecc79.nq.gz
    ├── 6d170fd0b573462d0a51eae6ae0b1e67da03b062.nq.gz
    ├── 6d30421ebd6d5a3d33b5b86b2456af2caaeb0ca7.nq.gz
    ├── 6d9d0387415c80a6cec024db860ddd1b532dc0f9.nq.gz
    ├── 6daef86dc5e5f71b06646cbe949d75aadea25863.nq.gz
    ├── 6e7788177a821ea886d97ad7fefc03cab3cbdd40.nq.gz
    ├── 6fb1e8763b5712bfb8f38d2b471974cd6bf06d9d.nq.gz
    └── 6fb5d0704d3e507aced7c38b8806f6eff0ff21e1.nq.gz

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

[sgl-project/SpecForge](https://github.com/sgl-project/SpecForge)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
