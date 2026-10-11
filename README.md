# Repolex Knowledge Graph of pydantic/provider-upjet-logfire

RDF knowledge graph data for [pydantic/provider-upjet-logfire](https://github.com/pydantic/provider-upjet-logfire), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/provider-upjet-logfire
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5cf470dcbdd393521503955af67fd2e02aceb75d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5cf470dcbdd393521503955af67fd2e02aceb75d
│           └── chunk-001.nq.gz
├── blob
│   ├── 008e160fb820783067cbb074bf19e550c6c3c939.nq.gz
│   ├── 014e48eea985e9924ee23dc77a1beebf4fd90b5a.nq.gz
│   ├── 022203c4dfc5783849626926ad6538dad8939b2e.nq.gz
│   ├── 02dfedb45415655461655d041de73991398e3fb8.nq.gz
│   ├── 04a5b69ccd2ae4961cf1dc1c859efb511dec14f6.nq.gz
│   ├── 07c7463543466211b0c91346b509389f75e906d7.nq.gz
│   ├── 08295180e95fd82f6b6c3cb79f165be78ef5f7e2.nq.gz
│   ├── 083bec133123f41276dfdc02c7a18f43b027736e.nq.gz
│   ├── 0bfc5b3eb06175e0800747ce9074a7c713ea04ab.nq.gz
│   ├── 106238f2b240869e4389553ddbfc91afd5953f3d.nq.gz
│   ├── 11c91d215787efbc60f309be79da03b3924bf54f.nq.gz
│   ├── 163be8dbeb5e7dbe74f5fec92a48f89914c0452d.nq.gz
│   ├── 1660e6bdccb96565ded3caa9200e32f428ad8eff.nq.gz
│   ├── 17de389fc7529ef36f9adad20f3219d8624ade07.nq.gz
│   ├── 18bd2cc3e5f7442824d56f971e70b1168749c0bf.nq.gz
│   ├── 18edcaab4de5a93eac0bbb8755550cb6f0563341.nq.gz
│   ├── 1b567fde4e9bfd46bc9a6bc1094fde2a0050aa51.nq.gz
│   ├── 1ba080cc272d427fd8dbae95c31bcd8cf5ab9989.nq.gz
│   ├── 1bba4ca53f678b6d3b3eff4c9833817e38b4381d.nq.gz
│   ├── 1bd63530fb3d9a0ab15e6532e3af7c4199ff10c7.nq.gz
│   ├── 1f32653f9006ff966d2915a223ed7335060fc515.nq.gz
│   ├── 21c76f889c8fdddae0c3de6bbf14393662bebcd1.nq.gz
│   ├── 21d188ce77de6169db561354e268b24b1f3c122d.nq.gz
│   ├── 21f6f04deea5a5762d69fff586a8bdfd21551374.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 263dcb0ad2311152ffcad5e539f8009394359f53.nq.gz
│   ├── 267e31d68d766e5587d6c3b02eb6b6a1b3531540.nq.gz
│   ├── 2699126c0a7dfb28a597403977c9c4130e696693.nq.gz
│   ├── 27776d879e868a17da78b60c81495fe283872eac.nq.gz
│   ├── 28f1e807bec5b452cb0f891a0253ad80c647becd.nq.gz
│   ├── 2b8e23c090127bba48a55623aabcb9d5764c97f8.nq.gz
│   ├── 2bfd4f673a838e19a72b23fd18a68bff19fd66bb.nq.gz
│   ├── 2c07aaa9019962252b3e0b8fe7924f61420a9ded.nq.gz
│   ├── 2e2efc518b52977e620be63a44dc1b24fc7e65aa.nq.gz
│   ├── 2e5fbd1dd772c0dcca54980ceaaf66a4fdd4cc24.nq.gz
│   ├── 2e880a24e31e7d7189b87ea177c939b55c035c98.nq.gz
│   ├── 306f0bde34b64091f03bb21b9de05d3bc4785da0.nq.gz
│   ├── 309d646808ef24fe6d2b410680fccf273ce9f676.nq.gz
│   ├── 3580f99813360d6e370d97a4cb294de1ca080001.nq.gz
│   ├── 37b8c53ee805988ecbe7ae4e23bc36908c9fb72f.nq.gz
│   ├── 3a10078611cda78869c49632bfcd7e486b384190.nq.gz
│   ├── 3a8ea6f42d00bb07cc9010681dda4633ad13fc2f.nq.gz
│   ├── 3acf39d2af0dc9d6449ecfca76151fe405f94f3f.nq.gz
│   ├── 3ba7a000ab47d3998136aa6ab6427ed156cfe131.nq.gz
│   ├── 3c2324be74b1c0a60ef0ac048c7f46aedabb9101.nq.gz
│   ├── 3d2bdeb84b2711c51f4111aed4a729cc663bac47.nq.gz
│   ├── 3db139148c2e74bd9254ea92febf4faeb49f0e35.nq.gz
│   ├── 3e1ae93f25905eef26f028f2e8657ad57b6e9ae9.nq.gz
│   ├── 3e81f30698abdec79c65dcca298339d6e91aca3c.nq.gz
│   ├── 40fe57c41eaae4961ae44e41a203cd8c77528ef2.nq.gz
│   ├── 47450dfa7b947195115df373fb724c8d0d431559.nq.gz
│   ├── 47815046e796700f7eed51581b7a6fa2b2df3574.nq.gz
│   ├── 4795687820dbd6e977288474a01d0421977d3eae.nq.gz
│   ├── 47a53806364b5c500786836f8394585decc5db5a.nq.gz
│   ├── 47b80088cb881af41b73d810ccb1279e3f0fab59.nq.gz
│   ├── 48bd5bf59c2fcab75ff798c589d8d6ba27860bec.nq.gz
│   ├── 48d40687f36ef4a6ed86aed8693d374b613c2cca.nq.gz
│   ├── 49a1a43fc0b1b891197eba06fe02615f80bd6be5.nq.gz
│   ├── 4a424df541cce55c6122d4a5ee6346fe73aa6b9e.nq.gz
│   ├── 4bc22d4d392ba422ba390051955bc385c89782b3.nq.gz
│   ├── 4c02f8a223c68ef1de0537dfc7acea120f713763.nq.gz
│   ├── 4c7cb17160b166b5366e6f1c2b8a3231fd5c8ace.nq.gz
│   ├── 4f40b18b2b6d154c175065d947bd4050509c138e.nq.gz
│   ├── 4fbb5eecdfdc98628c21cffa0686be9704754693.nq.gz
│   ├── 50b7447c9eaf531e323f218621b95c69803aa2c1.nq.gz
│   ├── 5180433f522aa8404b01c5a74f41b67ac5d7954c.nq.gz
│   ├── 51be52831d89cb973b33eec659b9dbf2909b35ec.nq.gz
│   ├── 52b9c23f366c1fccdad632a229011e2edf88453f.nq.gz
│   ├── 5499adedb80777a1844bc1c41dd3e5c25ed3b153.nq.gz
│   ├── 57558404086cca47488610278765fc0ec85f3a31.nq.gz
│   ├── 5b7e557e1e005436b6dcfbbfc86aa9095f0a09b5.nq.gz
│   ├── 5caaaa94da4e4a74d34433a7cc14bf47ea5dec48.nq.gz
│   ├── 5d9982e12ba138aec27a364354bd199d45ad3916.nq.gz
│   ├── 5decb042277b9a0f51c4e7e570b49326dce1db25.nq.gz
│   ├── 60073aea49e1fbeab6952b00be47b82b66ba8a26.nq.gz
│   ├── 61a65f939d4b89bde70a448c6b2e4a04e6207220.nq.gz
│   ├── 632e8e369dfb1176dce8687a88ee4f1308cd5cdc.nq.gz
│   ├── 65faa27590e43ea312f7a8ea0ed26fe17361770d.nq.gz
│   ├── 69e667e7a478aeaebf124dbb2715586d83d02f23.nq.gz
│   ├── 6a3b817c589ab9baae8899f4498ac162f794b1e7.nq.gz
│   ├── 6e0bdf8f0b3ee1cf919c4baef1e065a1e592b4e4.nq.gz
│   ├── 6f07a9f4d618dafb4922cbf98a849d46505619df.nq.gz
│   ├── 6fb3e98c34289706b9c18f172d58be480d6b12ac.nq.gz
│   ├── 74021a822679c04d692c0f5fb03855f3fa654d6a.nq.gz
│   ├── 7441f37854cbefc2a314d22df7d9fc457dd16195.nq.gz
│   ├── 7627d1a98390d4fb795d4a5cd93a64060c11e2ed.nq.gz
│   ├── 762f1a1a9c197063ba7f4f6f4feb9aad3cb76d1a.nq.gz
│   ├── 79d7790bd719c019dd9ceac5a780d6d010a75852.nq.gz
│   ├── 7baf01150435b58b17ee9ecd40e00cea4b7fdcca.nq.gz
│   ├── 8132bed347435715adea9743da1cccb3e8fe2d5a.nq.gz
│   ├── 817c6cdc25bbe27b3d811f14a12f9f29e5843aee.nq.gz
│   ├── 81dc4aa2a236e1fc82fb6fa4aec06c2a9e9db9a3.nq.gz
│   ├── 836679dac5686f05ea8ca5fa07149fb324cf3437.nq.gz
│   ├── 84e16d4b09ba557624140ca5a509a20ca158279a.nq.gz
│   ├── 851f6c2ad189da128bd33aedece33ba63d16a5f8.nq.gz
│   ├── 85815b7fab4424b1596cd409a12ac01a4728a3a4.nq.gz
│   ├── 85954156c306493cf78cf475b7a710c4656c6531.nq.gz
│   ├── 85c1dab2a4981c1afce263b74867eeee78a14211.nq.gz
│   ├── 87f95b1507994f83072eb6539c230c5db0e58422.nq.gz
│   ├── 894e70a4199ec38daa11c271d02118cf932dbf1b.nq.gz
│   ├── 8a796cec5fe622298b3664696bbb646719c2924a.nq.gz
│   ├── 8ade2d38fa9cfa433ba12cdfd13b793a43dbdea3.nq.gz
│   ├── 8b2429c1f7a431cdae19eef3defc908578cd199c.nq.gz
│   ├── 8b6de8e091ba301e06235066c3e53480cd7e358c.nq.gz
│   ├── 8b7536ed300f23a0c6bd836463ec2e08c10bccd0.nq.gz
│   ├── 8c4cdf73333c100f8eb26ada5f2ec0a265a7f3ac.nq.gz
│   ├── 8f84209c8d1c55b74348e0b7b773d6bd9f311436.nq.gz
│   ├── 8ff7763606c3e06981a10e1e8bf5a3c4d8ab928c.nq.gz
│   ├── 90249d285b281d2ab7a987ea4ac500a0b23543e4.nq.gz
│   ├── 91921f17c850fdf8b91867ff7faceb50f810457c.nq.gz
│   ├── 92fef3fa21510168a6505e837f52862b056535a8.nq.gz
│   ├── 951b88b31c29a72681bceb3b3123390dbdba026e.nq.gz
│   ├── 9a058e9b1a4679978bbf9f976800609284a61b06.nq.gz
│   ├── 9c214569a442b0ad816bdf4fc0f88f7baa718de0.nq.gz
│   ├── 9e563d0ed9b8a57a6f34ff1764d4497b5565563f.nq.gz
│   ├── a225f878fef68fd78637ef0b64b082d26889640f.nq.gz
│   ├── a273c2d53135c3fac1beb26be1783eb76c67f62a.nq.gz
│   ├── a324ae929568141868ca0a871b55a5ae6b0207e7.nq.gz
│   ├── a3911204ca994439dead59b910fb0c60f19bb646.nq.gz
│   ├── a3f1f6073e6e5a7e85e393d50b6fe1652d853525.nq.gz
│   ├── a4d8ec3b3aac340cfbce7324ecfcf69bf9cd5896.nq.gz
│   ├── a6d3db0074fff06091b48ee4dc8f96b60895cee1.nq.gz
│   ├── a773a85b4fc317be0b7b6ef0dcdabc85e787f8e7.nq.gz
│   ├── a9823f65196fa07b4ddbcf5cefbc15a066a24fd3.nq.gz
│   ├── a9dc5f87127d7b67410a86e881166d8b4cfc20e0.nq.gz
│   ├── abc4f90c265056a83a398e8bb9cf6860d375fdae.nq.gz
│   ├── ad163bb9b6eba31f3b34bd18029286797802a67f.nq.gz
│   ├── ada7da3ba01c0eca7608fe175ca8d81d3a41ea39.nq.gz
│   ├── b0b429f8999796d838ce5b5212dc27b8f4e11327.nq.gz
│   ├── b112851dc40405cf5828281b7d081a166b49905e.nq.gz
│   ├── b1ef96538fcfe276e35e9942350fa242019332e2.nq.gz
│   ├── b20be0c839dff680c8e499289cf4ffff6aa3c067.nq.gz
│   ├── b373830946b09c0b208cdcef91d521f4b8839165.nq.gz
│   ├── b45f342f2a15d45342ded0d14d0d83189c506d2b.nq.gz
│   ├── b4e2df6389266f06af51ef1046102566424e6886.nq.gz
│   ├── b56247db45ccd51397d07a46b9eb18a9748a5836.nq.gz
│   ├── b7d80ea4781f44d6ea78f3717dd30bb11d2c5eae.nq.gz
│   ├── be33fd23c39c42c6c7b9ee8e68b0ba24fe7504b3.nq.gz
│   ├── be490534c9cf84ef88123ebda3d2d378a73f82fc.nq.gz
│   ├── bf893a07fd1dc90713df78a45786d336f82c9106.nq.gz
│   ├── c1bf5a8ad740a8e3ca20e6c263813b8762a744bc.nq.gz
│   ├── c212f5136fa514557bfed10f51af8782891fd4a4.nq.gz
│   ├── c25c6037ce2a45ebde6445710a026200e7aeebfa.nq.gz
│   ├── c553f3bbd93442eb2ab4cd945ab40985b49ab268.nq.gz
│   ├── c5914084e6c6e1ca110adae12f53735a908d2454.nq.gz
│   ├── c5cd98f1fe141d0db5293d58b15101f88dea6e25.nq.gz
│   ├── c90002fed61e25f70a19cc2f437fe6c8305c66e8.nq.gz
│   ├── ca36e0906aae3330a77902cb26a91aec661396d5.nq.gz
│   ├── cd3a0da0e917a46e784940f5e288cc2de685b657.nq.gz
│   ├── cddcf6f294b4741cfc256c96e644512cc44b9c73.nq.gz
│   ├── ceaf4654d94ae2976eedd91ee76afd430262dc00.nq.gz
│   ├── cee111f6fef4ddd389cd363db2916a94179f9c89.nq.gz
│   ├── cf722dbc58a0ecda1e7ec3f9bd72409b1599701c.nq.gz
│   ├── d17c4cfe8e1c498618f8dc939b471cff9f94ad85.nq.gz
│   ├── d21b6b637c8a1968a8df1ab3989ed51922692613.nq.gz
│   ├── d5b99db73f9f21ce88de367a0b54d0fadc78e2ce.nq.gz
│   ├── d61c8f65e0d760b4d345a91d4f2721e78aff99f7.nq.gz
│   ├── d9b4570938c884863d347be8f82ee17be5e9bf97.nq.gz
│   ├── da9c0cccdf652eebbeb8493780f4ea90e7f2cf94.nq.gz
│   ├── dadb254aa00910a01f7b50a044bf989abeee9e56.nq.gz
│   ├── de35106ee4420c0ab74f399d1b0734b83d740b61.nq.gz
│   ├── df70bd3e01a22c4a7e13c04cc22e8c037c8d9ac8.nq.gz
│   ├── e0a0e0701ee08b80346b377b2dd38f4df130d5f2.nq.gz
│   ├── e30996d7238bf1dadeb72656a8407c0aa8767363.nq.gz
│   ├── e720707964879597493be01d17e57eb0d947d3e7.nq.gz
│   ├── e8784aac8d082ae6508569c9c811f2a2d726f83a.nq.gz
│   ├── e89edf89addb61367261b8081a26bf29dd191c84.nq.gz
│   ├── ea198081769463a8579944290ce2293bc41a5a56.nq.gz
│   ├── ea76f3b76e604813a7276a45f34072183876c275.nq.gz
│   ├── eb6904321b9b69c880093231e4de9ad64be8d626.nq.gz
│   ├── ee76a646efa8211a9fa5f0a52e384f99595f6823.nq.gz
│   ├── eec88dfa62642f6282bf157c0f3dd7d251de0294.nq.gz
│   ├── ef929b78dce6d9f9dd8b971ee14e6e4212fe5f07.nq.gz
│   ├── f22d74afcffaff4d2025d86a1a7267e03d1e96b7.nq.gz
│   ├── f2ef36331826c395c667b085d9bacec2a11590dc.nq.gz
│   ├── f31a67da4229c6813e4a19cf1e9e57a5fb9cc259.nq.gz
│   ├── f3705c5c63d0c6ac144e762101098ba991fec69b.nq.gz
│   ├── f57a90f289c73c58c924af38842a95b551336e5e.nq.gz
│   ├── f969d7c3866be6f3dcc1f60a4a0d7002d8c63e7e.nq.gz
│   ├── f979f74761807681c10110add757d0cfb4e1af1d.nq.gz
│   ├── f9c8d1c9d29d921939abe33b5f655119d5b8ea3f.nq.gz
│   ├── fa549107b48bcfc5074386f6fc293dc2dbda02fe.nq.gz
│   ├── fd25d425bf93833b61ce0571cd9b237486dabb4c.nq.gz
│   ├── fda0ff7d7c540d9f9dc8445e2a1ff9c478cfbb2f.nq.gz
│   ├── fe445d8a6bb47a600f0011394d87a4b6f1d2ae25.nq.gz
│   └── ff83828afebe771071afae1c769414a1b98593a9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5cf470dcbdd393521503955af67fd2e02aceb75d.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 192 files
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

[pydantic/provider-upjet-logfire](https://github.com/pydantic/provider-upjet-logfire)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
