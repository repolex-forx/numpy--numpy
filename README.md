# Repolex Knowledge Graph of numpy/numpy

RDF knowledge graph data for [numpy/numpy](https://github.com/numpy/numpy), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download numpy/numpy
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 651ef74c4ebe7d24e727fd444b1985117ef16fae
│   │       ├── chunk-001.nq.gz
│   │       ├── chunk-002.nq.gz
│   │       └── chunk-003.nq.gz
│   ├── lsp
│   │   └── 651ef74c4ebe7d24e727fd444b1985117ef16fae.nq.gz
│   └── repolex
│       └── 651ef74c4ebe7d24e727fd444b1985117ef16fae
│           └── chunk-001.nq.gz
└── blob
    ├── 0018b73485d688be3d5783f404faa7c38ed819e4.nq.gz
    ├── 003df267a2f35254fb3a55f9d5e2b22b779b1b59.nq.gz
    ├── 00600f19065e727923a6c516aa7f16ee7d882b35.nq.gz
    ├── 006babe7a764ed65e5b594e4d9e1ff3d61928197.nq.gz
    ├── 00ed5daa70ab886be196343368b909fb0f44019a.nq.gz
    ├── 0127df9f9113a6a97b9b2698d7d387d9ee3d3033.nq.gz
    ├── 01a77895405e127c881fe91cec57c7c0d3f40cf2.nq.gz
    ├── 01b0b1c19700c5d5b021a260671826b783a7b954.nq.gz
    ├── 01cb5be4ca5e72836a286153f2c29d1aaf86147e.nq.gz
    ├── 01d47af500dea7a639c1f8579bf90670be0ce1ca.nq.gz
    ├── 01da361c603d51a453248eaa95dcae0cd08a1fff.nq.gz
    ├── 01f944df97e7472e888f580181a8b0f29f7c986b.nq.gz
    ├── 01f9febaf403a95750a3bc321fe9ed83684f9ea8.nq.gz
    ├── 021d08601d9db8c615488e6bc9c6539d26e1bc9d.nq.gz
    ├── 022efcaeb4ed6ebd3906552cdfdb1cf720d06bbf.nq.gz
    ├── 02430b08a9fd61d7a888174382a92c46bca8b895.nq.gz
    ├── 02474665540a1817c543013e72b918ebcea8b76d.nq.gz
    ├── 027f455decb0e8ebe511bc9edf55f036bb724923.nq.gz
    ├── 0313b0ef819e44fedb9397f13e7358b0b5255d0d.nq.gz
    ├── 036e923ec9995d4409aed9762fd4abbcd57c2c7b.nq.gz
    ├── 03b3270791dfd7f6f6b2a27e9d778e58de9c42d5.nq.gz
    ├── 03b809e3deb4e33e1e3bf6320c6d9e275a791154.nq.gz
    ├── 03d4aacf6311a08710b888ab5d6a91b76a15fc07.nq.gz
    ├── 03f81f21c66f2f68c3e542bdd1c3912c8a6652c4.nq.gz
    ├── 04401f991fa1f12397dbe159df6047c0f6a8d7d8.nq.gz
    ├── 0451a463e5fab8172a593b335f5fa10e5574f173.nq.gz
    ├── 048f85db6de2d644cdfb9c88da796b7cf0c9bc06.nq.gz
    ├── 04ee229b229dca11edf59fa2be80244c67c2e174.nq.gz
    ├── 051cf27e05477aaf3b3a61cb824ead1905b55784.nq.gz
    ├── 05712c02c48be943f56cc3fe645c33860484334e.nq.gz
    ├── 059b843dc0ed6d669d0963e0fa50e707cd3ad522.nq.gz
    ├── 05f234d37640fec4eff1e632777b7e8bcb9d0d8f.nq.gz
    ├── 05f3822401d52bcdbee6ce2ae9669374e9a33e6f.nq.gz
    ├── 06077f79ca08178ac7beb07585605be83054fc13.nq.gz
    ├── 065a207d2e824388e84ced3d645eb74227f3e5dd.nq.gz
    ├── 067782dc0e440b0cee1b2b72f6b67edf488c0c15.nq.gz
    ├── 068d251f67e1c45fb391401281e7c8a0014372be.nq.gz
    ├── 0766764958d56417d280cebd30e0134c630d27f2.nq.gz
    ├── 077189ee2c8c576c2da3799b788f2191ea75f544.nq.gz
    ├── 07c7e07bedcb88e54c5860319b7502d6c8eac2d5.nq.gz
    ├── 083a1fa15e54e7c23b72a1e6a6f27edd4e82be09.nq.gz
    ├── 08b050cd261a55200abe0a260b491adae7c50924.nq.gz
    ├── 0915f765e369a04ba80362256e9f36e13a310b7b.nq.gz
    ├── 0927a7ed37cd47b8f498ffbd0d005994f478131c.nq.gz
    ├── 093f0119e0d5fb1ea15acbfe529052f574736193.nq.gz
    ├── 0982742abc09296a47c33cbba840ab344072abf5.nq.gz
    ├── 0989c53d7ee77848a31715d8e0f783ac5586c8e3.nq.gz
    ├── 0a03929beb733093d3c7e1e2ef57ae678dfd3e76.nq.gz
    ├── 0a0d8045c7cbbd902c5fabcb088af1b3d4fc9aac.nq.gz
    ├── 0a181fca34121087e69e495b361b157177cffc36.nq.gz
    ├── 0a2e68ae192ae95422ae47136054d394bb45d2f0.nq.gz
    ├── 0a358bd6ee305a3c9debf861f1a376ecbf61507f.nq.gz
    ├── 0a3f0b9d66e6782da5d1f29f73309d780abd5754.nq.gz
    ├── 0a643d1e5d4f28d25ba0ccbd3dd02b3df93d318d.nq.gz
    ├── 0b5357632cb8a376178f01b4db1b312806d5142c.nq.gz
    ├── 0b96bb05a4f2869b775f281579f5bc0e28583b17.nq.gz
    ├── 0c09e02f92e5e189ae67c763614f001cb489b836.nq.gz
    ├── 0c78f35946e7141b447b7222703729e297dbbd6f.nq.gz
    ├── 0c9574511d1c6376dac80c8898781e2e44f4af7a.nq.gz
    ├── 0cd78c27e2e70c9b531f6e20528eaba60b92fa8c.nq.gz
    ├── 0d8408198845ea8ce84c5e7abd6bfd895e63f7af.nq.gz
    ├── 0e1807f3f900b4f7c5f5af9a3744ece71e894ae1.nq.gz
    ├── 0e98f046740fbf694e8dc5799a5f2bb17fa32ee1.nq.gz
    ├── 0f3fff2a9274715943c88474c61e510874515026.nq.gz
    ├── 0f87dfb840d48a921b8a542f33b731dd0472c1d3.nq.gz
    ├── 0f8869f726f13523788179d06c2163e5f714ecc6.nq.gz
    ├── 0f89276145fea22e85d71a2cf1561a502a1ae915.nq.gz
    ├── 0fcf2c1cd38c90e2ad350e5dfc3acd1caf5cf329.nq.gz
    ├── 104c2e1a899efa384fba6b286ca23752f1d856c7.nq.gz
    ├── 10d12330cdc5dfa3b5c00a95c392f65c38f0543a.nq.gz
    ├── 10d9dc9627bb529331448d407ae62f59ed08f2bc.nq.gz
    ├── 10f02f42b66573af5875a118f55016170e4b007f.nq.gz
    ├── 113134bbdfedff0ba880ea608ec9809fb603cd05.nq.gz
    ├── 1196eb754d361dbb2e53a25745f913c2f0cdb83e.nq.gz
    ├── 12061702d76a6102d1293d97b373ca1d94c73762.nq.gz
    ├── 12bc8a267310a5268adf7eee12d0684785e0c778.nq.gz
    ├── 12f10516096710d302c3d28938884432898f17eb.nq.gz
    ├── 131790dd66b8dfa8400593babdedb6f403814cf7.nq.gz
    ├── 1429e232ff8a7c28a702a59988a14a7eed11c210.nq.gz
    ├── 14669544cc9ec345373bf5f719e321348fc96a40.nq.gz
    ├── 14bf8bb78984a5f633160069e6230e54abd433d2.nq.gz
    ├── 1535bbf587eafd617a44104301b5f6cdfe2e9bde.nq.gz
    ├── 1543051dc3d8f3d19279eb58eca21e05144913b6.nq.gz
    ├── 15b868e23f7ae1afebe1e0f3aed58f2ae0ee63ca.nq.gz
    ├── 15d4c871e60d1cd5d2b6482cfbda8b8d0f7aec9a.nq.gz
    ├── 15ed7e6863c9bbda67fd63f57db0c429293e59ea.nq.gz
    ├── 160327de2d44467fb55c93ed624b8f0632e90637.nq.gz
    ├── 1677066719b8aa589e304eadb14cb4c319f348db.nq.gz
    ├── 16abe5ce197c39cbcbfa46d0aecd120dc12e9cc9.nq.gz
    ├── 173612ae8b8efaab04f9de794bbbc745a19886c6.nq.gz
    ├── 1739290aec8c0331a36cc70cd0e8e2635a5d1752.nq.gz
    ├── 173a6ad5328d4801bb81ca55c25e8a94bf0e0e9b.nq.gz
    ├── 173fd126cf336d051f3f2f33deccef1f50ce5a53.nq.gz
    ├── 17557605def5f5d243975e00077389624b4b38c6.nq.gz
    ├── 178555da065cb138c9e6481c24a41ea00afbfcc9.nq.gz
    ├── 17a9cbbde900283950b449d877fb08e1cda1d0d5.nq.gz
    ├── 17caa9e025432db89c97cadba5954fc7359faf5a.nq.gz
    ├── 17ffb4a430bcd469b3b2cb9f5ff2d051c97639c0.nq.gz
    ├── 180c55063ab2e1d8f304150c8dbb09e64d286cba.nq.gz
    ├── 1846d81143cbd698eddd3b7936309798431c5bc5.nq.gz
    ├── 18e036ab0dbb85dee65894fe986bb1cc3f95718b.nq.gz
    ├── 18ecc01e56795f86ed8343b3be4ac7ac00011d2a.nq.gz
    ├── 1933b145d69147db598643cc05d2fd0efb220c76.nq.gz
    ├── 1a9ac2c9e2cc1e4b07dc094cb4f7411d856806a4.nq.gz
    ├── 1b1ef4a773326a5ed1ee7cdd538141d7d744613e.nq.gz
    ├── 1b26c23e4a6abf130aa6d476f783129bb74d1478.nq.gz
    ├── 1b322aca3bd61adac93fb8e693bf74babb818087.nq.gz
    ├── 1c2141c98bf1e3fcf54b428f63cee4418e54e4a8.nq.gz
    ├── 1c25eb677d878b61ae1938da5393552c9e4578d3.nq.gz
    ├── 1c37dc2b9a245831e5c847624b92e7308a27130d.nq.gz
    ├── 1c3f96b8b13d1b79ff47da1b682b3b8fb8644bed.nq.gz
    ├── 1c52749a85177fffcdd3fa12e857eeaf5f5cc828.nq.gz
    ├── 1c6ef1b2eb43c4ee0bac9a691bde23b52658f4f7.nq.gz
    ├── 1c97d4d1eafb0ce397c49f65b6bcfcfb0d564e59.nq.gz
    ├── 1cd31217a60be3892879fd596dad8db3ce661a7d.nq.gz
    ├── 1cda1c8ddd3d4fd31f581420426feb4bb1ee3ee4.nq.gz
    ├── 1e14042b00c1c873bff77f0b44c85e53bf215854.nq.gz
    ├── 1e367e3148295c1760bd1dccda8a3e1975c5511d.nq.gz
    ├── 1e4bc37f44ecbe0f1741f2c03d2bf9fe42b38f7b.nq.gz
    ├── 1e508f3e5ddab963733055272a76ec85d785a395.nq.gz
    ├── 1ec212f8bd22cbccee2af73ff5ff28d340046c7c.nq.gz
    ├── 1f555a90a665ccabe16c447c059ebb19e0e31650.nq.gz
    ├── 1fb7a3acd0f8e51307480d765156e8486e26ecac.nq.gz
    ├── 2045c12cdc5b76e995baa7b48abc0e9e6f0f54bc.nq.gz
    ├── 20797dc712e7cbb9c083d6c606901c54c4bc3b3f.nq.gz
    ├── 213d6976013bf2d018d626b2baf47c3ff49964f5.nq.gz
    ├── 21ea18b77f022e836795a5b86416f12dd9a53459.nq.gz
    ├── 21f1dc05a931fd9e5d2068129c89e9b558abae39.nq.gz
    ├── 220cb3d8796867b77519fd88667ebddae66569d7.nq.gz
    ├── 221529929dcfdf61f2207c5aab1d2e1abc95d196.nq.gz
    ├── 2229f3ccb3840a0cdb6b582d64f8af471a21e887.nq.gz
    ├── 2255daf768f8a164ac64fd5704326b7b22f05a67.nq.gz
    ├── 229ac26db9e040d587746563e1478cec88f95fce.nq.gz
    ├── 22eadccf723108d079ab6ea3225009ad804dd517.nq.gz
    ├── 22eedc4f163f8d362be5a9a1475a5e8bdd8a5716.nq.gz
    ├── 230ca49557f42da8e63e1076d5407e59d281603a.nq.gz
    ├── 235705dff5894597b243e83f9c640a8e0c2afb15.nq.gz
    ├── 235822dfab8fe5eaa86e721944059b4a0ab5db62.nq.gz
    ├── 235ae4fe5af67e0fc14f6065075323822c4d1433.nq.gz
    ├── 237dc94abc5bc1af8ec228f7b9e0edbe73214a2e.nq.gz
    ├── 238dff9522a72b5c8167dd3d7f4d207a4a451433.nq.gz
    ├── 23b35243b2f6d1ec59becb25df5bb78e90473e79.nq.gz
    ├── 23e7d7f6ee6dafe4a2d687663b3229e272e7aabe.nq.gz
    ├── 246ebba6b6351379c5833a1dbfc7811bc959628b.nq.gz
    ├── 24b5eae249dab2b6796862619cea58b8e4b039c1.nq.gz
    ├── 24d709d2c802005d84130d6dff682a9a0314db77.nq.gz
    ├── 2588f53b264dcdebbc0caafbd962a187dc81b39a.nq.gz
    ├── 25de09edfe8cfef01fb92acada4beebdb1bd2f96.nq.gz
    ├── 25f6cd025c918e7253314bbc07e958d64eca69d1.nq.gz
    ├── 26511d7bf5148d880f9190a647b1c948913aefe0.nq.gz
    ├── 2665f89b52d2f17ce7b0a857bea73ec5fab2df88.nq.gz
    ├── 266847cbe9fc301c8b9c532a9db9e75a31f340ba.nq.gz
    ├── 268fdaf299c44e0e0b68cc1cc71db299c967fb55.nq.gz
    ├── 26e45da34251df7e06c22f9c5a65bd2f5b880840.nq.gz
    ├── 270e11c56f409586040b18d9658c5fe172ddaf9e.nq.gz
    ├── 2746b049d793dd0d9c0d75d3cfc7ca284a4c28b0.nq.gz
    ├── 276937be1d7341c13f061014cc948f2a3e146436.nq.gz
    ├── 27c6aeb89829048147daa7c15fdf187a0111ee43.nq.gz
    ├── 283021aa12d68a2d94d7369647c25cca4787139b.nq.gz
    ├── 28b72259a60526a2192583982ab37e6f937ceb05.nq.gz
    ├── 28d3f16dfc74f7f0f4a16d9c8baa702342f9a35d.nq.gz
    ├── 28e1c29acb602086bfc18dd111d341d488d64872.nq.gz
    ├── 2910acbac8f49cd64f5eea343dd6f26e7de4db74.nq.gz
    ├── 295d52ef4673b203fbd9189791991bd826786d0b.nq.gz
    ├── 29ad05318e45497f9a7cdb6f2b7a9cfce4664cdd.nq.gz
    ├── 29b47f2571149c2da15f7edb9a8811685ec6aed2.nq.gz
    ├── 29ecc3dfe402b608f73f043596ca1e4363688928.nq.gz
    ├── 29fbb9e5e7675fb91aaba981735e92b9ce33610e.nq.gz
    ├── 2a2ec3da562857e06034480d0d02c803a9c5414a.nq.gz
    ├── 2aac6158e206d80ba12d54920dd03f6bd55499ca.nq.gz
    ├── 2ada0c5a08d4fa5bf2b2e6e5a99e3103f28cd54e.nq.gz
    ├── 2b108bcf9cb4fa449cc9e131e5ff8569bc67b7bc.nq.gz
    ├── 2b3b7ebd33ecb42b8f8e01e52a0dc9e80ade1e9c.nq.gz
    ├── 2ba907f594ad81bfc8e71c81611c56a8772b7dd4.nq.gz
    ├── 2baae18674c99ee5fbf3800b58757d96eb21b6f1.nq.gz
    ├── 2c15d9dbc5dfa966cdf6a61116c6d2ea8d3fb418.nq.gz
    ├── 2c84b6960545eea376d9971a03c532b36043c695.nq.gz
    ├── 2c90404da1b4a8d27fb938b60d0b9a97f219cc12.nq.gz
    ├── 2cc8f6a8081d68dd1ade3982f024c03ca2fa53c3.nq.gz
    ├── 2cd389d44c25ae540785c1c35ece8ce7a8d15560.nq.gz
    ├── 2cfbec5d9222000c44d41387a6807dae7de5ec05.nq.gz
    ├── 2d1ed5576650eda3b7faf344c100a7d3eefd4fa6.nq.gz
    ├── 2d37e21092e7dce00687c205ee9100d31a643eb9.nq.gz
    ├── 2d8e4360ee84a72b63778b2dce5cbe10c09f32db.nq.gz
    ├── 2df05e51479da06a164d2619a176478600304c4a.nq.gz
    ├── 2e4ed27f351f69a1e3383bbd5dd3eb67d690df45.nq.gz
    ├── 2e6c6c96bcf73aa4861a4425de6cbd45353bdbd1.nq.gz
    ├── 2e7a264fe1cb6d5fc2854f197eaa6c4855046a84.nq.gz
    ├── 2e881542e1f6c59d0d544ebeabf79c2afd68fcd2.nq.gz
    ├── 2ee9183899cbffc9d6bcfb6ec9f4ba1047bad548.nq.gz
    ├── 2f241da0a5d964e97e1f6be55f2a399e4af47584.nq.gz
    ├── 2f7cd297fb75fb3dc41910654fac9c59b6520229.nq.gz
    ├── 2fb50c5efb506ef2b3283d78335fd1bef8d3ab76.nq.gz
    ├── 2fc1add999ffe6990167b2a025f6851cdc5f5d24.nq.gz
    └── 2fc29f6d5ba48039e9e4d6ddd570b1f927b96620.nq.gz

8 directories, 200 files
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

## Source repository

[numpy/numpy](https://github.com/numpy/numpy)

---
*Parsed on 2026-04-17 by [repolex](https://repolex.ai)*
