<h1 align="center">Hey, I'm Ismaël 👋</h1>

<p align="center">
  <em>EPFL Computer Science student · builder of games, engines & on-chain apps</em>
</p>

<p align="center">
  <a href="https://github.com/ismael-ayachi"><img src="https://img.shields.io/badge/GitHub-ismael--ayachi-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <img src="https://img.shields.io/badge/EPFL-Computer%20Science-CC0000?style=for-the-badge" alt="EPFL">
</p>

---

### 🧭 About me

I'm a Computer Science student at **EPFL** who likes projects that force you to think at every layer of the stack — from bit-packed game state and Monte-Carlo search all the way up to smart contracts and pixel-perfect UI. Most of my public work comes out of EPFL coursework and hackathons, where the constraint of a tight deadline tends to produce the most interesting engineering decisions.

- 🎮 Enjoys building **games and the engines underneath them**
- 🧠 Into **AI/search techniques** (MCTS, heuristics) applied to small, well-defined problems
- ⛓️ Also dabbling in **Web3 / smart contracts** through hackathon collaborations
- 📍 Based in the Lausanne / EPFL area

---

## 🚀 Featured Projects

### 🀄 [Ajul](https://github.com/ismael-ayachi/Ajul) — Azul, the board game, in Java + JavaFX
A full digital reimplementation of the award-winning tile-drafting board game **Azul**, built for EPFL's CS-108 course. Supports 2–4 players, any mix of humans and AI.

- 🤖 **AI opponent** powered by **Monte-Carlo Tree Search** with a heuristic move selector, running 100,000 iterations per move by default
- ⚡ **Bit-packed game state** — pattern lines, walls, and tile sets are encoded into raw `int`/`short` values using SWAR techniques so millions of simulations stay cheap
- 🖱️ **Drag-and-drop JavaFX UI** with smooth tile animations
- 🧵 A dedicated game thread runs the simulation while the JavaFX thread stays responsive, synchronized via a `SynchronousQueue`
- Developed incrementally across **12 weekly stages**, from low-level data structures to the final animated interface

**Stack:** Java · JavaFX · JUnit 5 · Monte-Carlo Tree Search

---

### 🔥💧 [ICoop](https://github.com/ismael-ayachi/ICoop) — a 2-player cooperative game on a custom engine
A top-down cooperative action-adventure built on top of a **hand-rolled 2D game engine**, inspired by *Fireboy and Watergirl*. Two players — one Fire, one Water — must split tasks and coordinate to clear puzzles, fight enemies, and beat the final boss.

- 🏗️ Reusable `game-engine` module: rendering loop, audio, actor/area abstractions, grid-based physics-lite movement, input handling
- 🌍 Six interconnected areas (Spawn, OrbWay, Maze, Arena, SanctumEntrance, Sanctum) gated behind cooperative challenges
- 🎯 Extended well beyond the base assignment: a full menu system, evolving companions, a boss that can turn invisible, ranged enemies, lockable chests, and animated decor
- 🧩 Clean separation of cross-cutting concerns via a `handler/` layer (interaction visitors, timers, target-following, challenge/logic gating)

**Stack:** Java · Maven · custom 2D engine

---

### 🏛️ [BidSui](https://github.com/AmineRah/BidSui) — Dutch auctions with NFT escrow, on Sui *(collaboration)*
A decentralized auction platform on the **Sui blockchain**: Dutch (decreasing-ceiling) auctions with automatic NFT escrow and real-time bidding.

- ⚡ Smart contracts in **Move** handling escrow, bidding, and automatic settlement
- 🔌 Node.js backend with WebSocket support for live auction updates
- 💻 Next.js/React frontend with wallet integration

**Stack:** Move · Node.js · Next.js · WebSockets

---

### 🏠 [LeasENS](https://github.com/H0lmin/LeasENS) — scam-proof rent payments using ENS *(hackathon build)*
Built at the **StableCoins & Payments Hackathon** (BSA @ EPFL, ENS track): every lease is minted as an ENS subname, so a payment link is only valid if the corresponding on-chain lease actually exists.

- 🪪 Three-tier ENS hierarchy (property manager → owner → lease) with lease terms stored directly as ENS text records
- 📜 Single `LeaseManager.sol` contract for the full lease lifecycle — create, pay, terminate, with automatic late-penalty accrual
- 👤 Privy embedded wallets for tenants (email login, no seed phrase) alongside MetaMask for owners

**Stack:** Solidity · Foundry · Next.js · ENS NameWrapper

---

## 🛠️ Tech I work with

<p align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/JavaFX-0d1117?style=flat-square">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white">
  <img src="https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white">
</p>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ismael-ayachi&show_icons=true&theme=default&hide_title=true" alt="GitHub stats" height="165">
</p>

<p align="center"><em>Thanks for stopping by — feel free to explore the repos above ⭐</em></p>
