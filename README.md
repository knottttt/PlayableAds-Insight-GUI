# PlayableAds Insight GUI

> Disclaimer: This repository is for learning and communication only. Commercial use is not allowed.

Language / 语言: [English](./README.md) | [中文](./README_zh.md)

A local offline tool for replacing playable HTML assets and store links.

## Features

- Parse common playable resource patterns: `ZIP`, `adapterZip`, `inline data:image`
- Replace single image assets
- Batch-replace images by filename
- Rewrite common store links (`apps.apple.com`, `itunes.apple.com`, `play.google.com/store/apps`)
- Regenerate a deliverable HTML file after replacement
- Built-in local preview panel for quick validation

## Typical Use Cases

- Frequent playable image swaps during iteration
- Rapid App Store / Google Play link updates
- Quick local verification before final delivery

## Quick Start

1. Open [index.html](./index.html)
2. Upload your playable HTML file
3. Replace images (single or batch)
4. Fill store URL(s)
5. Click preview and validate output
6. Download the generated HTML

## Notes

- Batch replacement mainly works for resources that keep filenames
- `inline` mode does not support filename-based batch replacement
- Always do a final rendering and click-through check before production use

## Project Files

- [index.html](./index.html): UI page
- [main.js](./main.js): core processing logic
- [CHANGELOG.md](./CHANGELOG.md): version history
- [UPDATE_NOTE.md](./UPDATE_NOTE.md): update note
