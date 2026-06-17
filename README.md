# Boron V1–V3

> *A modular handheld console ecosystem for embedded systems, custom firmware, and hardware experimentation.*

![MCU](https://img.shields.io/badge/MCU-RP2350-blue?style=plastic)
![Platform](https://img.shields.io/badge/platform-handheld-green?style=plastic)
![RiscV Cores](https://img.shields.io/badge/RISCV-Hazard3-orange?style=plastic)
![ARM Cores](https://img.shields.io/badge/ARM-M33-orange?style=plastic)


---

## Overview

**Boron** is a modular handheld console platform built around the RP2350 ecosystem.  
It is designed as a testbed for custom firmware, modular hardware design, and portable system experimentation.

The project evolves through iterative hardware revisions, each improving integration, expandability, and usability.

---

## Boron V1 (MVP)

> *Proof-of-concept hardware validation platform*

### Hardware

- **MCU:** Waveshare RP2350 Plus (4MB flash)
- **Display:** 128×64 monochrome OLED
- **Controls:** 8 buttons (D-pad + A, B, Plus, Minus)
- **Battery:** 2500mAh Li-ion
- **Expansion:** MAG4 4-pin magnetic connector
- **Storage:** SD-based cartridge system (prototype)


### Known Issues

- PCB footprint errors in early routing
- Cartridge system never fully validated
- Expansion connector not stress-tested

Despite this, the core system validated successfully and informed all later revisions.

---

## Boron V2 (Neutrino Edition)

> *First production-style PCB with improved usability and display upgrade*

### Hardware

- **MCU:** RP2350 Plus (16MB flash)
- **Display:** 240×240 IPS panel
- **Controls:** 10 buttons (D-pad + action set)
- **Expansion:** 10-pin rear connector
- **Battery:** 2500mAh Li-ion

### Improvements over V1

- Higher resolution display for UI clarity
- Increased flash capacity
- Improved input layout (more action buttons)
- Cleaner PCB routing and expansion design

---

## Boron V3 (Current Development)

> *Next-generation modular handheld with connectivity and audio expansion*

### Planned Hardware

- RP2350-based 16MB flash + 8MB PSRAM 
- **FULLY** single PCB design
- **FULLY** swappable input modules
- ESP32-C3 coprocessor (Wi-Fi + BLE)
- MicroSD-based software system
- Audio output (3.5mm + speaker) + microphone support
- 3000mAh battery system
- Optimized thin design

### Goals

- Fully modular input/output system
- Wireless connectivity layer
- Cleaner electrical and mechanical integration

---

## System Vision

Boron is not a single device : it is a hardware platform.

Each revision moves toward:

- modular expansion interfaces
- interchangeable input layer
- firmware-driven hardware flexibility

---

## Status

| Version | State |
|---|---|
| V1 | Completed (prototype validation) |
| V2 | Completed (refinement stage) |
| V3 | In development |

---
