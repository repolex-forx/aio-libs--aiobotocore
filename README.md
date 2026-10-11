# Repolex Knowledge Graph of aio-libs/aiobotocore

RDF knowledge graph data for [aio-libs/aiobotocore](https://github.com/aio-libs/aiobotocore), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiobotocore
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c58f9b5221f49f218c7be3493cf91305efaafcac
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c58f9b5221f49f218c7be3493cf91305efaafcac
│           └── chunk-001.nq.gz
└── blob
    ├── 00ca2d1a8cf2a1591cee62a8389d43a48cddf36d.nq.gz
    ├── 042ff1036eb0b92775b52b43a306595d51997d77.nq.gz
    ├── 047ef2aef583a694cdb91dc5b7f837ddc84ff209.nq.gz
    ├── 049dc8456eff689fcd81495717cbb54b178ea935.nq.gz
    ├── 051b086eb172c1adb5f44be0f0940f1730e937c2.nq.gz
    ├── 05ac625286aa2cd39571b4401157c039954abc94.nq.gz
    ├── 06674e6cb414883ad5b20ad5e41079f7a79b21d7.nq.gz
    ├── 072e2e2b69c2ae5877b96983a12ed82066aaad43.nq.gz
    ├── 07fe423a36f001ec82d2ee22a8340aa48f496ed1.nq.gz
    ├── 086ea6cb6fda80a145b5ea090cc9dd10ddbcea71.nq.gz
    ├── 0871f289b60f1972ea565594412fd5203dcb1030.nq.gz
    ├── 08b2dffbe49d6b72d397b1466f7a2419f621abe1.nq.gz
    ├── 0a52651d0815143a558cea7d98f1b63d5fc1a15a.nq.gz
    ├── 0c40a19720723aaecd46ccbff76cc21a33bc122a.nq.gz
    ├── 0cccf6b4b5108bf4f533ad632eb77109f2b7beca.nq.gz
    ├── 0d2874a1bb2b7070b049c533787f58dd0f73dd4e.nq.gz
    ├── 0de16060fd9e79f253a0288e3b53de19c16bb567.nq.gz
    ├── 0ff3030a0b0a8097d748e4c26b9fd530ada5c2ac.nq.gz
    ├── 11fec3851997bb8c4ff6dc0e970d0e43bc7b429c.nq.gz
    ├── 12d96adc015e4113086a0368a30a6da2fe654b07.nq.gz
    ├── 138110810fe43cf613cff9d20bac9b7d2d7dad78.nq.gz
    ├── 13a72fb859b41da027c76f6d3c85d1841878c698.nq.gz
    ├── 13dd7cfa560de3349cbf9be2b06203e9ebde30f7.nq.gz
    ├── 158b3747f402cfe56f76cf111b914f730016cbc0.nq.gz
    ├── 1670b4e4152bf20b7a54664c7214e85db880f61f.nq.gz
    ├── 1a572b9d0e4514637530bd6bb1ab5c78615a021d.nq.gz
    ├── 1b7f38836af0c32cbd9644279c1df5d7a98f0389.nq.gz
    ├── 1c0b0df6dbe4452dab9f08403a7e1b1205ebd192.nq.gz
    ├── 1d8ba921e77f18bbfa0afeb398b6c127aaa0dd7c.nq.gz
    ├── 1d8debb68b4ce22fe19ba6f6375b554b1f9cb18f.nq.gz
    ├── 1e2988eece0baf9036305fcff1e2df2272dd41e4.nq.gz
    ├── 1f9b5dd5f4517f84961254d6be17efe87e1db73d.nq.gz
    ├── 213b40e7ccc334827581420b7df25a4d91f9a105.nq.gz
    ├── 21b56f44c9e5399e3f753a02b9172b268cf8fa14.nq.gz
    ├── 229978e168c020042a1efb8b75ae1eeeead9fc27.nq.gz
    ├── 251bd6a6987b7fc76d388ccb206c2bfde38c7ab2.nq.gz
    ├── 2894e8631e6793b08eb0ebf419376867028af791.nq.gz
    ├── 2c152a12f278936dab60758f60d14133f4149fd5.nq.gz
    ├── 2d7756bea27413b680f2c730b3cbbf3bf9c71988.nq.gz
    ├── 2eb0e99f76dabb7b8920481b2d12941ffaedd655.nq.gz
    ├── 30e877a5250281e6e9e2359e5afec1206ef879a8.nq.gz
    ├── 323db8fd95489870f7f7371c68ba6ef41d8a3afb.nq.gz
    ├── 32791f762c7ce25c964ac7142318cc473c80d966.nq.gz
    ├── 333a4d65272e04f7749f8ab0806d729ac434273d.nq.gz
    ├── 370677860764c3a710923c59d27b71e7238dde00.nq.gz
    ├── 3bf9c3b99649dffe239e5d1a40f20659ccef0852.nq.gz
    ├── 3df376172cbd196897239e8f2358832deb806a0e.nq.gz
    ├── 3e3c2c99a0bb66a204ba09bf3b0d6ac97d9b2828.nq.gz
    ├── 3e93f89a9ce7c60d7fa6ca0b3722fa542cf96c00.nq.gz
    ├── 40c150df5d0bdcee6f04665faa7d73639c8e54ff.nq.gz
    ├── 40f0b95d4ffaaa467c99e8259878b61d1100f386.nq.gz
    ├── 41983e211c068d9989e62b2c5612020f0ec6df30.nq.gz
    ├── 4260b048e906835842c50e20a9b2ba3d315f5391.nq.gz
    ├── 441d2343913cbaada67e2c33db9ccd7d46898f98.nq.gz
    ├── 4460adecc78357f37ecdd9479f48f33c04454c01.nq.gz
    ├── 4462371319cd6b993624cd12426ca02d99e748ed.nq.gz
    ├── 471c13850f06a2c72ff2b1b7d28e34ee11d8c614.nq.gz
    ├── 477d464bc9c25c897a6f9b56ed2c2c1dc3ae00e9.nq.gz
    ├── 485b8acdb19a6b29cc1317a19e525b7cac8217de.nq.gz
    ├── 488a50878a5a7c8af1c0fe256c6e9b6fda06eb71.nq.gz
    ├── 4aa436c862927ced751f71918809bf22bdb484fa.nq.gz
    ├── 4afa81d1d468198f8d9ffaffa904936431336bef.nq.gz
    ├── 4ea5cddb649fafc06c07a59667e4d2662dd61d04.nq.gz
    ├── 4ee4689a283df8e720fcca9144cda8db5a50ab6d.nq.gz
    ├── 4ef24204f39300bd8c70003b461ad1ea3a7e0d8a.nq.gz
    ├── 4f5e998ae1b7a58d1e9a478a091655b394c46874.nq.gz
    ├── 5115eed338d0f65ca56813a438bc1b07e363111c.nq.gz
    ├── 53329a8b2dbd5e08449f0d1a919b6bb66947cc4e.nq.gz
    ├── 53f226f53e992bd067afe772cf9862d0113288c0.nq.gz
    ├── 554e0f9f78a085a0d3d011e8f84f088b1c70978d.nq.gz
    ├── 563cfe1df59b629feb86237782d8eebf0f53e04a.nq.gz
    ├── 57e7d57f19a8b7baefabc67b09383c104a2dee1b.nq.gz
    ├── 5858fcbba948dd13a26ac6d057adced6bd64e6e9.nq.gz
    ├── 58961846ff9babbeced34915cda58824580e7007.nq.gz
    ├── 5932d4c3a4c416c60b84acebf78a3749bea3b79c.nq.gz
    ├── 5d634824e5ca67207f837d0ab50e8c6cf5b7fbaf.nq.gz
    ├── 60a1ac3b894cc7519d9d1844febd3c6e60e85d74.nq.gz
    ├── 61ab536f7c51d972a5a9d1c7ae67bb6726ec31dc.nq.gz
    ├── 62913e9c578ea0daa8d99f60904cba7167427cf8.nq.gz
    ├── 637a722a61f93ce4f4e2f645a1bb76f6a025dd33.nq.gz
    ├── 6382dbb256eaa2da26eb5bfbe15dcf6a99f311f2.nq.gz
    ├── 649a384bf15796d9a84a69c04600a3b05c0bf7e6.nq.gz
    ├── 651cd37d2ebc8adaa6db4dd929848727000addfa.nq.gz
    ├── 67660cee5bf77d564dfef7515f8077fa881e2f31.nq.gz
    ├── 67ecbe0b68f507412fc60167cee8b32854148984.nq.gz
    ├── 686ee59ebd0e7797083b83cb33485aee20e83740.nq.gz
    ├── 6d109d8f6daba1c71dcce31d49dae2b07903f917.nq.gz
    ├── 6d62abdef0d0eee12c2d757ed5a140650f995b01.nq.gz
    ├── 71bf87a9bdc506f207b773682e2c39fcfcf94c4e.nq.gz
    ├── 73e6a0668875bc4d65ddfee722096d4d149f2a91.nq.gz
    ├── 7641d80eefcff3885a092093387e98127f91a3e6.nq.gz
    ├── 767451fecc5006953645725be6a9e0a812896305.nq.gz
    ├── 781a0e381279c7773ceb0249077fd7723030ca7c.nq.gz
    ├── 79acb072d97ad82c514d827dffe28e463441f694.nq.gz
    ├── 7bdc23e3044416c9e8209d041d6f65dc8d918d4f.nq.gz
    ├── 7c0230f2a38def445fd8c178a0813094fcb42f3d.nq.gz
    ├── 7c743196ece7b663b4bcd19c7ea794ea11646710.nq.gz
    ├── 7c77de01ed23c7a7ad34c244049aa04e3a0961d5.nq.gz
    ├── 7ef26dbd58a1f35131f1820d416dd235f646efb9.nq.gz
    ├── 7efe941f5d2603bd694b953989f0c2b5fcef4f56.nq.gz
    ├── 816401bc5967f01394f120985a11d0975a97bd57.nq.gz
    ├── 8195a44957c600452c1f959b2dcc7d375244916f.nq.gz
    ├── 8211e9b8fc8e58e8495b153649738eb7f6a02e04.nq.gz
    ├── 853d15ca6960c903a89f24a607751f3dbf2ddca5.nq.gz
    ├── 8c0da1fde7f160cb23c9cee7f3b243489fbddd94.nq.gz
    ├── 8da46809609e7b0963769657dd6912f17ccbd9d7.nq.gz
    ├── 8f6ad8dbc49883eafa6264ec1d1d5512b50ea845.nq.gz
    ├── 91087ebf64f65760f4deafa24c036dd3f565665b.nq.gz
    ├── 919009827e990f2e0d64159b22ffdc73917bb417.nq.gz
    ├── 920a8bebaef76164fc693f9bed27d62d4b3d3e48.nq.gz
    ├── 93b0432bd3a59080e0cfab68f40c314e30193a61.nq.gz
    ├── 958ba22c91738a43a49017f77a2ae101c5dc32b3.nq.gz
    ├── 9710bc28654751e639edd5c5166a4061f9bc67b7.nq.gz
    ├── 98e47a4d5cccf0340244a617f687014eea80c0c6.nq.gz
    ├── 99eb3d636291ee9ea75493fe28a5fe06d5efce29.nq.gz
    ├── 9bdf9de5f22620f77b6063bae3fe391e81143898.nq.gz
    ├── a0467587b2490ec8a95f642709b26c2768cc3712.nq.gz
    ├── a0a280f4d85e90ccdaf039a25b174779be67966a.nq.gz
    ├── a2bbe1ce5947a629d2f1dffba3a2ea1f09b6ae9b.nq.gz
    ├── a2ebb6e82169300ff0e5be7ed709216613de3d18.nq.gz
    ├── a3b18d0dc400dc75b0ac404059353d6856adece3.nq.gz
    ├── a4ac311df3fc280de0afab313ddc5f294cc607da.nq.gz
    ├── a595a2375f8de6e3f29d048ba8adc54909d9979b.nq.gz
    ├── a62e78dd81c3a5d78aec9a199fba101edbf5b448.nq.gz
    ├── a6413dc3b33b72cdf883c044ce6b2ba648592b74.nq.gz
    ├── a758fbfef86399480b3ed732e386275410065f46.nq.gz
    ├── a7b1bbcf7b913f3b73ce38e350ec0c120566693c.nq.gz
    ├── a881f1bef905c4b2190b1a0e7fc127eaeff17084.nq.gz
    ├── a990c8cdfce60213683adb575b05c4e922b22e90.nq.gz
    ├── a9a69816dca6faf7949459250a1973756fd646d5.nq.gz
    ├── a9aeb4960c7e623b6c6b03ad659686a989b5dae2.nq.gz
    ├── a9c7207491faf0e84a64d08dfd4d0b54a9c5b8d1.nq.gz
    ├── a9d00f9805d41b6fb39921fc9aed78257f3092c3.nq.gz
    ├── ad998f2437b01c2d2b9db4809b0961dfe90bbbb7.nq.gz
    ├── ae83553a0ea3e9a3f8931fcccfbd9fabb3209943.nq.gz
    ├── aef2000762372cc93db2e7df702051acb4530ce3.nq.gz
    ├── aeffc158adfd4010e5aae24877bd4ab6afd6d9c4.nq.gz
    ├── b01067507f8fdb77185d35110a2b0d9931a3fb34.nq.gz
    ├── b1fb14c8bce767b8ac54a3f9bf54fc50168cb4eb.nq.gz
    ├── b3a30752c69a8dead5abfd52b117cc0ef52f4c37.nq.gz
    ├── b505c04de55e6fda6d40df6731fc884662eaa6b2.nq.gz
    ├── b5109339fcc29022b0147bf13c848f1f6e5aaa05.nq.gz
    ├── b58ba9633058d82aed99216cab9b471229672e88.nq.gz
    ├── b7fa15b3ed252cf466c4048cfdefc3e368ccdbed.nq.gz
    ├── b8d3db657bc9ac836c069a75e1cce79d72acbb5d.nq.gz
    ├── b90b886a9187bb7b26722f25422897f06d10e25e.nq.gz
    ├── bad2dea0844361d4e2cbea627686401e35bc79e9.nq.gz
    ├── bbb4b0c0d2b5d896834d8a3488ac3cb0997bd04b.nq.gz
    ├── bc6eb5641dc95b2787a2abbacc5c247a379bf91f.nq.gz
    ├── befc92e1f05219a6b9a8fa54673a38e5205aeb70.nq.gz
    ├── bf69fd944d4cca7dbfcee49141efb17304e71191.nq.gz
    ├── bfb3813989f2bb5174570d0741e21dc47604dd27.nq.gz
    ├── c048fedfe8a596ccabb7bd3fad2aa9615952ff91.nq.gz
    ├── c29d950b15b5daeee519e15d3bf2124536f18172.nq.gz
    ├── c3a68c40d5f5099e0e0a77c59790687035ba021f.nq.gz
    ├── c463aac2bc90e82fac6437037c7b07cacf17b378.nq.gz
    ├── c4dee4837c1bcfaf3af7a784c334c21bd9a6a4d7.nq.gz
    ├── c519e65b758c449a89f0ee3bf58aab21f2ed208b.nq.gz
    ├── c568e167cd8cbc11e61f02d7c799082186bdb046.nq.gz
    ├── c6bd958b92171fd217910cffa531970d74b6b3d2.nq.gz
    ├── c7c28210c006de417a51765ac448c81a1f354c46.nq.gz
    ├── c87d9932a1184210cec5ac1ea4a2796763076847.nq.gz
    ├── c918f361ee8fec9cfb5c72fe87716530cd6e1f4d.nq.gz
    ├── c9ede3e0715bd399a70703d1d1240071914c3a6d.nq.gz
    ├── cb2d5f0252b32e3eb5c5ef850fe49b2698980685.nq.gz
    ├── cbdda45fa93f3eb4bff54c20bcb631f5057d5575.nq.gz
    ├── cc86d1c618bed20203699011163e7b3def3f16a1.nq.gz
    ├── cc887ab88aefaf6f33dedea76fc95b26e2ce7763.nq.gz
    ├── d3789b46ad12b787561f0a25d7fffacda2ef139c.nq.gz
    ├── d3910f0fabfb5e257dc84a808783204c5877592d.nq.gz
    ├── d428b56d68590a4ef913c37c7eee41703e4cebc0.nq.gz
    ├── d8124cba81ec7aecfc186c3ab0d9c9d80706d09e.nq.gz
    ├── d90c0f60f76d6d824877895b6776da4204e84e61.nq.gz
    ├── da39b57ecbaff314cf6df380647e9fc328117f6d.nq.gz
    ├── dadf08dfe23ddbc6509a68e36c87e5697228b99e.nq.gz
    ├── dbe3fbed79d77ce609b4cd5ebcabf9a61a90f5b6.nq.gz
    ├── dcd0e2de3928e05882aea772147b2a2c85fc52fa.nq.gz
    ├── dce5f3a267b0bfe1968d822b27b487967dc94409.nq.gz
    ├── dcea83281bd1c091fb4263b80d5a4d69dac968cc.nq.gz
    ├── dde68924d1a703d39008908b9a42ada518a68ec8.nq.gz
    ├── e017c9cf73bbebab2daf2341615253d8c3e6d41f.nq.gz
    ├── e02e16c63f08b46a4d05185c743330a236cca2c9.nq.gz
    ├── e2049c8a04d7849f2426703fd204c0086a07aae4.nq.gz
    ├── e392a4e9218483e96070fd346d37d476724b2850.nq.gz
    ├── e3c920aff439a2ece5a5bd6726537df6c6e899af.nq.gz
    ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e6f7e835c08b146292b9fd095900f15008675f0a.nq.gz
    ├── e964e67a7bc1b2143afba2de2496204da86af217.nq.gz
    ├── ea60279cb0b211d56498f7fad4e26dd7049eafe9.nq.gz
    ├── eb5ccaee70839612701f3f597c80c55a40515a69.nq.gz
    ├── eb7b6bc89e0fa6c262a3aee3e11f254f89902f44.nq.gz
    ├── ed287d52fcbc9832de383d337092125650020cdf.nq.gz
    ├── ee27cd2c42f13afdc318a41f0a3404ffbd2e29d9.nq.gz
    ├── ee2faac4eca3b3d8d2c13c461d692e208f4e5b8e.nq.gz
    ├── eea52b82834c3dd51503b364beeefed064aef7de.nq.gz
    ├── ef054c6d897d2be92cccd51d13e7ac9f8d45decd.nq.gz
    └── efd70f2839f7fe6645989b0bbd7e47c149b1a328.nq.gz

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

[aio-libs/aiobotocore](https://github.com/aio-libs/aiobotocore)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
