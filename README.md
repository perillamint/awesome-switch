
## Awesome Switch [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome things related to Nintendo Switch hacking

* [Resources](#resources)
  * [Writeups](#writeups)
  * [Hardmod](#hardmod)
* [Exploits](#exploits)
  * [Bootrom](#bootrom)
  * [Webkit](#webkit)
* [Exploit payloads](#payloads)
  * [Fusée Gelée](#fusee-gelee)
  * [shofEL2](#shofel2)
* [CFW](#cfw)
* [Other OS](#other-os)
  * [Linux](#linux)

## Resources
### Writeups
* [ShofEL2, a Tegra X1 and Nintendo Switch exploit](https://fail0verflow.com/blog/2018/shofel2/)
* [Vulnerability Disclosure: Fusée Gelée](https://misc.ktemkin.com/fusee_gelee_nvidia.pdf)
* [FAQ: Fusée Gelée](http://www.ktemkin.com/faq-fusee-gelee/)

### Hardmod
* [How to mod Joy-con to haxcon](https://imgur.com/gallery/it5eZvO)
* [SwitchX Pro (3D print jig by F0F)](https://github.com/fail0verflow/shofel2/tree/master/rcm-jig)
* [3D printt jig with paperclip](https://www.thingiverse.com/thing:2877484)
* [The ultimate list of mods to enter RCM](https://gbatemp.net/threads/the-ultimate-list-of-mods-to-enter-rcm.502145/)

## Exploits
### Bootrom
* [Fusée Gelée](https://github.com/reswitched/fusee-launcher)
* [shofEL2](https://github.com/fail0verflow/shofel2)

### Webkit
* [PegaSwitch](https://github.com/reswitched/pegaswitch)

## Exploit payloads
### Fusée Gelée
* [Example payload](https://github.com/ktemkin/Atmosphere/tree/poc_nvidia) ([precompiled](http://misc.ktemkin.com/fusee.bin))
* [Moonflower](https://github.com/moriczgergo/moonflower) (eMMC dumper)
* [BIS key dumper](https://github.com/rajkosto/biskeydump)

### shofEL2
* [cbfs](https://github.com/fail0verflow/shofel2/tree/master/exploit)

## CFW
* [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere/)

## Other OS
### Linux
* [coreboot](https://github.com/fail0verflow/switch-coreboot)
* [f0f's u-boot](https://github.com/fail0verflow/switch-u-boot)
* [shinyquagsire23's u-boot](https://github.com/shinyquagsire23/u-boot)
* [switch-linux](https://github.com/fail0verflow/switch-linux/)

#### Linux patches
* [perillamint's SDHCI bus speed fix](https://github.com/perillamint/switch-linux/tree/sdhci-bus-fix)

#### Linux tips
* [How to dump Switch eMMC using Linux](https://gbatemp.net/threads/tutorial-how-to-dump-switch-nand-using-linux.502201/)
* [udev rule for touchscreen conversion matrix](https://github.com/fail0verflow/shofel2/blob/master/configs/switch-ts-calibration.rules) (Copy this into `/etc/udev/rules.d/` when your touchscreen acts in rotated way)
