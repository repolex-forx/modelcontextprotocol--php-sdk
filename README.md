# Repolex Knowledge Graph of modelcontextprotocol/php-sdk

RDF knowledge graph data for [modelcontextprotocol/php-sdk](https://github.com/modelcontextprotocol/php-sdk), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/php-sdk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b648df0216f66fc0b9e6246dabde224c54037c8c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b648df0216f66fc0b9e6246dabde224c54037c8c
│           └── chunk-001.nq.gz
└── blob
    ├── 007bdd507e6ecffa2b7fd50afa15f9be4ff51f6a.nq.gz
    ├── 0083a83eb5946c000435d74d8094f652b653d6aa.nq.gz
    ├── 00f47b93e7fd3947ff725bc1552804691c447988.nq.gz
    ├── 036785a212cdbf39a3d745fa7aa6f40df779f539.nq.gz
    ├── 0387d44aaecb0d8935f74553a9a9e2b8a1155a84.nq.gz
    ├── 0498853510357822e6303cb2881ec0569ad97781.nq.gz
    ├── 04c7ae82e9f02c5f8bc799d817f693eb8ae8e325.nq.gz
    ├── 0520a715ad40881b9da0dc2d8f57da4a8f784bf3.nq.gz
    ├── 054eb61181001fec1de67e6a1a9f7c752a41f4fd.nq.gz
    ├── 058755f7221078f87f049bcc35f5af71bf3821af.nq.gz
    ├── 0761de371d45979ede78c6b876770911cb070e10.nq.gz
    ├── 07e975204d9a048a08b99e9edc1bd2096e76ddbc.nq.gz
    ├── 0812699a1e97e046e8c05eb65ed5c5ee4a479060.nq.gz
    ├── 088a5e8051859b978bfb587a79d3de4430005cb0.nq.gz
    ├── 08b8198d1d3707bb2eb2a38c56d68acc1b77d004.nq.gz
    ├── 094b714abd4ae08fb678143ea87ebd6e00deb932.nq.gz
    ├── 098b6e6ae9e814ef6837b900c1a26c11e2ef1ee4.nq.gz
    ├── 0a56987d958576f217903100974cb93017ca5544.nq.gz
    ├── 0a864e753c608393b7cf77f2bb7028879bfcec2b.nq.gz
    ├── 0b19fd3b18459aeab684043dceb7f86835324a74.nq.gz
    ├── 0b1d97a5c23af65497c63cd92dcf123bf03acbd7.nq.gz
    ├── 0b5b298b077aabf8eaf953412390fa6086949270.nq.gz
    ├── 0b80ce0f76389119825609dc814b67f2bd4e1213.nq.gz
    ├── 0c13f654d7c2fb6b5204f28fc4909a4d5d09436a.nq.gz
    ├── 0c445b28c5caa29a0f3d377db7ef89c77e518f7f.nq.gz
    ├── 0ca18360ff419a89928bd981494a5e0878859879.nq.gz
    ├── 0e0bbe93d318270fd1606a1e71525bdf846cabc3.nq.gz
    ├── 0e1472d304661d78d917a5f76407545da061ac1f.nq.gz
    ├── 0e2b90e0cfa1eb0d940a8670c84d876b55b5ab0d.nq.gz
    ├── 0e4e05b07e4d35ce1a8218876fe63197a460ac60.nq.gz
    ├── 0ef784e1040533713468caaceedb7c47e9df1701.nq.gz
    ├── 0f5e2234364763ebdd0d09e01c6fc38bc412dcf0.nq.gz
    ├── 0f961224802e2f52c78f2bec80b380183e98393b.nq.gz
    ├── 0fada878230d8e40b7e19a4454fc2297590394cb.nq.gz
    ├── 10152244a0614b7d9a4a9560238a6b4e3bf2a82f.nq.gz
    ├── 1028c97f185aba87009afa426e05049e56337861.nq.gz
    ├── 10d783776c69cf1769c55402d1d93870ecc32041.nq.gz
    ├── 10ec755ec75b6766a64aec5184f19ae050d101c3.nq.gz
    ├── 137270f57096a1b0e6fe8e0676608558754c81e8.nq.gz
    ├── 1399cd26375ae2b0510b57f196fbdf9cbcfff8fd.nq.gz
    ├── 13ba3f84d5c1754151004edb8486f23c3d4d57da.nq.gz
    ├── 13f5f16177b3b63a938402784f0e47e0da3ea792.nq.gz
    ├── 143b4320c04e2ba372b8d3e6bddb022b64e3937d.nq.gz
    ├── 14885ef487674c5d6dcafd187a29bc6db5ef4a46.nq.gz
    ├── 1499205f25fb6600569fcdedf1e884ef81e98d35.nq.gz
    ├── 15016156c0ab9331cdc0909c3c3d528276385a64.nq.gz
    ├── 1502e1e0e4d89851f7ddf2188ce9ada4e50636e8.nq.gz
    ├── 1557e1e3dbcab0cca86559e3739ab10b4684f5d1.nq.gz
    ├── 17abcebc1d8d81c21a3e90b39c02cc08a325000d.nq.gz
    ├── 180dfba7e2208f55d6739ded1555d466bde790f1.nq.gz
    ├── 18c414ec129321f47dfb11e8b1d20177612533a5.nq.gz
    ├── 193d8b8e66bf8f10571271c254240b45836d6173.nq.gz
    ├── 1a10e50fe8bba8e4334f7ee869bf92c5a6010f61.nq.gz
    ├── 1a25306f4ba3b4291e57666a7bba5e8dc08e71fd.nq.gz
    ├── 1a9498b3e9c519d9b8d772f51584efdc7cd3a2e7.nq.gz
    ├── 1ae0005d0b0d94d058c4f59a8fa1e3896719f604.nq.gz
    ├── 1b844096f47cbb4a9e26faa0dee4d1b053f5636e.nq.gz
    ├── 1b991d1da295c860d100e13cb312ff1d1500c6dd.nq.gz
    ├── 1c5ee7c1fdeb98289af29849706b076cd6d6ac74.nq.gz
    ├── 1c71e2cd37b5c0cc0817391198cf5313d36f7b71.nq.gz
    ├── 1cb2baf83427db15f79e34b7284983546e395398.nq.gz
    ├── 1d0d2a19abec4cfcb0d30b34162800724de054ae.nq.gz
    ├── 1d2a11058717c033db5a277e702239b48a740537.nq.gz
    ├── 1d368f52316ff83b5a7027634a73f5e3b72da9c0.nq.gz
    ├── 1dfd9368c9e6540d07f962d43eb7789f0ce7ffc4.nq.gz
    ├── 1e8147b022d92c60918cc39bdbbbcededb2324e4.nq.gz
    ├── 1e901efc17d97cd42bf20a11bf6afecc5a4063be.nq.gz
    ├── 1f4287f63853b8ddff6a78689583599e846383ec.nq.gz
    ├── 1f4f649ed54ff78b605a3f4eac2901045911ddb3.nq.gz
    ├── 1f73524e891071f74d3df2a0c9a746e9fd601dd7.nq.gz
    ├── 1fbb8a31423ac94a3d8c6c5c39478c2ff086ea07.nq.gz
    ├── 207c7e26aaa546c1a972144a5762845d518ef58f.nq.gz
    ├── 208f22a7166441aeeb5f792b5e3ee4b9fdcdea96.nq.gz
    ├── 20c0aae68d7fcc213b8b39e5d24b48110b7c9897.nq.gz
    ├── 20c455437021cf19b781ffccdf8be1d1b2297f44.nq.gz
    ├── 211521cfd8b44b94d751423ea98ac391c15ce019.nq.gz
    ├── 216157554a14c57a47d06b6c67604a238d09ee67.nq.gz
    ├── 2470b606b379d77ec80d978f2af5c34ab08f76be.nq.gz
    ├── 24798cd4413f3cfbb2e501269d4f904a0f55d257.nq.gz
    ├── 247b27fcd9c8ee4a801949d8d64c73c04677b8f6.nq.gz
    ├── 24852bc676223c32e7626d4d56ec78d32b18c59e.nq.gz
    ├── 24d065deae49afbb02bea92b69b3221c08d6412f.nq.gz
    ├── 251826c7593b4e3d5bd56dd5c5afe0a5edf74bdc.nq.gz
    ├── 25448188e617b6326e59e5c892a00bf1e9ed3f1b.nq.gz
    ├── 25df23b03857e1fa976b0f6b1d24f23a9a534c01.nq.gz
    ├── 26416983d2f7de4c7ba5952b78adad38de940c41.nq.gz
    ├── 26888e22a7ac6a8ade4dbb1e330e5b90737cc303.nq.gz
    ├── 27e146a80e1038371c08853ec6ca0625b274de64.nq.gz
    ├── 27e147be4495101cd4eeb17f0a4bd95c41efd068.nq.gz
    ├── 27edc84736c2cedff3d61f4ef8790a40d46075dd.nq.gz
    ├── 28432b35d72df7a54ef2f10800ae86e3282a6e8b.nq.gz
    ├── 28b25b09b9d8f7e131f5027dd1f21baa67d445c4.nq.gz
    ├── 294d9680b532f0e609a4df8de4407e01f8e29425.nq.gz
    ├── 29754663f997f8e90bee435c9cb8aee024ce02c4.nq.gz
    ├── 29ae8ac3a743164907ba12d999dbec8ff2f1a02b.nq.gz
    ├── 29bd882ceabadefd9047aa006729dd5a8b7d3fea.nq.gz
    ├── 29d23ffebea57e5991174fa78dc9b6c950c319b2.nq.gz
    ├── 29e79b5b6ea90fd492e6b3c9dccb7e1bc76f521a.nq.gz
    ├── 2a08f7ee94b4223333b8c2e426597047e9283271.nq.gz
    ├── 2a25b87b9defe1d6db90e439cb6164dcd73f4336.nq.gz
    ├── 2a33ecd1db31f6544ed484bab37adf779bba97b2.nq.gz
    ├── 2a5b3683fc3f94c7a0f5549b9614020b381562bb.nq.gz
    ├── 2a64e5d40040ad027acd9fc9e48953a749672ff6.nq.gz
    ├── 2a79a3ce86bae3647f5b1f08a868d5c16dad41b9.nq.gz
    ├── 2ae7046d019fe8a7c5d1b781a0ac939c5545a1ee.nq.gz
    ├── 2b3c941bba4d896a88df5acb77d65c06e3e7ec43.nq.gz
    ├── 2b642ea4a3de0e97b82d8bacbcc63a35b5cece0d.nq.gz
    ├── 2b70fd6e96d74ed5c2cb9e52ed7079428a928cf3.nq.gz
    ├── 2b7c6abb8e91d68850831c0f4b529bd674252638.nq.gz
    ├── 2b87837360bef8e0ff6c880a2d8fc869958c5751.nq.gz
    ├── 2bddb1bcd1629079b28efaeaaaea38da14f9771e.nq.gz
    ├── 2c67af626d515664516cf4c793f7838aad59133e.nq.gz
    ├── 2c71cf88d19040b055f4e919a3b63b67541e5c3c.nq.gz
    ├── 2d3c3706195765dbe3339e40c12f4dab23be07c7.nq.gz
    ├── 2df69f35aca6a8e20fbfce67007b8e26edfd5a0e.nq.gz
    ├── 2e9162aea62e55712ef3277edb92c5086b201914.nq.gz
    ├── 2eebe067aed11317ec4eba85a7e413db649881fa.nq.gz
    ├── 2f0bd7f0793ebc84e803993a095f53fc8a791feb.nq.gz
    ├── 2f3cdd70d95affe332c8e36c508d923913ea3769.nq.gz
    ├── 2f6ccca7aad8792307ac1e2a80219ece88feb593.nq.gz
    ├── 2f9b63a19b87e18e9974f43efd1273fca3dca47a.nq.gz
    ├── 2fb1c5ef751d062b13240bf0a0931f42d7aba789.nq.gz
    ├── 2ff24ba4e4c4d04a19392ef1720ab613bc1a7fe9.nq.gz
    ├── 31fe64bb3e64556559f607c9b7df74e29cffe0fe.nq.gz
    ├── 32817f644b88ade8fb8c3fd2e9f08646a0096202.nq.gz
    ├── 32ad37250f8b483531a4e1b6c2930917c46662a6.nq.gz
    ├── 32b0b70b6b96dccad65b5cc421ab6d4536eca612.nq.gz
    ├── 334e0bcdf5a098d4b17db9b263e3c2c0a20d8cd8.nq.gz
    ├── 33806076306ccc2abba924ef8cf3a5ea243d56d3.nq.gz
    ├── 33c8db32038eaf770fdc68345f97bddd2be3818f.nq.gz
    ├── 33e36680c776ac210e7bdc6c251395049a8ecab7.nq.gz
    ├── 33fb77caa51e7aed2ed8cf7092ad35660b32bcf3.nq.gz
    ├── 3425500f7fc35a7c8143dc26048dbc0c4c11456a.nq.gz
    ├── 363a2aea95b98d5793ffabecde19def8c6977fc1.nq.gz
    ├── 371ae4cd71b461a034ba00dc50a6904584f3d021.nq.gz
    ├── 373af4a385f32b8d3fdd17f2bda007711420b481.nq.gz
    ├── 373e6189f71e912da23699fe7f8b157c4cf7891d.nq.gz
    ├── 37ebcab7f7dc7efceecfa69e4d2f4580c75b55de.nq.gz
    ├── 38fe3dc0ad5b99ab2def7a317741a66db4bfe6e7.nq.gz
    ├── 39931e8cb295661a6b9fc42f3c6a17eb68179b4e.nq.gz
    ├── 39e036d334f3a8cc9b49c1f36d236bd99bc541fd.nq.gz
    ├── 39ebe113e3d20002d02979a60308bca7c41bb445.nq.gz
    ├── 3a7de08ee5c41b955ba0bd6d398965ab1b37acb6.nq.gz
    ├── 3a7f862e2e7f389766166e0ea1cf48fae33689de.nq.gz
    ├── 3b140f83580e32b70170ec228fb1c5149d0b75f4.nq.gz
    ├── 3bbccb88256b6daae1f120eeded09f19d197c430.nq.gz
    ├── 3c489bf0d61df8cab404ba9015a41f64d9d8a686.nq.gz
    ├── 3e385fefe4fdb599b5c8aefad7b6092cd224aa9d.nq.gz
    ├── 3eb8987bf7f0efb69a04e0c36133b2bc1a523020.nq.gz
    ├── 3ec0883ad04880c17f89fcff018e7588f8bfa8a8.nq.gz
    ├── 3ecdb00269f797a0910df4a9c50779d77fb11cd4.nq.gz
    ├── 3f1cff0e57b8f9ee41944b838ee5f3608d5dee51.nq.gz
    ├── 3f7ada583382b147011157d3f23f4b1726295ea2.nq.gz
    ├── 3faa772c55bad44b86d8543e84299911daeafb55.nq.gz
    ├── 41cfb2a82274271b420ed785b59b2c4b5ffc5fb7.nq.gz
    ├── 4205933d11a97befbe4050adc94961817bf629c0.nq.gz
    ├── 42095d0c065d172c34e1474a7e0254f8ecaf2d83.nq.gz
    ├── 422efaf151a0f6f673edc034d923a23be1f7bfba.nq.gz
    ├── 423a4122cafe35f52d964f338e963d552ed3127c.nq.gz
    ├── 428e1c702a643d3ccaadc959b89ed192bce81f27.nq.gz
    ├── 435c0a9270a9ac9005b686a3b6f40dbb63777855.nq.gz
    ├── 43c9fed4c825dceada5a8217e22a8949b9f64285.nq.gz
    ├── 461d9d964fcc94ac24985df37a02eeef1d61b62c.nq.gz
    ├── 46491269d0d7950f0b215e3c883997417f045c96.nq.gz
    ├── 464f3472ad0080174940fa189843baff11bf4084.nq.gz
    ├── 475ed419864af276b846176290135efe2bbd92f9.nq.gz
    ├── 47ea4a6a42d1185ca2991b1ec4cbac7ce356df13.nq.gz
    ├── 4a167ffbe03d49892688b9e48b017bc162e1a991.nq.gz
    ├── 4a93985763241755401a10678395303de4e720ba.nq.gz
    ├── 4aca9955a7f6db54116f9912b1a7f88c91c2b0d2.nq.gz
    ├── 4ae32576537e57842d59fb82e1fefdb9f7c98380.nq.gz
    ├── 4aff725667dfe395baf3fae4ded9a7629c0bbf4a.nq.gz
    ├── 4b53e6108bbe9b5b08cab407099b692da25f7680.nq.gz
    ├── 4b62f1b3397210d8299679d042e9ca67364180ac.nq.gz
    ├── 4d6a8917ec22b49be81567566808b44ad4381819.nq.gz
    ├── 4deef55e4d04dd7390f5ecb80b84606f9054dd0b.nq.gz
    ├── 4e21aab6b417fbf5b5862a13b026b526030b3c8d.nq.gz
    ├── 4e4527f5ea6fc8568e1b35623badd84b782d8986.nq.gz
    ├── 4edca4640269f7dd82ec04de107efcde43e98e7f.nq.gz
    ├── 4ee27f86f6d495f1b2041edc8a0682ffd2f2b863.nq.gz
    ├── 4f2ee3e97f8b416db878eb1f1a310ee8bfa750dd.nq.gz
    ├── 4f512dd8a05a9db138c6870d8d438cc352656bfb.nq.gz
    ├── 4f7f153722271b0e3167fb0cffeb015a4e502e29.nq.gz
    ├── 501fe1af1de97b4172c2514a0db6adbfb4ceda77.nq.gz
    ├── 50292420096eb98f07f3945dc30325fe8b17a2af.nq.gz
    ├── 50d10f9eb8f0165f364083679d94739137e204e1.nq.gz
    ├── 51348730bc42f3d57a638d5f2a88d467d3616fad.nq.gz
    ├── 5178652385085180944e6ac1b70a360b4961c718.nq.gz
    ├── 517be814f096f8ab58124ba909acb6d34486f97b.nq.gz
    ├── 522c5128926e18184529e12513bd18757e90d85f.nq.gz
    ├── 524f458abf413541e05c3d54f7d566798ab10610.nq.gz
    ├── 525d2ec711471de21ffcb905869fbd5cbd1df92e.nq.gz
    ├── 52815b3ecf2b133f0ac8f2473a7eb15f39afaf7d.nq.gz
    ├── 53596bc9009d9b8cf08b537ac535d7646cbc567d.nq.gz
    ├── 540c7ea918943c1d55ca483ca3ec426f6f36c9a5.nq.gz
    ├── 5421e3d754787de4bf912fb65029014e045e25d2.nq.gz
    ├── 54b1cde2a104dfa74cb40a71630c4d6de7a1c189.nq.gz
    └── 5586d05558068646f7b2ec4982ee73109dbc900a.nq.gz

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

[modelcontextprotocol/php-sdk](https://github.com/modelcontextprotocol/php-sdk)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
