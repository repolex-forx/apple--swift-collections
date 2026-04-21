# Repolex Knowledge Graph of apple/swift-collections

RDF knowledge graph data for [apple/swift-collections](https://github.com/apple/swift-collections), parsed by [repolex](https://repolex.ai).

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
lexq download apple/swift-collections
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6675bc0ff86e61436e615df6fc5174e043e57924
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 6675bc0ff86e61436e615df6fc5174e043e57924.nq.gz
│   └── repolex
│       └── 6675bc0ff86e61436e615df6fc5174e043e57924
│           └── chunk-001.nq.gz
└── blob
    ├── 00144c920e68c52843d5f8540657dbc1300f5bbd.nq.gz
    ├── 0088bfcac4c0cc98b7608ed9dad0b0942ec132fc.nq.gz
    ├── 00c37fa27bbc255b5783d65f7325824b38e34ea6.nq.gz
    ├── 0108f015e8d1aa8eaa8126cf0a57f087fb35a7ce.nq.gz
    ├── 01ba2def91bacae8e4aeabce2bf0668456b2665b.nq.gz
    ├── 023c61dd3dbffd1062675b23441092c2ec2bf43b.nq.gz
    ├── 024a4c33a28f759282d732d9575160ef960b3501.nq.gz
    ├── 0253d8e9ca650de79680f2a1c6439ac4eebb6d05.nq.gz
    ├── 02a79ad4f86029b4cc044c3f2dca41a16b14676c.nq.gz
    ├── 0322122d480c14dac478ef5f04a01db906140ab7.nq.gz
    ├── 03950752722ac4f28735b15e78e28a62918f7db6.nq.gz
    ├── 04f609ec884a9f16cb33b5399ea4a4e59788f507.nq.gz
    ├── 04fa89d492b14a740763244c5f979bd4a23c959c.nq.gz
    ├── 05475d8b7854f153006fe496318199ce86d0386e.nq.gz
    ├── 056b6a7a95cd83e2e37e752ce90fea1a59596787.nq.gz
    ├── 058922a9c65278525a0ea4dfa769a4c3bcf778fe.nq.gz
    ├── 05f3e0f2164d933736fb7ead430a2f7231edbb40.nq.gz
    ├── 05fe348c4f0d405d92b49c4187caa7d9d7b750e2.nq.gz
    ├── 06646b03b1fb1b08a52ee48166b78bd096b5ca8e.nq.gz
    ├── 06e0b45321c387c94042a4ad2b6194a30318d2b5.nq.gz
    ├── 077318ae1f54becdd78c94699a190677648d20bc.nq.gz
    ├── 07c638d4d43329b5b02dc6697581669222bb724e.nq.gz
    ├── 07e887c33eed6ecc529ac9999658deafba1164cd.nq.gz
    ├── 082d535a4c71f38dfaaceb25af11834d106d3049.nq.gz
    ├── 095c1d69178e42d668ee65a5f727a55e8ea523a7.nq.gz
    ├── 098501fa367d6123606f295bb58fb1f0d2b3e98f.nq.gz
    ├── 0a17e877d8061df9289777d295671a8f303a68ce.nq.gz
    ├── 0a35043873b66765153513de8f38712e0d52fc98.nq.gz
    ├── 0a4f8b4af4ad318861bd09d0c360685ce51190ce.nq.gz
    ├── 0a7542749a091dd34c5c60b8fe221e4a200fedd1.nq.gz
    ├── 0a993ca4c2e7bd328fc487a29a7846004c81ce5b.nq.gz
    ├── 0a9e5a16062574358db55aa79b9d655b09224a1a.nq.gz
    ├── 0b1a57b1c75a240ec5b0d935c927ba579f728fca.nq.gz
    ├── 0b4f18fbbb4a4aa3c14b6adae509b9b75b95ab57.nq.gz
    ├── 0b8ae382527fd14d203829d9a3df36eaeb13952b.nq.gz
    ├── 0bc2622f007c073cbaec0396f49973d4b5ffa6f7.nq.gz
    ├── 0c36d74cfd4caa92e82f528b90b04aad7d0106a7.nq.gz
    ├── 0c3a2547a7d52b6b8962095f85dd1699c01d59bf.nq.gz
    ├── 0d12410e4ba716869a65340ac612c4bc41d10d48.nq.gz
    ├── 0d2b620d0558ff16f873f2884ae13c33a4b18aac.nq.gz
    ├── 0d7c6d2c875ae7e34e368da0af127abc768f4643.nq.gz
    ├── 0db4d879750df773d5ab7d8a7734584ddd1668f9.nq.gz
    ├── 0ddeede93707c0292f5540097261c2c5235e97b3.nq.gz
    ├── 0e441831bf315219f94b0a3a770b4716d55442fa.nq.gz
    ├── 0e9c10231d2277bbca64ccb66b5490c6f398378b.nq.gz
    ├── 0ea51d17b8936e439d9e6004426e95a0129bcceb.nq.gz
    ├── 0fb3e6dda84fbb210b51197d18b38810679b4855.nq.gz
    ├── 106a27f29a4eb90e1f0468ec7410ef1c1c3796d4.nq.gz
    ├── 10c6889cdebdb38a4fdef9f00ffdae7f3293bd6b.nq.gz
    ├── 11feb6185fe3d17df6a793cee8346005a99d40e7.nq.gz
    ├── 12099b15c32825a2d4d78abcbfe08cd6082735c0.nq.gz
    ├── 1223e00d3c66d1530c802577a14f3ee422a578c5.nq.gz
    ├── 128d20a453c290f9583f809de851034aa7792e82.nq.gz
    ├── 12b2a196541ecef9f7632b6cd801f8c041314353.nq.gz
    ├── 12cd03d8c8e2c2c1a8f64c091cc21ad3465fa3b3.nq.gz
    ├── 1337bdd2f55efbad0dfc3affb4d2bc6517e13128.nq.gz
    ├── 13a96e0caf2b1ebd3451b0bf2b7c57c40bc7a6be.nq.gz
    ├── 147260c5c4c0403c44fcec856d600ce5cef4f8e8.nq.gz
    ├── 16c81eb333355208510506024f20f3e2cf712930.nq.gz
    ├── 175f4730c7aa72791a1f89563e761a5346235686.nq.gz
    ├── 18d981003d68d0546c4804ac2ff47dd97c6e7921.nq.gz
    ├── 1906623a0efe20e0a1e90d1d0e5e4824e88879a1.nq.gz
    ├── 19ea771fad78938775deb2a60110e2daba29f3ec.nq.gz
    ├── 1acce39a6c2f162a926bc2b4e379ed9b5168ae79.nq.gz
    ├── 1b6099cddb36126c85be40f55e9f25b542b81ee8.nq.gz
    ├── 1b6296dd22bd50d74cbd823228c2ebb64fbbd3f6.nq.gz
    ├── 1b8c4ddea672a1f552d3ff81f077208c76f7fb6d.nq.gz
    ├── 1bc8df2fb364033987f6f298ed8dd0c95a44cb0d.nq.gz
    ├── 1beacf84e5b499948995ac760c39c34ebd782291.nq.gz
    ├── 1beadba050499b45511e886aa7a180b2e5dd7861.nq.gz
    ├── 1bfe32d68e1d00ddbafc18e12cca7adff839beb3.nq.gz
    ├── 1bff90527c95443164fbaa752cc28f4cd2d03372.nq.gz
    ├── 1c1010aa68e64f1169b42fc6df2999c6ac10ea5e.nq.gz
    ├── 1c2e680487f1c24ad66ee3eb124de5e872f3bf18.nq.gz
    ├── 1ce0d2cdd9ee3eaa0ff412a461fb1ed00844fd89.nq.gz
    ├── 1d03677caee398865b97e49aad936786e279df5f.nq.gz
    ├── 1d5fe7f123d9a72ff2fc78f334322c9b91a33b15.nq.gz
    ├── 1e1291cdc43c8e0ec0d25627d9455f84843214d1.nq.gz
    ├── 1e1ae26d523009c94bcef1762edcb06def878dd0.nq.gz
    ├── 1e7a60504de091e85e3df16e4778a41a755253c4.nq.gz
    ├── 1e96e57e14683e08e1151ffc3250248f93cb66ac.nq.gz
    ├── 1ea179f2f6ae15f1d30ecc3bb78a02eec5cf2368.nq.gz
    ├── 1eea2934e507e3d9f8cecfa8f75ceb8e9cff2209.nq.gz
    ├── 1f2ef2f759b302bf16c0be88770653f4d8e56bc7.nq.gz
    ├── 2037472d386837ba661d726532ba755c134eeb42.nq.gz
    ├── 205129da4baade8f81d04d3c5e763963d83f88e7.nq.gz
    ├── 2054f885bf2d0519d0ecf599b9a49749c32874e0.nq.gz
    ├── 20e5c30bb84b18af31c0d727f5402363f9e514fd.nq.gz
    ├── 20edf640a2c47c5cd6373650968720037a608be4.nq.gz
    ├── 211d8496facac01bdb619b28cb97639d9330c107.nq.gz
    ├── 2160da266a08574ddea20a0725cbde129d9a374d.nq.gz
    ├── 21ddb4aa3112fdcb7c091bb69004b5931b1db98e.nq.gz
    ├── 21ef158c638343ef9c7b56e0e1d8c2aaf013f543.nq.gz
    ├── 22a6cf3236871a2adb3c6328872e27c555a83dac.nq.gz
    ├── 22ea66069eb1dd1a691182d545b66bcf1a9e0875.nq.gz
    ├── 232c3de3f1b656c23eb82417d3ec77e1fc0a91e3.nq.gz
    ├── 2358edb3028dc55595286b78421c77c8454fc44b.nq.gz
    ├── 236267ffd5bc2e92a8c003d0e245b766be150ef0.nq.gz
    ├── 23c5768ca7bbf6b6fd2ef61ca7141fc724063d1c.nq.gz
    ├── 23f1af41272deab48ec7d0dadf3bb342464a1a0b.nq.gz
    ├── 2409569bd07dc2d197e53ea3ff991c8e6b0a489d.nq.gz
    ├── 24f558757aa7b5725fde6b832138b08790c62319.nq.gz
    ├── 254a5782fba1f92f609db1c5ab52140a82c95fa3.nq.gz
    ├── 2571c483acb89ae6c5262a7772e4613d9ed2c539.nq.gz
    ├── 2591a10e7d719e66615f29cc61c98302a7363783.nq.gz
    ├── 25c4c5ccb948eab55b6073aeb2bbf24b3b1f1240.nq.gz
    ├── 2610822d2f090e7b9ef7fcdc814b33a35d7ba8a9.nq.gz
    ├── 26ba74fbb740b659707e17818bc30adb03d8f3a2.nq.gz
    ├── 26e6292009b59aff5fab6065efae1ca31e3e1f7e.nq.gz
    ├── 2738fa8038597878215d4a26fa884c6af4f35746.nq.gz
    ├── 28120f8a50b270c62a8b97f3e398657f2a37bb1f.nq.gz
    ├── 28285f80f48eb520ce502c42225d76da835ad0f2.nq.gz
    ├── 2829a2c113c47c755625c8521824243cad020d5a.nq.gz
    ├── 2833d9f04dc0d8ecba79ceb941a6169996288599.nq.gz
    ├── 2852c8ee3b65ecd7aed00f96064f0e776502828d.nq.gz
    ├── 28d2b777cb4133b0149216ec3df4a2333fb3232f.nq.gz
    ├── 28f04e767e2112b6f429266b7e1a887957ef93f7.nq.gz
    ├── 2904769d28e12e5df5f6806187ec8bdeb5038000.nq.gz
    ├── 2905a889afa5b74ffed9a4385dfd90852f0820bc.nq.gz
    ├── 292b4f20f30ca473885ed47a72e40c22b2490efd.nq.gz
    ├── 2978718e707d4be0ed3d5ccf82fa7e3e053806c1.nq.gz
    ├── 29beb4253923336612982a70b36845119534e4b2.nq.gz
    ├── 29d697e3b18241df264e0ffefd6630ed6a919973.nq.gz
    ├── 2a2a37ede99b1274454ff67a561ba39b98635e00.nq.gz
    ├── 2a6c0422ee0bd4e95e548eed090f08f155724bfe.nq.gz
    ├── 2a821b726f660992cd157f1724f0e0f57167ab7b.nq.gz
    ├── 2b63dd77767e56097f64d028654550f37149f469.nq.gz
    ├── 2b91055672d71b5bbcab120a89678167c0bb89d9.nq.gz
    ├── 2c8d61f6e0485454e578bbabbb132957f9e6554d.nq.gz
    ├── 2cc80b732e09a148e58bd0e9c31e7676e55d78ad.nq.gz
    ├── 2d1b3ceb7ac8de2631fca37b6b9ff78cdf2af02e.nq.gz
    ├── 2d494def976e16a1c947bc8acb76e45de59efc13.nq.gz
    ├── 2d4a72de32b09c407412f16830c222116486b5cd.nq.gz
    ├── 2d6d9ac468616324f793155106532b8b6bf2e451.nq.gz
    ├── 2d7799c5cfca9f7feb347652068cdc238542234a.nq.gz
    ├── 2db213072506371f5dde38079bdf4e0d0b1263b4.nq.gz
    ├── 2ed4c7f5bacd015e6838da980e2d038af2197055.nq.gz
    ├── 2ef8d9fcc11a7d37ee08209009014b5e55b83bcd.nq.gz
    ├── 2f22f25c89184d6ee32520df9abeb9281126bd31.nq.gz
    ├── 2f8459aa96e01183f67d880a92f99fdb47674937.nq.gz
    ├── 30053ef87b09c4ea568d437f03a4387bba605cd5.nq.gz
    ├── 3013843ea6a61df4f448738cf3fd6ba23fba7715.nq.gz
    ├── 301cfb7ac2503831285cbea135815251a081830c.nq.gz
    ├── 306b99124d7ebd72f639db0c7a416732034f9eaa.nq.gz
    ├── 30893223b8f86ecc2ded0a3f909372e61959b9ad.nq.gz
    ├── 30bd357f8188bdceaf0f899c63e33e6b46515852.nq.gz
    ├── 30da91c1ed5235dec17f627078a88d8e02865b0c.nq.gz
    ├── 3101cb4eefe18728875dc7abc282dc1e813a6e7b.nq.gz
    ├── 314e4067bbb2d977bf6f695c6f4ecbad289ee467.nq.gz
    ├── 31642c37d7891af8702ae42bb8f3bc384b6dacfb.nq.gz
    ├── 31737f0a7f8cf10104eddeea7473e279120f4a39.nq.gz
    ├── 31f371793e8f7dffdeb5a8bd659e052b0e983b27.nq.gz
    ├── 320bcf1f21e80052d419d099a6225fa8c2ad374b.nq.gz
    ├── 3210a7c309d9c025aa65b7002e102080f36bc0fe.nq.gz
    ├── 323c30b72e19ea84e553c1b0cddd02155cf488b4.nq.gz
    ├── 3250016ba8d85c6b4a9261ba0ad6707267f7394a.nq.gz
    ├── 3271a3cc5d9a3c39659f09da7dbf8dc95f4c7730.nq.gz
    ├── 328a34d39f8bf22cbd8780bcfb3c22c76f089941.nq.gz
    ├── 3294cd5a12a221711852c8fbd5ae73e9ab0f9e32.nq.gz
    ├── 331f527acea5f83c2c6ae52509809130f801cc8f.nq.gz
    ├── 331f7856667a9cc1861db88c88ba8b3eb3d661df.nq.gz
    ├── 33222a62509bb77c4c24c4593ecabb890ee7fdcd.nq.gz
    ├── 333c9f56b3608843d878252f0c61df53f726a9e1.nq.gz
    ├── 33769a6fd586108a9ee36b050a5f9376f9972157.nq.gz
    ├── 33d0940e3841b484d1a11ee87aabb3c0663cd7ef.nq.gz
    ├── 33d999d18068bdd32ed60d0ad5a3792c1bf9685f.nq.gz
    ├── 3403a1bd6b85ff8ea9f56410e39da99e68b8e32c.nq.gz
    ├── 340ee001892e8be4e53cf2b3c9f654cf695c83d1.nq.gz
    ├── 3422f8dd4327ee254e64b72553e0da15cfbe0913.nq.gz
    ├── 345ec5dbb63da7905ebddeb2d7c67f22ccc2390a.nq.gz
    ├── 34d6d21e6c94be25fc17f798b987991250b3954b.nq.gz
    ├── 3507ae743162fafea610b86350fb54b0409acd0f.nq.gz
    ├── 35631f44bc3e77f5cf5edca1dc5c07faeea5acd5.nq.gz
    ├── 357456064436bc4bbcc73b908132024144aaaff2.nq.gz
    ├── 35a2af2a516ea8bbb896985b2c6b2e085f1627b7.nq.gz
    ├── 35c286a4feb1e04531d0f515a2169ef1296cd243.nq.gz
    ├── 35c3eb2e4bdb9078ce0d3195356da7d2a1dc8cfc.nq.gz
    ├── 361640dfb68a43f0efd9e15a8a8f555e8147124b.nq.gz
    ├── 3637423b3009129ac9252e888b1274801135b49d.nq.gz
    ├── 367fc0bf665f46a0fdf3c4bf7f4ff5462edfbd82.nq.gz
    ├── 36c61817fa1b853176f6848e87a161dba50e6d12.nq.gz
    ├── 373337e65985bc74212434fc911365ab0d555958.nq.gz
    ├── 373f9d55e1e0d34afcc4c909bf6b9838f9e2a78a.nq.gz
    ├── 38424ffea7e367e5b599c275e67130fd1093f09c.nq.gz
    ├── 38eaa8b20f396001999e2791e106280315910e73.nq.gz
    ├── 3900026d9a84ab6574a63b1b190acd35fccd2790.nq.gz
    ├── 3a7cdb3ac64cb7d4d5c94235c102dfbaa620de02.nq.gz
    ├── 3abfd8b6dca621a09eadfb7ad0f737a0dde1f7fb.nq.gz
    ├── 3b0e264f695ce9fbb0850fabf7d07ec727ea58d5.nq.gz
    ├── 3b1147bcc0e56191369d820aa702ff83078f404f.nq.gz
    ├── 3c0a2d08607d6e96ea2a941bcb03aaa905fbfa11.nq.gz
    ├── 3c4354225ea21c1c564adc5b95ac3099973d7533.nq.gz
    ├── 3c8f99be705806e000549bcc39cbe2f18c524fba.nq.gz
    ├── 3d07b58da45379167691e5afd4c786d338a3be32.nq.gz
    ├── 3d9e0a5287fba9625dbc40deaa78fc42693ccf0c.nq.gz
    ├── 3db7d45538af34219193f914eba90759eb42d3e2.nq.gz
    └── 3db88fd350b16df467aa959bb7e1e3ee0d8c417d.nq.gz

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

## Source repository

[apple/swift-collections](https://github.com/apple/swift-collections)

---
*Parsed on 2026-04-21 by [repolex](https://repolex.ai)*
