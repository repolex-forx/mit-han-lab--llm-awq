# Repolex Knowledge Graph of mit-han-lab/llm-awq

RDF knowledge graph data for [mit-han-lab/llm-awq](https://github.com/mit-han-lab/llm-awq), parsed by [repolex](https://repolex.ai).

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
rlex download mit-han-lab/llm-awq
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d6e797a42b9ef7778de8ee2352116e0f48a78d61
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d6e797a42b9ef7778de8ee2352116e0f48a78d61
│           └── chunk-001.nq.gz
├── blob
│   ├── 0306a91da52e8d8846ac9c1e3bf9ac2edc370d04.nq.gz
│   ├── 04e205b238c56142a5568294978338c592a2005d.nq.gz
│   ├── 0714bae50bfa37c8873df2a8ae9ae6a038bd4d04.nq.gz
│   ├── 0917e6a2055a2b410564d9208ae44af05a9b2275.nq.gz
│   ├── 134fc1c02a12ad5b34c3ab3e2e3ea528ccd5b1ae.nq.gz
│   ├── 152adc2f616a29553b6cb7da7a9f6b95eff701ba.nq.gz
│   ├── 155609310c8035a8fd06efa61d2cecb5d3f5eb15.nq.gz
│   ├── 1588155c2661451ad2b65c4e5bc348ed5c3d8463.nq.gz
│   ├── 17ddad2a142490a81b6d44ebedd7629678d321c1.nq.gz
│   ├── 181637cfc8716a9293ebea721593d4f121d2dfe7.nq.gz
│   ├── 18a79eab327acdd98bf19d0b254c036381f5fc97.nq.gz
│   ├── 1b98c1d8d3076799f3f50ff8f527761b9cc5fc48.nq.gz
│   ├── 1c6f48b7a62ee2498e3838088b5cf4e4c1db0858.nq.gz
│   ├── 1cd01022d36e9ad39a6861f34d494e7fe4787d27.nq.gz
│   ├── 1d3a047ae5a53b4b4009d4fbf7837506608b19e6.nq.gz
│   ├── 205dbe68ac86538ddcced2405fdfe5455b7fa787.nq.gz
│   ├── 208df0707b907e082baa650a1279d82452bab354.nq.gz
│   ├── 231220b203c81cd5a008b37d9e85d3eb4322e63d.nq.gz
│   ├── 235293e43990a87bb4b1e6abb38cbc148c077478.nq.gz
│   ├── 23a5ecbe11befb977a79535701802703be31042e.nq.gz
│   ├── 2553283a83fbf4602396f1575b2e0fcabe518c7f.nq.gz
│   ├── 2ac65909bd5b6724fb5143544b386ac6a3f637dc.nq.gz
│   ├── 2ba12a2ca4d5dc0718cf424548d7a6851547ec53.nq.gz
│   ├── 2d8fff5ef785f1697dde3744c276d90bae14e5cb.nq.gz
│   ├── 2e01d2a4461434ad5c414a1e01e2066b7fbc9d3a.nq.gz
│   ├── 2fbba7a73c686782e915097791a0ec46d576e66f.nq.gz
│   ├── 30424ee05147bcb5d66f2df2a7819470934b7051.nq.gz
│   ├── 3178b30d20df281590b88a8d07ce5c7f59d25790.nq.gz
│   ├── 3302ae3f0bdb77546cb454ad1703f06461a1e365.nq.gz
│   ├── 34e0d67f30888765bdd62a91f66dbc8029cd07dc.nq.gz
│   ├── 37d25bad49963ea1797cdd2b58202aefe1bcec13.nq.gz
│   ├── 3a55e662e82d77d5c9322fef32df0f24bc2bb911.nq.gz
│   ├── 3c150b59e59927ad4632947307459acdd76a9437.nq.gz
│   ├── 3cec08cdada964a193399d0a00f82cf51ebbb613.nq.gz
│   ├── 3d4bd8bead10028bffd0116da411bf7965e28823.nq.gz
│   ├── 40b69ce064859f31a744658c2fd1a472b1623f93.nq.gz
│   ├── 43d02507448645e6441c7b131b69399dcad6ad3b.nq.gz
│   ├── 4614baa4df75f896f1a9b8f6234ff17fe263c858.nq.gz
│   ├── 4c0846c84866b23a44dc9a640358bf54b160bec9.nq.gz
│   ├── 4ebf6c644eb66d2cdf36d051450a5d94a03c0397.nq.gz
│   ├── 50adf198a5ec921e4fd4bf614d9e18266645bb9d.nq.gz
│   ├── 510d4e1e471fe67df5dd37656f23163a70fc2bf6.nq.gz
│   ├── 52cb95dfaf8a37510492af0555a507b374536664.nq.gz
│   ├── 53037116aae1d7858c63870125a146b4c2f7df87.nq.gz
│   ├── 54ea8e7fd01055b142376e1f26b1f2006e96040f.nq.gz
│   ├── 55a1949be58eaadd7aeedc66cf42624eed419a66.nq.gz
│   ├── 566f1db7c2c589a376d054f28daa5e91b6c494a1.nq.gz
│   ├── 58f8bbc7c7150b37522d3d3e872d5061161c84ca.nq.gz
│   ├── 596f69e8b9b1f65200e75ac086cedbec8615e5c0.nq.gz
│   ├── 59d8cf23f63ffa4b63910765f248b3b601c1ef00.nq.gz
│   ├── 5a771766f21ce3aeeb99b286fb8d188b0038a547.nq.gz
│   ├── 5c54fd5dafd854d04436048a4a4c27af0b276932.nq.gz
│   ├── 5c5a7e175750c384d9b3aad661a5f03cd624bcb2.nq.gz
│   ├── 5d333b35c148d0cd01c8cb6fffd5deb28db28d33.nq.gz
│   ├── 5dce6c1c55d7ba33c94094a97a6dc09ee6aeee59.nq.gz
│   ├── 5eadd5076ac2616741065c13951232d0bd29ea3c.nq.gz
│   ├── 6355fb99ec4d6fbd956df23c008e4236060512b8.nq.gz
│   ├── 6417a78a68f4d3e0b5cc6728592630d0f8a50c01.nq.gz
│   ├── 64f8335cb1b8990830c4583c237226e8e366f404.nq.gz
│   ├── 678160e8fdf5788757a82060bab1ca6b6f6d3baf.nq.gz
│   ├── 6a3609075f5eaf871f7ae9b55bf87b5ba8120c02.nq.gz
│   ├── 6a6c094c3b6651e40ea0cd4965091e253f956aab.nq.gz
│   ├── 6c19b38b9cebf7a44634e31442ba93639cfbd72b.nq.gz
│   ├── 6c5375f2553894095b40a2292a0f1f63657333b3.nq.gz
│   ├── 6e94d03de94ac204a3ef2781eb35a642b3f6e8cc.nq.gz
│   ├── 6f2905b776ca8fbfb8b5fb7ad2173f3427f8c12f.nq.gz
│   ├── 6f999d186e1f2ed76f8c31878b8591b7b94d12ab.nq.gz
│   ├── 6f9f723a4d1025ecde8c3a3e2be2199499d7319a.nq.gz
│   ├── 708e62edd897c7f8264c8fdc0abe883528aea4a9.nq.gz
│   ├── 73ae44cb7cc6a596910c33f8d3005bc11f1dd9b6.nq.gz
│   ├── 748abc5d1bcef5cca0c056c6e1e2279c3bb262a9.nq.gz
│   ├── 769dc6962dd8aa3d48ea19dff4a1a5f5561e6eb0.nq.gz
│   ├── 76c8d77fbfd487d670447bb4479f3fd40d155b2e.nq.gz
│   ├── 79a09b85083830a1dfed9c9b6196330428049f60.nq.gz
│   ├── 79e3febcc2bf30743d90155e1dad151abf598350.nq.gz
│   ├── 7a170943c8fdf5f5cfb208aca1da1668d453a1e2.nq.gz
│   ├── 7bbc462f8b3841424eead65166397243a6d7aa6e.nq.gz
│   ├── 7c0c49d392a9806f1da29f0df61d362ed7170f59.nq.gz
│   ├── 7d15191651545f504ace5e0f284525421e423bf1.nq.gz
│   ├── 7f6b7d81f69204c0f16cd5c2647196486c66ae08.nq.gz
│   ├── 8115702971b44876dcf237b92b6a34d8cd93a5f4.nq.gz
│   ├── 8263c7086336240f091c84181e713f83bf2e32d6.nq.gz
│   ├── 883b59c41b74cf1947c1b1e1bacde716f0f21857.nq.gz
│   ├── 8ada509238306072dd9dcd8f16c21737c6407704.nq.gz
│   ├── 8e16469b28dc1cfd0fda50ea710d82663b9d1b34.nq.gz
│   ├── 8e24164b893eb2d76eb76a3a4cd2aa736f143e37.nq.gz
│   ├── 8ea03b922349bd32ccf9147773342a6d05c2022c.nq.gz
│   ├── 8f2de9a199f5f7f2bcbeac050da7dfce01192eba.nq.gz
│   ├── 90a0f3db9541aa1805747cc0ad52f6bb0ceddfca.nq.gz
│   ├── 90c90ec40afe35cc346d74789aae1aada2d83366.nq.gz
│   ├── 91021aaab1324653c014a4fb6b23f6a520a10f6b.nq.gz
│   ├── 920af9a18355b6263722b95bfd9d75677fc9a2a4.nq.gz
│   ├── 9223dbd8157a98a4902866046c218a9ac18851d6.nq.gz
│   ├── 922e457242270a891e9fdbb3aa7d3dbaadf936b5.nq.gz
│   ├── 9302b6646b5157a4ed09bb6f5a9b258e09f0f763.nq.gz
│   ├── 94d1f3c1ee0edc3bb334f1fa92b18c54caadfb6c.nq.gz
│   ├── 96514ef12ee275ec8fca5ff5828a3707c9debb3a.nq.gz
│   ├── 96a72d7683d4d47f05d848e29ac803176ec5c2b6.nq.gz
│   ├── 980e6f4cfc9f6732babbad637af6d8b2e40eb042.nq.gz
│   ├── 98c92c2cfbaf8929321b921789cf48405d10f7a0.nq.gz
│   ├── 9917ec94911ca106844858ea855f4fc15902a2a7.nq.gz
│   ├── 9aed0f657eae43e8b33c545f628b5d0da47cb02f.nq.gz
│   ├── 9e45ac8bdccdc2b186a353d257a8d2bc04728c86.nq.gz
│   ├── 9e5d740520cf3b1f1b910e61e59ffe0dc570d810.nq.gz
│   ├── 9ee886c7daf887db80ae96746d743d4fd77f1663.nq.gz
│   ├── 9fd8e1e9203be1e18e233b2a17de5d2b185f9162.nq.gz
│   ├── a2abacbc75c581ebd11c041b94ab258d7b1b3114.nq.gz
│   ├── a34505d509667035a8a6ac78e88ade079b90ad89.nq.gz
│   ├── a44e1a5bb2d88352e6da5de690e8a2964ffbb9ac.nq.gz
│   ├── a5db72d730aa30075c2548a4cf4b5ac50b7f9b22.nq.gz
│   ├── aca305b14a992a4800fa8312c32edf071973de50.nq.gz
│   ├── aca327a505563c97f6ce15cbb88098e8e72f3965.nq.gz
│   ├── acc636f745c53fec08521c7ec863b5d1baf675f4.nq.gz
│   ├── b176cd0723b6587bf497e492de05a8ee58b4aed5.nq.gz
│   ├── b1ee1274d56acfe09da30939d021f5e19e21075d.nq.gz
│   ├── b263625be197a62c120a0795a3ed400e04270739.nq.gz
│   ├── b4aea70b51a8829a5d84a67a5349c0a508226cd7.nq.gz
│   ├── b50b9468c167e149b0094228610299f51b5f9139.nq.gz
│   ├── b70d4e78453b5f626a80aef748adb41e53942de3.nq.gz
│   ├── b733a1d5974ef2b3c2f3650f32d4d5dd95d32e1e.nq.gz
│   ├── b81ebff6da00a691de7e001d03562a9477d6f8a6.nq.gz
│   ├── b8259b93ffad3cc6168163fd707a4b798a1cc867.nq.gz
│   ├── bd581695cb7fd2f838c4b55645bc10362fb602f6.nq.gz
│   ├── bd5e6c1d238c0d01e572e1e0e82bebe905a6acf8.nq.gz
│   ├── bda32e53edc03c0c697dbffa88e25c40f9d27feb.nq.gz
│   ├── be21030707b268daa9a30e8e490ee924ac09a9b9.nq.gz
│   ├── c336d8017e026f66d77af8e40f2bb0494ea61214.nq.gz
│   ├── c4bb3f1856b1aca3274fb6e3fe8474aa38ad6cf6.nq.gz
│   ├── c4e93f261bcfb77d3aaa640c253e75c6f5c59d53.nq.gz
│   ├── c641c81f5e9f1a86f7a0a25ea657bed5e7790688.nq.gz
│   ├── c8259d04d1d9f292ed95ec1083e720cf3865e8d5.nq.gz
│   ├── c8afed1c4038f81f83466ba3af4108638c89df50.nq.gz
│   ├── cb7773838cad0c767e6bb4aca1668ee2cf7e2154.nq.gz
│   ├── cca412a3645b21e3c3e136f320884ddf67447a18.nq.gz
│   ├── cd4d45df253273bb1de6e2652836d86ecee4054b.nq.gz
│   ├── ce044f00d8a68f931746c75a746885f5b9ff58fe.nq.gz
│   ├── d0fe354b0a0583647ba1bfca82fa8648e1990767.nq.gz
│   ├── d4c17a913b77464b2642822f021fdeebc153e226.nq.gz
│   ├── d4d297da5a919d1cc7871a57b49924fdc36b39b9.nq.gz
│   ├── d5a7b158587a51e768163c5868e95f02dd8413d9.nq.gz
│   ├── d5c92eb7f56b61b6ad3faef6bb43a3bdbff8bb75.nq.gz
│   ├── d67bc41e09bc7ca43c145fb83680268eecada90b.nq.gz
│   ├── d747260f413badefb32d6111f102ecab553c8ba8.nq.gz
│   ├── d7793d8b3281146fe79b97a5546891159bf934d0.nq.gz
│   ├── d7b477c3b07bf66cfbe63752bb09f18374ac830e.nq.gz
│   ├── d83008b3f03a8fbcbe543387bb35385596cccefa.nq.gz
│   ├── da610a163e53c42345b2fc323c1b5ea4151d9cb2.nq.gz
│   ├── ddb1d22da5b9585a0d0b8f34011689f0ceb5a5b8.nq.gz
│   ├── de0933bc9a1865e6d7bb682e33855731d83e0770.nq.gz
│   ├── de0b6d80317f05eb76e466adc8aad667b3e33936.nq.gz
│   ├── de43ccac688d65b540b8fc9838e9e3c44b1758a1.nq.gz
│   ├── debbe2ebf44eb5bdc758e80e26278ceb553e9d83.nq.gz
│   ├── dfa4e70a2492e8fd44d727b8bbdb7894aa3541e7.nq.gz
│   ├── dff0a71f9ca3c733b1543dffbed12089b078d50f.nq.gz
│   ├── dff3fc11656ed752a91579bd6addf488d4bd3a85.nq.gz
│   ├── e1aeb4d23b733c1968f363577762a2fa6643ffa9.nq.gz
│   ├── e397f10c09be377d9b02d1cf115d60f18ebe5987.nq.gz
│   ├── e5a6690086489a46c39452d7c9d3d14c7edf2ddf.nq.gz
│   ├── e665d42442fddfc8e82d4383f4e9fee21347fe89.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7a4593f3294173ad4ed51c88b4cfae900772da0.nq.gz
│   ├── e8e1f0d49709f510957d91f58abf829ffeaf6efd.nq.gz
│   ├── ea46addb2e576f98ff7ac8ee3311f910b7e3623a.nq.gz
│   ├── ec0aae55e81684ebce5f0d5fd13680470ced7845.nq.gz
│   ├── ecd1460bb703b2cc17a5653786ccbe42abe557c6.nq.gz
│   ├── ed3fe7eb8df264f7cf42f4edcc20f4b8c678b98d.nq.gz
│   ├── eee15c88ffbc6b58c8297186d49f59a45f8b2593.nq.gz
│   ├── efb6e798730879bc2cd16088b2091991862a6074.nq.gz
│   ├── efdfc5ca931e3df823940f73cb697e5a8e265206.nq.gz
│   ├── f0ce7f92aa0af0f04b1ec6e504a7ae73b38b129c.nq.gz
│   ├── f4393f81edf2c0dbccb055c570c713ce3ebb3502.nq.gz
│   ├── f5641f61609172090da1c8e77e43f9f4694ccca0.nq.gz
│   ├── f6537f8a375300e8e8f9570c9b42ad5303783eab.nq.gz
│   ├── f68d48574900cd67487174784bd1bc26b037ac8b.nq.gz
│   ├── f69b57cac336ed15a7c6751a9d6d35ce123c0da1.nq.gz
│   ├── f6bc3c660751d58aedc832cc9905028a5d596d4d.nq.gz
│   ├── f7de6e4a5b319521bb1123bf028298723542db21.nq.gz
│   ├── fc039ec22a24e7586d9ae01e40fd8bfb08a95170.nq.gz
│   ├── fc4c2513717be2c25b103a248e00dcce64862c59.nq.gz
│   └── fe604908ad9aa6a97b597d6dfa43c7b427913b17.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d6e797a42b9ef7778de8ee2352116e0f48a78d61.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 188 files
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

[mit-han-lab/llm-awq](https://github.com/mit-han-lab/llm-awq)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
