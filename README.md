# Repolex Knowledge Graph of NousResearch/OpenShell-Community

RDF knowledge graph data for [NousResearch/OpenShell-Community](https://github.com/NousResearch/OpenShell-Community), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/OpenShell-Community
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 36c558e929359830bf272868f42de7bf47bd2716
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 36c558e929359830bf272868f42de7bf47bd2716
│           └── chunk-001.nq.gz
├── blob
│   ├── 013a4e41a784e6d319cdfa7231bf2b885e3940d0.nq.gz
│   ├── 062026bd397e3cbf17242b747b81d55adbd96e47.nq.gz
│   ├── 091730a53b5e32bfcba3e0328dc7c2ed6bcffbb5.nq.gz
│   ├── 0a3f705806bf29ff9db3252d5da4d371fde38c20.nq.gz
│   ├── 0dd5d1280bcf61fb52a7399d585326cc37e63971.nq.gz
│   ├── 0e22377083d42c3ef1d485f33f2ff55b3d63386d.nq.gz
│   ├── 0f5ddaf87fccf927c417900564bba0293175fceb.nq.gz
│   ├── 0fa4899ada92d9cbbb2c22211d03fcdbc7846a1d.nq.gz
│   ├── 130b7346bd1ae147860fff0bcce2fcacb6baab44.nq.gz
│   ├── 137d3fc501755178fc800219984b5a98962cfc9f.nq.gz
│   ├── 1588317cf2fcfc8a3facd467a6b0f2f0a2f36531.nq.gz
│   ├── 15e1ba69b6fe3db0a661dd2885053046b14a11f1.nq.gz
│   ├── 174c287a8636e13bb473a98b8731ece688ac8c0d.nq.gz
│   ├── 1cd06edcfa58644ef80068124816dc38d793ed0d.nq.gz
│   ├── 22218f2e3d0879a7ecc339b6148b81d133827782.nq.gz
│   ├── 247880c73993ef1c42232066c5f8ea6f1ab503ea.nq.gz
│   ├── 26b399d695f1f362895a992c85c4f8b141acb5ee.nq.gz
│   ├── 27856ad44956255c5d9bab6d73ede78d3e1e7bb5.nq.gz
│   ├── 27ae3eec28a3e19be75bc2ce2c6ea0db9ee22c7f.nq.gz
│   ├── 298f1ada8cd60274f20b9d46d80d347ae9444583.nq.gz
│   ├── 2a19edd521adbd3349d52b1f5b5d2089281a985c.nq.gz
│   ├── 2b998458662b3b4ce38218b5301be6337219a12f.nq.gz
│   ├── 2c73ae709ee754f047f1ca3c6cea79ac710d3157.nq.gz
│   ├── 312018286cedae0c4e33877b0f4738658702d08c.nq.gz
│   ├── 3216cab671e2fbbd0cf5469a18b5d7b6b62b629e.nq.gz
│   ├── 331addfe6330b869e6e4bea4ac7d0e625e242459.nq.gz
│   ├── 373adba029813a9281f9c5b1eaca90491af66731.nq.gz
│   ├── 3cd1ecbaae91bb86355568781f942c39d8c2b375.nq.gz
│   ├── 40d492f1d69a3c54f924969f9fe9bb15b6cbddad.nq.gz
│   ├── 4267179b664df489be742f711d8b55117e6c6c1f.nq.gz
│   ├── 44cee897a50cf26b39b43724a6fff8bf3b283aaf.nq.gz
│   ├── 451574a60c700c7d3c2f93b8459d21107c446099.nq.gz
│   ├── 4719b77b037a6502ae6782118b818e90f985791e.nq.gz
│   ├── 4e2414c1c8fb4784559185c2b963267ade8e17be.nq.gz
│   ├── 4f4e79258122ac1b534201e2514dbbf48871203e.nq.gz
│   ├── 50edb541d7ce88e72704d819eab5698646d5cb5e.nq.gz
│   ├── 510a5d79d15138c2c2a75a58839b41a642b9dafc.nq.gz
│   ├── 53eca443329052b6783bc66b7dcf46e21cae53f6.nq.gz
│   ├── 54affb1c6ff4f21961de72b5242a3566c7bba74a.nq.gz
│   ├── 6040400e748e83d5f5cc99bbf1ff8aa2966af73e.nq.gz
│   ├── 611d8a86046fa0715f345a75c27f9162eb434316.nq.gz
│   ├── 621a36d2c8f65e3a536119d7cf5426fad35d5840.nq.gz
│   ├── 6591efdc04a510847c44fd3fe57110e0aa8f6b4d.nq.gz
│   ├── 65a5eec4f82e957be73123bd1eed1aca61e67c30.nq.gz
│   ├── 686c93d325e247d0aa461b2a67874f41c3bbb219.nq.gz
│   ├── 69a6ff84c783213a31c75342421acc5753ebb7ea.nq.gz
│   ├── 6a89803d8f0dc0244fa40b9c4ff22ffe55a8e250.nq.gz
│   ├── 6ba86fef3178e598226accb859fc758cf71ee38b.nq.gz
│   ├── 76d821c156c32261e5063776228679bc49c1915d.nq.gz
│   ├── 7a661b5cbc2920545654c43b0cc94c9bb4e965cb.nq.gz
│   ├── 7a8c41c3252cebe019e02cc5f269386f6932626f.nq.gz
│   ├── 7b48020c0b49e0ad2b717621aaa61ce522469530.nq.gz
│   ├── 7bcdb14e2c6b154668eb3da08ede1cd2fef97b45.nq.gz
│   ├── 7bcf12245a668f9e79ce6a65321fcb433f768d59.nq.gz
│   ├── 7c19fcdaaee1788edd360390b41763f53d0ae4ba.nq.gz
│   ├── 7cc2318dd68c1f00b6913dddb4238c190d0f37e3.nq.gz
│   ├── 7f92d681dc040fdd23b3b3393c106f2e644f746c.nq.gz
│   ├── 81bcd2c81ae6ce5a346e36d1b55c2636f1538ebf.nq.gz
│   ├── 88d27353a3500bee8298dcd7ebdf7aa85b13c00a.nq.gz
│   ├── 89a6bf9b06f835eba25b500f138958171a1925d3.nq.gz
│   ├── 8ae5f7734a901bcda03f2a07daf40e8046bb0cae.nq.gz
│   ├── 8afa9198b783e2da27912f027a8863a572158775.nq.gz
│   ├── 8da45318111ae2514cace2e4ce8de2047fc2b455.nq.gz
│   ├── 8e9088f838d05ebcffb26cef14ec0e5617df5c3f.nq.gz
│   ├── 91e389d3df66c4fa16bef3e17d1d116dcecf12a5.nq.gz
│   ├── 98637fe4d73e376572cdf89257c0d8b33a7998c8.nq.gz
│   ├── 99655f01a292768d00909ada7388f674228c9533.nq.gz
│   ├── 9d1a71169c372a5b571c9e4b19acee216a60fe38.nq.gz
│   ├── 9fc1bdcf9f3735b9b2b1f858b45a3cad771628db.nq.gz
│   ├── a2d20f1d378a8abbeb96544d228c8c921050f9db.nq.gz
│   ├── a45f77ae3a9182ce65e2884a6b9b0dace33f442c.nq.gz
│   ├── a778e66acd33a45aac56cd95794fa28c46d1efab.nq.gz
│   ├── a8514613464849aec10bacc53226f52c3a066814.nq.gz
│   ├── a91da848a2ef0c325358f529e8fec8c31af29ca1.nq.gz
│   ├── a9543ab630eaa085133eeb41f0d4639e215bcf9b.nq.gz
│   ├── aa3da49b24cdcbde366ce56aebaa09dc63279268.nq.gz
│   ├── aaa2d5e090e46ae9f9a9f17da08b7573c8b227ed.nq.gz
│   ├── aeeea329803adcd75f5c8634f3dc996c64c1350b.nq.gz
│   ├── b3c913785c06f519263a658b050e84b582bfb2d8.nq.gz
│   ├── b40c8f7b02118beb91c4a5a1b36e66bc8c072cac.nq.gz
│   ├── b40e16e5dff596da3e74d9eebaae78a46b5d3fe6.nq.gz
│   ├── b4e09b9c1b773c4133b2dbf124056875785408da.nq.gz
│   ├── b6513fb9298dbeffd53607be317d5ab5ef5a0b55.nq.gz
│   ├── b9895a3c2c5d01ef3af2f4cccde010209e49f493.nq.gz
│   ├── bd5b9f29d30da3c769f62f0906e5e8406b93db54.nq.gz
│   ├── bdc9b4817296acbffbefb7a5d2f2f879061bd0d1.nq.gz
│   ├── c29620c832f199194627199b74dcdae25b8da01d.nq.gz
│   ├── c60a61e34613de11dff48473a608c1f6ea32d5f8.nq.gz
│   ├── cc5956fc2d7a648bc32acc3c3728e857f2deeeea.nq.gz
│   ├── d33f2e590ab1025777a51179dfb0b166f3cd1a2b.nq.gz
│   ├── d64a2443a8fed512e04163afb0b9bc82a600a6b5.nq.gz
│   ├── d92bee610552a655e3d19bee157e6c024b58e2a3.nq.gz
│   ├── dd1b7b60f2f0acb171c245dcb0acace84ebe7ae9.nq.gz
│   ├── dd76683c9eccb885f21729408aef65a6010e2cf7.nq.gz
│   ├── e5039786c0139d4b4a5c60793c50e7c1a8f8f317.nq.gz
│   ├── e5e6ecd4bc46c53d63121828fc2b4c07ca26c64f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eafb43e27d00b8c0a4ab9ebc5403f1cc8f3e41a0.nq.gz
│   ├── efe680f48961a25507e571df87bb7ed2b49a1164.nq.gz
│   ├── f349fb6bea7c6e5522730c4161fa5f179d4fb968.nq.gz
│   ├── f478bd16327178076af6bb48d60d926e1c76cbab.nq.gz
│   ├── f4aa20b83122132bbed6f6ac6bf6f4647b2acf6a.nq.gz
│   ├── fa01166d352fdf2073d96b9ee60349d28dfc6423.nq.gz
│   ├── fb8a94f902ba91da12bac5f0af9c8471b0b6db8e.nq.gz
│   └── fbf16285a3785a818f5b16d0f199ea8fa7909be6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 36c558e929359830bf272868f42de7bf47bd2716.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 111 files
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

[NousResearch/OpenShell-Community](https://github.com/NousResearch/OpenShell-Community)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
