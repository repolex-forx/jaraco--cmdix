# Repolex Knowledge Graph of jaraco/cmdix

RDF knowledge graph data for [jaraco/cmdix](https://github.com/jaraco/cmdix), parsed by [repolex](https://repolex.ai).

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
rlex download jaraco/cmdix
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ca4e0b795a06d8e7444d993de70620c29f4fc36a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ca4e0b795a06d8e7444d993de70620c29f4fc36a
│           └── chunk-001.nq.gz
├── blob
│   ├── 008aa56d9918af261359f5398affb18aeeada7d0.nq.gz
│   ├── 04174a796d1c973741db3eabb6970a3d4f43e9f5.nq.gz
│   ├── 0b7b8f87fb1120843d49fa691f326d92d6a5aee3.nq.gz
│   ├── 101c8b58fc2b9b8fefb47d94c5a17b61dcb73624.nq.gz
│   ├── 10d412f406891b9683f832fcbc134c9bdf4f916e.nq.gz
│   ├── 162fc1bed2e90155c45176a5ae19766cfecc28e3.nq.gz
│   ├── 1845d006e6ff4189865509a4f77c5d44471214b8.nq.gz
│   ├── 1894fe0734b6029c236809e1798510b90d8e32ab.nq.gz
│   ├── 197562e12fc901980200df5cc0043c21803b67dd.nq.gz
│   ├── 1df509e2929fb46e5a1f259c31e39665be86d153.nq.gz
│   ├── 1e4f9d3db7d79e3aabab1dccb2581c4e08e01dd0.nq.gz
│   ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
│   ├── 2209de870d17bd6517a9d6a7b688c85d8ae2d9c7.nq.gz
│   ├── 22584b77821ef7177577ef75a3546da61b030ca3.nq.gz
│   ├── 240329c3604d8ead4c10aa8c88352caa8e4ce7b2.nq.gz
│   ├── 2746985e3f2af787aafbaec0234528e6aba632f7.nq.gz
│   ├── 2c4ca3e676b5938cd6f35363d9e3e06603d56d2b.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 346a95cbd9150f31d55e44463b18b8137d78da75.nq.gz
│   ├── 36f8a4380b63b52654513f3a0cca37d69cad4832.nq.gz
│   ├── 399afc08dd9d87002539a735c43b063e1ad9f7d4.nq.gz
│   ├── 3b3d850afb6183fec2a4352883f3caf4cabf26ed.nq.gz
│   ├── 3c8988ea5933bfa048d13175f9517608d049f6ea.nq.gz
│   ├── 4081134397cdbba3c892b9cb23ff9de2681130d3.nq.gz
│   ├── 41f6204f772ecab84513312b6f8fc70ac760e509.nq.gz
│   ├── 4303400888c782c109f0783f0ccf2736d8352900.nq.gz
│   ├── 43c469da06f0a7d8b157e9adc74bd7534872614c.nq.gz
│   ├── 4462bd3e880b28de413d0e138d729c344be6704d.nq.gz
│   ├── 44c4c58f3456b93a217b2d5f192ab1f1fa60fd7a.nq.gz
│   ├── 4665a5261e7f943f1715020b2abc73d6f3fb5729.nq.gz
│   ├── 494c01b7197c0332bd213a7d973c6403480d43f0.nq.gz
│   ├── 4c4beeca102d48d7fa531262ce3c404e3dad9a9d.nq.gz
│   ├── 4d7d407cfb82af5021b3fd31095ade67c165c07f.nq.gz
│   ├── 4d863dde1414f8acb0056a950622dbabfce29815.nq.gz
│   ├── 4f3c83c9c766677b25a4bcf798fd7c462be4e23d.nq.gz
│   ├── 4f8d2881ad5e0386710ae2563aa96f006a6a195a.nq.gz
│   ├── 51d1d07d07047d7b441d373857ab6007e2887ab5.nq.gz
│   ├── 54c9000ec94341dd65c2053251b85b124017b9b5.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 57d05764717f6be81313731b4e7f4c7378c6bd20.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 5de4dfce834f88c68cca6c993712fbf91bacac09.nq.gz
│   ├── 62c207a9a53f90d827d7a3097fe8ec5d700f30de.nq.gz
│   ├── 64d3080110d514f2da4cfb3ddb100c952b8ae047.nq.gz
│   ├── 655b6f447bf4e6b3657745c465b1a905b2cb1678.nq.gz
│   ├── 671c5e4ba735f7ea1562bcd13c107b75e3715178.nq.gz
│   ├── 6a425ef175a15a3bb7be661d5cbc1a442ddb748a.nq.gz
│   ├── 6cb3d498a64bec36b0d10a15456dbc3f19bdd2bb.nq.gz
│   ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
│   ├── 70993555b701d86fdc3a8c58fe9de75856ab6413.nq.gz
│   ├── 71321bd302e2437e0363ced85281037f13b57eb4.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 7689f193c19a1715e55fe1d1db4e7c770774facf.nq.gz
│   ├── 79d3d2b14567de0d87154157e323d570a08a3795.nq.gz
│   ├── 7b5d817d05f742d52deaca3886ff978bfbfe1ab2.nq.gz
│   ├── 7f28cf5b1472f32d77f97b713d6dfda6e01688f8.nq.gz
│   ├── 8639cced1e8ca6d17908f9910b22bc98d222d47c.nq.gz
│   ├── 8765234689acf2fd54cbfab33b9a64fba72515d6.nq.gz
│   ├── 8930febc78f716dd685e87781b3342c25d2a877e.nq.gz
│   ├── 8a6655cfbdfb92bba5ac6d82e8f10a3f6d11f91d.nq.gz
│   ├── 8ea97368ae545fbbd54695a0a6c8f89c5bf52520.nq.gz
│   ├── 90075c527e54b5be86cbd3260f54a7c899ee7617.nq.gz
│   ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
│   ├── 9f3e7d871e947c53ebe0c5e5fac502af30521733.nq.gz
│   ├── a0c491a7df35a1b2bce9a8dc96b64b2482bc37e6.nq.gz
│   ├── a7bdc6310a73f710a4528ea009d7d0e48a2c5350.nq.gz
│   ├── aa29218e08ad21609d36eb82c6ecfff67e0b985b.nq.gz
│   ├── aa99b0da1ec15662606c774b2da6792e5bf4b96c.nq.gz
│   ├── ad32b2bd5f9c85ec1dfdd3702850f098e121dbde.nq.gz
│   ├── b01dbfd79808eacf17d8e6b4bcc288201185b0b5.nq.gz
│   ├── b095fff66aba9d444569f5d244c25274d46c59b2.nq.gz
│   ├── b117a66ad5f0288f9b7cc4d81456ac17669adf60.nq.gz
│   ├── b522569cefe58b437192a849ecbb6781cb025a12.nq.gz
│   ├── b7691370ad5a52641c2b650206c24ccae1241ba8.nq.gz
│   ├── b84e2e6388089aaf9ccff81e7d9ba5eeec6427b1.nq.gz
│   ├── ba492a91a74604fed32ed78e86006482bf291fb0.nq.gz
│   ├── bb68eeecee95d740a373d7bc3f873c6ec38ca205.nq.gz
│   ├── bdea8caccd1e93f8604b6cba328e2e49c91febe8.nq.gz
│   ├── c53cc31ec0bc7e6820b7bfdfa776513be5019143.nq.gz
│   ├── cc25957720758e7bc3890609e2c3aa60e8f9ea9c.nq.gz
│   ├── d071c2375d2419cc76f0334a624163d5e01710e1.nq.gz
│   ├── d21e0d25691c23d4476c215b145fab122544b56d.nq.gz
│   ├── d338940fc4edcba8789cf2b54939065343044c70.nq.gz
│   ├── d750621438e28a6f23864ca5cd993e560e3b0986.nq.gz
│   ├── d98ce5b1893db47c9cb138a892cb312d86ebacfb.nq.gz
│   ├── dc14d138519285873927449d17b7db6c17b36034.nq.gz
│   ├── dd1f81a421543d6c843466c77d83dc9225dd1016.nq.gz
│   ├── dd2aacb3bab77b03b358cfe7dacb234eb501ba5d.nq.gz
│   ├── dd39fc174a90a158373d3006f22cb2bcd08dadae.nq.gz
│   ├── dd8a91ae3ae7d2800e7a61ff08775151e3243348.nq.gz
│   ├── dd97e33a872680b4ad6b2bb5636e4d8c4ea3ae54.nq.gz
│   ├── e037f3d97166b0341e625e584b9e1a3e6f6e748a.nq.gz
│   ├── e05a3d4a2ab888e32952006d8cd380864368db5f.nq.gz
│   ├── e1090bc35239128f54097f426c1a0cf583ed59d3.nq.gz
│   ├── e3460c7b6fdda1fdf75eacdc6fa34b2cd2e919b3.nq.gz
│   ├── e3c5c17396ff1b6466d383d6ccbe4d9137a2fb93.nq.gz
│   ├── e52a283f1844f966e2f98db650910a3ca5f92d78.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea566ac7f198745ad43856deab3ca22ed5642633.nq.gz
│   ├── ed1d45a8d52ce96706ed7ceebee854147c0bf48e.nq.gz
│   ├── efcb8cbc2043faa7caf4f92fc7488bd6914c934c.nq.gz
│   ├── f680e1c073e5ad4be7ff7a2866daf33a167fb98f.nq.gz
│   ├── f9b3f059a804de5149b8a0035fbb073f1096920d.nq.gz
│   └── fd35fba9b75842a5e34944f14cfb4adaaf087409.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ca4e0b795a06d8e7444d993de70620c29f4fc36a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 114 files
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

[jaraco/cmdix](https://github.com/jaraco/cmdix)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
