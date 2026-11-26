# Jugend

A dark **Jugendstil / Art Nouveau** desktop theme for [Omarchy 4 (Quattro)](https://github.com/basecamp/omarchy). Warm black and olive surfaces with gilded accents; ornament lives on the wallpaper and lock/preview imagery while Hyprland window chrome stays calm.

![Jugend theme preview](preview.png)

## Install

```bash
omarchy theme install https://github.com/mauricewipf/omarchy-jugend-theme
```

Then open **Style → Theme** in the Omarchy menu and select **Jugend**.

## Palette

| Role | Color |
|------|-------|
| Accent (gold) | `#c9a84c` |
| Background | `#1c1812` |
| Foreground (ivory) | `#e6d7bf` |
| Selection | `#3a3228` |
| Muted | `#6a5e4e` |

The full palette, including ANSI `color0`–`color15`, lives in [`colors.toml`](colors.toml). Hyprland active borders use a subtle gold-to-teal gradient derived from the accent and blue stops.

## Contents

This repo is the theme directory itself (Omarchy clones it into `~/.config/omarchy/themes/`). It ships:

- `colors.toml` — source of truth for the palette
- `shell.*.toml` — gold lock, bar, menu, and launcher accents
- `keyboard.rgb` — gold keyboard backlight
- `icons.theme` — `Yaru-olive` for warm olive file icons
- `backgrounds/` — seven official wallpapers (Omarchy picks the first sorted file as the default and cycles through the folder):
  - `fruehlingsstrasse-jugendstadt.png` — **default**; bustling spring street in a c. 1900 Jugendstil town
  - `kaffeehaus-unter-kastanien.png` — twilight corner coffeehouse under blooming horse chestnuts
  - `lesesaal-zur-abendstunde.png` — quiet walnut reading room with curved gallery and brass table lamps
  - `lilienrahmen-mit-pfauenfedern.png` — full border frame with gilded lilies and peacock feathers over faint lily damask
  - `nachtfalter-im-silberblatt.png` — emperor moth and silver honesty seed pods on warm black ground
  - `palmenhaus-bei-mondlicht.png` — moonlit glass-and-iron botanical conservatory reflected in a park basin
  - `stadtbahnpavillon-nach-dem-regen.png` — glowing Jugendstil Stadtbahn pavilion after evening rain
- `unlock.png` / `preview-unlock.png` — gilded Omarchy Plymouth boot logo and boot switcher preview
- `preview.png` — theme switcher preview (`Style → Theme`)

Terminal configs, Lua, and `vscode.json` are intentionally omitted so Omarchy generates them from templates at install time.

## License

MIT — see [LICENSE](LICENSE).
