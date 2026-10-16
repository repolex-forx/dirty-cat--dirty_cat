# Repolex Knowledge Graph of dirty-cat/dirty_cat

RDF knowledge graph data for [dirty-cat/dirty_cat](https://github.com/dirty-cat/dirty_cat), parsed by [repolex](https://repolex.ai).

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
rlex download dirty-cat/dirty_cat
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f27c58e3705acdbf75d4bd14a28aa43a598528d1
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f27c58e3705acdbf75d4bd14a28aa43a598528d1
│           └── chunk-001.nq.gz
├── blob
│   ├── 01417a3e9e8f0562bea5d1cc6cfa0393ab9ed86e.nq.gz
│   ├── 02aa10a34c27804b2c1d1965c80f902c434858ea.nq.gz
│   ├── 0436726f4f200967ee2f847a72137b672fba483e.nq.gz
│   ├── 0b00c7a803d9a4b05b92f7f6bffc3b88bfc0d8fe.nq.gz
│   ├── 116bc11d40e20f240abb2f9dba863be36f07c71e.nq.gz
│   ├── 1189bbcc9e18d4f9176222b98d9963bcc6411d7e.nq.gz
│   ├── 14bef64ac0f8f112f0d083acfc45cea54a9e9d29.nq.gz
│   ├── 188d42ee7310c1da6c722983c7681ccb1bb2d5e6.nq.gz
│   ├── 220c89bbc08526398a8c07e9dbbb554a351dad2d.nq.gz
│   ├── 262d1592161dc9e59643daa2730321e28ed50956.nq.gz
│   ├── 262de97f53c88fa6ee2f676a1cead4ec73c9db35.nq.gz
│   ├── 26e08e48e8f82869ef1dec35972ee25826efecfb.nq.gz
│   ├── 2a5b38b3efc1258ba89ff704d260db4fab4ff0ab.nq.gz
│   ├── 2b7c5ae01848a77d95e2792eb83ab605c9aed91a.nq.gz
│   ├── 3010e16ccd69284b426f4593be55e47d18b9c743.nq.gz
│   ├── 30bebda6113b139cf384567a3b259dbdbc916d3f.nq.gz
│   ├── 34cc2946c60fe48b65107a981104c45fefd247d6.nq.gz
│   ├── 36a47fca2b31719d9b374c1f95b7262ea1fd72e7.nq.gz
│   ├── 37258d8d76a760f00e7eabf8191d382666b0c8be.nq.gz
│   ├── 3782c9075039ce92f9c16936cc261abda7566544.nq.gz
│   ├── 38ab20274a272570478ba2722f76ebec0a816cc4.nq.gz
│   ├── 39ceb68c5ab74193016fe25c987e32143af0c1f9.nq.gz
│   ├── 3ad374370e9c93c2921d516e95395236a89f1704.nq.gz
│   ├── 3c86f8ecc7cf10ee81646f10de8a95cdd3e81603.nq.gz
│   ├── 402597348b424428ef99cc8253b0d06ce20c6262.nq.gz
│   ├── 431286abfa2213894bea21c082b76ef25cdd7dc3.nq.gz
│   ├── 4709ef0bfe971459dba52153d569e9b2a593268f.nq.gz
│   ├── 49bb2c4a48b26d690f01ac5c2815aa4f79120c84.nq.gz
│   ├── 4a4e08f9eb3e3d5ac347452cbf064a854bb44f5a.nq.gz
│   ├── 4b5ecfd26940194015191e00f78b991759647ea3.nq.gz
│   ├── 4c79193ed7dd1af053c39e257714f7b14db56caf.nq.gz
│   ├── 5163bb1d1660735d452f08bfe46dcaa5833ce71f.nq.gz
│   ├── 52e7fa0cc802ea47221e326e4e0695870eb64427.nq.gz
│   ├── 53ee9be5c17dafdeea94cfe7a2b4654435094c21.nq.gz
│   ├── 560a548314f09d89ae2a0e4b3e440ee013f53944.nq.gz
│   ├── 5749bc005aa05a9bb1548b7b9f6d5893b4e9d9d3.nq.gz
│   ├── 5793f3144af22045b250a63b15bc6fdf824c49a3.nq.gz
│   ├── 58dc8c327c5dad5af05f6585124ef825695bc81c.nq.gz
│   ├── 5f3b2259390aa6e667b00b8b9114df10a854f2f5.nq.gz
│   ├── 61ebb2d8b8a350d5aee2c1f1c567dc6e7303cdba.nq.gz
│   ├── 6378dadf06554346e0651f909dccc8403f5209de.nq.gz
│   ├── 63a1cda66616a41179558fd2c9a812f44d31d7cf.nq.gz
│   ├── 68943aff85afa72215e5bbd9f58bc85ba1e2779c.nq.gz
│   ├── 69aa265de012556a39cb3269006b25138e8ad7fc.nq.gz
│   ├── 6ca1adb1d6798b19f54a38a408414cb8c63d7ca2.nq.gz
│   ├── 6d04e1baae7bd99ef11490670254c42ca7db8503.nq.gz
│   ├── 746bffc0b4019b2cec8afa949d5da48007b8d031.nq.gz
│   ├── 74b0b187032bc1f79717145d99b989f6545008d5.nq.gz
│   ├── 75b3c6bbe588b8540e025331fab52430346f21bf.nq.gz
│   ├── 75d6a181f1a09761f9eefc5d7c9513e4107fd9e2.nq.gz
│   ├── 76320e2718e636f9ca74ee76f4c36fb70df055e8.nq.gz
│   ├── 76bc7dec98025ab4e285bbaf2f698767836b4dc3.nq.gz
│   ├── 7ab0e265cf1b54410ab84ff7242098b8645b240c.nq.gz
│   ├── 7bbd0484658d0f24548471e5de45bd357a4842ba.nq.gz
│   ├── 7ddd0bc67cb67cdc850c36be681ba22bb6418f18.nq.gz
│   ├── 7eeecd171fbf7cc21f5f7a28f9a0b9793c96eb7f.nq.gz
│   ├── 822da6f59dee8e0efb4f775adf18e6519f0c116e.nq.gz
│   ├── 890e89be8857f994be9e765582a5c2f9b8031b7c.nq.gz
│   ├── 8f5bbb57f7bdaff68da7cbbabce0343670913fe8.nq.gz
│   ├── 8fdd90711cf30a647773d20e3211b7f6b84862b2.nq.gz
│   ├── 936162a50a15622a8f232e2c39705f7fc689e10a.nq.gz
│   ├── 9502eadbe71ec0daf05b1e457462fa648ffdb8ae.nq.gz
│   ├── 96bf957d4eaaa4dd550f0893ec67f7c1e649d4bc.nq.gz
│   ├── 96c61ecf65bf9d303e52fc94f02d5a3e2a4215e6.nq.gz
│   ├── 9842245281fa563412cd7bc15128cc96add2d997.nq.gz
│   ├── a08bd44feed4dcfa83c74a3a676befa444344f87.nq.gz
│   ├── a1d3ab79f6306f616e5172e4a07fc8ac6c92ec1c.nq.gz
│   ├── aaa2fab4601d6c8a5722be6f8bab8e78968763d1.nq.gz
│   ├── ae1903092a9f6290ca4fc9bfbc049a56f7b2b79b.nq.gz
│   ├── b4e1709e67c3f7bd61ca318f21ee5a4ac09a497b.nq.gz
│   ├── bcc27895504fa8449f5b5334fa0593efe285067e.nq.gz
│   ├── bd67ae4c0f7e9ea5193136a09d750f6d4fb6a90d.nq.gz
│   ├── bff5bf0b8b2cacc7c73cbf541dd611fe39677f4a.nq.gz
│   ├── c011076d82a0bda00390b362d3eaf404135a4571.nq.gz
│   ├── c30e004f276f3ed393ffffd327d2ddd78d63cc29.nq.gz
│   ├── c37b8a7c4edb719bc70cc6d7d038af76c52c7710.nq.gz
│   ├── c3b2c7699ef607f33e918f1a818a9163418a13d8.nq.gz
│   ├── c680095cac77235c3808b9c33ff890f4400b0401.nq.gz
│   ├── c6c375659cf1edd06d4676b62f78bb4a604373a0.nq.gz
│   ├── c6ca7727074bc0d31b327fae931db27e2664340e.nq.gz
│   ├── c6cd417f2688c163e285d370d41915111300734e.nq.gz
│   ├── c956f18b8d443e97b4f23f04b2414f076006d9ef.nq.gz
│   ├── c98bc88e75112b324c977fadd988fdd052bd3aff.nq.gz
│   ├── ce9122bf2124cc936c1fba717131ee759c363991.nq.gz
│   ├── d24e63e5507506c9eb46994ab54956ed8303acf8.nq.gz
│   ├── d257d48fd8499c1e2ccccd587b1027fcbd536eaa.nq.gz
│   ├── d2c61a74a4010f909e60f5c47c82ff21f3aa1768.nq.gz
│   ├── d5783037f1e974531124f0511ccb2ad543fdad94.nq.gz
│   ├── d9860b0ab5277a25ae515caea29f252c93c34f9c.nq.gz
│   ├── d9eae8788dd76823a3ddd96817a3d31d865bc020.nq.gz
│   ├── dbe663cd3b93b41885dd48d7bdae07f4a6f56ebf.nq.gz
│   ├── dbea2557ec4b1622e0144e85131d0d41fb7a96d7.nq.gz
│   ├── dc4118e4507e2cd0bd4304dd8194e4d9d3aebb8b.nq.gz
│   ├── df571e0f78e9d111b617ef4a970332dc1a8b10b3.nq.gz
│   ├── e22636e1e57ed6000d13d50749244a0a575fabde.nq.gz
│   ├── e4184d76db0a16eaaa873e6f987702910c189210.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea3e9ceb50d1d586d7c3c13477d7702d662b64c7.nq.gz
│   ├── ee6454a12d72085c9264953696c236fdb6582bf9.nq.gz
│   ├── f0d43d67229dcd9596dcd8ef3b2199e25b2e05e9.nq.gz
│   ├── f4b11eda770e4606376a354d09a24093a2e35a19.nq.gz
│   ├── f4b8a1640a71c10a8244f90d385b7c1f0798ce68.nq.gz
│   ├── f834be1e33d9c64651d712fae2f1e4d711da152f.nq.gz
│   ├── f97bce47b3d0f8c3190673990e3fb773b8df8b15.nq.gz
│   ├── f9fbe3e95336eb482e7c1c4eca4a92e5a704550a.nq.gz
│   ├── fae34b6bab9db04def1d43a3e1def81837283ba9.nq.gz
│   ├── fb6522bf96a708352e0ad2707e162310b399c49d.nq.gz
│   └── ff68e53244d839eb20ff201d627eaad7ebbd2649.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f27c58e3705acdbf75d4bd14a28aa43a598528d1.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 114 files
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

[dirty-cat/dirty_cat](https://github.com/dirty-cat/dirty_cat)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
