<div align="center">

# Uzair Ashfaq

**Embedded Systems Engineer**

Firmware • RFID Systems • RTLS • IoT • Hardware–Software Integration

[![Portfolio](https://img.shields.io/badge/Portfolio-uzairashfaq85.github.io-4B3F8C?style=flat-square&logo=githubpages&logoColor=white)](https://uzairashfaq85.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-uzairashfaq85-4B3F8C?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/uzairashfaq85)
[![GitHub](https://img.shields.io/badge/GitHub-uzairashfaq85-4B3F8C?style=flat-square&logo=github&logoColor=white)](https://github.com/uzairashfaq85)
[![Email](https://img.shields.io/badge/Email-uzairashfaq85@gmail.com-4B3F8C?style=flat-square&logo=gmail&logoColor=white)](mailto:uzairashfaq85@gmail.com)

</div>

---

## About

Embedded software engineer with firmware development and PCB design experience across industrial and IoT systems, currently specializing in UHF RFID/RTLS. I build reliable embedded software close to the hardware — real-time data ingestion, device communication, structured payload construction, and the integration work that takes a system from bench prototype to production deployment.

Most recently I built and deployed a production RFID Smart Space Portal pipeline at Acceliot on Impinj R700 and Zebra FXR90 readers, achieving 99.8% average accuracy in real-world retail testing. My focus is the parts of a system that have to actually work in the field: reliability, debugging, clean device-to-system data flow, and measurable outcomes.

---

## Core Technical Focus

| Area | Practical Scope |
| --- | --- |
| Embedded Software | C / Embedded C/C++ on STM32, PIC18F, ESP32; bare-metal and FreeRTOS |
| Firmware Development | Interrupt-driven control loops, peripheral integration, hardware bring-up |
| RFID Systems | UHF RFID reader integration (Impinj R700, Zebra FXR90), EPC Gen2, LLRP |
| RTLS-Related Systems | RFID data ingestion, phase/RSSI data processing, session-state management |
| IoT Device Integration | IoT Device Interface, device-to-system telemetry, structured payloads |
| Hardware–Software Integration | 4-layer PCB design (Altium), sensor interfacing, MCU peripheral bring-up |
| Communication Protocols | UART, SPI, I2C, CAN, BLE |
| Debugging & Validation | Firmware debugging, signal-integrity work, real-world deployment testing |
| Production Deployment | Standalone deployment packaging, live customer-site deployment support |

---

## Skills

**Languages:** C, Embedded C/C++, Python, ARM Assembly, VHDL, Verilog

**Embedded / Firmware:** STM32 (HAL/LL), PIC18F, ESP32, AVR, Raspberry Pi, FreeRTOS, Zephyr, Embedded Linux, UART, SPI, I2C, CAN, BLE, GPIO/event handling, interrupts, hardware debugging

**RFID / RTLS / IoT:** UHF RFID, Impinj R700, Zebra FXR90, EPC Gen2, LLRP, IoT Device Interface, RFID phase/RSSI data processing, structured payload construction, reader integration, device-to-system data flow

**Data & ML:** NumPy, Pandas, SciPy, scikit-learn

**Tools:** Altium Designer, STM32CubeIDE, Xilinx Vivado/Vitis, QuestaSim, MATLAB, Git, GitHub, JTAG debuggers, Linux

---

## Featured Work

### Production RFID / Smart Space Portal (SSP) System — Acceliot

An embedded RFID system delivering real-time data ingestion, structured payload construction, and classification-response handling for retail RTLS workflows, deployed at a live customer site.

| Metric | Detail |
| --- | --- |
| Deployment | Live retail / production environment |
| Hardware | Impinj R700, Zebra FXR90 |
| Scale | Tested on carts carrying 500+ RFID-tagged items |
| Accuracy | 99.8% average accuracy in real-world retail testing |
| Scope | RFID data ingestion, payload construction, classification-response handling |
| Focus | Reliability, integration, debugging, production readiness |
| Reference | [Portfolio case study →](https://uzairashfaq85.github.io) |

- Built the full Python reader infrastructure: EPC Gen2 data ingestion via LLRP and IoT Device Interface, GPIO/event handling, and RSSI/phase data processing.
- Constructed structured payloads and handled real-time IN/OUT classification responses returned by the SSP for retail RTLS workflows.
- Developed event-driven state-machine logic for multi-crossing RFID session management, with a SQLite-backed EPC inventory tracker and atomic CSV export.
- Packaged and delivered a standalone deployment binary with a menu-driven terminal interface (no external dependencies), successfully deployed at the customer site for live retail operations.

---

## Public Projects

| Project | Description | Stack | Repository |
| --- | --- | --- | --- |
| RSA Modular Arithmetic — FPGA | VHDL RSA pipeline on Basys-3: FSM modular multiplier, square-and-multiply exponentiation, 7-segment integration, verified under GHDL | VHDL, Basys-3, Vivado, GHDL | [GitHub](https://github.com/uzairashfaq85) |
| RFID Phase-Based Localization | Python RFID phase/RSSI data processing for indoor positioning experiments | Python, RFID, Signal Processing | [GitHub](https://github.com/uzairashfaq85) |

> **TODO before publishing:** replace the two repository links above with exact repo URLs, and add 1–2 more real public repositories (embedded firmware / IoT / C systems) after confirming names. Do not publish with placeholder links.

---

## Experience

**Embedded Systems Engineer Intern — Acceliot, LCIS Laboratory** · Valence, France
*Feb 2026 – Present*

- Developed and deployed a production RFID Smart Space Portal (SSP) pipeline on Impinj R700 and Zebra FXR90 readers, achieving 99.8% average accuracy in real-world retail testing with carts carrying 500+ RFID-tagged items.
- Built the full Python reader infrastructure: EPC Gen2 ingestion via LLRP and IoT Device Interface, GPIO/event handling, RSSI/phase data processing, structured payload construction, and real-time IN/OUT classification-response handling.
- Packaged and delivered a standalone deployment binary with a menu-driven terminal interface; deployed at the customer site for live retail operations.
- Developed event-driven state-machine logic for multi-crossing session management and a SQLite-backed EPC inventory tracker with atomic CSV export.

*Skills: Python, UHF RFID, Impinj R700, Zebra FXR90, EPC Gen2, LLRP, Linux, embedded data pipelines*

**Embedded Systems Engineer — Lean Automation** · Abbottabad, Pakistan
*Sep 2024 – Aug 2025*

- Developed bare-metal C firmware for STM32 and PIC18F microcontrollers, integrating UART, I2C, and interrupt-driven control loops for industrial automation systems.
- Designed and revised 4-layer PCBs in Altium Designer, improving signal integrity and enabling cleaner hardware bring-up across multiple industrial control projects.

*Skills: Embedded C, STM32, PIC18F, UART, I2C, Altium Designer, firmware debugging*

---

## Education

**M.Sc. Embedded Systems Security (IMESS)** · Grenoble INP–Esisar, Université Grenoble Alpes, Valence, France · *Sep 2025 – Sep 2026*

**B.Sc. Electrical (Electronics) Engineering** · COMSATS University Islamabad, Pakistan · *Sep 2020 – Aug 2024*

---

## GitHub Stats

<div align="center">

![Uzair's GitHub stats](https://github-readme-stats.vercel.app/api?username=uzairashfaq85&show_icons=true&theme=tokyonight&hide_border=true&count_private=false)

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=uzairashfaq85&theme=tokyonight&hide_border=true&layout=compact)

</div>

> **Check before publishing:** confirm these cards render numbers that *support* the production narrative. If commit counts are thin or the language mix is dominated by coursework, remove this section — a weak stats card undercuts a strong CV.

---

## Currently Focused On

```yaml
Currently_Focused_On:
  - Production RFID/RTLS reader infrastructure and deployment reliability
  - Embedded software and firmware debugging
  - Hardware-software integration on MCU and Linux targets

Learning:
  - Embedded Linux and edge deployment
  - Real-time firmware architecture
  - RFID reader-integration optimization

Open_To:
  - Embedded Systems Engineer roles
  - Firmware Engineer roles
  - RFID / RTLS Engineer roles
  - IoT Engineer roles
```

---

## Contact

[![Email](https://img.shields.io/badge/Email-uzairashfaq85@gmail.com-4B3F8C?style=flat-square&logo=gmail&logoColor=white)](mailto:uzairashfaq85@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-uzairashfaq85-4B3F8C?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/uzairashfaq85)
[![GitHub](https://img.shields.io/badge/GitHub-uzairashfaq85-4B3F8C?style=flat-square&logo=github&logoColor=white)](https://github.com/uzairashfaq85)
[![Portfolio](https://img.shields.io/badge/Portfolio-uzairashfaq85.github.io-4B3F8C?style=flat-square&logo=githubpages&logoColor=white)](https://uzairashfaq85.github.io)

---

<div align="center">

*Building reliable embedded systems where firmware, hardware, and real-world deployment meet.*

</div>
