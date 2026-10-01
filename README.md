# Repolex Knowledge Graph of block/artifact-swap

RDF knowledge graph data for [block/artifact-swap](https://github.com/block/artifact-swap), parsed by [repolex](https://repolex.ai).

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
rlex download block/artifact-swap
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6715907acef67e3347273853ac1aa4bdd894cc57
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 6715907acef67e3347273853ac1aa4bdd894cc57.nq.gz
│   └── repolex
│       └── 6715907acef67e3347273853ac1aa4bdd894cc57
│           └── chunk-001.nq.gz
└── blob
    ├── 00efc7d017bacdc18f7b51d5375a57a1f82ee612.nq.gz
    ├── 017f6937a4255e4bd7bff7394f52f1b71849d8c8.nq.gz
    ├── 01ce989711ac8e1120ab76d246241eb3264ee272.nq.gz
    ├── 03754c4c3d9206f5c9ef69e41990dfe26a05251e.nq.gz
    ├── 0440bbe6b4c41f7088e03099267e943e862292f7.nq.gz
    ├── 06bc81af259b54f11e7bc921423c97b64cef4881.nq.gz
    ├── 07959204101713b4016e3e010cece9e4502ea8b7.nq.gz
    ├── 07f0b2835419972624aa8714a525924bfb0306ed.nq.gz
    ├── 07f8a0f4c91a8221f34e49850bf6bc422fd6ab9e.nq.gz
    ├── 08631781130cea0713f42cc099559a827955206a.nq.gz
    ├── 091f651c8f07c13b267b4be372e5d1241f4b8797.nq.gz
    ├── 095be9e64dca73bfe39ed7afd2ac7435742ef59d.nq.gz
    ├── 09b7c010529753065d09d1208c531629d62fd90b.nq.gz
    ├── 0d59dfb5ae0cc1b886619ec3e5b3d99e9cd96745.nq.gz
    ├── 0e2e5873fc1982dcf9ef109e54954847d31a0177.nq.gz
    ├── 0f02fba3f3f72b6ddc480ba2dd5c9ef1d9282b4a.nq.gz
    ├── 133dae0705c5f2ba92fcf25329c1300fef1a908b.nq.gz
    ├── 192f9e1b047ba9f454e868354ba092ad7b16e541.nq.gz
    ├── 19a3a28c084d1fc1130779b16105199e84a101fb.nq.gz
    ├── 1bc469e68eb776aa52185c6cbfc5cdcaee837ce3.nq.gz
    ├── 1d0469ff3885d3ffcdd2092abea6c9b25ac91610.nq.gz
    ├── 1f5ad987e6b17329c341ec8f5ab5ae9387a6b698.nq.gz
    ├── 2001f5b4c554d1b786d48ddda524444b073e87a0.nq.gz
    ├── 211d1f35161802f8ecc805c17ddb4761f7461e1a.nq.gz
    ├── 214e16712663646bd5185cf8a983fe62dcc99d7a.nq.gz
    ├── 21550f88e8a5cdef4f9e425c33ed39daa55b3520.nq.gz
    ├── 21f88bf1cfda034171c2a9b330170d9618709623.nq.gz
    ├── 2230a3f856c6a2fb2cdbee9ac6646af6ed284019.nq.gz
    ├── 228fe2a1cb69d11e17f1c21ba8b67774db922dd6.nq.gz
    ├── 22c7ce2d184f90db68ea7b492f822a14c99a8514.nq.gz
    ├── 230e8f3502873025683366890dc87c147665c292.nq.gz
    ├── 23f8a1b209c6e59ea45dd01c25e941262e841b7d.nq.gz
    ├── 249efbb032ce46a80c687c0723eb172e85f6a136.nq.gz
    ├── 257cd1c89a10e0303d7002f6c5a369286ce63351.nq.gz
    ├── 2764ca44b3b09e217ee68ae7d267d4dbf27cd2d2.nq.gz
    ├── 2937e9fb334c713a2b1d3e757e282362c0687efd.nq.gz
    ├── 2941084966bb8d5abc06146e1fbcaf50075761e8.nq.gz
    ├── 2a5f7182ef98bdf88df7dc9b80d7567e50dff74b.nq.gz
    ├── 2a91e38e97ddcf965feefb07f0c8f6c85749ea5a.nq.gz
    ├── 2aca13e7fa25836199e4fafbac4672443d852694.nq.gz
    ├── 2bbb34a344fca4fd36ff6c6cabd38e683dcd6455.nq.gz
    ├── 2dadbb40512cd6f0ff6656d72beb6a10ab9458c8.nq.gz
    ├── 2ea83b9263eb7127bed94f8c5a2320f002330b61.nq.gz
    ├── 2ed82ebfee256bc549f00320967cbdb069c37041.nq.gz
    ├── 2fca63274ac94d03093d9234a0c8d21d92210a95.nq.gz
    ├── 30929479f56c7662e1f1000dd644d5dd92ae87d6.nq.gz
    ├── 33faa05152b3c7ad9c1f57e655957bc6a4e16d31.nq.gz
    ├── 3461c007dd7a0d0fc45bd9bafd47bf9abc24dc0e.nq.gz
    ├── 347bf296d8bd6fca6013805bb31c4ef0a2db6b0d.nq.gz
    ├── 3481d685bae05663ccf1605613f96d5522352599.nq.gz
    ├── 385151b3608412c733523c6eb86d24ba8d7c5077.nq.gz
    ├── 3a8c2bad644e67d90f4e7af6e8bd45daa6e1b7ad.nq.gz
    ├── 3ac4d40cac5674f001e4a48b2d2188f2b83cc0c8.nq.gz
    ├── 3ce30b71d8fd0ea19d136a96be4ebc949f8fd9a6.nq.gz
    ├── 3e6bf833fd4f4dbd5809d07a6d7440edbdf14bbb.nq.gz
    ├── 3fd46bf327efcb99f5bc86f76ac970d1db4633ac.nq.gz
    ├── 3fddd721757ae63d1a4c2d3ac90695b33d78182b.nq.gz
    ├── 40cd9a2b68bc463f696356b5092825057d9a3b1f.nq.gz
    ├── 41e77d645286e1a35b0764f5a1ec06847abf4966.nq.gz
    ├── 42b97ca938f3af682fcaad524237344cfbb37972.nq.gz
    ├── 43ba6d5d4d966d65bbf80acd67088fa827718e49.nq.gz
    ├── 4443d1958d9e40d9d7e82ed12729494db1ae3ed1.nq.gz
    ├── 45c5fed10add271bc234b08dca65a7ebe9374548.nq.gz
    ├── 463ec50198356c11568bd082bb842f9479221363.nq.gz
    ├── 48c9d46df85b229ea1b177cf9606662e609b838e.nq.gz
    ├── 4ac663357a35512616ae11d4b2d4cc95110ea022.nq.gz
    ├── 4b5b9257ce25e153f65ca580920843209ee43d31.nq.gz
    ├── 4d47f1a1b816ffa380df967daaad825a7cab8038.nq.gz
    ├── 4e0b59c2c963d62f6579f1f8ffacb2e41cbcdaea.nq.gz
    ├── 4ec9d674f5c0811ea95f12eb62e0d6974fdffca9.nq.gz
    ├── 4f3880fcb7f1fe7e4f40dda129a8fa1b32ffc86f.nq.gz
    ├── 4fd92bca21eb0ee0117c83510231846ea0dd50e7.nq.gz
    ├── 5097068a8d375f5bf0d15693fb5b3615c972a801.nq.gz
    ├── 50b7bb42d853fc5beabc792d978b9ae7b4d40fa7.nq.gz
    ├── 5104619d9e7cde4e8a0aa7b072ccbff66d1964c3.nq.gz
    ├── 51cc7d9047357fc77768b2df58ca32e52b04fe8b.nq.gz
    ├── 56705fc9a8978b9512b555b1b5f084945342e809.nq.gz
    ├── 567501e3a0e47edb4b3e3731931485ff1fa7c84b.nq.gz
    ├── 5852212212fb7caa12dc58029d8f65c302481061.nq.gz
    ├── 58dcb08e1b94f8da7928e49caa3debc9a6324625.nq.gz
    ├── 59b273d0007de4e6868c4110b26d2c9c184386a5.nq.gz
    ├── 5e1d4226a0a15cc35516e1dde9a149bc64b992cb.nq.gz
    ├── 5eb2d7cbce07773254431af39da2d03cf88e7a36.nq.gz
    ├── 5f1d9645f9dbd165ceaa5931bde78f3b6df43a34.nq.gz
    ├── 5f96f8a9a7b4ad49fac98158c9a151d95e10d22f.nq.gz
    ├── 60679dd274a6c439f05bb7e0c5a3566aa7ced7f9.nq.gz
    ├── 618e2ff41e458ada80942283333ece682024daa2.nq.gz
    ├── 620037111367d855f6a19a274e066aed73e263aa.nq.gz
    ├── 62a7d8ab6afe6a11f5c02699d8fefdb0d7e92236.nq.gz
    ├── 6b4cb93f089791681909cd182318a35f8c901996.nq.gz
    ├── 6ba30e16e761f78f4067be2abe7bf039b5b2a513.nq.gz
    ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
    ├── 6eb441061df55ebdf8b1600c66eabb5dc1bf2b3b.nq.gz
    ├── 6ebd4d117f313d217e6e909f3cbee900de31a0bb.nq.gz
    ├── 6f2bf4c6a4c77d8fbe867afb24fbc8f40f54c93a.nq.gz
    ├── 6f4742e0a33d3024921444cccfc56ab018217ff6.nq.gz
    ├── 6faaa890e37273d9f2ecd2273b2e251199ae9c76.nq.gz
    ├── 7070107a3a5c0478cd9094a2f99bdb55bb6a13d7.nq.gz
    ├── 74fb3f512385fcf37c13b415beba7996e5cc9165.nq.gz
    ├── 7609817e6b79a484973b3eda850b4713609555ba.nq.gz
    ├── 764adbdbaaf18e308eb970d77192896c764771b7.nq.gz
    ├── 775773c4870c444b3f716a301362c97b8f4b434d.nq.gz
    ├── 7774e1ef0edf585cd71d322b9948e72ff78309c0.nq.gz
    ├── 7787a689563c4e83bd8fb3bad0bf987e281d66be.nq.gz
    ├── 787bdfe03627d14a499bc024ebe28e2dc87e224f.nq.gz
    ├── 787c02ebd3920df76ef14f727447fc63d5cec3d9.nq.gz
    ├── 79691b0421f28cd8efc9e62413eb4d2060ade595.nq.gz
    ├── 7ace41afdfe396f70d1dc75d649374f80807e500.nq.gz
    ├── 7d20a5cb8f9d5d768197dbef226f6ab22550fca7.nq.gz
    ├── 7d5680e531dc5dd8caa89fb502bfba47e30e14a4.nq.gz
    ├── 8295a6c1474df2486402ecb3c19f20690d8abe9c.nq.gz
    ├── 83896690bec40281054e653ce9191578fecab4df.nq.gz
    ├── 84598926fb2bb00c0a8444a03c73590705baffff.nq.gz
    ├── 84b929ce11f1a15a41582dba225f75d95aef7a8c.nq.gz
    ├── 856163d52b366f94a84c5295aeb041aeacf6377e.nq.gz
    ├── 87e021289a8dbac7c1ef3efca5c419669a0cdfb5.nq.gz
    ├── 888d21c5e024556197bc879820430b2c203aadea.nq.gz
    ├── 88ff47d4623daa005c262bd8843272bfea843d0d.nq.gz
    ├── 899f33cd31b9ac1efefa98a407b985d0d7b3a1cd.nq.gz
    ├── 89a4e2843e89bdfdadec6477292b1d34477bfac8.nq.gz
    ├── 8a85a99b4a5b5e63d1602b2838259fcc1384d430.nq.gz
    ├── 8cf84552b919fa83bb0e005d60345dda5d267ec1.nq.gz
    ├── 8dce898d6c60a8315a8c0ec89d026e501d42232f.nq.gz
    ├── 90c39561d233c2847763f3609a4803d94c3e49b9.nq.gz
    ├── 91186849a7607d9abaadbf9766ae7feb81a8999c.nq.gz
    ├── 9201bd62d5aeb7bde2d635f4597196c80c224c46.nq.gz
    ├── 9225f23783c1d590bdaa75f16ce75031e172cdf3.nq.gz
    ├── 926e7d56bcca6dc03685c3ba714e2b6b607a3cd5.nq.gz
    ├── 94e932a323353026881ea99cd82fedf1eb015c94.nq.gz
    ├── 991bd5f2c189a6e2b47dcc25dc33068fab5cb554.nq.gz
    ├── 9a1d0f15989f1201602821be7544cb34dc1a1d1d.nq.gz
    ├── 9b7cb4af38a3bcfd7aea8919056099ac0d11eee9.nq.gz
    ├── 9e1db33a5c14462a99bfadf580f59aa863f3a891.nq.gz
    ├── 9fcc5f0d1f145c20e9e77fcb19ca8955234216b9.nq.gz
    ├── a0f438aa000fc7849084f7224021238c7525dc9a.nq.gz
    ├── a1be322dde14444e347639de67863deff59e4e6c.nq.gz
    ├── a205963815cdf05909e092d4aa1b0f0f9a77372e.nq.gz
    ├── a2bf35eac4eb18dc0c2b735b0a60253bc3a06df0.nq.gz
    ├── a2fb7d1d1e29e529d153ed07474d2ae9d72b85d5.nq.gz
    ├── a3d614388b0fd5b7688ef94cf26773edb07a3e94.nq.gz
    ├── a76ffa9189c572b2d611a446e619d41de230851e.nq.gz
    ├── a7d741bc5327626353b72691f2ec025a5ab4327d.nq.gz
    ├── a7e76108bf4fc62dce45600f52b706b86df22849.nq.gz
    ├── a84a852f5a7cc90761c7327dbb0303563ce412c0.nq.gz
    ├── a86b00d1602dbfcffc70be1254d0dce09cdccfbd.nq.gz
    ├── aaef5d91021aba7ec65c78892428a2720d67bb57.nq.gz
    ├── aaf44ed690f0954d4a4825d16a54087f48992b55.nq.gz
    ├── abeffaf64736c9eb93f7f5ddb45f165ae1c185aa.nq.gz
    ├── acd0c872d7cd7f17dc672561a1aed041670e4995.nq.gz
    ├── ad236541042b9fbfe2f2d9e04556ef0227b3ddf1.nq.gz
    ├── ae0040fa8f03da87f47e3b61aa8c72ac65f70657.nq.gz
    ├── ae00a7eecfade1be55545518a6e7499644632122.nq.gz
    ├── ae97951e992d3fb6ce6c531a034867f01be5d0be.nq.gz
    ├── b09c15b1a63508172decce39dbd5519488798f5e.nq.gz
    ├── b15eddfe43cf9d7e6e1cef522acd51f3a014f68f.nq.gz
    ├── b32982a4a7eb6687bf29e284c5602b93465ec4c6.nq.gz
    ├── b40a87003fb8042d98b92ed54b7ec8588e1b6301.nq.gz
    ├── b42f86dd666ada36bd08bdad1eb865c447fb1e0f.nq.gz
    ├── b4b125ea8147c8b52139ea73c2d5f9aaecde1924.nq.gz
    ├── b53cb9bf337beb29e5a7499942aa89eff062deff.nq.gz
    ├── b63e6d6cd7db550715741244ed275e734d4259db.nq.gz
    ├── b642e0fe4f2c9e526941cb71bb95e7ea058842e3.nq.gz
    ├── b68fe3f6be1706df111aec8d5c542f7f8c7954ca.nq.gz
    ├── b691d42d573bc8d237ee197b8376bc720adbdd3e.nq.gz
    ├── b7c4492d552c36e50ca149a42178a1a7c3010c66.nq.gz
    ├── b853cac360ac8f40dfa98f24a82744c41c87fbe5.nq.gz
    ├── b86fce64346d94939423122d1ddc5aada201696f.nq.gz
    ├── b94de3834429012ca42a6f54896f819e90b6528e.nq.gz
    ├── b9b8d34e267350f42f4a0cf566b3517cff555241.nq.gz
    ├── b9e0ac0bcd80089538325fd92da017649f13d4a5.nq.gz
    ├── ba3f767e77dea8fad64c530943d264413c1cf7ed.nq.gz
    ├── baca15057ed18cfc5243e80c75958495a55fcf5d.nq.gz
    ├── bc00a398c98260b64ff87bb02b6494805bc13ac1.nq.gz
    ├── bcb59dcba84730173687357542e1274a453c2f66.nq.gz
    ├── bd3d50d2f5327cc757afa172195c8d065025bb11.nq.gz
    ├── beb0a7a4d370dbf42fad3fc117c74d0c22891cfe.nq.gz
    ├── c0dea73a685e2d2f5522220293c96ff837929662.nq.gz
    ├── c2a7918f94ff212408978d3b6c1ea67a24bbde98.nq.gz
    ├── c2cae166f90794cc89bc5e469c09762747cbf25b.nq.gz
    ├── c30680c898fbddebbfb3c51e608d18b8878b3f82.nq.gz
    ├── c42701b8e3fd466ee853fff3d9f41155595ca644.nq.gz
    ├── c6166897d681f46ee56cebc6f6bd34cbe310be9b.nq.gz
    ├── c6c26deba4f86b9541712b67a8632ac94330099d.nq.gz
    ├── c7073ab123562dcc2cfa6cea5fb28d73a23d52a5.nq.gz
    ├── c78c487deca3e5ba3dbe34bfa304f8e69d58ef12.nq.gz
    ├── c7f13dad80525d7e18acc8cf8fe2d4819febd798.nq.gz
    ├── c832d6f3e02034e7498a6701c8426b9886f5557d.nq.gz
    ├── c87ebde1622176a4a6da9dc801c6536fbce9917d.nq.gz
    ├── c8894513862138a79665603ff6afb651378d9e10.nq.gz
    ├── c96f83d02c306abd86b5d9d0ca91f1a9c6a076ce.nq.gz
    ├── cb1d4a45181da5a2b35ea447115b307f2319c24e.nq.gz
    ├── cb211a73603f85fe6e7318bdfa19b4dfa2118c02.nq.gz
    ├── cb29f688bf7a7698ec406dd388df2cbd95b45020.nq.gz
    ├── cb2e260b12718e0e74ef938e8b6ac18d3ec62299.nq.gz
    ├── cbb75996b670881b6c66203dd137edbb733774ee.nq.gz
    ├── cbb9e9839e6e2da45b6456af19cf94c5183ddeef.nq.gz
    └── cc95b6f4e2e8da68151825d82440ba01437126f7.nq.gz

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

[block/artifact-swap](https://github.com/block/artifact-swap)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
