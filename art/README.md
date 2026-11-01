# Peerora logo

The logo is Peer Link: two identical peers joined by one unbroken ribbon.
The SVG files are the source. The PNG files are exports.

## Files

| File | Use |
| --- | --- |
| `peerora-mark.svg` | The main mark, in a 7:1 shape |
| `peerora-mark-mono.svg` | The mark in one ink |
| `peerora-mark-small.svg` | The mark drawn for a 16 px size |
| `peerora-app-foreground.svg` | The compact mark for a square tile |
| `peerora-app-icon.svg` | The compact mark on the navy tile |
| `peerora-lockup-dark.svg`, `peerora-lockup-light.svg` | The mark beside the wordmark |
| `peerora-lockup-stacked-dark.svg`, `peerora-lockup-stacked-light.svg` | The mark above the wordmark |
| `peerora-feature-graphic.png`, `peerora-feature-graphic-light.png` | The README header |

Each lockup has a transparent background. "Dark" and "light" name the background that the lockup is for.
The wordmark in each lockup is outlines, so no lockup needs an installed font.

## Rules

- Keep both peers identical in size, colour and weight.
- Use the long mark in lockups. Use the compact mark inside a square tile.
- Do not add a ring, halo, arrow, cloud, Wi-Fi fan, glow, particles or a centre node.
- Keep clear space around the logo equal to one peer diameter.
- Set the wordmark in Quicksand Regular. Do not use a font with a double-storey `a`.

## Rebuild the feature graphic

Run this command from the repository root. It needs Google Chrome.

```bash
art/feature-graphic/render.sh dark
```

Replace `dark` with `light` for the light variant.

## Fonts

`fonts/quicksand-variable.ttf` is the wordmark font. The SIL Open Font License 1.1 covers it, and `fonts/OFL-Quicksand.txt` holds the license text.
`feature-graphic/fonts/README.md` lists the fonts of the feature graphic.
