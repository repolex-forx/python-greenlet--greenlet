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
│   │   ├── 3dfd54b533e2328443a6aacc0774d4158eaf9dc6.nq.gz
│   │   ├── 475f83f05adf3bcd3d6a748ca812a6222ef2eecd.nq.gz
│   │   ├── 94a01a18b243c9e795b4383bdf6f99d3fc3009b0.nq.gz
│   │   ├── bad771c72f04dd98c1ad4d069bce9505a777fe9a.nq.gz
│   │   ├── c5502fb8ecbdf584b6948fda15135e690cc55e80.nq.gz
│   │   └── c78342e6231a3f97633a5f0a39de9bb9bcaf8a99.nq.gz
│   ├── lsp
│   │   ├── 3dfd54b533e2328443a6aacc0774d4158eaf9dc6.nq.gz
│   │   ├── 475f83f05adf3bcd3d6a748ca812a6222ef2eecd.nq.gz
│   │   ├── 94a01a18b243c9e795b4383bdf6f99d3fc3009b0.nq.gz
│   │   ├── bad771c72f04dd98c1ad4d069bce9505a777fe9a.nq.gz
│   │   ├── c5502fb8ecbdf584b6948fda15135e690cc55e80.nq.gz
│   │   └── c78342e6231a3f97633a5f0a39de9bb9bcaf8a99.nq.gz
│   └── repolex
│       ├── 3dfd54b533e2328443a6aacc0774d4158eaf9dc6.nq.gz
│       ├── 475f83f05adf3bcd3d6a748ca812a6222ef2eecd.nq.gz
│       ├── 94a01a18b243c9e795b4383bdf6f99d3fc3009b0.nq.gz
│       ├── bad771c72f04dd98c1ad4d069bce9505a777fe9a.nq.gz
│       ├── c5502fb8ecbdf584b6948fda15135e690cc55e80.nq.gz
│       └── c78342e6231a3f97633a5f0a39de9bb9bcaf8a99.nq.gz
└── blob
    ├── 010a22c4cb96eddb25ec9c190ebdc3f55a11fb00.nq.gz
    ├── 010c651d9cd425e010a062b820bd0e1bf38ad48d.nq.gz
    ├── 0241a08ddc8fbd955ff83a790de71f7e5d60e128.nq.gz
    ├── 035d6b9499a000de9022bcdc0e843025228b0ad4.nq.gz
    ├── 049f0e731893c1ca06add172826f64c54e7658a2.nq.gz
    ├── 04fddf22f46ed64b3861b45704733c8fe9a4125d.nq.gz
    ├── 074d5ed786dcf20b7a5935f35f4ad63dab612507.nq.gz
    ├── 09514ad1b81d632b16ba85f29daabec14de4d1f0.nq.gz
    ├── 0a38d458160bebb328a311aa75ce683e7443444d.nq.gz
    ├── 0a7125545de2d79c425de21290c202cf5bb4cef9.nq.gz
    ├── 0a8547bcc8ef93701d14b4aab7e7986166744553.nq.gz
    ├── 0c323700460908b59e7b462ece5ac37736df9b3b.nq.gz
    ├── 0d42a671004577e681f6c3df9af9e58d8c4662cb.nq.gz
    ├── 0d8f53574d365b0756e580d9e41c3e5c2ecce2ef.nq.gz
    ├── 0f20756833a251e026c923c958a8debdcc92c1c5.nq.gz
    ├── 106dcf61d6a6f4d2dc4695f02cdc3d7d27cee3fc.nq.gz
    ├── 119378cd8c988c80fc21841b02605d29710e6cc1.nq.gz
    ├── 11cf5421399c25b04f7708b1e30c8f1e59149df0.nq.gz
    ├── 125435f382ac1e5745b224d14ed5f7eb075121ed.nq.gz
    ├── 150ec8be002236a06c609140864fcdb8a8d7acd2.nq.gz
    ├── 162f97df8565cc9e236ab875fbfb5b98cb5c6d2c.nq.gz
    ├── 16b99b782033493bac24969c6c54ff0b4400aded.nq.gz
    ├── 178fd9d3d94bd7fcff7f5bbda79058a1df59fcec.nq.gz
    ├── 1916b264dd06e164f12b2882e6015b22e21323bb.nq.gz
    ├── 19d4c89259178676844682fb0143a7418d4c0b81.nq.gz
    ├── 1c9c70b045abf70e430d68a9314075d3c5108801.nq.gz
    ├── 1d0d28f82d60db0cf71b90438c362624f63c88b6.nq.gz
    ├── 1f701a2a6d52d1ca304e94a1a20fdf03ab30b889.nq.gz
    ├── 2097b4435a23bbd99927e960b378489915f604b7.nq.gz
    ├── 2101ec81bde87676d980225920633789dd6ec332.nq.gz
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
    ├── 4f3272876bb95c5ee7035655dcf8454d76b0c506.nq.gz
    ├── 4f34b156ce49ed8e56f4b390492e171a7db95e90.nq.gz
    ├── 526a5040f6b35dd549c7a8a505c2fc549e530c88.nq.gz
    ├── 547bdf62f6c7cec679b213f3c03264e7391f8053.nq.gz
    ├── 569978e4e96d81677052d7b023aadae55fcc5b16.nq.gz
    ├── 56e573feef52fe262d44c51744625aedcb853a48.nq.gz
    ├── 57c497172971a932961f4b31b4b5097da30ff147.nq.gz
    ├── 583ccfdee8e670ae8a87eb4ff87fc9697af5ef63.nq.gz
    ├── 5870e52abd6b47f4dfe8ef52ded6ad3322628b66.nq.gz
    ├── 5a3fe10523a12718c692aa001a9b5ae0eb8bc8e4.nq.gz
    ├── 5da547c499eea5b8b91ab7f29d6752a376148a8a.nq.gz
    ├── 5ddebbcad5984f4be488a157e9ec73a301e27800.nq.gz
    ├── 5e009e3c685ca193daa8072f4eedc0fa2dd0a202.nq.gz
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
    ├── 68caa4efef955d7f8a95fa3caf934396a9d75dd8.nq.gz
    ├── 6a2ff066f651396c0e544bd9550d9ede6650c4eb.nq.gz
    ├── 6b4f023afacdbc5582516ed1496f415f61dd6168.nq.gz
    ├── 6c7353b898ba8815ea3079f2d9cecbf992fa1e33.nq.gz
    ├── 6d951b4b0af0f1a34f60c8a2e52056468f08bc19.nq.gz
    ├── 6de0dde201838df82d5fc8446666d32382d11a04.nq.gz
    ├── 6e0bfa2e53950a77cf675db3fc460ee812ddddda.nq.gz
    ├── 6e1286a9844531eea28a1dac608158b86ac1b6a6.nq.gz
    ├── 6e6549bf338b1ad3b6b724f4353ebfc920b6a56f.nq.gz
    ├── 6e8d0bacda4da0dca7e7ef9989a94a96eef61e06.nq.gz
    ├── 6ff733c61e0cf39316a1236aa8ad94d6f5d4ad5e.nq.gz
    ├── 70fc1e55e00d265d7c12711b27a532a1b929f75d.nq.gz
    ├── 7333afb81eeb2c3830dae6dabdc22af190e11ccf.nq.gz
    ├── 746d041f01ffdb260db97638e79b1d875078e2a4.nq.gz
    ├── 75faf922ed639a238d8494ab5bc2e38fb699918d.nq.gz
    ├── 764c10bb796f0eb148c23c780d81a768b05e06f0.nq.gz
    ├── 7986125055299c84c0234c4b88ccd9b5f70abb0d.nq.gz
    ├── 857d7fbacb36236e56656ed8cbc50b531cb74551.nq.gz
    ├── 85868c4dece3810aa80f61ed02ddc2010bd36239.nq.gz
    ├── 8651961842596a0acfa53d992490bf2706d601b6.nq.gz
    ├── 883e5aef88c0620011b534fa4815d69d8be7fbef.nq.gz
    ├── 88599f47e0195198792f548f1d7561f2bf582896.nq.gz
    ├── 886f623ffdd1d3e8b3224ce976f06cc5f4ccac82.nq.gz
    ├── 88a42a6a35e35cd10016d78ffb08755ecc0ba09e.nq.gz
    ├── 88c022555f7cd0eafd1e35d5271ff35d48caaba2.nq.gz
    ├── 8c98e15ffe2bd0871fb47fa38b08be8ba482ce7d.nq.gz
    ├── 8d30e74391b09b4f0918f8782058bff1809e4081.nq.gz
    ├── 8e18e7fcca17b3cb268973bc00ed9c3e2e4dd9c0.nq.gz
    ├── 8efdc7726fd84ecbe784b2149ef247ebc9b4de81.nq.gz
    ├── 9131bb81c84522b2089582e6c1ec74d1f019a25b.nq.gz
    ├── 915ccb2f161b9c31aa26397114cea2abe2409338.nq.gz
    ├── 9245103c129e7524aee82f5d6b9c10a15bf76425.nq.gz
    ├── 94b5489177db42b7fdea4105dd33aef719797d0e.nq.gz
    ├── 953aaac1b16a83f98f57254e02a6b3c6363064be.nq.gz
    ├── 9594e6247b10db3fb7116569c49b8b02ce82d59d.nq.gz
    ├── 9887ed2e9bead47cdd8e979d6db9c88049542c95.nq.gz
    ├── 99048c46f4eb2ab54b6284b5a0eb0f10c6e01b0a.nq.gz
    ├── 997adb0184fb05c53bd21f7500cc9b7250da95e5.nq.gz
    ├── 99f3e747b75fb3b89da81523b8399c7b54acf05f.nq.gz
    ├── 9a9c0ed0030c3d4368978536d3b6586343c30259.nq.gz
    ├── 9b98ca74c9f01cdf5cc0963b634a31ad493dfcc8.nq.gz
    ├── 9ca1893d923cdb2febe1c5966031b37eb3326a81.nq.gz
    ├── 9d911a103e7f9a93b8aa630643942d3e3ca3b78b.nq.gz
    ├── 9e5bfd5ed50e8b9c05312560301f8dbd3292cb0c.nq.gz
    ├── a1e9855ef18552ff3ac736e3d324719d75ac5e0e.nq.gz
    ├── a2014a9500f51c71301c3ab6fc63b7ab95445dee.nq.gz
    ├── a2a41cab400c6b16807d9ca9f55431496ddcdcdb.nq.gz
    ├── a4557d1f659d0f06b0cf0eb8c5524cfa82555c9f.nq.gz
    ├── a53ea06c88c971d7c543c93490aebdb69c4e46cf.nq.gz
    ├── a5765ef547fc2ecf0541a1a7dd0dd59c76c665da.nq.gz
    ├── a72de7522f81010b8bdd55959ca5cced8c783c1e.nq.gz
    ├── a7f1fc99ad1dbe92791a9213d400db3fcfe00afd.nq.gz
    ├── a96c741e778dd5a4da3c7b2bcea17dd73190466c.nq.gz
    ├── a9d387a3d37f5545f1dde723c16f65ff42b2437b.nq.gz
    ├── ac346bfb5e0bde702777fd81c473dd32a9116ee5.nq.gz
    ├── ad1888fd31677988612b7eb967c08e4a59354c71.nq.gz
    ├── ad412a39528c2ba026a688f9108edf2691f5c148.nq.gz
    ├── aed8e5d93bf57b7a73f57040515a1fbe61e2dadf.nq.gz
    ├── b291baf10f97aca8e4bf05653cf5fc267ddf4533.nq.gz
    ├── b3f27c2f26f0b7e9e76dc969dbdb5fb86485d0ed.nq.gz
    ├── b512b6440d5a3f438f83707e20de179d6425e0e3.nq.gz
    ├── b5919c19de3bf99dd587ce1c6320c6ac116b6d12.nq.gz
    ├── b8431b488474a7227e2b3ee72553ab5e211ed972.nq.gz
    ├── badae7fa2546703ec6a20b95cc69a793bfa6b940.nq.gz
    ├── bc03c14ff48c4342ba5be777b4ae2a027bf54714.nq.gz
    ├── bc49033e275f806ca281a30375fae3755a94d09b.nq.gz
    ├── bfc52d9e1cce3128e4df8383a5940eb01a47e0a4.nq.gz
    ├── c0f1e6cbef2983fc0657109a63e711563e63a285.nq.gz
    ├── c42a605de1f2b4b83a14069273c6df2be0c98bc3.nq.gz
    ├── c6b6671a9085950701b12848c2fa181ca680b81a.nq.gz
    ├── c6e160d346689505bce0fcd4eae909f404513e60.nq.gz
    ├── c7d2b4a66caef039c169fa7ba969f106cc5be4ac.nq.gz
    ├── c8fe7de9a9b8aceaa75996fa67eedce69dcb74f4.nq.gz
    ├── c9b82630db5e20eef8a42c314b039aa70159b36b.nq.gz
    ├── cb14ec1cf92ac71adf106464d0337e2ff0cba82c.nq.gz
    ├── cdc02ce5401014161bfcd6be30b650b49e6152b6.nq.gz
    ├── d33c13b88b46be75c2d00101b630c80fdbd15188.nq.gz
    ├── d3b509a2b4119c47ad86af9fc1b400ce2eb09cf1.nq.gz
    ├── d546e2ffbb379e4ce585fb52b1af42b3f634cdf9.nq.gz
    ├── d5acc55c47f606d6f96bfa4405eb3af5bd158fe4.nq.gz
    ├── d774c50e168188a05b5cf54c6b88e337b242ac2e.nq.gz
    ├── d97e96466ebd1acfca4b2d45a6e45d7355dc14d8.nq.gz
    ├── d9a31585ccddf0e20008204ff402d97bfeac15c7.nq.gz
    ├── da761c2da81825aad0463af2c5864c2d9d8580e2.nq.gz
    ├── dc8450698b3e5f940b0ff1b0944c19c30c889ccd.nq.gz
    ├── debd28089249743963ac7472af8be44be552193a.nq.gz
    ├── ded1fda0b05ef35e83ecdcac704922fa45ca6179.nq.gz
    ├── e3d92a12d6c6f113b545d15938dd00672be71579.nq.gz
    ├── e5ed111c04f3a75be87b9c6ec47ad51abfcdfcb6.nq.gz
    ├── e6c7337bd18bfffde84e896efc1a70b63fb07b4a.nq.gz
    ├── e7452717a9fb6fd0fac71a6bf4b06557e61dff17.nq.gz
    ├── e7935fd827d43d2d9e9d50f708672208ed4b60b3.nq.gz
    ├── e7bfbfdaba6403fee85e729d60d892d12fd1a31e.nq.gz
    ├── e80bb7edb047c2425af346878622318a558134e0.nq.gz
    ├── e8bdde80232d16700bea6f9752945015e4f82f04.nq.gz
    ├── e993707f56e88da55b13cfecdc318844dc435c46.nq.gz
    ├── eb1dc22c52ac4a67e9f60a954336e9183d24168f.nq.gz
    ├── ec8b70c84aec82116db819b084c52db750bc1fe1.nq.gz
    ├── ed35a495d75777ae93be1167c789183e9075e258.nq.gz
    ├── efbc00dcc3c3aeed1342bd3a4e278c15843cf39f.nq.gz
    ├── f1b1af083886bb35ac7403d7511c6ff23c81af8f.nq.gz
    └── f34a0880b4fd8cc9d5b6c161e047083a2fe520e4.nq.gz

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
