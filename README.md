# Repolex Knowledge Graph of xarray-contrib/pint-xarray

RDF knowledge graph data for [xarray-contrib/pint-xarray](https://github.com/xarray-contrib/pint-xarray), parsed by [repolex](https://repolex.ai).

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
rlex download xarray-contrib/pint-xarray
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 908d2d94d21a30e77f24c2efacf3340719d54afb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 908d2d94d21a30e77f24c2efacf3340719d54afb
│           └── chunk-001.nq.gz
├── blob
│   ├── 057e6b18428581e46089a731f8326338c29dec72.nq.gz
│   ├── 06e0b5da14342503575af6580ca0bb67360d925b.nq.gz
│   ├── 1c9f6cf008ec2406951c06eb6629fcba586c8348.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 265b05e70db0c7bd3c8fb1d5a936c33bccb1eb8c.nq.gz
│   ├── 292c3a50a9401c5e0cafc1802060dd25936021ef.nq.gz
│   ├── 308122a38ad936d5f6a763e1cc178bd902c8cc42.nq.gz
│   ├── 35527f430c102f164ba1458ac07af6379799f466.nq.gz
│   ├── 3954d6f480cfdbb38090d35b963f9766ce9bed63.nq.gz
│   ├── 44df3e986e2cc7f149a18926d02d0c0eacb3b7eb.nq.gz
│   ├── 4849b1d7f39c6ff4112170edf67fc38c1f72351a.nq.gz
│   ├── 4d44165c7d2a5d793a3ccf3592be5ac9d24b0da2.nq.gz
│   ├── 4f2d3163ac176e6e4faaf8edac297a575bab2f64.nq.gz
│   ├── 554f840cb323bcd157ecd9b9ceedd690843f0f19.nq.gz
│   ├── 59d7efee242ee06b9a3e19845d8ee25a9682ce76.nq.gz
│   ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
│   ├── 6101c71950d607bb2c3700b8335ab4cdb9982747.nq.gz
│   ├── 61c2169b412fdc12513c73650f334a9f291fae49.nq.gz
│   ├── 6600d24791faad63f3f965f21c38a9363d4b4fc0.nq.gz
│   ├── 772099cf4c2a014c05287a3d6d866c6d775b96a6.nq.gz
│   ├── 825b94ece6d854baf406d83d35c9ea89ceefbb53.nq.gz
│   ├── 874026dccd0410377c7aaadc33eddcde11106f6d.nq.gz
│   ├── 887a2c18f01df0784f690be728f22c1f9d1fa5c4.nq.gz
│   ├── 978b509e558287cd43e5c06ab41e8b808942e795.nq.gz
│   ├── 9ab12d6fb5f0f462c8a57c9d5511019e7e89ea70.nq.gz
│   ├── 9d5280b935a1cde1129b27cfb71462363d14bd14.nq.gz
│   ├── 9eda156709711f3b5f510a9b9fa993cc5891fdf8.nq.gz
│   ├── 9ef7a294f4c711ce84cfe415fb9bad1b273ea8d8.nq.gz
│   ├── a5e805587e1e688e8614083e03424a00fcdb52f1.nq.gz
│   ├── aff22b26fb1c6ff50c18c245726e10627b7de349.nq.gz
│   ├── ba9a4f027a4ad6196319151c794be1136d7190e5.nq.gz
│   ├── bc2e9a3e07a147c85133d652c0c382913c07f169.nq.gz
│   ├── c7ea19a53cbe5342f6bc49d2045143995958e774.nq.gz
│   ├── cd7cc80adfa3716cfa878331fb2e628980053dfb.nq.gz
│   ├── d4c70078e401a0fe4b89a8ea52c61d7693c7c253.nq.gz
│   ├── d7890a54cfb3863a1a577ccdf7e1c2ea7f47144a.nq.gz
│   ├── db031f831198a339eb864a75120b77d2ac2512d6.nq.gz
│   ├── dcabd47f94e1f0996d83c147f3afd5ff5f6a4d4e.nq.gz
│   ├── df784fae57f28cf0ce9fc276d9f99d4b7c32e0da.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8eb01ec33ac0200ef526ed34ad79ad09f3afb6a.nq.gz
│   ├── ed45118232fd8a1c1fd6510eb91f5578795cbc15.nq.gz
│   ├── ef0fcee09ca7145e0461dbb0e1ea7d77f519e694.nq.gz
│   ├── f03634d01b0abd8fefc96131be3e6c80f147b845.nq.gz
│   ├── f27d44e502a02c9f6700f8f17aa7db112b082d7f.nq.gz
│   ├── f2ac5123e93306aa8868616f7b1e2f7f9de7ed5d.nq.gz
│   ├── f3a055c09d499d9c22f2837ffbee0bd90cb306ce.nq.gz
│   ├── f3cee5d7652ca43b30046dec640889d52fab737e.nq.gz
│   ├── fe24ad646cbcb97d91c12070967756d11a59102b.nq.gz
│   └── fec05f165f4f324b7333db8cc416eda0610e47d5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 908d2d94d21a30e77f24c2efacf3340719d54afb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 58 files
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

[xarray-contrib/pint-xarray](https://github.com/xarray-contrib/pint-xarray)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
