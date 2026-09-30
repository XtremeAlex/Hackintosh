<div align="center">
<img alt="Logo Hackintosh" src="Asrock-H110M/i5-6600K/clover/macOS Catalina 10.15.7/_img/hackintosh-logo.jpg">
</div>

# Hackintosh

Le configurazioni EFI e le note che ho usato per far girare macOS su hardware
non Apple, insieme ai link alle guide della community che mi sono state più
utili.

> Stato: progetto storico. La build documentata (Clover + macOS Catalina) non
> viene più aggiornata. Oggi il bootloader di riferimento è
> OpenCore, e le versioni recenti di macOS stanno abbandonando i processori
> Intel: se inizi adesso, parti dalle guide Dortania qui sotto.

## Build documentate

- [Asrock H110M / i5-6600K / Clover / macOS Catalina 10.15.7](https://github.com/XtremeAlex/Hackintosh/tree/main/Asrock-H110M/i5-6600K/clover/macOS%20Catalina%2010.15.7)
  — cartella EFI completa (Clover, kext, driver, SSDT) e scheda hardware

## Guide OpenCore (Dortania)

- Creare la chiavetta di installazione: [link](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/)
- Configurare OpenCore (esempio AMD Zen): [link](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html)
- Post-installazione: [link](https://dortania.github.io/OpenCore-Post-Install/)
- Risoluzione dei problemi: [link](https://dortania.github.io/OpenCore-Install-Guide/troubleshooting/troubleshooting.html)
- Patch ACPI: [link](https://dortania.github.io/Getting-Started-With-ACPI/)
- Mappatura USB: [link](https://dortania.github.io/OpenCore-Post-Install/usb/)

## Credits

Questi sono i progetti e le persone a cui devo il lavoro sugli Hackintosh
(riferimenti per le build OpenCore, anche su AMD). La build Clover documentata
qui usa a sua volta diversi di questi kext (Lilu, VirtualSMC, WhateverGreen,
AppleALC, RealtekRTL8111, NVMeFix).

**Software**

- [[Bootloader] OpenCore](https://github.com/acidanthera/OpenCorePkg)
- [[Resources] Picker GUI](https://github.com/acidanthera/OcBinaryData/tree/master/Resources)
- [[Patch] AMD_Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)
- [[SSDT] EC-USBX-DESKTOP](https://github.com/dortania/Getting-Started-With-ACPI/blob/master/extra-files/compiled/SSDT-EC-USBX-DESKTOP.aml)
- [SSDT] SLEEP-PTXH (file della build OpenCore, non incluso in questo repository)
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

**Persone**

- [Apple](https://apple.com) per macOS
- [AMD-OSX Developers](https://github.com/AMD-OSX) per le patch del kernel per CPU AMD
- [Acidanthera](https://github.com/acidanthera) per OpenCore e per la maggior parte dei kext usati
- [Trulyspinach](https://github.com/trulyspinach) per i kext di power management e monitoraggio Ryzen
- [Mieze](https://github.com/Mieze) per il kext RealtekRTL8111
- [Dortania](https://github.com/dortania) per le guide di configurazione di OpenCore
- [XLNC](https://github.com/naveenkrdy) per le patch Adobe per CPU AMD
- [AMD-OSX Community](https://amd-osx.com) per il supporto mentre costruivo il mio Hackintosh

## Licenza
Distribuito sotto licenza [Creative Commons Attribution 4.0 (CC BY 4.0)](LICENSE). Puoi condividere e adattare il materiale, anche commercialmente, a condizione di citare l'autore.

## Contatti

Andrei Alexandru Dabija (XtremeAlex) · [alexdabi92@gmail.com](mailto:alexdabi92@gmail.com) · [2ad.bubume.it](https://2ad.bubume.it/) · [LinkedIn](https://www.linkedin.com/in/andrei-alexandru-dabija/) · [github.com/XtremeAlex](https://github.com/XtremeAlex)
