# Asset stockroom

## Structure

`assets/packs/<pack-name>/` holds each pack intact as downloaded except that non-glTF format exports (FBX/OBJ/MTL and Unity variants) were removed, along with the Windows/shortcut artifacts described below. Licenses and supporting files are retained.

`packs/` is the stockroom. A lean curated game-assets folder will be added later when the vertical slice picks its models; the curated folder is what loads in the game.

## Packs

All seven packs are CC0 1.0 / public domain. Counts are tracked `.gltf`/`.glb` files in this repository, not upstream advertised model totals.

| Pack | Creator | Official source | License | Contents | glTF/GLB files |
| --- | --- | --- | --- | --- | ---: |
| `kenney-mini-characters` | Kenney | [Pack page](https://kenney.nl/assets/mini-characters) | CC0 1.0 | Animated mini characters and accessories | 43 |
| `kenney-mini-dungeon` | Kenney | [Pack page](https://kenney.nl/assets/mini-dungeon) | CC0 1.0 | Dungeon characters, weapons, shields and objects | 30 |
| `quaternius-fantasy-props` | Quaternius | [Pack page](https://quaternius.com/packs/fantasypropsmegakit.html) | CC0 1.0 | Medieval fantasy props, weapons and tools | 94 |
| `quaternius-medieval-village` | Quaternius | [Pack page](https://quaternius.com/packs/medievalvillagemegakit.html) | CC0 1.0 | Modular village walls, floors, roofs, stairs, doors and windows | 176 |
| `quaternius-stylized-nature` | Quaternius | [Pack page](https://quaternius.com/packs/stylizednaturemegakit.html) | CC0 1.0 | Stylized nature environment models | 68 |
| `quaternius-ultimate-monsters` | Quaternius | [Pack page](https://quaternius.com/packs/ultimatemonsters.html) | CC0 1.0 | Fully animated monsters | 50 |
| `quaternius-universal-base-characters` | Quaternius | [Pack page](https://quaternius.com/packs/universalbasecharacters.html) | CC0 1.0 | Humanoid base characters and hairstyles | 18 |

**Total: 479 glTF/GLB files.**

## Art direction

Assets were chosen for geometry over color. The pack textures are bright/cheerful and will be replaced with generated dark textures for the game's aesthetic.

## Cleanup

FBX/OBJ/MTL and Unity format exports were removed because they are unused: the engine loads glTF. `desktop.ini` and `.url` Windows/shortcut artifacts were also removed to keep the repository clean. Kenney `Overview.html` catalogs are retained.

## License note

`quaternius-ultimate-monsters/License.txt` has a header reading "Ultimate Platformer Pack" — an upstream copy-paste error. The license text itself is CC0 1.0 Universal (CC0 1.0), Public Domain Dedication. Keep the original license files with their packs.
