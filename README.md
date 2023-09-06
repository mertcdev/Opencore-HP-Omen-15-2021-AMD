# Opencore-HP-Omen-15-2021-AMD
## Working with macOS 12.6.5
Opencore config files for HP Omen 15 2021 AMD Variant

Battery life the best I can get for this machine is around 2h. (dGPU disable with SSDT method cause bootloop)

## Specs
* CPU: AMD Ryzen 7 5800H
* GPU: AMD Radeon Vega 8 (Cezanne-Renoir) + NVIDIA GeForce RTX 3060
* Ram: 16 GB Samsung DDR4 3200 MHz
* Audio: ALC245 (layout-id 13)
* Trackpad: Synaptics (syna32a5)
* Main SSD: SAMSUNG MZVLB512HBJQ-000H1 - PM981a  ***This SSD unsupported for MacOS. Someone used on cloned partition from different SSD, but not guaranteed method. Replace this SSD(PM981a) as it may cause various problem even with [NVMeFix.kext](https://github.com/acidanthera/NVMeFix)***
* Second SSD: OCZ-VECTOR
* WiFi: Intel® Wi-Fi 6 AX200
* Display: FHD 144hz (LGD05FE)
* BIOS Version: F.21 (10/21/2022)

## What's working/not working
* Everything works except video output since all video ports are connected to nVidia.
* Built-in Mic works with AMDMicrophone.kext and 3.5mm jack microphone output not working. (General issue with AppleALC.)

## CinebenchR23
![Image of Cinebench]
