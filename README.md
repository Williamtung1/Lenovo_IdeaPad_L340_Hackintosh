# Lenovo_IdeaPad_L340_Hackintosh
Hackintosh of Lenovo IdeaPad L340 Gaming

## System Specification
IdeaPad L340 Gaming specification:

| Type | Name | Note |
| --- | --- | --- |
| CPU | 2.4 GHz Quad-Core Intel Core i5 9300H | |
| Graphics | Intel UHD Graphics 630 | GTX 1050 is disabled |
| Display | 15.6in FullHD |
| RAM | 8GB DDR4 |
| Wifi | Realtek 8822BE WLan |
| Bluetooth | Realtek 8822BE WLan |
| NVME SSD| Samsung PM991 250GB |
| SATA Disk | WDC WD10SPZX-24Z10 1TB |
| USB | 2 USB 3.1 + 1 USB 3.1 Type C |
| Trackpad | Elan0626 | force-polling is needed |
| Audio | Realtek ALC 257 |
| macOS version| macOS Ventura |

## Not working?

- GTX 1050 (Not supported by macOS)
- HDMI Port (it was connected with GTX 1050)
- Wifi (not supported by macOS) 
- Bluetooth (same as above)
- ~~Trackpad~~ I have finally worked out the way to patch it

## Wifi

If you have Realtek card and want to use Wifi or Bluetooth, please use USB tethering, ethernet or buy a new native support Broadcom card. If you have Intel card, you can use the kext by [OpenIntelWireless](https://github.com/OpenIntelWireless/itlwm/releases) and enable it using this [guide](https://openintelwireless.github.io/itlwm/).
 
## Enable HiDPI

If you want to make the text bigger, you need to enable HiDPI [one-key-hidpi](https://github.com/xzhih/one-key-hidpi). If you change text size with changing resolution without enable HiDPI, text is blurry.

## Credits
- Apple Inc. for providing macOS
- [acidanthera](https://github.com/acidanthera) for providing Opencore, kexts and the drivers.
- [5T33Z0](https://github.com/5T33Z0/OC-Little-Translated) for providing the guide for every single detail of hackintosh.
- [dortania](https://github.com/dortania) for providing the guide.
- [CorpNewt](https://github.com/corpnewt) for his useful tools.
