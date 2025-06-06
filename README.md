# AMS1117 3.3V Regulator Module (LDO)

This is a simple **3.3V linear voltage regulator board** based on the **AMS1117-3.3**. It converts 5V input to 3.3V output and can be used to power ESP8266, ESP32, sensors, and other 3.3V logic devices.

## Features

- Input Voltage: 4.5V to 6.5V (typically 5V)
- Output Voltage: Fixed 3.3V
- Max Output Current: ~800mA (with proper heat dissipation)
- Low dropout (LDO): ~1.1V typical
- PCB designed in **KiCad**

## Pinout

| Pin | Description     |
|-----|-----------------|
| IN  | 5V Input        |
| GND | Ground          |
| OUT | 3.3V Output     |

## Usage

- Connect 5V to `IN`, Ground to `GND`
- You’ll get regulated 3.3V at the `OUT` pin
- Use decoupling capacitors for stability (e.g., 10uF and 22uF at IN and OUT resp.)

## Files Included

- KiCad project files (`.kicad_pcb`, `.sch`, etc.)
- Gerber files for fabrication
- Schematic PDF
- Board render 

## Preview

---![Screenshot from 2025-06-06 15-29-35](https://github.com/user-attachments/assets/9672bc9e-badc-49da-980f-10da88ea7abf)

---![Screenshot from 2025-06-06 15-30-10](https://github.com/user-attachments/assets/de00f7d0-868d-4755-a2a4-48064d4837b1)


For powering ESPs and low-voltage devices
