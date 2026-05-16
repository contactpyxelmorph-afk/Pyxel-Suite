# Pyxel GB Studio Suite

Pyxel GB Studio Suite is a single-file offline HTML toolkit for optimizing images, sprites, palettes, text, and GBVM helper data for GB Studio projects.

It combines several older Pyxel tools into one tabbed dashboard:

- **Pyxel Morph**: background image palette quantization for GB Studio’s 4-colors-per-8x8-tile workflow, with recolor output, green preview, palette JSON, tile map, and GB Studio plugin C export.
- **SpriteBingo**: sprite palette optimizer for GB Studio’s 8x16 sprite tiles, 3 opaque colors per tile, transparent green handling, remix generation, restoration tools, green preview, palette legend, tile map, and plugin C export.
- **Pyxel Matrix**: quick matrix editor for generating optimized GBVM `VM_SWITCH` code.
- **Pyxel Text**: browser-based `.gbsres` dialogue/menu/choice text editor with ZIP export.
- **Pyxel Tile**: background tile reduction tool for reducing repeated/near-repeated tiles.
- **Pyxel Clear**: palette reuse workflow for reusing existing palette libraries and exporting recolor/green-preview assets.
- **Pyxel Palette**: quick palette sheet generator from connected image regions.

## Usage

Open `pyxel_suite.html` in a browser.

No install, server, account, login, or backend is required. The app is designed to run locally and offline as a self-contained HTML file.

## Notes

This suite keeps the original GB Studio constraints at the center of the workflow:

- Background tiles use 8x8 tile logic.
- Sprite tools use 8x16 sprite tile logic.
- Sprite palettes respect 3 visible colors plus transparency.
- Green previews are generated to match GB Studio palette slot expectations.
- Exports are blocked or warned when a result would violate important color/tile limits.

## Included Tools

### Pyxel Morph

Use this for GB Studio background palette optimization. It supports exact and complex workflows, priority colors, dithering, recolor previews, GB green previews, palette JSON export, tile maps, and plugin C export.

### SpriteBingo

Use this for GB Studio sprite palette optimization. It supports color pool and strict palette modes, remix generation, deep restoration, transparent green handling, green preview export, palette legend export, tile map export, and plugin C export.

### Pyxel Matrix

Create grid-based mappings and generate compact GBVM switch code.

### Pyxel Text

Load GB Studio `.gbsres` files, edit dialogue/menu/choice text, and export modified files as a ZIP.

### Pyxel Tile

Reduce background tile usage by substituting or merging similar tiles, with optional sky sacrifice behavior.

### Pyxel Clear

Reuse palettes from existing palette JSON files, generate recolored output, palette data, green previews, atlases, and GBVM helper output.

### Pyxel Palette

Generate palette JSON files and preview images from connected image regions.

## License

MIT License.

IMPORTANT NOTE: the app was vibe-coded
