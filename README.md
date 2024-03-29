# Thunderbolt firmware

Please note that the following repository is used for archiving purposes.
The original post can be found [here](https://www.tonymacx86.com/threads/success-gigabyte-designare-z390-thunderbolt-3-i7-9700k-amd-rx-580.267551/page-1640).

Please note that we do not own the files above and you're responsible for any type of damage to the Thunderbolt 3 card.

|Device/Model|Thunderbolt firmware|Comment|
|---|---|---|
|Gigabyte Designare Z390 and B550 Vision D Motherboards|[`DESIGNARE-Z390-NVM33-Elias64Fr.bin`](/Firmware/DESIGNARE-Z390-NVM33-Elias64Fr.bin.zip)|On-board Titan Ridge|
|Gigabyte Z390 AORUS Xtreme Motherboard|[`Z390-AORUS-XTREME-NVM33-Elias64Fr.bin`](/Firmware/Z390-AORUS-XTREME-NVM33-Elias64Fr.bin.zip)|On-board Titan Ridge|
|Gigabyte Z490 Vision D Motherboard|[`Gigabyte-Vision-D-NVM-50-Elias64Fr-CaseySJ.bin`](/Firmware/Gigabyte-Vision-D-NVM-50-Elias64Fr-CaseySJ.bin.zip)|On-board Titan Ridge|
|Gigabyte GC-Titan Ridge v1.0 add-in-card|[`GC-TITAN-RIDGE-NVM23-Elias64Fr.bin`](/Firmware/GC-TITAN-RIDGE-NVM23-Elias64Fr.bin.zip)|PCIe card V1.0 (before Jul 2020)|
|Gigabyte GC-Titan Ridge v2.0 add-in-card|[`GC-Titan-Ridge-V2.0-Mod-NVM50-CaseySJ.bin`](/Firmware/GC-Titan-Ridge-V2.0-Mod-NVM50-CaseySJ.bin.zip)|PCIe card V2.0 (since Jul 2020)|
|Gigabyte GC-Alpine Ridge add-in-card|<ol><li><a href="/Firmware/GC-ALPINE RIDGE-NVM20-V1-Elias64Fr.bin.zip">`GC-ALPINE RIDGE-NVM20-V1-Elias64Fr.bin`</a></li><li><a href="/Firmware/GC-ALPINE-RIDGE-NVM20-V2-Elias64Fr.bin.zip">`GC-ALPINE-RIDGE-NVM20-V2-Elias64Fr.bin`</a></li><li><a href="/Firmware/GC-ALPINE RIDGE-NVM21-V3-NATA.bin.zip">`GC-ALPINE RIDGE-NVM21-V3-NATA.bin`</a></li></ol>|<b>PCIe card</b><br>Some issues were reported with V1 and V2.<br>Try V3 by [@NorthAmTransAm](https://www.tonymacx86.com/members/2080127/).<br>May need to jump pins 3 and 5 instead of connecting to THB_C header.|
|Asus UX550 laptop|[`ASUS-UX550-NVM33-Elias64Fr.bin`](/Firmware/ASUS-UX550-NVM33-Elias64Fr.bin.zip)|On-board (Alpine Ridge?)|
|Intel NUC Hades Canyon:<ol><li>Model NUC8i7HNK</li><li>Model NUC8i3BEH</li></ol>|[`NUC8i7HNK.zip`](/Firmware/NUC8i7HNK.zip)<br>This contains:<ol><li>`NUC8i7HNKpatched.bin`</li><li>`SSDT-TbtOnPCH-Intel-NUC.aml`|This applies to both NUC models listed in first column.<br>Credit: [@dgsga](https://www.tonymacx86.com/members/12060/) and Osy86|
|Asus ThunderboltEX 3|[`ASUS-THUNDERBOLT-EX-3.zip`](/Firmware/ASUS-THUNDERBOLT-EX-3.zip)<br>This contains:<ol><li>`AlpineRidgeEX3-NVM18-NATA.bin`</li><li>`AlpineRidgeEX3-NVM26-NATA.bin`</li><li>`SSDT-TBOLT3-RP21-ASUS-TB-EX3.aml`</li></ol>|<b>PCIe Card</b><br>Use NVM18 for Rev B boards.<br>Use NVM26 only for Rev C boards.<br>Adapt the SSDT to the root port of your system.<br>Credit: [@NorthAmTransAm](https://www.tonymacx86.com/members/2080127/) (NATA)|
|ASRock Z390 and Z370 ITX/ac|[`ASROCK_Z390_ITX_NVM20_MOD-Elias64Fr.bin`](/Firmware/ASROCK_Z390_ITX_NVM20_MOD-Elias64Fr.bin.zip)|This applies to:<ol><li>ASRock Z390 Phantom Gaming ITX/ac</li><li>ASRock Fatal1ty Z370 Gaming-ITX/ac</li></ol>In BIOS, set `Thunderbolt Usb Support` to `Enabled`<br>Credit: [@Elias64Fr](https://www.tonymacx86.com/members/2347319/) [@mango1122](https://www.tonymacx86.com/members/2241238/)|
|ThinkPad X1 Carbon 6th Gen|[`Lenovo-X1-Carbon-NVM-43-MOD-1-CaseySJ.bin`](/Firmware/Lenovo-X1-Carbon-NVM-43-MOD-1-CaseySJ.bin.zip)|This applies to:<ol><li>Lenovo ThinkPad X1 Carbon 6th Gen Laptop</li></ol><br>In BIOS, disable `BIOS Assist`" mode.<br>May need to use [Thunderbolt 3 Unblocker](https://github.com/rgov/Thunderbolt3Unblocker) to allow certain devices such as Dell Thunderbolt Dock to connect.<br> [Reference](https://www.tonymacx86.com/threads/success-gigabyte-designare-z390-thunderbolt-3-i7-9700k-amd-rx-580.267551/post-2160656) ([@contemporarygary](https://www.tonymacx86.com/members/2266784/))|
|ASRock Z490 ITX/ac|[`ASRock-itx/tb3-NVM50-E64Fr-CSJ-dgsga.bin`](/Firmware/ASRock-itx%20tb3-NVM50-E64Fr-CSJ-dgsga.bin.zip)|This applies to:<ol><li>ASRock Z490 ITX/ac</li></ol><br>ASRock Z490 ITX/ac uses a single port Titan Ridge Low Power (LP) chip with device ID 0x15e7.<br>Credit: [@dgsga](https://www.tonymacx86.com/members/12060/)|
|Asus ZenBook Pro laptop|[`ASUS_UX550GE_TB3-CASEY-MOD-1.bin`](/Firmware/ASUS-UX550-NVM33-Elias64Fr.bin.zip)|This applies to:<ol><li>Asus ZenBook Pro UX550GE</li><li>Asus ZenBook Pro UX580GE</li></ol>|

# SSDTs

**Please note that the following SSDTs are taken from [https://hackindrom.zapto.org](https://hackindrom.zapto.org). We haven't found any way to contact you, so if you're the owner of those SSDTs please open an issue and we'll find a solution ^^**

Choose the right SSDT for your motherboard and eventually change the `RPxx` with your `RPyy` path (you can use [IORegistryExplorer](https://github.com/utopia-team/IORegistryExplorer/) to find it). For more infos check [here](https://elitemacx86.com/threads/how-to-enable-thunderbolt-3-hotplug-on-macos.462/)

- [`SSDT-ASRock-Z390-Z370-ITX-ac-TB3.aml`](/SSDTs/SSDT-ASRock-Z390-Z370-ITX-ac-TB3.aml)
- [`SSDT-ASRock-Z490-ITX-ac-TB3.aml`](/SSDTs/SSDT-ASRock-Z490-ITX-ac-TB3.aml)
- [`SSDT-ASUS-ThunderboltEX-3-TB3.aml`](/SSDTs/SSDT-ASUS-ThunderboltEX-3-TB3.aml)
- [`SSDT-ASUS-Z490-ProArt-Creator-TB3.aml`](/SSDTs/SSDT-ASUS-Z490-ProArt-Creator-TB3.aml)
- [`SSDT-Gigabyte-B550-Vision-D-TB3.aml`](/SSDTs/SSDT-Gigabyte-B550-Vision-D-TB3.aml)
- [`SSDT-Gigabyte-Designare-X299X-10G-TB3.aml`](/SSDTs/SSDT-Gigabyte-Designare-X299X-10G-TB3.aml)
- [`SSDT-Gigabyte-GC-Alpine-Ridge-TB3.aml`](/SSDTs/SSDT-Gigabyte-GC-Alpine-Ridge-TB3.aml)
- [`SSDT-Gigabyte-GC-Titan-Ridge-v1-or-v2-TB3.aml`](/SSDTs/SSDT-Gigabyte-GC-Titan-Ridge-v1-or-v2-TB3.aml)
- [`SSDT-Gigabyte-Z390-AORUS-Xtreme-TB3.aml`](/SSDTs/SSDT-Gigabyte-Z390-AORUS-Xtreme-TB3.aml)
- [`SSDT-Gigabyte-Z490-Vision-D-TB3.aml`](/SSDTs/SSDT-Gigabyte-Z490-Vision-D-TB3.aml)
- [`SSDT-Z390-DESIGNARE-TB3HP-V4.aml`](/SSDTs/SSDT-Z390-DESIGNARE-TB3HP-V4.aml)

# How to choose the best PCIe card?

At the time of writing this README.md, <b>we highly recommend the user to have a motherboard with a PCIE\_16X slot in 4x mode.</b>

This requirement is really important since PCIe Thunderbolt 3 cards don't work on PCIE\_16X slots (also known as `PEG` slots).<br>
If you satisfy this requirement, then proceed by:

1. Buying a <b>Gigabyte GC-Titan Ridge v2.0 add-in-card</b>
2. Flashing [`DESIGNARE-Z390-NVM33-Elias64Fr.bin`](/Firmware/DESIGNARE-Z390-NVM33-Elias64Fr.bin.zip) as described [here](https://github.com/ameyrupji/thunderbolt-macpro-5-1/blob/master/GC-TitanRidge.md#thunderbolt-mac-pro-early-2009-with-gigabyte-gc-titan-ridge-card)
3. Using [SSDT-Z390-DESIGNARE-TB3HP-V4.aml](/SSDTs/SSDT-Z390-DESIGNARE-TB3HP-V4.aml) and edit it by replacing `RPxx` with your `RPyy` path (you can use [IORegistryExplorer](https://github.com/utopia-team/IORegistryExplorer/) to find it)
4. Setting your Thunderbolt BIOS settings as it follows:
	- `Security Level` = `Disabled`
	- `GPIO Force PWR` = `On` 
	 - Please note that if your card works with this option you don't need to follow the next step
5. Jumping pins `3` and `5` as described [here](https://github.com/ameyrupji/thunderbolt-macpro-5-1/blob/master/GC-TitanRidge.md#connect-pin-3-and-pin-5-of-jumper-for-hot-swap-capability) if `GPIO Force PWR` doesn't work

# What if I fucked the firmware and want to restore the stock one?

You can either choose to reflash the stock firmware using the utility provided by your AIC vendor, or can use the following firmwares:

###### Please note that the list is not complete. PRs are welcomed

- [Titan Ridge 2.0 blue and green chip firmwares](/Firmware/Original/Titan%20Ridge%202.0)
