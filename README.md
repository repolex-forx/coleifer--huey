# Repolex Knowledge Graph of coleifer/huey

RDF knowledge graph data for [coleifer/huey](https://github.com/coleifer/huey), parsed by [repolex](https://repolex.ai).

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
rlex download coleifer/huey
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c5afa051a9663be479669e687c7460bdbbfd204d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c5afa051a9663be479669e687c7460bdbbfd204d
│           └── chunk-001.nq.gz
├── blob
│   ├── 029503ef6e6c3f5e403eb19d8e24788d823ed826.nq.gz
│   ├── 05a42c713d01d73fb88c0f29cb0ab471e00755fb.nq.gz
│   ├── 084523658c89ebb97a8737e52704d59ce1a3333d.nq.gz
│   ├── 09096c4c930d1ab0adbbde41a0a872e239456678.nq.gz
│   ├── 0a32cb64fa5121045a9204a7afecdc4dfeb3db46.nq.gz
│   ├── 0a4ba7c92777851dc03331c438119e2f9ca2fa23.nq.gz
│   ├── 0b9f037fc38615d2055ac1fdcc3903f1e9e6a61c.nq.gz
│   ├── 0bb21e3163f4d3788e607b31cec80d0c899ff340.nq.gz
│   ├── 0d2282634e2d535f8562e392da018df6a41db0fe.nq.gz
│   ├── 0fc6a2d81d7c7fcc4439281201fb5f5dfd420bc3.nq.gz
│   ├── 10deb0ddb1291882d6d3a912e9372007d08746dd.nq.gz
│   ├── 10fcb0dd4d0fe9fa4af19b307b42aabc216a5eaa.nq.gz
│   ├── 12affc138b7143a5fe1e1d14733e48908256f76b.nq.gz
│   ├── 136ebc3da0040294ceff6c5f2e516c14cd7625ec.nq.gz
│   ├── 156805def429a0b2511c80bd09e085e1cd4d36b7.nq.gz
│   ├── 17eb3881f987bf15119c7a9c3763d82d4bb6b1bb.nq.gz
│   ├── 18344fccb8b6a85e203f0ca2f9ffc59e968fd15e.nq.gz
│   ├── 19cc4885acec905b733f10117a2d668432fbc975.nq.gz
│   ├── 1bdfcdb9c9fe159d485927c62c4f065839a2fb4b.nq.gz
│   ├── 20ff8444c8bb92ae9a10403628ed96010bfb43bc.nq.gz
│   ├── 2142e8fc8312877990681bf25d48ef39562ee324.nq.gz
│   ├── 23852960af980ae61e8f9c59d746a0954c3b7a5b.nq.gz
│   ├── 2b8239c726c3acdc7842097ac4760f4a0981d6e1.nq.gz
│   ├── 2c87d272bfa50d0687bd187525f1ac304e460f36.nq.gz
│   ├── 2e39b81f5ebf938196acd09be82b4a3d8a045926.nq.gz
│   ├── 31672fd638e0309edc6d89764100c5fe8cc92760.nq.gz
│   ├── 33ec3339b6cbfa999a2cf32e037f105cf225b5b7.nq.gz
│   ├── 3733d3b5f6caa640a493254dff941832006528ac.nq.gz
│   ├── 38c7f7bfd7013d2fd531351553a08dac6a4f1fb3.nq.gz
│   ├── 39edd0516d346a049d3db839768d273f831a1677.nq.gz
│   ├── 3a5608820e7ad9b19a4707ad32ea558aea636f6e.nq.gz
│   ├── 3d81f0759d92aa12f63e235ebb6023132848d672.nq.gz
│   ├── 40d6f0692bed3f11a222458b95aab3133141b344.nq.gz
│   ├── 431a0b29ccf58ea26c65b60924077322461937f2.nq.gz
│   ├── 431aaee577afb29545372a8002a6fbd160f5c52a.nq.gz
│   ├── 463978e81869f8d8cf58c1b278e7280b7d4cabba.nq.gz
│   ├── 4791044446800eb52df4c8c44eceeef0a8c6f36e.nq.gz
│   ├── 49a7a3042002f7019f2d457077848ec7cb162853.nq.gz
│   ├── 4bdf657107d75f755a65bc70b17d82c7380f5545.nq.gz
│   ├── 4d3c951e617bf090db23382deadd809fb6c6b90e.nq.gz
│   ├── 4da59506a446a9e4b56994b992fb6a92e4de71da.nq.gz
│   ├── 4f446c5435b9faf6533bb15195f5d73303e4c0d9.nq.gz
│   ├── 52c04763d09301aa7c0c7b6a256a65ef0a418546.nq.gz
│   ├── 54efa91d35f5fa50590e19946a7d4e6dc7c5dd4d.nq.gz
│   ├── 554ff975e36d127d6126df61400df24ad6fcc302.nq.gz
│   ├── 57310acf9660736e0219a34999c00a92cce76272.nq.gz
│   ├── 5ae135365ad4e883b9dfecd36172fbc3114b4dcb.nq.gz
│   ├── 62fb5b1265cabdcda5bc46442970b7b7f91b2821.nq.gz
│   ├── 6414065fde14a94453fa5d915b93bcf2da3ee2aa.nq.gz
│   ├── 6448799e9fd962fa573190e1f9a45172db318541.nq.gz
│   ├── 67320062bd2f7880eb4cbe6165206a814b6f2c0c.nq.gz
│   ├── 6790b39da74942252b7ebfc3616600bcaf14f37a.nq.gz
│   ├── 67bf8d482769b76e8562e2d8b726c430d9c80a20.nq.gz
│   ├── 6bd3561c694aa763d0f6527726d524305b4f46a5.nq.gz
│   ├── 6c5d5d44e78ada9ae8ccbf17ec4f3bc72779ced0.nq.gz
│   ├── 6c9714fb4b9bef36e4e71966a51f5e09c690d66e.nq.gz
│   ├── 6c9fccbf43ae31616aa147cde2bcd3468842742f.nq.gz
│   ├── 7255cb1fb428cdf049e93f6f28b6a218feefdbb8.nq.gz
│   ├── 72996c3ae17af92107adf2b6eecd41a893a5b952.nq.gz
│   ├── 74717e51f2ab8a66cdca475e6357bd12b71e2279.nq.gz
│   ├── 7577cf0f0ecd9065c4178710d6fb975ac3f215e2.nq.gz
│   ├── 78c46a10fb3f53d0c5e93eedc50cbc3bc32f1d0d.nq.gz
│   ├── 7bde124eeb9c7ad0ca882d687a9beadc28502bca.nq.gz
│   ├── 7c7ab1e2c936ddf8159b68115dae16ae6a146c80.nq.gz
│   ├── 7e0021197a5975245da2f214acd928f2d4e5fa44.nq.gz
│   ├── 7f16cb9ea3c5ee5f0390c478154696e10be1d181.nq.gz
│   ├── 7fb6ece2b7e0a08583ff6c0bb72a00e9cb78e8ab.nq.gz
│   ├── 81eaba4553da83765a0fe67c4278335eff651eec.nq.gz
│   ├── 85d054025f7cd964dffab3df38e6dd6d45f0e51d.nq.gz
│   ├── 8950c4b6e3a7947bc93a364b3951f7f87b80e6f6.nq.gz
│   ├── 897230d870cb22cae0c28b5689028cafc56cbfd3.nq.gz
│   ├── 8a4b7e740d46d03feb0d6d341a5952d3a4b8756c.nq.gz
│   ├── 8b7fce1b6a89286faefba134772c368bb9154b52.nq.gz
│   ├── 8d0b4e9af429d932c1cbfa5ff0971f2f49a724ea.nq.gz
│   ├── 92f002beae5c273cd96cac369da1fd072dc2ad43.nq.gz
│   ├── 95150f1d9e5831fcc510ca17b13f66a85228a2a8.nq.gz
│   ├── 97c53d34994e074a16bf31851a463172986d6cb2.nq.gz
│   ├── 9840bafb73fea8eeac2f0f03790f71be533caf0b.nq.gz
│   ├── 9b1f38f6f8b7d0973b2e6289e73248a7a7fe008e.nq.gz
│   ├── 9c5378c779abdf9bd4fd64bcb01b8af199385250.nq.gz
│   ├── a34650ccaf617c5cd1a01f8cf40d923784b9996d.nq.gz
│   ├── a4397222b24730fa76c9b5f31ee0b594b2fd972b.nq.gz
│   ├── a7f92fca7b129a3182bc0c622d44aa034cd5c52e.nq.gz
│   ├── a821c192f3e79ead460f0112a75183fdf7c1e0ab.nq.gz
│   ├── a904ae7bb504aa5d67136a88dceb0a77c0c05ab0.nq.gz
│   ├── a98cf1aed24e91a5a8fad241bd32ecc2b7da5b77.nq.gz
│   ├── a9a09fd04edc6ba5300ddec30f3a50faeab307d5.nq.gz
│   ├── ac971223161148ac98c7de2650008778df4cf573.nq.gz
│   ├── b0cb9df9effb81ed60e0066c71ccf3b584eb09f7.nq.gz
│   ├── b0fdbebf72320296858c5876bced8299f4e09b26.nq.gz
│   ├── b130797f7e4d21e3635dcb806493573a9f126810.nq.gz
│   ├── b578c341876d0f2f4af961527c7647149381f16a.nq.gz
│   ├── baf38a177bac4038ba24a60c1a0cccb88bf94a28.nq.gz
│   ├── bd2002cf35059019034ad173b889981200859b95.nq.gz
│   ├── c0dd1afb901f77a85f9f978e5da1ba792a01d59f.nq.gz
│   ├── c22479e045ddf890ec28f16f34acbd769faf1ae4.nq.gz
│   ├── c3f316ad0932d16e6d26b3427a2d081346a42f43.nq.gz
│   ├── c48c218d68a6f6c797c4e048e2f9eef79d2d906c.nq.gz
│   ├── c5eb47ecd6921bc48dc9795ea338ac4715a0be5a.nq.gz
│   ├── d165e06f720e8f59b4f31e8d001c2f45541183e6.nq.gz
│   ├── d358d7a7d33df14a27716efbcfd4e229e5d0da61.nq.gz
│   ├── d3cb0ea5898a3e7ee4b6cee61848d1ab048e17db.nq.gz
│   ├── e07f12a2c3c857f00b05aec74880a12720c412a5.nq.gz
│   ├── e0a2a02822230e69d98c9b99db4ecb252778a72a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73357069afbdd9bf8baf2c3af524dbfafa9686d.nq.gz
│   ├── e7af990ad8b62f08cd2b624ada7357aa12cd9df0.nq.gz
│   ├── ea63853f30118c80eb79b87637e204f59c315093.nq.gz
│   ├── ec7a1bfff50748c4e7b93e837026840a56f3adc3.nq.gz
│   ├── f02f967909d563a7d4caa0fda9b8048eda63e648.nq.gz
│   ├── f2f7402923e96d3276755e47165f8730e523c678.nq.gz
│   ├── f427ef0952e57248cc1b40585d38185ab1a647a7.nq.gz
│   ├── f505316b47a0d81a113128eb531efd94342b0a12.nq.gz
│   ├── f97060bf381f2a7fcb02a022c985990d76e48b9f.nq.gz
│   ├── f9efe3f339c17168634d4c0d81f47bf3be8ac322.nq.gz
│   ├── fa0553ed2078b44e22a949477a51d1f29e6bfc21.nq.gz
│   ├── fbaa44000b58749640bbe39dcc9cdd58396400c5.nq.gz
│   └── fc239521224a7043912ffa295459bb6736f9dd84.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c5afa051a9663be479669e687c7460bdbbfd204d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 126 files
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

[coleifer/huey](https://github.com/coleifer/huey)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
