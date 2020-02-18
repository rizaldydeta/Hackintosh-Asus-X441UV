# Hackintosh Asus X441UV

Hackintosh resources for Asus X441UV

This is my complete EFI folder to be used for Hackintosh on Notebook Asus X441UV

<img src="/img/macOS-Catalina.png?raw=true" alt="macOS Catalina" align="center">

--------------------------------------------------------------------------------------------

### Notebook Specs
<img src="/img/x441uv-wx091d.png?raw=true" alt="Asus X441UV" align="right">

- [x] <b>Model</b>: Asus X441UV-WX091D (X441U Board) 2018
- [x] <b>CPU</b>: Intel Core i3-6006u (4) @ 2.00GHz (6th Gen)
- [x] <b>GPU</b>: Intel HD Graphics 520 @ 1536 MB & Nvidia 920MX  @ 2GB
- [x] <b>RAM</b>: 4GB DDR4 SDRAM @ 2133MHz (upgradable to 16GB)
- [x] <b>HDD</b>: 1TB HDD SATA @ 5400rpm (GUID Partition Table)
- [x] <b>Audio</b>: Realtek ALC255 Rev. 2
- [x] <b>Wifi</b>: Qualcomm Atheros AR9565
- [x] <b>Ethernet</b>: Realtek RTL810xE PCI-e Gigabit Ethernet
- [x] <b>Others</b>: 1 USB 2.0 + 1 USB 3.0 + 1 USB type C ports, Elan 1200 TouchPad, HDMI/VGA, Asus WebCam, 14.0" 16:9 HD (1366x768) LED, Pioneer DVD-RW, (SD/ MS/ MS Pro/ MMC) Card Reader, 3-Cell @3200mAh 36Wh Lithium-ion Battery
- [x] <b>BIOS</b>: Ver. 309 (Asus).

--------------------------------------------------------------------------------------------

### EFI Contains
- [x] <b>Clover Bootloader binary, config.plist</b>, drivers for legacy/uefi, themes, etc..
- [x] <b>Patched ACPI Tables (DSDT-SSDT)</b> for Graphics, Audio, Wifi, Ethernet, Battery, etc..
- [x] <b>3rd party kexts</b> for working devices under Mac OS X 10.11.6 upto macOS Catalina 10.15.x
 
--------------------------------------------------------------------------------------------
 
### What Worked
- [x] Restart, Sleep and Shutdown
- [x] Audio Out (In and Ext) + Int. Mic and Still Work after Wake
- [x] Sleep and Wake with Close and Open LID
- [x] QE/CI of IGPU
- [x] HDMI Out
- [x] HDMI Audio
- [x] Brightness
- [x] Function FN Keys
- [x] CPU Power Management
- [x] USB 3.0 Full Working (Super Speed 5Gb/s full Working)
- [x] Touchpad
- [x] Battery Indicator
- [x] WiFI
- [x] Etc
 
--------------------------------------------------------------------------------------------
 
### Not Worked / Bugs
- [ ] Nvidia GT920mx (Nvidia Switchable GPU / Optimus is not supported by Hackintosh)
- [ ] Bluetooth (Need Boot to Windows First)
- [ ] Etc
 
--------------------------------------------------------------------------------------------
