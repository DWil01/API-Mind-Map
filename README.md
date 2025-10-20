# Interactive HTTP Header Payload Map

**Interactive mind map for testing, adding, and visualizing HTTP header payloads — built for web security researchers and bug bounty hunters.**

This repository contains a standalone, browser-first tool for exploring realistic HTTP request payloads grouped by header/category. Each node holds payload examples you can copy, edit, add to, export, and import — all per-node (per header) so teams and individuals can build curated test suites.

---

## Features

- Visual **tile-based** map of header categories (no external dependencies required).
- **Per-node payload lists**: add, edit, delete, and copy payloads for each header/topic.
- **Add payloads interactively** via editor or prompt if a node has none.
- **Export** all payloads to `payloads_by_node.json` for sharing / backup.
- **Import** previously exported JSON to restore state.
- Works offline — just open `index.html` (or `interactive_payloads_standalone.html`) in any modern browser.
- Keyboard shortcuts and accessible tiles (Enter / Space to open).

---

## Quick start

1. Clone the repo:
```bash
git clone https://github.com/YOUR_USERNAME/interactive-http-headers.git
cd interactive-http-headers
