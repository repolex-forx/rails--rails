# Repolex Knowledge Graph of rails/rails

RDF knowledge graph data for [rails/rails](https://github.com/rails/rails), parsed by [repolex](https://repolex.ai).

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
rlex download rails/rails
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 126d0d64d529d4c55d34d6f38e8c7ca3366923ea
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 126d0d64d529d4c55d34d6f38e8c7ca3366923ea
│           └── chunk-001.nq.gz
└── blob
    ├── 00379af23c28d07ebdd20538cb524ec06104ebb7.nq.gz
    ├── 004d1d878c0595d2d075216f20fdf32029ef3dd4.nq.gz
    ├── 008aca3fb59e41a2ff3fb59e84ebe43d46fd19e4.nq.gz
    ├── 0179b070b8a653c36a1c0628fdd1d01f181c5a68.nq.gz
    ├── 023abc64f7a2a8a27bae59d2ab8c12aa58455672.nq.gz
    ├── 02f0c6c103b564737cd474eb009cc7b38168d959.nq.gz
    ├── 036850194c81cc3424bfc217097e414236cb8469.nq.gz
    ├── 03adf71701daec0d86eca1e859a8b323a76c77a4.nq.gz
    ├── 0479cc958bb98aea13f4bed7128d6294ffcf7045.nq.gz
    ├── 047fc057a041a703471b64b87633983b482a6b70.nq.gz
    ├── 0533a3b2fee2503d207d1b33f2464223cbf282a1.nq.gz
    ├── 06055eb947d4c7b48172be55c40bb6163c0f69fc.nq.gz
    ├── 061eefd7acf70b0a89ff386511a18964476f231b.nq.gz
    ├── 06296de2128da719ab173f211fc738ad71040fc3.nq.gz
    ├── 063e726152e31d995e2b07451e4330cc01bf4f6f.nq.gz
    ├── 080c9c0aeedc3fe87e33cfe284cac968e8e1891a.nq.gz
    ├── 08407f4620bde9b9a745b9a1de20d67e49748071.nq.gz
    ├── 099e7e38e0fa5747e09a64c96be2a87808ef9289.nq.gz
    ├── 0a0403f469383afd9833be70222c51746887d6cc.nq.gz
    ├── 0a7af8da1cd9130a0970ed1a88eca92876109e5e.nq.gz
    ├── 0abdfea340bcc43c3ff04f3f73589f2d30efa2df.nq.gz
    ├── 0ae1181be17dd13faba0e9fbfb11ee631bc66881.nq.gz
    ├── 0b2772596d76f6ab78576924d3525ecab4a75642.nq.gz
    ├── 0c3a976f8f78bd65b4c43ead90694f93e47d963c.nq.gz
    ├── 0ca08292bbe27c1b2853f33c9cf7c35a2e2162da.nq.gz
    ├── 0ca3fd70320cbb54813b16be28d938883fe2a2e9.nq.gz
    ├── 0cdfa41494c9e1d49c061a350ee65ad57bb5ea73.nq.gz
    ├── 0d4b022548995b6f03fbaf97e04fcf470de0d037.nq.gz
    ├── 0d64d9d9c7a410778c025c6d2f125309e6419d3d.nq.gz
    ├── 0df1ec161df28955b8225151aeee51814296c632.nq.gz
    ├── 0e271d482bc79cad0942466498eec04b0a3e96ba.nq.gz
    ├── 0e4f6651084d3f9562e0e446f8e05258e722d1ce.nq.gz
    ├── 0e555e9809dc453665a992d023ba377f5d4b6e29.nq.gz
    ├── 0e69842c90df0c7bd7f2bb19ae63ceb9ae33e5b6.nq.gz
    ├── 0e69d001b59172b5fece4e8bb2c2227526fa07ad.nq.gz
    ├── 0ef65865ef21d8d5db1126c7026aebd518b0ebef.nq.gz
    ├── 1023c079fc64b344f09fc43e80ad3ada4c989ca6.nq.gz
    ├── 1290c90613c750be936d3e6f9692e1577d62b950.nq.gz
    ├── 12f68c67e4525a9fc8434a7d3204bf4ae560a302.nq.gz
    ├── 13db899bf4aad9aacb0f55c330466ac09f3242c5.nq.gz
    ├── 14a0594cd525ea417b32ea8094a6b04c2d6da6d0.nq.gz
    ├── 15413317b8dd2d0c97497f8275b1fa69f344aea3.nq.gz
    ├── 1586f3d022fb60777048ecf239cb073187ec758f.nq.gz
    ├── 15871d82087919d4d3b903080c2226d84c9a405d.nq.gz
    ├── 15c1a742c6c7f47d0a82a2f1984f43a6f6849cdc.nq.gz
    ├── 15fe4a7f27968f73e0025fa5ac256ec7413a93c8.nq.gz
    ├── 168076289fd064135f028951be11f29443e2de60.nq.gz
    ├── 16a453ca12db696517828ed2f05dc26bfc3cab77.nq.gz
    ├── 1709ab5f6d34ab5e7c66bea9d4ed06439241a878.nq.gz
    ├── 17b7dff454d42f3340e72151990d413bae02f1e9.nq.gz
    ├── 17c2c83b35afe597bb09eef8fa9249b6cbd3eaea.nq.gz
    ├── 17f21cbbc53ccac0419b8b52d46d835f448d4f54.nq.gz
    ├── 182a1aea51ac56d7cf64f685c97f6ae52caa0f99.nq.gz
    ├── 187bbd3fca2589e736c3d109ddafdd2876b0bbde.nq.gz
    ├── 188cb5a4d26104d5a9c3c0d7fa200a25987fb704.nq.gz
    ├── 196f229d10595f54ca0816b3cf3bba0ee720d182.nq.gz
    ├── 19b241f08e6a9c4ed8326401836aa10a3394fbee.nq.gz
    ├── 1addaa40d93056105aacb3be90544bcb5a432e3a.nq.gz
    ├── 1aeb81fcbae970ff91db505e06d656e025ed5c7c.nq.gz
    ├── 1c536f3cc0048a7204fa4f289f757dfb9062914b.nq.gz
    ├── 1cae44cb322854ac8989b088dc55b982e494e670.nq.gz
    ├── 1cc8d41475fe1186e8c3929fbb1c67ff78597217.nq.gz
    ├── 1e4e60dd209bf0f654ab080ac4bc5806e2454894.nq.gz
    ├── 1f48bb16e8f20334d4211a1948ec9d75a5bf4c82.nq.gz
    ├── 20e8c0c8ecb0acc5696a045f445702a465b83a1a.nq.gz
    ├── 2359f1314860bff05375014143dca60ce7043ee4.nq.gz
    ├── 23745cd282cf82a4d8fdb414f39c8fc7286f2b5c.nq.gz
    ├── 2375b361e207f37027ad7ec5b6aedd23f486ae69.nq.gz
    ├── 239ca3afafea8d12946f858b223b453fca6f1e96.nq.gz
    ├── 243bb6a439be7920c15c5ed49f11e38a1418303e.nq.gz
    ├── 246d94ffaa220b1d5461cdd3fdf09ae6ea136164.nq.gz
    ├── 2475d4a34b860faf380e18377855bf72d12105ac.nq.gz
    ├── 24a4206119e86f92ac02353ed987c8fe059a651e.nq.gz
    ├── 24bb75002b6dd1eba917a1ee6fca55de4624310d.nq.gz
    ├── 253473da013f73a74d89dc21b325eb06493bc00b.nq.gz
    ├── 25874365fdd49c02afc9431fc37e0662ff62457f.nq.gz
    ├── 25dc746886c84049487c57a1c095fcabbe72cbe1.nq.gz
    ├── 25ffc66d04c4daf63205815c66845503831854f9.nq.gz
    ├── 26ede1a64e48dd424a59884f6ac489ce65c948f4.nq.gz
    ├── 277cc8ff8e0e22a7b2c2628a417442f681ca761d.nq.gz
    ├── 27e4cf4749f1490d8a0d71cf73d76dcefefddb37.nq.gz
    ├── 285d4ac2bef5646808f169fcc5ed44dc8cbc1c04.nq.gz
    ├── 28a0438b82b5e53810fede05f337758e0e1aaf62.nq.gz
    ├── 290a9c91f0d1e2035ceb8ddfe95baee21f5d80ee.nq.gz
    ├── 2b0136ff2224a5823c3629194e8b94df66e02933.nq.gz
    ├── 2b0763ba106a98184127ee23d238934e56bc5382.nq.gz
    ├── 2c086e451f9e0a2ea2a9f748b67354e5b685bab4.nq.gz
    ├── 2d69fdb5122ef692e6ab2761c06a64c56cacab0b.nq.gz
    ├── 2e2c825acb7be20ade0187104afb2a3c919cd6b4.nq.gz
    ├── 2e2e9384ccfb561f75b4c5d6ca5c1009f8b8dc3a.nq.gz
    ├── 2ec7d11a2fa074806e41ee92a4278d50c442a9d5.nq.gz
    ├── 2efa4bc42bf62726ffd520cb1d00dfb320cd0a07.nq.gz
    ├── 308fc1416826a2b74f5d849515f9d427b8319d5e.nq.gz
    ├── 31029a7dd3f83eaf550a096cbcf9a1815e2bd4c5.nq.gz
    ├── 31559bffc70bd340f4a4399b653b25b8f7621cb9.nq.gz
    ├── 31ea4b987e0ad2a1b80af1959b698551a15038f6.nq.gz
    ├── 335e6a1fa281bd8b0501cc8e6a57c596fb651dd3.nq.gz
    ├── 33b628441f0a4a7d97cd6d444d0518179a07e21f.nq.gz
    ├── 34600ac30e4a2a17be5858a1e6834b217c7b7d02.nq.gz
    ├── 3460fec5a11aa9252b02d7bddc143436bd8bc01d.nq.gz
    ├── 347e7f4c09849fe068a54570680910cea68dd4c4.nq.gz
    ├── 361e63a3fdbb2136aab45f4416097f3c0b9bc812.nq.gz
    ├── 37015afd29900c3098ab5a86e9795404c53693f0.nq.gz
    ├── 371fc2af691194a8387c0d631ea4f65a5d5eea73.nq.gz
    ├── 3784cb08443d05b4c01febf5339b371b53702284.nq.gz
    ├── 3810158fcedf47f172dfe9d21badb3cf696b47d7.nq.gz
    ├── 38b8c86938fac9bfb998f0fb12abc160869409a6.nq.gz
    ├── 38bf0ad3d2839fc47c7ead6669a28e9043e5b525.nq.gz
    ├── 3976c23d98575d8fc8550a252d4ec597e8c5a4e4.nq.gz
    ├── 3a1ce56001e9f10b4d972b8ebebac02251826c6c.nq.gz
    ├── 3a2714c8386f5afc042a7e9410a41b42be649ebf.nq.gz
    ├── 3a62910042278a206374d2a1d20b812fe5f4d27a.nq.gz
    ├── 3aac9002edca73300507bcd9f9589ffb36ba1faf.nq.gz
    ├── 3e308d3d86dddfb06fdad71004a5e670368cfc81.nq.gz
    ├── 3e5b2e41a7ed154eff4b5f834e6f1896f335d5a2.nq.gz
    ├── 3f7fb0a604a293bf2bc2bed2fdfcc5e4f60026a1.nq.gz
    ├── 4017a848f2bfe5063f8d7e67aa3d00d516dcd294.nq.gz
    ├── 4089cf6019c80d40dcc80a895ba4019d5cdc2e87.nq.gz
    ├── 40c72ed9b77d591e8ee81fc068556831618cde8c.nq.gz
    ├── 40d007f024f7879ee5dd2ee316486da6126edbe2.nq.gz
    ├── 41241fe41aabb12f950755746d221644ee0d3d29.nq.gz
    ├── 41501b7af73a9b55b8a8a624fd9efe608305f06f.nq.gz
    ├── 41fe2d782b9e6dcb654ac3f92f2e33aab447693e.nq.gz
    ├── 425ede8df268a7fd2c9f3d3faaa3d770449a1977.nq.gz
    ├── 430493d50465cbce66049ca7492b911b65cc11a6.nq.gz
    ├── 436e0ed102e2b25e2171ee8c1c6f64531d31f7dc.nq.gz
    ├── 436ffb6471cd823155faed2b2eac4f254ac55cee.nq.gz
    ├── 448c918258e86ecec8bc7baa2f3cf12caf56b511.nq.gz
    ├── 44fd359257fb1b30c732aea4deb902ac9cce3dd8.nq.gz
    ├── 461d86832d5821ddb94ea03a1054ead31073a364.nq.gz
    ├── 4663fe4bc86605f3d71ddc6dd4d7da74440395ca.nq.gz
    ├── 477f76ba0778a18e489aeb7c8ed66be60ac3edd8.nq.gz
    ├── 4789e888c624fd725884f7cd589e6f99097d4fbd.nq.gz
    ├── 487324424ff4acf9223fe9c361a0a709e86b8f18.nq.gz
    ├── 487a1e2b8418af3c93556fb9e9067903f9124fa2.nq.gz
    ├── 48882dca3589726291c0ef4f85d01a8e29485cb1.nq.gz
    ├── 4930a9d3ee6621d619f6d7286df5454e5b7491a9.nq.gz
    ├── 49686bd44a24969c5140b1fb6bbea48c8d57d4c8.nq.gz
    ├── 49df88f56cc484d6eb57c88bfbbe6fc53b26bfbe.nq.gz
    ├── 4a11845cfed5c0a8a3fe38323e5af2a66a646300.nq.gz
    ├── 4a42b079a153248e4361ef1a64f2ba4c4fa57389.nq.gz
    ├── 4a5296a71290edb75a8bdff6a11b3c9a0be920a0.nq.gz
    ├── 4a805aa79fe51b020b6bbdd6a4f9123d4f302c92.nq.gz
    ├── 4b1245a1c81febeb291e290047f0e25911cd9061.nq.gz
    ├── 4bbe59410a854d19d892bcfb1a5e4203ddbe79be.nq.gz
    ├── 4bcfb2be4dc19000ee9d2bf3da44f9016061da55.nq.gz
    ├── 4bf8a1af60e67788ed6e812330d32896e30d505b.nq.gz
    ├── 4d1650768a9960d48a0931469d12921459dc6970.nq.gz
    ├── 4d204aef5b57b9721c51a947222253db9c518af5.nq.gz
    ├── 4e036ec1058a97a4527b05522367709f7452c6e3.nq.gz
    ├── 4e85d052d7aa50df75b54798ac5da3cb0ef02d57.nq.gz
    ├── 4e904e996dc7fe9d0190209b754f7d1b955c4487.nq.gz
    ├── 4e92d0f58cb910db51bd60118b22d401dc43edd5.nq.gz
    ├── 4eaf45cb21188553644f4ae1a2fa8d64f915f20a.nq.gz
    ├── 4eb76664656fa768f7990cb5cbc394d6138f7ad1.nq.gz
    ├── 4ee54c0aaed2db4a4806208777b3072b59976bde.nq.gz
    ├── 4fa3a108fb192bb2ee2db3e3e86768f0c97d64e1.nq.gz
    ├── 4fbf10b960ef780b748861e6a616a4d88b00b50a.nq.gz
    ├── 5059b5d06940e306c1fe62d4c3a559b8f41993e3.nq.gz
    ├── 510712ea01849586911f73378a61b69fdf851e67.nq.gz
    ├── 511a78a1306bb971e9665412fc52c574869acfc4.nq.gz
    ├── 52d0483eae99b53967054bdd72e886f3d3f76a75.nq.gz
    ├── 53677197c4cfaee9cb4518979d00290efa85744c.nq.gz
    ├── 538c19ce3a5ba9f82a35d9031e72f637e4430ae9.nq.gz
    ├── 541eb98fcc813944a8860881debabd6fd7a9099a.nq.gz
    ├── 552c6c5abe79b044ff8601f230d557f0370788e5.nq.gz
    ├── 55e8216ec7c98f62ef0d7d1a76e70f0ba0081d9b.nq.gz
    ├── 561d26620d04634d77e717a49416121536e6dba8.nq.gz
    ├── 58d67eb20c0cd84e4abae85faacdd5eb2cd36e03.nq.gz
    ├── 58d94e0415c5877166fb1ce40eb0898a16f23581.nq.gz
    ├── 58dbf1e8c9dd94f7106fd2d8264005527cc9fb0c.nq.gz
    ├── 597cd2a6fb109f3e2e349fa737c9636e86e87c57.nq.gz
    ├── 5a2c893ab9a86c8405600d7229e8f82e010391fa.nq.gz
    ├── 5afb05751d1164c28af08473ee903afa9e095195.nq.gz
    ├── 5b0e639509a6daa0323605f05b14091d8e8e8e44.nq.gz
    ├── 5c8673c707fef9bc5f3e6f91a785dded46544d1b.nq.gz
    ├── 5cdaa56d6b205f6cd702a5286bf678d5f3c1c98a.nq.gz
    ├── 5d4e226267e96a9a1d80f25959f951ca9cd02d44.nq.gz
    ├── 5ee1a611ca130830d6d79bbc919f0d50c0279637.nq.gz
    ├── 5f1f0abcdf7d4ad4d106b2f05dc52f544f5153a1.nq.gz
    ├── 606ba898b765920b8f470ad5d6d91e1de36df659.nq.gz
    ├── 60f04d77d526ceb0294860551909d063127ab131.nq.gz
    ├── 61ce70d578709a39ce3e72839974c6764bef52b3.nq.gz
    ├── 620ed9784073bc8563e8f61d4b0fe19b26cbfd6f.nq.gz
    ├── 622dcd3424927f0e81cca3aad58a4de978308f33.nq.gz
    ├── 627338c76a2eb983b5b3f90ffa4982b5eedaf322.nq.gz
    ├── 62970ea4046167338bc9850ecc0a45b91984366b.nq.gz
    ├── 63143e296a109c09b83b38fd2b3de984bcc272d5.nq.gz
    ├── 631fceeaab1b089d9a42c82ca8fb73f716a81331.nq.gz
    ├── 6327c99523826f5a0a911b3014e8784fcca32463.nq.gz
    ├── 64b1bad83845bd62bedd533fa7dbb32c32417f16.nq.gz
    ├── 64dc28dd2d6f4f6fb8a088dd11983af4a5642074.nq.gz
    ├── 65ae86b4005336d6524cc8f24daa38c0e1f77016.nq.gz
    ├── 66059d82e8c5686705d62ae51e31fc7b516ef4e8.nq.gz
    ├── 666efadbb62da2ab7ee1785c7660fbd32004acf3.nq.gz
    ├── 66d1bbac5bb431519bf11cb939063fbf752f683e.nq.gz
    ├── 672edc5253324c2aff9668949825d0fd9dabb471.nq.gz
    └── 674935b49a57729182788054bb1c4c675071f492.nq.gz

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

[rails/rails](https://github.com/rails/rails)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
