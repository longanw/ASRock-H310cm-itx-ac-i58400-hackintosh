# ASRock H310cm itx/AC + i5 8400 Hackintosh（OpenCore）
`Yale Wei 更新于2023-09-08`

![Catalina](./pic/Catalina10.15.7_2023-09-08.png)![Monterey](./pic/Monterey12.6.8_2023-09-08.png)

[English](./README.md) | 简体中文  


#### 简介
华擎H310cm itx/AC + i5 8400黑苹果EFI配置文件集，同时支持Catalina和Monterey启动，目前主力系统为Monterey 12.6.8。其中的intel WIFI (AirportItlwm.kext)为精简编译版（不一定适用其他黑果设备）以减少体积，其他资源均来自因特网。

机型三码已删除，请使用工具自行生成更新config.plist。

#### 状态：进行中
[![release](https://img.shields.io/badge/Download-latest-brightgreen.svg)](https://github.com/longanw/nuc8i5beh/releases) [![OpenCore](https://img.shields.io/badge/OpenCore-0.9.4-blue.svg)](https://github.com/acidanthera/OpenCorePkg/releases/latest) [![itlwm](https://img.shields.io/badge/itlwm-2.3Alpha-blue.svg)](https://github.com/OpenIntelWireless/itlwm/releases) [![MacOS Catalina](https://img.shields.io/badge/macOS-10.15.7-brightgreen.svg)](https://www.apple.com/macos/catalina/) [![MacOS Monterey](https://img.shields.io/badge/macOS-12.6.8-purple.svg)](https://www.apple.com/macos/monterey/)

#### 配置表

| 组件名称          | 型号规格                                 |
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
#### 驱动情况

- [x] Intel UHD 630 iGPU HDMI/DP Output
- [x] ALC887 Internal Speakers/Front Panel Speaker
- [x] ALC887 HDMI/DP Audio Output
- [x] All USB Ports 
- [x] SpeedStep / Sleep / Wake
- [x] Intel® Ethernet Connection I219-V
- [x] Intel® Wireless-AC 3168 + Bluetooth 4.2


#### BIOS设置
先载入默认配置

``` 
Advanced -> Chipset Configuration  -> Onboard HD Audio & Onboard HDMI HD Audio: Enabled
Advanced -> Chipset Configuration  -> VT-d: Disabled
Advanced -> USB Configuration -> XHCI Hand-off: Enabled
Advanced -> CPU Configuration  -> C States Support: Disabled
Advanced -> Super IO Configuration -> Serial Port: Disabled
Security -> Secure Boot: Disabled
BOOT -> CSM: Enabled

```


#### 赞助，一分也是爱！

| 微信支付 | 支付宝 | 
| ---| --- |
| ![WePay](./pic/WePay.png) | ![alipay](./pic/Alipay.png) |

#### 感谢名单

- [Apple](https://www.apple.com) 的macOS
- [Acidanthera](https://github.com/acidanthera) 维护的项目
- [Rehabman](https://github.com/RehabMan) 和 [黑果小兵](https://github.com/daliansky) 维护的项目
- [zxystd](https://github.com/OpenIntelWireless/itlwm) 开发的Intel WIFI和Bluetooth驱动
- [Dortania](https://dortania.github.io/OpenCore-Install-Guide/) 的OpenCore安装指引
- [码云](https://gitee.com) 
- [github.com](https://github.com) 



