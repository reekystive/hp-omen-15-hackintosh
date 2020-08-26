# hp-omen-15-hackintosh-efi

OpenCore BootLoader for HP OMEN 15

**Thanks to the developers of OpenCore and the other drivers used here!**

## Before you use this EFI

- Change the PlatformInfo

## Hardware Detials

This EFI was made for HP OMEN 15-dc0006TX.

- CPU: Intel Core i7-8750H
- iGPU: Intel UHD Graphics 630
- dGPU: NVIDIA GeForce GTX 1050 Ti
- Motherboard: HP 84DA (U3E1)
- SSD: 119GB LITEON CA1-8D128-HP
- HDD: 931GB Hitachi HGST HTS721010A9E630
- Audio: Realtek ALC295
- Bluetooth: Intel Wireless Bluetooth
- WiFi Apdater: Intel Wireless-AC 9560 160MHz
- Ethernet: Realtek Gaming GbE Family Controller
- Touchpad: Synaptics SMBus TouchPad
- Keyboard: Standard PS/2 Keyboard
- Camera: HP Wide Vision HD Camera
- Memory: 8GB DDR4 2666MHz

You can view this product on [JD](https://item.jd.com/7649695.html).

## What is working

- iGPU
    - Backlight is working fine.
- Keyboard
- Touchpad (but the keys on it is not working)
- USB Port (I don't know if it works with USB2.0 or USB3.0)
- Camera
- Built-in Speaker and Microphone
- Audio port
- Ethernet
- WiFi
    - To connect to a WiFi, you need [HeliPort](https://github.com/OpenIntelWireless/HeliPort/releases/latest).
- CPU temperature monitoring
- SSD temperature monitoring
- Battery

## What is not working

- dGPU
    - This will not be fixed in the future.
- Keys on touchpad
- Sleep
    - After the black screen, the fan spins fast, cannot sleep and cannot wake up.
- Bluetooth
- NVRAM
    - You cannot store some information such as brightness.
- Fan speed control
- Fn key and NumLock key

## Reference

- [Vanilla Laptop Guide](https://dortania.github.io/vanilla-laptop-guide/)
