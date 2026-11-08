# Repolex Knowledge Graph of run-llama/llama-parse-py

RDF knowledge graph data for [run-llama/llama-parse-py](https://github.com/run-llama/llama-parse-py), parsed by [repolex](https://repolex.ai).

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
rlex download run-llama/llama-parse-py
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b0f2e7b5c50709d8e44873a9d132e7bd7be2f7a7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b0f2e7b5c50709d8e44873a9d132e7bd7be2f7a7
│           └── chunk-001.nq.gz
└── blob
    ├── 009a68bc938540e7643158e3d67ceeed96f38cbd.nq.gz
    ├── 00cd17b8c66e748174dc456dc8ffc90a4542b2f6.nq.gz
    ├── 00d095fa43f29c3111c579edb7602022afc39054.nq.gz
    ├── 0142046c3e015ecb62e00b22833bea89d88ad9dd.nq.gz
    ├── 017368133d0ef826f03736afe2bf452caca34b0e.nq.gz
    ├── 01860499a263c57e1353dfa35c1bde26cfa3801a.nq.gz
    ├── 024984b39e74b43e790822d9607339ee1a7c5421.nq.gz
    ├── 02731f777f6b86e5d6e9f80559750792d1b34918.nq.gz
    ├── 03168980cdd63af09b59945f8ad5a79be01b3adb.nq.gz
    ├── 0416af0ab213dbace78e4cd83dac45b687fd8660.nq.gz
    ├── 04b511940a29675c09fcdf3ff6c483e2d8b1c228.nq.gz
    ├── 05d1e892c661b0551e346d6dab86ebb48237e997.nq.gz
    ├── 05e13a8b8a9bc60968bd2b2217f62128dd2cc89b.nq.gz
    ├── 06384b754fc1823dc6c0fc2ccfc2ec9b5072f588.nq.gz
    ├── 0672f5963219b217fdaf19fa46325a4151525cc6.nq.gz
    ├── 07cdcbd153209919300780dbd4a69602b11e7583.nq.gz
    ├── 07e5033adf75c53ca5511c54b7bdf2aa671c3208.nq.gz
    ├── 07e9984f0a70a1ed7fcb1abc8def042f22765449.nq.gz
    ├── 0991df092a94afef89c6d03f262944697db24aed.nq.gz
    ├── 09ae40da3874e44cccd66c9ba0a92b6c150c7bc4.nq.gz
    ├── 0a62c5382c1e00780ddff7b4c7757693d4151657.nq.gz
    ├── 0b28797d2b05cc1a7c60d3d743c01b9779cef812.nq.gz
    ├── 0c2f6843e448cfc4085c973de329134645e2496e.nq.gz
    ├── 0c4ddfcb9ac1f1922917cf5ef2eae5ae85e013a7.nq.gz
    ├── 0c9f4cc420a061bad372fd393913813e909aee79.nq.gz
    ├── 0cbcb346097035eb300583d914a128487a85b570.nq.gz
    ├── 0cd58e6dc431531767dc3f4e3092d6c55f8dcaf0.nq.gz
    ├── 0cf2bd2fd9d04040ba557f3f6658e6c4134d26d4.nq.gz
    ├── 0d152e92e8d40bddc9283536551aaf55d5de884c.nq.gz
    ├── 0f0c181950897c1101b2108561e5e59f3eec9ad7.nq.gz
    ├── 0f239a33c6df82d00988a48777a64ab13449b72f.nq.gz
    ├── 10540b0544f65313284864f656a11df4fa0fb727.nq.gz
    ├── 10fd8698a7c4bc2ab14092f89485a380dcdf4ca2.nq.gz
    ├── 11236b510873425b8950188ec016d91688fa60d0.nq.gz
    ├── 11c0376a69556247d04bed540aaf81e0cee33d75.nq.gz
    ├── 134bc610d46c8e84ac78e7ab64b311528606e22e.nq.gz
    ├── 138c5b10c3a941120c33b549b34ebed583e873f8.nq.gz
    ├── 13d5810f2bdb6a8ae5b53aa17a3ed73f87b1ed7a.nq.gz
    ├── 14300cb799b62184044a8c02ccf7f3fc426cb7c2.nq.gz
    ├── 14bfea8b3ed66f24e0bd1414a0077b3eadec26b8.nq.gz
    ├── 154d3f7cee66acf9c33214a03a3fc23d0161a46f.nq.gz
    ├── 1551f80e483dfaf400ef09054796ca7f970156eb.nq.gz
    ├── 15bcf02a80a2d2099db5ac879f25d520c115439f.nq.gz
    ├── 1670641beef8f2d23e775456b251f84b5495b5e3.nq.gz
    ├── 16c3246d867cd3228382027090b10dc07e1d779d.nq.gz
    ├── 16cf5c218e5916fcb0ef6d1b28785613bdf1c4ae.nq.gz
    ├── 16fcbcdeb4481c07afd80a223785746a43b3fa4d.nq.gz
    ├── 1789b1735502b2ba5d70440cf30234ab90d1d244.nq.gz
    ├── 17c8f05c6ebee9162dd3a241874e07b257dcaef4.nq.gz
    ├── 1848b62ce44b9678fa6f2d0dc8a10d7f548f156e.nq.gz
    ├── 19334c369b23ece3840714291f01c37699dd5c2c.nq.gz
    ├── 199cd231f14cd937a50bb06bae21b80d564309dd.nq.gz
    ├── 1a46feaf5f32c4656419988375a1bbf3dcac7056.nq.gz
    ├── 1a4b987323039656471e08c07525d3dda74422b8.nq.gz
    ├── 1ab49597c69390eaa1ab5b718c7b83f3baf24da2.nq.gz
    ├── 1b39ff7b305084df62502f6a8a4211a60d8f4d07.nq.gz
    ├── 1b694c1d146e564cad106ddebd6a21d66194d194.nq.gz
    ├── 1c090e51f78f261698fb6f7f960df33d8b6dbf96.nq.gz
    ├── 1c0e6213cb2e2fcf2227aacd64b44f66cd2eaf38.nq.gz
    ├── 1cac2c252e9d089b0253b8eed39e4562732a4684.nq.gz
    ├── 1d704dbcab4c955b2157ee384a212f47c382679f.nq.gz
    ├── 1de1222c92ad808d3822ac86a0596fa03987cb4b.nq.gz
    ├── 1e235d29f40b9f94a4fea16c4ea8f666d70a3209.nq.gz
    ├── 1f5f3fe3558861daf684b2d09e5adce9845b65a7.nq.gz
    ├── 1f995edeb502674610bae24051ab45515f7626e5.nq.gz
    ├── 1fb6c805ff055115c06d5be063f3af63a0c994a3.nq.gz
    ├── 2002df532822fa7070c4a88a6119f17a2c8e4c9f.nq.gz
    ├── 2086228d29064b0130df1a2615f3076a22619d2e.nq.gz
    ├── 20f9b5d63785ba4037eeb3b82c7ff94b5aa8d53b.nq.gz
    ├── 2279a5427fff797d36cf8171aee277c25d30993b.nq.gz
    ├── 2287745ffeaf573c3a14ce4386cd22792b934b67.nq.gz
    ├── 22cb1ea87dfeaa50f2e0f5ceff2e06ff9a8f9aeb.nq.gz
    ├── 2402e35f1aec340e7011eb415d7fc7d2c3818958.nq.gz
    ├── 24334d12720064333b95738278b81f5c686bf683.nq.gz
    ├── 249617d77eda5dc2004d5244b2c08927a3459783.nq.gz
    ├── 24e4c408ffaa0465e80efd92a1321febade00ea0.nq.gz
    ├── 263aa9a7ca8442a94055c18be14df890e4043fdb.nq.gz
    ├── 2677082fc60cb9fdc19ae51571a4887f297cbe24.nq.gz
    ├── 26ea83ff7c4e86cedbf623e437d489f6e00fcd53.nq.gz
    ├── 270c611018df7c9c912bf148e9197375480ab7b9.nq.gz
    ├── 283949eea84242a26d6bac25f1d6be7b5cea05fe.nq.gz
    ├── 29443fa25c3d51476c1008d92d14fa28e28e6f23.nq.gz
    ├── 2a0f26c2424083736a1a01e16df9cfd035123f41.nq.gz
    ├── 2ac13ddc5e3bc9670847742f8d1d23646c906abd.nq.gz
    ├── 2b119758eed62abe05284ef84012d1cf8694131b.nq.gz
    ├── 2b27ba27070ceb26070f19cd6a26757133df3374.nq.gz
    ├── 2b97eafa91435d598b828f198dee349762907aca.nq.gz
    ├── 2c0f2e4d97f99c050d7c29b8b028be9caec7bca5.nq.gz
    ├── 2c141ce19171aae52e42c157f8f0998183f009b1.nq.gz
    ├── 2c70b299ce498586ae71933a8e7fc8bc40953489.nq.gz
    ├── 2d05a23635297238fbe6098638401211e8136918.nq.gz
    ├── 2e468b345563ae6dc3ae3a8e8c2b5756d9d48db7.nq.gz
    ├── 3086036ab787e6f7465d6e4af083f0f6654f2256.nq.gz
    ├── 30cdf25037899695bc366d5ac844087e685280d0.nq.gz
    ├── 30fc814163ceff6d9b18c7a8366b1193a087c81a.nq.gz
    ├── 311494c2d93be73543a48d8acd8b4b1026e7bb22.nq.gz
    ├── 312adf57b1114c48ff3c1763aa3dca01c98aaa55.nq.gz
    ├── 3170233256f63645d8f91dea686833a8efd56525.nq.gz
    ├── 318523229682575556088719b4771463d712f2ef.nq.gz
    ├── 31e639502361d5e7fd137451962aea9d7346cb5d.nq.gz
    ├── 323243559c2b6a4d42cbcd3ccf1fb1f42d49f403.nq.gz
    ├── 323851dce3d04347b44ab54e89c9d895ffd8ba02.nq.gz
    ├── 3260486826cbf285187bc5e756ae20084ea256fc.nq.gz
    ├── 332096f41a401cb2b1decb3d63d35a201626cf66.nq.gz
    ├── 33db7a29a91751f344909e52edd1bb57a1c019d0.nq.gz
    ├── 341706137480a4d35f3c9ec754068d7bf4678cf3.nq.gz
    ├── 346c7441cf0d1bdd6d2e3c1f3ca1c1538c75091b.nq.gz
    ├── 34a0e01570ecd0e9fa357b42a80ca171fae03917.nq.gz
    ├── 350a94d8e5d6256cab823802a3e782ef5838b8ad.nq.gz
    ├── 351a0247112d9fd5046c3fd7fac1e0c6f852b862.nq.gz
    ├── 3585374d8967c5b12693cb7494523b8107fbb8fd.nq.gz
    ├── 3695599618209ef7f0a45bf3329687722b0cbaab.nq.gz
    ├── 36ab877de16a133dd7ebf20f083e69b998b8302d.nq.gz
    ├── 37234bb2db3d241d3dc77b89a66a7cd4f94f953d.nq.gz
    ├── 384e920269b1a1ba98a66c7f5210f3024a77e7d7.nq.gz
    ├── 3a054bf35b1bc60b8ef1b200e10f54826dac7309.nq.gz
    ├── 3a3fe270b33c5def91dc43459e0efbe626c54a67.nq.gz
    ├── 3bc774dc5909d5e6fcc8e7db872a66fd4a8c9028.nq.gz
    ├── 3be50d78409d8705e8a5c9e91008578a2b973405.nq.gz
    ├── 3fb8a3a6f6d06f8a147dd26f52080670436cac05.nq.gz
    ├── 40549f2d1e9a506fb669f62a23a45744547d8a5f.nq.gz
    ├── 408d6338f3dbc9e343a3610ab426a00c4b6ca522.nq.gz
    ├── 40d285cd5d01ce022fd283d541f829f25562a9dd.nq.gz
    ├── 4127c19c62b7cac54723e7493864b6925c900dde.nq.gz
    ├── 427a49d71716dc62f3385d0334266cc84074259a.nq.gz
    ├── 42a70c2c7d6e9dfca8ee571ce5ed5cc8cd017524.nq.gz
    ├── 43077b246094f0b2ea3a54995d76fe1d320945a1.nq.gz
    ├── 434163fad9cb8d4e5be33d9ab330c9235dc8cdff.nq.gz
    ├── 44537567981e7e54924d151df93d2b2e191c3043.nq.gz
    ├── 45671b5513ca9dc22ae7afb1e989719bf541a43c.nq.gz
    ├── 459f0969700956998dc8532d2a08950aa84353ac.nq.gz
    ├── 45fa18cd9368b9cc04714161b80562f842760175.nq.gz
    ├── 466ffbe19fada2e0116fac6d08bdf923b9c37b8e.nq.gz
    ├── 46f52c564e4cb00305624bd19d95a29670cef4cf.nq.gz
    ├── 47227ae9d3084207a9f1d4d303a5b6030d216719.nq.gz
    ├── 478b808c8c22a0cd838beadd74fd1b396321a91b.nq.gz
    ├── 492ca37bb07dadfd96cabc7a76e2c647833082b1.nq.gz
    ├── 493c2320b6db2268ba9da3ac80d82ae1e374e1bd.nq.gz
    ├── 495959ea50af6961320e8b7b8312870f9225a8e1.nq.gz
    ├── 49d32b6d4bd1a498265b4762371be482908bd7ee.nq.gz
    ├── 4a5e65a6ecb217cca10670fdf3d5ffe9d3c34203.nq.gz
    ├── 4c33fdacff89453f2523c360e05ad1dd4ca71cbf.nq.gz
    ├── 4cb7a51777e29251093f3a2e9d8a92333c648be5.nq.gz
    ├── 4d123ba87a04eaf4a77049cb0b894cfb6ebaa817.nq.gz
    ├── 4d1b7f697d45cf282f102c5be8cb727a43b9b03c.nq.gz
    ├── 4d6e1e4cbca09d0aa6e892fbe52b0f7aed3ba947.nq.gz
    ├── 4d73a1422e6d83ae399e3ac9e945f5ae9b7ed003.nq.gz
    ├── 4e4e8316c1afcae925ff7297578550f7c208a20b.nq.gz
    ├── 4ec641f6c0ed15842b1cc4f25e6153aa3018483b.nq.gz
    ├── 4ed8f2e8ee3d11a508ca752b96b5019a6e2e2d2d.nq.gz
    ├── 50ce8f7eb654aba2e8140087a60ee19c11d8891f.nq.gz
    ├── 51990dc0702725edac3b89b7bd5136ca00720668.nq.gz
    ├── 52e5af987fdeff5321647a454cef9272ce64c986.nq.gz
    ├── 53d29cef9d92e739579261210a8ef50dc4983be0.nq.gz
    ├── 5412182d7e83d550fb9783136683207b98ced7e1.nq.gz
    ├── 5439c507889277eda546f9b9d093d0464b9a30fd.nq.gz
    ├── 550f6b81061e8301e31dbdb3838865ccdb3ebad1.nq.gz
    ├── 5569cfd906cfba9bbae86dc3e30ed9f35f9d6a6e.nq.gz
    ├── 5578feae516f5b48826f879195458a05a35b8542.nq.gz
    ├── 55f2b2afab6d11c419397366c75ee9ebeb915db9.nq.gz
    ├── 5661d3fd74e27d320366f68aac094c35abdc0ee5.nq.gz
    ├── 56b3dbfca697dd1d5f82fea5f8b02da2fed98023.nq.gz
    ├── 56c0087423fede7e68da6ec752cb5b82a0a4dd6e.nq.gz
    ├── 56d88a94e4236d0b65228a5dbbcdb525eec3f4bd.nq.gz
    ├── 5725a9d8a4148ebfe9f6f0136b0da4c3f0b39974.nq.gz
    ├── 579445b96f3536e87eda484fa29b64e108f021f1.nq.gz
    ├── 579551581420f593143c148d5c0b53a77c25606a.nq.gz
    ├── 57f4f9e05fb5b6318f159419319644968a7b294c.nq.gz
    ├── 582c4b57230bce501eb4ba72c4b61eff996dbbda.nq.gz
    ├── 594ae2645e2ba0d5c16a1e783b9fbc30683ec18d.nq.gz
    ├── 595ed0eab38fb4536c44aaf3d89d13b005fae764.nq.gz
    ├── 599e7d136bf810f78925d905bcfce4394a44df43.nq.gz
    ├── 59bdafb82f2c467be933521962cbd10ba42674ed.nq.gz
    ├── 5b7fc855bab1d8c263a3235102d810df5b66350a.nq.gz
    ├── 5b8317498eddfd322bdb8dd38a0c2ecf356c6a8c.nq.gz
    ├── 5bab0c67a70846fcadb1be7ef2b1147e38db8d7f.nq.gz
    ├── 5c0daa66ec58ccf2257da1daacb16d60f6d49a19.nq.gz
    ├── 5c1d968a2ed2987a02f12d99e91167d63bb18e16.nq.gz
    ├── 5c99e71f60f8a97768db4b512b1e48ef3d61a1a7.nq.gz
    ├── 5cb1ad004311bbb3fd00293f664376b757936178.nq.gz
    ├── 5ce11cea489f8d67c532b4dfcb77e5899324d3a9.nq.gz
    ├── 5d9c6d48b4d7fa48c6e71bf13143ac1f0991cbe2.nq.gz
    ├── 5de26f107143d057222923281849bad2cf8cc01a.nq.gz
    ├── 5e815bbc6bb346769ae54d4461b788cc1ace73eb.nq.gz
    ├── 5e931249bce3ea64ff71e358225f21b293857f98.nq.gz
    ├── 5f01091e99522fea18f8cbc628c1fd4dc413a364.nq.gz
    ├── 5f1e3eb6a21de8223f7b1984b0f3d25b0768226c.nq.gz
    ├── 5f69f9192059b371cb9d97ea7e56c47354a42aeb.nq.gz
    ├── 5f755d70e29a1a43a5539f17b25b2990b9b0edb9.nq.gz
    ├── 5f92d179d8e35df32061daab2419e5a3c8210629.nq.gz
    ├── 6041f1a305e602a3c32d8a99b045a4c20d5c12a9.nq.gz
    ├── 60584214af7a92e0f32e3fa713c9199f52ad6f72.nq.gz
    ├── 611d84224c50c4560409736cef6447b45111c9f9.nq.gz
    ├── 612799a06905f33558fa6ede3cf423aefa670d03.nq.gz
    ├── 622b56a0c01b4276ec6cae2e025faaad1c893058.nq.gz
    ├── 639dce4ec7bb20a74360981f941494330f5c3176.nq.gz
    ├── 64466778c040f1bee558f77910b099afeceb748b.nq.gz
    └── 6488ebaf71cf63bbda5290025cb2f06904c2fc64.nq.gz

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

[run-llama/llama-parse-py](https://github.com/run-llama/llama-parse-py)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
