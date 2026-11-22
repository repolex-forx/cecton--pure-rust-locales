# Repolex Knowledge Graph of cecton/pure-rust-locales

RDF knowledge graph data for [cecton/pure-rust-locales](https://github.com/cecton/pure-rust-locales), parsed by [repolex](https://repolex.ai).

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
rlex download cecton/pure-rust-locales
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ccef8b36a9d9dc98216ecf2149eb287f89885cad
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── ccef8b36a9d9dc98216ecf2149eb287f89885cad.nq.gz
│   └── repolex
│       └── ccef8b36a9d9dc98216ecf2149eb287f89885cad
│           └── chunk-001.nq.gz
└── blob
    ├── 00fae2b94ea73c342d6b2aaef8da4bbff8d11768.nq.gz
    ├── 0256e42979c94887c960f5ec340f97b7084c7e44.nq.gz
    ├── 029a3794e2a17dcb67eeac074c5d7019bd45724d.nq.gz
    ├── 02bec3e9aed6fddc85d6de9034b3a4e6acf4349e.nq.gz
    ├── 03b8350749ab2c0a66e1a4f744c99bfaa6a562cc.nq.gz
    ├── 03e60f838a41584c17d85a4ae3dba773110fbb3e.nq.gz
    ├── 03fb0f54560fcd76a96a49bc31d9fe28e2ec323c.nq.gz
    ├── 05a2681bef5242c24d57156cf28b4a54b8de3eff.nq.gz
    ├── 072270bc4d8d834f72257afd17df2fb092019eae.nq.gz
    ├── 09c42c7f6ad1f7a95e17584c6c78f2616802bf3d.nq.gz
    ├── 0a584114b8f06590998eb1927bc2bd452673e04d.nq.gz
    ├── 0ba74ccf33267989f272e3030f59346eb6af16e1.nq.gz
    ├── 0c1405b37ab9fce2104ba3e3507bb11ede9ebe13.nq.gz
    ├── 0c2a56f4cad2847bef31d47a075feeedef7ac7d9.nq.gz
    ├── 0c8b6b6057424c8204bbb56e26e23b3573bd9796.nq.gz
    ├── 0d8c9ce78ddb1d0ca9625dca8fb6a4413b43fd37.nq.gz
    ├── 0e0a79d2f1b9445f376e045602a4bdcccdbf87d1.nq.gz
    ├── 0e63580f489e2ffa288203a038870fd5f158af1d.nq.gz
    ├── 104f4152a98b37abd55ee67b94a6427951f272e6.nq.gz
    ├── 10610e65f37bcbe4d072e17c2d6f8ccd3f975650.nq.gz
    ├── 109201c2fe01476afd1a3b564052a1b126439848.nq.gz
    ├── 113294a0f58ab576ce82fb3f3c58f6688049c1bd.nq.gz
    ├── 13825880e86f17f0c8f3499bc259e7fda0625a64.nq.gz
    ├── 13fc8e91f5b965fde91cab2b9b37922aac115c5e.nq.gz
    ├── 14047fe0b185cc85abbbde83668000db6c8e925b.nq.gz
    ├── 149fb53771feab23a866a8cdfda88975a4f6e453.nq.gz
    ├── 14f850a98a5e4490e736814189822df7f6fc1a10.nq.gz
    ├── 156caf26415cd9c7adf774bf7d004196c1b2f4c6.nq.gz
    ├── 15787b93f98e7388eecc58006fbdd4aae13be3bf.nq.gz
    ├── 160d4abb61bc68b910c2fe6218e614e4603da7fc.nq.gz
    ├── 185c2099ec339b2bf3ab949f87014455f829bb88.nq.gz
    ├── 18ef57adbeac93f69b4e3c80fa20f98529d6bad6.nq.gz
    ├── 1952b3924f77f1e4a39b89f36329bf72c1199662.nq.gz
    ├── 1bc7c4a7d9c799319b39460e2b1eaa8dd4ad13c9.nq.gz
    ├── 1c2a2fadc766d864565d5766adeee6d7707fa7b8.nq.gz
    ├── 1c68aa261145cc8be7de92d73d4a82b7b951b116.nq.gz
    ├── 1da76705dbec80aa66482abdd89ee902a1cd08c7.nq.gz
    ├── 1ff2a523aa65f92b78bc54c65c6a340e9321fedf.nq.gz
    ├── 20190925034c9ab443183f111e0b779d75635144.nq.gz
    ├── 214c805c839c97b222c7eb9b5a113f6a53d52a45.nq.gz
    ├── 22612d4c94ed691213ae12ac8cfca86917fd8312.nq.gz
    ├── 227400cc4ea4362d0e82464a803ec534a0cfe3a6.nq.gz
    ├── 23dc86dcf1c1453b7e45af50fd527b4838e9b95d.nq.gz
    ├── 2483b0416755092b9ab038c3a91a50e42904a47c.nq.gz
    ├── 251b50e6d7fa292c7035b4755ecfdffa29ea432b.nq.gz
    ├── 2603bf18be8f3e50275e6ca43d2486a8a46c0e93.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 261f9da0aabc1e0741f9992c6c39785df17e6927.nq.gz
    ├── 266ff17e7dd569f02cb06dfcaa080c8bb76908fe.nq.gz
    ├── 269712b60f5b3ac9057b1eec123f81fe9789fb31.nq.gz
    ├── 26a9142bb56b48f83f985cdbba8faac594af6bb2.nq.gz
    ├── 272fa7e78f4d77f24684a254a85e127bf30f1e1b.nq.gz
    ├── 28055f335bbc5da71c185e3b05e7b04cb323d050.nq.gz
    ├── 2823005c0635b6cff731db8049320424bcaacb10.nq.gz
    ├── 2857a9755495c9ff085d855a09ff4f3f34530415.nq.gz
    ├── 28a908bd4a5cb4c6ec453dabee3931660388b457.nq.gz
    ├── 29fdfbec499e147676a9b4d4110a711fc1e1db01.nq.gz
    ├── 2b5a4b7bd660fb6e500c3c9fe8e479317fc25db3.nq.gz
    ├── 2bb4f0e0eb82aceed00fe12c3e7b5ba99637c3bc.nq.gz
    ├── 2d23b0f93ce8f538664b9314ac7aa41d9cf7d32b.nq.gz
    ├── 2d6e5fcc5c136181dcc7a4b2403c2e4ecd0142d5.nq.gz
    ├── 2dae80c8aa8fb9949d3a825ef1dba42f4688f747.nq.gz
    ├── 2dbfcb3c6572cd0ca77f98e155fe5f80feff0ed1.nq.gz
    ├── 2e4975e7b710b5926264071224336b278341c063.nq.gz
    ├── 2e6aa85f6fdd0a1e6349aaef56c6ff3987b0fad1.nq.gz
    ├── 2eba7d2630f8a46deb8fbf449e13930d111e295d.nq.gz
    ├── 2ec46b10d2ee2882707bdfd63951db74b0e27232.nq.gz
    ├── 2f089cdbeb7d0d5536ff187493d2d266797fd64c.nq.gz
    ├── 2f24efc605609c002f7e13dbc8e50e7a5de677d4.nq.gz
    ├── 2f45ddad638ba99681ce36cb4c533225e01bbd28.nq.gz
    ├── 2f8fe420ccce119f0d3977a0e2cc90ef99a37bbb.nq.gz
    ├── 30b7d8160a644a60899334c885df80ad22fc8c96.nq.gz
    ├── 31cb4673dfa4a3aa4524cc5ea6ecc84b30115fd3.nq.gz
    ├── 322c0356901af898f48c3ac15fbf5def3e3c71da.nq.gz
    ├── 324379b65a1849834a1be87eb8bc692dccbbf456.nq.gz
    ├── 32626404d2956e8c1728bb1e5f2005007f7d11b2.nq.gz
    ├── 3273affedd3945874e35bbfda0f44214259c741b.nq.gz
    ├── 327f7250987aaa5741bc5fbd78d34da082fb9c11.nq.gz
    ├── 33db4c4ef5ce0c26282abbd7407d91febe1e1afb.nq.gz
    ├── 34f522a3a1e240397c43d4ab79314901092bc48c.nq.gz
    ├── 352790adc0eb227cc7604c2237d0dc3da49b98c7.nq.gz
    ├── 35f30562511c32a3302179a9520c1967abc2d050.nq.gz
    ├── 362294af5a3a12c530be2c0a41cb42b0c1588284.nq.gz
    ├── 3701909dd04a5c7826dc0a8f27b204b6154ea6b3.nq.gz
    ├── 3714a30932189ab4c29f2db642b6978a3e04cd76.nq.gz
    ├── 3745f21e3c5e8420d7b8eae37011b4861110d957.nq.gz
    ├── 3854d0582a3d21db7ec7aac41615e6532862502d.nq.gz
    ├── 387e109109fc037472cd968b7dcc718eb91c1f89.nq.gz
    ├── 39c4d09a07773f9c4e2cd976edd157b2477a7ce0.nq.gz
    ├── 3a89e50ae9b6f049dc2035c269c045b706a95fc2.nq.gz
    ├── 3c0db0be3de1e6d352397d3dbfbed1192735ef5d.nq.gz
    ├── 3dee82be4e4fc9dfa3af8541886b5cfa7e47a87c.nq.gz
    ├── 3f4f88598cb885ef917dc34de33b893443762302.nq.gz
    ├── 403a919580eda709464132f2d19e326c80309d39.nq.gz
    ├── 40ee2d7cdc0e9b265458c01f8496a4164d51f599.nq.gz
    ├── 419bb6691bc340348e9d8a5e8a158cdd297a55d6.nq.gz
    ├── 420076cf7263d9d583359c18048ec4fdd6ef36fa.nq.gz
    ├── 42f67670d02d37637c681941fd2f816ca19a1bff.nq.gz
    ├── 447ee3b6d5b1e835734005be97d1ba51ac08752f.nq.gz
    ├── 44a33d744d21f36ba5ddccfdb17cf6f4c5c1e225.nq.gz
    ├── 44e84e86bc98e7aabad5f935db1f334724204556.nq.gz
    ├── 47133dc65df3d48ffcf085dc7a3e5fa898b28b11.nq.gz
    ├── 472843c7f77b8ed61c15018fbfed179e9bc03acb.nq.gz
    ├── 473c043cba3aa031789b0344f39af0b1c0b454d7.nq.gz
    ├── 4740418a83a32cedb4eb9fa3bafc5585b795924b.nq.gz
    ├── 488455ae246e553e9947a485961dc69e65d321ad.nq.gz
    ├── 48d4153019ac60a64599457b12fad19f845db39c.nq.gz
    ├── 49800a83fe3051a62261c384a7d14b07595f8452.nq.gz
    ├── 4b3b5cff75485a59edf03d78d822e7310b4ed855.nq.gz
    ├── 4c1b2a869dd8ae1aaeaf36ef18c6c3903f9c9c90.nq.gz
    ├── 4ce7c7fe4a416541d6100ff7357b64de92b537b9.nq.gz
    ├── 4d14330749f242ef00887dfcec8324c1ff1d864c.nq.gz
    ├── 4fa1bdfff94b9efdf6f55545e2dfb8d96922532a.nq.gz
    ├── 50ba5aa4348c960b36620df2a0a18d2c9fbdad78.nq.gz
    ├── 51ce9ef92b4a8097b42fac1e997964134307b76b.nq.gz
    ├── 51d31fca79b1f85411f7ff5b60ec8b05a781781e.nq.gz
    ├── 5225430e177bd2558424b4f1469c438fa8e807ec.nq.gz
    ├── 524ec8a3471f27fedffd7046db64fe82ee2aead1.nq.gz
    ├── 5271c5b6e24b099e9fdf3678cc2d496e49ce0d99.nq.gz
    ├── 52b5a6bff0fa49c2d72984a6fab53bd841cf1b39.nq.gz
    ├── 52cb6c8676f5053c048779d862c0801b9deee677.nq.gz
    ├── 53bdace4b3107608441792b4a0d6659fc182e0c2.nq.gz
    ├── 53eaa21960d1b9c229de5e6ca9becd1a6089c021.nq.gz
    ├── 547c0a10d6abfadb6490b7769e21e7223c718298.nq.gz
    ├── 55e787a5cdfc559ffdaeafe2e6f69af7864eadf2.nq.gz
    ├── 57563c35126dad9c57bdbab0418e65d701e965e0.nq.gz
    ├── 580e8303f660b207bd82bab8d8372c4b449974ed.nq.gz
    ├── 5b06a1ecfabd362b5fad1a31fbac9e822a80597a.nq.gz
    ├── 5b180db6840fd24b39a487f322e12809a2b60c22.nq.gz
    ├── 5b6c6e231256089ae89393591480cf7229fb3a24.nq.gz
    ├── 5b895574acdeef2349bfe4a7307c3fd23ce612ce.nq.gz
    ├── 5c7629f704f8eff1f9f8ad5b2527eb837f84327c.nq.gz
    ├── 5d19354ad65069eb66d7351cf1ddf5de86a3714b.nq.gz
    ├── 5d532b4ac46b384bbc4c628b3b976b51508ba770.nq.gz
    ├── 5e40629ff1f646b2d324cb8e653d92a5f2c9d754.nq.gz
    ├── 5e900ac66cb2f12f04d7bdde3b57d2c6fb3a6f14.nq.gz
    ├── 5ea9796b6765d23a4d9ccfe483df7c22a3c80ff0.nq.gz
    ├── 5f3919cfa8cd6587f14845af8545aeb1d5dda487.nq.gz
    ├── 5f422a4fb0349d747db0550aa90e4ade76840286.nq.gz
    ├── 5f6fd7c87f1898a1916b41828e95f56e7cd4eaf2.nq.gz
    ├── 5fdb7e8f2759ec36935bf4380b0e626295f8d17c.nq.gz
    ├── 6026bcd5878d2291491412cd34dcc996a170bc1b.nq.gz
    ├── 608378d205a5553298fffe256232cc7fedef19ee.nq.gz
    ├── 6157b26d4f1b8462a767da1c94c01bda6157ee0f.nq.gz
    ├── 6225036edf7e8723c8fa752540072bf43bf8aa0d.nq.gz
    ├── 6232998847f529d37670e01606481e4143c6301d.nq.gz
    ├── 65b8e5f5bef33a304dadf3c5d47d6c22873dd081.nq.gz
    ├── 65dbc161daf78e381c3b647e198f4ebfd5a975e2.nq.gz
    ├── 662dcefa15a2cae33d8ef67a2609cc6a39065025.nq.gz
    ├── 66ae3018f7beaf9e32adc33799dbff71802a4b41.nq.gz
    ├── 66cdcf5c45b75cd2e054c03526d0e8fc330785da.nq.gz
    ├── 67360c1d13551f982742fa21239d5d3b0fe20942.nq.gz
    ├── 681e94e484914fe8adf614d41d6ee3a32fb62bfc.nq.gz
    ├── 6950da96a41f7bfbc40d1a2e54c36e72ab1945a9.nq.gz
    ├── 6a8801374f27f7f11aed854fbe788dfd49529a8d.nq.gz
    ├── 6b6ab1cac9ccab1485f20b6de062a27033d326b4.nq.gz
    ├── 6b80455c98de7fccd58b1f84adf7311a6d71693e.nq.gz
    ├── 6c303da983f2cd480ebb5df0068505538770eca4.nq.gz
    ├── 6d1e4d8ab339501fcf1a1eff27610fe95f03dae9.nq.gz
    ├── 6d85e1b1107872ed7521f57e392cdd83a47cb243.nq.gz
    ├── 6f1d3eac341ec13175e555e6222d7b3e404d9e4d.nq.gz
    ├── 6ffdab7572fad3a1208b45404deeec557901cfd7.nq.gz
    ├── 706ef3e50aa5a6e1b1050ed25d300ac6d2546c0b.nq.gz
    ├── 70dd1cad2e418a4dc03bf0c8ea9bfe66dc613825.nq.gz
    ├── 725ff594c0c9285f67faaabfc8da871fb7b221cb.nq.gz
    ├── 728dcfb879e515867d17c774cb7088e1786162c6.nq.gz
    ├── 72f66220b79663c2851c6807e30c454199e84d84.nq.gz
    ├── 7362492fbdaab731ece4588d55d32b61508379a3.nq.gz
    ├── 73b9678ec4b230551db99f0489ccea4e58411da2.nq.gz
    ├── 73d6b69402377d8bf46c573ac6877fc18c44efe4.nq.gz
    ├── 74e1b77efb27aab68a4c0f24ed43e24cdd21abf7.nq.gz
    ├── 75cc000c2357d9cbfb27c6241996113d1b1c1a63.nq.gz
    ├── 7846d6278c4d7756e215f5e6b4e96e5af4f2c076.nq.gz
    ├── 78ff7d27a65a53b7678f7dbf474b781226fffa86.nq.gz
    ├── 7a10376e8058a3f38b5fb3a98c05a20cde8d615c.nq.gz
    ├── 7b8b6b4d7f7e644f58470b9beb29cdffcfc656bc.nq.gz
    ├── 7c4aebcff12bd6b175a46c7120dacfcf41b3e0c6.nq.gz
    ├── 7eba1bf107f77fb4aaefd88c593cb530b6ab483f.nq.gz
    ├── 7f51b82aa8d558b556698de8c7301a6437394c8e.nq.gz
    ├── 7f9c6b01973d34f4bd83fe9d3d6306a90893fabb.nq.gz
    ├── 7fabc5f80d9ae5e53a6d6e7b20478d05e0357b91.nq.gz
    ├── 7fac1fbbcc21c46e6cb02a4370ef700727749e32.nq.gz
    ├── 82ebc2f0d14091f00a99958d9bba0a762e754793.nq.gz
    ├── 831eff0910547fa67bac1628b04e91ac79d02275.nq.gz
    ├── 832e6d67abcc714eca3ce3fcb1a6ad017441eaba.nq.gz
    ├── 846363223883723bebf51896186a47e1c2ca1c64.nq.gz
    ├── 8473426eab9a6174e40d1ce333f531ccf96c0238.nq.gz
    ├── 850ee1e5d501781de0200838c6239c648adf93f7.nq.gz
    ├── 85116e5e9cf39327241b2e2e438d60a5e3665405.nq.gz
    ├── 86281a27db1cc64d4890792997c6514b9ea18493.nq.gz
    ├── 86868c02e9ae2e1ca7159796dece163217c1d652.nq.gz
    ├── 871b8a818bb85b05366dca231504e65477c731b5.nq.gz
    ├── 87bae1dc7ce557371d21ea4e4eec010b6c043a4c.nq.gz
    ├── 87ecf8c98fd90235a991bfe64bb8dd4964fcb712.nq.gz
    ├── 881b43fb1769970fe610dcaf28da9c91ba7d67c7.nq.gz
    ├── 885481974c8b531b9fdb5e20bf8f44617b312694.nq.gz
    └── 88890f71e63ae507dfadbd3c90383847d5c1664a.nq.gz

8 directories, 200 files
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

[cecton/pure-rust-locales](https://github.com/cecton/pure-rust-locales)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
