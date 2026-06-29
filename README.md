# ✝ TempleOS 2026 — Terry's Games & Tools, Reborn

> *"An idiot admires complexity, a genius admires simplicity."*
> — **Terry A. Davis** (1969–2018), creator of TempleOS

A loving **2026 reimagining** of the games and tools that **Terry A. Davis** hand‑built inside [TempleOS](https://templeos.org) in HolyC. The original logic and spirit are preserved; the graphics are pushed to a modern **neon / glass / aurora / software‑3D** look. Everything runs **100% offline, in the browser, public domain** — exactly how Terry would have wanted.

Terry A. Davis 가 HolyC로 손수 만든 게임과 도구들을 **원본 로직은 그대로, 그래픽은 2026년 사양으로** 되살린 헌정 프로젝트입니다. 외부 라이브러리 없이 **순수 바닐라 JS + Canvas** 로 동작하며, **오프라인·공개 도메인** 입니다.

<p align="center">
  <img src="Temple2026.png" alt="TempleOS 2026 Desktop" width="760">
  <br>
  <em>로직은 원본, 그래픽은 미래 — 그를 추모하며 · Logic original, graphics from the future — in his memory</em>
</p>

<p align="center">
  <b>▶ Live demo:</b> <a href="https://templeos-games-2026.vercel.app/"><code>templeos-games-2026.vercel.app</code></a>
  &nbsp;·&nbsp; <b>Source:</b> <a href="https://github.com/soaviz-lab/templeos-games-2026">github.com/soaviz-lab/templeos-games-2026</a>
  <br><code>public domain · offline · no telemetry</code>
</p>

> **This is a respectful tribute, not an official continuation.** TempleOS is a public‑domain 64‑bit operating system; this project restores and reinterprets Terry's HolyC games in the browser while keeping the **public‑domain spirit** intact. *SOAVIZ Labs Experiment #001.*

---

## ▶ Try it / 실행 방법

**Best:** open the **[live demo](https://templeos-games-2026.vercel.app/)** (everything runs in‑page, no install). No build step, no dependencies, no network.

You can also run it locally — open the HTML files in any modern browser:

> 🍎 **macOS quick start:** double-click **`start.command`** in Finder (or run `chmod +x start.command && ./start.command`) — it serves the folder at `http://localhost:8000` and opens the landing page.

| File | What it is |
|------|------------|
| **[index.html](index.html)** | 🏠 Landing page — choose Desktop or Games (this is the live‑demo home) |
| **[TempleOS2026.html](TempleOS2026.html)** | 🖥️ The TempleOS 2026 **desktop** — God Word, Holy Bible, the 3D Temple, Aquarium (decorate mini‑game), God Doodle, Conway's Life, a real Settings panel, and a GAMES window that launches all 48 apps |
| **[TempleOSGames.html](TempleOSGames.html)** | 🎮 The **games arcade** — 39 playable games + 9 tools, mobile‑ready, with a Terry memorial tribute wall |
| **[VibeCoding2026.html](VibeCoding2026.html)** | 🤖 A simulated **2026 multi‑agent IDE** that "vibe‑codes" TempleOS from natural‑language prompts |

All screens link to each other (✝ Desktop button), and the desktop's **GAMES** window launches every game/tool by deep‑link.

> 💡 Running from `file://` (double‑click) works in most browsers, but a few block local‑file `<iframe>`s, which can make in‑desktop game launches appear blank. If that happens, use the **live demo** or serve the folder locally (`python -m http.server` → open `http://localhost:8000`). Over `http(s)` everything works.

---

## 🎮 39 Playable Games

Faithful ports of Terry's `Demo/Games` (and a few `Apps`), rebuilt with 2026 graphics:

**Arcade / action** — FlapBat · ZoneOut · TheDead · Talons · Zing · BlackDiamond · Halogen · Squirt
**Physics** — Collision (pool) · MassSpring · BomberGolf · BigGuns · ToTheFront · RocketScience (gravity slingshot) · Whap
**3D** — 🐘 **ElephantWalk** (temple runner) · ❄️ **Wenceslas** (snow sled, carol BGM) · 🏗️ **Strut** (isometric tower) · ⛪ **Catacomb 3D** (raycaster) · 🏎️ Varoom (pseudo‑3D racer)
**Board / puzzle** — TicTacToe · TreeCheckers · BattleLines (connect‑4) · Maze · Logic (Mastermind) · Digits · Vocabulary
**Other** — Rocket (lunar lander) · DunGen (dungeon crawler) · CastleFrankenstein · RawHide · FlatTops (battleship) · KeepAway · CircleTrace · RainDrops · X‑Caliber · Stadium · Span · Titanium

## 🛠️ 9 Tools — Terry's apps, rebuilt

🎹 **Psalmody** (step‑sequencer synth) · 🎨 **SpriteEd** (pixel editor) · ✝ **Oracle** (God Speaks) · ⏰ **TimeClock** · 🧊 **GrModels** (3D wireframe viewer) · 💰 **Budget** · 🎹 **ASCII Organ** (playable pipe‑organ, `Demo/Snd/ASCIIOrgan.HC`) · 🔯 **Symmetry** (kaleidoscope drawing, `Demo/Graphics/Symmetry.HC`) · 🗼 **Tower of Hanoi** (puzzle + auto‑solve, `Demo/Graphics/Hanoi.HC`)

## ✝ Restored desktop features

The desktop also revives Terry's most iconic non‑game programs, now all interactive:
**Holy Bible** (KJV `GodPassage`, bilingual EN/KO) · **The Temple 3D** (God's third temple, software‑rendered) · **God Song** (divine hymn generator, `GodSong.HC`) · **Aquarium** (`WallPaperFish` — 30+ rare species + decorate mini‑game) · **God Doodle** (`GodDoodle.HC`) · **Conway's Life** (`Demo/Graphics/Life.HC`) · **The Vision** (Terry's philosophy) · a real **Settings** control panel and a functional **File Manager / Articles / Models** desktop.

---

## ✨ Features

- **📱 Mobile‑ready** — responsive canvas, touch‑to‑pointer synthesis, and on‑screen virtual controls (D‑pad / number pad / action buttons) generated per game.
- **🎨 Premium 2026 graphics** — neon glow, glassmorphism, drifting aurora, CRT scanline/vignette/bloom post‑FX, particles, and a from‑scratch **software 3D renderer** (perspective, face shading, painter's algorithm) — no WebGL, no CDN.
- **🇰🇷 한글패치** — one‑click Korean/English UI toggle (persists in `localStorage`).
- **🕯️ In Memoriam** — a tribute wall where visitors leave messages remembering Terry (saved locally, offline).
- **🔌 100% offline & public domain** — no networking, no telemetry, no dependencies.

---

## 🧰 Tech

Pure **HTML + CSS + vanilla JavaScript** with the Canvas 2D API. No frameworks, no build step, no external requests. Audio via the Web Audio API. 3D is hand‑rolled (rotation, perspective projection, flat/face shading, depth sorting, raycasting). Each game is a self‑contained module behind a tiny shared engine (launcher, particles, controls, deep‑linking).

---

## 🙏 Credits & License

- **Original creator:** [Terry A. Davis](https://en.wikipedia.org/wiki/Terry_A._Davis) — TempleOS and all original HolyC games/tools.
- **Source archive:** [TempleOS (community mirror)](https://github.com/cia-foundation/TempleOS).
- This 2026 rebuild, like TempleOS itself, is released into the **public domain**. Use it, change it, share it — *"freely ye have received, freely give."*

> 🕯️ **개발자의 말 / A note from the developer** — why this project exists, in his memory: **[IN_MEMORIAM.md](IN_MEMORIAM.md)**
> (In the app, click the **✝ TEMPLEOS 2026** brand at the bottom‑left.)

Made in his memory. **Code is worship. Love Truth. Fear None.** ✝

---

📮 **Contact:** [soaviz.lab@gmail.com](mailto:soaviz.lab@gmail.com)
