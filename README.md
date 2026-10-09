# Gruvbox Dark for Actual Budget

A dark custom theme for [Actual Budget](https://actualbudget.org) based on the [Gruvbox](https://github.com/morhetz/gruvbox) color palette by Pavel Pertsev.

The classic retro-groove dark scheme — warm backgrounds, high contrast, yellow accents.

## Installation

### From the catalog

Settings → **Theme** → **Custom theme**, then choose **Gruvbox Dark** from the catalog. Custom themes no longer require an experimental feature flag.

### Manual

1. Copy the contents of [`actual.css`](./actual.css).
2. Open Settings → **Theme** → **Custom theme**.
3. Paste the CSS into **Custom theme CSS** and select **Apply**.
4. When updating an existing override, use the **Custom CSS is active** button to reopen the editor.

## Palette

| Role         | Color     |
|--------------|-----------|
| Background   | `#282828` |
| Foreground   | `#ebdbb2` |
| Accent       | `#fabd2f` |
| Yellow       | `#d79921` |
| Red          | `#fb8467` |
| Green        | `#b8bb26` |
| Blue         | `#93ada0` |

The theme maps all 237 current color tokens, including the redesigned sidebar, chart palettes, date ranges and alternating rows. Contrast tints are precomputed blends of Gruvbox colors so they remain compatible with Actual’s CSS validator.

Some component colors are outside the custom-theme variables, including syntax highlighting and generated chart labels. Active formula toggles reuse a primary background with bare-button text; one variable palette cannot make every conflicting use accessible. These limits need a separate upstream component change.

## Credits

- Palette: [Gruvbox](https://github.com/morhetz/gruvbox) by [Pavel Pertsev](https://github.com/morhetz) (MIT)
- CSS mapping: [Dakyne](https://github.com/Dakyne)

See also: [Gruvbox Light for Actual Budget](https://github.com/Dakyne/gruvbox-light-actualbudget).

## License

MIT — see [LICENSE](./LICENSE).
