# Urchin 🪸

![Showcase Picture](./gallery/case/coral/urchin-coral.jpg)

<span>
  <img src="https://img.shields.io/github/last-commit/duckyb/urchin?style=flat-square">
  <a href="https://github.com/duckyb/urchin/releases">
    <img src="https://img.shields.io/github/v/release/duckyb/urchin?include_prereleases&color=success&style=flat-square">
    <img src="https://img.shields.io/github/downloads/duckyb/urchin/total?color=success&style=flat-square">
  </a>
  <img src="https://img.shields.io/static/v1?label=license&message=MIT&color=success&style=flat-square">
  <br/>
  <a href="https://discord.gg/hAm5QVJrbU">
    <img src="https://img.shields.io/discord/669011382284451861?style=flat-square&logo=discord&logoColor=white&label=Urchin%20Chat&color=%235865f2">
  </a>
</span>

I created this design because I wanted to upgrade my [Sweep](https://github.com/davidphilipbarr/Sweep) with the fancy nice!view displays. I decided to use the edge design from the [Swoop](https://github.com/jimmerricks/swoop) and to make it compatible with Kailh hotswap sockets.
**This is a strictly wireless-only design, and is only compatible with ZMK / nice!nano. Only Choc v1 switches + Hotswap are supported!**

> Q: Why is this not just another Sweep?
> _A: In order to support the nice!view display I had to use a switch matrix with diodes instead of the Sweep's direct pin design. This means that the firmwares are not interchangeable. I also wanted to use a different PCB shape which makes it incompatible with Sweep cases._

**If you enjoy my work, please consider ⭐ starring and/or ❤ sponsoring it.**

## Sponsors

_Support the people that support me!_ 🙏🏻

<span class="sponsors">
  <a href="https://www.pcbway.com/">
    <img src="https://user-images.githubusercontent.com/27895007/201170595-901a4723-b910-418c-b273-a5c9987ad1c8.png" height="50"/>
  </a>
  <a href="https://shop.beekeeb.com/">
    <img src="https://user-images.githubusercontent.com/27895007/192096782-2ca086d8-54a3-42fd-a67b-0f1e25f1ffbc.png" height="50"/>
  </a>
</span>

## Features

- [x] Design fully optimized for wireless
- [x] Native nice!view support
- [x] Familiar Ferris/Sweep layout
- [x] Improved outline shape
- [x] Support for Kailh hotswap sockets
- [x] Mounting points for cases
- [x] 3D printable enclosure case
- [x] Switch Plate files (3 options)
- [x] MCU/Screen Cover files

## Part list (for a full keyboard)

#### Required

- 1× PCB Kit (files for it are in [releases](https://github.com/duckyb/urchin/releases))
- 34× Kailh **CHOC** Hotswap Sockets
- 34× Kailh Choc v1 Switches
- 34× Keycaps
- 34× SMD diodes (SOD-123)
- 2× nice!nano
- 2× Lipo battery (301230)
- 48× mill-max machined pins
- 2× Pair of female headers

#### Optional

- 2× nice!view
- 2× Reset switch (B3U-1000P(M))
- 2× Power switch (MSK 12C02)
- 10× adhesive silicone feet

#### Case (NEW!)

| Coral Case                                         | Description                                                                                                                                                                                             |
| -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Coral Case](gallery/case/coral/coral-render.png) | The official Coral case is available on [Makerworld](https://makerworld.com/en/models/1057239#profileId-1044921) (for free). Other cases can be found in this repository inside the `3d-prints` folder. |

> [!NOTE]  
> Installing a case, microcontroller cover, or screen acrylic cover will require additional M2 hardware not included in this list. (Like screws, standoffs, nuts, heat set inserts)

## How do I make this?

<a href="https://youtu.be/CHSh1-dJq24" target="_blank">
<img src="https://gist.githubusercontent.com/duckyb/337340baa1f0c8bcc06fef7b3b57242b/raw/97e6e0748dd1b8a3fb54fac0a88e84e6b6e0e10a/build-guide-button.svg" height="44">
</a>

## Firmware

Urchin supports ZMK only. To get started with ZMK visit the [zmk-urchin repository](https://github.com/duckyb/zmk-urchin) and follow the provided instructions.

## More videos about Urchin

- https://www.youtube.com/watch?v=o2W_uG-OBjk

## Credits

- PCB edge design by [jimmerricks](https://github.com/jimmerricks/swoop)
- Coral, rocks, sand & bubbles by [Kneecrust](https://linktr.ee/kneecrust)
- The development name "Swipe Light" by [Pete](https://github.com/petejohanson)
- Nice!view integration reference: [sadekbaroudi/sweep36](https://github.com/sadekbaroudi/sweep36)
- ZMK Firmware help by [Mabroum](https://github.com/AlaaSaadAbdo) & [Bravekarma](https://github.com/caksoylar)
- Silkscreen labels style: [bastardkb/dilemma](https://github.com/Bastardkb/Dilemma)
- 3d case by [iamDrakkir](https://github.com/iamDrakkir)
- 3d case by [chewiedies](https://www.printables.com/it/social/360738-chewiedies/about)
- 3d case by [carrefinho](https://github.com/carrefinho)
- Coral logo idea by exosr on discord
