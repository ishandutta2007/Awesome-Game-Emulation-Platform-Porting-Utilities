# Awesome-Game-Emulation-Platform-Porting-Utilities

<p align="center">
  <img src="./assets/banner.svg" alt="Top Game Emulation & Platform Porting Utilities" width="100%" />
</p>

<p align="center">
  <a href="https://github.com"><img src="https://shields.io" alt="Awesome"/></a>
  <a href="https://discord.gg"><img src="https://shields.io" alt="Discord" /></a>
  <a href="https://github.com"><img src="https://shields.io" alt="GitHub stars" /></a>
  <a href="https://github.com"><img src="https://shields.io" alt="GitHub forks" /></a>
  <a href="https://github.com"><img alt="GitHub followers" src="https://shields.io" /></a>
</p>

# 🕹️ Top Game Emulation & Platform Porting Utilities

**Curated List of SaaS/Commercial Platforms & Open-Source GitHub Projects**  
*Focused on Console/Arcade Emulators, Cross-Platform Translation & Porting Layers (macOS/Linux/ARM), Retro Gaming OS Distros & Self-Hosted Cloud Game Streaming*  
**Last updated: November 2026**

This repository tracks notable **SaaS/Commercial platforms** and **open-source projects** for **Game Emulation & Platform Porting Utilities**. These tools power multi-system emulation frontends (`RetroArch`, `ES-DE`, `Playnite`, `Pegasus`), Apple Silicon & Linux platform porting/translation layers (`NX2Apple`, `Wine`, `DXVK`, `Box64`, `Whisky`), dedicated retro-gaming Linux OS images (`Batocera.linux`, `Recalbox`, `RetroPie`), and self-hosted low-latency game streaming (`Sunshine` + `Moonlight`) for preservationists, Linux/macOS gamers, and emulation engineers.

**Examples** include GeForce NOW (NVIDIA), Boosteroid, Shadow PC (OVHcloud / Octave Klaba), Antstream Arcade, Utomik, LaunchBox / Big Box, RetroArch (Libretro Cloud / App Store Ecosystem), Playnite (Hosted Addon/Metadata Ecosystem), Batocera (Hosted Image & Content Ecosystem), and Recalbox (Commercial Hardware/Kit Ecosystem) (the category leaders).

**🚀 Open-source emphasis**: This section is heavily expanded with every major active project for cross-platform porting & translation (`LNPANDY/NX2Apple`, `Wine`, `Proton`, `DXVK`, `vkd3d-proton`, `Box64`, `FEX-Emu`), flagship open-source emulators (`Dolphin`, `PCSX2`, `RPCS3`, `PPSSPP`, `melonDS`, `MAME`, `ScummVM`, `Flycast`, `Xemu`), retro OS distributions (`Batocera.linux`, `Recalbox`, `RetroPie`, `Lakka`), and self-hosted game streaming (`Sunshine`, `Moonlight`, `RomM`) — ideal for game preservationists and cross-platform porting developers.

🤝 Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📑 Table of Contents
- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS/Hosted & Commercial Platforms](#️-saashosted--commercial-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#️-how-to-contribute)
- [⚠️ Disclaimer](#️-disclaimer)
- [💖 Support & Thank You](#-support--thank-you)

## 📊 Sector Overview & Market Dynamics

The global Cloud Gaming, Retro Emulation & Cross-Platform Game Porting market is valued at approximately **$9.5B–$12.8B+ in 2026**, expanding at a ~20%–26% CAGR propelled by handheld Linux/ARM gaming PCs (Steam Deck, ROG Ally), Apple Silicon native/translation gaming, and official retro preservation storefronts. The commercial cloud-streaming layer exhibits **strong winner-take-most consolidation** around NVIDIA GeForce NOW, Xbox Cloud Gaming, and European leaders like Boosteroid and Shadow PC, whereas the emulation, OS-distro, and binary-translation layers are **overwhelmingly powered by open-source community projects** (`RetroArch`, `Wine/Proton`, `DXVK`, `Box64`, `Batocera`, `Sunshine/Moonlight`).

## ☁️ SaaS/Hosted & Commercial Platforms

*Sorted descending by company valuation / annual revenue scale.*

| Platform | Description | Company Scale (Valuation / Revenue) | Starting Paid Tier | Free Tier / Trial Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[GeForce NOW (NVIDIA)](https://nvidia.com)** | Cloud RTX game-streaming platform running PC libraries from Steam, Epic, Xbox, and GOG on low-power laptops, macOS, Linux, and handhelds. | **Part of NVIDIA Corp.** (~$130B+ annual revenue; ~$3T+ market cap) | **$9.99 / month** ($49.99/6 mos Performance) or **$19.99 / month** ($99.99/6 mos Ultimate RTX 4080/5080) | **Forever Free Basic Tier** (Ad-supported **1-hour session limit** with standard queue access and basic cloud rig) |
| **[Shadow PC (OVHcloud / Octave Klaba)](https://shadow.tech)** | Full cloud Windows 11 gaming and workstation PC streamed at low latency to macOS, Linux, Android, iOS, and smart TVs for running any emulator or PC game. | **Backed by Octave Klaba / OVHcloud** (~€1B+ OVHcloud group revenue) | **$19.99 / month** (Discovery tier) or **$32.99 – $49.99 / month** (Boost / Power RTX GPU tiers) | **No Perpetual Free Tier** (Occasional promo discount first-month trials; full Windows cloud VM requires active monthly subscription) |
| **[Boosteroid](https://boosteroid.com)** | Leading European independent cloud gaming platform streaming AAA and indie PC titles at up to 4K/120fps across browsers, Linux, macOS, and TVs. | **~$100M–$200M Est. Valuation** (~$20M–$40M est. ARR; rapid EU/US server expansion) | **€7.49 / month** billed annually (€89.89/yr) or **€9.89 / month** monthly for Ultra 4K | **No Perpetual Free Tier** (Free account allows latency/bitrate connection testing before purchasing a monthly/annual pass) |
| **[Antstream Arcade](https://antstream.com)** | Official cloud retro-gaming platform streaming 1,300+ licensed arcade, Commodore, Amiga, SNES, and PlayStation classics with cloud saves and tournaments. | **~$30M–$50M Est. Valuation** (~$5M–$10M est. ARR; $20M+ VC funding) | **$3.99 / month** ($39.99/yr annual subscription) or **$99.99 one-time** Lifetime pass | **Forever Free Ad-Supported Tier** (Free retro game play supported by pre-roll ads and tournament gems; 7-day full trial on select platforms) |
| **[Utomik](https://utomik.com)** | Subscription cloud and fast-chunked-download PC/retro gaming platform curating 1,400+ indie, classic, and family titles on PC and smart TVs. | **~$15M–$30M Est. Valuation** (~$5M+ est. ARR; Dutch cloud-gaming company) | **$8.99 / month** for PC plan or **$11.99 / month** for PC + Cloud TV plan | **14-Day Free Trial** (Unlimited access to the 1,400+ game catalog during the 14-day evaluation period; no perpetual free tier) |
| **[LaunchBox / Big Box (Unbroken Software)](https://launchbox-app.com)** | Premier Windows/Android retro-game launcher, metadata scraper, and 10-foot arcade cabinet frontend ("Big Box") integrating RetroArch and standalone emulators. | **~$5M–$15M Est. Scale** (Profitable independent US retro-gaming software company) | **$30 / year** (1-year updates) or **$75 one-time** Forever Updates license for Big Box mode | **Forever Free LaunchBox Desktop** (100% free desktop game library organizer, emulator launcher, and metadata/box-art scraper forever) |
| **[RetroArch (Libretro Cloud / Store Ecosystem)](https://retroarch.com)** | Cross-platform frontend for the Libretro API running hundreds of open-source emulator cores with netplay, shaders, and Steam/App Store cloud saves. | **Non-Profit / Community Open-Source Project** (Patreon & bounty funded) | **$0 / Free Open-Source** (Optional Patreon tiers for buildbot infrastructure support) | **100% Free Forever** (Available free across Windows, macOS, Linux, iOS/tvOS App Store, Android, Steam, and consoles) |
| **[Playnite (Hosted Addon & Metadata Ecosystem)](https://playnite.link)** | Open-source unified PC and console-emulator library manager with hosted plugin/theme repositories and full-screen controller UI. | **Community Open-Source Project** (Maintained by Josef Nemec & contributors) | **$0 / Free Open-Source** (Optional Patreon sponsorship) | **100% Free Forever** (MIT-licensed unified launcher integrating Steam, Epic, GOG, Xbox, and 50+ emulators with zero ads) |
| **[Batocera.linux (Hosted OS & Content Ecosystem)](https://batocera.org)** | Plug-and-play retro-gaming Linux OS distribution with hosted theme/bezel repositories and zero-config support for x86_64, Raspberry Pi, and ARM handhelds. | **Community Open-Source Project** (Donation & OpenCollective funded) | **$0 / Free Open-Source** (100% free downloadable bootable OS images) | **100% Free Forever** (Unlimited USB/SD live-boot retro console OS with 150+ pre-configured emulators and shaders) |
| **[Recalbox (Commercial Hardware / RGB Dual Ecosystem)](https://recalbox.com)** | User-friendly open-source retro-gaming OS paired with official Recalbox RGB Dual CRT hardware adapters, pre-flashed kits, and Patreon early builds. | **~$2M–$5M Est. Scale** (French retro-gaming hardware & open-source software organization) | **$0 / Free OS** (Official Recalbox RGB Dual/JAMMA CRT hardware kits from **€39–€89**) | **100% Free Forever OS** (Free downloadable OS images for Raspberry Pi, PC, and handhelds with built-in Kodi and netplay) |

## 💻 Open-Source GitHub Projects

| Project | License / Hosting Cost | Free Tier / Self-Hosted Limit | Description |
| :--- | :--- | :--- | :--- |
