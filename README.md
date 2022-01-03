# Lenovo_IdeaPad_L340_Hackintosh
Hackintosh of Lenovo IdeaPad L340 Gaming

## System Specification
IdeaPad L340 Gaming specification:

| Type | Name | Note |
| --- | --- | --- |
| CPU | Intel Core i5 9300H | |
| Graphics | Intel UHD Graphics 630 | Disabled GTX 1050 |
| Display | 15.6in FullHD | |
| RAM | 8GB or 16GB DDR4 |
| Wifi | Realtek 
| Bluetooth | Realtek
| NVME SSD| Samsung SSD 970 EVO Plus 250GB |
| SATA Disk | WDC WD10SPZX-24Z10 1TB |
| USB | 2 USB 3.1 + 1 USB 3.1 Type C |
| Trackpad | Elan 628 |
| Audio | Realtek ALC 257 |
| BIOS version| BGCN28WW - BGCN29WW |
| macOS version| macOS Monterey |

## Not working?

- GTX 1050 (Disabled)
- HDMI Port (it was connected with GTX 1050)
- Wifi (No kexts to fix Realtek card)
- Bluetooth (same as above)
- Trackpad (I'm just a student do not know much about editing DSDT)

## Enable HiDPI

On the default resolution (1920x1080), text is fine to read my experience. If you want to make the text bigger, you need to enable HiDPI
[one-key-hidpi](https://github.com/xzhih/one-key-hidpi). If you change text size with changing resolution without enable HiDPI, text is blurry.

## Credits
- Apple Inc. for providing macOS
- [acidanthera](https://github.com/acidanthera) for providing Opencore, kexts and the drivers.
- [alexandred](https://github.com/alexandred) for providing VoodooI2C
- [xzhih](https://github.com/xzhih/one-key-hidpi) who helps enable HiDPI easier.
