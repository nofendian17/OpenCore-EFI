# Hackintosh B450 AORUS PRO WIFI (rev. 1.0)

### System Components
- Prosesor  AMD Ryzen 5 3600
- 16 GB 3600 MHz DDR4
- Radeon™ RX 580 Graphics 8 GB
- CHIPSET AMD B450
- Audio Realtek® ALC1220-VB codec
-  Intel® GbE LAN chip (10/100/1000 Mbit)
- Wireless Communication Wi-Fi 802.11 a/b/g/n/ac, supporting 2.4/5 GHz Dual-Band, BLUETOOTH 4.2
- NVME ADATA SX6000LNP 120 GB

### OS
- MacOs Catalina 10.15.6 (19G2021)

### Software
- OpenCore version [0.6.0](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.6.0 "0.6.0")

### Kext
- VirtualSMC.kext 1.1.5
- Lilu.kext 1.4.6
- WhateverGreen.kext 1.4.1
- AppleALC.kext 1.5.1
- SmallTreeIntel82576.kext 1.0
- AppleMCEReporterDisabler.kext 1.0
- NVMeFix.kext 1.0.3
- AMD-USB-Map.kext 1.0
- Innie.kext 1.2.0
- IntelBluetoothFirmware.kext 1.1.2
- IntelBluetoothInjector.kext 1.1.2
- itlwm.kext 1.0.0
- MacProMemoryNotificationDisabler.kext 1.0.0

### Note
- Sleep/WakeUp not working 
- Intel Wifi work using HeliPort [1.0.0](https://github.com/OpenIntelWireless/HeliPort/releases/tag/v1.0.0 "1.0.0")
using itlwm.kext 1.0.0
- Realtek Audio output working (ALC1220-VB), but input not working (currently using layout type = 1)

### Recommend Upgrade
- Wifi, Bluetooth, Airdrop (can work if replace with Broadcom [BCM94360CS](https://www.tokopedia.com/galericomputerba/bcm943602cs-pci-e-wifi-bluetooth-4-0-dekstop-hackintosh "BCM94360CS") 1750Mbps Dual Band 802.11 a/b/g/n/AC Desktop + Bluetooth 4.0)

### Troubleshoot
- OpenCore Install [Guide](https://dortania.github.io/OpenCore-Install-Guide/ "Guide")
