# PixelVault

A living, animated workspace where AI agents are visible pixel art characters working in rooms that reflect your actual life and projects.

Built on a fork of [Pixel Agents](https://github.com/pablodelucca/pixel-agents) by Pablo De Lucca.

---

## The Vision

A pixel art creative OS backed by Obsidian as the brain and Claude Code as the muscle. Seed inventory room. Warhammer painting station. 3D printing bay. Arcade. A virtual you. Each room maps to a real section of your life — and the agents in it are actually working.

---

## Rooms (Planned)

- **Main Office** — agents at desks, default workspace
- **Seed Vault** — virtual seed inventory linked to Obsidian notes
- **The Workshop** — 3D print queue, active prints as animated machines
- **Warhammer Studio** — painting table, model inventory
- **The Arcade** — game prototypes and experiments
- **File Room** — cabinet drawers linked to Obsidian folders
- **Personal Quarters** — home base for your pixel avatar

---

## Stack

| Layer | Tool |
|---|---|
| OS / Runtime | Windows 11 + WSL2 (Ubuntu) |
| AI Agent | Claude Code |
| Code Editor | VS Code + WSL Extension |
| Office Interface | PixelVault (this repo) |
| Knowledge Base | Obsidian |
| Pixel Art | Pixelorama / LibreSprite |
| Image Gen | ComfyUI (local) |
| Version Control | Git + GitHub |

---

## Getting Started

```bash
git clone https://github.com/nSOLOTIMEm/pixelvault.git
cd pixelvault
npm install
cd webview-ui && npm install && cd ..
npm run build
```

Press **F5** in VS Code to launch the Extension Development Host.

---

## How It Works

PixelVault watches Claude Code's JSONL transcript files to track what each agent is doing. Characters animate based on real agent activity — typing when writing code, reading when searching files, waiting when they need your attention. No modifications to Claude Code required.

---

## Working Principles

This project is built by an artist who needs secure, private, and efficient implementations.

- **Credentials** — Never expose tokens, keys, or sensitive credentials in plaintext without explicit permission
- **Infrastructure** — Never delete infrastructure or repositories without explicit permission
- **Standards** — Follow TDD, OWASP Top 10, and NIST AI RMF throughout the codebase
- **Creative tools** — If a visual goal can't be met with existing tools, ask whether to build something custom rather than forcing a bad fit
- **Copyright** — Flag any potential copyright concerns immediately with guidance on how to proceed
- **Security by default** — Minimize attack surfaces and practice the principle of least privilege throughout
- **The goal** — Have fun without getting pwned

---

## Credits

Forked from [Pixel Agents](https://github.com/pablodelucca/pixel-agents) by [Pablo De Lucca](https://github.com/pablodelucca) — MIT License.

Office tileset: [Office Interior Tileset (16x16)](https://donarg.itch.io/officetileset) by Donarg ($2 on itch.io, not included in this repo).

---

## License

MIT
