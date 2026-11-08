# Repolex Knowledge Graph of scrapy/scrapy

RDF knowledge graph data for [scrapy/scrapy](https://github.com/scrapy/scrapy), parsed by [repolex](https://repolex.ai).

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
rlex download scrapy/scrapy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1bc0473909e4e5a3d0b62710715b6383c5641765
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1bc0473909e4e5a3d0b62710715b6383c5641765
│           └── chunk-001.nq.gz
└── blob
    ├── 003076a1dffe461813003398d90cfbcade879d81.nq.gz
    ├── 0058896b5a96e8222e78450137dae25bf48f88b0.nq.gz
    ├── 009b20ac885c549d77d6c95a0637765d1177b752.nq.gz
    ├── 00f483ada13aa0f4d19e9b7849b50c08dc3eaa06.nq.gz
    ├── 019badb597942bb8a6abddcb5ef0380e292f2c72.nq.gz
    ├── 022650c7c1aadcb15e75cf004bf5eb61fabfb430.nq.gz
    ├── 0261ae903c7fa5180fd7297058c2fa25b4efd61a.nq.gz
    ├── 026226b2ce0d04a25aa50f9717faac01c17bb6ae.nq.gz
    ├── 034cb4f81367fdb99217d28a3264c29dce9b2535.nq.gz
    ├── 0428dde6eb38e633102efba99e5d8387e9dc38f8.nq.gz
    ├── 0461ff8afa1dc476f8d7a87434ebc8ebde59030b.nq.gz
    ├── 04b2d18a778df366efa98bb82a5821bc9a9f15dd.nq.gz
    ├── 06988e0033274af1bb380081394596a68e8cd2c1.nq.gz
    ├── 086606cf9c48373ebc1a8e28e6252d2fabe0bb24.nq.gz
    ├── 08beb66b53a92cd2c3217a7190da774312e445dc.nq.gz
    ├── 09e50fe1f62bd9339e733265366c5a19ac1bad49.nq.gz
    ├── 0a53fdb790ee95fbabd3e55c2a204f3c5182bc30.nq.gz
    ├── 0ac75f754cf121125b7d5eece3ffcfd28d986bdd.nq.gz
    ├── 0b17233f080caa3fb0b11246ff804ed11f81fd40.nq.gz
    ├── 0b3a52cfe04c951930bb6ccf16c85058e9640f24.nq.gz
    ├── 0b7ca1ecd8945c7edf107e87042b6ed4c0aab8ac.nq.gz
    ├── 0c8d1fba881519535bed97356e4783831c2579c3.nq.gz
    ├── 0d11a0996b1c7546e1777d91891a08907f7f97d3.nq.gz
    ├── 0d7ef11cbd6a4772802472d1cc1b1c057f83dceb.nq.gz
    ├── 0dae511a049cac7a28145202c7ec0afdfe1e9adb.nq.gz
    ├── 0df0bbc7c79bd28e89b15f555fe01c594adee792.nq.gz
    ├── 0e4c520d5a8233eb015eaa1804c7253263909dc9.nq.gz
    ├── 0e9884cc831d2da03aaeb0d7795f91e9a4e1ebae.nq.gz
    ├── 0ec87d82ed3e2a0c4dd58880c12466054a889fe9.nq.gz
    ├── 0f3e762d772f9004b43e8feee8def62d9bbcdcc4.nq.gz
    ├── 115b152aa7c40e3fd16cded2d3d069264645c9d5.nq.gz
    ├── 1292edde40ba8605cad2f64137decf4d43fbb736.nq.gz
    ├── 1405de00f2a3c81d49bb6e536abaa493340b9081.nq.gz
    ├── 1490d764623494322adca416e33a4e02fe0a91ba.nq.gz
    ├── 14d982595fa78164eb39e057d392ee7b97ab7ce4.nq.gz
    ├── 14e5cda2a623cd63add80afc4cd6d44edbe7ea20.nq.gz
    ├── 171611c0c5f0c2cf976d0b48625d4eaed4580b8b.nq.gz
    ├── 17b1aa5388ecdacf3696d95fd31e33c72f48e6d6.nq.gz
    ├── 17ba9fb37de8b2bce40b67b26ee06a1118dffa29.nq.gz
    ├── 17c83628eea368a72a16268e921a320011df580c.nq.gz
    ├── 19384b6bd102a8aa6db7c7f6a34f9c86a65f4703.nq.gz
    ├── 1a42f953134031735f77badb5603a5918ed18816.nq.gz
    ├── 1a7e9c61c68d4869d746d4e804d9683c04d10b6b.nq.gz
    ├── 1a7fc89da45df6153469297247072a21d7d23d31.nq.gz
    ├── 1c07f288e457ce4d60aa08649db7ad19677826ce.nq.gz
    ├── 1c2859debf111c6ac90a35a937f72d9898c2b1c4.nq.gz
    ├── 1c5c5f27511d0d6a75719e609318158fe1c49a54.nq.gz
    ├── 1caacc9e4591719bd6eade3963a74bd70d251082.nq.gz
    ├── 1d36a66fce36242f378a2d0647857dceba17f227.nq.gz
    ├── 1daeaa54184d73c4f8bd3f745292a5452a89bba4.nq.gz
    ├── 1e0aea5fecb977d9afa07edd9e4805168c73a62f.nq.gz
    ├── 1e5ae1be7e85e165c4fc0053c73f116d457039e2.nq.gz
    ├── 1f062eef23a5a71a97469935aca357300a1ef9cf.nq.gz
    ├── 1f137de5cbd86c2f3379aa22e897ffc46ce16672.nq.gz
    ├── 1f9c25e431abc5ecaf961af9a17b2a50b1b4f803.nq.gz
    ├── 20423821d10efc2b9939dfad308fb03c08ca9a06.nq.gz
    ├── 21647f288062786d2ba20468d89f14a781a83c4e.nq.gz
    ├── 21679e3aaff0156d61ef60f877eb2894e1755b00.nq.gz
    ├── 21ce3db7c479d526509cfdf5e3cef3a53c1ee7e4.nq.gz
    ├── 21e552c62e6bfe3b4c553870ab5e554e38428f51.nq.gz
    ├── 224606bf64776eb98142624e14d5541f7c3e8d70.nq.gz
    ├── 2271e8ca2ec4bb80d2a54b619624b28418de8384.nq.gz
    ├── 22c499339b6c963efaf76fd794df6e83ce27869c.nq.gz
    ├── 238517694b306bb2daa59a6734d26f14f0a55c98.nq.gz
    ├── 2490ed61cabb78fa83246ae73c729b5678830a6b.nq.gz
    ├── 24c3b950b13503c0b588fe75ddb47931c7108894.nq.gz
    ├── 2620327af8450110bf9d43ad449ecf3d9cd4ef51.nq.gz
    ├── 26c62f015eebede89c37cc45ae1968e8feff51bc.nq.gz
    ├── 26c822a9326b23def9bfd38fc9078ed0c2b1d3e6.nq.gz
    ├── 279f518210cd2f734e8f1aff56a0ec3cabbca473.nq.gz
    ├── 2804208aa09df58eb9a262b57f7750516bda1103.nq.gz
    ├── 286c61bd39b87ba6ffda0a8c8443f02da5931696.nq.gz
    ├── 287ffe5cef545d3564307725a2b7a2e84ba0f985.nq.gz
    ├── 289df734f49680c1569bc6b81cba1d2438ffc101.nq.gz
    ├── 28e20a86e0a2a6be6fbbca8f4ddf6e5be41ebead.nq.gz
    ├── 290ed3b1f50ead13284b1adcba314fc99c258458.nq.gz
    ├── 299bb9f606bfc8d2de5b0692e18f5ad44d8512bf.nq.gz
    ├── 2a00ddf37357ce1a1aa5f575412312f4a428126f.nq.gz
    ├── 2a0f55e61aa4634798038c7a8a462eeda46a8f42.nq.gz
    ├── 2a2142b322396b48dabde8c6650fedda562e2955.nq.gz
    ├── 2a6cb6dd87cf796523d3d9ef556546a1d7f733fb.nq.gz
    ├── 2bc4ad244cdb6095fc49c9f00c91e70abc98707d.nq.gz
    ├── 2eeb4da1640a0df90bd652e17af24284bdbbde35.nq.gz
    ├── 2eede5471d7ddea7b1e7e965447c4fc5b8ffa55b.nq.gz
    ├── 2f4f2d051095c42e1ad31447e1bd957ef623adc6.nq.gz
    ├── 2fa8d8231ad2a3ae37038bffd9694bf2e6ae7da5.nq.gz
    ├── 2fff5b13e1fc13d98eabfd52e6cce38b635a3d9e.nq.gz
    ├── 30336a84c4ecb4d788b1a1a2e78d10a63fde5807.nq.gz
    ├── 3073d996830b68b5b4ce6a675f1f82b471d009de.nq.gz
    ├── 3080595654cd683ce13a62aee55c8115d2f4830a.nq.gz
    ├── 31ab4d6a67d098df2ead27789d368cce891ac454.nq.gz
    ├── 31d75af750de1acc2b608e4fdb318f7c9aa0c126.nq.gz
    ├── 31ecb7089e19a16adb6881f9ba194e7545cd347d.nq.gz
    ├── 32f849a36f4378a814890ed866a80c7df1f1cf59.nq.gz
    ├── 34d7bdd8283771d106aa0af794cecf0bfc5b700d.nq.gz
    ├── 34daf877964d561ec49e2a8888a893de15a2e4bf.nq.gz
    ├── 34f16e52aacb3978c01c9873697c4e81fca1b9f2.nq.gz
    ├── 352601863daac54827be3404cffe1dd0b8ef0aad.nq.gz
    ├── 353b6d0192c33e84992208f732ee3a12ed73f1d4.nq.gz
    ├── 35619a839056b21ba3f26db73406396d3042a66b.nq.gz
    ├── 361751ec2dff30d0758c85e7ee4e005dad80cf6b.nq.gz
    ├── 3630170a9e980ba54106d77d1f6694ed5349ad26.nq.gz
    ├── 368e05608d931110beec81e28b752049ef6f5f07.nq.gz
    ├── 369c2495f45ec46ebea83e8b75e71bfc292e08d1.nq.gz
    ├── 36d05e43a210982bc59b455753444d4c8f4fcf58.nq.gz
    ├── 36dde8aa05a34a7778945b37d8a47e5b5c3ab439.nq.gz
    ├── 37dbc8eb545b559e925c4644ccb711a65b7b5bce.nq.gz
    ├── 37f6b4719e3b10d0e1f5b8866c39557fd0f85d91.nq.gz
    ├── 3884d4730286834bf0a9e20d11456696d0e86c42.nq.gz
    ├── 38a4e85999b4a1ef8ed871b92e4b6917ecb55f46.nq.gz
    ├── 38c1c3f5a2fd79f8b461a06718ac7438cb381e08.nq.gz
    ├── 39132b64bf3fbeef96d80f3e5f58d74cf6b297f0.nq.gz
    ├── 39bd916459b5eae85c05751fdb7854aae3e81ea3.nq.gz
    ├── 3acc90c6e47e6edc88bad920a063a3a979f0dcc1.nq.gz
    ├── 3b201255f9cd0e67026b80c1fa9012f7e6efeb4a.nq.gz
    ├── 3c8e4d1b5f8c74a70571c5d22cf7c84ccddfd1d4.nq.gz
    ├── 3ca3ec12ee4c1e807ed6f1cea93889ca05603790.nq.gz
    ├── 3cccb7fce83ce9f6b026f2226107bb3303783067.nq.gz
    ├── 3d494192e2c72294810309eb14e8d55e0431fd1c.nq.gz
    ├── 3fdd1324a33680fb06a539fbbb46fd6859fa9a28.nq.gz
    ├── 411ef77c82b36ec660728bd5dd992dc117799530.nq.gz
    ├── 42a3b8ad774aa0d9fd8494980108a76fb897091e.nq.gz
    ├── 43d0dc05376d0af7285f205459c38beb739bc802.nq.gz
    ├── 4484688b2c547f316bbd3c9772f63fae3bb78fbe.nq.gz
    ├── 44876ebcc1742bd50d8f7ccf3e4fc482b698b9f7.nq.gz
    ├── 4631d909d1a1f0f98fc13c0ce7e227b521e575d1.nq.gz
    ├── 47204cce2e2f9f9651f875a751a0a8c646ee02fd.nq.gz
    ├── 473503f74424cab5913a643cece01f974a007a5e.nq.gz
    ├── 4736e1df2f173deb7c2a96009a6418684fc65bf2.nq.gz
    ├── 48d7bd9a32804ed3fba02ecc93bd1d4acdece4af.nq.gz
    ├── 49089191f93340998653c4254c380eb7ad3d7efb.nq.gz
    ├── 495413f97bd8b32d28b58bb067173af0313e9497.nq.gz
    ├── 4a046ca453ab1099cd0bbb67dcff7825bef2661f.nq.gz
    ├── 4a67d3450a97fa16c010831697e03a36c6d56231.nq.gz
    ├── 4a9615582d823c984e8f721a5d189e679f60f8e0.nq.gz
    ├── 4ad8e5741688f265e4d2535dc2db084efb3421b3.nq.gz
    ├── 4b6a33f669f5c0409b772fdef96e7cbf3eb3899e.nq.gz
    ├── 4bc9abd30aa4bb605e24be90898f591da5054bb8.nq.gz
    ├── 4c6fa1dd34066e8c68756288838c1949b37d2857.nq.gz
    ├── 4cbd381b1557b525524c1f37352d01040b77608b.nq.gz
    ├── 4cc6b3348f53106e5e12f230869ed1ad5576bbc4.nq.gz
    ├── 4d0a0863ad6724fd6fdd10407169fe288a3cc95e.nq.gz
    ├── 4d35dbbb8aaa6a0ae6a944448f21e7cc262ec26d.nq.gz
    ├── 4dd2baa6119596ebeb6b3c8e7b06d0844e28227f.nq.gz
    ├── 4f17d807c15cc2fedec94219c64479f9e1499079.nq.gz
    ├── 5048081f7def540359cfd3b9756838db542002a4.nq.gz
    ├── 504b3d1ede3ee3c6b1f0b0dd8c211a1c7c4c5107.nq.gz
    ├── 5066842ef7d137786f43682c99c63e24eae261ec.nq.gz
    ├── 50b04de0b4a2fc1bfe14b5a7a3897668d7b837f7.nq.gz
    ├── 515c2ef8f91e45ec7a90a6871a634d53ed5dc1ce.nq.gz
    ├── 53941568aa79b3cc19abcdafae801eb612bc10ee.nq.gz
    ├── 540b8b1d00734d293cb09c09f70d4a655e648bc2.nq.gz
    ├── 5502ab8d5672d2c9f7179df7f76cc5e66b2f8853.nq.gz
    ├── 56467eb2847d1afa2b1d3c54ccef553296f715e6.nq.gz
    ├── 569438574ce2dc0fb523458311d8d3f332a7f7cc.nq.gz
    ├── 56e805df88d84975228c4d3d221818f940ff363f.nq.gz
    ├── 571ad4075c713a38afefc1c1c0dc0c29b780a0c1.nq.gz
    ├── 5739d77ae0fab7a1566958953623f62892c3f826.nq.gz
    ├── 575051526013da2b5c7dbacd46658d62bfb766a4.nq.gz
    ├── 5760bcbe4275f781b4131883cb9016c9795ec8cd.nq.gz
    ├── 59e07e643c47a657eaf0a1ad008bc48a1eebdf34.nq.gz
    ├── 59fedc8491c33473b46b26b14d19c34241042f17.nq.gz
    ├── 5b42d65eb45b42c97d98fa9689e55c6f0e8cd7da.nq.gz
    ├── 5bd1bba7e9dc7358b2c742723de264655c760cde.nq.gz
    ├── 5bed01a3ae5f29ee46b0c650c8f0b884749dee35.nq.gz
    ├── 5c9b737c679b755e31285595da65fe5dc09cb893.nq.gz
    ├── 5d39ae601ae7c29c8f69fa4709859e0a2006e54f.nq.gz
    ├── 5e4f489b4b6fce3c6ae939bfa1b562d5389cfe8c.nq.gz
    ├── 5e52ecf1ee44731a50a6b7effea6b0579f2e9819.nq.gz
    ├── 5fe393f2266966d612eff57e2eca252e214fc5b2.nq.gz
    ├── 60b69da84067a5279598445281ed17c14e2bfe3a.nq.gz
    ├── 61a690cc8ffcd0c62a9626ac13e680a06b48ebbb.nq.gz
    ├── 61c90c2bda0f6b2266cbfe81a2a32ed6e864b5a5.nq.gz
    ├── 62927acba4792e2cd16160e6aa07fa57cf4827b2.nq.gz
    ├── 6345726b652257a515d256896df4f1e81f024245.nq.gz
    ├── 63cae77e72549b60bfae0d8155bacaa29269453d.nq.gz
    ├── 63e53621418a35481195c602b474ed606e32d3ba.nq.gz
    ├── 640d2828f0d70d831c46ba440d1600071c17c767.nq.gz
    ├── 6424ad83ee90524ea434066215db9b42d5c909b1.nq.gz
    ├── 647540baa7c9fa1e37f29d7c7de1b68819fb79ad.nq.gz
    ├── 64aa0c3696cc1c6d86d218c70635d88f2035ec9e.nq.gz
    ├── 64f28503de410538dacbd1a6e34ade8bbf373cf9.nq.gz
    ├── 6617f46d59a6d4dfc5818e190f372af70b38d091.nq.gz
    ├── 663ea5799c50c08866cd040b237963d7fd6c1bd4.nq.gz
    ├── 66b47088e3a71805a96e601c18af42b6d939779a.nq.gz
    ├── 66e86f567f56b2e06bc993615a01a8c6e7d98b68.nq.gz
    ├── 678815a076186d911d617e53d96a8f3ac0742ef2.nq.gz
    ├── 68e6cc9319b4b09be8b3dc838c7754b14fe4a874.nq.gz
    ├── 68ec4a93131fe264cfe12a5af43459871910185b.nq.gz
    ├── 68fcfe7b04176087a2f5fd8a7268c0762b7888b2.nq.gz
    ├── 693be6addf6ccb98a86f5524b43bf493552311ce.nq.gz
    ├── 69f1eb303bc8aef02e530779568f3e5626e54938.nq.gz
    ├── 6aa0e9c9a46817f244ea68861d320cdcbba7a82a.nq.gz
    ├── 6b4317a90ffaa39608ae29a290cdee3b8d1f8ac6.nq.gz
    ├── 6ba5668ab45a8ef4c3778987aa7bb1ac0883716f.nq.gz
    ├── 6c07e59cc81add5fdc9fb5d8b634eef0863f04ea.nq.gz
    ├── 6c15cd596df81c6fdec4f6566c6e7c3506e29349.nq.gz
    └── 6c8ea4fe4bcc5984e34737772a8279859f0e50e6.nq.gz

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

[scrapy/scrapy](https://github.com/scrapy/scrapy)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
