# Lenovo_IdeaPad_L340_Hackintosh
Hackintosh of Lenovo IdeaPad L340 Gaming

## System Specification
IdeaPad L340 Gaming specification:

| Type | Name | Note |
| --- | --- | --- |
| CPU | 2.4 GHz Quad-Core Intel Core i5 9300H | |
| Graphics | Intel UHD Graphics 630 | Disabled GTX 1050 |
| Display | 15.6in FullHD |
| RAM | 8GB or 16GB DDR4 |
| Wifi | Realtek 8822BE Wireless LAN 802.11ac PCI-E NIC or Intel |
| Bluetooth | Realtek 8822BE Wireless LAN 802.11ac PCI-E NIC or Intel |
| NVME SSD| Samsung PM 981 250GB |
| SATA Disk | WDC WD10SPZX-24Z10 1TB |
| USB | 2 USB 3.1 + 1 USB 3.1 Type C |
| Trackpad | Elan or Synaptic |
| Audio | Realtek ALC 257 |
| BIOS version| BGCN28WW - BGCN29WW |
| macOS version| macOS Monterey |

## Not working?

- GTX 1050 (Disabled)
- HDMI Port (it was connected with GTX 1050)
- Wifi (No kexts to fix Realtek card) 
- Bluetooth (same as above)
- Trackpad (I'm just a student do not know much about editing DSDT)

## Wifi

If you have Realtek card and want to use Wifi or Bluetooth, please use USB tethering, ethernet or buy a new native support Broadcom card. If you have Intel card, you can use the kext by [OpenIntelWireless](https://github.com/OpenIntelWireless/itlwm/releases) and enable it using this [guide](https://openintelwireless.github.io/itlwm/).

## For trackpad
  For those who have Elan0626 touchpad, you MUST force polling 

## Enable HiDPI

If you want to make the text bigger, you need to enable HiDPI [one-key-hidpi](https://github.com/xzhih/one-key-hidpi). If you change text size with changing resolution without enable HiDPI, text is blurry.

## Credits
- Apple Inc. for providing macOS
- [acidanthera](https://github.com/acidanthera) for providing Opencore, kexts and the drivers.
- [alexandred](https://github.com/alexandred) for providing VoodooI2C
- [xzhih](https://github.com/xzhih/one-key-hidpi) who helps enable HiDPI easier.
- [dortania](https://github.com/dortania) for providing the guide and SSDT.
- [CorpNewt](https://github.com/corpnewt) for his useful tools.
