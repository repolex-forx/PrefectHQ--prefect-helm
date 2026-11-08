# Repolex Knowledge Graph of PrefectHQ/prefect-helm

RDF knowledge graph data for [PrefectHQ/prefect-helm](https://github.com/PrefectHQ/prefect-helm), parsed by [repolex](https://repolex.ai).

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
rlex download PrefectHQ/prefect-helm
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 84e22f664a3a6eb678842aabfa069a01ae42b0ea
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 84e22f664a3a6eb678842aabfa069a01ae42b0ea
│           └── chunk-001.nq.gz
├── blob
│   ├── 00c2a7a1e4ba2f2961749958ffdb1881620ba13f.nq.gz
│   ├── 0540975b4de28e0df92be5032e1fc9dc0527a304.nq.gz
│   ├── 0a66065e6697696676f6be14e23ac87e13051138.nq.gz
│   ├── 0da891a2e600f58c19c791b14213ea9ef109f102.nq.gz
│   ├── 0e0d1d1949bf42dc8c0ac19d28b9a2abf3118ec2.nq.gz
│   ├── 0e8a0eb36f4ca2c939201c0d54b5d82a1ea34778.nq.gz
│   ├── 1e63f71f4dbef71cb869ba51c461816c7badb876.nq.gz
│   ├── 1f6cf7f97957253c7089ef88fe68aa79e27ca8f2.nq.gz
│   ├── 2028f899bab21c162be785848884f8b168166e36.nq.gz
│   ├── 22b080fc3f1b17ca09890471ecec7f12c9545736.nq.gz
│   ├── 24cdf02e8fd555a9e2bcf104d799dc9545711451.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 26996c2bb38bf47b4875c2597d9880061d919f2c.nq.gz
│   ├── 2a80e09c53d46836b1415d92c8128eda64eefae5.nq.gz
│   ├── 30fc63891425d108b1667373043331d478952579.nq.gz
│   ├── 324beaae10dbb8008df71cad8f6202f83c7163aa.nq.gz
│   ├── 341b170c687d8c49419e67e791b6429b1036b35d.nq.gz
│   ├── 3cf4c8377b76799dee7a09e349543d22e0b30968.nq.gz
│   ├── 4143689d5f35683cef912f9b7a6236f097061ae4.nq.gz
│   ├── 42d73b09c4fceda23f1575bdd4ea90537d3ac26c.nq.gz
│   ├── 43d9e5a9c1c256ec3bf9df2bcb923edf04285ad2.nq.gz
│   ├── 46da4143a6a1ddf51553a67735157f6330a7dd31.nq.gz
│   ├── 4d0ca9e970abb2d22ae59bb41e03233f3f8ac451.nq.gz
│   ├── 54a6585661672d129d7682ea5392f5161219cb46.nq.gz
│   ├── 59ff2f8c8bc7f66490570ce508269a524aac4e86.nq.gz
│   ├── 5b14f043782b183677fae7e5f040b2503e1ac9bf.nq.gz
│   ├── 5b3160d1245a0f7c3f4541fdbb6d78417308add4.nq.gz
│   ├── 5b4335699367fb55e44e551b7f2bfe103e20583f.nq.gz
│   ├── 5b4ada2761854482ad515cf060cbbd6ddafde5ce.nq.gz
│   ├── 5e53777d76a49cabe5fb2a6d47b3962c4343212b.nq.gz
│   ├── 60974b8c43dcade93b472e032031a691d40542e4.nq.gz
│   ├── 68bfef8abb362802497fa1d4c0b84cc85b538a4e.nq.gz
│   ├── 6da5060b2409b83766ab075170290ced010f7f91.nq.gz
│   ├── 7298a4408f1466cf12bb2b3bd1f5a3a97448cdba.nq.gz
│   ├── 786300189b7aa0fbfa540232221752e087730d94.nq.gz
│   ├── 791074ca08c710a58687684e06c8ecb7892e4446.nq.gz
│   ├── 7ba0f287a7a94327531d67b2f0940d71e573ff0a.nq.gz
│   ├── 7f6c35f6860725326ed96b80860fb8d7b783ef1e.nq.gz
│   ├── 80cb86fc6ef2150d25a76269faa04378128302b9.nq.gz
│   ├── 82b8387bbde788c01e9e2f1940a094a8c328d8cc.nq.gz
│   ├── 831013f431f1df17f04cbb2fffd381b945f0a34c.nq.gz
│   ├── 8482586d0611198b06d4c90e11444f491b3052c9.nq.gz
│   ├── 8546a7e459c5ef496d841c441b00ec3940eeae59.nq.gz
│   ├── 876d8a443157122a3bf29a4825cf75fae5d3a99b.nq.gz
│   ├── 8783714d77ee89e819c7127561bfb9b0ce809919.nq.gz
│   ├── 8a598861f4e0bf5ab4a3c64bac1d0ed2f4df6c89.nq.gz
│   ├── 8ab32b4a8e69d2a13909cca8954604198d3f1dc8.nq.gz
│   ├── 8c0e39e40b452ceeff20d52c9a5ad108c4d80f86.nq.gz
│   ├── 8f21f6345d462892fcd3fd8c514da84a3ccd0e0a.nq.gz
│   ├── 8f79589af8f4346491fdb22aefbd0048451a982b.nq.gz
│   ├── 9221a152f684ac2cf182dc243c5a508ad40a1837.nq.gz
│   ├── 94983ebdb882763c59b8ee605682dae057b45156.nq.gz
│   ├── 9cb8b3f58fe20d098735a57e838107af3b63277f.nq.gz
│   ├── 9de03fcd0d2c8ac84ade5e60820cf597ad335df6.nq.gz
│   ├── a3082cdf1b18b728c3c2d9268b975275ddd85a58.nq.gz
│   ├── a83f66648e5c199f89ccd6857a6f5b87334872cc.nq.gz
│   ├── ac5585cad2088d80fb09ee4f0c629d1a2b7d3026.nq.gz
│   ├── b0459947e46a9148f67a0d4debcc823a2a5a61f9.nq.gz
│   ├── b0e90ea25553c794e0e897e0e27bb4f80dc873b3.nq.gz
│   ├── b3b30cf30f0a97f86c25b9ddfc9de69edceb42c8.nq.gz
│   ├── b404371adbb891750efd283856bbac853aa64616.nq.gz
│   ├── b59ba247061f0df309533857cce8a0ff40cd3c83.nq.gz
│   ├── ba3c31c8925a5f10bb225daab92d8500620734c6.nq.gz
│   ├── bb31de5af16d1a97362eba846036d039dd092259.nq.gz
│   ├── bc5b656b681db444e3505abcb3bd199b42354846.nq.gz
│   ├── c1ee1c1dcd7eaba1501da6de87a5ab2eb5234193.nq.gz
│   ├── c5035b06f586d2b151f38cee5be460ad3fe9b9f3.nq.gz
│   ├── c7f2e645aee5c5f58e2655ab4f06dceb06e619ee.nq.gz
│   ├── c8486dcc9182e5396540e8363c74547ee7dad7e5.nq.gz
│   ├── cb5d55584cd088e3ab2fa17488c27bb604074be7.nq.gz
│   ├── d3e9cc1b27c3327edc0d4654795da5e65bc59c09.nq.gz
│   ├── d6e8ef4722e7c36dd500f97189bb3c4e769da010.nq.gz
│   ├── d7f7958d7430c0adb6b961432db4e5ee2dcf228b.nq.gz
│   ├── d93e390094fd637c3a7e59e867c00cc8f592fa13.nq.gz
│   ├── df36c7df8f4ffac1c5cdf79bc7baae698e1af35a.nq.gz
│   ├── e1c74898871464aa2bd3c82957d4a426335d3c94.nq.gz
│   ├── e333071c0663ee5621078ef42979852ec08fce20.nq.gz
│   ├── e5542d74f89184ed6797e34ea5f7edcf0de9f5f8.nq.gz
│   ├── e76968f82e25a91cd37260a8209a48b3996b9bdf.nq.gz
│   ├── e8a70cace378fcc7e2069e6f17837fc7002dc04f.nq.gz
│   ├── f1de5fdaa73ddad8da78f900a14363e59147322c.nq.gz
│   ├── f4753c34ed76b3c779b615df218e7b903c1c20af.nq.gz
│   ├── f48bceee728551ea95bd03e290d87e6da6c2bf1e.nq.gz
│   ├── ffc888994e60bdaed306eb15f71423d615316ef7.nq.gz
│   └── ffcc9086683012b3f24eddd63d22b7bb083ff831.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 84e22f664a3a6eb678842aabfa069a01ae42b0ea.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 93 files
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

[PrefectHQ/prefect-helm](https://github.com/PrefectHQ/prefect-helm)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
