# Repolex Knowledge Graph of hugapi/hug

RDF knowledge graph data for [hugapi/hug](https://github.com/hugapi/hug), parsed by [repolex](https://repolex.ai).

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
rlex download hugapi/hug
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e4a3fa40f98487a67351311d0da659a6c9ce88a6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e4a3fa40f98487a67351311d0da659a6c9ce88a6
│           └── chunk-001.nq.gz
└── blob
    ├── 064d1c2e1877664d2e133052c841877e977ddad8.nq.gz
    ├── 066af8610a315cf062938cdae69f94aea42e41f1.nq.gz
    ├── 06955f6233604f22e9847b3352d429c022b29dfb.nq.gz
    ├── 07470c01b569fa8a53acea60c6fa6c6aa5831885.nq.gz
    ├── 07bc70eb8db760ea72dd8465814a11cf40defa0e.nq.gz
    ├── 09aabb6d0de13c9a3f51b2b6aa59512ed82574b3.nq.gz
    ├── 09d88444ce9c79110fa342f603b7ba5513ac8705.nq.gz
    ├── 0bc5d3015f5bb7e6e415ce3c67b158627c89bafb.nq.gz
    ├── 0c4b261c9ad47e7b79df31d2b282a2d5b2b02041.nq.gz
    ├── 0f28b346e00b52339107e2c2aef89d032f69635c.nq.gz
    ├── 0fc15531eefa24ab3a2a6887139fbebd4d89c8b2.nq.gz
    ├── 10efcece725550ba3dc9e31436b55fa6d1b98b4e.nq.gz
    ├── 1111b4722423aa25bbf3b642ca1b776745970cf7.nq.gz
    ├── 11d0e158d0d65627cb772c33135454b792540cca.nq.gz
    ├── 15829e7fdfc211adf8cc6c17dbead94dd5d6930c.nq.gz
    ├── 1668d64c7b2561604ca899f32533543d25ae6ce4.nq.gz
    ├── 16dbaa5bacde1309bfdaf687b30b5d63cb5d14db.nq.gz
    ├── 18891612268324d274ca795797de0fa340fcd052.nq.gz
    ├── 189ee6a924171e4113083982575784df1944f002.nq.gz
    ├── 1ae04fd5d36a199041ecb44a7b029d801ed234c8.nq.gz
    ├── 1e0bbb71b14252cf0429769430e5051429986cac.nq.gz
    ├── 1eed2352587e1228d7c76066dd48b9681a6aefba.nq.gz
    ├── 1fc478842f51e7519866f474a02ad605235bc6a6.nq.gz
    ├── 20ffa319d7f00bc2958637d019da8c876473a299.nq.gz
    ├── 219e49fdccbd6a3412d1c7450925ae002cbfdd24.nq.gz
    ├── 24a3f264dd0e940781af02c29d0962e12f5d6e7f.nq.gz
    ├── 252029ef71db6b970a45ecb356593f30e86932d5.nq.gz
    ├── 25b2445f7199fdea5f60abc5b84a1e5528837d7e.nq.gz
    ├── 2600bd3f15847adf2efed331c26ca3ffa1a934ad.nq.gz
    ├── 261d6f1470ca6af9de46d86448326990f8ab8f96.nq.gz
    ├── 26d7d4d7ce92cedc9aa04acae33900619ef0d91d.nq.gz
    ├── 27f726ddb8a205e828c8bb109615c388c32ffc47.nq.gz
    ├── 281cd43dbdf6aca2282969e7e17f7cdc1ece03e6.nq.gz
    ├── 2a46086583fb042fe019826a6cbd4c158a936c29.nq.gz
    ├── 2bb618a0afc790ca761d0dd2c1139a7305b10b5b.nq.gz
    ├── 2beb22cf14c764e7296e30b4b901db502a502862.nq.gz
    ├── 2d2cf920e7e8f17d67b378df3cb68be52304c1a0.nq.gz
    ├── 2dae81adbc3251c8b45cbf0a87d98aaf2825ee04.nq.gz
    ├── 2eda4c3759d12569a05c1eac92646880d179dd82.nq.gz
    ├── 2f79787e28402829e0b1ad6f76459f3bc899cafb.nq.gz
    ├── 3023c026841c3c076437099e498e980af787a361.nq.gz
    ├── 328feacaef7098f00709d5a1873e078914325e5e.nq.gz
    ├── 33a02c929c06daef3271245b13ff133c9a2009ef.nq.gz
    ├── 350ce8f6746574a9b0d84d241261132ea3d1e892.nq.gz
    ├── 362b1fe6a8ed2147781e3bf35c791d0d1c5a1a4e.nq.gz
    ├── 37413c6ccbcb34fb8cc447b144438bbb86859951.nq.gz
    ├── 388c280155b235ef3abc515d0ddfc0914ddb736e.nq.gz
    ├── 3acc78913ae8fa2a8093c48d6d3b9c6a46269f69.nq.gz
    ├── 3c1adcc6b209faf8b3b550ec7b213bf81f8e7c99.nq.gz
    ├── 3cccea619fd9c0dad6042d7abfab3682dde4eb3f.nq.gz
    ├── 3d060614db21a45942bee2f23c73e0e81e01754e.nq.gz
    ├── 3eb7c874929af23f6690a5c2625c6d6d2715a473.nq.gz
    ├── 3ef8230c5436d6dc6450294fc149d3bf83fc3754.nq.gz
    ├── 3f1bb113a235c8c6ce0ae6d704dda68f34ceaad8.nq.gz
    ├── 3f430133c78a34f2246f34fbde7055ead54f33ca.nq.gz
    ├── 3f9a8a6774f9a9f61152005f684d1d34274de990.nq.gz
    ├── 408249a7da5c80cc39924f8e2ef67e254bd58941.nq.gz
    ├── 4142d01c78667725311243f2f5b80cf09011d448.nq.gz
    ├── 4176df78adda177e9bbd106651155e825b7059fd.nq.gz
    ├── 423b84e261b3dfcd80b193f9ec9c6ded133fca8c.nq.gz
    ├── 42bcc1b6431e40fa6d49b5440b0dc072827bb190.nq.gz
    ├── 443c83afaf229fa35b9b51557413e369aec9cd16.nq.gz
    ├── 45e1e284557e657420ed4ca228684567e7dccb2c.nq.gz
    ├── 49159922def70bb8943e209ac942926bc4752fb3.nq.gz
    ├── 4936fd615b7aae367cb497e2653a6768d634ecc0.nq.gz
    ├── 4b1f2faf512cd91f4e7ea22f90e560a2d55831a3.nq.gz
    ├── 4d17c9c89bd9abe99dc26e15906b67d914eb5f5d.nq.gz
    ├── 4d8f75277416e4eb87f3f1a13317e8b28696fed8.nq.gz
    ├── 4da0554ad1c30db5a31a66524d04b23a77072c5a.nq.gz
    ├── 565d32acf61b206eb76723820ac9c18dbfdc6dd9.nq.gz
    ├── 56c3b96c79eee5a347d243fd94806093c3641f2d.nq.gz
    ├── 5746cf8d92512e1943ebda4b2864a0ac547bf2dc.nq.gz
    ├── 5752fea38627d3451f5c0891415bff202e46824f.nq.gz
    ├── 58ba28d267273980aeb03643b0231718f9ea7002.nq.gz
    ├── 5b1dd096da6399e4bc08c1165034bdb5d6e0b83a.nq.gz
    ├── 5b90eeb2c8dd52ca7c917b4fcd336a005cb335e6.nq.gz
    ├── 5dd8e6b0b9eb94267a6fe9c6a202e863311f20ce.nq.gz
    ├── 5de6f60b85fcbe914dd89055821b4593a1bfd145.nq.gz
    ├── 5fe9b1bf430cbb78642c3e4d25ea7e0c1ff5eece.nq.gz
    ├── 62d638e28d1797f99eb7a82a7a18737c4bafe691.nq.gz
    ├── 65cca92eaa90a25a5c0590e19a21bbdc9f0b099b.nq.gz
    ├── 6624a30209056c79817923f13f8e0abfbfb1d8e0.nq.gz
    ├── 6b0329fd9db8ab3480ed00f7c281d0bb4f7121a6.nq.gz
    ├── 6b36318f7231bc9f8c335bf51ffd40db3efe4c23.nq.gz
    ├── 6e60dfb3bcc1bccc10e7d1abc471fe162e2bcd2d.nq.gz
    ├── 6fee467c675e7bbb5bb54e0669ac8495f7aa7757.nq.gz
    ├── 72e27931bf2628acaecc14b7ebb27e44e36a2ca1.nq.gz
    ├── 748ca17d29249fc169b575ff6aa6591b963027a0.nq.gz
    ├── 75c553f94afadef3d131b0d46e2f57d1840ab1f9.nq.gz
    ├── 76b4364f1f92d020d70a6ae68dc4072531a3bd6e.nq.gz
    ├── 7736b95930068a89031ddb3a85ab488ffc1c3c6b.nq.gz
    ├── 790f0385b0140e25d69eff57aada61eb4dd8e8b2.nq.gz
    ├── 7ac32e54942b36212a102073c1cf7876e44b38f1.nq.gz
    ├── 7b0107a7a6ed4014f2bfd6607c860d691a7f65f8.nq.gz
    ├── 7b0292a6f3f78ea4e1964bd512d620d58bca71f7.nq.gz
    ├── 7db9393bba7081595fc7f8a1622301fa2002631a.nq.gz
    ├── 7e014caceb5da5bbce3700041b4108fc1f845440.nq.gz
    ├── 7f092d88e4282f491d64b14f07c07c05302ee4bd.nq.gz
    ├── 82010074bd0f8f2d56c0e52924b0cac83b6acc46.nq.gz
    ├── 843e6ab04e9239eddce75af3b81e6ae54ab02f46.nq.gz
    ├── 859d4c0971d16aa50ad8b2f8fd76273a164ae478.nq.gz
    ├── 88710fcb282b2b4b7ff9db126f1f3d79cce6509b.nq.gz
    ├── 88f2466ebeb5fa54ff891485aa992934556eda50.nq.gz
    ├── 893259871e3d022bbc88839d6714c377fe57853b.nq.gz
    ├── 8bbda22352dffc5921f0ed3ce2b4af81cc712c4c.nq.gz
    ├── 8c4ff562bb08973bf9cd12c37a75c92868e2ccfb.nq.gz
    ├── 8d80fc0f73147a4e59dec6a7dfc65dbed4a3d7b1.nq.gz
    ├── 93f0859767ce6941e095d2144d701a91ce36aeb7.nq.gz
    ├── 94b6faf1f10e5c9a735051b44ebbe105548f975e.nq.gz
    ├── 9600534ad15673c1afa12b75f45fc80ae1484a6b.nq.gz
    ├── 971ded8f7c0b3c1749496b66650541f177ec45f8.nq.gz
    ├── 99100df131034df9ce2b71e52bbdd0016bb51899.nq.gz
    ├── 99fc0b6f25b5e17bf8e14fe5f8df079648c20e37.nq.gz
    ├── 9b899c336f657d821927933f07298d84361ee0f6.nq.gz
    ├── 9bb12ca600a6748a20cc8af238b892db2a7585cc.nq.gz
    ├── 9bcc9015d0e1a0873ca7e10d6ee0150c67605bcc.nq.gz
    ├── 9cddfd6c699e6d7e491158ab176422b98010b985.nq.gz
    ├── 9d8df8a5e705941831cde9b4b00c0ed6ada7f201.nq.gz
    ├── 9f175da79d97a4e06587982179e95215ac7415ac.nq.gz
    ├── a1e35e3906b45c2a2c9ec7020cd5f998cb02504b.nq.gz
    ├── a312c6ded4573f9829cc2b6ca900c1006583a953.nq.gz
    ├── a454edabf1a5888a8d472ad314737275b24a1852.nq.gz
    ├── a5e7fccfa10b883d97864df02798c3b879b4eeb0.nq.gz
    ├── a6167d3da34169833934181fd4a52fa5b7fb91b0.nq.gz
    ├── a67127dffb76c4cd4647b32225bdd310025aad23.nq.gz
    ├── a8c716dc8d807732ed0417868ad297859fe875df.nq.gz
    ├── a8e060974c9849ad3bea428dde446630d0dd0702.nq.gz
    ├── aadd395f8f2f0ddd76f3f03eafc2046f1af1443e.nq.gz
    ├── ab302c207c6f3de8e9646096f5ca6409c4278fd0.nq.gz
    ├── acb3660891b307a91d63ad8898ea276eca7d6d73.nq.gz
    ├── ade7ea50c08f44770a72230011a033f375dfac33.nq.gz
    ├── b0617535a3db06fa6a931cab77fbc2427eaf42e4.nq.gz
    ├── b07539b443471fc2fd0baad390665522c22b6366.nq.gz
    ├── b1571cf5ccf2fd7a0725503545512696486e0700.nq.gz
    ├── b1770e2ffd012e01d849cc5c900fc5bb3c03f2ac.nq.gz
    ├── b61ee09ac3ce82a172373708297977d8d4bbc239.nq.gz
    ├── b66362b6366948e79f50da6877708f25ef86bf54.nq.gz
    ├── b9ba84f6772f7ec6d191cd91ab13039da9ba2100.nq.gz
    ├── ba84e4df6d4352381c2ae94d3c3e431d3cc34172.nq.gz
    ├── be28cdf3bae3f1b43cffcf03a13bdaead6c07ee5.nq.gz
    ├── c063eb9f06afb40888ef8c5e276b38d92bded15d.nq.gz
    ├── c0c9a9df1d6898ce859f8a089569c00f7216c208.nq.gz
    ├── c1565f84d30f7c074f5e7f5a86d704e1f3e26d3d.nq.gz
    ├── c15d7753716f924d526a8177737256399f5ea7bc.nq.gz
    ├── c16b16896c57f4e9aac1c1cd97ba3bc84a2c8710.nq.gz
    ├── c2a5297a15acd83adeba0977cdd2625c29c5010b.nq.gz
    ├── c492909eefc63adafc79ca0fa02562565391a8f9.nq.gz
    ├── c54f0711afe54ebb12cec950ca524d2f4f4e988e.nq.gz
    ├── c5becfa76a6a7bea0af484d4042a2646b4d307e8.nq.gz
    ├── c67e0eb323ea8b0f7b0f8cb1ad81f60360df505e.nq.gz
    ├── c6a59744f4d34feb67f5a3762a279fcafd49823c.nq.gz
    ├── c7672004d82a8c1224ed5d341e098160a0ea2b17.nq.gz
    ├── c7b3004dac19a54e5574f66a668de4bfc2f43c29.nq.gz
    ├── c83626831c6d08931cce61f0e490337270c2a506.nq.gz
    ├── ca2069932b0682996465d09f87f23e34b5c31a28.nq.gz
    ├── d0c31a13235c61ae910be3400235ba0da9fb85c7.nq.gz
    ├── d16bc0e977892e796387f65c38e3368c4717b0e9.nq.gz
    ├── d31f72f6dbbe3cb05ee899b7b82bac1197d91988.nq.gz
    ├── d59cc5d40d029581d0f605042861cb6a70931d3a.nq.gz
    ├── d5c68b583e198b65f6b9fc43d07fe72982ec3029.nq.gz
    ├── d5f857dce2fa7f25f4da00eb9604be2434a7e027.nq.gz
    ├── d64e52d83d349079bc4ef79335e1f3465e38e41e.nq.gz
    ├── d695b26898a5440ac23e3fb48d57fa6ef425d8dd.nq.gz
    ├── d763b2a4f96f4dd1f7604acdd4d2ea276d825a8a.nq.gz
    ├── d8407dcc4e751a98c1c9252cdd9d680130f7110c.nq.gz
    ├── d8b994e6bc342096b0e5d66464da1d7171a5bd90.nq.gz
    ├── dd54693b58dbcbcf2a37858852e42864a65d2202.nq.gz
    ├── dfe6f1176abbc1b415d1612dcef82f91b78aa74c.nq.gz
    ├── e002cb6a50485d5cacbed84918d896af1405e2d6.nq.gz
    ├── e0c03ef77f71dfc7c9b1333941efb2d237a5cc7f.nq.gz
    ├── e1ce207e4c15c83023f0db076793fd0efd16912e.nq.gz
    ├── e20a312605586a7add3d388301468596ec20a337.nq.gz
    ├── e3775e59106039ea4dff7f5f1d913a0e67e22433.nq.gz
    ├── e3a1b29f2652eff8c9a0436cdcec14fe34b289ea.nq.gz
    ├── e60bd0d0cb0bbe8d431abb8836f6cae6d4df7895.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e7bb6c69914c6f11d5cfb44f591839735aa1e2c2.nq.gz
    ├── e8142a64ece031bd1a1fa24f05ae5d488480b222.nq.gz
    ├── ea5227944214c4ded216f6c2304f36a4e72eaa52.nq.gz
    ├── ea5f23c5dfb5c0c46878be3e9888532f31347cf3.nq.gz
    ├── eac4720e4fd1c39e6e1bb97e1337e430681b9372.nq.gz
    ├── eac7019a78d4c392dfe5f6901bceec6814fa65d7.nq.gz
    ├── ee314ae543dbce096220fd3fb7c57e41d9f57299.nq.gz
    ├── ee80b37823e560a5df03f810dcace0d43ba5ed85.nq.gz
    ├── efb6a094ac4472a70a0fa8f7237a390945af76c2.nq.gz
    ├── f0a408adc0008734199c590d9513bc2dd5d2d0af.nq.gz
    ├── f25945be367374eed24986c97361db7341652c3f.nq.gz
    ├── f2addd5bae93aaddc382f0d9443cd67f5893f5ff.nq.gz
    ├── f398665474f7344b1253100653ee73bfd7b6e829.nq.gz
    ├── f3bc20bdf07727257a9d60f119ef81a72b7f675f.nq.gz
    ├── f47df8ba6cd2d6ea5906c4bb758a1a806df15c4f.nq.gz
    ├── f63e89077e0077c5a1410c2d25491b8df8abda81.nq.gz
    ├── f68d3ea540135fbe5563a6ca72721fc59b8a4cb8.nq.gz
    ├── f6ecc6d7b22e667c6f4bf8ae8a7fda229acb95f5.nq.gz
    ├── f7242804448ff4b2f473b97c4a2b021f1d175c50.nq.gz
    ├── f881f7f891b5599d56e2f262f2557211cbef61c8.nq.gz
    ├── f8c5c6f3a0942a6408b94c05f6b1fd0e655c4e04.nq.gz
    └── fd5d707f3b649eb7afda9fbd07b69d9dd1ad9aa2.nq.gz

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

[hugapi/hug](https://github.com/hugapi/hug)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
