# Repolex Knowledge Graph of ultralytics/ultralytics

RDF knowledge graph data for [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics), parsed by [repolex](https://repolex.ai).

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
rlex download ultralytics/ultralytics
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f413c7b2a603469bfcd17cf01671baba3b030eb4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f413c7b2a603469bfcd17cf01671baba3b030eb4
│           └── chunk-001.nq.gz
└── blob
    ├── 0019c2c98e4664506c1e7068d2e7bb05b6992815.nq.gz
    ├── 00a40726195ceb09de6541496834cd92212be23f.nq.gz
    ├── 0129ece23e63012193a92e4884bb69461bd0f532.nq.gz
    ├── 018041cc39eea2ce216714f814e149302b7242bc.nq.gz
    ├── 02ce52fd0180c8d4f0c3ce58ed458bfb73904bbe.nq.gz
    ├── 03ae6aaa0251b567bac501e6fb93571e15fce650.nq.gz
    ├── 03c33473a0bd45076fa98dfe3ceb1cc71394a1f1.nq.gz
    ├── 03e6d427070a983aec94cb6a63f5ed6de8f3040b.nq.gz
    ├── 043e904146defa24ad40514b37f93adb28c599ed.nq.gz
    ├── 04671a26cf9e660d1b71ed5fbb1440073e18d644.nq.gz
    ├── 048ece887dfb31850fb0d5079e922e21486ba8c1.nq.gz
    ├── 063369f25fe653fccd5af4ce40a35ebbfc7f25ff.nq.gz
    ├── 06c0fac47160707fc1856e248bf7ab6c36f0ee4f.nq.gz
    ├── 06d1f845b0690eafe0568a9366c6d91f924a67d6.nq.gz
    ├── 071f855764b13dfa23ebb33838803d8b276af452.nq.gz
    ├── 07a981b581e7796a4034f221b62d45f2b7c9a7a2.nq.gz
    ├── 0800b03c2921ef90b5700c171579b1132ea49de9.nq.gz
    ├── 08a1f3ec9d526eee35695bd143e35f36615c17a4.nq.gz
    ├── 08aa54967330d39a53d175e41b5c649c33d82622.nq.gz
    ├── 08ad9f27f3dac873dc0daef541cc573e2979763c.nq.gz
    ├── 0a57b430377511f985ba3d296fa517a8fe9486a2.nq.gz
    ├── 0a7123a2441b84e249d8ceebd6cb53c5d1a164fb.nq.gz
    ├── 0c7ac86f73a30f882a837f944249d08f60e78a4c.nq.gz
    ├── 0e551b9c47113a6ebed7f66f7e55533232142c49.nq.gz
    ├── 0e5844c7f488ab233c8596d7c4470d66f35ed23e.nq.gz
    ├── 0e5a6198c6643f5e80c9a5d98c68cace257b3426.nq.gz
    ├── 0e9d5b94305513d86cedf5db43e2941808001e62.nq.gz
    ├── 0f002685d684e5e33623e5b992ebbfb86e0bc720.nq.gz
    ├── 0fdb80fb59b39769031ce53a1cd0f2c76b874d58.nq.gz
    ├── 0ffadb4201c91707ee1ba4149860405581d64324.nq.gz
    ├── 1030d2b3742df4d89c33998731fc41e14e2a5693.nq.gz
    ├── 10484f03058a10f3d7e4ee9f64631b2d547a824c.nq.gz
    ├── 1158aeced10299933ee1a223899d4a30a617e2d2.nq.gz
    ├── 11a05756a041a07920c7ef3d0f415227aab48986.nq.gz
    ├── 1220308eeea1fbc4a8776fe34b6c1e9673c1080d.nq.gz
    ├── 12cba7b1c915200e925ddfc645f971e10a935c91.nq.gz
    ├── 1392cf1c2536e08417de341dfeb2eeaa1090bb48.nq.gz
    ├── 14a11469fb3223f710b2845a88ffcd438f06165e.nq.gz
    ├── 14d574c52f2d92809a5c9f7d0fa1e78ec3889560.nq.gz
    ├── 1522965979feb9f70bba939aaaeca559ba28deea.nq.gz
    ├── 169890195bbbf5e027d02ae4dfc57afc309642c0.nq.gz
    ├── 180e7bcf4f529d4e7123d112b0e29d0d39226842.nq.gz
    ├── 181b4db2b055be1d7c1bf0ff8e9789a07df81e24.nq.gz
    ├── 1844702b5520275827e5cc05e6721164ac8ad38c.nq.gz
    ├── 195d75f4a6f59a6d266299cec3647605e182b6d9.nq.gz
    ├── 196aad984ccb91494d7f5413c7d8a0441fde6b0e.nq.gz
    ├── 1ac39679e8686537ce39cc2ac7c1931767bc8a65.nq.gz
    ├── 1c5158801cbcfe45e49517b2adb2c5efc940974d.nq.gz
    ├── 1d902ae69566226dc77265214f27ed32fab416f3.nq.gz
    ├── 1e9b86dfc4b09079e59bb57e580fe6a9a413333b.nq.gz
    ├── 1ecf1a4cd15ba3e11c934539033814b94c9b5e1d.nq.gz
    ├── 1eff6dd69e8f9230ce2ba0ef21dd144fb6179a05.nq.gz
    ├── 1f4551b7c03cc5f21e63f8478d1905436d74a955.nq.gz
    ├── 1fdee5e2f65e3b49c94657154f81d47e24144af9.nq.gz
    ├── 1ff336b5e50c782388ac7c79021f460de7169c2c.nq.gz
    ├── 206faa43bc4564996f635747297facca9c771a2a.nq.gz
    ├── 209597ffef81d0c5392148fd7d5aacc33a0ac568.nq.gz
    ├── 209665d7f4526af316bae057022bd22a1e7fe974.nq.gz
    ├── 20c92990e70e70c97e25a645e5fbae63a2351f14.nq.gz
    ├── 210a2fda12fe2f434d5fc9caab3080cf3c4ca5d7.nq.gz
    ├── 214153288c5dd2659890df6e965da7f243314fe8.nq.gz
    ├── 226a825d8e8c532a21a9962418f8f0200eaaf1b5.nq.gz
    ├── 22b4f7c0b5c2cfba9fd58b84dae79ae468589b00.nq.gz
    ├── 237e71ff7f5f7452c9196353cbd634ee6ac9b47d.nq.gz
    ├── 238c87989869a88611158e635c82fc1c26de18ca.nq.gz
    ├── 23fa26e28a0a555deab7b7202d05eb1c4f9ba37f.nq.gz
    ├── 244652ee02f0ca33b7b0317c288ceb0be39c4627.nq.gz
    ├── 2457321f752b14ddfde78c106de01d550a46807a.nq.gz
    ├── 2507c594163f0c7893d72acd29f437fb0e846dfa.nq.gz
    ├── 25364c0dc7edf0ab6330657f805296c8c384a3fb.nq.gz
    ├── 25fd62b8a35bfe848dc0a40a6ea4aa4d2cd163cb.nq.gz
    ├── 2616817704f61eb117c64cd92655af2a2d26b9cc.nq.gz
    ├── 26432bca7b74e74e49a6b82027e565b2ca44677d.nq.gz
    ├── 265f7ba1148162e46a89f6a16b460b3f1c784840.nq.gz
    ├── 26dbd39f7c48196feb6891fadef8395f776d40d1.nq.gz
    ├── 27194e57bf8ad2c0ac117ee8b3d7f6d930e2e9f3.nq.gz
    ├── 275c1a38e1cf4dff4c1834ec0d7bcbc55406af2c.nq.gz
    ├── 28842caa9e0148b3143e0a564368e697ec120e01.nq.gz
    ├── 28e4181a47c55d1dc4b6784ef7058509683a31a3.nq.gz
    ├── 292c86a7d4306b428ce618cffad7225c51df96cb.nq.gz
    ├── 29a15af1f768eacce3ba034061ca803c4418567b.nq.gz
    ├── 29a61e5cbb2f0d85c86331e5d08241b46e06f8e8.nq.gz
    ├── 2a1aeaa97f7a29e49bbf96049e8de1cd82a9805d.nq.gz
    ├── 2afb1a3ab7000998ca7064aaf39d4594bef7518a.nq.gz
    ├── 2b45823f4fd9c5635d2734fab0f3890ca763b9c5.nq.gz
    ├── 2bfa9b67dd5616e1b5fbb86f18a1f43090fa8156.nq.gz
    ├── 2c159f999acdd8cb53b47227037840b7e09e5d5c.nq.gz
    ├── 2c4df696f90af47e3c6b11ad664ab995f667b723.nq.gz
    ├── 2cca5597ac6ef89b3df8df547a3bd84f65d05707.nq.gz
    ├── 2d35fa067262bcfdbefc40369da329d7781c632a.nq.gz
    ├── 2da8311476ce5d11d8daab329d87fb11e892b752.nq.gz
    ├── 2e3fdc9e9744845189831d829dc35f57e4ebcab2.nq.gz
    ├── 2e53fbe62d690394674e35ba44c944d98f24972b.nq.gz
    ├── 2e9e8553a13b23c590c51fe29e0f86ddc451d5ab.nq.gz
    ├── 2eacaa6465e78d42267ac69004aca01080d0e33e.nq.gz
    ├── 2ec9d7bf3031a2f6538d99b721626cf9b99b495a.nq.gz
    ├── 2eef59c1eb459a2fe0510aa330b44312591b6ae4.nq.gz
    ├── 2ef0ac984b9a0ef50f3ef891737eb19626748ee6.nq.gz
    ├── 2fbcd7185f96efa44534c86c659d2633814cf8f0.nq.gz
    ├── 30f7575682835170112ae53b76a1a8fe5f84d1ed.nq.gz
    ├── 31395c04f5f8823112ce1eb6b524a8ad776645d2.nq.gz
    ├── 31a87362f88448d2a3e25ec794b09bef2ac7a739.nq.gz
    ├── 32095b111f33ed4367fbe3976a9f7c3a99fb6cba.nq.gz
    ├── 32f241bd39f974c7ef5777c1c2af8464ec5935e3.nq.gz
    ├── 34b194a01ba3f0ef14b92326014e053d9f4bd540.nq.gz
    ├── 34c21d7ae63f377ac51431e5e2aa06c79a20d62e.nq.gz
    ├── 34c30e05ff4f774f1fb20d4102be038036135b1e.nq.gz
    ├── 354d6dbecb1133e9af9489798fbb83fac7a8ca07.nq.gz
    ├── 3593b48e695cb9fbe36c3ac9d546ac2b0c736b74.nq.gz
    ├── 35fd7a7a084a7c1e8d874a725bff762a58995300.nq.gz
    ├── 3657c3077d554cec4d943649e73eb5ad997f7ca6.nq.gz
    ├── 36a921a9a36a0f0a0bf1bf03be9014c6886f6c6e.nq.gz
    ├── 36d26bdd15079ebcaf0694d52d473f074391feb8.nq.gz
    ├── 376d1aba90c24c0df93c14af4a45f5b98b6dbf02.nq.gz
    ├── 37f0827ab53c5105fe3f058db1e66552174405d5.nq.gz
    ├── 37f71b934e3342c925db4e39cfd64524ebd7b335.nq.gz
    ├── 39291ef39b89d9457868a4c42c62c27c08fd461f.nq.gz
    ├── 396066cfad22a3057835e12e37a9f7b261611f41.nq.gz
    ├── 39b3e89e93a8b289ddce4ec63e28c055f22bb117.nq.gz
    ├── 3a10629229f8a8e5769480d004bbdbe42a633e79.nq.gz
    ├── 3a15268a6e0f9bc1a7eb833cbbedbbf08672abf2.nq.gz
    ├── 3bc39d3c6ff7917d274f0587f7a9ed895beaed13.nq.gz
    ├── 3c6ee0c25e7d37de138a7f6c9191028238fc5724.nq.gz
    ├── 3cafa681e803cdf81c2638d01ccf246424bf35c3.nq.gz
    ├── 3d76b37db07735c6fde366b0ba18d00c3fb17987.nq.gz
    ├── 3da1fde92e3eabc2929ca3f8775483aed98247a8.nq.gz
    ├── 3dfd66cf11324dff1e4a5070026771c780c83af6.nq.gz
    ├── 3eafb3bb42fbc3116d380e2a35953da134ec8547.nq.gz
    ├── 3efeccdf0a1e3d0bc882647b7bf6e858dcb9bcbe.nq.gz
    ├── 3fe78680465e14199a90d41a74a6d43f16d0fbd3.nq.gz
    ├── 4090296608941473a2be1bd7748c42461eba9166.nq.gz
    ├── 4109ea4dd752a9c2b1521243eeba59fef991ef15.nq.gz
    ├── 411895f1cdf4ae9062680eca25e6ec7f8d7394fe.nq.gz
    ├── 4118f0b2ab7773fd1666fbc92d0b8af630d74c16.nq.gz
    ├── 413033b22bb425d62f3e496f7516901beffa1399.nq.gz
    ├── 4183c2b3a386735859bee13655e36946a11591a6.nq.gz
    ├── 41cc3657b2e6bb889d825a0de710832f8c86d262.nq.gz
    ├── 41ed12c866b0e558701515730fca8d566bc8e6e6.nq.gz
    ├── 42cfd9e10ea3754a492f479ea58e8ab85a076e1a.nq.gz
    ├── 43fbe0ec98f1cdb9c9e83605c769bd5adcf07842.nq.gz
    ├── 4428c11b95d93cd86ca5dbe73ea023723b33a118.nq.gz
    ├── 4490a14d25424450eccb4ece5e8febda13ba826b.nq.gz
    ├── 44b032ed1cb5da59ec8f9e9d4c7b6774018714ea.nq.gz
    ├── 44e0b1bf6beb9913e320909aed700569f73f8d61.nq.gz
    ├── 4597320deef71aeaef98cca3d5a26032acdc889a.nq.gz
    ├── 4711deb8cb07c3d8c14b724c1352360107d02d8f.nq.gz
    ├── 47effe0e94a94bf7c99a15990187c5dff7894c7d.nq.gz
    ├── 481f18d196c42a1eedc65fd0b660dc253c161baa.nq.gz
    ├── 482710b02a6b8c5994e06c6832ddaf7542b86bbf.nq.gz
    ├── 483c2e8264f44d1e9117bcd8194fb0e7cb2837ef.nq.gz
    ├── 48a5c5ee33cc5ed3be676f482e1cb4687a98628a.nq.gz
    ├── 48e9d3c1711dc5f2524cd1828d9d71f8112b9197.nq.gz
    ├── 48fb0c88cad48dabbfd8471f1312e60c8af6f603.nq.gz
    ├── 49129bf70fc686eba8b6d2d13591971e7c985324.nq.gz
    ├── 4923e1260a8c941510b4749b40a0fd6b31667ea6.nq.gz
    ├── 4af5a373d4f397c1a3d9590f1729c0e748e3170c.nq.gz
    ├── 4b2f903d9d67838a1dae6d5ff579869c326b390e.nq.gz
    ├── 4bc722126ad8868d2c2e320fecc08d772769aaff.nq.gz
    ├── 4be4b302352cda6b482a390036346861f7e7e424.nq.gz
    ├── 4cddf325e5a50726d9e50b0c3c6a13d168d1ba3d.nq.gz
    ├── 4d087576d3b10e87298b51a36ca668bcdb6136ca.nq.gz
    ├── 4d486c290c91483dcc3971a6ae9ca5d63d4fe18d.nq.gz
    ├── 4e109fb7f841eb4d3ac2c1bfbcd96e59ff58c2f2.nq.gz
    ├── 4ed599de9ee112f15286edbe544563968dfb4d70.nq.gz
    ├── 4fc9eb29bad151741c39c958f1dfba17bdc4c25c.nq.gz
    ├── 4fe5e1776fc82e4312c660b810cae9ef7b1c10b3.nq.gz
    ├── 50356245d3c381e8f3f2adf1a21586f03e4d2ebf.nq.gz
    ├── 511cead7a350a9bc92fc6305fa576026cc0d1b12.nq.gz
    ├── 5152df0d4efbb7b23f9a56ad8e43d60e293ecff9.nq.gz
    ├── 51d740f485252d8140fb6533a4a7f447f1822b5f.nq.gz
    ├── 5209db4e3f0e28d8529d3f62e84533faec3b9c38.nq.gz
    ├── 523c70e523c39360e0711fcd47b09c667ce52d26.nq.gz
    ├── 52b1c7e9aedc4fbc04d5c4f48f4ad214ad6a51e2.nq.gz
    ├── 533a73cde0d1265dc3f4e1366e8ea8939353c697.nq.gz
    ├── 5343d70a7222569789f0585ed93762e2c6db46ce.nq.gz
    ├── 534de2b3c875d49c2b0f6d6464d9ffee663b8c90.nq.gz
    ├── 547db457e111164e6a965c33fe276431b8d9e5f9.nq.gz
    ├── 555cd53d40ded2f05a0789648ed6e89812a25115.nq.gz
    ├── 557db77a23555f8f82f29d52b7b70ac5f8c29eec.nq.gz
    ├── 55c080ced4bc83df54b24689ef2a9252aa2445e3.nq.gz
    ├── 55e220ca16a824346de246b1edc2095f93646e35.nq.gz
    ├── 561cd6ea69307c78bcf878c292eb2c4283cf4358.nq.gz
    ├── 5739066fa072edcd5b4dc5e7c9c7ec8c92a3b906.nq.gz
    ├── 576e6ddf334597361dd426c87a6e02a229b21c63.nq.gz
    ├── 57f2c8e554be6498cae9bc0e00bf147216eccc84.nq.gz
    ├── 58e1d71581726d4aaee6efb6e0c34e3bc06c93a8.nq.gz
    ├── 5905aa4aa81d9ca701c33b1eb4fb65b2facb21e2.nq.gz
    ├── 598b447f6c92f1fa76026e0bb043d8fb4a46fe51.nq.gz
    ├── 5ac3c5374f23830347925e4b5edc1c69840cb6d0.nq.gz
    ├── 5afd227f02531353adc10b9f06f87ed0047d5137.nq.gz
    ├── 5ba5e7a3d1885c03f08d651044f188ddc96162dd.nq.gz
    ├── 5bada5baea088e82c7a778daeb8dac6d4d588511.nq.gz
    ├── 5bdde5451c0429eae9f07f4f78658972d4b74fd7.nq.gz
    ├── 5c8010b076e67c3e803d70473181da70ab050671.nq.gz
    ├── 5d1b748bf1a27563c3bef330c707f52a7ec690dd.nq.gz
    ├── 5d52f6bff17293b357f472d9244f52ae4deef4a1.nq.gz
    ├── 5d598152b9c0f221e61ec7c0bef2d6f83ff6f309.nq.gz
    └── 5d6d6a0154ad7120d516560e5e0cc1af0aa84001.nq.gz

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

[ultralytics/ultralytics](https://github.com/ultralytics/ultralytics)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
