# Repolex Knowledge Graph of astropy/astroplan

RDF knowledge graph data for [astropy/astroplan](https://github.com/astropy/astroplan), parsed by [repolex](https://repolex.ai).

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
rlex download astropy/astroplan
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7b1c154a79f619069bbbfe82e57eea5ce6444c5c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7b1c154a79f619069bbbfe82e57eea5ce6444c5c
│           └── chunk-001.nq.gz
├── blob
│   ├── 03886de1970f1cf14b88162e7bb9ec3a4ef3d373.nq.gz
│   ├── 0530f3318668d392226dcd55599e2bd1837031d2.nq.gz
│   ├── 06bf71a26ea4b7b405c7751863c06052fe73b227.nq.gz
│   ├── 0b92e8f366d9bfa914a32e01f17cf871de8b6875.nq.gz
│   ├── 0f63b0af1161c2f18c9517fa11e5f9ae2a91f0cf.nq.gz
│   ├── 17b74f8445d2e8c79db72fa58541d65a2c966e6f.nq.gz
│   ├── 1c07ead69b2e33d300f7616e451c0ca1c3290d82.nq.gz
│   ├── 1e3100b0e8c9dcea80646b404f42a7c5e065949a.nq.gz
│   ├── 2541a13901ac418fe4100e8cbfc736cf88715966.nq.gz
│   ├── 2aec964a91427d9419c8b2599eb952d215be0171.nq.gz
│   ├── 368dd8237b942d533190c66916d1df17ccd5b037.nq.gz
│   ├── 3b2bd46797658a9978be71f85ec8b38802357029.nq.gz
│   ├── 3e2c259bd27f060c7bdefa54b7a27656ee3c7642.nq.gz
│   ├── 4977c01f3c0e68974e64fa5fe9ae10136d27afff.nq.gz
│   ├── 4982cbf370743d212cb3c460ee57ed6f0a8b1de2.nq.gz
│   ├── 499b82cfee09bc05e48bd6bfd94f2d8d313b629e.nq.gz
│   ├── 506bacccd9be49065cf99887d17de284e7ea6bcb.nq.gz
│   ├── 5221b36777f82fd6bc5431f1e30582f5c6c33dc3.nq.gz
│   ├── 57f8174a2a0781efa73f24998246a356562ff2f0.nq.gz
│   ├── 5bd952bbadb60c5649749c9a383e7e848ed7d2f1.nq.gz
│   ├── 5bfcd874ddb010189f9c574d508fbd4ffe3cebb7.nq.gz
│   ├── 6073d4fb580edeabd54dbf2bbbba415e61d73a26.nq.gz
│   ├── 6b214a5c09d3a2ed5399a65ba6100bdfd0b070ca.nq.gz
│   ├── 75db0dd8639e0d3821e87023f4b039ab2511bd1c.nq.gz
│   ├── 7e8988e28b0663fe1bd2aca85843ca4853629e00.nq.gz
│   ├── 7e95d757b6755e7f98909cbba15beeeb55e75e72.nq.gz
│   ├── 7f949f57207b59fda7b889dac4f2e0049b9f677a.nq.gz
│   ├── 8413a505c3fef84761baca942d1391415dd63a97.nq.gz
│   ├── 8c0d3fa34ab835f9e5312ad778712d7bc213ac5f.nq.gz
│   ├── 8fda4a2bebd26cd70a637c39b8644939a0bf4096.nq.gz
│   ├── 9186b5e42ce16b5068e6df8e98e79394cb1df0ee.nq.gz
│   ├── 93dfe92b9c98e009c2f75b6477817411d3a15585.nq.gz
│   ├── 9773c61edf4ec84d1ec74d8d6193b1c93e5321f0.nq.gz
│   ├── 9a3c083e6f95ee1801bcbbb2dee5633f652ec67e.nq.gz
│   ├── 9b43a50af3f064832013b20b1a4b23d118d2de05.nq.gz
│   ├── 9cabaf5238d62b16f3ff3c1fd828130815f33324.nq.gz
│   ├── 9d3eef7e8e7dcf44ffde324f215054707dfed653.nq.gz
│   ├── 9ecd65dacf7866365583dfa503a6e474a642ec75.nq.gz
│   ├── a3cd1203037210c83cbebcc263bbd060f961c5c7.nq.gz
│   ├── a86b47935a8cc0023ecd8ed78e116b819029cda0.nq.gz
│   ├── acfe92c48f8c76aa2b57b3d2801ec5220858faf8.nq.gz
│   ├── ba2dde4756afc986a4c45699f7aa74fb788270c5.nq.gz
│   ├── bad7a41d3bd1b1281f01e13b4a412d6e7ec51483.nq.gz
│   ├── c4d19d530db7f948d99004e73e4f5831c1680a6b.nq.gz
│   ├── c8ad7c763606d225f5d84823083bfb3c1ef73f86.nq.gz
│   ├── cc8f7e50fdd0578e728a13bfe9ab4a7466b616fe.nq.gz
│   ├── d048742c5ae6f6593fcf3b1582946aa59f0804ab.nq.gz
│   ├── d8f1857f93097019788ca5474f81f0a8692600eb.nq.gz
│   ├── d9bb930ec0a9999cd5f04ac1f65409ff8a37882f.nq.gz
│   ├── df810cf3bbb11db37d98c7343a37ca237d9edfbc.nq.gz
│   ├── dfee7d85c3d65d6d54ebe4ee480e0a2851478cb4.nq.gz
│   ├── e4db748af44c5a4463bf9834f47ff30f2541798b.nq.gz
│   ├── e534e5c56a7665c18bba8b3ba4d19c99a8ebb732.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e82c7e5e75ba976698f1e872c94707607077bf3c.nq.gz
│   ├── e972842078dcf61063b91ee12b7e1d324051c39b.nq.gz
│   ├── ea51f0bdc853fd2231755e0fc35ec762338ed086.nq.gz
│   ├── edd6f27088f4f516fbac85d9a9e2a21c2d70e61e.nq.gz
│   ├── ee1fec041afd0f59940955d867e022eb4214c346.nq.gz
│   ├── ee2b7ca55a864b4565d191bb952be296c5542dc9.nq.gz
│   ├── f38315b22a4929c146aebfb5f2671bb16c003fd7.nq.gz
│   ├── f4dad54087cd2ad6e586d09dcb738a2e52b6aa4e.nq.gz
│   ├── f6bd40d281a67aa2d97251c236ecbb948f858552.nq.gz
│   └── fce489157e01b7ce4cc4f3229cbc9c70ce973f58.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7b1c154a79f619069bbbfe82e57eea5ce6444c5c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[astropy/astroplan](https://github.com/astropy/astroplan)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
