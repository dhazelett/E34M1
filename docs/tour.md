---
title: Visual Tour
summary: E34M1 Modules Tour
authors: Jon Harper
date: 2023-1-26
---

## Overview

E34M1 replaces many of the printed parts from EVA 3, while maintaining compatibility with hotends and extruders. This tour introduces the E34M1 *and* everything else you need to print from EVA 3.

<div markdown class="jh-grid-container jh-grid-2">
<div markdown class="jh-card">

**Core E34M1 Assembly**
<figure markdown>
![core](img/tour/core.png){width="300px"}
</figure>
</div>
<div markdown class="jh-card">
**Complete Assembly**
<figure markdown>
![complete](img/tour/master.png){width="300px"}
</figure>
</div>
</div>

## Core Modules

Each E34M1 module comes in multiple varations. These parts are all specific to E34M1.

<div markdown class="jh-grid-container jh-grid-2">
<div markdown class="jh-card">

**Front**

The Front mounts the hotend, belts, and the front of the Drive module.

<figure markdown>
![front](img/tour/front.png){width="300px"}

[Front Module Reference](modules/front.md){.md-button}
</figure>

</div>
<div markdown class="jh-card">

**Top**

The top mounts the MGN12H carriage, the X axis endstop, and the back of the Drive module. It has an optional attachment point for an umbilical cable guide.

<figure markdown>
![top](img/tour/top.png){width="300px"}

[Top Module Reference](modules/top.md){.md-button}
</figure>

<div markdown class="jh-grid-container jh-grid-1 jh-link-grid">
</div>
</div>
<div markdown class="jh-card">

**Bottom Horns**

The bottom horns are primarily for part cooling and form the lower joint between the Front and Rear Inlet. Some ABL methods (e.g., Beacon, Klicky) mount here.

<figure markdown>
![bottom](img/tour/bottom.png){width="300px"}

[Bottom Horns Reference](modules/bottom.md){.md-button}
</figure>
</div>
<div markdown class="jh-card">

**Rear Inlet**

Stock EVA 3 has a rear piece here that acts as a belt tensioner. It's unneeded for Mercury One printers, so we moved the cooling inlet forward to save space.

<figure markdown>
![inlet](img/tour/inlet.png){width="300px"}

[Rear Inlet Reference](modules/rear.md){.md-button}
</figure>
</div>
</div>

## Extruder, Hotends, and Shrouds

These modules have not changed in how they join with other parts. This keeps third party mods compatible while allowing us to make small improvements and fixes to the existing options.

We've assembled lists of known hotend and drive mounts.

<div markdown class="jh-grid-container jh-grid-2">
<div markdown class="jh-card">

**Hotend**

The hotend module mounts the hotend, cooling fan, and an optional shroud.

<figure markdown>
![hotend](img/tour/hotend.png){width="300px"}

[Explore EVA 3 Hotends](compat/hotends.md){.md-button}
</figure>

</div>
<div markdown class="jh-card">

**Drive/Extruder**

The drive module attaches the extruder and extruder stepper to the toolhead.

<figure markdown>
![drive](img/tour/drive.png){width="300px"}

[Explore EVA 3 Extruders](compat/drives.md){.md-button}
</figure>

</div>
<div markdown class="jh-card">

**Shroud**

All stock shrouds are compatible with E34M1.

<figure markdown>
![shroud](img/tour/shroud.png){width="300px"}

[Stock EVA 3 Shrouds](https://main.eva-3d.page/heat_insert/shrouds/chonkier/){.md-button}

[cuiviemen's Chonky Shrouds with LED Lighting](https://www.printables.com/model/420929-eva-30-chonky-shrouds-with-led-lighting){.md-button}

</figure>

</div>
</div>

## Other E34M1 Components

<div markdown class="jh-grid-container jh-grid-2">
<div markdown class="jh-card">

**ABL Side Mount**

The side ABL mount is modified from stock EVA. Most ABL methods mount here (e.g., BLTouch and CR Touch).

<figure markdown>
![abl mount](img/tour/abl.png){width="300px"}

[ABL Side Mount Reference](modules/abl.md){.md-button}
</figure>
</div>
</div>

E34M1 provides several other components that may be useful:

| Component                     | Purpose |
|-------------------------------|---------|
| [Front Intake Duct](modules/other.md#front-intake-duct) | Allows hotend cooling fans to be removed with two (2) screws. |
| [X Axis Stop Block](modules/stop_block.md) | Bumper for the X axis endstop. |
| [Z Limit Switch Mount](modules/other.md#z-endstop-mount) | Raises the Z endstop for Ender 5 Pro printers. |
| [Toolhead PCB Mounts](modules/pcb_mounts.md) | Mounts for '36 and '42 PCBs for NEMA17 steppers and shrouds to cover them. |

## Additional Mods

These are related mods not linked elsewhere that may be useful for your build.

| Mod Name | Author | Purpose |
|----------|--------|---------|
| [Klicky Probe Dock for Mercury 1 Zero G](https://www.printables.com/model/386819-klicky-probe-dock-for-mercury-1-zero-g) | [Sir_Wash](https://www.printables.com/social/415185-sir_wash) | Adds a dock for Klicky; works with `klicky_bottom.stl`. |

### Filament Sensors

Multi-material printing often requires a filament sensor at the toolhead. There are two known third-party mods for this using different detection methods.

- [Inductive Sensor](https://www.printables.com/model/239026-eva-3-toolhead-sensor) by [Dutchwoody](https://www.printables.com/@Dutchwoody)
- [Microswitch and Ball Bearing](https://www.printables.com/model/442650-eva-3-toolhead-sensor-mechanical-and-reliable) by [Guy](https://www.printables.com/@Guy_258839)