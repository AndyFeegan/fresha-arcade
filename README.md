# Fresha Sales Training Arcade

Multi-game training arcade for Fresha sales teams. 16 standalone HTML files across 4 languages.

## Games

| Game | Description |
|------|-------------|
| **Millionaire** | 15-question quiz with lifelines, timer, and point ladder |
| **Hangman** | Guess Fresha terms — 10 rounds with streak multiplier |
| **Trivia Board** | Roll dice, answer questions, collect 5 category wedges |
| **Hub** | Player profile, XP, achievements, leaderboard |

## Languages

- 🇬🇧 English (`/en/`)
- 🇫🇷 French (`/fr/`)
- 🇪🇸 Spanish (`/es/`)
- 🇸🇦 Arabic (`/ar/`) — full RTL support

## Quick Start

Open `index.html` or navigate directly to any language's `hub.html`. No build tools, no dependencies — just open in a browser.

### Host on GitHub Pages

1. Push this repo to GitHub
2. Settings → Pages → Source: `main` branch, `/ (root)`
3. Your arcade is live at `https://<username>.github.io/fresha-arcade/`

## Tech

- **Zero dependencies** — pure HTML + CSS + JS inline
- **localStorage** for persistence across all 16 files
- **Web Audio API** for sound effects
- **Canvas** for trivia board and particle effects
- **Fisher-Yates shuffle** for answer randomisation

## Storage Keys

All files share these localStorage keys:

| Key | Purpose |
|-----|---------|
| `player-profile` | Name, XP, join date |
| `fresha-arcade-progress` | Per-game stats |
| `fresha-arcade-achievements` | Unlocked achievements |
| `fresha-arcade-leaderboard` | Top operatives |
| `fresha-arcade-settings` | Sound on/off |

## Categories

1. Fresha Product Knowledge
2. GAP Selling
3. Beauty & Wellness Industry
4. Objection Handling
5. Industry & Market Knowledge

## XP System

| Level | XP Required |
|-------|-------------|
| Trainee | 0 |
| Rookie | 1,000 |
| Agent | 3,000 |
| Specialist | 6,000 |
| Expert | 10,000 |
| Senior Agent | 15,000 |
| Elite | 21,000 |
| Master | 28,000 |
| Director | 36,000 |
| Grandmaster | 45,000 |
