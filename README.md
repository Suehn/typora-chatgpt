# Typora ChatGPT

A Typora theme that mirrors the current ChatGPT web Markdown style.

[![Typora Theme](https://img.shields.io/badge/Typora-theme-2ea44f?style=flat-square)](https://typora.io/)
[![CSS](https://img.shields.io/badge/CSS-single%20file-1572B6?style=flat-square)](./typora-chatgpt.css)
[![License: MIT](https://img.shields.io/badge/License-MIT-black?style=flat-square)](./LICENSE)

![Typora ChatGPT hero screenshot](assets/screenshots/hero.png)

Typora ChatGPT is a quiet, single-file Typora theme for people who like the official ChatGPT Markdown reading surface and want the same feel in a local editor. It focuses on the Markdown body: typography, heading rhythm, inline code, code cards, blockquotes, links, citation-style pills, task lists, footnotes, and responsive tables.

## Highlights

- Matches the current ChatGPT Markdown body rather than a generic chat-inspired palette.
- Uses the same compact system-font rhythm: 16px body text with a 26px line height.
- Recreates ChatGPT-like inline code pills and rounded code cards with tuned syntax colors.
- Keeps blockquotes, task lists, links, footnotes, and citation pills visually close to ChatGPT.
- Handles narrow Typora windows with safe side padding while preserving the desktop message column on roomy windows.
- Keeps standard tables wrapping naturally and wide tables scrolling locally instead of stretching the whole page.
- Ships as one CSS file. No build step, no font download, no plugin required.

## Screenshots

### Overview

![Typora ChatGPT overview](assets/screenshots/hero.png)

### Markdown details

![Code, quote, link, citation and task list details](assets/screenshots/elements.png)

### Responsive tables

![Responsive desktop and narrow table behavior](assets/screenshots/responsive.png)

## Installation

1. Download this repository, or download the latest release ZIP.
2. Open Typora.
3. Go to `Settings` / `Preferences` -> `Appearance` -> `Open Theme Folder`.
4. Copy `typora-chatgpt.css` into that theme folder.
5. Restart Typora.
6. Select `Theme` -> `Typora Chatgpt` from the menu bar.

### macOS quick install

```bash
mkdir -p "$HOME/Library/Application Support/abnerworks.Typora/themes"
curl -L https://raw.githubusercontent.com/Suehn/typora-chatgpt/main/typora-chatgpt.css \
  -o "$HOME/Library/Application Support/abnerworks.Typora/themes/typora-chatgpt.css"
```

Restart Typora after running the command.

## Updating

Replace the old `typora-chatgpt.css` in Typora's theme folder with the new one, then restart Typora.

## Compatibility

Tested on macOS with Typora's current editor DOM. The theme is CSS-only, so it should work on Windows and Linux as long as Typora's theme folder and editor markup remain compatible.

## Design notes

Typora ChatGPT is intentionally focused on Markdown rendering, not the whole ChatGPT product interface. It does not copy chat controls, sidebars, buttons, or application chrome. The goal is simple: make Markdown documents in Typora read like the official ChatGPT Markdown surface.

The responsive table behavior follows the same principle:

- roomy windows keep the desktop-style content column;
- narrow windows keep a readable side boundary;
- ordinary tables wrap inside the content column;
- wide tables scroll inside their own container.

## File list

```text
typora-chatgpt.css              # theme file
assets/screenshots/             # README screenshots
assets/preview/                 # local screenshot preview pages
sample.md                       # markdown sample for testing the theme
```

## License

MIT License. See [LICENSE](./LICENSE).

ChatGPT is a trademark of OpenAI. This project is an independent Typora theme and is not affiliated with OpenAI.
