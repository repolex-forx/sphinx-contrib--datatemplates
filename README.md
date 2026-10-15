# Repolex Knowledge Graph of sphinx-contrib/datatemplates

RDF knowledge graph data for [sphinx-contrib/datatemplates](https://github.com/sphinx-contrib/datatemplates), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/datatemplates
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2ad0b634fa1a8fedfc87d8635bb3dfe57f2c845a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2ad0b634fa1a8fedfc87d8635bb3dfe57f2c845a
│           └── chunk-001.nq.gz
├── blob
│   ├── 05615dcf3112598a300d47f1d24dfe9485d5c9f0.nq.gz
│   ├── 0a21b615bc120744e7d484a2ea4c5d995ce9787a.nq.gz
│   ├── 108fc255c43578daa935d9c3c8b4d5a1a4496aa3.nq.gz
│   ├── 11fe7e936150586b36e406da37056596dd163240.nq.gz
│   ├── 190a089f218d5aac600ef48b80d2bc91141b1cb2.nq.gz
│   ├── 1d235aa5eda4fab97c505ccfa8cbf8ad0d24939f.nq.gz
│   ├── 1ed74973490b3b24a290720580728db0d9c0589d.nq.gz
│   ├── 20b8ed20e4d81b805d06c2c1023278676257223f.nq.gz
│   ├── 2119e508e4726881f8e580c2ebb337cf169dacc4.nq.gz
│   ├── 21afea53b038a73c1a233ee0e34c2d5a9c90435d.nq.gz
│   ├── 2318430c1e42b779f1373a9bf8dc9ccb810789c6.nq.gz
│   ├── 245d5e0d1ef04766f7c1da62fef7763128233336.nq.gz
│   ├── 278166aab7417496a66eb7aa05f74a7253cb19e4.nq.gz
│   ├── 2c0ef4fb5f3671a069006889d1e3b773768f9b72.nq.gz
│   ├── 3335ca2fa69af11f8e0134215db9aad0213f2f3c.nq.gz
│   ├── 367d1bbb7e47f8dcc3f11a24cd7b5d93e0d86154.nq.gz
│   ├── 3dfcfb0d09a3e1f81afd4a01fdab55d1c93db3c6.nq.gz
│   ├── 438dff5b3f0a411e6788420c508f6ca582fa56f1.nq.gz
│   ├── 44e83d261df4812096018bf82e319b242cd74767.nq.gz
│   ├── 4919406c1acf5aeec7e2cf195ce31b1c3e85976c.nq.gz
│   ├── 4ca2989548bf736be265a1c45b4b74b076b84b32.nq.gz
│   ├── 4daf7d946180ce5a60a6b1c33b78f60a2bfb7b7c.nq.gz
│   ├── 4e6b8e28b18b7cc1c89440b4bc103557c9002e4f.nq.gz
│   ├── 50d102878b116663a7ca229587f1ed0b02741e36.nq.gz
│   ├── 510ef19317e60afa0980e677617c202e34b1fe84.nq.gz
│   ├── 51f7c928a7163d110ad0d9f957c3d64de133b83b.nq.gz
│   ├── 528e53ccd5f7e46a3480bb64d836b94dc4894d51.nq.gz
│   ├── 55105a09e804524c2b5b0939c3fbde4ecd65df7f.nq.gz
│   ├── 55a0733bc65c3afd7a20d2ff79954f119f7e2c5a.nq.gz
│   ├── 577e5a0b7520eb545ede571c7298124b8307cf87.nq.gz
│   ├── 57bf4c738659e5a90d0d2f19fc39a744c9862a72.nq.gz
│   ├── 5fbc1fa4f2a411d57667c784e036b84bc76aa531.nq.gz
│   ├── 624edfaa99c80d7c6479a856cc6196d04c30b810.nq.gz
│   ├── 62cb45064d307d891280f7a21395dbaf690c94ef.nq.gz
│   ├── 67875cf39924dce784957cf5e294dd975dc37c60.nq.gz
│   ├── 679aa535f6a97ef99b13ae04725c8a6e75710f56.nq.gz
│   ├── 6fa54da467d49bb0750f85515816499410abb891.nq.gz
│   ├── 6feb4f7a1b0b906c2f613ddaa0b4ff959a8d55e7.nq.gz
│   ├── 7072235886654c6c6ae6e70b317f1558aeaf75bd.nq.gz
│   ├── 70a38becea01965b1896be01f3912a6b61be3403.nq.gz
│   ├── 731b3c5f0e406d36e19bb4d1f6f27806526827fd.nq.gz
│   ├── 78a1837385de1c9ce47d212f8342ba740b7186cb.nq.gz
│   ├── 7931cab27da337955710e6d91eaad5f3ea5e1167.nq.gz
│   ├── 79e2cd149fccc02b35381611ce2adfc78cd23dc7.nq.gz
│   ├── 7b6f226b4446b65f900d7b58ef004f35b8f851d1.nq.gz
│   ├── 806159c75f4383b5dcd4c8dd53522c188b49e15c.nq.gz
│   ├── 8090b56e2eda00f9571e06cf0f96f7c636de1538.nq.gz
│   ├── 8be986bd65ac65b261a4c60c34702c2f59e455d4.nq.gz
│   ├── 8e03fa2acb5c090ced426fa03d3f36c9e25b920f.nq.gz
│   ├── 8f9ad39fabb016420c5658894e56fe9360072069.nq.gz
│   ├── 9116aa4048455ee563339c3c945220fefafe0286.nq.gz
│   ├── 9aed68327d09e73515faa7eb170401b9174b873d.nq.gz
│   ├── 9d3be9b16a53ba56721647120b54d3e681b947df.nq.gz
│   ├── a23ba66b81f35781fdc291ba71dd964d078aff09.nq.gz
│   ├── a712da2f482262b0141f907875dc512030072a7c.nq.gz
│   ├── aca3e8865873587975d56687e574da03d9187d09.nq.gz
│   ├── bc151c795fd5e13bdcbb4188750b252a854af387.nq.gz
│   ├── be626c62f354b91f313bccd5fea0daa666aa95aa.nq.gz
│   ├── c08cfbe3e6f5560cbf46fa637b2aad1fff31398d.nq.gz
│   ├── c1110c1faa4e5f41d0a5e45bab5a125cd2a70e7a.nq.gz
│   ├── ca1e1dbcc094d50f3bf996665494ada34470ad00.nq.gz
│   ├── cc335674203c560347d1777219737eb435425181.nq.gz
│   ├── cca331369db4aacb640d0578c05db5f3c632dc7e.nq.gz
│   ├── cecb680056d3cdbfd40bf2e1eda79350580fad48.nq.gz
│   ├── d32d623d7fe3f216d068d9b10d67e2498a94c977.nq.gz
│   ├── d4e87172adf013250e5f86f91d59e09d1ca5f28e.nq.gz
│   ├── d5e6040f09aad3a67052c4ce106c58cf5f89c9b8.nq.gz
│   ├── d9bc9922c9b474d4949fa62b06ee8b331b207a7f.nq.gz
│   ├── dea9715f3497bbdd1028dc7f6a515b8569c77681.nq.gz
│   ├── e128c43d43c421c73455d04a6b20e35d0de86789.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eee9f3e3ed66a017445c3f5518327f033359a6f5.nq.gz
│   ├── f09ba8a3046e5332c384d88e39ba3cf56df6982c.nq.gz
│   ├── f225751c45fb4d46db665ea5344c4974c42fd53f.nq.gz
│   ├── f635ce49733406d2ef7102e17f78802815b20f11.nq.gz
│   ├── fab615a5474ab3040a3997c9d5f4352af2760fcf.nq.gz
│   ├── facb5234696d9f107218484872ee6bd4a675f67b.nq.gz
│   └── ffa42546cd2b0c82e3a710410fb696c9174783cb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2ad0b634fa1a8fedfc87d8635bb3dfe57f2c845a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[sphinx-contrib/datatemplates](https://github.com/sphinx-contrib/datatemplates)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
