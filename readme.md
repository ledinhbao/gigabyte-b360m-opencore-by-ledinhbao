# Opencore EFI and settings

## My desktop specification

- Motherboard: Gigabyte B360M AORUS Gaming 3
- Chipset: Intel Core i7-8700 3.20GHz
- RAM: 4x Corsair Vengeance LPX 8GB DDR4 2666MHz
- dGPU: Gigabyte Radeon™ RX 580 GAMING 8G
- Audio: Realtek ALC892
- Bluetooth: Broadcom BRCM20702

macOS Catalina (Version 10.15.7, 19H1217)

## The guide

OpenCore Vanilla Guide: https://dortania.github.io/OpenCore-Install-Guide/

## Driver & Kexts

- AppleALC
- IntelMausi
- Lilu
- NVMeFix
- SMCProcessorr
- SMCSuperIO
- USBInjectAll
- USBPorts
- VoodooTSCSync
- WhateverGreen

## WORKING

- Audio, speaker and microphone work.
- Network: Ethenet and Wifi.
- USB Ports on the back of motherboards. (Mapped)
- One Internal-USB at bluetooth component.
- USB 3.0 enabled.
- Hardware acceleration is fully support (using VDADecoderChecker)
- Shutdown and restart.
- Sleep mostly works. (Computer & keyboard's led turn off when sleeping)

## Need fix

- Sleep sometimes causes panic (VirtualSMC kext)
