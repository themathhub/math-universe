<div align = center>

<img width = 300 src = docs/Logo-light.png#gh-dark-mode-only>
<img width = 300 src = docs/Logo.png#gh-light-mode-only> 
 
<br>
<br>

[![Badge License]][License]

Self-hosted **Javascript** emulation for various system.

<br>

[![Button Website]][Website] 
[![Button Usage]][Usage]<br>
[![Button Configurator]][Configurator]<br>
[![Button Demo]][Demo] 
[![Button Legacy]][Legacy]

[![Button Contributors]][Contributors]

Join our Discord server:

[![Join our Discord server!](https://invite.casperiv.dev/?inviteCode=6akryGkETU&format=svg)](https://discord.gg/t8fnbYRjdj)

</div>

<br>

**As of EmulatorJS version 4.0, this project is no longer a reverse-engineered version of the emulatorjs.com project. It is now a complete re-write,**

<br>

**README BEFORE YOU UPDATE:** EmulatorJS Version 4.0 is a complete re-write of the application. At least some bugs are expected. If you did any communicating with the emulator, there is a 100% chance you will need to re-write your project, and to people with active branches of this project, I wish you luck with merge conflicts (I'm very sorry). The emulator object can be accessed through the `window.EJS_emulator` object.

It is **HIGHLY** suggested that you update to 4.0 ASAP.

<br>

### Ads

_This project has no ads._ <br>
_Although, the demo page currently has an ad to help fund this project._ <br>
_Ads on the demo page may come and go depending on how many people are_ <br>
_funding this project._ <br>

_You can help fund this project on_ **_[patreon]_**

<br>

### Issues

_If something doesn't work, please consider opening an_ **_[Issue]_** <br>
_with as many details as possible, as well as the console log._

<br>

### Extensions

**[GameLibrary]**

_A library overview for your **ROM** folder._

<br>

### Development:

_Run a local server with:_

```
npm i
npm start
```

<br>

**>> When reporting bugs, please specify that you are using the old version**

<br>
<br>
<br>

<h1 align = center>Supported Systems</h1>

<br>

<div align = center>

### Nintendo

**[Game Boy Advance][Nintendo Game Boy Advance]**   | 
**[Famicom / NES][NES / Famicom]**   | 
**[Virtual Boy][Virtual Boy]**

**[Game Boy][Nintendo Game Boy]**   | 
**[SNES]**   | 
**[DS][Nintendo DS]**   | 
**[64][Nintendo 64]**

<br>
<br>

### Sega

**[Master System][Sega Master System]**   | 
**[Mega Drive][Sega Mega Drive]**   | 
**[Game Gear][Sega Game Gear]**

**[Saturn][Sega Saturn]**   | 
**[32X][Sega 32X]**   | 
**[CD][Sega CD]**

<br>
<br>

### Atari

**[2600][Atari 2600]**   | 
**[5200][Atari 5200]**   | 
**[7800][Atari 7800]**   | 
**[Lynx][Atari Lynx]**   | 
**[Jaguar][Atari Jaguar]**

<br>
<br>

### Other

**[PlayStation]**   | 
**[Arcade]**   | 
**[3DO]**   | 
**[MAME 2003]**

</div>

<br>

**_PSP is not yet supported_**. Some of y'all may have seen that I pushed a "beta" ppsspp core, but this core is not ready for daily use. It still crashes randomly and any games that use 3d (so like, all of them) will just have a white screen (and might just crash). Do not open issues related to the "psp" core.

<!-- 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 --->

[License]: LICENSE
[Issue]: https://github.com/ethanaobrien/emulatorjs/issues
[patreon]: https://patreon.com/EmulatorJS

<!-- 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮   Extensions   🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 --->

[GameLibrary]: https://github.com/Ramaerel/emulatorjs-GameLibrary

<!-- 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮   Quicklinks   🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 --->

[Configurator]: https://emulatorjs.org/editor.html
[Contributors]: docs/Contributors.md
[Website]: https://emulatorjs.org/
[Legacy]: https://coldcast.org/games/1/Super-Mario-Bros
[Usage]: https://emulatorjs.org/docs/
[Demo]: https://demo.emulatorjs.org/

<!-- 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮  Systems  🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 -->

[Nintendo Game Boy Advance]: docs/Systems/Nintendo%20Game%20Boy%20Advance.md
[Nintendo Game Boy]: docs/Systems/Nintendo%20Game%20Boy.md
[Nintendo 64]: docs/Systems/Nintendo%2064.md
[Nintendo DS]: docs/Systems/Nintendo%20DS.md
[Sega Master System]: docs/Systems/Sega%20Master%20System.md
[Sega Mega Drive]: docs/Systems/Sega%20Mega%20Drive.md
[Sega Game Gear]: docs/Systems/Sega%20Game%20Gear.md
[Sega Saturn]: docs/Systems/Sega%20Saturn.md
[Sega 32X]: docs/Systems/Sega%2032X.md
[Sega CD]: docs/Systems/Sega%20CD.md
[Atari Jaguar]: docs/Systems/Atari%20Jaguar.md
[Atari Lynx]: docs/Systems/Atari%20Lynx.md
[Atari 7800]: docs/Systems/Atari%207800.md
[Atari 2600]: docs/Systems/Atari%202600.md
[Atari 5200]: docs/Systems/Atari%205200.md
[NES / Famicom]: docs/Systems/NES-Famicom.md
[SNES]: docs/Systems/SNES.md
[TurboGrafs-16 / PC Engine]: docs/Systems/TurboGrafs%2016-PC%20Engine.md
[WanderSwan / Color]: docs/Systems/WanderSwan-Color.md
[Neo Geo Poket]: docs/Systems/Neo%20Geo%20Poket.md
[PlayStation]: docs/Systems/PlayStation.md
[Virtual Boy]: docs/Systems/Virtual%20Boy.md
[Arcade]: docs/Systems/Arcade.md
[MSX]: docs/Systems/MSX.md
[3DO]: docs/Systems/3DO.md
[MAME 2003]: docs/Systems/MAME%202003.md

<!-- 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮  Badges  🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 🎮 --->

[Badge License]: https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge
[Button Configurator]: https://img.shields.io/badge/Configurator-992cb3?style=for-the-badge
[Button Contributors]: https://img.shields.io/badge/Contributors-54b7dd?style=for-the-badge
[Button Website]: https://img.shields.io/badge/Website-736e9b?style=for-the-badge
[Button Legacy]: https://img.shields.io/badge/Legacy-ab910b?style=for-the-badge
[Button Usage]: https://img.shields.io/badge/Usage-2478b5?style=for-the-badge
[Button Demo]: https://img.shields.io/badge/Demo-528116?style=for-the-badge
[Button Beta]: https://img.shields.io/badge/Beta-bb044f?style=for-the-badge
