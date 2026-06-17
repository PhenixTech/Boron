# Boron: The Handheld Console Project

Boron is a standalone handheld console designed to explore embedded systems, custom firmware, hardware design, and experimentation. Built around modern microcontrollers, Boron serves as both a learning platform and a capable portable device.

---

<details>
<summary><b>Boron V1 MVP (Minimum Viable Product)</b></summary>

## Overview

The first proof-of-concept version of Boron, focused on validating the core hardware and software architecture.

### Key Features

* **Microcontroller:** Waveshare RP2350 Plus (4MB flash) soldered directly to a custom PCB
* **Controls:** 8 buttons (D-pad, A, B, Plus, and Minus)
* **Display:** 128×64 monochrome OLED display
* **Expandable:** MAG4 connector (4-pin magnetic connector)
* **Battery:** 2500mAh Li-ion battery
* **Cartridge System:** SD connector-based swappable cartridge system

### Additional Information

This version had several issues with footprints and PCB routing, and the cartridge system was never fully tested. Despite these shortcomings, the console operated correctly and the identified issues were resolved in later revisions.
Note, this was my first ever PCB !

</details>

---

<details>
<summary><b>Boron V2 (Neutrino Edition)</b></summary>

## Overview

A major revision focused on improving design, expandability, and usability while keeping the same MCU and introducing a higher-resolution display.

### Key Features

* **Microcontroller:** Waveshare RP2350 Plus with 16MB of flash storage
* **Controls:** 10 buttons, including a D-pad and action buttons
* **Display:** 240×240 IPS display for sharper graphics
* **Expandable:** 10-pin rear expansion connector for future modules
* **Battery:** 2500mAh Li-ion battery

### Project Goals

* Explore custom firmware development
* Serve as a portable experimentation platform
* Provide a foundation for future Boron revisions

</details>

---

<details>
<summary><b>Boron V3 (Current Development)</b></summary>

## Overview

The next-generation Boron platform focused on connectivity, audio support, expandability, and a more polished user experience.

### Planned Features

* RP2350-based single-board design
* ESP32-C3 Wi-Fi + Bluetooth coprocessor
* Fully swappable control layout
* MicroSD-based software system
* Audio output and microphone support
* Improved battery capacity (3000mAh)
* Thinner device with an optimized internal layout

### Status

Currently in development.

</details>
