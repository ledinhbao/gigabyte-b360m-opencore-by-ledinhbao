# Opencore EFI and settings

## My desktop specification

- Motherboard: Gigabyte B360M Gaming
- Chipset: Intel Core i7-8700 3.20GHz
- RAM: 4x Corsair Vengeance LPX 8GB DDR4 2666MHz
- dGPU: Gigabyte Radeon™ RX 580 GAMING 8G
- Audio: Realtek ALC892
- Bluetooth: Broadcom BRCM20702

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
- USBMap
- VoodooTSCSync
- WhateverGreen

## WORKING

- Audio.
- Network: Ethenet and Wifi.
- USB Ports on the back of motherboards. (Mapped)
- One Internal-USB at bluetooth component.
- Hardware acceleration is fully support (using VDADecoderChecker)
- Shutdown and restart.

## Need fix

- Sleep doesn't turn off the case's LED (meant: maybe it did not work)
- Internal usb ports.