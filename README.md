# HP-AC163TX-Hackintosh-OC
My EFI Backup for OpenCore 0.6.6 running macOS Big Sur 11.2

# Note
If you want to use the config file, don't forget to generate your own DeviceProperties.

| | Specification |
| ------- | ------------- |
| Model | HP 15-AC163TX |
| Bootloader | OpenCore |
| Bootloader Version | 0.6.6 |
| CPU | Intel Core i7-5500u |
| Graphics | Intel HD Graphics 5500 |
| Memory | 8 GB DDR3-1600 MHz |
| OS | Windows 10 20H2 and macOS Big Sur 11.2 |
| Storage | 120 GB SSD for Windows 10, 150 GB HDD for MacOS |
| Display | 15" 1366x768 and LG 22MK600 1920x1080 |
| Sound | ALC282 |
| Wifi | Realtek RTL8723BE |
| Ethernet | Realtek RTL8139/810x |
| Touchpad | Synaptics SMBus / PS2 |

# What's Working?
- QE/CI on Intel HD Graphics 5500
- USB Ports
- HDMI Output
- Shutdown, Restart
- Brightness control
- Ethernet
- Touchpad
- Battery Percentage

# What's not working?
- Wifi (Realtek RTL8723BE is not supported)
- Audio ALC282 (Not detected at DCPIManager)

# Workarounds?
- I'm using my USB Mixer as my Sound Output

# Kext Included in the Kexts folder
- ACPIBatteryManager
- AppleALC
- Lilu
- RealtekRTL8100
- SMCProcessor
- SMCSuperIO
- USBInjectAll
- VirtualSMC
- VoodooPS2Controller
- WhateverGreen
