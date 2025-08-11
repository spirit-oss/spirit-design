# SPIRIT Smartphone – Hardware Design

<p align="center">
    <img src="https://github.com/user-attachments/assets/99de57de-c5d9-4f54-9140-fb388b046b55" width="20%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Hardware-Open%20Source-blue">
  <img src="https://img.shields.io/badge/Tool-KiCad-green">
  <img src="https://img.shields.io/badge/Status-Prototype-orange">
</p>

---

## About This Repository

This repository contains **all hardware design files** for the SPIRIT smartphone:

- KiCad schematics & PCB layouts  
- Bill of Materials (BOM)  
- Mechanical drawings  
- 3D models for enclosure and components  

It is the **engineering workspace** for SPIRIT’s electronics and physical design — ideal for hardware engineers, PCB designers, and repair/modding enthusiasts.

---

## Hardware Highlights

- **Core Module:** Raspberry Pi Compute Module 5
- **Custom Carrier Board** – connects CM5 to all peripherals  
- **Privacy Hardware Switches** – physical cut-offs for mic, camera, GPS/GSM, and battery  
- **Expandable I/O** – breakouts for unused CM5 pins  
- **Optimized Power Management** – for portable operation

---

## Repository Structure

```
/EDA-kicad       → KiCad project files
/BOM             → Bill of Materials (CSV, XLSX)
/Mechanical      → CAD and enclosure files
/Docs            → Hardware-specific documentation
/Gerbers         → PCB manufacturing files
```

---

## How to Open & Edit

1. **Install KiCad** (v7 or later recommended)  
   [https://kicad.org](https://kicad.org)  
2. Clone this repository:
   ```bash
   git clone https://github.com/your-org/spirit-hardware.git
   ```
3. Open `cm5-carrier.kicad_pro` in KiCad.

---

## PCB Specifications

- **Board Size:** 80mm × 150mm  
- **Layers:** 4-layer design  
- **Main PCB Thickness:** 1.4mm  
- **Primary Components:**
  - USB-C 3.2 connector
  - Dual speakers (CMR-15062S-67)
  - SPH0645LM4H-B digital microphone
  - Arducam camera interface
  - GPS/GSM module (EC25VFA-512-STD)
  - Fingerprint scanner module

---

## Bill of Materials

The full BOM is in `/BOM`.  
It includes supplier links, part numbers, and alternative components.

---

## Prototype Notes

Current stage: **Prototype PCB** in assembly & testing phase.  
Known tasks:
- EMI testing & optimization
- Power routing review
- Thermal performance measurements

---

## Contributing

We welcome:
- PCB layout improvements
- Alternate component sourcing
- Mechanical compatibility suggestions

Please ensure **all contributions** remain KiCad-compatible and are documented.

---

## License

All hardware files are released under an open hardware license (see `/LICENSE`).

---

---

<p align="center">
  <strong>SPIRIT: Taking back control of our digital lives</strong>
</p>
