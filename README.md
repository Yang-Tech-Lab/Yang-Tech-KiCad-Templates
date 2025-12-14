# Yang-Tech KiCad Templates 🛠️

**Professional Hardware Design Standards for KiCad 8.0+**

This repository contains the standard engineering templates used by **Yang-Tech-Lab** for high-frequency and IoT PCB designs.

## 📂 Contents

### 1. 4-Layer Impedance Controlled Template (`/Templates/4Layer_JLC_Impedance`)
- **Stackup:** Matches JLCPCB JLC04161H-3313 (7628+3313).
- **Impedance Rules:** Pre-configured constraints for:
  - 90Ω Differential Pairs (USB/HDMI)
  - 50Ω Single-Ended RF (Antenna)
- **Design Rules:** Conservative 5mil/5mil clearance for high yield.

### 2. ESP32-S3 Minimal System (`/Library/ESP32-S3-Dev`)
- A production-ready schematic symbol and footprint for ESP32-S3-WROOM-1.
- Includes auto-reset circuit and USB-C protection (ESD) best practices.

## 🚀 Why use this?
Most default templates lack manufacturing awareness. This template is **DFM-verified** (Design for Manufacturing) to ensure your board works on the first try.

---

### 👨‍💻 Need Custom Design?
I am available for freelance work! If you need a customized version of this board or full firmware support:

- **Hire me on Fiverr:** [INSERT YOUR FIVERR LINK HERE]
- **Services:** Schematic Capture, PCB Layout, ESP32 Firmware (Micropython/C++), Automated BOM Generation.

*Maintained by Yang-Tech-Lab. Open Source for the community.*
