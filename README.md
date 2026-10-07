<h1 align="center"> macOS Tahoe on HP EliteBook 840 G5 </h1>

<p align="center">
  <img src="macOS_HP_EliteBook_840_G5.png" alt="HP EliteBook 840 G5 running macOS Tahoe" width="700"/>
</p>

<h4 align="center"> OpenCore EFI for Hackintosh HP EliteBook 840 G5 </h4>

<p align="center">Created & supported by jellobo</p>

<p align="center">
  <img src="https://img.shields.io/badge/macOS-Tahoe%2026.0-9cf" width="130"/>
  <img src="https://img.shields.io/badge/OpenCore-1.0.8-9cf" width="130"/>
  <img src="https://github.com/j03ll0b0/hpelitebook-840-g5-efi/releases/download/latest/EFI.svg" width="115"/>
</p>

## What works

- CPU: Intel i5-7300U (2 cores / 4 threads, native PM)
- Graphics: Intel UHD 620 (full acceleration, HDMI mirror)
- Thunderbolt 3: 10 Gbps sustained
- Audio: AppleALC (alcid=3), internal + headset
- Wi-Fi / Bluetooth: Intel 8265 (AirportItlwm + IntelBluetoothFirmware)
- Sleep / Wake: Deep sleep reliable
- USB: USB 3.0 mapped
- NVMe SSD: CT2000P3PSSD8 (NVMeFix for APST)
- Battery / Charging: SMCBatteryManager
- Keyboard / Trackpad: VoodooPS2 + VoodooI2C, gestures work
- Ethernet: Intel I219-LM (IntelMausi.kext — standard version without VT-d/IOMMU support; VT-d aware version disabled, not stable on Tahoe)

## What's included

- `EFI-PAGE.html` — full visual documentation
- `EFI-CLEAN/` — clean OpenCore folder with placeholders (MLB, ROM, Serial, UUID must be filled)
- `OC/config.plist` — cleaned (placeholders for sensitive identifiers)

## References

Based on open-source work by yusufklncc, kmasterycsl, timbachmann, tblesshack (see [`references`](#)).
