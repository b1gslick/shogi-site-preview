# Supplied figure sources

From `фигуры.zip`, supplied on 2026-10-21. SVG/PNG contents are unchanged here;
`python3 scripts/build-piece-assets.py` normalizes the generated artwork to the
site orange. `*-map.svg` supplies glyphs and rays, while the grids remain CSS.

Original generic filenames mapped by their actual glyphs:

| Site name | Archive filename |
| --- | --- |
| king | Новый.svg |
| gold | Новый-2.svg |
| dragon | Новый-3.svg |
| rook | Новый-4.svg |
| bishop | Новый-5.svg |
| horse | Новый-6.svg |
| promoted-silver | Новый-7.svg |
| promoted-knight | Новый-8.svg |
| lance | Новый-9.svg |
| promoted-lance | Новый-10.svg |
| pawn | Новый-11.svg |
| promoted-pawn | Новый-12.svg |
| knight | Новый-2.png |
| silver | Новый.png |

King and dragon movement maps are absent from the archive; the horse map is
only PNG. Their existing Figma vectors are retained instead of redrawing glyphs.
The redundant lance PNG is not used because the archive also contains its SVG.
`promotion-board.svg` is the supplied `Board and Move Paths.svg`.
`promotion-cases.svg` is the unchanged `DiagramThreePromotionCases.svg`, supplied
separately from Telegram Desktop. Its generated version replaces the complete
promotion illustration, including the three numbered cases and labels.
