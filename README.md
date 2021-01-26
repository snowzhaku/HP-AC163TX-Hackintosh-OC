# HP-AC163TX-Hackintosh-OC
My EFI Backup for OpenCore 0.6.5 running macOS Big Sur 11.0.1

# Note
This configuration is NOT finished yet. If you want to use the config file, don't forget to generate your own DeviceProperties.

| | Specification |
| ------- | ------------- |
| Model | HP 15-AC163TX |
| Bootloader | OpenCore |
| Bootloader Version | 0.6.5 |
| CPU | Intel Core i7-5500u |
| Graphics | Intel HD Graphics 5500 |
| Memory | 8 GB DDR3-1600 MHz |
| OS | Windows 10 and macOS Big Sur 11.0.1 |
| Storage | 120 GB SSD for Windows 10, 150 GB HDD for MacOS |
| Display | 15" 1280x720 and LG 22MK600 1920x1080 |
| Sound | ALC282 |
| Wifi | Realtek RTL8723BE |
| Touchpad | Synaptics SMBus / PS2 |

# What's Working?
- QE/CI on Intel HD Graphics 5500
- USB 2.0 Works, haven't test the USB 3.0 Port yet.
- HDMI Output
- Shutdown
- Brightness control via System Preferences

# What's not working?
- Wifi (Realtek RTL8723BE is not supported)
- Ethernet (Haven't found the right kext for the Ethernet Port)
- Audio not yet configured
- USB 3.0 port may only reads USB 3.0 devices

# Workarounds?
- I'm currently using TP-Link TL-WN725N for connecting to the internet

# Kext Included in the Kexts folder
- AppleALC
- Lilu
- SMCProcessor
- SMCSuperIO
- USBInjectAll
- VirtualSMC
- VoodooPS2Controller
- VoodooSMBus
- WhateverGreen
