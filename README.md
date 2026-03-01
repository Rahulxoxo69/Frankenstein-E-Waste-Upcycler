# ⚡ Frankenstein E-Waste Upcycler
> **Intelligent triage and combinatorial upcycling engine for broken electronics.**
Stop throwing away devices just because one part failed. The Frankenstein E-Waste Upcycler helps you diagnose broken electronics, classify which components are still usable, and suggests real upcycling projects you can build with what you've salvaged.
---
## What It Does
1. **Ingest** — Describe your broken device: model, symptoms, cause of damage, and your available tools/skill level.
2. **Classify** — A combinatorial algorithm sorts the device's components into three categories:
   - 🔴 **Irreparable** — parts that are dead and should be recycled responsibly
   - 🟡 **Repairable** — parts that can be fixed with the right tools
   - 🟢 **Good** — salvageable components ready for reuse
3. **Upcycle** — Get project suggestions based on the surviving parts.
4. **Vault** — Save good parts to a persistent inventory across multiple devices. The vault feeds the combinatorial logic to suggest cross-device builds.
---
## Features
- **Component Triage** — Structured diagnostics form with image upload support
- **Tool & Skill Matching** — Results adapt based on your available tools and experience level
- **Draft Vault** — A running parts inventory; add items from results or manually, delete when used
- **Upcycling Suggestions** — Context-aware project ideas based on salvaged components
- **Zero dependencies** — Pure HTML, CSS, and vanilla JavaScript. No build step, no backend.
---
## Getting Started
Just open `index.html` in any modern browser — or serve it locally:
```bash
python -m http.server 8080
```
Then visit `http://localhost:8080`.
---
## Tech
| Layer | Choice |
|-------|--------|
| Structure | HTML5 |
| Styling | Vanilla CSS (glassmorphism, CSS variables, animations) |
| Logic | Vanilla JavaScript |
| Fonts | Inter + Space Mono (Google Fonts) |
---
## Why?
E-waste is one of the fastest-growing waste streams on the planet. Most devices are discarded because of a single failed component — while the rest of the board is perfectly fine. This tool is a small attempt to change that habit, one salvaged RAM stick at a time.
---
