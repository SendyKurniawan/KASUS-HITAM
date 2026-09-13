# KASUS-HITAM
🕵️ Kasus Hitam — Web Edition: a single-file, pass-and-play hidden-role deduction game for 4–12 players. One device, no install, no server. Forensic Scientist, Murderer, optional Accomplice &amp; Witness, clue cards, means cards, scene tiles, badges, and three rounds of accusations.
# 🕵️ Kasus Hitam — Web Edition

A single-file, hot-seat hidden-role deduction game for **4–12 players**.

Everyone shares one device. The **Forensic Scientist** knows the solution but can only communicate through **Scene tiles**. The **Murderer** secretly chooses one **Clue** and one **Means** from their own hand. Investigators have three rounds and one badge each to expose the killer before the case goes cold.

No install. No server. No build step. Open `index.html` and play.

## ✨ Features

- 🎭 **Full role set** — Forensic Scientist, Murderer, Investigators, plus optional **Accomplice** and **Witness** for 6+ players
- 🔪 **Murderer-chosen solution** — the killer secretly locks in 1 Clue + 1 Means from their 4+4 hand
- 🧩 **20 Scene tiles** — 2 fixed (Location, Cause of Death) + 4 random per game, drawn without repeats across rounds
- 🔄 **Tile replacement** — each new round draws a fresh tile to swap into the board
- 🎖️ **Badge accusations** — accuse a suspect + Clue + Means; a wrong guess burns your badge permanently
- 👁️ **Witness endgame** — if the crime is solved, the Murderer gets one final guess at the Witness
- 🤝 **Accomplice obfuscation** — with both roles in play, the Witness sees only two names in random order
- 🔒 **FS View toggle** — peek at the solution for debugging or solo testing
- 📱 **Mobile-first** — sticky header, tap targets, and private “pass the device” reveal screens
- 🚫 **Zero dependencies** — one HTML file, no frameworks, no CDN, no package manager

## 🎮 How to Play

1. Set the player count (4–12) and enter names.
2. Optionally enable the **Accomplice** and/or **Witness** (6+ players).
3. Pass the device around — each player privately views their role.
4. The **Murderer** secretly locks in one Clue + one Means card.
5. The **Forensic Scientist** places one bullet on each Scene tile.
6. Discuss. Anyone with a badge may accuse someone, naming their Clue and Means.
7. Three rounds max. Solve it — or the Murderer escapes.

## 🛠️ Tech

Plain HTML + CSS + vanilla JavaScript. No bundler, no package manager, no runtime dependencies. State lives in a single object and re-renders via `innerHTML` with event delegation.

## 🚀 Run It

```bash
git clone <your-repo>
cd <your-repo>
open index.html
