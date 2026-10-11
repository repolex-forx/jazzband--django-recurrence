# Repolex Knowledge Graph of jazzband/django-recurrence

RDF knowledge graph data for [jazzband/django-recurrence](https://github.com/jazzband/django-recurrence), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-recurrence
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 14bb9b303a7435feb3ee1ef448409f94ebf64849
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 14bb9b303a7435feb3ee1ef448409f94ebf64849
│           └── chunk-001.nq.gz
├── blob
│   ├── 05c614dc9fe9027a28ba22e72ef017583d1d4bc5.nq.gz
│   ├── 070decbd391ffacd651dea7f141b6dc4e8e4ed08.nq.gz
│   ├── 0a483366e10edab0d3637969e8967e226d5e8091.nq.gz
│   ├── 0f2630f0ebaf3e9610fa62a5dc5d568371aa4f45.nq.gz
│   ├── 1623fb0a750940a04715f4d8cc73f8f4e3273d86.nq.gz
│   ├── 1b2979724b2f2dfbd9adb0e32437b8c4b17900f0.nq.gz
│   ├── 20a8785f641d54f25e9d46d6441b95a91167fd3e.nq.gz
│   ├── 2136326934a0f2c1b21a5fdf577e05d584894626.nq.gz
│   ├── 221a86f7023e2a99a09b0140073182855231e46e.nq.gz
│   ├── 22d3704ab6ab1f55a474cce50f66faf70f73298f.nq.gz
│   ├── 22f222483f29356ab942274c430a677c2dd71d8d.nq.gz
│   ├── 23fe9e2a57c4225acae8988a539c7cba1393092c.nq.gz
│   ├── 29b49393cdfb4447debcf07eed514a277cf4b83c.nq.gz
│   ├── 2ba83e6382beee9488bc676fca620e7a04045378.nq.gz
│   ├── 2bb25037576036abf087899a8af0b364c9434bae.nq.gz
│   ├── 2ccc3e593d5207108f44a1ed312d6cb0993a39f3.nq.gz
│   ├── 301332ab87cde7d9ba7e693d09906235ea9adae9.nq.gz
│   ├── 310d483fc1efe94f1224ff5c257e48f81c1e842e.nq.gz
│   ├── 38c5e0733cfddf172da590f79cb9dbfcc654c2d4.nq.gz
│   ├── 3a4006316eca8e9e7effa09c64c6244970a3a5bd.nq.gz
│   ├── 3cb69cdbe04e29a9bc7be5f2e72b9eb0efbd34c9.nq.gz
│   ├── 3e00a6dbc60b98733e1edb1a647f6192ac8ddcc1.nq.gz
│   ├── 40a15cd2b939edf37a18c8c9239a4226c7f419ea.nq.gz
│   ├── 43be9f50e7005db0db706ccb1dbc8d8511a0982b.nq.gz
│   ├── 46ece92e6c25f05e364ca72f9f197a888e28a4dd.nq.gz
│   ├── 4868a79531b5f0b7a09caef8b6a33e3a79206f82.nq.gz
│   ├── 4909218b91a8aa0f3f0d53a07bb15e871986f0f3.nq.gz
│   ├── 4b6c55e90f9dea3375f756e00cb6de8b546682be.nq.gz
│   ├── 4e6a92c443efecb47ac790fb7170e4a27d8069fd.nq.gz
│   ├── 4f9a98014fa752cba770f0f0a837a571f37f2c15.nq.gz
│   ├── 52af6924a6fd72cc3d264b4a64fa6eaadb9c8d02.nq.gz
│   ├── 535f1f150bdeec86c5cd6d946509004a159f433d.nq.gz
│   ├── 5f9c05184b6c5bd34fda5543310ee5283e5ec801.nq.gz
│   ├── 6116776c3ff04cc5cf2d3d0436fcea322265b5e1.nq.gz
│   ├── 67898902147b77ac38e72392f0599be4b8e519a4.nq.gz
│   ├── 69dfc462d9d91d5744b7bafb9b0ca92b84365736.nq.gz
│   ├── 6a737353300b5a745cba544d264a687ac2363845.nq.gz
│   ├── 6aab17ca693398a8de0fc18be087256f0132151c.nq.gz
│   ├── 751fc4ac470d9259e189a317b9e02a6fb26e51c9.nq.gz
│   ├── 754dca67aca95272e05c10228eb72257a4d73dac.nq.gz
│   ├── 7679a2afd802652255cd0a433d8703814838b386.nq.gz
│   ├── 7742ebcda57087cedac1ed3474fdbeb41bdfb153.nq.gz
│   ├── 7983dfce60dc2274b55d8d852ce0582a7cc4b008.nq.gz
│   ├── 7bc99b291672b9d9a83feae13ba10d9d0d0c67ec.nq.gz
│   ├── 7db991bfe09c963dc0ed5a0881707198a06d8a89.nq.gz
│   ├── 7e468e08f736d417d0275cd4d8d7a2d1dc82ae0c.nq.gz
│   ├── 7f3c2630517f734c93fec4977d20c34a218bde70.nq.gz
│   ├── 7fdefc1b65d75ccfd04106b2a9a895c984a6f07b.nq.gz
│   ├── 824d9cf0e6225c9b457d0aa5eeff99f6468746f2.nq.gz
│   ├── 8338f734584fd2d54c9b9c26f8aeba10e447663d.nq.gz
│   ├── 869644dee1908773de9dd83c9a83527eac98d66f.nq.gz
│   ├── 87ed42b9f385a97f6c4d8d5cdf87cc47495224e8.nq.gz
│   ├── 87fb14321e0ab32cf481febbf5666a1ac9823227.nq.gz
│   ├── 88cd21fa185433f8b74fb060b275160bf8f33a8e.nq.gz
│   ├── 8bd64d2172b97b4a5d6d83ca5297ac3e0cb30a45.nq.gz
│   ├── 8d61b36d07726ba51e4863a20c4db870cbe108e4.nq.gz
│   ├── 8d674aac3d24a4aaf747e219f5baf503ba7a433f.nq.gz
│   ├── 8db9e491cd346eb5827cbf33c1c0ba895dc1e1f8.nq.gz
│   ├── 8deb3c736c7b205df0f37f0b7db6c34eef8e9000.nq.gz
│   ├── 8e3d73ba97dd7f0d1713afc744a3ee33b735da63.nq.gz
│   ├── 8e738163e8ebaaa6bd0e94ce52757e87f457e373.nq.gz
│   ├── 8f9ab6acfbd0fdc65ae665dd050a7cb9cc742d81.nq.gz
│   ├── 9484d0b20d4a14e3366cd17ff09f6288584ed69b.nq.gz
│   ├── 975abfb6c282fba6da8290ab0619d3362003194d.nq.gz
│   ├── 991bacadf7ebc428f168cc1b66fb28d6299c65c4.nq.gz
│   ├── a05ebeb1aec2d42edf681ea7f87f5e04a28b23bd.nq.gz
│   ├── a4b1c6c465afd8b012f9360b92f32ac4fa1e5e35.nq.gz
│   ├── aa0691ba2717ec9d58c7631058102da7d76852e3.nq.gz
│   ├── af814f79f39530983400809a52978f8ba93ce655.nq.gz
│   ├── b2b8fa92146e55c0935bc0ea61b05fa2f1bbbd74.nq.gz
│   ├── b30e26cec8f7969e01379eef529fde641f6a555f.nq.gz
│   ├── b3eb071c98fa23caedcf4fae4a6bb3f37dc926ff.nq.gz
│   ├── b4c59ded760665d56fcae746b90f46159e4dbf3c.nq.gz
│   ├── b5dfd04e321d50969e5aba74c717fba2de0118d0.nq.gz
│   ├── b78276c025700fc59192aead9d1a1722e0701ae3.nq.gz
│   ├── b7f1036186fa8aa8a9ed6bb9c0aa6daf6d088f71.nq.gz
│   ├── bbf8f16ebc5d77ef5a428df4da72c27743d5be6b.nq.gz
│   ├── bd83f0745c1ea408f754c77c02ba82c9a673ea4d.nq.gz
│   ├── be6bd7713bd3cc3a5f806cbbb21abb61f71d104b.nq.gz
│   ├── c374d10fab69eccb967b43df789f642a95135289.nq.gz
│   ├── c83f93cb72ef4ff2bb54e2826ae16a6e33491907.nq.gz
│   ├── ca293bb496ee4837b1c9ba10857bcf69386ac79d.nq.gz
│   ├── ccdf850de8c08201441836e3c25f5a09ee61b3e7.nq.gz
│   ├── ce1237f7327e3a6749740ac50d37374b1fb50428.nq.gz
│   ├── cf4518d7ba5d064e090b56dffc3f43a64db067d2.nq.gz
│   ├── d027dafd9678bbd404989987175280c547e5539e.nq.gz
│   ├── d139a0b03dcf921a81277a12354b7a146314b40a.nq.gz
│   ├── d2ce00e1da90138df46660a2b1189344d6b45d71.nq.gz
│   ├── d64dd0c6fbb0a6dcffd20b977ca14a9a447986c2.nq.gz
│   ├── d86aa7a1c7f2fe9466797d119f339a47c80361c0.nq.gz
│   ├── db49115f13efbe1e6fbe4b5df1384e610360c993.nq.gz
│   ├── db8505c1ca8e332331295f38fadfdf01a29891d1.nq.gz
│   ├── dc54c1fe66043cbe5462ffbab6a083e01e2b8554.nq.gz
│   ├── dceef07a50f121f439763ef31a95f83e02955c64.nq.gz
│   ├── dd41ad136be9f3784114811f0f963943a1708bb7.nq.gz
│   ├── dfa5a8a627ca79f383123462790a465edca287f7.nq.gz
│   ├── e01cf586a491859476653f9fc57afe28459a3e14.nq.gz
│   ├── e0d9d8663c544ac6c2077c6616e0c9a5eb8e67d4.nq.gz
│   ├── e1757bbd89561014b10cd362cff81c60910a15b1.nq.gz
│   ├── e3715fbb12ffb7058779f7337011e025902ec000.nq.gz
│   ├── e5eef063d19fe0bb5f4311f69a6b015d05dd44bc.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee8c2e74fae7fa2b4668a1ddfdfa69c88f71b203.nq.gz
│   ├── f55b86558cca4a43203933040f87aed2ab50501a.nq.gz
│   ├── f76811ab2dda4df13847b25309e352053cb4b576.nq.gz
│   ├── f9f153da2c740bba6198aaa375f742ba65f46837.nq.gz
│   ├── fc3af324a4ec2b5fc548aa6d22de7eb54bfda44a.nq.gz
│   ├── fc824f0cba5cc29b81107c169328b0972b301e6f.nq.gz
│   └── fd4c6c825a32f77655a6fa9b027eee741db30ca5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 14bb9b303a7435feb3ee1ef448409f94ebf64849.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 117 files
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

[jazzband/django-recurrence](https://github.com/jazzband/django-recurrence)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
