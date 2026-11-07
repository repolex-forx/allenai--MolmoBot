# Repolex Knowledge Graph of allenai/MolmoBot

RDF knowledge graph data for [allenai/MolmoBot](https://github.com/allenai/MolmoBot), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/MolmoBot
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 33c0ca77bf6062a23d60ffd4a6859334c4a46d30
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 33c0ca77bf6062a23d60ffd4a6859334c4a46d30
│           └── chunk-001.nq.gz
├── blob
│   ├── 00531e8b959adb72c40354f4c23126184003b63e.nq.gz
│   ├── 0058359ec9899252ede47f3ee03b9cabef34f3ec.nq.gz
│   ├── 08af289c1bf88ec77d01c0e18b98718fa3095279.nq.gz
│   ├── 09543013012dd4041ca6c68d6e9c2d9c2f1f2d71.nq.gz
│   ├── 0b92a893e121638ed7c53ed3b145db3dddfda932.nq.gz
│   ├── 0c354ffed29ff8b2bc778cd4dc1aff1bb7471742.nq.gz
│   ├── 0cc82660924c9ba2009897d60f3bcd2e7bdf16bd.nq.gz
│   ├── 0ce47a4555d657f2ab2b71c4b18a8c63ad05d0f2.nq.gz
│   ├── 0e0a7a9c6184904a8fe6f7a6d42ae304dec4ef26.nq.gz
│   ├── 0f60b88443fb14b857a1addfecb396eba11a9f58.nq.gz
│   ├── 0f8c012afe256802fb49cdaaa5052fc8368b12f7.nq.gz
│   ├── 0fae18447af96411558ec9e46933392fe5ad6875.nq.gz
│   ├── 0fecac23451586dc8571a8b16d7c782526d842f5.nq.gz
│   ├── 13d49d08f1da5981b3849893ea35ec9e9b135e7c.nq.gz
│   ├── 14823c7842aa541bd2db225f6d9c3475a97ccb89.nq.gz
│   ├── 14f904f91d6dbc25651a4d4758ea1e94fed036c6.nq.gz
│   ├── 1784aebdd34dff35c599237170adb10b757a5ad1.nq.gz
│   ├── 181baee7bae9dda4e03a1a7ecc36ae862aff888a.nq.gz
│   ├── 19322e7123a6da3afbf6ce125d889df527dcf91b.nq.gz
│   ├── 1b1c91c41bff6045ebf5271bfea556b1b5b6ff15.nq.gz
│   ├── 1d9622d9a2769e0a5b2aba29a2d8884dca6b759e.nq.gz
│   ├── 20e4bd85661f5fbc86e0a8aac3934ddabe776160.nq.gz
│   ├── 234319cd7927ce95ad6e1983d08fce75535029f9.nq.gz
│   ├── 29287aabbb66f4a4512069845e6b645bbf61d0d7.nq.gz
│   ├── 2a4689e83be1ad2825771146f16a9f22275a5e55.nq.gz
│   ├── 2b0a25559e412080e80beec73747d6fd54b5780b.nq.gz
│   ├── 2b6540cf7dfea406f5a2e65ec93b459cbdb2d1b8.nq.gz
│   ├── 2c0733315e415bfb5e5b353f9996ecd964d395b2.nq.gz
│   ├── 2d1ca3067319d9554b92255e9574781eb7accbaa.nq.gz
│   ├── 2e0f2db8b70af5f0cedec0a469e7de2d45baae29.nq.gz
│   ├── 3042502583ef0d6e7b38b8198c24b6a302e461ac.nq.gz
│   ├── 31a71bb2ccd8c4353dcf479aa85c03eefb1cffda.nq.gz
│   ├── 32d7be401a5bedca8f8053e9a70afc5529a0a427.nq.gz
│   ├── 34281fd32e3136dfecaf7b1530e4c48699db587d.nq.gz
│   ├── 34b8108b661c8b2ec86bcd8a7f12dda1c2df247d.nq.gz
│   ├── 35ecb442fb6e1911dd3aadb8839bb53c722a5335.nq.gz
│   ├── 38cc145fa99f8210fef97d9b0a14bce3493bfc56.nq.gz
│   ├── 3a9d0a14a483679e015b42ee749600798cd0b661.nq.gz
│   ├── 3d5f18daa573cb2cfc0283644b43a474463800d9.nq.gz
│   ├── 3e0bf3771b9ddd5e808457199fff73747e5885c0.nq.gz
│   ├── 41b2d774df75b1c99e894c675de514f3739d0398.nq.gz
│   ├── 42443280ac0ed30aca5f5ec9dcb1205aa1a1d41e.nq.gz
│   ├── 45729e78bad325a95d7cbd9fa7536f788d413392.nq.gz
│   ├── 45b13e1447c9fc8ab61cfe1428faf873e50cb98a.nq.gz
│   ├── 46a4c93d84d331d708c0a43387532d46a8fbc597.nq.gz
│   ├── 47b46e35dbfe427a7b3d38f50370229356cbd349.nq.gz
│   ├── 48d437626aad0713a670af3bd6aa6750b64ecf00.nq.gz
│   ├── 48fc69c0b3c883d0e48aa96773c4b9950ce3e76b.nq.gz
│   ├── 49711dafd95bbe72648add2cabad68a01464d75e.nq.gz
│   ├── 49acdcc9bcdf50a3d12717688e1417b766bc8e9a.nq.gz
│   ├── 4a4249a08a028770812f92b15c8d4d0ff2afe4e2.nq.gz
│   ├── 4c63de390b8f611d27d09e87e89b4d995ea70d7d.nq.gz
│   ├── 4ebe4d0fb74390bfcb571335a7d8e75d3bdacdc4.nq.gz
│   ├── 4f0b59c17890a2508d59b1c789320c47d065dfb3.nq.gz
│   ├── 4f6a97f01275aa9882a5e46b0047789d84ddaba9.nq.gz
│   ├── 5462399387676427bc1b92574b810a37f01e2588.nq.gz
│   ├── 599a1aa80ebb181bfcfdc3cb047f22e889339026.nq.gz
│   ├── 5a48e025dac94f0ce3193faef6d73cea2e0f542f.nq.gz
│   ├── 5db8cc4762aca82dc4624c9629f0a079a4970ef3.nq.gz
│   ├── 64cb9a17cf0c9546a4c7414558067d8766643baf.nq.gz
│   ├── 6682861cdc2408165e9a9030004cd43fe907c80e.nq.gz
│   ├── 66dd8e161e358329e7fc9b9c7082a05dd0ff9cd0.nq.gz
│   ├── 6a66b6009272e432374a2d19e65be331f80aff0b.nq.gz
│   ├── 6f49c0aff219496f6488f082bdc90867d4a5a114.nq.gz
│   ├── 6f70e0da64e6946056c6445e1cd1f2f93a1604bd.nq.gz
│   ├── 7175ece4e5055f6419f454be28a15aae9b391f3b.nq.gz
│   ├── 72cf3fe20e4a1c0bf8e79912b6ead6bd898018c3.nq.gz
│   ├── 73b1add730403802dc56699d400ead46c2f3ec04.nq.gz
│   ├── 772ccc45b7e55617f471dd8b967a2b9faa701202.nq.gz
│   ├── 77a8ec23f89bdcc6e619922960f28e183512006e.nq.gz
│   ├── 7a9562da7a81db87dca98c6780f9d842894e2da4.nq.gz
│   ├── 82600561c96c7f115ed567a01cf5797f99d9bb1b.nq.gz
│   ├── 82b7ea0cab63790c978c73b89ea691710252d7ac.nq.gz
│   ├── 85f875c97934c927b9ba14cfce86779b30435076.nq.gz
│   ├── 87a47e81e4942683d38c88c93abab10caa1238ff.nq.gz
│   ├── 8963526904db0cd8363cfaca6d21ecbb4534f0a5.nq.gz
│   ├── 8a949b61680f80a9e2afa2f4789065eae4ae1aad.nq.gz
│   ├── 8c4b501882c43723665888f24d553a894deebf54.nq.gz
│   ├── 8d401cbffa6fe5834bd90a5dc7e9820f14b61345.nq.gz
│   ├── 8d7675d790a650563be037e055e46fdbaa987a5c.nq.gz
│   ├── 915af24852d29ac388ec3511e60ab439b4a5a4a8.nq.gz
│   ├── 91c1ca813d9c712ca363e5cd70407577e7743132.nq.gz
│   ├── 921017156dc279529d7ef219f2e0367575a3690c.nq.gz
│   ├── 937ef7aa85e34be77c39ba251c80bf6491835a0c.nq.gz
│   ├── 9593950d08fd506b6705e58ff09c98abd0c9b20d.nq.gz
│   ├── 95a2488764f142701958bc1544a8b681c2991657.nq.gz
│   ├── 95ea0248e6e701dc17f46ff5e8267f27bdade557.nq.gz
│   ├── 967588221b6673e4a9420b87e31958ada7594088.nq.gz
│   ├── 96e7ee0d7574af4f7d60852c22256cf64b93cc50.nq.gz
│   ├── 9747a12121ce61b26d39c44b3777691184d15eed.nq.gz
│   ├── 977e6a1c3ec2db1f98e1f69d85e782f8bdded5da.nq.gz
│   ├── 97a2ab594962b35f9120d1041adb25791ef919ed.nq.gz
│   ├── 97ea7137ca155c2dd86fd778df95d68dad5993c3.nq.gz
│   ├── 98a769d68c64d5eee38c7bb4f9939f9842092fb0.nq.gz
│   ├── 9bd6920da5bfd9ea448d9df38f05bb9629093272.nq.gz
│   ├── 9c334f6724d051320b2565f1f6eb2be3deb26ced.nq.gz
│   ├── 9e0c5504c428ce28fe3251eb1fde6e46de66d06c.nq.gz
│   ├── a06c42d79eda00b309914665015b4b6f3a02d30e.nq.gz
│   ├── a09a76278f88b81859abb62ada91b1366524a3c9.nq.gz
│   ├── a575b22b1cb9dbb29852e495a7e55367c04dc8b2.nq.gz
│   ├── a825a70b21ec294073893ee6740db9616e2db45e.nq.gz
│   ├── a9565bdf9432b2893a1461a76ddfda004c359079.nq.gz
│   ├── ab30c42858c9d8bf83b501daa22fdd8d958d08d4.nq.gz
│   ├── ab4d8721f8e2f7038301fc4f8629ccb336229ea1.nq.gz
│   ├── ae489ceded69bb77c14b315ca9fbdd51163b6254.nq.gz
│   ├── aef34c1821ad0e47a3353267cb17186625630849.nq.gz
│   ├── b0f0c210bef7fc3d5d26a63d4025c19fe44e26b0.nq.gz
│   ├── b2331135eead22137cb96899ac6608ae6aea0443.nq.gz
│   ├── b4782815a06cfd3c1518d7349ea37fb7808687d3.nq.gz
│   ├── b52c9fc0dab5509aba6f3bc0281651a6b485a45a.nq.gz
│   ├── b65cafa237ef045cb66386f4a0527172bc16ee43.nq.gz
│   ├── b7530c2895f71eb1787312c4005b404fd6eec846.nq.gz
│   ├── b885621484d73152ae4f24dc9b718515162f2d30.nq.gz
│   ├── bc540e257974f74709d3f8fed3ad47b403689700.nq.gz
│   ├── bce0832cbcd62cef83fd7d8733b9d7b5a742b699.nq.gz
│   ├── bd79ae4c6e7d5b20fbd7d0d8cfa72467256a939a.nq.gz
│   ├── bf7d1e24c578a8290e2bcf34cadfc878426f32d4.nq.gz
│   ├── c0627ab58cf9b929494072773ccc03a223c49b52.nq.gz
│   ├── c401ac3e20dc1c7319b07d5f8d72289d71eb12c5.nq.gz
│   ├── c80f2722f77a056c5bbac49d82847dd5b02eee13.nq.gz
│   ├── c88a48aa95999337b71cc3cb74fdec540b49b1af.nq.gz
│   ├── cb90140bf60fb7c1be2877150b2f2c1a80d6cc7b.nq.gz
│   ├── cb943ea414e12397ce66e5351ed5c06b4f2a934e.nq.gz
│   ├── cd4e090bffc6b302c35c252f608a15ecfa70fcf2.nq.gz
│   ├── ce1ba4c991f994c48def747aee55b9ff63455e87.nq.gz
│   ├── d10e93b82b1a67307cb703b58debd9edcdacd4cb.nq.gz
│   ├── d13cbb4e3adab7ecff79bdab283edfda031eea2a.nq.gz
│   ├── d347a8a04aa8dfe83b632dea8781dd26ddfc2c1e.nq.gz
│   ├── d3f746c22651a5828779b7deab8b2450343d6fe0.nq.gz
│   ├── d594bc05e9c56a60f3ee2bfac8d4a08c40e64e75.nq.gz
│   ├── d6143ab0c9cd0778db5f265836cab4882653ab18.nq.gz
│   ├── d625b5c7f6696483377c246027a03179b54c99c4.nq.gz
│   ├── d939d2ae2f180169a13fe5e4ec4aff6b4eae2ef6.nq.gz
│   ├── da07303d3e9a8734aaad91eff5d516d142ac7c76.nq.gz
│   ├── dc8094747dd07ee1ca75aac489ab3dcbb2aa5594.nq.gz
│   ├── df44c983e84dadaaa155219d36c3f9eec340bc38.nq.gz
│   ├── e01b19881275a41a393dce997d1098d6c2212c39.nq.gz
│   ├── e09b97a65d1174ab93a29ef89d23cb4b03a1896c.nq.gz
│   ├── e1601c8b1db0c1af33d20afbf6bd5286d7138147.nq.gz
│   ├── e329301bbc82ed544006a78584c7d16cecff3e06.nq.gz
│   ├── e3c2c7ba08bc894e2cfee8ddd48e3f5708544481.nq.gz
│   ├── e404600b30a832e94ef8d90fee2bd5c9915cac11.nq.gz
│   ├── e63b6efd62e556688f200bbb3054bfac15d08278.nq.gz
│   ├── e64db68fe3992eccc2386c28facc8f75a2487fb7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea8625f940bacf3506ddd8f8c252fff72a95d16c.nq.gz
│   ├── ead0e129c67ff686bdd290580398f16d5567905b.nq.gz
│   ├── ecdc831f0197ea19560ddb76f964c6bf6e504dfc.nq.gz
│   ├── edab73fe100f8454afe8e0fd470c8a771c15c5f0.nq.gz
│   ├── f00b175c27f97384c13c7f5029e2c0432ccad033.nq.gz
│   ├── f0b926a29ec865440210b666fb44361f6d2d674b.nq.gz
│   ├── f5ffd4f9c4efb44a082bb8f63c8906ea8186e175.nq.gz
│   ├── f78e3963c7d8ca0d9517c7a0cd5d34f98bf77459.nq.gz
│   ├── f978ed51a6a2405d2402b332fb5b0c45ebefdb03.nq.gz
│   ├── fb36b6a088300d804b6e2157cfb8675df8431df4.nq.gz
│   ├── fc9d26543c365f9f9ebeffffabd242890d1778d6.nq.gz
│   ├── fdbfc5f7aa9dfb9ed883bbbf3fc52f5c9925605f.nq.gz
│   ├── fdf9e3d2a2338bc39be3f0b456c8c78fb88368c4.nq.gz
│   ├── fe7634f3ffecbb436436b19422d6d7f0eefa035c.nq.gz
│   ├── ff02a6299dc1a24de57d751393a75376dbe9646c.nq.gz
│   └── ffdab7de6b83e406ae7ad1191695b8fa0b5501bc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 33c0ca77bf6062a23d60ffd4a6859334c4a46d30.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 169 files
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

[allenai/MolmoBot](https://github.com/allenai/MolmoBot)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
