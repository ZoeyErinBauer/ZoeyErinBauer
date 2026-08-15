# Hi, I'm Zoey 👋

I'm building [Shelly](https://github.com/Seafoam-Labs/Shelly-ALPM), a modern package-management experience for Arch Linux and CachyOS. My work at [Seafoam Labs](https://github.com/Seafoam-Labs) focuses on making Linux more accessible without hiding how it works.

## What I'm working on

### [Shelly](https://github.com/Seafoam-Labs/Shelly-ALPM)

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

### [Devario](https://www.seafoam-labs.org/devario/)

A managed Linux workstation platform for small-business fleets. Devario uses Shelly as its trusted package transaction boundary, pairing it with Remora software policy, an Aqueous desktop, and Windows-connected identity.

The current focus is completing the installer-led domain-login path, hardening release and repository operations, and preparing measurable mixed-fleet pilots.

### [Aqueous](https://github.com/Seafoam-Labs/Aqueous)

A visually expressive Wayland compositor and tiling window manager written in Zig. Aqueous keeps layouts, rules, input, workspaces, multi-monitor policy, animation, and Vulkan effects together in one process—with performance costs explicit and optional.

### [Atoll](https://github.com/Seafoam-Labs/Atoll)

A .NET service for mirroring Arch User Repository metadata, tracking package history, and providing fast package search and Git Smart HTTP access. It uses MongoDB for authoritative storage and OpenTelemetry for operational visibility.

## More from Seafoam Labs

- [Conch](https://github.com/Seafoam-Labs/conch) — StatusNotifierItem and desktop notification support for Zig over D-Bus
- [Pori](https://github.com/Seafoam-Labs/Pori) — a GTK4 systemd mount manager for Linux
- [Starfish](https://github.com/Seafoam-Labs/Starfish) — an interactive Arch Linux package dependency visualizer
- [Seafoam Labs website](https://github.com/Seafoam-Labs/website) — project documentation and news built with Astro and Starlight

## Technologies

`Zig` · `C# / .NET` · `GTK4` · `Wayland / wlroots` · `Vulkan` · `Arch Linux` · `CachyOS` · `libalpm` · `D-Bus` · `MongoDB` · `OpenTelemetry` · `Astro` · `TypeScript`

---

[Seafoam Labs](https://www.seafoam-labs.org/) · [GitHub organization](https://github.com/Seafoam-Labs)
