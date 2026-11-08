# Repolex Knowledge Graph of canonical/kratos-operator

RDF knowledge graph data for [canonical/kratos-operator](https://github.com/canonical/kratos-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/kratos-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f68a77402cbf15eceaf4736b91c023be90888160
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f68a77402cbf15eceaf4736b91c023be90888160
│           └── chunk-001.nq.gz
├── blob
│   ├── 05646a76ebdd59c4c1cb443171a5230b9e876b45.nq.gz
│   ├── 0d451b22d1c9a3b3a0de0a3d06160bebbb5091e5.nq.gz
│   ├── 0f16506e42b0af4ef4a5e6bcd10503ed36cabc91.nq.gz
│   ├── 0f9fb02ce3cf94419f3a3767bdbc97c1e02d0016.nq.gz
│   ├── 13ec6ce68ff3b2595f1bff8d2eac5ad5b6775fa0.nq.gz
│   ├── 159b307c9a5cac1bbce3ab822c020fe0bdf3fa59.nq.gz
│   ├── 163a87881c9bc2c61d9c41bf0aa781d1f6045485.nq.gz
│   ├── 166bb70f891efe5f46673da9763dc00f1866d8bd.nq.gz
│   ├── 18b3e1857c07e0c0bacd42e75bc5a290eccb2f1d.nq.gz
│   ├── 1a5f0e77f4c103012fb323e34faeae62c1132c58.nq.gz
│   ├── 1c6c885415b657dc4d062ecd611d10817c580df4.nq.gz
│   ├── 1f5992268bbb06ad69656f4a087ff42a97167c79.nq.gz
│   ├── 21ca85a55dc3b10d04bd9d8538b20135a878b548.nq.gz
│   ├── 24ba0d6bdb9982a1d266d2b2b5e60e6c1510149d.nq.gz
│   ├── 25e92d6ea236482e22444bd5730e0656fbd52c1d.nq.gz
│   ├── 274f23c53c3c01b68169b2037f5d28a4e080a054.nq.gz
│   ├── 32eb0c9190df80d87141186c71d96611fdc4bdd7.nq.gz
│   ├── 334ecd0db888ee20f42fdee1ace15785b132fd53.nq.gz
│   ├── 3539a40f42773b8387279f442fdc73aff4e0c178.nq.gz
│   ├── 35c6ad899e1777bfa21530e7170c99687d072975.nq.gz
│   ├── 384fe531919e9076911661e654b5c84d76340c9e.nq.gz
│   ├── 387ac6a47738bcce3f686ea6d43178ab2197e414.nq.gz
│   ├── 3a557378ad321375e4b05b7ae66e4ed7fd8d36ed.nq.gz
│   ├── 3bde77d20eb48a6fb037204b2e7d36ea93e72bae.nq.gz
│   ├── 3e2e9bd20b53779d85c8ff1f68e1773f406cd2c1.nq.gz
│   ├── 3f9bb1e2fb6657282911a432e13eb2aab7043294.nq.gz
│   ├── 404359c6585a362931f246a7606810dfb142ee62.nq.gz
│   ├── 43563d9a6f71cc4619960633ba4fb998fdf6bda8.nq.gz
│   ├── 454117ac283526fc4eb226d21e35061050534495.nq.gz
│   ├── 479d18231934c5a9da8a9d5242d16c2801776c98.nq.gz
│   ├── 4a258ac2d2bfb8fbd50f54d0930b41893ed08d81.nq.gz
│   ├── 4fa549f230343bc90dcdbf5282ba1f45f20140b4.nq.gz
│   ├── 507860acb48bd0bc5c906f3ad84785817df206a9.nq.gz
│   ├── 521efdc84946a01cc45abd0dc274f9cda3e76678.nq.gz
│   ├── 5232dc5dbbeefc3de9bebb5f4896da7ad9a54c29.nq.gz
│   ├── 5293e562c2bb3f7370efc88c86d72f46bf88d4a4.nq.gz
│   ├── 55969d643048afbcfabdfa8a3314e271294fff2f.nq.gz
│   ├── 585f06dd79eef8eb2d2d5ed52e5d4bd76ccebaae.nq.gz
│   ├── 5b17e86f0c523b69cd93f4e692a546f71be99a5c.nq.gz
│   ├── 5b8558cc899028e5ea26586ab58997af6d735ec2.nq.gz
│   ├── 5be1d93158856891c2a493ea37cb1f116fc81f61.nq.gz
│   ├── 5e92b136cdfd49e3a4941c219ec8de15964d3d3a.nq.gz
│   ├── 6296e21035af62a275281e1f4ebabd407785ff13.nq.gz
│   ├── 664ead0dcc8305c3fa5c61b3cfea41b699cc6412.nq.gz
│   ├── 692b675b9bec232be62350594f04f129039aa3d9.nq.gz
│   ├── 6ccd559eabeae93e4d23215fa450130fa9b37ace.nq.gz
│   ├── 785c345bbff2683f4b49d6817da5a19ba206cb22.nq.gz
│   ├── 7ae77e936dc43a5e327ae47a7f8488214e2d6d97.nq.gz
│   ├── 7d072293dcad68d9f4abb651db0303132a3cb686.nq.gz
│   ├── 7d11ff8b6e43d82ee44c113803899c685d771795.nq.gz
│   ├── 7d3dc2a52f39e3d5d86fe2e3645711ed0af00d9d.nq.gz
│   ├── 7e9d50461abcf8053278e38c1eb264abc49fac0d.nq.gz
│   ├── 7ff4cebf4f0afe30dc9bcf791b3b1ce5ec1c726c.nq.gz
│   ├── 8158442001d2f0c78966ca235a9c1d453c3ce8c8.nq.gz
│   ├── 82c83f5f4f94ae221c3d64cfcfb3fd3f1490c3a3.nq.gz
│   ├── 88e29337a708747c933a0369f8438be88fb553ee.nq.gz
│   ├── 8ab7f285e27e818741f688c454c3fada4f29649d.nq.gz
│   ├── 8effef09eb14498502834db1077041d942488e36.nq.gz
│   ├── 98088a2fd073e864c5e4f9429db81fab5e24a960.nq.gz
│   ├── 9a802181673292b323c41b93eac737454f1c8c67.nq.gz
│   ├── 9f62b95f6acfc01fde9f39d6841e109f67a47b6d.nq.gz
│   ├── 9feb84e69f246bd1555d224f55bf58187d427e90.nq.gz
│   ├── a19fba286c8e98041deeca9682cb88e5f05f98ae.nq.gz
│   ├── a32cbc0761412d2c5b1e4fe1e2deebde1f7b7504.nq.gz
│   ├── a8253f4eda5d27b87851bf36e8dc7c48f7e8c077.nq.gz
│   ├── ab3371c7f57d9e0941f05bd6d5f27874a000bcae.nq.gz
│   ├── af540cc9946dea8875deeed1d2c1605e22ccce02.nq.gz
│   ├── b2348b9fbfdc4eb154566c80f844510446be1d02.nq.gz
│   ├── b74807804320970d7832f6232051d35fce35a703.nq.gz
│   ├── b80555bbb19accaadb130c50317b025d74f6e0ef.nq.gz
│   ├── b9fc5df5881e8b00c7a2ae34e98d0b17b41eb527.nq.gz
│   ├── bba7f5be4ad644abaf46486fb7c2e18c1aaae468.nq.gz
│   ├── bbe86cd9dd5584483b36da03816c5072108e9142.nq.gz
│   ├── beb553886341d0d90e7e7c931220719ab8dc7347.nq.gz
│   ├── bffe3324eaad669c2e5f0ccd841f22bff0e8dea6.nq.gz
│   ├── c0645ed0c3a2d17b81e918cb81966003cdb16cef.nq.gz
│   ├── c7cedef565a7c06e0cab82b7421eabfe1ed659ff.nq.gz
│   ├── c93f3225755edbebbbdaac1eb71de205d4451abd.nq.gz
│   ├── cc946fbc5218b240e86a5588c516f1dc1c823f8e.nq.gz
│   ├── ccef7258eec17c6108948d6a666ae13de3a9dcd3.nq.gz
│   ├── d3d0e67e619de872c70f41b9184e384cf753bf8f.nq.gz
│   ├── d3d593452a9fcfa8c51d6df0883af4129ac165ea.nq.gz
│   ├── d41f000e117bd1bd1afea92420d87c6b065f9c7e.nq.gz
│   ├── d45673d0ea5778c3ecccdf5bb0280992ccbc2ba2.nq.gz
│   ├── d5c2aa1692cb82028dac4c84b5eb6c515894d785.nq.gz
│   ├── de8e5a6904ca865317bcdf0d814d8ceca4f22227.nq.gz
│   ├── e5fc5d4b937d0693686fe607cfa47e3ca840dab7.nq.gz
│   ├── e639a8f03d1a433ab19f486d5818c47420998a50.nq.gz
│   ├── e7ef36ef24f293802f98eb2ed4c8ace11a82233d.nq.gz
│   ├── ec05185487e1b1236925f6f90a4be5b6e6af9fa4.nq.gz
│   ├── ec3995047a98381ae06569a0ddfff4f9be670958.nq.gz
│   ├── eccb38dc85d257a8ed459b997295d85f3755e512.nq.gz
│   ├── ecf381ac60ef83f3f3fdfa17a73cb656b256ceea.nq.gz
│   ├── f39011bf0731a795cd537412b387e35a8d791550.nq.gz
│   ├── f7de1d6594c45e80c7973322181d5aa630dd2dff.nq.gz
│   ├── f83a929f6f3a54722cd45e0820346b9ed3b7b486.nq.gz
│   ├── f849d85841908f003664a296aac67898d46d4f18.nq.gz
│   ├── fa65f2a789e5144ec2f5c700e24cbaad862feca9.nq.gz
│   └── ffeec6e52ce561b3043a2d878cab6f59201e8a62.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f68a77402cbf15eceaf4736b91c023be90888160.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 107 files
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

[canonical/kratos-operator](https://github.com/canonical/kratos-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
