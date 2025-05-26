# STM32F030 Custom Board

This project contains the KiCad design files and documentation for a custom microcontroller development board based on the **STM32F030** series MCU. The board is designed for low-cost embedded systems and prototyping.


---

## 📦 Features

- **Microcontroller**: STM32F030F4P6 (ARM Cortex-M0, 48MHz, 16KB Flash, 4KB RAM)
- **Power Supply**: 3.3V regulated via AMS1117-3.3 or LDO (external 5V input)
- **Programming Interface**: SWD (via ST-Link or similar)
- **Onboard Peripherals**:
  - User LED (GPIO)
  - Tactile Reset & Boot buttons
  - Decoupling capacitors
  - crystal oscillator (8MHz)
- **IO Pins**: All GPIOs exposed on 2.54mm headers
- **Form Factor**: Compact, breadboard-friendly design

---
## 🛠️ Tools Used

- **KiCad**: v6.0 or later (for schematic and PCB design)
- **STM32CubeIDE** *(optional)*: For writing and debugging firmware
- **ST-Link v2**: For flashing and debugging over SWD
- **OpenOCD** / **pyOCD**: For CLI programming (optional)

---

## 🔧 Getting Started

### ✅ Hardware Setup

1. Connect 5V and GND to the board (via USB or external header).
2. Flash firmware using ST-Link via SWD pins.
3. Press **Reset** or toggle **BOOT** pin to enter programming mode if needed.

---
