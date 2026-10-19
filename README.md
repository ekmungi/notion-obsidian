# Notion Obsidian

Notion Obsidian is an Obsidian theme that makes notes look and read like Notion. It is a fork of
[Obsidianotion](https://github.com/diegoeis/obsidianotion) by Diego Eis.

## What it changes from Obsidianotion

- Table text is the same size as body text.
- The light and dark colour palettes are closer to Notion's.
- Heading sizes follow Notion's proportions.
- Tables from the database-views plugin are styled to match.
- Typography and spacing are refined throughout.

## Install

1. Create a folder named `Notion Obsidian` inside your vault's `.obsidian/themes/` folder.
2. Copy `theme.css` and `manifest.json` into it.
3. In Obsidian, open **Settings → Appearance → Themes** and select **Notion Obsidian**.

The fonts are built into `theme.css`, so they display on any computer without being installed
separately. Obsidian Sync copies the theme to your other devices with the fonts included.

## Settings

The theme works with the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings)
plugin. With the plugin installed, open **Settings → Style Settings → Notion Obsidian visual
control settings** to change the body width, the body font, the interface font size, heading
sizes and several layout toggles.

The defaults are a 1280px body width, Fira Sans as the body font, a 0.825rem interface font, and
headings at 1.8, 1.4, 1.3 and 1.2rem for H1 to H4.

## Credits and licences

- The theme is based on Obsidianotion by Diego Eis, which is released under the Unlicense.
- Fira Sans, Fira Code, Source Sans 3 and Nunito Sans are distributed under the SIL Open Font
  License 1.1. They are embedded in `theme.css` unmodified, and the licence text is repeated at
  the top of the embedded fonts section. The `fonts` folder holds the original font files and
  each family's licence file. The theme does not load that folder.
