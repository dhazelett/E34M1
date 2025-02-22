---
title: Front
summary: Components for the Front Module
authors: Jon Harper
date: 2023-4-5
---

There are two version of the front module:

- Stock Front: Mounts an ADXL345 input shaper (stock EVA 3)
- PIS Front: Mounts a FYSETC portable input shaper

## Stock Front

<div markdown class="jh-grid-container jh-grid-2">
<div markdown class="jh-grid-para">

**Description**

Modification of the stock EVA Front for Mercury One. This mounts an ADXL345 accelerometer.

[**Revision:**](#revision-history) v0.4

**Bill of Materials**

| Parts     | Qty |
|-----------|-----|
| [:material-printer-3d-nozzle: `stock_front.stl`][front]  | 1 |
| [:material-printer-3d-nozzle: `belt_grabber.stl`][belt_grabber] | 2 |
| M3-0.5 x 6mm SHCS  | 4    |
| M3-0.5 x 40mm SHCS | 4    |
| Heat Set Insert, M3x5x4   | 14   |
| *ADXL345*                 | *1*  |
| *M3-0.5 x 8mm SHCS*| *2*  |

</div>
<div markdown class="jh-grid-img">
![front_illustration](../img/parts/front_universal.png){ width=256px}
</div>
</div>

??? info "Heat Set Insert Locations"
    <div markdown class="jh-grid-container jh-grid-3">
    <div markdown class="jh-grid-img">
    ![illustration1](../img/inserts/front1.png){width=300}
    </div>
    <div markdown class="jh-grid-img">
    ![illustration2](../img/inserts/front2.png){width=300}
    </div>
    <div markdown class="jh-grid-img">
    ![illustration3](../img/inserts/front3.png){width=300}
    </div>
    </div>

## Portable Input Shaper Front

<div markdown class="jh-grid-container jh-grid-2">
<div markdown class="jh-grid-para">

**Description**

Slightly modified Front that mounts a FYSETC portable input shaper.

[**Revision:**](#revision-history) v0.4

**Bill of Materials**

| Parts     | Qty |
|-----------|-----|
| [:material-printer-3d-nozzle: `pis_front.stl`][front_pis]  | 1 |
| [:material-printer-3d-nozzle: `belt_grabber.stl`][belt_grabber] | 2 |
| M3-0.5 x 6mm SHCS         | 4 |
| Heat Set Insert, M3x5x4   | 16 |
| *FYSETC Portable Input Shaper* | *1* |
| *M3-0.5 x 8mm SHCS*       | *2* |

</div>
<div markdown class="jh-grid-img">
![front_illustration](../img/parts/front_universal_pis.png){ width=256px}
</div>
</div>

??? info "Heat Set Insert Locations"
    <div markdown class="jh-grid-container jh-grid-3">
    <div markdown class="jh-grid-img">
    ![illustration1](../img/inserts/front1.png){width=300}
    </div>
    <div markdown class="jh-grid-img">
    ![illustration2](../img/inserts/front2.png){width=300}
    </div>
    <div markdown class="jh-grid-img">
    ![illustration3](../img/inserts/front3.png){width=300}
    </div>
    <div markdown class="jh-grid-img">
    ![illustration_pis](../img/inserts/front_pis.png){width=300}
    </div>
    </div>

## Revision History

| Date | File | Version | Description |
|------|------|---------|-------------|
| 23/06/08 | `pis_front.stl`    | v0.4 | Tweaked belts & shaper mount. |
| 23/06/08 | `stock_front.stl`  | v0.4 | Tweaked belts. |
| 23/06/08 | `belt_grabber.stl` | v0.4 | Tweaked belts. |
| 23/05/13 | `pis_front.stl`    | v0.3 | Fix for shaper mount. |
| 23/04/24 | `belt_grabber.stl` | v0.2 | Better belt grip. |
| 23/04/25 | `pis_front.stl`    | v0.2 | Fixed belt angle. |
| 23/04/25 | `stock_front.stl`  | v0.2 | Fixed belt angle. |
| 23/01/24 | `pis_front.stl`    | v0.1 | Initial commit. |
| 23/01/10 | `stock_front.stl`  | v0.1 | Initial commit. |
| 23/01/10 | `belt_grabber.stl` | v0.1 | Initial commit. |