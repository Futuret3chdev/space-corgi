# Space Corgi BETA 🐶🚀

**BETA v0.9** — Single-file browser game. Adorable corgi astronaut + bosses + rockets + sign-in + wallets.

[![GitHub Repo](https://img.shields.io/badge/GitHub-Futuret3chdev%2Fspace--corgi-181717?logo=github)](https://github.com/Futuret3chdev/space-corgi)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FFuturet3chdev%2Fspace-corgi)

## How to Play (Desktop + Mobile)

1. Open `index.html` in any modern browser.
2. **Mouse / Drag** — Steer the corgi (inertia flight)
3. **Click / Hold or TAP** — Fire bone "Bork Blasters"
4. **Mobile**: Left **joystick** + right **BORK** button (auto-shows on touch devices)
5. **Arrow Keys / WASD + SPACE** — Keyboard backup
6. **P** — Pause
7. **R / Enter** — Restart

**Sign in** (top-left) with **X, Discord, Telegram** or **connect Phantom / Solflare / Backpack** to earn and keep 🚀 **Rockets**.

## New in BETA

- **Rockets (🚀)**: Earn from playtime, score milestones, collecting bones, and especially defeating the **Void Meowlord** boss. Sign-in / wallet gives bonus rockets.
- **Sign-in**: X, Discord, Telegram (demo) + real Solana wallet connect (Phantom, Solflare, Backpack). Persisted in localStorage.
- **Boss fights**: The Void Meowlord appears periodically with phases (homing shots, minion summons, charge attacks). Big rewards.
- **New enemies**: Zig-zag Squirrels, Icy Comets (split on death), Void (black holes that pull you), Laser Turrets (burst fire).
- **New power-up**: **STAR MAGNET** — massively increases collect range + orbiting visual + bonus rockets on pickup.
- **Mute button** (🔊 top-right)
- **Full mobile support** with virtual joystick + dedicated fire button.
- Fresh **neon cosmic color scheme** (deep indigo + electric cyan + hot magenta).

Power-ups: Rapid Bark • Mega Bork • Shield • **Star Magnet** (new).

## Features & Animations

- Procedural animated corgi (wagging tail, ears, jetpack flames, neon collar)
- Layered particles, parallax stars, pulsing nebulae
- Screen shake, popups, boss HP bar
- Procedural Web Audio (toggleable)
- Everything self-contained — no install, no backend required for demo features. Real wallet connections work when extensions are present.

## Technical

Pure single-file HTML/CSS/JS Canvas. No deps.

Wallet connect uses native injected providers (window.phantom.solana etc.). Social login is a polished local demo (no real OAuth keys needed).

## Deployment (GitHub + Vercel)

The game is **100% static** — perfect for free hosting.

### One-click Deploy to Vercel
Click the button at the top of this README, or use:

https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FFuturet3chdev%2Fspace-corgi

### Live Demo
**https://space-corgi.vercel.app**

### Manual

1. The repo is already on GitHub.
2. Vercel has been connected (or import manually from GitHub).
3. It deploys as a pure static site automatically.

Or with Vercel CLI from your machine:
```bash
npm i -g vercel
vercel --prod
```

The `vercel.json` in the repo configures it as a pure static site.

## Tips (BETA)

- Sign in early to bank rockets across runs
- Bosses reward big rocket hauls — focus fire when it charges!
- Magnet power-up + joystick on mobile = excellent bone farming
- Mute if you want silent focus sessions

Enjoy the BETA — bark among the stars, pilot! 🐾✨

---

Made with love for corgis, the cosmos, and on-chain corgi pilots.