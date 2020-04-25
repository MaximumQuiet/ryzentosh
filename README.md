# Hackintosh EFI for Ryzen 3700X &amp; XFX RX 5700XT

![Screenshot](/images/about.png)

## OS info
**macOS version**: 10.15.4 (19E287)
**Bootloader**: [OpenCore](https://github.com/acidanthera/OpenCorePkg) 0.5.7

## Hardware info

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
 - [[Kext] NullCPUPowerManagement](https://www.tonymacx86.com/resources/nullcpupowermanagement.268/)  
 - [[Kext] Intel-211-AT-PCEe-GBE.kext](https://www.tonymacx86.com/threads/how-to-build-your-own-imac-pro-successful-build-extended-guide.229353/page-109#post-1618005)

## Functional

- [x] CPU by [AMD-Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)
- [x] Audio by [AppleALC](https://github.com/acidanthera/AppleALC) (alcid=5)
- [x] Graphics by [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [x] USB
- [x] Docker (Docker Toolbox only)
- [x] iMessage / FaceTime / Airdrop / Handoff / iCloud (**You cant't use serial, SMBIOS, etc from this repository, it must be unique for every macOS installation!**)
- [x] FileVault
- [x] Supplementary updates (update your OpenCore EFI, kexts and patches first!)
 
## Problems
See [issues](https://github.com/MaximumQuiet/ryzentosh/issues)

## Resources
- https://vanilla.amd-osx.com/
- https://forum.amd-osx.com/
- https://github.com/AMD-OSX/AMD_Vanilla
- https://dortania.github.io/OpenCore-Desktop-Guide 
