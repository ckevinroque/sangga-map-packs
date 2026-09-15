# SANGGA Offline Map Packs

Large offline map archives for the SANGGA preparedness app are published here
instead of being bundled in the APK. The app downloads a selected archive,
checks its exact byte length and SHA-256 digest, validates its PMTiles header,
and installs it atomically in app-private storage.

## Philippines v1

| Archive | Coverage | Zoom | Bytes | SHA-256 |
| --- | --- | ---: | ---: | --- |
| `SANGGA-PH-nationwide-street-v1.pmtiles` | Philippines `116.8,4.4,126.7,21.5` | 0-14 | 307117688 | `45e0363130a22e3de3f0e6263834975108b692bd0436a4dcce280920ee500589` |
| `SANGGA-PH-nationwide-terrain-v1.pmtiles` | Philippines `116.8,4.4,126.7,21.5` | 0-12 | 586727065 | `b273d14a0e5e2cfcea7643fa7c2e7ce32ef52f2d26f6cb1e4714793b276ecc9e` |

The street archive is a Protomaps Basemap derived from OpenStreetMap and
Natural Earth. Map data is © OpenStreetMap contributors and is distributed as
an ODbL Produced Work. The SANGGA map displays the required attribution.

The terrain archive is a Philippines extract of Mapterhorn's Terrarium-encoded
terrain archive. SANGGA displays © Mapterhorn attribution. Mapterhorn's source
catalog and individual source licenses are available at
https://mapterhorn.com/attribution/.

The PMTiles format is documented at https://docs.protomaps.com/pmtiles/.
