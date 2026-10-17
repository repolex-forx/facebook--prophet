# Repolex Knowledge Graph of facebook/prophet

RDF knowledge graph data for [facebook/prophet](https://github.com/facebook/prophet), parsed by [repolex](https://repolex.ai).

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
rlex download facebook/prophet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0cf18fc38e002cbe7f2cf77a81120e6c26d5b73d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0cf18fc38e002cbe7f2cf77a81120e6c26d5b73d
│           └── chunk-001.nq.gz
└── blob
    ├── 0068584ca4e044a66647e90a40f3a43bb6201d5a.nq.gz
    ├── 012254f76c545dd16e8a71091a0cbad93d3e4b34.nq.gz
    ├── 0253da57ef9e4ca8e6b7fc4669dee6c727803094.nq.gz
    ├── 03a869b1f0b821c87872795e6ba21b18ba9c56ee.nq.gz
    ├── 051e1f2450fc042f70aa26e5dc24dad6e4cbd66d.nq.gz
    ├── 05bcb34a8f18eec7a41bff9013f4c98f62ceb3f6.nq.gz
    ├── 0631c8cb14868722a774a6bfe8bafc1fe7b61d52.nq.gz
    ├── 0632832a2ecb9c2f51ff34fdbfba1ad968dd5dbd.nq.gz
    ├── 067b3bed5b407c0a9f6010661f37c53c69a025b7.nq.gz
    ├── 06cb231b5612a9f42973417ee6e72775ad7b1614.nq.gz
    ├── 089222c9f69f04890246351d803523c7235d2dc6.nq.gz
    ├── 0a500e4fb223ed5b92416779640950ccfedf5a1c.nq.gz
    ├── 0ae418152a30e3c9a08238f95798cc47021b2f47.nq.gz
    ├── 0d1310df83a0066048a088e1c4827e33ee3b7edf.nq.gz
    ├── 0d40b3f8af59e953fedb6a2c4968d5133df15ac4.nq.gz
    ├── 0e0ebe4f019c16d04d16fc45a9fd93e002812dae.nq.gz
    ├── 0e5f2e0c1d30992245a7025ce19ebbf5ba555d7b.nq.gz
    ├── 102ed91ba486d14d0df39665cb5fb85768ce9bbd.nq.gz
    ├── 10315e062aeb92c6d9d42b8242f45824d267a9c0.nq.gz
    ├── 1114b29014ddd8a0ecc2d73186260720bb4f6e41.nq.gz
    ├── 1166fd33e0ddde46de6cbc61bb4b896c36ac4500.nq.gz
    ├── 11c194b7164b6baa86f3fd291b3f94bf00623c11.nq.gz
    ├── 11def86914b328ba8888037843b9186aef408619.nq.gz
    ├── 128b39d8b7ae8f74739e4bbcc4dc269c3ebb57f6.nq.gz
    ├── 13c0e562b76a0d46df54a35ba3eacc97c40630c9.nq.gz
    ├── 142c1c9c48d42989e9829318ea1024fd2e08c370.nq.gz
    ├── 178847b408b8f61fb90e0df28a32b9c45a4b09c5.nq.gz
    ├── 182f8bcc7c840fb8ff46a3775114061eb7c74c74.nq.gz
    ├── 18acdf93d0350f193f97e64dcc62f00e1c6c0321.nq.gz
    ├── 194337d883e15fca24b52b81ee44dcea3bb7146b.nq.gz
    ├── 1946f8e63809a42445ba928be2f8303ace6e5a89.nq.gz
    ├── 19fc7fb235ad383e6fb03248aec559bb6a1cd14b.nq.gz
    ├── 1b57717f00ac06f020fd06a388e404bf92afbf2c.nq.gz
    ├── 1b99f127297a02f0b66d92546404dd89f64381f3.nq.gz
    ├── 1c047986921b22d47cf529024a8dc8ee5e390176.nq.gz
    ├── 1d4f76c68a035596b0ec05161c0be2e234b64ab0.nq.gz
    ├── 1debb0464e2d1b4987a36ad47dad4e1614caf1ee.nq.gz
    ├── 1f255c9f373e1cc7cdd338faa31c89cce35b04ab.nq.gz
    ├── 21dbd873fed55132fa45bf965d8f112e09a53985.nq.gz
    ├── 2496ac82aed23ba095ae0539662dbc6a12e5b065.nq.gz
    ├── 2546d5dd79155faf46607e8c71fb3292b18364c1.nq.gz
    ├── 255da059aa0e474c2c9494869d7c8f0bf3301020.nq.gz
    ├── 258a75a8838b2204112a4630bfa2994a2bb19027.nq.gz
    ├── 2593ddf1be40a6c4b4658b1cab8891c1096ba11f.nq.gz
    ├── 25dadf7439e3af957b0775f7a1e6cb1da1b441c9.nq.gz
    ├── 26db4388ba1dcc36f061ec4ceb2da089e0ef6cb0.nq.gz
    ├── 27f6b49b6e6ab312357f4853b0412f79eb8e7f86.nq.gz
    ├── 293dde15d2118acbcb2bbc0d26535519c9451e87.nq.gz
    ├── 295b9d4fd57e939bbf7d381075496d478a10e018.nq.gz
    ├── 29fed9dee2c969b68de94c46e44dffd6839309a0.nq.gz
    ├── 2af02df44cd7e8104fcb5dce4b66306b9d6a79fc.nq.gz
    ├── 2b0dfa6c898773c7329ba09fecb6870687bdda8e.nq.gz
    ├── 2c0c534470292c2be488d0a7f91b67d7a98df80f.nq.gz
    ├── 2d466ca9d87ea98de2f5987bca97a0867a029af0.nq.gz
    ├── 2e20953f27ceb26b83ff8bb5a404882b1cf3e4b8.nq.gz
    ├── 2e2fa5d15fb15d97930d2bd132e9658633b74b2f.nq.gz
    ├── 3062fd47cc4552eba52f26026e77b7cc9ad7b1f9.nq.gz
    ├── 3076fb0a018c616bde9af2a0cba34efce1e38d4e.nq.gz
    ├── 311a7306a0035dedf3f4d8d9f38f40642dcac1ae.nq.gz
    ├── 31fb71ab7edf4c3ebccbb9630cfa4c907a0c779e.nq.gz
    ├── 331951355104268a79f1414a680d8b61815a6ad4.nq.gz
    ├── 33c9005ced32c984f083470246fa7bcb97ec1b55.nq.gz
    ├── 33da327c89f2fce87ef39ae166a47cfa0d206211.nq.gz
    ├── 355ca09c828c7696ba737d11a9b574722e421f19.nq.gz
    ├── 35bae0eb2d1c27f5f408ae89c6b0c39e15d4b7f3.nq.gz
    ├── 35d574ef8f9e73008abf505f405ef414b548bdc0.nq.gz
    ├── 36715b5fb1ab3f3aba417d66e12f4d8118477510.nq.gz
    ├── 36b0f94c09881b1c0f7664f0a5ff52826e71b1d5.nq.gz
    ├── 388b0e137746317f6b973a74e1653ea25ee6c34a.nq.gz
    ├── 3909583b42e0d09c0c0bdf884be06084b042f77a.nq.gz
    ├── 390a1b82c1506f0544015ff01c646c04cc81f419.nq.gz
    ├── 391046829ba6d7cc68641895d551b9aceae3dd81.nq.gz
    ├── 3985caabe71bd30a84c100c1100e28e35566936b.nq.gz
    ├── 39b78a90c0e876a49e055cd72a80e6f115a0a553.nq.gz
    ├── 39fd582c5d2efda8344d2d267c6abd8aa0d4f42e.nq.gz
    ├── 3ab1f5f1958c948285f0d6e7a870f3795c835fb2.nq.gz
    ├── 3b3c69dd1d689438a28e6dfea54ba8376de84f14.nq.gz
    ├── 3b914da24fe076a402f684097d6a6f5718ae2c74.nq.gz
    ├── 3bbda9138f5bf3e8809db4c27d9ce9931f62e38e.nq.gz
    ├── 3c8bf3d7084d9bede355be29e4688d3b80772f23.nq.gz
    ├── 3ce3141a9f79238aefb08f68ea1861514c1239b4.nq.gz
    ├── 3d899021f84060718c5909f132690f66839036a4.nq.gz
    ├── 3f4353b3cc894ade36e908ffde59d91f2585fa2e.nq.gz
    ├── 4127b4d0b9f0977d1a366a5ec6537ded003fcac0.nq.gz
    ├── 4155b605361541322418a3dafecce2d0ae588b93.nq.gz
    ├── 41aa91ec037df7da82df51d56995ecca28f3c493.nq.gz
    ├── 4215139b07c6709cc3bca89fd131dfd81148781d.nq.gz
    ├── 429ee3467dd3ddaef0ff7b9d7245b869e24e28fc.nq.gz
    ├── 430090f81c2ca11422390ab4f14a17e6b11e0e73.nq.gz
    ├── 44b96298e641aa2ca9aab0f600966032174e2e59.nq.gz
    ├── 46295fef233130cdd440647ef8f2e3b8b37b39a4.nq.gz
    ├── 462b76e403803ba21bde16609aa862eece9c6365.nq.gz
    ├── 46ae22aa1d1854052ec2f2baa7ac216ad374b0f4.nq.gz
    ├── 47eb4864ca9fd0baba7950e26261ac19daf1660d.nq.gz
    ├── 4861e8f8c5632a5f23b7e2a54f74db08d8134d31.nq.gz
    ├── 4b26abe11cdc28fc64f415d4c0b4007a8707be65.nq.gz
    ├── 4b63053e77ca132fccfcc3001e014ea44686a6b7.nq.gz
    ├── 4d5f38133fa37cbd26c4d886687b02cfbe3043f1.nq.gz
    ├── 4e6447c607db1404af8020390f0c65123147f1c0.nq.gz
    ├── 5000604cd5ec00cc8e01314170f034b3944323a4.nq.gz
    ├── 5337f24ec876581eb76833f5dbaf618734b83ad3.nq.gz
    ├── 53563814dcac74242f72e9a786330cc0a991dc47.nq.gz
    ├── 53f64c26ed4b425d517d9bb2ac27259b8a916c62.nq.gz
    ├── 54f46faaa1265cd16bc2d9e8a2d641bbc72a8f75.nq.gz
    ├── 556739702003f414baa260145acbd33cb602b815.nq.gz
    ├── 55c88d72f56aea5f332243302d2ef5f1e8966a68.nq.gz
    ├── 55e2006bac85b80d88e550677cef626269f46692.nq.gz
    ├── 56ef4da21de55dc9aa2607bc7e79b710a909dac0.nq.gz
    ├── 577781e862664710d21f3a5e383daa63b0f79905.nq.gz
    ├── 57cf3fea62f478ab58ce7cd7c70fbfbb4e30bdd7.nq.gz
    ├── 583fd5721689e2c51b8a6f333edbc9d699c56232.nq.gz
    ├── 5870caca48b813d0ec0e1436cc31dfd8dea6c876.nq.gz
    ├── 59b2e04bf4ce54a220a71f77c20be00a8b8abcd0.nq.gz
    ├── 5b030d235c2e7a26bd1c7fc598edcb99c2b2f8eb.nq.gz
    ├── 5b601886131b044f9738fb1a32022bb045a52787.nq.gz
    ├── 5b7439517997ee2dafa40531c5e8c849e120ed5d.nq.gz
    ├── 5c0622d4bd91b1c903bf6621c4adba3bbf69a51a.nq.gz
    ├── 5d5b880b655772eb3db68ce28cbf022aa22b6114.nq.gz
    ├── 5dce112e1061cbd0d26a8f6591fd86cb1320f108.nq.gz
    ├── 5f02ead9c13653c5cb8710256d05b495196be433.nq.gz
    ├── 5f9537f83870c6eb81b7285fe1299a4107416174.nq.gz
    ├── 601b36b66494fbdd22515ba2f41984819e78640d.nq.gz
    ├── 602a09444af3f9d3104c3d338d9d562625798c7d.nq.gz
    ├── 6065c67cff5a675743f6c851784f02fd41738ed6.nq.gz
    ├── 614f9d87ff0c1ba14366e4575df0d05acd4582e2.nq.gz
    ├── 622ee65bccf4bbd35ab4cacc8896a1876d011ae3.nq.gz
    ├── 646df3b788c361d44ed87e120fd1f5d7a83363c9.nq.gz
    ├── 6497ae131334485c09d4efbd29f665c6f46157d8.nq.gz
    ├── 662dcb8d171b37687205b8e51291b834de76e0cf.nq.gz
    ├── 663c16684a7b791fdca34b6fd6b7890c5238ba2e.nq.gz
    ├── 663c22e862558e5e589c996714651663706a7230.nq.gz
    ├── 665f4b9f5bd6236f3ac09c9b43dc3921e05a6151.nq.gz
    ├── 678e45b1e51084a3e3ff4c46122433cbef3bf2a8.nq.gz
    ├── 679b31c14c5daac4534f0d8bb3e90c43990a3f2f.nq.gz
    ├── 6bb5d9cbacc94a659af0a0b644aea7b3b501e455.nq.gz
    ├── 6be82f8f452d20bacc3a47251243bad5ac4e6d47.nq.gz
    ├── 6c739c2f3005645756e392748706f269f6a007c3.nq.gz
    ├── 6cb38f3f04ec780dea15392f5d6be4aedd559826.nq.gz
    ├── 6ccbc2bfc9c5846fb1b3b1a45bfdab7cece31910.nq.gz
    ├── 6d26d9feba6e09f331d9c06396c3fa129c7df3c7.nq.gz
    ├── 6e8079e9ee6564f5298f90f289bcbf577da514e0.nq.gz
    ├── 6fb862d23b0309ee789e3c8efe7b3e57e86e6f89.nq.gz
    ├── 6fec26c8fbc4e91e5c7a13d46b14243a5f7fd29c.nq.gz
    ├── 727aab90809e433259db1ab4de4300571a6dc469.nq.gz
    ├── 738233aed1df84221e54c0f65246f15edeb9e8f4.nq.gz
    ├── 738749ef09a9b4fa9e6bde5dabdc9bcd9b6e7d4a.nq.gz
    ├── 74335d10b41f68859d1f2b2918d9a6113f97c96e.nq.gz
    ├── 7496452e069ba40673622d48f075c2e2ac603acb.nq.gz
    ├── 74a399c99bb8229cf4810c1b6bd6c5b96b5742a5.nq.gz
    ├── 75c253f164c764fb4e4a6ae3122075ff7c8314ac.nq.gz
    ├── 760d9231cdeb4e03357e4d9a76cca75f8da70c60.nq.gz
    ├── 76219a74cde8b7a460cee61ccf0b32cc527676ee.nq.gz
    ├── 76e24b6b8be0e3fe9b883bbab91c4211ef7d1604.nq.gz
    ├── 77451718d6e1453db6aac6307f92ca61f3ced550.nq.gz
    ├── 7817c91f7689efb9d17e58883d26a61071448900.nq.gz
    ├── 78827092433e20945c05f24f1c03a16ee1b7c3cc.nq.gz
    ├── 7996201383e3515af6945c62c955543e8d4b8df4.nq.gz
    ├── 79b465846efdca363c7f8b29f2ea19588a6c32d1.nq.gz
    ├── 79c4967502c18d45bfce5bfe9435100406512225.nq.gz
    ├── 7b9af138614564da787f39ed4be095f526b472c9.nq.gz
    ├── 7bce31beb224d84570f1905f9977aa57d1485c1c.nq.gz
    ├── 7bfb2b16395f833d5e35023c19eb2d3c29d2d627.nq.gz
    ├── 7cd13e3281087ac77ac4ef70d98d7afe9944861a.nq.gz
    ├── 7d0db8d0e54aaa1f1e3da727cc56070d329b5a31.nq.gz
    ├── 7da9d7688fd3cefc4d60cd8b4cc69644123d7ad8.nq.gz
    ├── 7f6591f14d869404ed0a4e70603c4fd03e9f23eb.nq.gz
    ├── 8051188c8dc3bcb57814f77d667735deefedd2d4.nq.gz
    ├── 81237180e92b89979dde443ecf40aa3bb10f14c6.nq.gz
    ├── 81e689779b5257d49d1357bc547f4c90f4c3cbc1.nq.gz
    ├── 82cd5858915329077c1b3c743527f95d25001542.nq.gz
    ├── 831e6c0f4984d1a8dc82067efb40d407aa0b0427.nq.gz
    ├── 844538215cc3fab647c19ff23b0e2ae51c64f4bd.nq.gz
    ├── 84851c1601780bd235969432f83e99a4848b6475.nq.gz
    ├── 864ba33e6f54cc98d597cf83bc15a825a066b9a5.nq.gz
    ├── 86953ffeadb035ee72e0df238fbde103c2f6d461.nq.gz
    ├── 86bd9d8876e014c5a52fa0552c7759309cc21e5d.nq.gz
    ├── 88ff2b5da5290b15e8432217ec33020881dd5aa4.nq.gz
    ├── 890b5334f8c4c470c63fe58af0b35ec06b1ec9f7.nq.gz
    ├── 8937e67f524e4d34d4fbfd54a813c77ba1f27b56.nq.gz
    ├── 89f740c06199cc4fa25cdd4aa56049d0e3591d5d.nq.gz
    ├── 8c50c5a8b63e1ac1f4ba2b192d158e59deea5781.nq.gz
    ├── 8c9a809dcb14a63480015363d86f72e0e094ec98.nq.gz
    ├── 8da0c491a5b9bc7387a3203b913b763a39143e8c.nq.gz
    ├── 8da20251309a512b0626bc5eb52801199f506e54.nq.gz
    ├── 8fa113ed2d5612cb7a97b2be0c50f816f260e501.nq.gz
    ├── 8ff75fa003af79b7e5032682f2a5cc4ee89d6738.nq.gz
    ├── 92efb798bce728b5b554456c89b33a2c585aff2d.nq.gz
    ├── 932df50317d187338ba62b4f4776e04b59392007.nq.gz
    ├── 940b48bcfb46860216dccd76e42a09e77e6157f0.nq.gz
    ├── 94af754571464d3ddc95da6bc99d3b6ca94475c9.nq.gz
    ├── 94d77bdc623191396aabf67b396a99f5e3c9b413.nq.gz
    ├── 96b3be11a5cf961abb34e33316ceb48f67cc28bc.nq.gz
    ├── 9921fd56c62f18587f345df0726dfb44262acabe.nq.gz
    ├── 9991400b3878368d81344b6aaf4a3a6bdf9a8734.nq.gz
    ├── 9995d6988d0b5a5700ef95f581d3c8bfe831615c.nq.gz
    ├── 9af38424e7cad948261faf1b2f2e688e7009bda3.nq.gz
    ├── 9af6755d240ac5480bcb848626182937d1b2fa83.nq.gz
    └── 9b990e19e477524cfb3472fd0193b3e6f2f5e53d.nq.gz

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

[facebook/prophet](https://github.com/facebook/prophet)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
