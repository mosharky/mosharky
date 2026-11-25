# Hi, I'm Mo

Canadian Computer Science student at **Sheridan College** (B.CS, expected 2028). I mostly build **game mods and the tooling around them**: native C++ engine patches, Java mods for Minecraft, and Python utilities for mod managers. Most of it is open source, and a few projects have reached over a million players.

- 🔧 **Currently working on:** [Artificer](https://github.com/mosharky/Artificer), a native C++ performance plugin for *Europa Universalis IV*
- 🤝 **Previously:** mod developer at [Monad Modding](https://github.com/Monad-Modding) on *No Man's Land* and *Wayfarer* (300k+ downloads)
- 💬 **Ask me about:** reverse-engineering game engines, Minecraft modding (Fabric / NeoForge / Mixin), Mod Organizer 2 plugins

---

## ⭐ Featured projects

### [Artificer](https://github.com/mosharky/Artificer) · C++ · Python · CMake
A DLL plugin that hooks *Europa Universalis IV* to fix a memory leak that slows the game down over long sessions.
- Reverse-engineered the engine's pop-up lifecycle (vtables, object layouts, destructors) and found **4,600+ closed pop-ups that were never freed**
- Cut paused frame time by **70%** (4.95 ms → 1.48 ms) and the per-day slowdown from **26% → 4%**
- Python profiling tools (stack sampler, profile comparer) built on Win32 APIs to measure the before and after
- CI/CD with GitHub Actions and release-please, releasing to GitHub and the Steam Workshop

### [Mo's Grounded Origins](https://www.curseforge.com/minecraft/mc-mods/grounded-origins-fabric) · Java · Origins API
A Minecraft mod with **1,250,000+ downloads**. Worked with the Origins API developers to get new features added upstream, and reviewed and merged contributions from other developers.

### [Vintage Story Mod Updater](https://github.com/mosharky/MO2-VS-Mod-Updater) · Python · PyQt6
The first GUI mod updater for *Vintage Story*: a Mod Organizer 2 plugin that updates installed mods through the game's mod database REST API. 1,000+ downloads, with pull requests from users.

---

## 🛠️ Tech I use

**Languages:** C++ · Java · Python · C# · JavaScript · SQL

**Game dev & modding:** Mixin · Fabric / NeoForge · Unreal Engine 5 · Unity · SDL2 · OpenGL / GLSL

**Tools:** Git · GitHub Actions · CMake · Docker · Visual Studio · IntelliJ

---

[![Stats](https://github-readme-stats.vercel.app/api?username=mosharky&show_icons=true&theme=dark)](https://github.com/mosharky)
[![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mosharky&layout=compact&theme=dark)](https://github.com/mosharky)
