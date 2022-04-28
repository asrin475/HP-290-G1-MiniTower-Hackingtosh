# HP-290-G1-MiniTower - Hackingtosh
This repo contains Opencore EFI files and scripts to Install macOS


![HP290G1](https://ssl-product-images.www8-hp.com/digmedialib/prodimg/lowres/c05511779.png) ![Moneterey](./Monterey.png)

## Bootloader
- Opencore `0.7.9`

# Specifications


### Basic
- Model : **`HP`**
- BIOS Ver: **``**


### Hardware

- CPU: Intel® Core i5-7500 @ 3.40 GHz processor (4 Cores)
- GPU: Integrated Intel® HD Graphics 630 (1 HDMI + 1 VGA Port)
- Memory: 1 x 4GB Micron DDR4-2400 MHz  
- Storage: Segate ST500DM002-1BD142 500 GB (7200 RPM) 
- LAN: Realtek RTL8168H/8111H PCI Express Gigabit Ethernet
- WLAN: TPLink TL-WN725N (RealTek Chipset) 
- Audio: Conexant CX20632 (Rear - 2 ports, Front - 1 Mic port, 1 internal speaker)

### Tested OS

- Bigsur 11.2.3 
- Monterey 12.3.1 (Build 21E258)
> had a black screen issue with booting the installer - adding device-id to the iGPU solved it.


### BIOS Setup



### Issues

- Waking monitor after sleep or locking


### Credits

- `Apple` - Eye candy macOS
- `Acidanthera` - Well crafted Opencore software and plugins
- `Dortania` - Another level of Hackintoshing guides
- [chris1111](https://github.com/chris1111) - Drivers for Realtek 802.11n and 802.11ac USB Wi-Fi adapters. Packages for macOS
- `RehabMan` - Specially for the USBInjectAll.kext
