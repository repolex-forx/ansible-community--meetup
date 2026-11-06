# Repolex Knowledge Graph of ansible-community/meetup

RDF knowledge graph data for [ansible-community/meetup](https://github.com/ansible-community/meetup), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-community/meetup
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0dfed587b7f1c38e5c747d16b7e188c02433f141
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0dfed587b7f1c38e5c747d16b7e188c02433f141
│           └── chunk-001.nq.gz
├── blob
│   ├── 02b7be272f7b214b9d9fcf977c3d06ec4236c328.nq.gz
│   ├── 09b09be24d1db9add9c7dd44e7a0229f74d87037.nq.gz
│   ├── 11ea9587dd6e0e26ef88336eb9c2c61369313f51.nq.gz
│   ├── 1605dfbfc49f2d6fac834a88f0b3917e017de26f.nq.gz
│   ├── 1a2c994b78a5024143b94130d286a93c8a708c5e.nq.gz
│   ├── 21c950a719e6588376533829e52a38ff2721fc2b.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 26eda3dac767ce296600526539d9656cb87e8252.nq.gz
│   ├── 2ab9fa8284b6441e3c1227b5a88236c38275ae34.nq.gz
│   ├── 30e469a6907b5bdf22575e1358f91a034c670832.nq.gz
│   ├── 332edd5ae1a455baa2dd87a3d2d649b407c1af07.nq.gz
│   ├── 3ac2f6ec4db77b5b061730187f2585191941a965.nq.gz
│   ├── 3d2f3487304b48a22070560cdb5818b0a025ab05.nq.gz
│   ├── 3d7eb54939ae47c352795ec482ba1f20c06ec305.nq.gz
│   ├── 3da205b65bec3c66ec353c7cdbbca6b4711e6b81.nq.gz
│   ├── 44f592669abe9e6b5205d2e65deed4fbb47c5ea6.nq.gz
│   ├── 4601e7efade724ebc61c58e2f73355d66a7e49f0.nq.gz
│   ├── 46da42d8d4063e9fc825f6d97ec247964face0f2.nq.gz
│   ├── 49eb125640efe91e87f672e23322219b5ee91d07.nq.gz
│   ├── 4ffd12358ad6a83216ec906a7f3811ec5524a3a7.nq.gz
│   ├── 50c3d4f07535ff5052cd79a47d659b7219255696.nq.gz
│   ├── 51c2882d8295fbf8e84644889bfe3614ef8165b8.nq.gz
│   ├── 546556ef53fc255cb7109c2e981b80fb219e0fd8.nq.gz
│   ├── 5a2e15f2c60a45c235832cd3126ec7962f227c87.nq.gz
│   ├── 5c4abb127a398c79726ce1bd4e628259218c1294.nq.gz
│   ├── 601cb88bf75cb840c2cdd6e3801354180f0b5188.nq.gz
│   ├── 6101a45a3b1c74e1da53eb9d56479048dc8acbdb.nq.gz
│   ├── 683814625d5168d790ca11c29fcf7fbe305a0147.nq.gz
│   ├── 698825c8349d23a18edbb5f90245026676e21e39.nq.gz
│   ├── 701577af4409fee2636ba039ad25246db0029415.nq.gz
│   ├── 711ca90358bb779fe0687330084fe2bf47e0cc59.nq.gz
│   ├── 73ded4db00bf6e59964b5bf0aab12a89fadd3e81.nq.gz
│   ├── 7a30aa8ce4fa04c9b29383a10211abed0f9fb33e.nq.gz
│   ├── 844258c7088287f4a45497eb1147e8f8078c9398.nq.gz
│   ├── 84f94352d24f5c7ccd6bbc3a316299c32c80bd40.nq.gz
│   ├── 859cdc822d31f64be05af4aed7eff319d5dd8bc3.nq.gz
│   ├── 9017b5a7e4a314049e2a86444fec24ec51d2b847.nq.gz
│   ├── 903c55788ef9a58cc38ebd02e76edfc6f0541972.nq.gz
│   ├── 92f278f225a2a3c864f0a9ed346b3b874f97eafb.nq.gz
│   ├── 965365d46cb139c210576370adc7e867026ec44b.nq.gz
│   ├── 97a121370fa7b9829807af8eea5d24ea76c58bf0.nq.gz
│   ├── 9f495d37b68d5d1a38ec959f9323b499d41bafff.nq.gz
│   ├── a283f3d4a9d91d0aa98b3adfb88d91f3004e1775.nq.gz
│   ├── a45b331519549a0c48ce0432b235fe6c25126105.nq.gz
│   ├── a51121d923c912fbfa3274cefb0eceff7ae87f4f.nq.gz
│   ├── a7dde0b61aa6551069f8ae72b8d4e438cef6344b.nq.gz
│   ├── abb786038987157075ce9095662d00f78a5c4c67.nq.gz
│   ├── aea84681596223fadd8dcc89400257dac1bc59f1.nq.gz
│   ├── afbb0e4f3982098e46567485acbf4025101a00c5.nq.gz
│   ├── b0de840396fabcbf0eab2cf1878d7920dcf04932.nq.gz
│   ├── b485c5876064baff8bbcc7a117ee5dcc59ff24db.nq.gz
│   ├── b4e68862166386b06e60d5151e9c016d449a6aa7.nq.gz
│   ├── b88eef3dca61d6611abfbc40e13cb0dd5710e15c.nq.gz
│   ├── b89165591563647d26d5b549a1632cd34b4d5606.nq.gz
│   ├── bc8a76fe054527692bad675e3976a172d23c5047.nq.gz
│   ├── bff37932e349b9812e72824a94932c84e3117cdc.nq.gz
│   ├── c743b3bcf482cc028696ba03c50c7a14e43285cf.nq.gz
│   ├── ca3f4cfe26f1e388428f9462c38d45b68d69cf2a.nq.gz
│   ├── cb5cb23afc0c4a885b52507c856f2a895f794b3a.nq.gz
│   ├── cee7d84f18db2640b5279b4b0330a1d8d9ecee18.nq.gz
│   ├── d10409b2dbfbbb26ddf97c0be6823f86cb2c13f6.nq.gz
│   ├── e086b3727151d70badb17a8149076f7bc2e572e6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8d6f3b46c5a3c8934ec270e1ab69d664de35cbd.nq.gz
│   ├── effc239d96d6f163a3d6bba2be9625c24e8be5e7.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f2ac5a274a70a58c2d1dc462219d347195fc547e.nq.gz
│   ├── f32fc9acef096f985889a27bf8a471199cff628e.nq.gz
│   ├── f59dd2cafa330e0202c03f1538ba8f9e56747287.nq.gz
│   ├── f67173f98ab659747d41656264291df684d28c27.nq.gz
│   ├── f68ff424dd9af862cada3ffe14081fc7f0317b5f.nq.gz
│   ├── f73de41efc6de31f183672aa672306bab6b59139.nq.gz
│   ├── f9a45137190ae28bf1f626d73c763a5b05d7ab52.nq.gz
│   ├── fb2129aa9bed8c9f693411db4993cf5a7d283c55.nq.gz
│   ├── fcf593be200553f8a30d6581cfc3bca1c3351573.nq.gz
│   └── fe4ebc736f0f6399f4ab1cbd9231aa344d1cd8ea.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0dfed587b7f1c38e5c747d16b7e188c02433f141.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 84 files
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

[ansible-community/meetup](https://github.com/ansible-community/meetup)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
