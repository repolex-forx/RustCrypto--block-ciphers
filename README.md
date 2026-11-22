# Repolex Knowledge Graph of RustCrypto/block-ciphers

RDF knowledge graph data for [RustCrypto/block-ciphers](https://github.com/RustCrypto/block-ciphers), parsed by [repolex](https://repolex.ai).

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
rlex download RustCrypto/block-ciphers
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c69a235c1289b8743aa66db6e6ed1bdfcf1e956d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── c69a235c1289b8743aa66db6e6ed1bdfcf1e956d.nq.gz
│   └── repolex
│       └── c69a235c1289b8743aa66db6e6ed1bdfcf1e956d
│           └── chunk-001.nq.gz
└── blob
    ├── 00078c83ad60a158d587091e2931ce3cc9b93a7b.nq.gz
    ├── 007f4c9ef2ea96fdb8d44887d07d4c4f8785d355.nq.gz
    ├── 023b7dba0974deec1cbb8b63857116b5324da8cc.nq.gz
    ├── 036d7181ae4f01362d2443a086e83b52e00c8c47.nq.gz
    ├── 04778ab4007c44f295f73ae9e0dedc6dcb13e01b.nq.gz
    ├── 047933399cdb3b7d74db44bbaccc7e1ca4c0fecd.nq.gz
    ├── 053704c1347ac0b4a074793fc5d4f9a33bd3d455.nq.gz
    ├── 0591a4a43132b56d4ade7f51674936e656e4b87f.nq.gz
    ├── 05ad2e61ab8148c757106e3ae8edccf99d6c4bd9.nq.gz
    ├── 069bb21ec1c2251a44cebc4645e1278afa2fea6f.nq.gz
    ├── 06a70a888853068d4ce9de3f38a5355c9da0a2d7.nq.gz
    ├── 0a4bc45132f393e534c597fc92eab230471f18e6.nq.gz
    ├── 0b266bb6924c3589b81bdbd86b3bcf01a903277a.nq.gz
    ├── 0de24dde24254438345e6c46c4fa63747d4492d5.nq.gz
    ├── 0e0f2533cfa8ba93447026fdfc5183aa866275ac.nq.gz
    ├── 0e9a9cd2bf88cc67851e7581b72d83497c929d8d.nq.gz
    ├── 1105734da89fcfc067568e51639d3180ce0f1e9b.nq.gz
    ├── 1136b2a919a5492f502945ab531d657ef246075b.nq.gz
    ├── 1166c59d204d650ff83a9b5dd67d40383026ce31.nq.gz
    ├── 12db0da26cb059c59ea50bfdd706569a796e3f57.nq.gz
    ├── 1307b47b5ab16056f0b98b1fb4a80177ad29b505.nq.gz
    ├── 135d8c3f9094d18eb7da977d7b2a8898f9ef04df.nq.gz
    ├── 13eba95f4983167c6f8182b0d8f13be15216b524.nq.gz
    ├── 145c2b3c07f6ef9612b0e6bb03bcc8b51c994ed2.nq.gz
    ├── 14f2f73581b1257fc974a09389787673bf118ace.nq.gz
    ├── 14fc5645cdfbdf4c0c2a4cd32c082e198f9eee51.nq.gz
    ├── 152901b909d6e643a0fdc8813779eafd469a30cf.nq.gz
    ├── 16044019d3f8504c79ed2e480617fbbc6585a6d8.nq.gz
    ├── 16f8065baf22d9594e64b705004c31584c51f36a.nq.gz
    ├── 1a56575cf6de20a85e13e45407528cd146e437f3.nq.gz
    ├── 1a6e2927cdf1c0ea0adf9b266584bb4cd34752d7.nq.gz
    ├── 1b1cb4d44c57c2d7a5122870fa6ac3e62ff7e94e.nq.gz
    ├── 1bcf120ae49f1da2de5aa705cd3ff8de5f9f5baa.nq.gz
    ├── 1c2bf454dac5cc8db7dcbc4a297ab7e4525ae59d.nq.gz
    ├── 1e2ec5756840d8f2765a31515dbaf907a32f4f13.nq.gz
    ├── 2029d081a6bbc4442190912211ecb1fee5d0decd.nq.gz
    ├── 20d2d7a3da06be878f780dc9ababf3045f63e1f2.nq.gz
    ├── 20eb48a1420299c16dbc393d995d3942876c5d1a.nq.gz
    ├── 2104abdcbdaede382cb2474cd6a43c080e224ca6.nq.gz
    ├── 21a207fb3eb160466bd6cb930e8c1bbd0591db18.nq.gz
    ├── 22f9556e15f16790cd622e7f37607f1b14afa069.nq.gz
    ├── 2437662e5bd1644f366f24bb3e76932352785f16.nq.gz
    ├── 24a365a5c1ffca912018a968de59781f3763bdf0.nq.gz
    ├── 2510857b6d36aabe6a4b5cd68c30982d4838e1f8.nq.gz
    ├── 2538b09c22020ca21e162fc6cf97266c73516fd0.nq.gz
    ├── 257ba9ac108ca3fdc090cd6300849671e659fa03.nq.gz
    ├── 28d3b18b5f898b44cc9b06980fa565bffefd5aff.nq.gz
    ├── 2a45f565f73cb5e40b2a07e2c725c2d0ecba0a66.nq.gz
    ├── 2a7976ca50b603481b75a2e78dd49cc36a30b4ba.nq.gz
    ├── 2ccc73379340654223a666284bc6854f7c2684fd.nq.gz
    ├── 2d06e06320bae6bb7f5f44615dd43edb0f990f8f.nq.gz
    ├── 2e8b8501afbfbc02edfc52474f6ec2898112b13c.nq.gz
    ├── 2edc2bce63762ff0d0344d66670a93982c7a0783.nq.gz
    ├── 2ef3c18d4f4cbf91c491b4ee5a97918f2db6d94c.nq.gz
    ├── 2fb5984f44fea73e6dfdbe5a23214d7d6a170672.nq.gz
    ├── 303df83e81117078ddf6b666e7add06114967803.nq.gz
    ├── 308e44c2a1a738ea2141f851d324b2c433a64655.nq.gz
    ├── 325c4c349459c535850eb71e545b1f155aef29ae.nq.gz
    ├── 327d4ec35f1247df3ad5a13ade4dcac0bbff14ff.nq.gz
    ├── 32a173227ba512fed069288b5048c7f2b6476b36.nq.gz
    ├── 344e58c766f8a6f91f3d87c4354b49184e637d0e.nq.gz
    ├── 34c5cd732c8f7b45f1555c8104549ae7b9ba2ea8.nq.gz
    ├── 36218ed1a725513020bf17a4024c7fa5bf50039b.nq.gz
    ├── 393be8627aa89aec4c7a96287549f19cca7492db.nq.gz
    ├── 394b496c37bc65c34d7b472caa46ff32b0fc8b46.nq.gz
    ├── 396ec68a22d1c9ba30d8da1542726bd9a505d2cf.nq.gz
    ├── 39b36feae3a38d78944a9a011e30e7ddec82663e.nq.gz
    ├── 3a31f95257ea2861432a4698368b6727da86bf56.nq.gz
    ├── 3a5221bbef9d9cfb3d32d37e36c07b64a6d9ef15.nq.gz
    ├── 3acc642dcc08a742aa6b36f054c373fc42917f0b.nq.gz
    ├── 3b0382bffe01317e8b167013ee96d5eac4d31048.nq.gz
    ├── 3b73c41cf46d494f8485db1a1342b8d3313f58cd.nq.gz
    ├── 3cb7f1b31aba345881b8d31043a89f2e78e2290d.nq.gz
    ├── 3ccaeeb4c2a78b1574d2c58974caa80d5374ef3d.nq.gz
    ├── 3e5dfff2cb64e8c4e82e61454db194a04c4ec237.nq.gz
    ├── 3f3b7005e6e4fc69c6daadb710943ff7b2a428bc.nq.gz
    ├── 3f3d2276e96675221eb41648847ec063a1ab9c20.nq.gz
    ├── 4021c12b4179b3561eac754afaab6143ab94dbbf.nq.gz
    ├── 4135009c85a23ee5d0a0f0aa61e025de06dfb74e.nq.gz
    ├── 413633ed599f8300adfe4395d60269885efea8c5.nq.gz
    ├── 42704c70d2d3f605099d390fef4bf95bdf4e0226.nq.gz
    ├── 4288990fd1d7dd40b3f2b367d15749204698b4f0.nq.gz
    ├── 42b75e5fff841af91ab38d6b6ff32934d4563a7a.nq.gz
    ├── 432eb3ef29a69a2a76972ab85ee0a37a00f5face.nq.gz
    ├── 43325a012042cc3b43646ccd825c89f35565e1aa.nq.gz
    ├── 445adc390437bbc8905eeba3b27108ac38ebe760.nq.gz
    ├── 44bf0bde1084bfbdddffe822ff77f73cf2288b4e.nq.gz
    ├── 44eba9dfb70442f3ac27d8c7298b8423241eb105.nq.gz
    ├── 4526c001e721eb40876d8e54fc9d442b386e6ded.nq.gz
    ├── 46075e788f9782b881ca3eb23f9804876b1c89cc.nq.gz
    ├── 460d35b622c18d845f2289b68ca80e9418a4c3ab.nq.gz
    ├── 46eb01ebe2d771ed3dd658c0388f680554b70965.nq.gz
    ├── 47f5ff6188d827efcc955fe39ee12f745dcf0920.nq.gz
    ├── 4a7802c0bf81b39beb0d665f5c845be98c5e88f7.nq.gz
    ├── 4aaf46faf4aeb34ec0c57cd29b67c2b1b6c8a518.nq.gz
    ├── 4b01945791ea229f7c116b0c8bbecf086964770d.nq.gz
    ├── 4ba0c921637372a041eb09f4e32937e6645e8fc3.nq.gz
    ├── 4cafc86ecb37d1a604e7159e87399a961a45840c.nq.gz
    ├── 4cf57b94da479b260dfe3a1a3063a880732b09e3.nq.gz
    ├── 5013c62d9fc3423c1bd70d4a581de0afbd99bb7b.nq.gz
    ├── 514340c56e1c580131953f2ad3b9adcc4eaa3dd7.nq.gz
    ├── 5434e0640b0ae049bef2d0fa3eefce9a9f2d5ef7.nq.gz
    ├── 54c086f8699078cd28d230562a96fd16b008dba8.nq.gz
    ├── 55e17180da3e4eeb8957ed9a9e98246b11efc9c1.nq.gz
    ├── 5664066faf28ca32eefff83a04eccdd97351020f.nq.gz
    ├── 573db22fc5b6b12d2b7d5003cca94cf8d2e73d58.nq.gz
    ├── 57ae27dbf51c34516e1104fc8af27a8c880b4ee7.nq.gz
    ├── 590cdb7ee05970c05126c566229d99f27b65e569.nq.gz
    ├── 5a50b7f98af55f170e1fdf31eb39caff1e628297.nq.gz
    ├── 5ab1014151d3d2bcd37964b67abb967e10e88f29.nq.gz
    ├── 5b8501f8fc3aa08b99913f783582f0dd1a414846.nq.gz
    ├── 5bac66e1d4036c03d18877a1fb56d2dae3349fa6.nq.gz
    ├── 5c73fab96c6c028e13eb2c0ff4c55673f6f45dbd.nq.gz
    ├── 5cfe25c673986397346ac3448ede531804253452.nq.gz
    ├── 5e2685de0d8f857ca3db6c911db5105821b16438.nq.gz
    ├── 5f8844dd7ed3d22c1df3fc09c85c173b12a71f09.nq.gz
    ├── 61b068db8c346dbd1d4ce87897f99334efd473de.nq.gz
    ├── 61b9058d9bb3b494e3faa0d7a465a0e2ec45358b.nq.gz
    ├── 62f35eee4aabbf7de1209e8ba322468193f4ffd6.nq.gz
    ├── 6303251b251a71989d8c6ed5c9cf6fdb2facfbd6.nq.gz
    ├── 652489d770c5c3d8c43f94edd193a7889cd182a4.nq.gz
    ├── 6524ef74a0f425c42a2f088279620ca75af1bfdd.nq.gz
    ├── 65d4373dd1c9c2dbe6869cb1c99204effa51ebab.nq.gz
    ├── 66a9cad09b4e4f303bbc2f5c27e14938f7c5c865.nq.gz
    ├── 67bb90371c284f7fc2b860dd037b594eb4a8d891.nq.gz
    ├── 68bdb357f274325e52e11ada59a65b54ff28bb3e.nq.gz
    ├── 696743d1aaa4e5557826cd667785201ddece394d.nq.gz
    ├── 6969436b509377cfa1648ab6797f39f5fd8d0b6b.nq.gz
    ├── 6aa9bce4656903a57ffed26c7a8d6ccb5d663a21.nq.gz
    ├── 6ab20fb3903ead51f5b08d9db917398b198ffbed.nq.gz
    ├── 6af7d7ceef8dcf1efd4b5138186f8e115d946ad1.nq.gz
    ├── 6de73b7d132af9552f8ce29ccd51424a6e84975f.nq.gz
    ├── 6ebea87dbaaf1af6a549320eb8bf9f7831cfb5ae.nq.gz
    ├── 6f7bf4d8d42c8aac04ed1495cdf6fa5eeefff927.nq.gz
    ├── 7183366086c9f37e4f928202278de16d7227fdaa.nq.gz
    ├── 729f11451c13a2a6eeb6621a3cab1a026062aead.nq.gz
    ├── 734da5c9ea8159c0cefb980e1bf6b4c246a24a9a.nq.gz
    ├── 756a0f2ca369eafb0d8ff53ba9e25f1980391e12.nq.gz
    ├── 767d3264ed76f54e04f2f012b7a778b7e7a879d5.nq.gz
    ├── 76ddb0374730a20fe5f927eaf8db3ab2d411f081.nq.gz
    ├── 7800280e0c752e2ac93560e8f2be73f99a2e9286.nq.gz
    ├── 7812b2943b067bb787ccff45f1c8efa14e042764.nq.gz
    ├── 78173fa2e753d614bb0aa5ad125ddbbe70b282c4.nq.gz
    ├── 78bc3494e4223b3b4f09ca39a187bf8c4dd97824.nq.gz
    ├── 7b171967aef2b458d27c111f6ba3d74a1addcadc.nq.gz
    ├── 7b54516eb5342c759bd4859e6ef1b571d89932a7.nq.gz
    ├── 7b990b07a16b104febcc2591873dc2be6e310687.nq.gz
    ├── 7c863351925c1187db807405bf2cd73e0037368c.nq.gz
    ├── 7de5cca3452ba0a0555fd07e65ae26f035ad69ed.nq.gz
    ├── 7e197c09dde9dbb7e85219addfe528b2c9fc0684.nq.gz
    ├── 7fbff7abbbc05f438fd443b002d833f13e4c8aaa.nq.gz
    ├── 7fc59329277f849441323749e2e823aa0f2c038c.nq.gz
    ├── 80ed305c818c414128a1620ea79994b41a26901e.nq.gz
    ├── 8170ac08e2cb93ff21cf9b4415cc1e2b6cc89622.nq.gz
    ├── 81ba654ad259b62f61d453a667cc492784027d40.nq.gz
    ├── 83ca1d79d924d27198cd8209058439f119d733fe.nq.gz
    ├── 83f40153fd5eb29050e2aebef13eb145009fcc49.nq.gz
    ├── 84f2d33c59c99ca919df8f6c679376e9b0634901.nq.gz
    ├── 8563cd42f592c7fd489e8defc69ee89c046714b3.nq.gz
    ├── 862df51383120f4fbe6365ce38ae8e2894cf73d8.nq.gz
    ├── 8663f7de5dd7a79b04f7fcc4fea0046e2659a1a1.nq.gz
    ├── 88227ec1ad48c523f38848202e713e2157cf4f1e.nq.gz
    ├── 88d5ce98c6ee3ef5aa152d21f15865fd8bf34605.nq.gz
    ├── 8dd47a210894f8c6b049a85eda748d6d25a198de.nq.gz
    ├── 8f19f54362bc273c54ac58d1bd8ac7a298c430c5.nq.gz
    ├── 8fc434810a1d39973553fad3fe00f8219e698334.nq.gz
    ├── 9019275319fcd7ef8de39aa7f135283af1f678a1.nq.gz
    ├── 905e0c1cddb7afe1e568cf3b3640d624e1555fb7.nq.gz
    ├── 9111bb1d3159fae41858dc87478aa05592f718b0.nq.gz
    ├── 9124418849445cbaf797d497cd3bd91d395c982d.nq.gz
    ├── 93e5ae77fd8efbc8204e0405eda860f44b407e17.nq.gz
    ├── 94700758c3ae443de1f62f6fdc7c9a70ed58e6e0.nq.gz
    ├── 950456d4438782e81ed450e660e3c3b9ff2bd98a.nq.gz
    ├── 954d6a84f812cbc2b3f0f600c39be6f522ce57fe.nq.gz
    ├── 95edb5c31729d54eeda0e4f841b3bde21b44608b.nq.gz
    ├── 960c1d99f59c13869e4f98a20c634112331056f4.nq.gz
    ├── 96c43f11478c8c4b34154ed4ab7d731b74ecaeec.nq.gz
    ├── 973f827d3f2bea3d468fa1260af1765d2e7d3021.nq.gz
    ├── 990449494427793b380fc2c43ae88ad1d06bba5e.nq.gz
    ├── 992beeea179e556d9521bf8c9898e76fc0080ca4.nq.gz
    ├── 994f89c5a036b7c2980c608b376a0007aa68f2b1.nq.gz
    ├── 997f697192a2e27406d2ed2bc1136820be1f80d2.nq.gz
    ├── 9a9f8c0802a06e027cb66219de733ff38e1625d8.nq.gz
    ├── 9aa3e7b1be86b25031972ded4cc8159c43b15c06.nq.gz
    ├── 9c1bd72c601a5bfd34eeac6b0f4a3943d84baab2.nq.gz
    ├── 9ec7de50ff4f25ceb85dfee7ceb83b53f386c974.nq.gz
    ├── a3013ac90ed76e944e11790e62be650b6c6fa548.nq.gz
    ├── a37a9ff77d317e7695d7475084ac31fbbf780151.nq.gz
    ├── a5bc0ca134ab61a34e11254f67fb864a470f0008.nq.gz
    ├── a663ddf6cad384b941ee69e701b789795eb87023.nq.gz
    ├── a68412c54bc39abfab7a68bb038b1c983c18a01c.nq.gz
    ├── a7b6cda82cca8038600b5221be660008236767c4.nq.gz
    ├── a85fb15a3ed5a7bac7c6f330c94d3f85a6c6eeab.nq.gz
    ├── a955a795125d699aebb125031863151ba97ef576.nq.gz
    ├── aa0f432f23ff0d857abf9db7aa1a62c9782429c0.nq.gz
    ├── aa324c586f6691c56e9a77f1e288e37f33a4ffea.nq.gz
    └── ab09c73215d9ee219454a3ee05c04716d3a6373a.nq.gz

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

[RustCrypto/block-ciphers](https://github.com/RustCrypto/block-ciphers)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
