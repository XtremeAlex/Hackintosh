<div align="center">
<img alt="logo_hakintosh" src="Asrock-H110M/i5-6600K/clover/macOS Catalina 10.15.7/_img/hackintosh-logo.jpg">
</div>

# Hackintosh

Configurazioni e guide per l'installazione di macOS su hardware non Apple (Hackintosh), con build documentate e riferimenti alle guide OpenCore.

## Info sul progetto

Questo repository raccoglie configurazioni EFI, note e riferimenti per costruire un Hackintosh, insieme ai link alle guide di riferimento della community.

## Guide

- [Asrock-H110M / i5-6600K / Clover / macOS Catalina 10.15.7](https://github.com/XtremeAlex/Hackintosh/tree/main/Asrock-H110M/i5-6600K/clover/macOS%20Catalina%2010.15.7)

### Guide OpenCore

- Creating USB installer: [link](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/)
- OpenCore configuration: [link](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html)
- Post-Install: [link](https://dortania.github.io/OpenCore-Post-Install/)
- Troubleshooting: [link](https://dortania.github.io/OpenCore-Post-Install/)
- ACPI patching: [link](https://dortania.github.io/Getting-Started-With-ACPI/)
- USB mapping: [link](https://dortania.github.io/OpenCore-Post-Install/usb/)

## Credits

**Software:**

- [[Bootloader] OpenCore](https://github.com/acidanthera/OpenCorePkg)
- [[Resources] Picker GUI](https://github.com/acidanthera/OcBinaryData/tree/master/Resources)
- [[Patch] AMD_Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)
- [[SSDT] EC-USBX-DESKTOP](https://github.com/dortania/Getting-Started-With-ACPI/blob/master/extra-files/compiled/SSDT-EC-USBX-DESKTOP.aml)
- [[SSDT] SLEEP-PTXH](./OC/ACPI/SSDT-SLEEP-PTXH.aml)
- [[Driver] OpenRuntime](https://github.com/acidanthera/OpenCorePkg)
- [[Driver] OpenCanopy](https://github.com/acidanthera/OpenCorePkg)
- [[Driver] OpenHfsPlus](https://github.com/acidanthera/OpenCorePkg)
- [[Kext] Lilu](https://github.com/acidanthera/Lilu)
- [[Kext] VirtualSMC](https://github.com/acidanthera/VirtualSMC)
- [[Kext] WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [[Kext] AppleALC](https://github.com/acidanthera/AppleALC)
- [[Kext] RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X)
- [[Kext] AMDRyzenCPUPowerManagement](https://github.com/trulyspinach/SMCAMDProcessor)
- [[Kext] SMCAMDProcessor](https://github.com/trulyspinach/SMCAMDProcessor)
- [[Kext] NVMeFix](https://github.com/acidanthera/NVMeFix)
- [[Kext] AppleMCEReporterDisabler](https://github.com/AMD-OSX/AMD_Vanilla/blob/opencore/Extra/AppleMCEReporterDisabler.kext.zip)

**People:**

- [Apple](https://apple.com) for macOS
- [AMD-OSX Developers](https://github.com/AMD-OSX) for kernel patches for AMD CPUs
- [Acidanthera](https://github.com/acidanthera) for OpenCore and most of used kexts
- [Trulyspinach](https://github.com/trulyspinach) for Ryzen power management and monitoring kexts
- [Mieze](https://github.com/Mieze) for RealtekRTL8111 kext
- [Dortania](https://github.com/dortania) for OpenCore configuration guides
- [XLNC](https://github.com/naveenkrdy) for Adobe patches for AMD CPUs
- [AMD-OSX Community](https://amd-osx.com) for support while making my Hackintosh

## Contatti

Andrei Alexandru Dabija — [LinkedIn](https://www.linkedin.com/in/andrei-alexandru-dabija/) — [github.com/XtremeAlex](https://github.com/XtremeAlex)
