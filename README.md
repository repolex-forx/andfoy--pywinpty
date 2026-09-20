# Repolex Knowledge Graph of andfoy/pywinpty

RDF knowledge graph data for [andfoy/pywinpty](https://github.com/andfoy/pywinpty), parsed by [repolex](https://repolex.ai).

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
lexq download andfoy/pywinpty
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 185653eda0d5aeedbf9dfc90b6424b1d9e41a532
│   │   │   └── chunk-001.nq.gz
│   │   ├── 529078a9c08c81b26598b26457603c783eb818f9
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6aa5ef7e248af38b44e502997b1873f7227d8508
│   │   │   └── chunk-001.nq.gz
│   │   ├── 7a18d13f87a8ba55404f4ce8cd21d07b527380ef
│   │   │   └── chunk-001.nq.gz
│   │   ├── 86c2c2d06c2ef03dedaae7345c92f7aef3174eaa
│   │   │   └── chunk-001.nq.gz
│   │   ├── 88ea24f726e82e3fd80cbfbc07ca24419b54eb33
│   │   │   └── chunk-001.nq.gz
│   │   ├── d7e3fe4a115f18722513c3e3e75879cba5b16673
│   │   │   └── chunk-001.nq.gz
│   │   ├── e6582445feebbcb16c02b7b84b747c2e7ebe12fc
│   │   │   └── chunk-001.nq.gz
│   │   └── f84f66b97680d1babfbeaa4cc8b79e868a617553
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 185653eda0d5aeedbf9dfc90b6424b1d9e41a532.nq.gz
│   │   ├── 529078a9c08c81b26598b26457603c783eb818f9.nq.gz
│   │   ├── 6aa5ef7e248af38b44e502997b1873f7227d8508.nq.gz
│   │   ├── 7a18d13f87a8ba55404f4ce8cd21d07b527380ef.nq.gz
│   │   ├── 86c2c2d06c2ef03dedaae7345c92f7aef3174eaa.nq.gz
│   │   ├── 88ea24f726e82e3fd80cbfbc07ca24419b54eb33.nq.gz
│   │   ├── d7e3fe4a115f18722513c3e3e75879cba5b16673.nq.gz
│   │   ├── e6582445feebbcb16c02b7b84b747c2e7ebe12fc.nq.gz
│   │   └── f84f66b97680d1babfbeaa4cc8b79e868a617553.nq.gz
│   └── repolex
│       ├── 185653eda0d5aeedbf9dfc90b6424b1d9e41a532
│       │   └── chunk-001.nq.gz
│       ├── 529078a9c08c81b26598b26457603c783eb818f9
│       │   └── chunk-001.nq.gz
│       ├── 6aa5ef7e248af38b44e502997b1873f7227d8508
│       │   └── chunk-001.nq.gz
│       ├── 7a18d13f87a8ba55404f4ce8cd21d07b527380ef
│       │   └── chunk-001.nq.gz
│       ├── 86c2c2d06c2ef03dedaae7345c92f7aef3174eaa
│       │   └── chunk-001.nq.gz
│       ├── 88ea24f726e82e3fd80cbfbc07ca24419b54eb33
│       │   └── chunk-001.nq.gz
│       ├── d7e3fe4a115f18722513c3e3e75879cba5b16673
│       │   └── chunk-001.nq.gz
│       ├── e6582445feebbcb16c02b7b84b747c2e7ebe12fc
│       │   └── chunk-001.nq.gz
│       └── f84f66b97680d1babfbeaa4cc8b79e868a617553
│           └── chunk-001.nq.gz
├── blob
│   ├── 04d50297e3e803615b158b4dac29e04ab0644dc9.nq.gz
│   ├── 0a9ae73a8e1fe751a33923af7e45d0b296bfacd8.nq.gz
│   ├── 0ac76b835040ec07222fe18ee97fc4cc62a223f9.nq.gz
│   ├── 0e509b511e6ad7a0ab95f9cda8ff44e77dd3be68.nq.gz
│   ├── 13d910732bac5a8aa0cf5c503eb3d22a6e60482b.nq.gz
│   ├── 1d7662db06d3a4b221c75419dfefe5894135c9ed.nq.gz
│   ├── 1f3334d9aebe008a14a8a121937fe6ff9a17b28a.nq.gz
│   ├── 218b02a402b1ba77bc566bb89c478220bbde3238.nq.gz
│   ├── 220f7ba70e7635908cf1d9d4fac1aa559a587815.nq.gz
│   ├── 25be2691ce84edd9e2c2fd7447784b55be2c941b.nq.gz
│   ├── 264ec0263c3b0cb8c7c97d5462b32f776d54ca36.nq.gz
│   ├── 268761a6c86e9e90b979a77f3f518be5ba5f7446.nq.gz
│   ├── 27a3827d1e1a389bec6a6cbfafb437333e7da1ff.nq.gz
│   ├── 297f9d634d640caa54257fbd18d3867a6f64de89.nq.gz
│   ├── 29f470ccf0587a1b2bf90058d1a43b75acd8bb9c.nq.gz
│   ├── 2aa66a65d757ccfab764a24e098b4f30442b46b7.nq.gz
│   ├── 2d717e559571658dbe41534ea1b4229002ada208.nq.gz
│   ├── 2e1f20a79ffc4055d7500ad5c97eb93cae1df3e8.nq.gz
│   ├── 322fc527399ad5905cdda9f6184b32d048d91059.nq.gz
│   ├── 36e7d8a798144babdc97cb64753fab8f25a2cd3a.nq.gz
│   ├── 3f260f74440fd66b579afb7407e63a5a19c383ca.nq.gz
│   ├── 425e8982e486c92f2b4384f2e1ddfeb99b007738.nq.gz
│   ├── 42e2d233dd16adb77f1f9ef8de719a88775d0ae5.nq.gz
│   ├── 4380a2e9a6cfa666e44165118ba5684a6129e4eb.nq.gz
│   ├── 4429ead0d218fb33c3126a7f69caee1a97837314.nq.gz
│   ├── 45add20174d820f3b2b26df667f19fe779d02cf8.nq.gz
│   ├── 50bce83ef427523c04fb831f46048966abf3fdf1.nq.gz
│   ├── 52fb4c145121060c9b959b734532e9a058a3039b.nq.gz
│   ├── 53982a5c3de2c76488a4601652038131a88864c1.nq.gz
│   ├── 53c075fb27630c2cd21d8a3a11a4ecebe8d76da7.nq.gz
│   ├── 53f61e6ef79745d57a874c677d86d32213e39e83.nq.gz
│   ├── 585cf26669f25c3444eca689a922ef02c1e3dc39.nq.gz
│   ├── 5b3387d68286064000b6f857edb89be5f647b70b.nq.gz
│   ├── 5b5032ec1b1b93de00e767d3bf9e3dd38df82ce2.nq.gz
│   ├── 6090e50385b909a86f2bfeec947143fd81a32549.nq.gz
│   ├── 63dbb85ce063fc375d95d17fd564bd0a75164a6c.nq.gz
│   ├── 64331189d3da7361b38534465691b4b8b887ccb9.nq.gz
│   ├── 6e3b7df7de6eb00a4f6af5a29f8f46d62940c788.nq.gz
│   ├── 704d5bae57d9e98dd521698d0bcbfae23616cae0.nq.gz
│   ├── 70c0c8b5a6095a42617d4aad8eec7916efacbfea.nq.gz
│   ├── 715dc01e81e10a6dc080e1bc4de4599ac27b0b34.nq.gz
│   ├── 72887b926027fa24a1c76ebfc53a46397cabf6fd.nq.gz
│   ├── 728e09af2f070172401896105096a1bb9714bdf6.nq.gz
│   ├── 75320bd5b054034f71332e83b9a32ef617084e68.nq.gz
│   ├── 7848b7ccc68a309cad5a1eead49711bc4d9fe944.nq.gz
│   ├── 7ead94970f96a6fd7ed22a90b3666848b39af829.nq.gz
│   ├── 84decd66f03cd8e5474d4dcdccab29cec2d6c2e7.nq.gz
│   ├── 854bb4bdf3bb8855020ac4adaa56b841052a5428.nq.gz
│   ├── 894b8f351961ceed07de461baa30904b77b96e6d.nq.gz
│   ├── 8add15d9d2c26035339535a1e1046ea6bb1ddc0d.nq.gz
│   ├── 8b494d4eb7544f3d5e25b507c81fd612309dd6bb.nq.gz
│   ├── 8cce4cc967f3a7f2824b80ce05817204444ed379.nq.gz
│   ├── 8fc38475bb147bd06b06b7fb5446ca10c4d034b1.nq.gz
│   ├── 90d5c4b055e72306e19ec0914c928752682f9725.nq.gz
│   ├── 92facd2a4489cce43ef54253a57266398d834eea.nq.gz
│   ├── 937bf7c70cbb2468b3d55d59d67776b0bebe04c8.nq.gz
│   ├── 93eccd32de980bd35c6d19c565a1b8647cc7d5c3.nq.gz
│   ├── 95318025865fbc4a2ceebc7801fb41deaa9821c1.nq.gz
│   ├── 9b9914e754e0851a4ea680ea65bb96b90a231c28.nq.gz
│   ├── 9c245dd4267e85bf69673c812f8cf10b8d5a33c0.nq.gz
│   ├── 9e6b4193e11cf43b861cadbe589a577cb4bec25b.nq.gz
│   ├── a2364af001edfb3023042d46fb81781f48d8e413.nq.gz
│   ├── a66224bc39d41e27c616a782b636123be6e8b42f.nq.gz
│   ├── a90ec181e2fd1124796b04c08a3f56acc1d7d658.nq.gz
│   ├── af1b7a1e70d7163fdaf85a9836cdf70478487390.nq.gz
│   ├── b026c04347c517b8dc843d594fb9b7f9d82c7898.nq.gz
│   ├── b1881d3823bfa1f3d1bf3a18162b977114576dc0.nq.gz
│   ├── b25281084791d9c38825b6ef865233e248522fe5.nq.gz
│   ├── b6f29dd645ab1523f9142f8978a2edf79e0fa744.nq.gz
│   ├── b7d6543d809146acabde9d7a194eef9890030ddb.nq.gz
│   ├── bb1a690bdb8357db0e8cefd8b1e612f62b6a6759.nq.gz
│   ├── be0a382a34c18f035c470bd36e7953195f01fb10.nq.gz
│   ├── bf0da8e72fb4faea1041ee95a5d90c2e2bd1bce4.nq.gz
│   ├── bf8ef5556095ae46b9bfdff619a884a8d5e959c1.nq.gz
│   ├── c5424d6b9a43fb0fbf36347fee32fee1d3f0b978.nq.gz
│   ├── c735dc3b74af357af76b719f1d16188bbdf47ba2.nq.gz
│   ├── caa7e1ec563207af401f3d31f7e4bbb30afe31c9.nq.gz
│   ├── ccba51a97f1578d04f49200d3d4b330e54761469.nq.gz
│   ├── d1aaee32d546c1896ea8f6c723e85f3f5845fb26.nq.gz
│   ├── d2c1669031351b1a2d4214a4df7b266c696c55b8.nq.gz
│   ├── dd9cc2cae08672bdcb12fd8d2d6835c9ca2038be.nq.gz
│   ├── ddf3f899707eaae7d600ca24f011f3e943314a6f.nq.gz
│   ├── e09e0fb891c8769ef02b8dfaa92e974740785b52.nq.gz
│   ├── e0ae3e4ab77103364ff2f8ea0d1b8dac61de6bff.nq.gz
│   ├── e31012dd9145ce9946564ca4541fd0c4e0a29192.nq.gz
│   ├── e7e82e2e88597824d154a5402db43cd515650992.nq.gz
│   ├── ec4ce424b49b82c33d3446511b5c8f64a0392113.nq.gz
│   ├── f4d088cd581de1fe41e95a43fb313592b23d237a.nq.gz
│   └── f69e054f245be752937e6c48012eab8fdc60b58d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 185653eda0d5aeedbf9dfc90b6424b1d9e41a532.nq.gz
│   ├── 529078a9c08c81b26598b26457603c783eb818f9.nq.gz
│   ├── 6aa5ef7e248af38b44e502997b1873f7227d8508.nq.gz
│   ├── 7a18d13f87a8ba55404f4ce8cd21d07b527380ef.nq.gz
│   ├── 86c2c2d06c2ef03dedaae7345c92f7aef3174eaa.nq.gz
│   ├── 88ea24f726e82e3fd80cbfbc07ca24419b54eb33.nq.gz
│   ├── d7e3fe4a115f18722513c3e3e75879cba5b16673.nq.gz
│   ├── e6582445feebbcb16c02b7b84b747c2e7ebe12fc.nq.gz
│   └── f84f66b97680d1babfbeaa4cc8b79e868a617553.nq.gz
├── filetree
│   ├── 185653eda0d5aeedbf9dfc90b6424b1d9e41a532.nq.gz
│   ├── 529078a9c08c81b26598b26457603c783eb818f9.nq.gz
│   ├── 6aa5ef7e248af38b44e502997b1873f7227d8508.nq.gz
│   ├── 7a18d13f87a8ba55404f4ce8cd21d07b527380ef.nq.gz
│   ├── 86c2c2d06c2ef03dedaae7345c92f7aef3174eaa.nq.gz
│   ├── 88ea24f726e82e3fd80cbfbc07ca24419b54eb33.nq.gz
│   ├── d7e3fe4a115f18722513c3e3e75879cba5b16673.nq.gz
│   ├── e6582445feebbcb16c02b7b84b747c2e7ebe12fc.nq.gz
│   └── f84f66b97680d1babfbeaa4cc8b79e868a617553.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

31 directories, 139 files
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

[andfoy/pywinpty](https://github.com/andfoy/pywinpty)

---
*Parsed on 2026-09-20 by [repolex](https://repolex.ai)*
