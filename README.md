# Light Hill map data

Machine-readable map data used by **Light Hill | 嵐の前の帰還**, a fictional park exploration game.

**Map data © OpenStreetMap contributors, available under the Open Database License (ODbL) 1.0.**

- [Download the complete data package](LightHill-map-data-2026-10-04.zip)
- [ODbL 1.0 license text](LICENSE-ODbL-1.0.txt)
- [Attribution and source notices](ATTRIBUTION.txt)
- [OpenStreetMap copyright information](https://www.openstreetmap.org/copyright)

The ZIP contains the original OSM extraction, the current edited map database, coordinate-conversion documentation, and additional spatial data tables. It is freely downloadable without a Roblox account. ODbL rights apply to the OSM-derived database; no Roblox-only reuse restriction is added here.

## Contents and verification

Snapshot: 2026-10-04. Four map strings were compared with the saved Roblox Studio place. All 16 place coordinates and five spatial configuration tables were extracted directly from the same snapshot.

| Data | Count |
| --- | ---: |
| Paths | 73 |
| Areas | 49 |
| Building footprints | 27 |
| Named places | 16 |
| Sampled paved-path nodes | 1,638 |

`ParkMapData.json` and `latest-strings/` contain the edited map. `spatial-configs/` contains gate, toilet, shelter, gameplay-location and sampled-path tables in Lua notation. `COORDINATES.json` documents the local metre system, origin and Roblox conversion. `MANIFEST.json` contains file hashes. Original OSM extracts retain their provenance.

This is a **fictional, modified game map**, not an official or surveyed park map. Gate geometry and added toilet footprints include approximations. See the included toilet-map audit. The project is not endorsed by a park operator, municipality, OpenStreetMap Foundation or Geospatial Information Authority of Japan.

This repository distributes map data and associated notices only. It does not distribute the complete game, independent gameplay code, UI, music, or independent GSI terrain/imagery/vegetation data. Their rights are separate.

## 日本語

ライトヒル公園で使用する、OpenStreetMap由来の編集済み地図データの配布先です。上のZIPから無料で取得できます。道路・区域・建物・移動先・追加の配置設定を収録し、元の地図データと利用条件も同梱しています。地図データはODbL 1.0に従って利用できます。実在の公園の公式地図ではありません。
