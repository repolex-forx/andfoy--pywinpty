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
│   │   ├── 7a18d13f87a8ba55404f4ce8cd21d07b527380ef
│   │   │   └── chunk-001.nq.gz
│   │   ├── e6582445feebbcb16c02b7b84b747c2e7ebe12fc
│   │   │   └── chunk-001.nq.gz
│   │   └── f84f66b97680d1babfbeaa4cc8b79e868a617553
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 7a18d13f87a8ba55404f4ce8cd21d07b527380ef.nq.gz
│   │   ├── e6582445feebbcb16c02b7b84b747c2e7ebe12fc.nq.gz
│   │   └── f84f66b97680d1babfbeaa4cc8b79e868a617553.nq.gz
│   └── repolex
│       ├── 7a18d13f87a8ba55404f4ce8cd21d07b527380ef
│       │   └── chunk-001.nq.gz
│       ├── e6582445feebbcb16c02b7b84b747c2e7ebe12fc
│       │   └── chunk-001.nq.gz
│       └── f84f66b97680d1babfbeaa4cc8b79e868a617553
│           └── chunk-001.nq.gz
├── blob
│   ├── 04d50297e3e803615b158b4dac29e04ab0644dc9.nq.gz
│   ├── 0ac76b835040ec07222fe18ee97fc4cc62a223f9.nq.gz
│   ├── 0e509b511e6ad7a0ab95f9cda8ff44e77dd3be68.nq.gz
│   ├── 1d7662db06d3a4b221c75419dfefe5894135c9ed.nq.gz
│   ├── 25be2691ce84edd9e2c2fd7447784b55be2c941b.nq.gz
│   ├── 268761a6c86e9e90b979a77f3f518be5ba5f7446.nq.gz
│   ├── 2e1f20a79ffc4055d7500ad5c97eb93cae1df3e8.nq.gz
│   ├── 36e7d8a798144babdc97cb64753fab8f25a2cd3a.nq.gz
│   ├── 3f260f74440fd66b579afb7407e63a5a19c383ca.nq.gz
│   ├── 50bce83ef427523c04fb831f46048966abf3fdf1.nq.gz
│   ├── 52fb4c145121060c9b959b734532e9a058a3039b.nq.gz
│   ├── 53c075fb27630c2cd21d8a3a11a4ecebe8d76da7.nq.gz
│   ├── 53f61e6ef79745d57a874c677d86d32213e39e83.nq.gz
│   ├── 5b3387d68286064000b6f857edb89be5f647b70b.nq.gz
│   ├── 5b5032ec1b1b93de00e767d3bf9e3dd38df82ce2.nq.gz
│   ├── 6090e50385b909a86f2bfeec947143fd81a32549.nq.gz
│   ├── 63dbb85ce063fc375d95d17fd564bd0a75164a6c.nq.gz
│   ├── 6e3b7df7de6eb00a4f6af5a29f8f46d62940c788.nq.gz
│   ├── 715dc01e81e10a6dc080e1bc4de4599ac27b0b34.nq.gz
│   ├── 72887b926027fa24a1c76ebfc53a46397cabf6fd.nq.gz
│   ├── 75320bd5b054034f71332e83b9a32ef617084e68.nq.gz
│   ├── 7848b7ccc68a309cad5a1eead49711bc4d9fe944.nq.gz
│   ├── 84decd66f03cd8e5474d4dcdccab29cec2d6c2e7.nq.gz
│   ├── 854bb4bdf3bb8855020ac4adaa56b841052a5428.nq.gz
│   ├── 8cce4cc967f3a7f2824b80ce05817204444ed379.nq.gz
│   ├── 90d5c4b055e72306e19ec0914c928752682f9725.nq.gz
│   ├── 92facd2a4489cce43ef54253a57266398d834eea.nq.gz
│   ├── 937bf7c70cbb2468b3d55d59d67776b0bebe04c8.nq.gz
│   ├── a2364af001edfb3023042d46fb81781f48d8e413.nq.gz
│   ├── af1b7a1e70d7163fdaf85a9836cdf70478487390.nq.gz
│   ├── b026c04347c517b8dc843d594fb9b7f9d82c7898.nq.gz
│   ├── b1881d3823bfa1f3d1bf3a18162b977114576dc0.nq.gz
│   ├── b6f29dd645ab1523f9142f8978a2edf79e0fa744.nq.gz
│   ├── b7d6543d809146acabde9d7a194eef9890030ddb.nq.gz
│   ├── be0a382a34c18f035c470bd36e7953195f01fb10.nq.gz
│   ├── bf0da8e72fb4faea1041ee95a5d90c2e2bd1bce4.nq.gz
│   ├── ccba51a97f1578d04f49200d3d4b330e54761469.nq.gz
│   ├── e09e0fb891c8769ef02b8dfaa92e974740785b52.nq.gz
│   ├── e7e82e2e88597824d154a5402db43cd515650992.nq.gz
│   ├── ec4ce424b49b82c33d3446511b5c8f64a0392113.nq.gz
│   └── f69e054f245be752937e6c48012eab8fdc60b58d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 7a18d13f87a8ba55404f4ce8cd21d07b527380ef.nq.gz
│   ├── e6582445feebbcb16c02b7b84b747c2e7ebe12fc.nq.gz
│   └── f84f66b97680d1babfbeaa4cc8b79e868a617553.nq.gz
├── filetree
│   ├── 7a18d13f87a8ba55404f4ce8cd21d07b527380ef.nq.gz
│   ├── e6582445feebbcb16c02b7b84b747c2e7ebe12fc.nq.gz
│   └── f84f66b97680d1babfbeaa4cc8b79e868a617553.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

19 directories, 61 files
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
