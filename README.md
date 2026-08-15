# Hi, I'm Zoey 👋

I'm the lead dev for [Shelly](https://github.com/Seafoam-Labs/Shelly-ALPM), a modern package-management experience for Arch Linux and CachyOS. My work at [Seafoam Labs](https://github.com/Seafoam-Labs) focuses on making Linux more accessible without hiding how it works.

<p align="center">
  <a href="https://github.com/Seafoam-Labs/Shelly-ALPM">
    <img src="https://raw.githubusercontent.com/Seafoam-Labs/website/main/src/assets/images/chel.png" alt="Chel, the Shelly mascot" width="360">
  </a>
</p>

## What I'm working on

### [Shelly](https://github.com/Seafoam-Labs/Shelly-ALPM)

[![Build](https://github.com/Seafoam-Labs/Shelly-ALPM/actions/workflows/build-and-publish.yml/badge.svg?branch=master)](https://github.com/Seafoam-Labs/Shelly-ALPM/actions/workflows/build-and-publish.yml)
[![Latest release](https://img.shields.io/github/v/release/Seafoam-Labs/Shelly-ALPM?label=release)](https://github.com/Seafoam-Labs/Shelly-ALPM/releases/latest)
[![License: GPL-3.0](https://img.shields.io/github/license/Seafoam-Labs/Shelly-ALPM)](https://github.com/Seafoam-Labs/Shelly-ALPM/blob/development/LICENSE)
[![AUR](https://img.shields.io/aur/version/shelly?label=AUR)](https://aur.archlinux.org/packages/shelly)
[![CachyOS](https://img.shields.io/badge/CachyOS-repository-00a9e0)](https://github.com/Seafoam-Labs/Shelly-ALPM#quick-install)

[**Install**](https://github.com/Seafoam-Labs/Shelly-ALPM#quick-install) · [**Documentation**](https://www.seafoam-labs.org/shelly-alpm/) · [**Report an issue**](https://github.com/Seafoam-Labs/Shelly-ALPM/issues/new/choose) · [**Contribute**](https://github.com/Seafoam-Labs/Shelly-ALPM/blob/development/CONTRIBUTING.md)

Shelly is a modern package manager for Arch Linux, written primarily in Zig and backed directly by `libalpm`. It rethinks how people discover, install, update, and manage software while remaining native to the Arch ecosystem.

It brings several software sources and interaction styles into one cohesive system:

- Native package operations through `libalpm`
- AUR discovery, dependency resolution, building, and installation
- A GTK4 desktop application for visual package management
- A fast CLI and terminal interface for interactive use and automation
- Optional Flatpak integration without making Flatpak a base dependency
- AppImage support, repository management, updates, notifications, and cache maintenance
- Shared package-management components designed for reuse by other applications

Recent work has focused on replacing the remaining `makepkg`-style build path with Shelly's own builder and archiver, expanding the terminal UI, strengthening PKGBUILD parsing, and improving the reliability of upgrades and failed builds.

Shelly is available through CachyOS and the AUR:

```bash
sudo pacman -S shelly
```

## Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Seafoam-Labs/Shelly-ALPM">🐚 Shelly</a></h3>
      Modern package management for Arch Linux and CachyOS, with native GTK and terminal interfaces.
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Seafoam-Labs/Aqueous">🌊 Aqueous</a></h3>
      A visually expressive Wayland compositor and tiling window manager written in Zig.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Seafoam-Labs/Atoll">🪸 Atoll</a></h3>
      A .NET service for AUR metadata mirroring, package history, fast search, and Git Smart HTTP access.
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://www.seafoam-labs.org/devario/">🐟 Devario</a></h3>
      A managed Linux workstation platform combining Remora policy, Shelly transactions, Aqueous desktops, and Windows-connected identity.
    </td>
  </tr>
</table>

## More from Seafoam Labs

- [Conch](https://github.com/Seafoam-Labs/conch) — StatusNotifierItem and desktop notification support for Zig over D-Bus
- [Pori](https://github.com/Seafoam-Labs/Pori) — a GTK4 systemd mount manager for Linux
- [Starfish](https://github.com/Seafoam-Labs/Starfish) — an interactive Arch Linux package dependency visualizer
- [Seafoam Labs website](https://github.com/Seafoam-Labs/website) — project documentation and news built with Astro and Starlight

## Technologies

`Zig` · `C# / .NET` · `GTK4` · `Wayland / wlroots` · `Vulkan` · `Arch Linux` · `CachyOS` · `libalpm` · `D-Bus` · `MongoDB` · `OpenTelemetry` · `Astro` · `TypeScript`

## Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ZoeyErinBauer/ZoeyErinBauer/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ZoeyErinBauer/ZoeyErinBauer/output/github-contribution-grid-snake.svg">
  <img alt="Animated contribution graph" src="https://raw.githubusercontent.com/ZoeyErinBauer/ZoeyErinBauer/output/github-contribution-grid-snake.svg">
</picture>

---

[Seafoam Labs](https://www.seafoam-labs.org/) · [GitHub organization](https://github.com/Seafoam-Labs)
