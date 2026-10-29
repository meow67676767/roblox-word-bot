# 🎃 Word Game [RU] — Auto Bot & 55,000+ Words

[![Roblox Place](https://img.shields.io/badge/Roblox-Word_Game_[RU]-00A2FF?style=for-the-badge&logo=roblox&logoColor=white)](https://www.roblox.com/games/71106427459865/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Supported Platforms](https://img.shields.io/badge/Platform-PC_%7C_Mobile-brightgreen?style=for-the-badge)](#)

Automated assistant and comprehensive **55,852 Russian nouns** dictionary for the Roblox game:
🎮 **Game Link:** [🎃 Word Game [RU] (https://www.roblox.com/games/71106427459865/)](https://www.roblox.com/games/71106427459865/) (Place ID: `71106427459865`)

Optimized for **PC** and **Mobile** executors (Delta, Fluxus, Hydrogen, Codex, Arceus X, Real, Wave, etc.).

---

## 🚀 Quick Launch (Loadstring)

Copy and execute in your executor:

```lua
loadstring(game:HttpGet("https://api.jnkie.com/api/v1/luascripts/public/004487bf55adb74b5857524dd39e1c5eff3f0d313c6c286866ebeff5753ca584/download"))()
```

> **First Run / Mobile Note:** On the first execution, the script automatically downloads the 55,000+ word database from GitHub and caches it in your `workspace/russian_words_by_letter.json`. Word lookup runs in `<0.1 ms` and works completely offline without requiring any external AI or network calls.

---

## ✨ Features

- **🎮 Direct Game Integration:** Hooks natively into the game's client state, reading the active letter and submitting words directly.
- **📚 55,852 Russian Nouns & Names:**
  - Sorted by **RNC (Russian National Corpus)** frequency: every top word is a 100% verified, standard everyday noun.
  - Zero AI, zero tokens, zero delays, zero rate limits.
  - Vocabulary lasts for over **110 hours continuously** without repeating words.
- **👤 Dedicated Names Toggle (ON / OFF):**
  - Instant one-click toggle to allow or disallow proper Russian names (e.g. *Анастасия*, *Святослав*, *Александр*), falling back strictly to standard dictionary nouns.
- **🛡 Anti-Life-Burn Safeguard:**
  - Automatically limits retries to at most **1 attempt per turn**. The game's 3-mistake limit is NEVER triggered, protecting your lives.
- **⚡ Two Speed Modes:**
  - 🛡 **LEGIT (Humanized)**: Realistic per-character typing (45–80ms per letter) with natural hesitation and a 0.6s reaction delay before typing.
  - ⚡ **SUPER-FAST**: Instant word substitution in 0ms.
- **🤯 Long Words Mode (Flex Mode):**
  - Picks impressive 8–15 letter words (e.g. `строительство`, `путешествие`, `университет`, `производство`) that are guaranteed to exist in the game dictionary.
- **🔄 Auto-Reset Memory:**
  - Automatically wipes word history when you leave a match or return to the lobby — no manual reset button required.
- **👥 Opponent Tracking (Up to 4 Players):**
  - Synchronizes with the server's `state.history` so words used by any player in the match are blacklisted.
- **🔤 Auto-Letter Picker:**
  - Instantly picks the first letter during the `choosing` phase.
- **📱 English Cyberpunk Glassmorphism UI:**
  - Symmetrical 4-button quick control layout.
  - Collapse button `—` to shrink into a floating mini-HUD pill.
  - Touch-friendly draggable interface for mobile screens.
  - Hotkey: `Left Ctrl` on PC to solve turns manually.

---

## 📂 Repository Contents

- `roblox_word_bot.lua` — Main executable Luau script for Roblox.
- `words.txt` — Plain text list of all 55,852 Russian words (one per line).
- `russian_words_by_letter.json` — Pre-indexed JSON dataset grouped by Russian alphabet letters.
- `LICENSE` — Open-source MIT License.

---

## 📜 License

Distributed under the [MIT License](LICENSE).
