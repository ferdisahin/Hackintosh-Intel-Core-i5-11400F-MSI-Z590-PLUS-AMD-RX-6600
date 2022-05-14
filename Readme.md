### Before Installation

Before installing Hackintosh, you need to configure the [BIOS settings](https://dortania.github.io/OpenCore-Install-Guide/config.plist/comet-lake.html#intel-bios-settings). You can review the Dortania guide for this.

### Hardware Configuration

| Configuration | Model                                               |
|---------------|-----------------------------------------------------|
| CPU           | Intel Core i5 11400F 2.6Ghz                         |
| CPU Cooler    | ID-Cooling Frostflow X 120                          |
| Motherboard   | MSI Z590 PLUS Socket 1200                           |
| Memory        | Hikvision DDR4 3200Mhz 16GB * 4 (64GB)              |
| Graphics Card | Sapphire Pulse Radeon RX 6600 8GB                   |
| SSD           | SanDisk Ultra 3D 500GB 2400MB-1750MB/s NVMe M.2 SSD |
| Power Supply  | Thermaltake Litepower 650W APFC                     |
| Case          | NZXT H510 Tempered Glass                            |

### What's Working

| Name                  | Working | Details                                                                   |
|-----------------------|---------|---------------------------------------------------------------------------|
| Audio                 | ✅ |                                                                           |
| Graphics Acceleration | ✅ |                                                                           |
| Sleep                 | ✅ |                                                                           |
| Wake                  | ✅ |                                                                           |
| USB Ports             | ✅ | USBMap.kext is ready but you may need to reconfigure it.                  |
| HDMI                  | ✅ |                                                                           |
| DisplayPort           | ⬜ | I haven't tried displayport. Most likely DP won't work.                   |
| App Store             | ✅ |                                                                           |
| PowerNAP              | ✅ |                                                                           |
| FaceTime              | ✅ |                                                                           |
| iMessage              | ✅ |                                                                           |
| Ethernet              | ✅ | If ethernet doesn't work, delete ethernet from settings and add it again. |

### Important Information

I would not recommend using SMBIOS except for the iMac Pro1.1. Because the processor is 11th generation, it only works with iMac Pro1,1.

### Image

![Desktop](https://raw.githubusercontent.com/ferdisahin/Hackintosh-Intel-Core-i5-11400F-MSI-Z590-PLUS-AMD-RX-6600/0.8.0/Images/desktop.jpeg)
