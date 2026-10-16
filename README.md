# Repolex Knowledge Graph of koaning/scikit-lego

RDF knowledge graph data for [koaning/scikit-lego](https://github.com/koaning/scikit-lego), parsed by [repolex](https://repolex.ai).

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
rlex download koaning/scikit-lego
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f329086cb176a03a4e7c78055d7f6ea906987d1c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f329086cb176a03a4e7c78055d7f6ea906987d1c
│           └── chunk-001.nq.gz
└── blob
    ├── 019fbc010fab7154ef5ee617b3de11fef7dc4a72.nq.gz
    ├── 01a996cc1550f7e02708e26e5c4492b662116c44.nq.gz
    ├── 027f4057273f519b62891192b7d8f7171ebd084f.nq.gz
    ├── 029234f3bbc11d4f1cb148acc99ac732d3a44d73.nq.gz
    ├── 03d1f4693b5f0695ef50d72b9dd1bcd0c1472f59.nq.gz
    ├── 0454cbcf073c3fe84ffce1b0c56f2f4c570fa5b3.nq.gz
    ├── 059d1c3b41bf578070a9d7ce280d1b3fff96bc5d.nq.gz
    ├── 068a93ca818337a8e803ae37b26b0c2dda4204a9.nq.gz
    ├── 06cd54461a8b10dc0d6fcd80dd657a045f180cc2.nq.gz
    ├── 06f802f25d337a69a0dbeef1d86a6eebaeeeefbc.nq.gz
    ├── 085977c208c85c5455d4826794dd1db56dcf4084.nq.gz
    ├── 08b24ba0653e90830d8f3d8ae7b2af09ee8a4f17.nq.gz
    ├── 0a2650dbf30e8d59d3dfb4d58895bb75844c6168.nq.gz
    ├── 0b0a3ee55cfabff5530f29d49be4554d3c998f06.nq.gz
    ├── 0b410fbc9e207f4acb33a7a998780574e8fa2ce8.nq.gz
    ├── 0b5af5a1777443eaab89a3b4652f8e5877b5a446.nq.gz
    ├── 0db2e1b10442f4e35d265bfbf4b3990f83d3a772.nq.gz
    ├── 0fe550c4b750a40449afc7e5b6901aa79921bd71.nq.gz
    ├── 103d0f272021846bf31ad23bcc018212e5ae9759.nq.gz
    ├── 11dfa306e1cd0045882d05220a5d66e9a76f3f3f.nq.gz
    ├── 12508f4cb21414aeb7d4c7f7600cd243b66e9327.nq.gz
    ├── 13e5801b73613d2c87af9f8751dd0cbcf0d37d34.nq.gz
    ├── 1496ff9e0c14c112f7bba4ee115a067783c48cec.nq.gz
    ├── 14f97c627699b6b12e519bcd2feee1553b9eeccf.nq.gz
    ├── 1658a65f79df292180ad31c23b441cbd0b750df1.nq.gz
    ├── 16ae6a744341c8dce1934dfba2f344378dc949dc.nq.gz
    ├── 1770947be6b6bbd2c5c09ee9cdcf533770718843.nq.gz
    ├── 18571bd96d077d21609722ab7c80b46226bf363e.nq.gz
    ├── 1b720beb7f29da1d398f39e126da5c976a6b980a.nq.gz
    ├── 1d4b940754785e33e370750d4b609a42b9387674.nq.gz
    ├── 1d85495642e85f2582df750eb6ae4d196d5145f0.nq.gz
    ├── 209ea52f9ed990d2b9308153ebae1b5496b257f5.nq.gz
    ├── 2100d777011f654dac8582548ec31949abfa0698.nq.gz
    ├── 212c1dc0b7d6f66ccf33ca975c18048ef3657668.nq.gz
    ├── 214f05550a911893973dcfa863227545d755e600.nq.gz
    ├── 22e24380d4494747ccd2dbe9f1af627aad113d79.nq.gz
    ├── 24210844ec4eeb98b88d1a0a18b7352079f26b64.nq.gz
    ├── 2477a3d35afe4f91716e1a56d309d1927da1c8e7.nq.gz
    ├── 2713dc2e89f50be27a4570e43ec166d650762330.nq.gz
    ├── 28e564a32fa5f22e4614ed38cab1c0fcb4e5b861.nq.gz
    ├── 2a89ff5c1527dd10a52c01962c31d82127b090a8.nq.gz
    ├── 2a93b608219cfd8d8bb0766d6b402adb6c286659.nq.gz
    ├── 2d44f2928858443bc05ef3ba84ef570b1f9fcf74.nq.gz
    ├── 2eb00b4f0941ccd562949dd5afa1cb910e4933f4.nq.gz
    ├── 2eef340014f2f08ab9fb90af1e11f6b760e05296.nq.gz
    ├── 30a993e61e589607c0a646b62653192d0b4e7118.nq.gz
    ├── 30bda3abd84e664a031ea6262928c7697e4afb09.nq.gz
    ├── 316ab49ffee9bd7f5de11fab7ca7aef90fa4bc9c.nq.gz
    ├── 3185a18bf14b30cd9dc1f8fd3b9a15a54a561c41.nq.gz
    ├── 31b53ef1290a7eb6b292a16e775592a37ef9604e.nq.gz
    ├── 31d225b9d06a6cbcc6ff2fdcc14a9ed1d9880ee3.nq.gz
    ├── 31ed3670ef73aab52937a04c17567c1fb77548e3.nq.gz
    ├── 32d2b39962dee7a2f56efd82579667d6223a7ac4.nq.gz
    ├── 347c40dead8a1817bace41f8a3ee3e3fe676f9fd.nq.gz
    ├── 35669985d7bd99945803218d80a6acd983a5e97a.nq.gz
    ├── 35c16007ce6ffda6786f93b8e620e83526c9e80a.nq.gz
    ├── 36a9e87ed1ec373adbcf0d6964a1c3fdeb0ed4af.nq.gz
    ├── 36ba6108a635e66be1e77ffdf56d5299c0e02499.nq.gz
    ├── 36c5ea47cf7bf187f3d812cb27b42554e126aaae.nq.gz
    ├── 36e0bd4e73902f7000aed15644447dfea977a815.nq.gz
    ├── 37bfa873dc156f87568dbed532a96b8bccbc2e6d.nq.gz
    ├── 37debf819901cf6b99715acf5242063c3e6637c1.nq.gz
    ├── 3921bf0517836b0d2b1a666e79051d38be504845.nq.gz
    ├── 39231eee4d4802d8abfb9ccfe1e477127ca13de2.nq.gz
    ├── 395d0cd7a612fddd5cf3fc1e4ddd960f3613376a.nq.gz
    ├── 3aa5de646e740b656319b2249229f4ed1391139b.nq.gz
    ├── 3b57ce42d0ee9f1a110fd5a791841ee9d3e81913.nq.gz
    ├── 3b72db8f77b458557b2a4beeaa2580dfda5d7c99.nq.gz
    ├── 3c7eed969bd942c36c33a71d10f912719800f61d.nq.gz
    ├── 3d4ebdac6a55813d8d1c2e32fe4f6b611d6567c7.nq.gz
    ├── 3e7a7877d11a95471dde699d2e5a621bb44bbdc4.nq.gz
    ├── 3f3b3d24ccd9482896109ffe7b40ca8d6d642400.nq.gz
    ├── 3fab30eb4eb2b1aa917da4d7ff8fa4db67ae3f9b.nq.gz
    ├── 40890272ac08f5e2ddfcaa8cb0634881a52c863a.nq.gz
    ├── 4161c5acff6f471824e7f186c3be6d45386f7a2d.nq.gz
    ├── 419cc86f7b176a4e899773f48dd536b28c0d043c.nq.gz
    ├── 41e482e6af1324b0d18b9055c31a426f4cc7130d.nq.gz
    ├── 4262e73e6a8dfb4fc9d1408c40eed0b331c9293a.nq.gz
    ├── 42700f98464f9ccc9f03605d63158c13e53648ca.nq.gz
    ├── 4438c99b0dc03cf6f6e2a88211d1f16a876ed5d1.nq.gz
    ├── 449bc294974a882a9065c625a403ad2887b6b95b.nq.gz
    ├── 44c5a459ba6364a67aa20f21b5dfe7aac6c8d07b.nq.gz
    ├── 4547c5d07190112c2d499a574d48ccd3098c4949.nq.gz
    ├── 4627365868a4434b619defd263cc927673205c6f.nq.gz
    ├── 47f83c00c7de2973521c16e031ac351d4a7030bb.nq.gz
    ├── 48830b5ec112368f81f2d9c92b0d4c13cccc1f6b.nq.gz
    ├── 48cb4b53515e7ac7e0337e2b47d99ca70d38d0fc.nq.gz
    ├── 49188dc28f6046c676fb24bf4dd25d4b5c425952.nq.gz
    ├── 498ed07243e6a6ee540c63b02ab8b64e5e9243f0.nq.gz
    ├── 4a76be1f6b9e7fa306dc1333e28e43f2b43997da.nq.gz
    ├── 4d2b3e0e9acca8be233c28a611c545563accf5d6.nq.gz
    ├── 4dc49bf05f7c589aa4c36072af274d45a12ddb8b.nq.gz
    ├── 4ea24dd13a5faca35284c4727bb3a7cd90729fd4.nq.gz
    ├── 4fe48dc3f0fa84f203cf2b83065e24e4442d3a3e.nq.gz
    ├── 51a89213da36fa7f9f9539323f1871f459788730.nq.gz
    ├── 52d40a7dc30bfe41848caa08f9985fb1c0a9ba53.nq.gz
    ├── 5494d13c9fe1d5b677d4bd3f21404af91a2ae826.nq.gz
    ├── 5531c9f80ddd4c026cf1b76cac4a9ec583924e74.nq.gz
    ├── 555f933ca72219d391d397bffba372e614cb76d7.nq.gz
    ├── 560d4ddf2e4d722e3a10194d120d5b9a17607ed2.nq.gz
    ├── 568e13b73d3502e168d5e7d918f9ce29f233fc40.nq.gz
    ├── 5735d5726b38dbf478dc723f6e3aaf7729cba295.nq.gz
    ├── 57a3de75f1541978835b6706bb8870085434efa1.nq.gz
    ├── 5812e7d1b14b281ac0bf2198fd40f02827e9f94c.nq.gz
    ├── 594fe417b19b3f1c219cc78196011255b68c0388.nq.gz
    ├── 59db1ec9a0b925a1319c8327850f16580050efc9.nq.gz
    ├── 59f03f27269a63ff9cff8380727de39178bb09ea.nq.gz
    ├── 5a1553fc015a505a34693f69e065aab2442b9aaf.nq.gz
    ├── 5bd9db0e2af8ed1a595eedcd83e6ad48b3a6d757.nq.gz
    ├── 5c1045fbcc3e83d91a0987042f2dc4f0414963a3.nq.gz
    ├── 5c825ddbb6f1f797257aeb50dde5a26557adb1aa.nq.gz
    ├── 5ead256dac7f225b13eebbe89aefa98b127fdfb6.nq.gz
    ├── 5f05e1f21c1b0ab90fb6b5fbf2ca4d36f5c64926.nq.gz
    ├── 5f9d3b0f77fc0dce33d101bb0da70eaad0c4bb62.nq.gz
    ├── 606fa88ea5e918bf44dea8251c0ea8619a743423.nq.gz
    ├── 60cd8e49ae3e57dfa2280e373990916307a2748d.nq.gz
    ├── 60d0215270d4f6eb26a26271f4b60e7e045707db.nq.gz
    ├── 62851d12b88331d7f8076fb49237ef21b2619dd3.nq.gz
    ├── 635747abe80dcfe84523e64201778471c77d7419.nq.gz
    ├── 63750bd83dd8824a58c72e7e25052e238c256cc8.nq.gz
    ├── 643e0bd434ca7238084626c8de8bc55dc6b1c51d.nq.gz
    ├── 6663e8d3da70e7e873d67ed7e17b5307fd2a18af.nq.gz
    ├── 672784a0281b5e0e8fba01dead5c7d824c1d30a0.nq.gz
    ├── 67a89645c417115a6cca538e2175f16fb42ff11b.nq.gz
    ├── 67b20c53305abfb1ab5ae88b1c3f241dae9c1186.nq.gz
    ├── 67f25e2352d8812c6485696a69ffaa740ff26e1a.nq.gz
    ├── 683f509969bbcb91d1d0271b079a9a18b62f4b22.nq.gz
    ├── 694decdb4626b9d530d99da160b5487a0fb5fc59.nq.gz
    ├── 6b27e090cd13e5c2c6c2b1100e8c3261705a44fe.nq.gz
    ├── 6bb86e043366766e8857c55a38402675ba6b3d4e.nq.gz
    ├── 6c7b01b6e6f5048e98f72efc0ee98e8cf5069bc1.nq.gz
    ├── 6d1abcd35a61233213275dc9cf60f13326733954.nq.gz
    ├── 6dfa44c4d010cc48f374136889c8e433a7c9b1a6.nq.gz
    ├── 6faec56f4105f6d31686b5b9bc1ed998262a2e04.nq.gz
    ├── 7128e8c4cff5ab6247a19caac13581f31f4567dc.nq.gz
    ├── 7196eebad0c865cb74d54534d35aacf0aae6f934.nq.gz
    ├── 73d9ac678da5ad316b0d409286651e773589ab66.nq.gz
    ├── 74dc5393bb7ae181da3e1c19031523eba4696e13.nq.gz
    ├── 757eeee46c01b3a77ef36e23a0ac661c620ce832.nq.gz
    ├── 775bc77ff5a22dfa84208b77b4e3fe45c1415f51.nq.gz
    ├── 798bb6c25ef232efdda408aa24569402019e0a43.nq.gz
    ├── 79b83a5a8ab42031c6722f2a34bd5c6d84ca4bfa.nq.gz
    ├── 7a68b75694b68078973ec7a7e47977d95f959777.nq.gz
    ├── 7b43405e9a8c1057ce7138c3ae08fedb727a0cdb.nq.gz
    ├── 7b4d74f85d700fd00931d20effedb0024c0d77bf.nq.gz
    ├── 7cd45e5c3d02e5858a182e1aa9a017a32fde7136.nq.gz
    ├── 7df542b6917590c4a0cfb4540be9dbd27cb6cd74.nq.gz
    ├── 7e0995df8b7304ab1f4b416832d5195cfedc760e.nq.gz
    ├── 7e8a925af110eb85e51d42be6a00a007519c4df3.nq.gz
    ├── 7f11d3c00094a090c7a6c8d01deb7a69ab0a90c8.nq.gz
    ├── 7f166308133a7f1cc5d3d85b6a13daf171252547.nq.gz
    ├── 80cd6518791df77b6db18ba5bcf7518c18f1ea9d.nq.gz
    ├── 80de4d4198b8f83ebb6a3ca2b72c902610582124.nq.gz
    ├── 8102242113d3449494a611d73e77c0af713abd50.nq.gz
    ├── 83339e927f44ff113a886db27c652924b973f90c.nq.gz
    ├── 83ab59d659b1649d9e257139b16d0457105a8cc2.nq.gz
    ├── 841cf706184aa30c1f9c46bcb20b4e2ddb586f3a.nq.gz
    ├── 843ba933d49aae3d9d6db32a948a0e822d0fec17.nq.gz
    ├── 845f02da9af0997b418131b5c8f79e517dbd507b.nq.gz
    ├── 88e371bdfb99525124ee4ff25cf555033e58c56a.nq.gz
    ├── 8976e4c4e00242dcad4601933fdcfd4a1f26f5b8.nq.gz
    ├── 8b2fbadb11ead0bc2b44573741ab1d7b05390f41.nq.gz
    ├── 8bab95607bc0998fca8ae404bbcc47a9197f986e.nq.gz
    ├── 8cd7cbdc25d1e51612148bf6821c873f3c4f2b7a.nq.gz
    ├── 8d4ea5cdf6177f93b2516e4c603f601731715b99.nq.gz
    ├── 8f18a0e36c2d9b7a7cf6fadf600e799e45906424.nq.gz
    ├── 8f26a72ccf40f1ffaadacf5068b67525bdf1c10f.nq.gz
    ├── 9069c8ed5951229f492700467a857c5ba8b1f989.nq.gz
    ├── 92c8f5091d6cd3e8d4f0afb693f85b7c1f03a764.nq.gz
    ├── 95d13f89c9b6149abe2d0122eff22ad11dea33da.nq.gz
    ├── 979407027b0adb9c62a209808bfc00f66197a674.nq.gz
    ├── 9824c54278afcea9b4a250564d392e5c2be04db1.nq.gz
    ├── 98efa85043a868745f57ce52cbfccbe6aac92d86.nq.gz
    ├── 98faa4766554cdb96f19ef73105df56b7e4e5bf0.nq.gz
    ├── 9965c0bdd8fde4a9d3f3e9133a845ce61b07cf92.nq.gz
    ├── 9a761cb2c2a59a85e8030f0e312cce89f86e7af0.nq.gz
    ├── 9aca2daba3083c982aa0a9759c5811ce0c3b5b92.nq.gz
    ├── 9b36c70629aa1dd8b9e5e30d13ceb1849a2135d3.nq.gz
    ├── 9c071ccd5a67de0a29371cfa1e604ccf7e1fcb25.nq.gz
    ├── 9c1769c3b8fe1263e2f1bf27caaf51a213b674e4.nq.gz
    ├── 9cd8e80211b2713390627512444300e135d8df1b.nq.gz
    ├── 9de052d1fb9b06984735b2e8abbb490e85fad388.nq.gz
    ├── 9f66dafac71cf82d9d2579623b8464b84591125f.nq.gz
    ├── a0e014a0a727dc34677052f1026f1443dea8b05a.nq.gz
    ├── a1081b469c338f8b4560253e19932d218b81ea56.nq.gz
    ├── a15702837a09eb72d5971627d4f0d65e78162a8c.nq.gz
    ├── a2b62d0533a136610797b879932dd8640dcd5df3.nq.gz
    ├── a2d399bcf1028021f86411b6236592167c8a6688.nq.gz
    ├── a4d39f3fe305607f8a76ab763f11e4b15b120250.nq.gz
    ├── a5110e7e84cd568b1d4f527d59a2d706a82897ea.nq.gz
    ├── a57c75a2685d81b6c872bc6e4a0a1b4458a313b2.nq.gz
    ├── a6e29297056e7171ec947bfbcb1f18891661147b.nq.gz
    ├── a79b577af97a4cea4f3fe098e0f44a213a9ce62f.nq.gz
    ├── a7f075f6c50d62d3dc080a429d5e7b0cf6dc8fab.nq.gz
    ├── a8fb7efb68ee347e88233d4ae6dac9428b25d588.nq.gz
    ├── a9984feed54da1fb0bd939c697ce886105e63e2b.nq.gz
    ├── a9c99a2f2276c0549b52298f3910d36e44e58d28.nq.gz
    └── ab89a62ba521c1f2ff3801ae847861312e54ae1a.nq.gz

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

[koaning/scikit-lego](https://github.com/koaning/scikit-lego)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
