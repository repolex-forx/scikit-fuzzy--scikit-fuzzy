# Repolex Knowledge Graph of scikit-fuzzy/scikit-fuzzy

RDF knowledge graph data for [scikit-fuzzy/scikit-fuzzy](https://github.com/scikit-fuzzy/scikit-fuzzy), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-fuzzy/scikit-fuzzy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── be7e344f3ce65845e39922aa5fc1af7412d01944
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── be7e344f3ce65845e39922aa5fc1af7412d01944
│           └── chunk-001.nq.gz
├── blob
│   ├── 0185ce6b7b7cb18a04636115127c9ee48a795630.nq.gz
│   ├── 032cb0fca204b689d016666bc48f76937f607ceb.nq.gz
│   ├── 064cf8fe653e1ace1ebe40cbaab4ef5b6344fbff.nq.gz
│   ├── 096841fddd0c88af5ae2068cd16c11324581fa1c.nq.gz
│   ├── 0c7fd6348f2a8125ac7f0454176393d32115c3f8.nq.gz
│   ├── 0e74d2bfbe9816997a84df10c17fefbacb1604a2.nq.gz
│   ├── 105faac5685f987e4e4ed6528acad59ae307e06a.nq.gz
│   ├── 1250052eb53ef562bf7191c5225b9ca3afa98ac2.nq.gz
│   ├── 12eb642b5291a5cc69f7a8eae2fbd947bd47de33.nq.gz
│   ├── 176ab33e44dbb8e017679d9db2a739fdbd6cd4dc.nq.gz
│   ├── 17c644dd5ba46737e8edc78fef3c561ae2369dfd.nq.gz
│   ├── 1947c45c9894f7791abc4334673506c909b72a46.nq.gz
│   ├── 19add100225c1997f4d4918ebefece1f1900f664.nq.gz
│   ├── 1f175d06de7e87f316c6306e09e9b3597c4b25f5.nq.gz
│   ├── 1fa134741d2fdf478e3b3100083e355da27e640e.nq.gz
│   ├── 225098f3c6acd153d49f362944860a176b3b1227.nq.gz
│   ├── 23de444b3f1a9c6f0434d2d0e0b3f9eebfe8e9ec.nq.gz
│   ├── 24c565f809cdc36ace1bc9ab9603fa0648ad7186.nq.gz
│   ├── 25790d947278700afa703fb7702f8e0b7115b7bd.nq.gz
│   ├── 2624b48fa80dc4460c625e352c067ce7d9958727.nq.gz
│   ├── 2689339b89dd391ff3f19861c8ae8f5537defb4d.nq.gz
│   ├── 2bf14e07e80139d7cd8dc74874087ba868fdda60.nq.gz
│   ├── 2d6670edc37d015c91b03cd2b409927c0ef07bba.nq.gz
│   ├── 2e469309b63a57cab05abaa7ec1aead22f6c245f.nq.gz
│   ├── 2f40378ffb13ef54a2acf146fdbab5e2fd6742e9.nq.gz
│   ├── 317222f0fb713b7b33cad6e215bb75a95ca9ed7b.nq.gz
│   ├── 32644ccc7d3dd67c0de138dfe9d407d3cacc2665.nq.gz
│   ├── 3865f8f05559c5d83f52a34a75b581303a041683.nq.gz
│   ├── 3bafe2d58224aaf3fadd81fd1249cf71361458bf.nq.gz
│   ├── 3bba2108c71cf4cecc0499b3d82ae5cd615dab76.nq.gz
│   ├── 3bf6484a29d8da269f9bc874b25493a45fae3bae.nq.gz
│   ├── 3ebab89379fcae56c422a59c6720b51ba1793c7a.nq.gz
│   ├── 3eee0b3541f5578f0fdbb0c75ef4ba566e9089f3.nq.gz
│   ├── 3f7554a3b0e94c532236a50afc9086687eed2182.nq.gz
│   ├── 408ba99cd6ee17629738b2887e32b4e6014c5359.nq.gz
│   ├── 46a17fa237e042ee733dff97fcde86499e3ca384.nq.gz
│   ├── 4b45f52dca2ebc4624393691aa17e6bd4ba163ef.nq.gz
│   ├── 4cd7a72e71ce4166b8ddacdeb9f01510a81e1afe.nq.gz
│   ├── 4e73f15cbf3126e656d7a584e90a4937900e68c5.nq.gz
│   ├── 4ee0edaf10b9b04c276595c557c131096a2e8270.nq.gz
│   ├── 584ae266ef62ae5b83d27c8c8eeaed30f4dd48e3.nq.gz
│   ├── 58a2ee1e2c4ee38ad1315154730e78581309b53a.nq.gz
│   ├── 5a453aa049e497fbdfe23f674f70da4568e8d353.nq.gz
│   ├── 5b31a9e903eb659c7afb0550810de5b8d63ad30f.nq.gz
│   ├── 60e85f20a8064d66ab6363a3f5cddbed9623df1e.nq.gz
│   ├── 6162db6ae10cb96778ff59f74c5470669122ac7e.nq.gz
│   ├── 68faafb2379d65dffcf3a595779e8e180e692cc9.nq.gz
│   ├── 6a7129e911ab683e9fea0b46400a7b47af74729b.nq.gz
│   ├── 6b35fec85a303d3406bd2123a52076919c4d16f8.nq.gz
│   ├── 6e17cfa585e8217bfeed535a0a438b00689eba08.nq.gz
│   ├── 7228bea336f9bcb5f4e61b2ca9b455c2ea8133ad.nq.gz
│   ├── 739d84ceb03adbe331418b0ffa6d89af301d6c05.nq.gz
│   ├── 745aa0d8aa8ee44bf0bbc77a6ea074fc987673de.nq.gz
│   ├── 753579c15ba94e2cf4e7fe9ade4557847379e241.nq.gz
│   ├── 75ae6118a655b0262c80e28742d26ead9ead0355.nq.gz
│   ├── 7654144726c48417c0092f6e74172c022c128ede.nq.gz
│   ├── 7aa01b731654527b803cccd1fa783bae9ed7ea0c.nq.gz
│   ├── 7ae6a480a54a11e23380bc92d5f427ceba2b6ab1.nq.gz
│   ├── 7daea97ee8cd8d234064457430c34fe354c1bd4d.nq.gz
│   ├── 8048b3cec3cdd76baabbbc3506c88019947b7b0f.nq.gz
│   ├── 80841dc553f75ad78f2704ed53ac0fa14d41211e.nq.gz
│   ├── 80d2b6b886e0714dcf72a15a44ce681b629b8038.nq.gz
│   ├── 8186bc823374e03b25fa4f0ecb888e677019f81a.nq.gz
│   ├── 819ca71cc67c711c5453be6d75877a7365db9fd5.nq.gz
│   ├── 8d0dc5cf4b34844f50a4d7060fb5f4459654040f.nq.gz
│   ├── 8ffbfe1f4d0540ed2ec8700487d54daaceeb1a72.nq.gz
│   ├── 9035215b9eab3c4be3699a23514b8c7316423fb4.nq.gz
│   ├── 944286728a541d333e1ad46348d48b9c0eb36f6c.nq.gz
│   ├── 94dfde0766cd45a99d7e865acd6d5b792cc9c740.nq.gz
│   ├── 958d0a49c9e9981f33f1f9c7a4a392065cf4791e.nq.gz
│   ├── 971ada845b905d9ea398b6c60091c41235e4c535.nq.gz
│   ├── 97d3300456331a4e56d49c79b484c8e72317acb1.nq.gz
│   ├── 97f39ebc13caf84aff7031e15924e61514a4f6b4.nq.gz
│   ├── 98d45c951f716d22974f10439731390c34fd7406.nq.gz
│   ├── 99fcb8ab434cdcd50b36eea1871a8329464f3208.nq.gz
│   ├── 9a380b7c5e221113597e05181a834eb6761b0156.nq.gz
│   ├── 9e66c4be8f186e214e945854bfe39269d44ed5dd.nq.gz
│   ├── 9fdef96f70c00a6c1eb17681b922d57b6b4f7286.nq.gz
│   ├── a032e90da1abf355e5cac3a8d4c28bef9d8db875.nq.gz
│   ├── a048c053c907638f70bdd6aefccbda1e2c2a487c.nq.gz
│   ├── a377a33c4f63f42018359644f70feea9c961f3a6.nq.gz
│   ├── a8d4fe0526a48d53200fbeb4f89a9224c4be3652.nq.gz
│   ├── a9969993201f9cee63cf9f49217646347297b643.nq.gz
│   ├── b3bdc6ee2011bcd329ae197585d2dc05262cdbc2.nq.gz
│   ├── b442b08a65abc5d5e78ba26c780e1e8d4e7e2c4b.nq.gz
│   ├── b66ccc0cfc3895fe7719d26929e238696d6978ea.nq.gz
│   ├── bb21219d47745bdc204570d1ac21b2de7e973f18.nq.gz
│   ├── bb71b59064a7524a354ad4d220fc79465194d97e.nq.gz
│   ├── bf2017cb5a160b7bc1eb702b64564b81e27e7743.nq.gz
│   ├── c0a4a6ebf905a9660471779d40011c819d7b1a64.nq.gz
│   ├── c3fe8127fc65ccc6fe10cb17c6e4d415706ae92c.nq.gz
│   ├── c637d87466e95d7833efb1fa6424996980dd47a7.nq.gz
│   ├── cb77ccf4e503553df7b6e653591e4891bfef5ea8.nq.gz
│   ├── cbb6fe010c2b3314f886163f36af02943d222684.nq.gz
│   ├── ce629fffa26fbdd394356752c55e8418c0a05de1.nq.gz
│   ├── d01c0b37fc9fe59bad7390c285cd01512249dc9f.nq.gz
│   ├── d029f08647a71a542d755d02d4966741f5f406d0.nq.gz
│   ├── d30d88bd1194f92e5eece87f0d500b662b8adb6f.nq.gz
│   ├── d3b57f48ae1f4baf5b3369a41d8f4a3307281daa.nq.gz
│   ├── d4d9fe2724a6a6c70b72cd1021746009a799f96a.nq.gz
│   ├── d625da56aa5b0dea61209a5e2ff53e529df63566.nq.gz
│   ├── d71699412cdd7f804bdf77c4ce7977bb1903c850.nq.gz
│   ├── d7ae6012a5e3d0ddb7865dfad0acd5382b2edcd7.nq.gz
│   ├── d7fdb61e287f060d6449e4e2b5ca74e3080c6ad1.nq.gz
│   ├── d866bd145d883e1b2a923b4007d60594a188f141.nq.gz
│   ├── d9175d426f1c96e4703e932aa3672a1833fa7c6a.nq.gz
│   ├── de878881f260d7e95b60a8ca8dd50364d1eefc82.nq.gz
│   ├── e11dc796ab0f1c0c6da71b95584a93e10b752de0.nq.gz
│   ├── e7e9d93c17e5401b8d07c61d153840e8a0560729.nq.gz
│   ├── e81f4d925a9ca93f763964391e97ba1e5fb9cc75.nq.gz
│   ├── e9a0f2781256b5ccbd220e112a28a52a4470addf.nq.gz
│   ├── eaec246838eb59e9a6a454b69c768fd88d9e1cbc.nq.gz
│   ├── ee7986cf99f118cb6d91a0198019431fc0c0eb0b.nq.gz
│   ├── f3404b890663c4cdf92682d4b93fc7c1b5fa6fc4.nq.gz
│   ├── f59e91da1f6f7512977637e69f50627424ee16b8.nq.gz
│   ├── f6b69a2b403eb49ff160d5f4067a27cb09556f1b.nq.gz
│   ├── f763f8b6852ebae07d56dab56523f662abb01d7b.nq.gz
│   ├── f83ec96df22301cbc0ead1b09ccde83e1a364be8.nq.gz
│   ├── fa9eb6f0507c8155d947b7708d550df7860a4eb1.nq.gz
│   ├── fd7a7dbff535200e1c3f4322be864d8d2d873b84.nq.gz
│   └── ffc54f354233e18551cd3910bf91a6cb9b115e6c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── be7e344f3ce65845e39922aa5fc1af7412d01944.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 129 files
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

[scikit-fuzzy/scikit-fuzzy](https://github.com/scikit-fuzzy/scikit-fuzzy)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
