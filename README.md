# OpenCore-HP-800G1-DM-HD4600

HP 800G1 DM with HD4600‘s OpenCore for MacOS 11
(为什么是 11 因为 12 系统 HD4600 有显示毛边问题，老老实实呆在 11 养老吧)

## OC information

- OC Version: 0.7.9
- Tested OS Version: 11.6.5 (20G527)

## Tested

- 2K screen resolution
- Double screen (resolution: 3440\*1440@60Hz + 1920\*1080@120Hz)
- Sleep

## Not working

- Unknow

## Before installation

### star this project >w<

### Edit config.plist

**At first, please complete the 'PlatformInfo' use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS).**

- PlatformInfo>Generic>MLB
- PlatformInfo>Generic>ROM
- PlatformInfo>Generic>SystemSerialNumber
- PlatformInfo>Generic>SystemUUID

### BIOS Settings

#### Disable

- Fast Boot -> Disabled
- Secure Boot -> Disabled
- Security -> VTd -> Disabled

#### Set

- Storage -> Storage Options -> SATA Emulation > AHCI

## Kext information

| Name                                                                | Version |                                                                                                          |
| ------------------------------------------------------------------- | ------- | -------------------------------------------------------------------------------------------------------- |
| [Lilu](https://github.com/acidanthera/Lilu)                         | 1.6.0   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/Lilu)             |
| [VirtualSMC](https://github.com/acidanthera/VirtualSMC)             | 1.2.9   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/VirtualSMC)       |
| [WhateverGreen](https://github.com/acidanthera/WhateverGreen)       | 1.5.8   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/WhateverGreen)    |
| [AppleALC](https://github.com/acidanthera/AppleALC)                 | 1.7.0   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/AppleALC)         |
| [AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup) | 2.1.4   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/AirportBrcmFixup) |
| [BrcmPatchRAM](https://github.com/acidanthera/BrcmPatchRAM)         | 2.6.1   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/BrcmPatchRAM)     |
| [IntelMausi](https://github.com/acidanthera/IntelMausi)             | 1.0.7   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/IntelMausi)       |
| [NVMeFix](https://github.com/acidanthera/NVMeFix)                   | 1.0.9   | ![GitHub release (latest by date)](https://img.shields.io/github/v/release/acidanthera/NVMeFix)          |
