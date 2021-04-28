# Gigabyte-Z590i-Vision-D-10900K
 <p align="center">
  <img src="Docs/AboutThisMac.png" align=center">
 </p>
 <p align="center">
  <img src="Docs/PCI.png" align=center">
 </p>

 ## Specs
 | **Component** | **Model** |
| ------------- | --------- |
| CPU | i9-10900K @ 5.3GHz |
| RAM | DDR4 32GB (2x16GB) 3200MHz Crucial Ballistix White RGB |
| Audio Chipset | Realtek ALC4080. Works OOB as it is connected like a USB-Audio interface |
| dGPU | MSI RX 5500 XT Gaming X 8GB |
| iGPU | Intel UHD Graphics 630 |
| WiFi & Bluetooth | BCM94360NG Works OOB. Fits into original Intel card slot |
| Lan |  Intel® 2.5GbE LAN I225-V |
| OS Disk | 512GB Samsung 850 Pro SATA |
| macOS | Big Sur 11.3/OpenCore 0.6.8

## BIOS
- Press Del to enter the BIOS. Use latest available bios for this board which F5d as of this writing.
- Enable XMP Profile1.
- Disable Legacy USB.
- Enable Internal graphics and set DVMT Pre-Allocated to 128MB, Total GFix memory to MAX.
- The rest of the settings can be left at their defaults. Make sure though that CFG Lock is disabled and CSM Support is disabled.

## Opencore
- Fill in your own PlatformInfo. For Big Sur use iMac20,2 SMBIOS.

