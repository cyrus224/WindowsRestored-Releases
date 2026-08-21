<p align="center">
  <img src="assets/windows-restored.png" width="112" alt="Windows Restored icon">
</p>

<h1 align="center">Windows Restored</h1>

<p align="center"><em>…or, “stop removing my damn features!”</em></p>

<p align="center">
  A lightweight Windows 11 utility that puts useful classic tools and buried settings back within easy reach.
</p>

<p align="center">
  <img alt="Platform: Windows 11" src="https://img.shields.io/badge/platform-Windows%2011-1674D1">
  <img alt="Status: early development" src="https://img.shields.io/badge/status-early%20development-E9A23B">
  <img alt="Runtime: .NET" src="https://img.shields.io/badge/built%20with-.NET-512BD4">
</p>

## Why Windows Restored?

Windows still includes many capable, familiar control panels and administrative tools—but each Windows release seems to bury another shortcut, redirect another link, or replace a useful desktop interface with a thinner Settings page.

Windows Restored provides one clear, searchable home for those tools. It opens the Windows features already on your computer instead of trying to recreate them, replace Explorer, or redesign the desktop.

## Highlights

- **Classic Windows destinations** — Quickly open legacy sound, network adapter, power, hardware, programs, account, system, and maintenance interfaces.
- **Favourites home page** — Keep your most-used destinations immediately available.
- **Custom tray menu** — Add only the shortcuts you want, arrange them with drag and drop, create separators, and organize nested submenus.
- **Helpful explanations** — Understand what a tool does, whether it needs elevation, and how much impact it can have before opening it.
- **Safe by default** — Advanced and high-impact entries are hidden until explicitly enabled.
- **Per-action elevation** — The main application runs normally; Windows requests administrator permission only for the individual action that requires it.
- **Windows-aware availability** — Missing, removed, or redirected tools are detected instead of blindly launched.
- **Desktop-first interface** — Compact mouse-and-keyboard design with System, Light, and Dark themes.
- **Reliable startup option** — Optional delayed startup uses a verified per-user scheduled task and can repair its own configuration.
- **Configurable close behavior** — Closing the window can minimize to the notification area or exit completely.

## What it does not do

Windows Restored is not a shell replacement, visual patcher, debloater, or blanket “tweak everything” utility. It does not patch Explorer, replace the taskbar or Start menu, or interfere with tools such as ExplorerPatcher, StartAllBack, or PowerToys.

The goal is straightforward: restore convenient access to your own computer while staying additive, understandable, and reversible.

## Availability

> [!IMPORTANT]
> Windows Restored is in active early development. There is not yet a public installer or portable release.

When the first build is ready, downloads and release notes will appear on this repository’s [Releases page](https://github.com/cyrus224/WindowsRestored-Releases/releases). The application is designed for **Windows 11** and will explain rather than run on unsupported Windows 10 systems.

## Coming next

- Optional Explorer context submenu, including elevated **Open here** terminal commands
- PowerShell 7 and Windows Terminal detection and guidance
- Per-user installer
- Proper in-app update checks, verified downloads, install-and-restart, and rollback
- Carefully reviewed reversible settings for options Windows exposes only through difficult interfaces
- Continued research into useful Windows features that have been buried or redirected

## Updates and safety

Future updates will be handled inside the application rather than sending users through a manual download loop. Update packages will be checked against signed metadata and cryptographic hashes before installation, with rollback if a new version cannot start successfully.

Windows Restored runs unelevated during ordinary use and never embeds GitHub credentials. Individual Windows tools may still display their normal UAC prompt when administrator rights are genuinely required.

---

Windows Restored is an independent project and is not affiliated with or endorsed by Microsoft. Windows is a trademark of the Microsoft group of companies.