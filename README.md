# Repolex Knowledge Graph of Farama-Foundation/PettingZoo

RDF knowledge graph data for [Farama-Foundation/PettingZoo](https://github.com/Farama-Foundation/PettingZoo), parsed by [repolex](https://repolex.ai).

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
rlex download Farama-Foundation/PettingZoo
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b0fe02166d2106f8fcb6a6e0ca8125765699bdba
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b0fe02166d2106f8fcb6a6e0ca8125765699bdba
│           └── chunk-001.nq.gz
└── blob
    ├── 00c0d6086328929a09b1e01750176b5588e3bcb7.nq.gz
    ├── 013bc5ae29f56ef7411ffeb346e42aef3ec65362.nq.gz
    ├── 0164e4933a6d598d2d5112fdac8ed720212ce318.nq.gz
    ├── 01f9b401c4a829fbd6b86e8f24c5b8ff23aad62a.nq.gz
    ├── 02040ac175fbaf849ae509fc60b92575cb09d92f.nq.gz
    ├── 0230ac3f9afaf39b15f65e747d961a0a99194a88.nq.gz
    ├── 02787cf2e58d7a32989f3cfc7568f4577d647115.nq.gz
    ├── 02b00c86e3b4f42353c79e6b39c8e631c5bc920c.nq.gz
    ├── 02c04531005e01342d7f50430b1503e3d15661ee.nq.gz
    ├── 02ee67ba86a406272de996336b777ce12aac5c31.nq.gz
    ├── 0326dac16f64e4df4cbe51bc81a1d7fc05214e79.nq.gz
    ├── 0350fad236da1d3179728995ab791e08fa0fc7da.nq.gz
    ├── 0395d224fedba598a367d634f6fc8f6ee2620a2c.nq.gz
    ├── 03c680d91c39004422f3eee5fe8991ac1d30903e.nq.gz
    ├── 03f6b4b9377aa4f8640236949478053f34e5ea24.nq.gz
    ├── 04d963934e0e257db2a216bb7bc9287928fba2f5.nq.gz
    ├── 04e108b282cb457f92b18b4c136870f6bdac9923.nq.gz
    ├── 064ba15f84bb21c9e681af57612a51ea4e9c69fd.nq.gz
    ├── 069422654adf642b8e81a1e6466eeca3892289e2.nq.gz
    ├── 07d935d31fa8a6a4408551a66268f4593f5f6bc7.nq.gz
    ├── 0963c29e31189ef72fc73a33513f8a7d9679e0fa.nq.gz
    ├── 0974ee2665c36871196011d3ea6d9de30de92802.nq.gz
    ├── 0a75b7bf84100e252bca2a8ecea5fb7a4060af8a.nq.gz
    ├── 0b10ea713fcf729b9a818f139d2868f9f10d38fe.nq.gz
    ├── 0b5770bfc73bf9b696437281778f93be973bd681.nq.gz
    ├── 0d008ed651766659b4020718d46bdd7ea6cb97d3.nq.gz
    ├── 0d6c847fbc6c824289ed53f3d30a81db90a361a6.nq.gz
    ├── 0d70b8bde1fc2da563e885af7485aa5927379a56.nq.gz
    ├── 0e3058cf13a9242e46450c2aa8f3996d605971df.nq.gz
    ├── 0f02b7dcb125ff338cf92722deba016b1a35f949.nq.gz
    ├── 107e2192211355e19f839152fb9e12c493df7f63.nq.gz
    ├── 10dae3a1ad297369a27007911aa78b3ccc7e2f93.nq.gz
    ├── 1197d680ba562a9a27c54f046f1631a5e52461f8.nq.gz
    ├── 11d38719e43a1d4f2f84d232d0f490f96d711425.nq.gz
    ├── 1257b48922cedef9ddf453e5940fa8491e85f454.nq.gz
    ├── 12a73f9a7bc1975b9e7cdb91f4d4c2d01717d8c0.nq.gz
    ├── 13a16257b20d7194a281cada4e39af002aa523eb.nq.gz
    ├── 1451088f24d15ceb03166638e6855ee07e744119.nq.gz
    ├── 146d42025e9af90e4bb16b817c2bb2ef23f52e17.nq.gz
    ├── 149ffeac64f01456ad5c61e065b0e6f043a28348.nq.gz
    ├── 165fc47634be11383b295dba3b920ca2af250c80.nq.gz
    ├── 16a21c927a121eb555c78fcd94f6dff681f120ad.nq.gz
    ├── 16bb1aa64d0aab683cc250c6daeeb2906e82152a.nq.gz
    ├── 1baa2fb4217a396e6dc6a7f4f481ee990d52b56d.nq.gz
    ├── 1c4b361b34cf9e19310a1c4aecab2eb8837b0961.nq.gz
    ├── 1de6b6c2e7fe8cd880ccef869bbe62a061104b61.nq.gz
    ├── 1e1395afbd9d2f596493632a80551a430f3faa93.nq.gz
    ├── 1e7142bcaa4722acacb0babfd8f461ddc9002dce.nq.gz
    ├── 1ef40670450d2b3a4a3027458456c3b2ad499d17.nq.gz
    ├── 1ef77a3f666fd26dbaa2833d891e875d6b694ddc.nq.gz
    ├── 1ef941b65daf58d1f1f199e9f44189a4b2dc6906.nq.gz
    ├── 1fa811241a07ab2d659d18c0c0a04805666bd95f.nq.gz
    ├── 20034330bb57bf7c3bfb0d4b80eb82737208aa20.nq.gz
    ├── 20595ff91c675cde2b4996f9de1f5605b649cd64.nq.gz
    ├── 20646988e715359f3cbce98d6618a476304b8503.nq.gz
    ├── 207b97c50e4b26c88da77d33706f6fd08b8613e6.nq.gz
    ├── 20f8ca2d9fa709f17dc859c1973fbbe349da8c11.nq.gz
    ├── 21d9d13108a68a4f925bf77bbf2bec4189647b9d.nq.gz
    ├── 222e585b2532a7776a9abbd8631952e6dbade8dc.nq.gz
    ├── 231fec3ddfbb1875bf1cd0b5427a191149d08b75.nq.gz
    ├── 2363a9faf20734be04d09ee6a9cd1adebd321dda.nq.gz
    ├── 2479c70bf6f8f3012a2f31eb656a58495a317181.nq.gz
    ├── 254152d69f6b3c6bafb1e41a9b4d471089ab1456.nq.gz
    ├── 2556f80bf20e6041060f7e97b88edf4cc1a1f5c4.nq.gz
    ├── 25d7fdc62625d695ed6a1947d09a797bf4d2cc8a.nq.gz
    ├── 2617293cb296386cd05f9c90e974ba59d1405dbd.nq.gz
    ├── 262c78a5b08b1fe8ea91a273eff4e96b455a7135.nq.gz
    ├── 263b79c2fd67eab9692196337c2625b545ac2b77.nq.gz
    ├── 2727e9bb74968c2d34bbeac0d4041ea5fb3845cf.nq.gz
    ├── 2738e1708e8f91a72ad5cba46ceb823201f8a973.nq.gz
    ├── 27e4c31495923ed5a84668bf8a683c25cd6c27f0.nq.gz
    ├── 2813e54fcae99d02e4d1c5c66ef2951a925eaafb.nq.gz
    ├── 2880135cf14d12effeeedd482c0652121cd36a49.nq.gz
    ├── 2952501db5904fb55e97182825c5e1156e7b2bca.nq.gz
    ├── 295a716b0ca4474f093101581d07f3a1a5df64bc.nq.gz
    ├── 29c66f79c51598a037a68932a112f335cbd480f7.nq.gz
    ├── 29e8e097aa0fd29536fe878fc2a96c97c4c63bc5.nq.gz
    ├── 29ec77332ffe8d320372441721e76db2d9bb3eb6.nq.gz
    ├── 2a392bd7ea9fc75571ab7899834a31736903646f.nq.gz
    ├── 2a6d6c5b447426440c4103e0203a884f4aaba8b7.nq.gz
    ├── 2b47f1aeaf5911b2fa529a34a8d47190d128d27f.nq.gz
    ├── 2b6e248df6aaf933736b0153efcfa86145bb9bfc.nq.gz
    ├── 2c0872ba11943c9701f2321123fef30ca47a96dc.nq.gz
    ├── 2c37d2e6a7f2c1dacfca81e8cbff7e03d3373a38.nq.gz
    ├── 2d3bd303606ed402284d05816c9276891591e4e6.nq.gz
    ├── 2db0c308743b4b7cad204c7889037257bf26fd7e.nq.gz
    ├── 2deb868c2fc666f2d2c30b1527e1424cfa0612bb.nq.gz
    ├── 2df157f2e2ede9febb26728c81e3ebc5cb21665a.nq.gz
    ├── 2f01dda725c4e4f7e415ae45a71d347b0e3a1750.nq.gz
    ├── 2f09ee22dcf4fdeb808d3720e96606ee9cef69b6.nq.gz
    ├── 2fb186cefe090f3064ae66f4d0e5dfd1100e09f3.nq.gz
    ├── 30893923d1d43be89b29494d1b9104e309f74573.nq.gz
    ├── 308c9cf8fa2ff23e3ab24ae697e822c12b5adcc4.nq.gz
    ├── 30fa014245babe46c6d871e54c43c273dec6f667.nq.gz
    ├── 31158dec6a01fb957aee6850c65c44c62d0bf92b.nq.gz
    ├── 319b2bba3f823fcf8f375086eee4942a989649b7.nq.gz
    ├── 31cc03bc7c30b60109ae5695d41d2c2f9c505824.nq.gz
    ├── 32096dfa4549ca8406215dbec44608a41962357f.nq.gz
    ├── 334e0966b758d271499b2ec835a9b6e3edec0460.nq.gz
    ├── 338e093f614db06e106961696921d07a9346cdcd.nq.gz
    ├── 33a54c93a56592c7e3bb8fb92f6cfa42dd89e0fd.nq.gz
    ├── 33ecda188fb6cf1e258ce099409cabeee6b3cde1.nq.gz
    ├── 340433d119d1ce1f5319676331d14154dba4f9ab.nq.gz
    ├── 344a6e3fec2ba253abcab0ae397759bc018e241a.nq.gz
    ├── 35001fcb368cee821d9f284e1cb3498756caa4cd.nq.gz
    ├── 35997685037fc5e838c395e0d5029caa2139b0fc.nq.gz
    ├── 3661681fbb3c7ecb568520f3b2e1201bcf092b5b.nq.gz
    ├── 36989616dfd8be0725e844c7d58aa1953888fb72.nq.gz
    ├── 36bd89320f757b16ded77c75c9869fdd1df0650d.nq.gz
    ├── 378da9cf0c8b4d16ae838e0423d6c14960354953.nq.gz
    ├── 379727ec871be35364b35b1ff888afa50b81ce33.nq.gz
    ├── 38783c89fa6abc8be8bf147bee06d92f3b437629.nq.gz
    ├── 389559c27f750002fd815a943a843077e79a6fa8.nq.gz
    ├── 389d70a3082d9e90f14ee60cd774b996adac9ed0.nq.gz
    ├── 38f6580282ef1dd5388aa1aad0384509f75fb70b.nq.gz
    ├── 3938b43e80363b4b13eacff54d977ebc48d454e8.nq.gz
    ├── 39cceb4150080dd8847be09a3866dce38380362a.nq.gz
    ├── 3a82e14e0b015f6338531d8a33de77908ecc0ce8.nq.gz
    ├── 3b248b31c32f657ca9ac5089292b0be5435868d6.nq.gz
    ├── 3b8ce49fa0b9e075cffcedd00d8ca73a4dc5106e.nq.gz
    ├── 3c0db97863c2f7f607a49fab13046dc6e59c59ff.nq.gz
    ├── 3c4ca531fd037dc335b7de67d76c6048c44a7f4c.nq.gz
    ├── 3c75862d9e9ba1b1471eac56d11143cd6f43a83f.nq.gz
    ├── 3d22866ae98a6980d3993e303c2d722acc6b3870.nq.gz
    ├── 3f26e4905966e8cbaf0d75d24451d8ad2db35256.nq.gz
    ├── 3f735b9d9f4e1f9013f8f799a9639ced9bfeed07.nq.gz
    ├── 3faf70d2401cf7884da23474a25a4d0bdc140fdb.nq.gz
    ├── 4059c6c056b6cbcbda2576e8a271d2fe977ec11e.nq.gz
    ├── 40c8f08d8aa07b6fcd4cefbd88188aab208b8e28.nq.gz
    ├── 4112392f643addb900a1f5c51e5e14600564b3d0.nq.gz
    ├── 41474bbbb4d08020b223fde159526452572e37de.nq.gz
    ├── 4211158e21485e955123e22771c13c611ced0dec.nq.gz
    ├── 4260ccdd16191d44953b728f5630d17e4348d692.nq.gz
    ├── 4398c6f221b6230ce1822391be38d7ba18c96fe6.nq.gz
    ├── 439f6f78980212dd1528098ee11b9dace0f9eb2f.nq.gz
    ├── 44b0344fb7325b3560b671324d3ac8d120bd1efd.nq.gz
    ├── 4509bb3f67c3533a5daf1994a853c7e0d27684c7.nq.gz
    ├── 450aba762c19273f28894c09666b70609184fd1b.nq.gz
    ├── 45319208e1ef4eb0866b77fd3b58b937f64b37fc.nq.gz
    ├── 458cdcf20ec6c543ba01a063d780136be3562fe6.nq.gz
    ├── 46922c475c60f6814d17adea51de670ba3f469e6.nq.gz
    ├── 46cdd6904a2ae815e18c1c5e55a2943d0cd54832.nq.gz
    ├── 46ef599e37cfa5b798505f377983f25040f0a839.nq.gz
    ├── 471846ce2206977fa67e29ad459fccdd58dc42dc.nq.gz
    ├── 476779a8c10dba0daa216397f3ec1ff4723854e2.nq.gz
    ├── 4799be85a914fd8911cb2536dd5f0ae81419d0f4.nq.gz
    ├── 481b0e69e9e5421c864ff3c341e353299c62cce4.nq.gz
    ├── 48cd7ffb292353deeea17b92526b16c070761aae.nq.gz
    ├── 48ef4c79b4f3c725fbbe2e03f1a7e5c7b4b03aa2.nq.gz
    ├── 49735ea78d5e562c29b904978edf23a6cca8394c.nq.gz
    ├── 4989cb910529b2bf335af1d10c715d02a3626d9b.nq.gz
    ├── 4a1cd3e89483aab7cd0648d3ba23067b7f9d6684.nq.gz
    ├── 4b0e3e54e0a1df66c5498967ee48e982667591e5.nq.gz
    ├── 4c6640abea067c687f6d13e7e6faeab475d6c74e.nq.gz
    ├── 4c9fa13e698f7d44c98449517471c157bc93061d.nq.gz
    ├── 4dafc6c124b88b0b54adb3fb24d21eed64398fe5.nq.gz
    ├── 4e762fadfd51da4847da2bbbac3898b87ae0c65c.nq.gz
    ├── 4f71d811936bff8fae55db956757138b340220bd.nq.gz
    ├── 509fc5e2901073814c2f1e09628347ba5df739e9.nq.gz
    ├── 50a9783f9bf7beef727861a01cbc61fa962c6b1a.nq.gz
    ├── 51332cc4547dc83144d7139da0a2d82e8a97cd21.nq.gz
    ├── 519a99a036f74228a1a478f001f16eba2f3f815a.nq.gz
    ├── 51e86214a5ba0604f3cf82f2d18a1cb3c0e0ca25.nq.gz
    ├── 524e5dc3b41946f10a8e30a3ede1a9d7c24ccdfe.nq.gz
    ├── 52668143792986dc77c30489e90196c3348e4f0a.nq.gz
    ├── 52d2e61518963bad795badf3e6cb07379830a3bb.nq.gz
    ├── 5358dcc65485efb8a0098b67bbcd53351ac9860b.nq.gz
    ├── 53e99a2ae9c7708b887d3184ae9a81cb9e52a0be.nq.gz
    ├── 54e28aa9363541c631cee3162e2676417885c6cb.nq.gz
    ├── 55cff1b7249d2019f1db23867c3dd6e8ebf5ec33.nq.gz
    ├── 55f711ef44d30c8ab847fd7c22db918c8f0d11d9.nq.gz
    ├── 56139db582c53f03ec2c2f66a382926eda899991.nq.gz
    ├── 56a9710301f00d1f779a450d959a94d2b304d655.nq.gz
    ├── 56b8a3a4d9f552303097e28ca2fb4af387104c0b.nq.gz
    ├── 56fa01811d663a21ec56ad800e6f56d480a95222.nq.gz
    ├── 57531a4a57f029b0a1eabcfafa1bf3087b8a25d2.nq.gz
    ├── 5830686a0c41e6e1cc4289801678920543e44808.nq.gz
    ├── 5863be5a8b7c5b84cad96e1e733f3f3ac618ee38.nq.gz
    ├── 589271d07754b7c110cbf668279c782adc02812c.nq.gz
    ├── 58b8567ffe9c9c80a9bac804b56a66284fbc6701.nq.gz
    ├── 58bf7b9d2556a7f60a76a2a09b0726d426a5ef45.nq.gz
    ├── 59fe5312686f5df1ffab675b698e065cf6c6029b.nq.gz
    ├── 5a57becc0e505fecff8aef080174a2dc4c4148bf.nq.gz
    ├── 5a7275d9246411fd5b729749148e9b87c6b834f5.nq.gz
    ├── 5a9606b5658bc16cfa7c2db90923ef1f598612c4.nq.gz
    ├── 5abec1f3908e4c8aee86e129d63832a7a8004bba.nq.gz
    ├── 5ae95a04e2f75e6e977097f891b88a2d63e6265a.nq.gz
    ├── 5af5af6023e889ea7ba1db9e40a1c14eb39e17ab.nq.gz
    ├── 5b4bf52761e503a7375f50295e8f5223c773921a.nq.gz
    ├── 5bc1f08970b15c3ae4be0adf6c6877d8ce7e1960.nq.gz
    ├── 5be39d46e6a3ea4dfd0549c036a30dab8041b45a.nq.gz
    ├── 5c1e4de5826e5c18c91c07247e249eafb86e539e.nq.gz
    ├── 5c76f44902c9f15f8621cdb6662c4972aee20f18.nq.gz
    ├── 5cf7c7614c8271bbfeb9e179eadc3cbdcd6600a3.nq.gz
    ├── 5d8605075a15eaab67a3ee612db6c37d5308cb2e.nq.gz
    ├── 5d8fb6a9e4e5a8f005bce2aa12bde4027e4978be.nq.gz
    ├── 5e2466bce300b52f28005cf79f6723b7c46c867e.nq.gz
    └── 5f829cc1fa812d7814ebcad19d8265bf143800cc.nq.gz

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

[Farama-Foundation/PettingZoo](https://github.com/Farama-Foundation/PettingZoo)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
