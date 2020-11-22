
[![macOS version](https://img.shields.io/badge/macOS-10.15.6%20(19G2021)-informational.svg)](https://www.apple.com/macos) [![OpenCore version](https://img.shields.io/badge/OpenCore-0.6.3-informational.svg)](https://github.com/acidanthera/OpenCorePkg) [![GitHub issues](https://img.shields.io/github/issues/MaximumQuiet/ryzentosh.svg)](https://github.com/MaximumQuiet/ryzentosh/issues/)

<img src="extra/catalina.png" width="150"/>

# Ryzentosh

Hackintosh EFI for AMD Ryzen 3700X &amp; XFX RX 5700XT.

## Hardware

| Type                 | Name                              |
|----------------------|-----------------------------------|
| CPU                  | Ryzen 3700X                       |
| MB                   | MSI X470 Gaming Pro Carbon        |
| Audio                | ALC1220                           |
| GPU                  | XFX Radeon RX 5700 XT THICC II    |
| RAM                  | 16G DDR4 (8G * 2)                 |
| Ethernet             | Intel I211-AT                     |
| Disk                 | Samsung 860 EVO 250 GB            |

## Patches & Kexts
 - [[Patch] AMD_Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)
 - [[Kext] VirtualSMC](https://github.com/acidanthera/VirtualSMC)
 - [[Kext] Lilu](https://github.com/acidanthera/Lilu)
 - [[Kext] WhateverGreen](https://github.com/acidanthera/WhateverGreen)
 - [[Kext] AppleALC](https://github.com/acidanthera/AppleALC)
 - [[Kext] AppleIntelMCEReporter](https://github.com/AMD-OSX/AMD_Vanilla/blob/master/Extra/AppleMCEReporterDisabler.kext.zip)
 - [[Kext] Intel-211-AT-PCEe-GBE](https://www.tonymacx86.com/threads/how-to-build-your-own-imac-pro-successful-build-extended-guide.229353/page-109#post-1618005)
 - [[Kext] USB-Map](https://github.com/dortania/OpenCore-Post-Install/blob/master/extra-files/Sample-USB-Map.kext.zip)
 - [Kext] RadeonBoost

## Functional

- [x] CPU by [AMD-Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)
- [x] Audio by [AppleALC](https://github.com/acidanthera/AppleALC) (alcid=5)
- [x] Graphics by [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [x] USB
- [x] Docker (Docker Toolbox only)
- [x] iMessage / FaceTime / iCloud
- [x] FileVault
- [x] Sleep
- [x] Supplementary updates (update your OpenCore EFI, kexts and patches first!)
 
## Resources
- https://vanilla.amd-osx.com/
- https://forum.amd-osx.com/
- https://github.com/AMD-OSX/AMD_Vanilla
- https://dortania.github.io/OpenCore-Desktop-Guide 
