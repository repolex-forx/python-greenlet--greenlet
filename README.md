# Repolex Knowledge Graph of python-greenlet/greenlet

RDF knowledge graph data for [python-greenlet/greenlet](https://github.com/python-greenlet/greenlet), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download python-greenlet/greenlet
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 04303e5b8d4b0f7a4e9c9d02e3905009e55cbd45.nq.gz
│   │   ├── 1a23cf9e011c49fe855c0afd9dcfaa6eb9c73a7e.nq.gz
│   │   ├── 38d5728992a173762445bddcbac8661ee8dd0002.nq.gz
│   │   ├── 3dfd54b533e2328443a6aacc0774d4158eaf9dc6.nq.gz
│   │   ├── 475f83f05adf3bcd3d6a748ca812a6222ef2eecd.nq.gz
│   │   ├── 94a01a18b243c9e795b4383bdf6f99d3fc3009b0.nq.gz
│   │   ├── 9b39e4ba75a0c17025e69a6b02b34fab4ebd822e.nq.gz
│   │   ├── b3eb1ac391ca46aecefe94a5e017fd6d25339c84.nq.gz
│   │   ├── bad771c72f04dd98c1ad4d069bce9505a777fe9a.nq.gz
│   │   ├── c5502fb8ecbdf584b6948fda15135e690cc55e80.nq.gz
│   │   └── c78342e6231a3f97633a5f0a39de9bb9bcaf8a99.nq.gz
│   ├── lsp
│   │   ├── 04303e5b8d4b0f7a4e9c9d02e3905009e55cbd45.nq.gz
│   │   ├── 1a23cf9e011c49fe855c0afd9dcfaa6eb9c73a7e.nq.gz
│   │   ├── 38d5728992a173762445bddcbac8661ee8dd0002.nq.gz
│   │   ├── 3dfd54b533e2328443a6aacc0774d4158eaf9dc6.nq.gz
│   │   ├── 475f83f05adf3bcd3d6a748ca812a6222ef2eecd.nq.gz
│   │   ├── 94a01a18b243c9e795b4383bdf6f99d3fc3009b0.nq.gz
│   │   ├── 9b39e4ba75a0c17025e69a6b02b34fab4ebd822e.nq.gz
│   │   ├── b3eb1ac391ca46aecefe94a5e017fd6d25339c84.nq.gz
│   │   ├── bad771c72f04dd98c1ad4d069bce9505a777fe9a.nq.gz
│   │   ├── c5502fb8ecbdf584b6948fda15135e690cc55e80.nq.gz
│   │   └── c78342e6231a3f97633a5f0a39de9bb9bcaf8a99.nq.gz
│   └── repolex
│       ├── 04303e5b8d4b0f7a4e9c9d02e3905009e55cbd45.nq.gz
│       ├── 1a23cf9e011c49fe855c0afd9dcfaa6eb9c73a7e.nq.gz
│       ├── 38d5728992a173762445bddcbac8661ee8dd0002.nq.gz
│       ├── 3dfd54b533e2328443a6aacc0774d4158eaf9dc6.nq.gz
│       ├── 475f83f05adf3bcd3d6a748ca812a6222ef2eecd.nq.gz
│       ├── 94a01a18b243c9e795b4383bdf6f99d3fc3009b0.nq.gz
│       ├── 9b39e4ba75a0c17025e69a6b02b34fab4ebd822e.nq.gz
│       ├── b3eb1ac391ca46aecefe94a5e017fd6d25339c84.nq.gz
│       ├── bad771c72f04dd98c1ad4d069bce9505a777fe9a.nq.gz
│       ├── c5502fb8ecbdf584b6948fda15135e690cc55e80.nq.gz
│       └── c78342e6231a3f97633a5f0a39de9bb9bcaf8a99.nq.gz
└── blob
    ├── 005549851520353a543bef3481111e5c22b42a4a.nq.gz
    ├── 010a22c4cb96eddb25ec9c190ebdc3f55a11fb00.nq.gz
    ├── 010c651d9cd425e010a062b820bd0e1bf38ad48d.nq.gz
    ├── 01d177c680b8637a26e11bf165b970e85b7e4665.nq.gz
    ├── 0241a08ddc8fbd955ff83a790de71f7e5d60e128.nq.gz
    ├── 035d6b9499a000de9022bcdc0e843025228b0ad4.nq.gz
    ├── 049f0e731893c1ca06add172826f64c54e7658a2.nq.gz
    ├── 04fddf22f46ed64b3861b45704733c8fe9a4125d.nq.gz
    ├── 074d5ed786dcf20b7a5935f35f4ad63dab612507.nq.gz
    ├── 093f8502931fcd64f69f155e67236ddcdcef415f.nq.gz
    ├── 09514ad1b81d632b16ba85f29daabec14de4d1f0.nq.gz
    ├── 0a38d458160bebb328a311aa75ce683e7443444d.nq.gz
    ├── 0a7125545de2d79c425de21290c202cf5bb4cef9.nq.gz
    ├── 0a8547bcc8ef93701d14b4aab7e7986166744553.nq.gz
    ├── 0b2721e3f3ac9a53a65047d48ea5b171c73fac46.nq.gz
    ├── 0b9d556ef0388a4ff666cd65190c3459369b1e1c.nq.gz
    ├── 0c323700460908b59e7b462ece5ac37736df9b3b.nq.gz
    ├── 0c85dd8b4a3d210439714007bf4a1b5658197e3c.nq.gz
    ├── 0d42a671004577e681f6c3df9af9e58d8c4662cb.nq.gz
    ├── 0d8f53574d365b0756e580d9e41c3e5c2ecce2ef.nq.gz
    ├── 0eceecbf1397651aa0d86126750519a5be8dcd9b.nq.gz
    ├── 0f20756833a251e026c923c958a8debdcc92c1c5.nq.gz
    ├── 106dcf61d6a6f4d2dc4695f02cdc3d7d27cee3fc.nq.gz
    ├── 119378cd8c988c80fc21841b02605d29710e6cc1.nq.gz
    ├── 11cf5421399c25b04f7708b1e30c8f1e59149df0.nq.gz
    ├── 125435f382ac1e5745b224d14ed5f7eb075121ed.nq.gz
    ├── 150ec8be002236a06c609140864fcdb8a8d7acd2.nq.gz
    ├── 153f243e2688cde8c26ab07fb14f8984bddb2cfe.nq.gz
    ├── 162f97df8565cc9e236ab875fbfb5b98cb5c6d2c.nq.gz
    ├── 16ad463552537cc1e54c79c2d42fbee78954d094.nq.gz
    ├── 16b99b782033493bac24969c6c54ff0b4400aded.nq.gz
    ├── 178fd9d3d94bd7fcff7f5bbda79058a1df59fcec.nq.gz
    ├── 17bdd1340488e12fce81200965b4f00207ea2ea8.nq.gz
    ├── 1916b264dd06e164f12b2882e6015b22e21323bb.nq.gz
    ├── 19d4c89259178676844682fb0143a7418d4c0b81.nq.gz
    ├── 1c9c70b045abf70e430d68a9314075d3c5108801.nq.gz
    ├── 1d0d28f82d60db0cf71b90438c362624f63c88b6.nq.gz
    ├── 1f701a2a6d52d1ca304e94a1a20fdf03ab30b889.nq.gz
    ├── 2097b4435a23bbd99927e960b378489915f604b7.nq.gz
    ├── 2101ec81bde87676d980225920633789dd6ec332.nq.gz
    ├── 22c387a8c4b5ac33643d101d9f71073e0adff845.nq.gz
    ├── 22da905f4007e865c5f0088a33ca3483bcbf28c5.nq.gz
    ├── 2341031af9c5dc5862348cedfec8ec583ffd0afe.nq.gz
    ├── 2773571426fd094615b3f3a67520dd81e860c6a8.nq.gz
    ├── 279dc7ce308dd00a5e76e253ebe1fd6f7b154763.nq.gz
    ├── 2a01cc78824b0833134196c5403736e65f718558.nq.gz
    ├── 2aa35f27e96c47165533f167fbb584495c3ef571.nq.gz
    ├── 2b3d307a22d298c0a0abbebb1ed34ac49c7f6ffa.nq.gz
    ├── 2fbc569d66873aa86d13ca39aa6488f467102b15.nq.gz
    ├── 305923e6aa6197aef096d716ce6a47571db2bb9c.nq.gz
    ├── 34ae79100bdcd0446bd3fd73b32e1e4fd704545f.nq.gz
    ├── 37f678cd6715b1f0d7af0bc015931682029b92d9.nq.gz
    ├── 38b7ef4a502d459760cb3a4f07afca3dbfb7289b.nq.gz
    ├── 38d6e391f91105771a59b157cd268f098b49b43c.nq.gz
    ├── 3a35133e58993b76d8ad21e77f31a3447c3452b8.nq.gz
    ├── 3a95186556021953237f4bb91f7bc8d30f5ae23e.nq.gz
    ├── 3b26571b5ac201f2e8d64f1ec8402dec6202577f.nq.gz
    ├── 3c64c504f1d1c0f82292f86fb0a341c4fbeb7d5b.nq.gz
    ├── 3d2dfb71897b4ffb273ce17de7bbea6f02793e1e.nq.gz
    ├── 3ed0a1659e62b8c91583457fc5e75d09e5309bb1.nq.gz
    ├── 40d10af25ba6db5969401407bf6d7fa03791df5f.nq.gz
    ├── 43a9c1dc08b46fdac95996830896729d5954468e.nq.gz
    ├── 45a277ab375391f9eed9fd1bb0c362d3d10b4d96.nq.gz
    ├── 45f2ed487cefba7c845fd86e7260f7804c24087a.nq.gz
    ├── 46e330d504c287a34e09eb3d8dd95178989d418b.nq.gz
    ├── 48111b781bc84e67aa1749e9871a55425b612d9d.nq.gz
    ├── 486d4e4538c3ba7fa978f027823d42e65b141656.nq.gz
    ├── 491034f1b6869b912da140d32c0c2dea2e2a471f.nq.gz
    ├── 4b53f27c1709d1d329ce14c205422352980dd279.nq.gz
    ├── 4f3272876bb95c5ee7035655dcf8454d76b0c506.nq.gz
    ├── 4f34b156ce49ed8e56f4b390492e171a7db95e90.nq.gz
    ├── 526a5040f6b35dd549c7a8a505c2fc549e530c88.nq.gz
    ├── 53c49d9212d8b0ce8edc80ca6fd1a57d4d9eb128.nq.gz
    ├── 53d127bb3da83ebf91a60447ee7591fd6773bed6.nq.gz
    ├── 547bdf62f6c7cec679b213f3c03264e7391f8053.nq.gz
    ├── 569978e4e96d81677052d7b023aadae55fcc5b16.nq.gz
    ├── 56e573feef52fe262d44c51744625aedcb853a48.nq.gz
    ├── 57c497172971a932961f4b31b4b5097da30ff147.nq.gz
    ├── 583ccfdee8e670ae8a87eb4ff87fc9697af5ef63.nq.gz
    ├── 5870e52abd6b47f4dfe8ef52ded6ad3322628b66.nq.gz
    ├── 5a3fe10523a12718c692aa001a9b5ae0eb8bc8e4.nq.gz
    ├── 5b5ea980b603f15dfb82d27c30a0c2e919fcf6be.nq.gz
    ├── 5b668a3703c45f778a5be53543775117f78c3a31.nq.gz
    ├── 5bfe57b41978b09b2d1102612c04ec3012da7627.nq.gz
    ├── 5da547c499eea5b8b91ab7f29d6752a376148a8a.nq.gz
    ├── 5ddebbcad5984f4be488a157e9ec73a301e27800.nq.gz
    ├── 5e009e3c685ca193daa8072f4eedc0fa2dd0a202.nq.gz
    ├── 601ea56053cfa03bd99dce523d0aaec7f240276b.nq.gz
    ├── 61d29a700159d94cd99317672ba80b442e20ede4.nq.gz
    ├── 62f9f26ea1150c3bfdce6362fcea29022389a0be.nq.gz
    ├── 638343de16b32710299fa728c16b06e44f4a820c.nq.gz
    ├── 63e5df984515d4968291d09aeb4c9215c24e284b.nq.gz
    ├── 64330eed2aab09afb7fa5b7ef2242eee58acd66b.nq.gz
    ├── 64d32df819c38924cce3c1977ded314982ab2388.nq.gz
    ├── 64e3e6b898ec765d4e37075f7b1635ad24c9efa2.nq.gz
    ├── 652b57fdd0e74dfde5fc5b23b8f06ae229f6c660.nq.gz
    ├── 655bf626de6a474f00654c8af7cc24671ad60fa5.nq.gz
    ├── 6641854e6a50701a7090c96527873639fd285fdc.nq.gz
    ├── 666df6aa6169952b06431b3ea84f40994daa0f2b.nq.gz
    ├── 68caa4efef955d7f8a95fa3caf934396a9d75dd8.nq.gz
    ├── 69c1dffa4088f3f00f6a3b68416f98f787b40f5a.nq.gz
    ├── 6a2ff066f651396c0e544bd9550d9ede6650c4eb.nq.gz
    ├── 6b4f023afacdbc5582516ed1496f415f61dd6168.nq.gz
    ├── 6c7353b898ba8815ea3079f2d9cecbf992fa1e33.nq.gz
    ├── 6c9b8ee3422e6c540e25e59eaf3e385d72b7c4c3.nq.gz
    ├── 6d951b4b0af0f1a34f60c8a2e52056468f08bc19.nq.gz
    ├── 6de0dde201838df82d5fc8446666d32382d11a04.nq.gz
    ├── 6e0bfa2e53950a77cf675db3fc460ee812ddddda.nq.gz
    ├── 6e0f686612351ae84ff0b3026103c3b709b79571.nq.gz
    ├── 6e1286a9844531eea28a1dac608158b86ac1b6a6.nq.gz
    ├── 6e6549bf338b1ad3b6b724f4353ebfc920b6a56f.nq.gz
    ├── 6e8d0bacda4da0dca7e7ef9989a94a96eef61e06.nq.gz
    ├── 6eb35cb09eb8a52dbbbcf493ce2f78e8b5efe347.nq.gz
    ├── 6ff733c61e0cf39316a1236aa8ad94d6f5d4ad5e.nq.gz
    ├── 70fc1e55e00d265d7c12711b27a532a1b929f75d.nq.gz
    ├── 7333afb81eeb2c3830dae6dabdc22af190e11ccf.nq.gz
    ├── 746d041f01ffdb260db97638e79b1d875078e2a4.nq.gz
    ├── 7486b948be8193e7d3e27e49b790543c46a8e82c.nq.gz
    ├── 75faf922ed639a238d8494ab5bc2e38fb699918d.nq.gz
    ├── 764c10bb796f0eb148c23c780d81a768b05e06f0.nq.gz
    ├── 7986125055299c84c0234c4b88ccd9b5f70abb0d.nq.gz
    ├── 7a50db5a944c4cf6de43547c7d28956a18f97999.nq.gz
    ├── 7ac40acff0a8ab61f387d8b980659842a28a1c17.nq.gz
    ├── 7f638d88e97e007c20d4291ebe523dbf03460958.nq.gz
    ├── 857d7fbacb36236e56656ed8cbc50b531cb74551.nq.gz
    ├── 85868c4dece3810aa80f61ed02ddc2010bd36239.nq.gz
    ├── 8651961842596a0acfa53d992490bf2706d601b6.nq.gz
    ├── 883e5aef88c0620011b534fa4815d69d8be7fbef.nq.gz
    ├── 88599f47e0195198792f548f1d7561f2bf582896.nq.gz
    ├── 886f623ffdd1d3e8b3224ce976f06cc5f4ccac82.nq.gz
    ├── 88a42a6a35e35cd10016d78ffb08755ecc0ba09e.nq.gz
    ├── 88c022555f7cd0eafd1e35d5271ff35d48caaba2.nq.gz
    ├── 88e6847fb614c63b1dbcd841746065b6d646590c.nq.gz
    ├── 8c98e15ffe2bd0871fb47fa38b08be8ba482ce7d.nq.gz
    ├── 8d30e74391b09b4f0918f8782058bff1809e4081.nq.gz
    ├── 8e18e7fcca17b3cb268973bc00ed9c3e2e4dd9c0.nq.gz
    ├── 8efdc7726fd84ecbe784b2149ef247ebc9b4de81.nq.gz
    ├── 8fff3f5c58c33aab59c55773e1e44a228772760b.nq.gz
    ├── 9131bb81c84522b2089582e6c1ec74d1f019a25b.nq.gz
    ├── 915ccb2f161b9c31aa26397114cea2abe2409338.nq.gz
    ├── 9245103c129e7524aee82f5d6b9c10a15bf76425.nq.gz
    ├── 92ae1fc0d3762539b0dfaf9351d03649129eb9b2.nq.gz
    ├── 94b5489177db42b7fdea4105dd33aef719797d0e.nq.gz
    ├── 953aaac1b16a83f98f57254e02a6b3c6363064be.nq.gz
    ├── 9594e6247b10db3fb7116569c49b8b02ce82d59d.nq.gz
    ├── 976904f8282355101867fb1f39bcd60aa0140b95.nq.gz
    ├── 9887ed2e9bead47cdd8e979d6db9c88049542c95.nq.gz
    ├── 99048c46f4eb2ab54b6284b5a0eb0f10c6e01b0a.nq.gz
    ├── 997adb0184fb05c53bd21f7500cc9b7250da95e5.nq.gz
    ├── 99f3e747b75fb3b89da81523b8399c7b54acf05f.nq.gz
    ├── 9a9c0ed0030c3d4368978536d3b6586343c30259.nq.gz
    ├── 9b98ca74c9f01cdf5cc0963b634a31ad493dfcc8.nq.gz
    ├── 9ca1893d923cdb2febe1c5966031b37eb3326a81.nq.gz
    ├── 9d911a103e7f9a93b8aa630643942d3e3ca3b78b.nq.gz
    ├── 9e5bfd5ed50e8b9c05312560301f8dbd3292cb0c.nq.gz
    ├── 9ea18d88ea4891f528b82cb0a5c7abff60bb5720.nq.gz
    ├── a0b66f6680559756b861345c7594cb70e6426cdd.nq.gz
    ├── a1e9855ef18552ff3ac736e3d324719d75ac5e0e.nq.gz
    ├── a2014a9500f51c71301c3ab6fc63b7ab95445dee.nq.gz
    ├── a2a41cab400c6b16807d9ca9f55431496ddcdcdb.nq.gz
    ├── a4557d1f659d0f06b0cf0eb8c5524cfa82555c9f.nq.gz
    ├── a53ea06c88c971d7c543c93490aebdb69c4e46cf.nq.gz
    ├── a5765ef547fc2ecf0541a1a7dd0dd59c76c665da.nq.gz
    ├── a72de7522f81010b8bdd55959ca5cced8c783c1e.nq.gz
    ├── a7f1fc99ad1dbe92791a9213d400db3fcfe00afd.nq.gz
    ├── a96c741e778dd5a4da3c7b2bcea17dd73190466c.nq.gz
    └── a9d387a3d37f5545f1dde723c16f65ff42b2437b.nq.gz

6 directories, 200 files
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

## Source repository

[python-greenlet/greenlet](https://github.com/python-greenlet/greenlet)

---
*Parsed on 2026-04-01 by [repolex](https://repolex.ai)*
