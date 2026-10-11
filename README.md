# Repolex Knowledge Graph of tox-dev/jetbrains-fish

RDF knowledge graph data for [tox-dev/jetbrains-fish](https://github.com/tox-dev/jetbrains-fish), parsed by [repolex](https://repolex.ai).

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
rlex download tox-dev/jetbrains-fish
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6bc004c209aa7f1b6443e4fb901a20978822a86b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6bc004c209aa7f1b6443e4fb901a20978822a86b
│           └── chunk-001.nq.gz
└── blob
    ├── 009108fea165c470ad3ea43fad0f9721dab29ff0.nq.gz
    ├── 024bf77db4374610fd36685e3772240ae0e19baa.nq.gz
    ├── 02600ead3ef997e2ab7c07f97ba7a0ab4554f25c.nq.gz
    ├── 02a79a78bfcf395dc268b3013526283dcb72124e.nq.gz
    ├── 02e48d40fa05d8fbfb90566fe6c1d022f8ad3e75.nq.gz
    ├── 03754c4c3d9206f5c9ef69e41990dfe26a05251e.nq.gz
    ├── 05681d850e0ff2726fd4a4d82b9f55623f957079.nq.gz
    ├── 06469d5ad4a6ecd48f11ec36dd423e7d0544b1ff.nq.gz
    ├── 07e4c1a9397489d3e58477469a52c78b29419117.nq.gz
    ├── 0a4f75d5fedc53a29ddbdf80cf289b4a7b9e9472.nq.gz
    ├── 0a68042cf65fb27ca1af9ca9bd32b8e0a85f33ff.nq.gz
    ├── 0aee8b00f7ed6a68e41dc8d8de06e66b6a1fd6c2.nq.gz
    ├── 0c23d7e7d2e3bb5c1fea9b91e2005db19b2959f3.nq.gz
    ├── 0c78237f9c700fca0e703514ef8b36299ac41e10.nq.gz
    ├── 0cd4e6c4d24bfe36d0a6e565a8f6f4d53822e513.nq.gz
    ├── 0d813615821e561756e3c5247930423ac75dec0e.nq.gz
    ├── 0e603deb2edd738e2504f9bc5a68a19eed9083eb.nq.gz
    ├── 0fc50b54b20648e01a71f942e543a073bb6ee65b.nq.gz
    ├── 10b5075da748b02c97974060bd2bf310d544f556.nq.gz
    ├── 1203cd0310158340337d9df7ef7d0a5fdf4609a7.nq.gz
    ├── 128605daa30d8d4ac0f44bb3386ea4ce577f7f34.nq.gz
    ├── 129d6ab78eb4f4d2d7c9d0ec07052dfbb39d3695.nq.gz
    ├── 1301167fca29aac42752d0726cf517bd00e4cc58.nq.gz
    ├── 13b395f6ce8b2ccbd2325e727665806e11dc4d1e.nq.gz
    ├── 159f34220d9aa8bd84e7608c9b40fdec89f0e90e.nq.gz
    ├── 15d45ee6be8d99c702c2db9fa3740bc7b2b27499.nq.gz
    ├── 1b7e1af68a4e4bbe2891dcaab66f02e4646a93cc.nq.gz
    ├── 1cfcb1ce3cfeb4af4f165d9515c09165031d549b.nq.gz
    ├── 2062ba0e36f3325df7005a5c3a48df4e565aa9ab.nq.gz
    ├── 220f93d375a19bb70914391ab389759183167d01.nq.gz
    ├── 223c8fd8e8c99a7e96128fc5c753d41ad0fdcf3e.nq.gz
    ├── 239ae4dbadf7fd86f912dee5bf3928e38e6ec90b.nq.gz
    ├── 249efbb032ce46a80c687c0723eb172e85f6a136.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 286f18676be8976b151e26645841f848c7e6fe1b.nq.gz
    ├── 2883138649606cdd558c5a0318ea47d696230d83.nq.gz
    ├── 294ebeebbe870e1e7710b2a7e134e3bd521b4c40.nq.gz
    ├── 2a7e20a83b70bd7079dc9472db9ec69a3523478a.nq.gz
    ├── 2ab7dd5a46e4226d8b4b6fc10c5c3ee6ed152ae4.nq.gz
    ├── 2cc4fe4da4e02f883cfffcac3a28d3af970b0053.nq.gz
    ├── 2d033dce4ccdea2557539861e56e4502dd7ddc7f.nq.gz
    ├── 2df11645f540c5cd9f9552e59bfdef0166c74ad0.nq.gz
    ├── 303673b6a6c806234f7409bc643fa00e147ae912.nq.gz
    ├── 3117e85fdc1709bb8b7f6ad2c51513dfcd0236ae.nq.gz
    ├── 319f1e162beb7aad5a98f1e43c2d2070b6de0144.nq.gz
    ├── 32511aeb3af363ef59774b2ac31279434d6f2abf.nq.gz
    ├── 327f1f0b0864d55e536cd5aa3eb6a7474f74305b.nq.gz
    ├── 3285e976f9dbaf4384daf8a697d7a14482f1c8a2.nq.gz
    ├── 32929d20df85c1106f79a7b713b88b6a3bdc30ef.nq.gz
    ├── 32cb665344ed39b1fc17ad35e512b69f5f22ef52.nq.gz
    ├── 34cfbaa58aa4e6050bdb160d7c8dc9017016ba49.nq.gz
    ├── 35252c2e92decf98167feef4908d005513638b74.nq.gz
    ├── 36dd56528262352730a8a7de5f54fe4ac33045db.nq.gz
    ├── 3710498bd8a26f30a9392e47c461f025859f0c5f.nq.gz
    ├── 37e11a41aa26b1310a0c88f6edde7c006c22fb36.nq.gz
    ├── 3872c22751ba3e81110ead5433f245a7ec61903d.nq.gz
    ├── 38d59dc5a964b4ccd385300797b7efe59d45861b.nq.gz
    ├── 39155d562a5558a625dacd29035968ae353f36f3.nq.gz
    ├── 39e3b1a494dec2c6902f4241497ea1c345742c52.nq.gz
    ├── 3a0f9155aa98e1200a0d8a780b04e20c8d6cc846.nq.gz
    ├── 3ad0923f28ce17f6e585ebeced7b9492122bd69f.nq.gz
    ├── 3c9faca2463c6350ee3652337d781ce67afce749.nq.gz
    ├── 3e175557f3a01975aa6fb52faec02992833e9ad4.nq.gz
    ├── 3e4e44634e62f1b976c5b1eb40d7f863e9bb7689.nq.gz
    ├── 3e8a4833f9c902dc430705bcfd49a3f185532685.nq.gz
    ├── 3edf8b1ce2a9f8171ad8daa878b06688f25b0756.nq.gz
    ├── 3eee582afa9e7cd98bd5f420812ad15997237b3c.nq.gz
    ├── 40da0645c2da36740d47af7f259545c49892f9e3.nq.gz
    ├── 4164ab610f44748d1182d7d88243850871c8e87e.nq.gz
    ├── 419142559221be2432e07ede4ae540291fab9a9b.nq.gz
    ├── 42117f426b09008e075b64250fd52a6c41494249.nq.gz
    ├── 43f111c563b32c7f55c674ea56267a5a73db1b51.nq.gz
    ├── 441bf1ed2ab4170e6b60dbb6df516f299f26edc5.nq.gz
    ├── 44f180d53b62a1985d9a15a45c0357a1609219c0.nq.gz
    ├── 46c2e9901605be6f3fb8d4ed7544594872997fd3.nq.gz
    ├── 46cde7ee8ee001216e1fa5cfb988ab45737e377c.nq.gz
    ├── 4741a45f6ccef4c21f93684dd43f88aa81ae6d8c.nq.gz
    ├── 47fc98d812d9d0985c79c579119e0b9b48399e50.nq.gz
    ├── 4905a79d0631a0c43249d1d1c48e9e066b861710.nq.gz
    ├── 49d4707a4a7853625e8fb0fd81694726600f914f.nq.gz
    ├── 4bc6d3314953064666288f122653ba5f082bc7e5.nq.gz
    ├── 4ce38fa1898feb11c82ae4412d9d3a49a10e6567.nq.gz
    ├── 4ced2cdff023d77ea5f0c10e8f078fd696feae87.nq.gz
    ├── 4cee87cf76ae67d60e0b3e335704655320b73860.nq.gz
    ├── 4e529eb94baf94d9cfcd4a6e58f2ebefe8b694c0.nq.gz
    ├── 5097068a8d375f5bf0d15693fb5b3615c972a801.nq.gz
    ├── 523475065fe88b4a92c39769bcb4a172cc390adc.nq.gz
    ├── 53019fcdd69da2dfc610783b6cbf052536e29121.nq.gz
    ├── 53a62d463b7a6852de54317a92a8eb52c8311500.nq.gz
    ├── 53c5ae814bd3e78ac016783cc488748a7176cc05.nq.gz
    ├── 5401ddb7b426393ec5d521ab3a9af3069f8b3c42.nq.gz
    ├── 5426de00b2d5dca2cecd8517e5542fdf139c6a36.nq.gz
    ├── 54db6306efdb2a465e5890383bb52f856c056538.nq.gz
    ├── 583feda69d79d1dbc7f94ee32c69511d1872ac0d.nq.gz
    ├── 5c73cb2740d2be11ec0e25694032b048d8eff842.nq.gz
    ├── 5eb514c7c591e514c2898936ac95d281e66cc9a7.nq.gz
    ├── 5f3ceb4112d4edfc9ece498f4eb719ecbaf3bd7d.nq.gz
    ├── 5f89818f9e63c2f6829c7706c57f223cdb5bbd38.nq.gz
    ├── 5fa991e6c7d352a709d588387fb7e84237742169.nq.gz
    ├── 5fedeb22b61dfd7e0a9cfe2b7c785db84cd7f2af.nq.gz
    ├── 606a9313ba683b0f093f24ab33fbbc49a48cdc79.nq.gz
    ├── 61274092c913f69323935c2c6f6f91712bf7bd0e.nq.gz
    ├── 6152a955245afa4528e50aadcb5fbaf3ac23d937.nq.gz
    ├── 628dd12ec07e5ea224e0e655b2605c15f7015005.nq.gz
    ├── 636a7d650a949292d0133cf57c8996c6a83dad96.nq.gz
    ├── 658c722743658faa2a0ed485a54400d3fd50664b.nq.gz
    ├── 65aea0620f6520b18a224e243b3200a853046efd.nq.gz
    ├── 6a52f2da79500f3929261b74800db5d1b326e157.nq.gz
    ├── 6a7d2b2ecbdaa0a6cec2db5da499a51092501d2d.nq.gz
    ├── 6bd90bb50dfadbc63b7684a8d5268c67be0667da.nq.gz
    ├── 6cbb1bf409d846a5a9ff4449d7cafa8177daaa6e.nq.gz
    ├── 6cc5e342de52c0e714c03bc330c9285f097182e6.nq.gz
    ├── 6e06fc8e51f7bf2882cf0d0f4dc133de0d1c1366.nq.gz
    ├── 6fbcf62ff8f67a5fab5bb220fa2094b1df98556d.nq.gz
    ├── 735dc0e6132184a16788e9f38ee0aaff31f7f501.nq.gz
    ├── 745bbc648ad7044e4880d70e6c59ffae87ad40ef.nq.gz
    ├── 75ef14b001518c68234e677d76ce300f2170dd23.nq.gz
    ├── 76065a81c46728a0d847d33610f5bb63ff221614.nq.gz
    ├── 767b3353eadcd532de81d7382233459510d8c96e.nq.gz
    ├── 771658f19dc17ad80669a0bd8748f1dccf17c1ff.nq.gz
    ├── 773fc96c64d0205fb51d41f73aaae92b22cbe15a.nq.gz
    ├── 77d4006b9340442deab283c9f51fee87bf5d1499.nq.gz
    ├── 79f8044ca3bc863bfc6ef6be5b56a1ec8f88682d.nq.gz
    ├── 7a1f24af3664c1f97c445cb1bc6c2dbb2e4e991f.nq.gz
    ├── 7ba58bffd0c84f91daa53c2d055361bcef23074e.nq.gz
    ├── 7c408432601c08741375de6079ab3dfeec71bc80.nq.gz
    ├── 7cc65321fc65843b25209849fa3925b84cb4459c.nq.gz
    ├── 7db02e8c3d5d7e954ffc0a8c59529e5cc6d6574f.nq.gz
    ├── 7dc6d2524480a96bb6befd61436bcbf7ae7ab674.nq.gz
    ├── 804d0956f70af842cd40725c526661b9dba8095e.nq.gz
    ├── 812dd51b931c6764c175c769981703103e225f20.nq.gz
    ├── 836b554cd830fbe2758ae6e47135b4b89d4c9903.nq.gz
    ├── 84cce872df264268759b22985e3649afcddd1a91.nq.gz
    ├── 85184ed7b5413c5bb7bf4f9bb221d4d9e2816637.nq.gz
    ├── 852e541a13c493ed16a703c71f088a3e6808865d.nq.gz
    ├── 858b00072b99e53c5b43740c8589add47898cf99.nq.gz
    ├── 86d03f69409f53a25732e753d43c356d3e2b6a84.nq.gz
    ├── 876f72470e89956f76478914cb30af964d8f1982.nq.gz
    ├── 884c7a96a4a82cd95a9ce3d698512415f2ff90ff.nq.gz
    ├── 888fcc038f71fb73b5099f7549312678c36a6519.nq.gz
    ├── 8a0c6380fea8be7b4c730eb129fd61f8abf3aa36.nq.gz
    ├── 8ae9050b3e597e4de6f9e327105fc89b8340e90e.nq.gz
    ├── 8c07670e9fba3e5d768c6845b01a176648d495a0.nq.gz
    ├── 8e5915b78c609e4e6fb1e97e1f9e581261b6800d.nq.gz
    ├── 8f27e44d7780ad7b4c442d85056f45c136bcf8cb.nq.gz
    ├── 90ac63b2c4182401138605628694f7ee41f6f6d1.nq.gz
    ├── 9266440913b8a66091d7f40aaacdd5916ffa6977.nq.gz
    ├── 95c9c287c8d1b17738051fca655c3a732108553b.nq.gz
    ├── 96fdf91aa48e11c2558db9478d2a907ddd2c32b4.nq.gz
    ├── 991266d1b7a3dcecd4dc4236d3cf0f2f1ac99bdc.nq.gz
    ├── 9a0678386b75be88d6c7400ef8f9fc60eae724f9.nq.gz
    ├── 9a4bea54d6112901a3be8300fda953e9266a0df9.nq.gz
    ├── 9a76225c548b999e431cc02ee962ab708a1df9e8.nq.gz
    ├── 9b738ce9ade3fb20ff82126cda5946d280862db4.nq.gz
    ├── 9decc0d3dd8995ea177296a9083669d82bba9f8e.nq.gz
    ├── 9e016a6a71f220d257ba8bc5790e5b61df10a02d.nq.gz
    ├── 9e30ac93867e7022ead850618d0b5217cd0f58eb.nq.gz
    ├── a1d0a4a56daf15d9237974f1d81dd3e61f705e3e.nq.gz
    ├── a2babf59111c0ce71121ee7a3f2064589bcfc163.nq.gz
    ├── a43f9a64e766bd65efb67b0fecb4f04c5813dc9e.nq.gz
    ├── a7717155ea1bdef20f6282843b0eb25881294da6.nq.gz
    ├── a7caf15acdb4b21c82f0966a83b883c74cd8b740.nq.gz
    ├── a89e865200dda0fc8c36f0fd61bfaf21f76c2bb9.nq.gz
    ├── a8c722c39ab6f6c36c16bfaf082f72bb72c8e4d0.nq.gz
    ├── a96f173b8365798e3f3ab8e089f03e85280e8401.nq.gz
    ├── aaa17b1ba36564ce11080d979e96c88b2f93b94e.nq.gz
    ├── aafebb28642c49950201b35e7e36297cc96c216d.nq.gz
    ├── ab3ee9bbf43012ac9079c5b7f321afbb2cf6dfa1.nq.gz
    ├── ab72221f1148b43542c1376ca5183d8c7bf622b5.nq.gz
    ├── ac07ea20af078af0fa83428d3116573f7bfc2595.nq.gz
    ├── ad9e855a829948152696762ec2ba052840e4ead3.nq.gz
    ├── ae419c100b25005bd082785a7709b42a9e0300ba.nq.gz
    ├── b1bd71af3e297d383f9d0fcd3468a0908f867b13.nq.gz
    ├── b2c1e3b0e386ac406d8d80f2000872086a9eea8e.nq.gz
    ├── b2f1b1ae994404f3343a74dad59d836684843c1f.nq.gz
    ├── b303898ab7cd2ac824ce39b5fd1f90ab68d9a33c.nq.gz
    ├── b76849768badaf33506cbaa6c4ad0df39261d123.nq.gz
    ├── b9edd1a456bb0998cda4c0caf01b36582dd06f72.nq.gz
    ├── bb807a7dc8f62a5b74e840b1c668dd0175183b53.nq.gz
    ├── bb99219eb010cbcf6a2bbc8bc957789015dbfd71.nq.gz
    ├── bc8c52774a1b9aeaa38e7b00a54a244edaa01ad7.nq.gz
    ├── bd4c3ada6b1a5ee6ebcfbeadf946d04950dda9ad.nq.gz
    ├── c0b073aa51bbde0703d6ca3b0f5a9db7b3e90ab6.nq.gz
    ├── c2e6d771c712bb692ff0982b639f9aef2353d4df.nq.gz
    ├── c3ace4db6898f6c0221df50f03b11b450fdda73f.nq.gz
    ├── c3d727ddebb1b6b317a5a53039c21d2a989d9170.nq.gz
    ├── c3e42f7b9810d964d578ed6a8d1336a94a34b4b3.nq.gz
    ├── c827a3a548f089bf03f448ec7811d8dc3afa412c.nq.gz
    ├── c9bf971c5a45aa9ff45e05b82a3846750ab3d9d1.nq.gz
    ├── cfd24e32859cd5a6521635d96b63b7b21419f143.nq.gz
    ├── d02e7089ed5e448ef7ad38d9876abbd66965b586.nq.gz
    ├── d0972b12f123cdca5729f99f73289ff83d02da32.nq.gz
    ├── d2105f28c6b49f45bdae93a00b8560dcec56d557.nq.gz
    ├── d4fde732446a27a2c9d65e60facf045a2cf3874d.nq.gz
    ├── d5107dd96d44581952adc042fbd7c60d9e7159a1.nq.gz
    ├── d52750269d3193074147de624a88e98173335112.nq.gz
    ├── d5e5adce6b2041bf2fec7dbdbdcabe31bf728d15.nq.gz
    └── d74c46a7d1ffc50ebff96da6402411034d740787.nq.gz

7 directories, 200 files
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

[tox-dev/jetbrains-fish](https://github.com/tox-dev/jetbrains-fish)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
