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
  <img alt="Latest release: 0.5.2" src="https://img.shields.io/badge/release-0.5.2-2EA44F">
  <img alt="Built with .NET" src="https://img.shields.io/badge/built%20with-.NET-512BD4">
</p>

## Download

Windows Restored 0.5.2 is available from the [Releases page](https://github.com/cyrus224/WindowsRestored-Releases/releases/latest):

- **Installer:** choose a current-user or all-users installation and configure recommended startup and automatic-update defaults.
- **Portable ZIP:** run it without installation. Preferences still remain per Windows account under `%LocalAppData%\WindowsRestored`.

Both packages are self-contained and do not require a separately installed .NET runtime. Windows Restored requires **Windows 11, build 22000 or newer**, on an x64-compatible PC.

> [!NOTE]
> The current installer is not yet Authenticode-signed, so Windows SmartScreen may show an unknown-publisher warning. Release assets include SHA-256 checksums, and in-app updates independently verify signed metadata, package size, and SHA-256 before installation.

## What Windows Restored does

Windows still includes many capable, familiar control panels and administrative tools—but each release seems to bury another shortcut, redirect another link, or replace a useful desktop interface with a thinner Settings page.

Windows Restored provides one searchable home for those tools. It opens Windows features already on your computer instead of recreating them, replacing Explorer, or redesigning the desktop.

Current features include:

- Fast access to classic sound, network adapter, power, hardware, program, account, system, and maintenance interfaces.
- Favourites as the home page, with search and category navigation.
- A configurable notification-area menu with drag-and-drop ordering, separators, and nested submenus.
- An optional Explorer submenu for CMD, Windows PowerShell, PowerShell 7, and Windows Terminal—including explicit **Open here as administrator** actions.
- System, Light, and Dark themes in a compact keyboard-and-mouse interface.
- Clear in-app explanations, availability information, elevation indicators, and impact classifications.
- Advanced/high-impact tools hidden until explicitly enabled.
- Per-action elevation: the main tray application normally runs without administrator privileges.
- Verified delayed startup through a per-user Scheduled Task, including configuration checks and repair.
- Configurable close-to-tray or exit behavior.
- Windows 11 feature-release support information and direct access to Windows Update.
- Manual and automatic application update checks.
- Signed update manifests, verified package downloads, **Install and restart**, startup health confirmation, and rollback to the previous version if activation fails.

## What it does not do

Windows Restored is not a shell replacement, visual patcher, debloater, or blanket “tweak everything” utility. It does not patch Explorer, replace the taskbar or Start menu, or interfere with tools such as ExplorerPatcher, StartAllBack, or PowerToys.

Explorer additions are optional, additive, empty by default, and work with both the Windows 11 menu and classic/“Show more options” menus.

## Updates

Automatic update checks can be disabled in Settings.

When an update is available, the app displays its version, approximate size, and release highlights. Nothing is installed until you select **Install and restart**. A separate offline helper performs the replacement after the main app closes and keeps the immediately previous installation available for rollback.

---

Windows Restored is an independent project and is not affiliated with or endorsed by Microsoft. Windows is a trademark of the Microsoft group of companies.
