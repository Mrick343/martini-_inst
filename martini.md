---
title: OnePlus 9RT (martini)
description: Brought to you by Mrick343
---
<a href="#"><img align="center" img src="/installation.png" /></a>

**Please note that OOS13.1 EX01 firmware is included in these builds**

 First Time Install / Clean Flash from OOS/Other Custom ROM

1. Be on OOS13 and have an unlocked bootloader
2. Download recovery & rom zip for your device from DevUploads
3. Reboot to bootloader
4. fastboot flash dtbo dtbo.img
fastboot flash vendor_boot vendor_boot.img
fastboot flash boot boot.img
fastboot reboot recovery
5. While in recovery navigate to Factory reset -> Format data/factory reset and confim to format the device.
6. When done formatting, go back to the main menu and then navigate to Apply update -> Apply from ADB
7. adb sideload rom.zip (replace "rom" with actual filename)
8 (optional). Reboot to recovery to sideload any add-ons (e.g magisk)
9. Reboot to system & Enjoy

Update
1. Reboot to recovery
2. While in recovery, navigate to Apply update -> Apply from ADB
3. adb sideload rom.zip (replace "rom" with actual filename)
4. Reboot to system & Enjoy
----
Download Link : [**Official Download Link for martini**](https://devuploads.com/qotsagjgecmh)

----
