# my obsidian snippets

English | [日本語](README.ja.md)

A set of CSS snippets that sit on top of Obsidian's default theme.
They focus on readability and refine headings, tables, code blocks, the sidebar, and more.

## Screenshots

![Headings and body text](img/img.png)
![Tables and code blocks](img/img2.png)

## Installation

1. Copy the `.css` files in `snippets/` into your vault's `.obsidian/snippets/` folder
2. In Obsidian, go to Settings → Appearance → CSS snippets, reload, and enable **all** of them

Every file depends on variables defined in `00-tokens.css`, so enabling only some of them will break the layout.
The number prefixes set the load order (Obsidian loads snippets in filename order).

## Customization

- Sizes and colors can be adjusted in `00-tokens.css` alone
- The dark mode color scheme lives in `80-colors.css`
- The accent color follows Obsidian's Settings → Appearance → Accent color

## Files

| File | Contents |
| --- | --- |
| `00-tokens.css` | Variables / design tokens |
| `10-app.css` | Status bar / title bar / window frame |
| `20-components.css` | Modals / progress bars / tooltips |
| `30-content.css` | Headings / lists / links / code / quotes / callouts / tables |
| `40-layout.css` | Page width / spacing / embeds |
| `50-extras.css` | Helper classes / image handling |
| `60-interface.css` | Sidebar / tabs / search / settings / scrollbars |
| `70-plugins.css` | Core plugins (Canvas, etc.) |
| `80-colors.css` | Color scheme |

`markdown-stype-guide.md` is a sample note for checking the styles. Drop it into your vault to preview how everything looks.

## License

MIT
