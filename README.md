# Repolex Knowledge Graph of UKPLab/emnlp2026-agentcibench

RDF knowledge graph data for [UKPLab/emnlp2026-agentcibench](https://github.com/UKPLab/emnlp2026-agentcibench), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/emnlp2026-agentcibench
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7b3fad424d0c5a450ac3bc3dc4050c38094c6dc6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7b3fad424d0c5a450ac3bc3dc4050c38094c6dc6
│           └── chunk-001.nq.gz
└── blob
    ├── 00038e28dfba722e88437055e19f7096ed464283.nq.gz
    ├── 00296e9598fadee8e22cfd89826d3d10f2c0ba26.nq.gz
    ├── 02200886e5fc83acb5f8e41285adb21b8e0c26f3.nq.gz
    ├── 03af9fe9c487cb39a62607c4c3dfbcf18b3186d9.nq.gz
    ├── 048f0d66b508fac1a8cf6d36826c2fe47dd1f89a.nq.gz
    ├── 04dc8c836cb7c3bbe0ba414192fa094e5287abce.nq.gz
    ├── 05d17df73809599182a4b6f3aff84a99ecec83d2.nq.gz
    ├── 05ebb9fbae8f86cb1c545220e6d1cf3b8a38533b.nq.gz
    ├── 0679e9abc2a2033c8303931c97e856af47a91859.nq.gz
    ├── 06b2c85ce1e2eae6f26bb472d8090f077289002c.nq.gz
    ├── 073e358fe12f398387bf15abc44b64f66ee3c335.nq.gz
    ├── 086e0f278033d718d841c0057e0c43238b697e67.nq.gz
    ├── 09503b65173124d08f4a3b0ba04122fbf272b82b.nq.gz
    ├── 0a217b841677ce10f2f569e75fd9e46cac86fd38.nq.gz
    ├── 0a4361221287e9d5d0e6e484544160e585ee607c.nq.gz
    ├── 0b31781431f3f4ad84a4ad01a68f9052e4a1b30f.nq.gz
    ├── 0b9fe1dc59e390193943bea62651adc37119dd19.nq.gz
    ├── 0e6e23fc725a079f45168a40f05cbfdede75aae7.nq.gz
    ├── 10f2e21a6950fecc0d42f09886c3bce249fc2bd3.nq.gz
    ├── 11221e45b591820ed9485697f2aa1c1452f1444c.nq.gz
    ├── 15c74ede0af01fd1d7d8d3137c804802e3491bf5.nq.gz
    ├── 169a7d8236e390b1615f9af1452b8dd303376229.nq.gz
    ├── 1934b914a0faa086227327b1016ab13afd4c249f.nq.gz
    ├── 1969d4733caa150c5a588351a2bce6e0dd11a217.nq.gz
    ├── 1b58f2b004cb40bff31ca1a16ec2e8eb1f016e00.nq.gz
    ├── 1e28b10681d6c456776a78666658e5bf55a1e339.nq.gz
    ├── 1f0d23072979e4446b80ad0a976d262414808e26.nq.gz
    ├── 1f1d4416e3a258aab2d429a63fef596814564e2f.nq.gz
    ├── 1fcea5e40b2c07fdefb68c08ec37dc9e4bd267ce.nq.gz
    ├── 22153e13130c1789a2262f37e36eccd909210b97.nq.gz
    ├── 2217164f0c05a385d7d0d83e030fdbae01e99304.nq.gz
    ├── 23ee663443a7c6d2393dbcb713b07c566f40c925.nq.gz
    ├── 23fc68e151e53b435aad1ccf13a5fb0f2981b864.nq.gz
    ├── 25abf389e22db851b03dd14d87ca10acb8b6b44b.nq.gz
    ├── 26fa5fff71694d9bde4028a8b637265ba220f1a4.nq.gz
    ├── 27f7f1cfd72e9e1dec507e427a6ca6e1dfab8752.nq.gz
    ├── 2995433d85ed555db9958e2611e76c11268019c1.nq.gz
    ├── 2a5e4e67e92b689d219b2b81fe079bfd8a2729ae.nq.gz
    ├── 2c51cd7c699ae2c3d2638848047f581b9768a9ea.nq.gz
    ├── 2deaf3dffa8b788b58309c7140af43b382da1aa1.nq.gz
    ├── 2e3db0e95f003199955bd51e4ccdda8e3f1f3efd.nq.gz
    ├── 30e79e43648b33f9b7c34ebb61da55fc41552d0a.nq.gz
    ├── 3223f0b361c57ee5ac1c2dfcd8cf2e297bbc3247.nq.gz
    ├── 32910d19733c72cb34ecc3f63f63bca6f3c51937.nq.gz
    ├── 32d71b194aebff93b8ffc07535aca860dbf2c2c5.nq.gz
    ├── 332cfc448968fa93c43020c0350ee771bede1d63.nq.gz
    ├── 336c73a5e0c23f731d44ccc59edf9000cc9bdf12.nq.gz
    ├── 3375bef0911555af28fea3c02c3e7671c50a5e7b.nq.gz
    ├── 35b3273bed8341f97558d3752e350e06a35e545b.nq.gz
    ├── 369b7661eae350bd34a46d6c6c5b47d5b1f0c030.nq.gz
    ├── 378f69e0fea1c2386a3859c1af22173901d0e9c5.nq.gz
    ├── 38aa7f6792f2e9620ffac28e380ed4a1e818dcb2.nq.gz
    ├── 3ae4d0740e18ad817c8d151a33ad64c7cb6f6675.nq.gz
    ├── 3d2556acdbf3ffdc9a4b21e3eb39b919d84381f3.nq.gz
    ├── 3d838462ee8c7e4b3134700108a04528a1d7f1e3.nq.gz
    ├── 3e7f30bef1c94b61f1d09ced821c9eb2673b74d8.nq.gz
    ├── 3f26b8de2fb276dd97f1b0cb09a8f9596a742f69.nq.gz
    ├── 3f76b71253b7ad31a59be3ad343148a1ce231af3.nq.gz
    ├── 3f7fc0e25488f2d86c08324aac6a442ecf516c01.nq.gz
    ├── 3fb9c98a85077cedffdfc19a874853cf38ddd3f5.nq.gz
    ├── 402f81c0bc082532fca61319959cb4b8e597de9d.nq.gz
    ├── 420ab11fd7fd8fd589cad868d1f62cc8cb220899.nq.gz
    ├── 4257c983aad889b606921887b8c9c8b9fafec460.nq.gz
    ├── 436f343f83636d27b90d05a49f2a37a23a88fb5f.nq.gz
    ├── 43d03ebe418fa112b016eceb88829b83c0c93505.nq.gz
    ├── 44ed71fdc52d5e5aa1e3a7f8ec14eaa32a875df9.nq.gz
    ├── 44f2bef3a991436583729ada9e9b25bacd8e0b22.nq.gz
    ├── 4551a88f2d89e36d7d88a7986b04570a81aeee8a.nq.gz
    ├── 45c83a029ee9ff414b5bce886b4da6651a283e7d.nq.gz
    ├── 461aef06a9702fdcdbfe004a0a6a90bd8a990ed1.nq.gz
    ├── 463af27c02dd3cf5f729e35f23050d4567855824.nq.gz
    ├── 47a187af79186e194cb8354dcfa61abebca8abc2.nq.gz
    ├── 48015ae5610160946ee8d4b235ab9721f40cdde5.nq.gz
    ├── 49224e899233afea4e18624919a01e2a8c61e5cc.nq.gz
    ├── 4d21b3297d87939e2fe802b4b0ce44e362f28b9c.nq.gz
    ├── 4eacfac8486923021ae40a9873fcd6940fd65934.nq.gz
    ├── 4f1248d3efbe791c42ee51d6b762de9ff02722c5.nq.gz
    ├── 5026a0d81ef48605f88455c30dbd2456cf3d1402.nq.gz
    ├── 50c8d919fe8018f9f7d3d6f20c34c305d72e6971.nq.gz
    ├── 51539d3312ee8e64eb657b3bd28ffb4ec896161a.nq.gz
    ├── 53003cdb2e520873313a2de3e72ef7427e38cfb7.nq.gz
    ├── 5608bd7efd24da9a35ce2a8f4e6c18080f9b2d7d.nq.gz
    ├── 56323ab61941a3530e6b990063660eadceb98a2e.nq.gz
    ├── 56328948b3b1bacb23a13af9d727fd75c0343448.nq.gz
    ├── 56f14ae682b0a77a04c34528c5caf0c697244c6e.nq.gz
    ├── 573d05907e85ff7447ea11cf052bfeb35867b1c4.nq.gz
    ├── 574ec96ccac1f6021d61a948c7b63e486b339433.nq.gz
    ├── 57be5d1e83fe5ddab3787bd0901b4570d6bbdee1.nq.gz
    ├── 58c07ebbbfc5ebd67ab635834962519399522629.nq.gz
    ├── 597319b5ea4f852fff101c02b432d493a1398e72.nq.gz
    ├── 5a163d4d0085267cbb0146769c420797b3d85f0e.nq.gz
    ├── 5a224bd24ce5b94c3ddab4dd72f7706a30885523.nq.gz
    ├── 5aee96980c764895be65af069745841b3236618e.nq.gz
    ├── 5b91c8baec66d9f08609a27337cd14afd3132a11.nq.gz
    ├── 5c939cb9c945683e4755829363c1e7a4b7539d43.nq.gz
    ├── 5eb268ff5e8ca8b4f5195ca574de06e10e084087.nq.gz
    ├── 5ef4d5e47bcddb57b525a30d3c8f0fbbf75da959.nq.gz
    ├── 5f53569cdecb249cd72cf4777f3ec7154d8aa12a.nq.gz
    ├── 602bf6d3ac97f53fcfb9f53a0ecb16541350a850.nq.gz
    ├── 6278956f6e2939c9fc7eec2a6d5f0f9e97480704.nq.gz
    ├── 639de7eee8b3054878a400f14915aac6806f8e25.nq.gz
    ├── 63a2849a2d150772d2f1a16d4bc851727750e512.nq.gz
    ├── 642828702fae1d3d2780e161b3a4c65438ecf2aa.nq.gz
    ├── 6445b6649aab8039c57e64179030e4a6341fff1e.nq.gz
    ├── 648937ae387540cfdb36396268a0f1c1c870861d.nq.gz
    ├── 6570576a07b048ac4fd47efd2d7daeda92928476.nq.gz
    ├── 662c5c6177103d574c261f9cd900960e46847169.nq.gz
    ├── 66b9c934272d0f2308ac43d9f6b28a5e860096cd.nq.gz
    ├── 689f9fc9f7d9a3da700dc8d47d2f1cfed6571f4f.nq.gz
    ├── 68d0458824766e6f0362a13ab18e1a6cdfdc2809.nq.gz
    ├── 6ab973a839548db7d34f9bfa9cb618dd5b208478.nq.gz
    ├── 6cb4e2b07960f879ef9f8265633f875f85a1ab03.nq.gz
    ├── 6d185c809b4baa711bd8b7fb9e04090383d05163.nq.gz
    ├── 6f1021bf0f87ff00300c8b93b90f81b70a3d8bb6.nq.gz
    ├── 6f65c145ed1afc200fe16f43656b2c6e6ebcb183.nq.gz
    ├── 6f71101b5c3df09b804cc0962764ece61c7bd177.nq.gz
    ├── 70e0104ed2aa3732756254fe3fe322694d2ef6a2.nq.gz
    ├── 7157aafbacdb095b479ae52f59e28e19ce61d79a.nq.gz
    ├── 7172553bda8dbdeb831bfd4466732fc6185c4e3b.nq.gz
    ├── 71db0aafd62c35b20d8181ca31e246973a653aed.nq.gz
    ├── 72d9c8f0d21c514875dc9edba64f8de5e5385384.nq.gz
    ├── 747b0fab0033818507d89c792b00d86faf202769.nq.gz
    ├── 74c690fd4325227fdac62bdd6bae34a495b6f841.nq.gz
    ├── 74ef94952a1ed798e63279b53da26a6183d8d6de.nq.gz
    ├── 74f9d5fd8f9a751f26c347e85dfd26119a7a0d8e.nq.gz
    ├── 74faf65904fbe32c7942edf805589fdda026a3d7.nq.gz
    ├── 74fcd0cc488f9ba939ff4aa820a0ddebf3e31d1d.nq.gz
    ├── 7dcdb45a8c9304ad6524de57541ef9561afeb5e1.nq.gz
    ├── 7e093442309714c0dcd08d6ce020fe01f56cddcc.nq.gz
    ├── 7ec2c8e50faf82422e65ada822772337c957e180.nq.gz
    ├── 7f3f26a8e39a4434683f04007e0cebaada82282a.nq.gz
    ├── 7f53af2cc4fc0f1aed1dd1421c1e42b06727525d.nq.gz
    ├── 8036e3369ea6c350a7f3802e51c878155880b6de.nq.gz
    ├── 810193f5fb87d7c0d1045c40467a64a46ee97b5f.nq.gz
    ├── 819ff60a95210d38e8e1c22cf30db1e65757e178.nq.gz
    ├── 8227766a327a82b095fc1d9d44b8581bd1331cd2.nq.gz
    ├── 8425bcd8546b30430cda7a724aa34cc94ab634ec.nq.gz
    ├── 84557c9aec8f7e0317834d2b1cffc07fbf62a065.nq.gz
    ├── 84dac173d13231054d39a8c2d6ec16055f168d9f.nq.gz
    ├── 85f14357a7afabfe1af11c7720a573985423090e.nq.gz
    ├── 864234754ec5b6f1d85363f6e60d9514a9dcb8fa.nq.gz
    ├── 877a55e837072757d19c66ce6b45608f9af44ea1.nq.gz
    ├── 8934c9fd01d0584cd53f90e69404a458ccfb07e7.nq.gz
    ├── 8a698ee50630d01555bf211141200ef5af93df74.nq.gz
    ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
    ├── 8d74c105092f5c2840a8374c4344913c3eda75a0.nq.gz
    ├── 8d75deddae520da95d3cf111f4ccbf3361074292.nq.gz
    ├── 8dc5f51fa063760b0ea1ac7608be332e6163ba8c.nq.gz
    ├── 93934efb95caba427ef07bcd0b3053a413480877.nq.gz
    ├── 944afbfa7a9741ecb8dc6dcef5b9a14fc4028087.nq.gz
    ├── 950668c0392e9dc71bdf6aa0ef331d5eee374b32.nq.gz
    ├── 96909a88a368ef4bdbbab99a4246b070889fca6f.nq.gz
    ├── 986dc1830879c5711a963d446a732c0e00edfa7a.nq.gz
    ├── 987304e79314439f5cc91547cfcb21ed132d06e9.nq.gz
    ├── 98fa7febd1c1f7d44eb01c8d994471c5670d8cce.nq.gz
    ├── 993ec1175d38881ba57a19ae9dbc0413006690ca.nq.gz
    ├── 9a2c026c52289849ac787eb13e67a0da288a2b61.nq.gz
    ├── 9af7bee55efd9104eb21403924a67c85f46c53c0.nq.gz
    ├── 9c6fb86dc35a9fc838d0fc20776e0693d3f97dd5.nq.gz
    ├── 9cb895f280f5da4c086527cdcaa11a36126cdde0.nq.gz
    ├── 9d51816b8b72b8883f1e4d5880ada1e3e838d6c2.nq.gz
    ├── 9e851798a7d30ebec216aa1f1da744fc4a02cf01.nq.gz
    ├── 9ee29af0fa834bdb75d29f0bf2a8e6b03821c2ed.nq.gz
    ├── a0510caafcb5fdaa7cede290b067cee42b1118c6.nq.gz
    ├── a0abc8b3106bb15cf8d5f834f41b49123078bbb4.nq.gz
    ├── a4e598936b3eb6ceb0080dccccdcd49bfe95ca98.nq.gz
    ├── a5cfe4991c99c9133f71d8f86a8d76d1c58316fa.nq.gz
    ├── a688da8787431167b8becf4d879c54cb7af3f6c4.nq.gz
    ├── a76f92533c9231ff01f734952ed576316d02eb23.nq.gz
    ├── a9329b78404605afe48af397354a76ac0c9a26b8.nq.gz
    ├── a9b9e87be27714c8a24e933ceff08586b8858923.nq.gz
    ├── aa0456a855a33b9096c439ecdd70ccc4a84ca35d.nq.gz
    ├── aa8dae8bfc8369f6f7c0e9ce2b223294db5c05c3.nq.gz
    ├── aaad217e4dda75d978cfe38ca3f997e7e21febb7.nq.gz
    ├── aac4307feb241f42208067de5215e62ee245231f.nq.gz
    ├── ad077c6bec782b7c15bfa4ec96ee5900faaa3ccb.nq.gz
    ├── ad7171e149314165657c716bfc5452fe45ebaee4.nq.gz
    ├── ae5df077329a9256d3db0dde8a9d1847bf67380f.nq.gz
    ├── aed41916b4a3ed2b8a23dd774d20aa44e70fc870.nq.gz
    ├── b07c8f2adbd7dc30ec2592ce3a3e4f1931eb4b88.nq.gz
    ├── b0919518f91dad0770c314a76096a919fac4b7e9.nq.gz
    ├── b12ecea094b39494123a5c941c678542c573e70d.nq.gz
    ├── b20996a5d52b364e044817d5e64b3b830fb288f2.nq.gz
    ├── b609316c8111f48bde3c4ba6500b99562a3770af.nq.gz
    ├── b6c9930ac8b4699bb9f64d6f910608b3d0126db0.nq.gz
    ├── b6f31da1f38a0104bd6a6be3f130229ced18c082.nq.gz
    ├── b7c34574d2d06f4949fa8c445eeb7760308f0e28.nq.gz
    ├── b815be7eb976d56f3b6eb89e1d56d5cac1737a8b.nq.gz
    ├── b9055b1646fcf046c6476d897f47bc24bc27e1ef.nq.gz
    ├── b9733702392b1658031e339c7b7631ce4e6a9e0f.nq.gz
    ├── b9881a43b7313e5a033582e4bf0bcb26bf11730c.nq.gz
    ├── bbf1e3678b83860e9f99249d9a0601cb442f0ec3.nq.gz
    ├── bc0cdeb1902957bc41046ab359d1a7cd7e89460e.nq.gz
    ├── bc883a4ef12bb4e00fd6be1bb9fd4ccdf3b2e901.nq.gz
    ├── bdb8e9f0b26baa090d77bab66d759d75413a4f01.nq.gz
    ├── be0dff65ee55694eebfe6fc1ebec32ee66a3f4d4.nq.gz
    ├── be1d08caa58e73d1db433c296541f84e83b0990b.nq.gz
    └── be25bc968e6f9321564fc84ed735647968dda78f.nq.gz

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

[UKPLab/emnlp2026-agentcibench](https://github.com/UKPLab/emnlp2026-agentcibench)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
