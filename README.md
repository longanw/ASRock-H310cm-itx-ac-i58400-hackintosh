# ASRock H310cm itx/AC + i5 8400 Hackintosh（OpenCore）
`Updated on Sept. 8,2023 by Yale Wei `

![Catalina](./pic/Catalina10.15.7_2023-09-08.png)![Monterey](./pic/Monterey12.6.8_2023-09-08.png)

English | [简体中文](./README-zh_CN.md)  

ASRock H310cm with i5 8400 PC's EFI configs for hackintosh, It can be using Catalina and Monterey OS, for personality purpose.

#### Status：developing
[![release](https://img.shields.io/badge/Download-latest-brightgreen.svg)](https://github.com/longanw/nuc8i5beh/releases) [![OpenCore](https://img.shields.io/badge/OpenCore-0.9.4-blue.svg)](https://github.com/acidanthera/OpenCorePkg/releases/latest) [![itlwm](https://img.shields.io/badge/itlwm-2.3Alpha-blue.svg)](https://github.com/OpenIntelWireless/itlwm/releases) [![MacOS Catalina](https://img.shields.io/badge/macOS-10.15.7-brightgreen.svg)](https://www.apple.com/macos/catalina/) [![MacOS Monterey](https://img.shields.io/badge/macOS-12.6.8-purple.svg)](https://www.apple.com/macos/monterey/)

#### Specs

| Name             | Information                            |
| ---------------- | ---------------------------------------|
| CPU              | Intel® Core™ i5 8400                  |
| iGPU             | Intel UHD 630                   |
| Lan              | Intel I219-V                           |
| Audio            | Realtek ALC887                         |
| Ram              | 8GB*2 ddr4 2667 Mhz            |
| Wifi + Bluetooth | Intel® Wireless-AC 3168 + Bluetooth 4.2|
| Nvme             | Great Wall GW3300                       |
| SMBios           | iMac19,1                             |
| BootLoader       | OpenCore 0.9.4                         |

#### Drivers

- [x] Intel UHD 630 iGPU HDMI/DP Output
- [x] ALC887 Internal Speakers/Front Panel Speaker
- [x] ALC887 HDMI/DP Audio Output
- [x] All USB Ports 
- [x] SpeedStep / Sleep / Wake
- [x] Intel® Ethernet Connection I219-V
- [x] Intel® Wireless-AC 3168 + Bluetooth 4.2


#### BIOS
Load UEFI Defaults

``` 
Advanced -> Chipset Configuration  -> Onboard HD Audio & Onboard HDMI HD Audio: Enabled
Advanced -> Chipset Configuration  -> VT-d: Disabled
Advanced -> USB Configuration -> XHCI Hand-off: Enabled
Advanced -> CPU Configuration  -> C States Support: Disabled
Advanced -> Super IO Configuration -> Serial Port: Disabled
Security -> Secure Boot: Disabled
BOOT -> CSM: Enabled

```
 
#### Buy me a coffee

| WeChat Pay | Alipay | 
| ---| --- |
| ![WePay](./pic/WePay.png) | ![alipay](./pic/Alipay.png) |

#### Credits

- [Apple](https://www.apple.com) 
- [Acidanthera](https://github.com/acidanthera)
- [Rehabman](https://github.com/RehabMan) 
- [daliansky](https://github.com/daliansky) 
- [zxystd](https://github.com/OpenIntelWireless/itlwm)
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/)
- [gitee.com](https://gitee.com) 
- [github.com](https://github.com) 



