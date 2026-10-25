# TetraPalm — Credits and licenses

TetraPalm was conceived and built from 1 October 2026 for the Meta VR Start Developer Competition 2026.
Game design, code, rules, 3D restaurant, menu lectern, tutorial glove, chalkboards, palette and audio are original work made for this project, unless listed below.

## Third-party assets shipped with the game

| Asset | Where | Author / source | License |
|---|---|---|---|
| Nature Kit 2.1 (`tree_default`, `tree_oak`, `tree_default_fall`, `rock_largeA`) | `public/environment/kenney/` | Kenney — https://kenney.nl/assets/nature-kit | CC0 1.0 (copy in `public/environment/kenney/License.txt`) |
| Painted Wooden Chair 01 (1k) | Restaurant chairs, source in `art/imports/painted_wooden_chair_01_1k/` | Kuutti Siitonen, Poly Haven — https://polyhaven.com/a/painted_wooden_chair_01 | CC0 1.0 |
| Inter (Blender's built-in font), converted to 3D lettering geometry | Menu lectern, tutorial chalkboard, table cards, restaurant sign | Rasmus Andersson, bundled with Blender | SIL Open Font License 1.1 |

## Software

| Package | License |
|---|---|
| Meta Immersive Web SDK (`@iwsdk/core`, `@iwsdk/vite-plugin-dev` and its `@iwsdk/*` packages) 1.0.1 | MIT |
| three.js 0.181 | MIT |
| Havok Physics for the web (`@babylonjs/havok`, via IWSDK) | MIT |
| `@pmndrs/uikit`, `@pmndrs/pointer-events`, `@pmndrs/handle` (via IWSDK) | MIT |
| `three-mesh-bvh`, `elics`, `@preact/signals-core` (via IWSDK) | MIT |
| UI fonts bundled by `@pmndrs/uikit` (Inter, Roboto, etc.) | SIL Open Font License 1.1 |
| Vite, TypeScript (build only) | MIT / Apache-2.0 |

## Made with

- Blender 5.2 LTS (modeling and glTF export; scripts in `scripts/*-blender.py`).
- Victory fanfare `public/audio/victory.wav`: synthesized by `scripts/make-victory-music.py`, no samples or third-party music.
- Menu waltz (original valse musette): composed for TetraPalm and played live with the Web Audio API (`src/audio.ts`), no samples or third-party music.

No identifiable people, brands, logos or AI-generated video are used in the game.
