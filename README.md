# Repolex Knowledge Graph of ansible-collections/community.postgresql

RDF knowledge graph data for [ansible-collections/community.postgresql](https://github.com/ansible-collections/community.postgresql), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.postgresql
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dfe50fce6c61df8e719a892ac8a7693183cf8583
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dfe50fce6c61df8e719a892ac8a7693183cf8583
│           └── chunk-001.nq.gz
└── blob
    ├── 0108e17a0f5339c159a2b0af95f0f1a522eb8734.nq.gz
    ├── 01a443a40f45ddb6c753c5f438dec180cd2ab4c0.nq.gz
    ├── 01b468754cb639ce7738836d0fb200bbf5c7d28e.nq.gz
    ├── 028c192d7714efc29c3da51e5127337893ad10b6.nq.gz
    ├── 0353e54bea7387585eb0f9f554798f8ed79cf93f.nq.gz
    ├── 041cbd58bbcd30020b30900c5d47938dd5698308.nq.gz
    ├── 049b5531f60fae414d3b358c45bdd9a9edf9d570.nq.gz
    ├── 05bac61d4527dafe994b88a7980be5b62110f9e2.nq.gz
    ├── 08645c0104b0947bed52031bea0b6d9ab85e9680.nq.gz
    ├── 08d2adb8a1c34a98868acb819c50a7cbc1aeaae8.nq.gz
    ├── 0a0b357d5960f2ad280bc7764fa87c18bce178a4.nq.gz
    ├── 0a2766702aa4aa0dcd60968d4f720591bea7ebe6.nq.gz
    ├── 0a4b7a2d3f5de65d5237f8106cb992ebe6507b01.nq.gz
    ├── 0b162335b95e2991cc33168b739a6d319f67613d.nq.gz
    ├── 0bada1b065fbef610220b61abcc22dd367848ea6.nq.gz
    ├── 0be75f39d18974f5632243290e72f83a6ea41e00.nq.gz
    ├── 0c61c0b6f8a69c2921f6f6fae527d4daf108b601.nq.gz
    ├── 0d91b7de01c742eaa5c4232030261c4a8af59299.nq.gz
    ├── 0e945a1d07e1cba085cd3fc49b62a900e29bca64.nq.gz
    ├── 0ec7d2fcc1f85e77ec910d74918f5a235ac74222.nq.gz
    ├── 0ee9a475cd318bec3c5754ca03d79581e7a55201.nq.gz
    ├── 0fab0252c61b47a788b1cd728cd2c1205a00c79a.nq.gz
    ├── 1111c3f501c8af39d9aefa8acfd1d31210d9591c.nq.gz
    ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
    ├── 142e8aa07710299c8c20fa7eb480746b36c445d7.nq.gz
    ├── 14807d61df9f3805f5f486161b7852b323f1eb02.nq.gz
    ├── 177a1c33ff921727b9a39f1a42b53b5dbde038bc.nq.gz
    ├── 1797556bf65e23290bfcc630391e55ed434a1ffa.nq.gz
    ├── 1864e4441056fcc37fd4024ff19c946244d82a60.nq.gz
    ├── 186d8507abe239e0672c93df94dbdd0e32742b20.nq.gz
    ├── 1b5e6ee2c5888ffe3571c86238b39189646b037b.nq.gz
    ├── 1bd91bdc99f8565731788ebe717960eb3594cc61.nq.gz
    ├── 1c4dd1a9f9be553e4b52e776a4fce61ebcdac5bd.nq.gz
    ├── 1cbb290c7188f4b12a6436d75535596b9a45f617.nq.gz
    ├── 1d8ab9c1a27f0fcdb57372f00f3f596836cc879b.nq.gz
    ├── 1e4d8426c71463002f718afeacc8093a85acb279.nq.gz
    ├── 1e511e6dd3e7398d31d0e62b88252e25f998c585.nq.gz
    ├── 1e5732cb3a0b958f7ad8d700f3817c5b2e7d8244.nq.gz
    ├── 1eb5b843ff245d6c406f89ca848d3b31f541565f.nq.gz
    ├── 1f78ce248eac80eb1f512b96156a9d35893c1b77.nq.gz
    ├── 1f99422080abce4605e114cfb95f7cf51e60222b.nq.gz
    ├── 2149d5bbd8a3c11df3e2c51a736f2f898c5c94b0.nq.gz
    ├── 21a47ee3b5dfa2cab3aee7d7fd6c0b2ac3cd0d01.nq.gz
    ├── 227ba1b4c4dd1e27a2e51650060376dd6e46790f.nq.gz
    ├── 230ec3421dc1b616a4119dfb96ea4728ecfd5b35.nq.gz
    ├── 233dbfc3095cf8bebc3d4da808beb10d3d734ac5.nq.gz
    ├── 23b42c1e26f2154e34f36e268e9c33cd68c2be7e.nq.gz
    ├── 252680ad61702e3035692efb882205eebf00ebc3.nq.gz
    ├── 270b47d9a36a49a8a583c1b9efd1526f1b95d31d.nq.gz
    ├── 27cfd813ce13883e76c8db18e16695d40c6f593b.nq.gz
    ├── 2ab8d06b137eba535ec76f07044b44a58a2847a5.nq.gz
    ├── 2be9cc40c01fd218d75204db3ce3e54586c5a562.nq.gz
    ├── 2d008c736becba7c5bc791ba17d003361750f305.nq.gz
    ├── 2d82eaefd38b4e72f127b8183741bea7e599b1dd.nq.gz
    ├── 2f0a8102a93156b77577bbde7f45712b5e529304.nq.gz
    ├── 2f86da36cd84a1a1d4ec9d83786e27bc75634a47.nq.gz
    ├── 2f88eca08a5760b11a42223f9e812df1de820d91.nq.gz
    ├── 317ba134ce9890bc85a6f1e5918d01624a767e7e.nq.gz
    ├── 3303407cb7f3a1be5e1832e061d6c85710a7af2a.nq.gz
    ├── 33aaef56883fb4cd6cbe3c76ab1adc60521c9032.nq.gz
    ├── 33ad6e84a6190ae9a6d57af3b1050ef2d3d80b1c.nq.gz
    ├── 33b26e792dd57be9b922cd4dfe3d856886c12064.nq.gz
    ├── 33bd94ebab7fe7322847b57878268b8d64f6ccff.nq.gz
    ├── 33d20cb3ae891753baf002fa8572b13be232a48d.nq.gz
    ├── 359c5d3bed6dff67033548ee2453d2011ebc6bc9.nq.gz
    ├── 35acd7fb5ff4bee4a15091b93cb73545679cb26a.nq.gz
    ├── 35e711215ca4163d04cbbc64dd591869f328c538.nq.gz
    ├── 3773c46e4d5a60632f1f69164060e9ac715771b5.nq.gz
    ├── 385e70bac59c4b7ed66ff71fb59cdbdf466efafe.nq.gz
    ├── 391138bd59687e1f18c051c246c7b829ea292d18.nq.gz
    ├── 3a1f09a0a43d4284a1e388788ddb6b21a0278585.nq.gz
    ├── 3c23cb5d1a0223d48bfc14018721ed734aab3df3.nq.gz
    ├── 3c3a7ecea88f01f2c1a858f30cc512fa80fcb1ab.nq.gz
    ├── 3ca192ccfd5a674092eeb4a5ccc226e57b299aca.nq.gz
    ├── 3fce77d5bf9366fa72722b4c594b4475be67fc51.nq.gz
    ├── 400528798060b6b63b2a77525978a625e27eca2d.nq.gz
    ├── 4071523ddb38b7a0a17e5885867d8fb3ab694203.nq.gz
    ├── 4105a0f81049158a4a1a17d0321e38509341f753.nq.gz
    ├── 4213f45a74ab3e8992820c1a7875da8559c461f3.nq.gz
    ├── 42d0f4ee9a03bea387bf33a28844c8d3ed5252ee.nq.gz
    ├── 439aaf2d4e58ff48970f849f50a8f8f379daa411.nq.gz
    ├── 44403c4f67d4cc8b5d7ab3e22a6a5d1e0c6d469d.nq.gz
    ├── 4456c2e24c76545f5e10cd943082a2f2c3e9f0c9.nq.gz
    ├── 45b5184026b4abaa07a4ef49ef58e46ab27bd66c.nq.gz
    ├── 47f2168fc9f4637731a53b710f910698dded0177.nq.gz
    ├── 48a491cd5fa990b8f63d0d50fada8963cdd13a01.nq.gz
    ├── 48d210d4eccaf2db68e86e1e327df3bd67079014.nq.gz
    ├── 4b2f575106068dfc8e689bfaba37965ab6c1e335.nq.gz
    ├── 4bd05d20348b85f5f8e3a228ac162a88dbc7f61e.nq.gz
    ├── 4ce5a5837ba8aa25b39798ce943eee6165942d2f.nq.gz
    ├── 4e9555dd3b6046e399d0b8171b77e9f4fa3a7535.nq.gz
    ├── 4f38316d478199a3b78c6b17f11b4dd84aea357b.nq.gz
    ├── 5073dbfcbe79a335c8cb8af262d21bdff30e001b.nq.gz
    ├── 507c1e2347681281e9de7517f6f63de19e21e423.nq.gz
    ├── 516e13faa04bf00e1f95efab322918d0bc3cfbbe.nq.gz
    ├── 5250ed80233d3310224eb2edf17e865bb5a16cf5.nq.gz
    ├── 535dd6467b3baf990742a11c7ef2e6c37f86eb0d.nq.gz
    ├── 53c79666b47b8a7d713cdb7409e025c00444bfba.nq.gz
    ├── 53e7217726ec3ad506861a993b57ab8e45fa5980.nq.gz
    ├── 5438ced5c30ae998cbd337fe217d86e970630166.nq.gz
    ├── 56385f9a1061a8dc1cda0a71d4b01cdb8b390192.nq.gz
    ├── 578032a42eaba4fc1063a4742b6f609da15d2556.nq.gz
    ├── 57bd11cd7a682e4d58a17386c9d7b247daf9cfc6.nq.gz
    ├── 58de3607f9d0aae194fd76d534e881406467f5b0.nq.gz
    ├── 5a2c9c80573d3035aed42680b0440d02520c5ff0.nq.gz
    ├── 5da901258957d893f488d7564d54687a791a6e19.nq.gz
    ├── 5e9458880199b91bbecf177f5f1dcf1abe69c3b0.nq.gz
    ├── 5ea74a292b312859a5a0f2d783ccf930e50f56c6.nq.gz
    ├── 60052fb760b65e7d67df9d2bc0e4601c2b4f0ba3.nq.gz
    ├── 60b553cf64acf8cb3c6e1a0d3e04d00174dbcca0.nq.gz
    ├── 61665464f12224c7e81dd4614e0b060a2268b068.nq.gz
    ├── 626b0fb4809bd7143b08b94f70438ec1c379b598.nq.gz
    ├── 632188460708a7fc708c79e90eaa69db51ad6119.nq.gz
    ├── 659e2113b9061562b47e72f23bf4be8b07425f26.nq.gz
    ├── 65db79ab68639de1f7bc52446abd6e8dae5fca30.nq.gz
    ├── 66e42dc9b18b1858bda0ca1004697c8c46de6a67.nq.gz
    ├── 69a6eff0200610eeb54b23f12b57f39fcc73317e.nq.gz
    ├── 69cee0e704c2629e8eb328ec35433dc2b40d8152.nq.gz
    ├── 6a178bea19b8820e2c9e33dc74993133d0211338.nq.gz
    ├── 6c1596f960583ae46a731a74af5dfd7c9fe835cd.nq.gz
    ├── 6d184f0b8da1d1198973da2c3145b32b1f2a57ed.nq.gz
    ├── 6d706ede93c85b0ff5b32bb3acb2773560f00629.nq.gz
    ├── 6ddb77685452b41e26a1a4aeafd20688342eec77.nq.gz
    ├── 70f0481a747bd73367bbf9df1414bbc45425ac5e.nq.gz
    ├── 71018ee5a253867f6a1f64d0a3445e732bfc4c02.nq.gz
    ├── 7297f9108bb105aace04bd383ec5ade64f9d9dcd.nq.gz
    ├── 729f1670afaa54379d886defb66010a5d7957196.nq.gz
    ├── 72e45d053abf52c581b05a5fa4952a78f1f7fe75.nq.gz
    ├── 7346f76709746f68766d70fecbb4a39f612f32a9.nq.gz
    ├── 73f3e189a16460aa78739af8581c832fcabf0d9b.nq.gz
    ├── 740c8115458b12e3a8f24220e718e0b33ef2e16d.nq.gz
    ├── 7496d2631d282ba94f0180c72a42602e70d3375f.nq.gz
    ├── 74991e83690143eab11b718c0f5a561771a93532.nq.gz
    ├── 77e25783046f219692c73b44e2c10e78e425c139.nq.gz
    ├── 786e053158ee271e94027b823c111a8107684772.nq.gz
    ├── 78f44403b241823f98ba748bda8ee8454054a9ab.nq.gz
    ├── 7b24dbf92acf12c018d20aa4d3eff039891e5c17.nq.gz
    ├── 7d6a60e543a442a31e31757f08898bebc21fbf5b.nq.gz
    ├── 818324eddebf4716de12c1b24b77154ff0660917.nq.gz
    ├── 823b6561a1bf70209795485224763c05c0bc5d73.nq.gz
    ├── 85dc2b77c8895a4c37f0ddc7be52a75c1806e4b6.nq.gz
    ├── 894eca1e37770192dacdfc6cccade3f517b2a325.nq.gz
    ├── 8b7a34379a23edfc5230124ca9a9665a7ceea656.nq.gz
    ├── 8be3cab4fa0bd96c2453f006f2efe2ac61e242a3.nq.gz
    ├── 8ca7c86dccf5f2cffc4f221902375112dacc415a.nq.gz
    ├── 8d0c8b489215a373d302c2616febc0ea13f8e3b0.nq.gz
    ├── 8de3d8ea7d4367efd2aa921e9f1db705d8d5f497.nq.gz
    ├── 8e16579ad9a95e43d2fc4494d1426cc0c903071e.nq.gz
    ├── 8ff0242b7372d27fd607492dafb5941fa8675b43.nq.gz
    ├── 91e468a92be6f2957cb53264f1efd31e016981de.nq.gz
    ├── 94df93f9e3f03b283a133ba709f143a3f5aa1f48.nq.gz
    ├── 952d75aaadaa69650bdd079ab4b99947a28ad51a.nq.gz
    ├── 96dfaebdca9ec51b6c23ab0dc5c20ac0badd359c.nq.gz
    ├── 97730cc1eff6903a6c6b07240f7075235c363c6d.nq.gz
    ├── 97f7497c9db07992043d0c3360cd5056e0c16b38.nq.gz
    ├── 991b966c03c2a9aad679d2ce6132e833cb74f99f.nq.gz
    ├── 9b5a043b43c431a19dc0fe7a1e418f694e441c8d.nq.gz
    ├── 9cc2f966cbbad35a9a02ccf29b9156c14d6ef893.nq.gz
    ├── a2630921cd622d85698ef77140a1f435a2aee5cc.nq.gz
    ├── a2ac435091f30c80ae244512106178925d3fed22.nq.gz
    ├── a4092ec481fa4621f5459b19e8b1757358f1227b.nq.gz
    ├── a4baf335d72ca19c17848b50e6ccfbc2ae026c80.nq.gz
    ├── a4c92ef8538742c65330f9a90cb6ca212fb1eea0.nq.gz
    ├── a5f52d3ad629ea686c1644dc99b2b9045a637c95.nq.gz
    ├── a5fa6582a7aa8b4a5e38a82def356d751ba8082f.nq.gz
    ├── a6fbbad049b90234ebdedcffb3e185902e83aa4c.nq.gz
    ├── a863020ae9ac0c8aa481c84a01272681bd6d5852.nq.gz
    ├── a947fdf013c094d1fab17bf5d424afd03db120e1.nq.gz
    ├── abed5d3c6d820a23994a819c67ff1df66bbb5d81.nq.gz
    ├── ac6d7b3fab39ff18af60452f4d98b44198e869f4.nq.gz
    ├── ae59228537d3d86d5850fd9313211ce8dc2e2c8a.nq.gz
    ├── ae6000ae186e34b4cf4d4100f9750118e963c765.nq.gz
    ├── af51cbca943b43b6796f3d3be56bfeaeee0bb68e.nq.gz
    ├── af7dfe475940dbf48e24eb675cd448d1fdbcb0fc.nq.gz
    ├── b1e21523edbd4ab90f68b2b081dd3d303e33bbdb.nq.gz
    ├── b26cb9c4e07a1d7c1032c9f9032e2a274a2b88f8.nq.gz
    ├── b33c44f78ac35618ebef4b5d82c59442ad2b22e1.nq.gz
    ├── b35ceaaa726e2ad527405fd3af1b4bf08e2e1ab0.nq.gz
    ├── b366bd17d4f604dfbc9095dd70bb3e036a270afd.nq.gz
    ├── b37dc39ec7243b437d4269386a26db5912ab9430.nq.gz
    ├── b3d94f3e6cdfd623bc07dddf90885a17dbeb9a90.nq.gz
    ├── b448bc6609c3b15b774252b5e468868b4c68b883.nq.gz
    ├── b4d90790223b95552556ea895ac541a489a7379d.nq.gz
    ├── b5c655105aab9a6c815711922131db8a8b89977f.nq.gz
    ├── b6b4cdd6d7090d395ed74434e76bf3864dbd0a98.nq.gz
    ├── ba08fdd0bee1ea95cafe9c7d9b5dbe1bd6505e92.nq.gz
    ├── bb966db98e7fdf3657eea99c883d49344aed3740.nq.gz
    ├── bc49dc7c308ef49bb23c0db5015c2dfb414920f8.nq.gz
    ├── beba23ba85df6422e645af56261c5fe1d32ab98d.nq.gz
    ├── c40946e063c380c157fd50d719cc7c3d7d92bcd1.nq.gz
    ├── c52af66c42e84ad9954598df6682c6b83f1e9632.nq.gz
    ├── c5fa981e7587ced680ce36bd8494ed569d841534.nq.gz
    ├── c6bf15532701d45fd46388ba3209bf9f06ec43bc.nq.gz
    ├── c71a79a509203bb8c940d0ebfe7f3cab4bde8993.nq.gz
    ├── c8cd6aee2a44da251a41084ef4e36c48848b56ec.nq.gz
    ├── c9033bf0c9668e2c09b6b2796b3c510759fdb2ae.nq.gz
    ├── c968a42e7ab368c9afd75a365b0b0420aed65a4e.nq.gz
    └── ca083dcb6592f2d904db4d5ee7eba715bc1ea56f.nq.gz

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

[ansible-collections/community.postgresql](https://github.com/ansible-collections/community.postgresql)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
