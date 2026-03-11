# 🕵️ COLD CODE: KGB SHADOWS — 1986

> A browser-based Cold War terminal game. No installation, no dependencies — just open and play.

---

## 📡 The Missions

| Level | Year | Location | Difficulty | Timer |
|---|---|---|---|---|
| 🎓 **Training** | — | NSA Facility | Beginner | None |
| 🖥️ **The Cuckoo's Egg** | 1986 | Berkeley, California | ★☆☆ | None |
| 🧱 **Operation Mauer** | 1989 | West Berlin | ★★☆ | 8 min |
| ☭ **Ghost Protocol** | 1991 | Moscow, KGB Center | ★★★ | 10 min |

> *Based on real events: Cliff Stoll's KGB hunt, the fall of the Berlin Wall, the Soviet coup.*

---

## ✨ Features

- **CLI gameplay** — everything is typed. No mouse, no clicks, pure terminal
- **CRT aesthetic** — scanlines, phosphor green, IBM Plex Mono — it's 1986 in your browser
- **Live threat system** — urgent alerts interrupt your work mid-mission; respond fast or lose security
- **System security gauge** — your health bar. Drops on wrong moves and ignored threats
- **3-slot save system** — save at any point, resume from any browser session
- **Command history** — Arrow ↑/↓ to scroll through previous inputs
- **TAB autocomplete** — context-aware per level
- **Multilingual** — Italian 🇮🇹 and English 🇬🇧 with full localization
- **Generative audio** — 8-bit sound engine via Web Audio API, no external files
- **Zero dependencies** — single HTML file, works offline

---

## 🚀 How to Play

### Method 1 — Directly in the browser
```
1. Download KGB_Shadows.html
2. Open it with any modern browser (Chrome, Firefox, Edge, Safari)
3. Enter your agent name and start the training
```

### Method 2 — GitHub Pages
```
1. Fork this repository
2. Go to Settings → Pages
3. Select the main branch as source
4. The game will be available at https://<your-username>.github.io/<repo-name>/
```

---

## 🕹️ Controls

| Input | Action |
|---|---|
| Type + `ENTER` | Execute command |
| `Arrow ↑ / ↓` | Command history |
| `TAB` | Autocomplete |
| `ESC` or `✕ MENU` | Pause — save and exit |

---

## 📋 Command Reference

### Level 0 — Training
`history` `system` `ls` `read` `drill` `locklog` `done`

### Level 1 — The Cuckoo's Egg
`log` `trace` `ls` `mkdir [name]` `monitor` `status`
Threats → `locklog` `firewall` `chmod`

### Level 2 — Operation Mauer
`scan` `intercept [node]` `decrypt [key]` `analyze` `transmit`
Threats → `boost` `reroute` `snapshot`

### Level 3 — Ghost Protocol
`login [user]` `escalate` `scan` `download [path]` `verify` `choice [A/B/C]`
Threats → `divert` `spoof` `silence`

---

## 📁 Project Structure

```
kgb-shadows/
│
├── KGB_Shadows.html    # The complete game (HTML + CSS + JS in a single file)
└── README.md           # This file
```

> The project is intentionally contained in a single file for maximum portability.

---

## ⚠️ Important Notes

**Save System**
Progress is stored in the browser's `localStorage` — saves persist between sessions on the same browser and machine. Three slots available. Type `save` mid-mission to access them.

**Compatibility**
Tested on Chrome 120+, Firefox 121+, Edge 120+, Safari 17+.
Requires a browser with **Web Audio API** support for sound and generative music.
If you experience issues with browser extensions, try Incognito mode.

**Privacy**
No data is sent to external servers. Everything stays in your browser.

---

## 📖 Historical Background

The game's three missions are built around real events:

- **1986** — Cliff Stoll traced a KGB-connected hacker through ARPANET using a honeypot trap. He documented it in *The Cuckoo's Egg* (1989), a landmark of cybersecurity history.
- **1989** — The Berlin Wall fell on November 9. Western intelligence raced to intercept STASI communications before archives were destroyed.
- **1991** — The three-day coup against Gorbachev triggered a KGB archive burn. The VENONA project — an NSA operation to decrypt Soviet cables — stayed classified until 1995.

---

## 🛠️ Future Development (Roadmap)

- [ ] Level 4 — post-Cold War scenario (1995, internet era)
- [ ] Timed score leaderboard
- [ ] Mobile layout optimization
- [ ] Branching dialogue system
- [ ] PWA (installable as app)

---

## 📄 License

MIT License — free to use, modify and distribute with attribution.

```
Copyright (c) 2025 Anton

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

## 👤 Author

**Anton** — [github.com/Tohiko98](https://github.com/Tohiko98)
Personal project — built with pure vanilla HTML, CSS and JavaScript.
Part of the **Neuro Arena** series.

> *"The Cold War was also fought in the shadows of terminals."*

---

⭐ If you like the project, leave a star on GitHub! ⭐
