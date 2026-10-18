# Repolex Knowledge Graph of hynek/environ-config

RDF knowledge graph data for [hynek/environ-config](https://github.com/hynek/environ-config), parsed by [repolex](https://repolex.ai).

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
rlex download hynek/environ-config
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dfbfdc910e0b80bb22752571619b7ad0e18379b9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dfbfdc910e0b80bb22752571619b7ad0e18379b9
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a7b00c94e08b86c765d47689b6523148c46eec.nq.gz
│   ├── 057262b1bf99fb4b228fa07524df1aebc58c0046.nq.gz
│   ├── 09f5221310fc9a1cefc9d5e012a207b959858e60.nq.gz
│   ├── 0d6dac823ae51b5ea63e30fcbed5f80a78903a2a.nq.gz
│   ├── 0df47ac3c37baba328ef23cb64dbe1c233286cae.nq.gz
│   ├── 17d76f576cb4b4a8f13705bd8fad0657c28558fe.nq.gz
│   ├── 1c92e1a159eaad0f2ee546a7379f9c4d56424e32.nq.gz
│   ├── 225b712a156b12da68fe88e830fc685b2ae00d61.nq.gz
│   ├── 2326644eadb0b5ff3aa71741c833e218e73bf0b5.nq.gz
│   ├── 257bff6dc815d5ac33bf7b7c5924d08e51a3a284.nq.gz
│   ├── 26774ab4f1ce1fa6dcba01b2c6046eaad50f6dee.nq.gz
│   ├── 2902ab9b0220219713c74a2e92f1009925ab0b95.nq.gz
│   ├── 2909d614bd157bca21beb7b5f5edb325f5e00e09.nq.gz
│   ├── 3270562a8b4d75e7f37c5263c5755507fb07ee0d.nq.gz
│   ├── 6324d401a069f4020efcf0ff07442724b52f47c2.nq.gz
│   ├── 65c39dfad0b0ca8fc4ed38631548b1fc65506a95.nq.gz
│   ├── 66efc0fecd1554e6e4681fcb149692591f388bf2.nq.gz
│   ├── 72083fee482321b1b3501a1c4edbfed3cae3d4e5.nq.gz
│   ├── 72cfa3d548d9eabacbaffcddfab7b422ffc16e1f.nq.gz
│   ├── 756e5474edad3f0a11c8e41463ed46187ee4c556.nq.gz
│   ├── 77dc4b9026943b52568d9eaec42ad9164fbc6dd7.nq.gz
│   ├── 7c5100942aae489ca04d07d2c69a4d8f6f8470fe.nq.gz
│   ├── 7ecc907fe406b82b329475483c8b5117ccb085c8.nq.gz
│   ├── 82e66f983e5bf2334642fbdccef54f32bcfba5d4.nq.gz
│   ├── 847e6329301f96e3e2074030930c1258570955df.nq.gz
│   ├── 852021b0e7b90c558e66dd79d6468bba8fb1b9e0.nq.gz
│   ├── 97a43a9216435759fbbf2c378b57f63355b768a7.nq.gz
│   ├── a131dd2f5dc1898b7ef89b46a5724311f5f80e8b.nq.gz
│   ├── a38d0249ba67f4b8f455a21c4728703d05fc2f54.nq.gz
│   ├── aa47dbbedabdb68b3f80569ff06120834fe39132.nq.gz
│   ├── aaa02b7b270ad4500fc0c986d0ebe93175bc52e5.nq.gz
│   ├── ab78eab5c46ebd6ee3ca9e603f78ce863c633dcb.nq.gz
│   ├── b47513dd24a3134eb1a85d70ed6d445ddbb6a918.nq.gz
│   ├── b4adf1a51eb722aa1d114e3beb62989039c493c9.nq.gz
│   ├── bbfbdae2ff7cc651d4017fc6a955f5602e36dcd2.nq.gz
│   ├── c463131e5910c46973c89478697be00eca469da4.nq.gz
│   ├── c70ffe654d175ad69f2be28b0f3338f70c915584.nq.gz
│   ├── c7e545053958506d30ec8d2879cf91ed3b73d73a.nq.gz
│   ├── cbd8037dc19e1b9fa7d5164bc7c484118719aaa2.nq.gz
│   ├── cd46bd07565aa2cf3aab3580363284ba2fac0458.nq.gz
│   ├── d230d394b16289f76febc952514adb419b64cc8a.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── d6efd6974c1634d840e8d7abce620bc8adb0b34e.nq.gz
│   ├── d9caa1c693b1652b4e2816336a00e997c9e78c3a.nq.gz
│   ├── e2045f3f86476bfd57faf4cd619e8f6003ee90c1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ecb69c20d4332d49dd0331a546b3218891441333.nq.gz
│   ├── f0dd6855c139e874f5e30afaefade995380bacf9.nq.gz
│   ├── f514cc396abc9b0494449ca1cad12126e8ae8e99.nq.gz
│   ├── f6fb1988423ad3211e07a568f7d5df77281f93ec.nq.gz
│   └── fd678d8b03568dfddec074aac6673bb458bb499b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dfbfdc910e0b80bb22752571619b7ad0e18379b9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 59 files
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

[hynek/environ-config](https://github.com/hynek/environ-config)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
