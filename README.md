# 🔢 Braun Unsigned Multiplier using GDI Technology

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![Made with Tanner EDA](https://img.shields.io/badge/Tools-Tanner%20EDA-blue.svg)
![Low Power](https://img.shields.io/badge/Focus-Low%20Power-green.svg)
![VLSI](https://img.shields.io/badge/Domain-VLSI-orange.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

---

## 📖 Abstract
This project presents the design and implementation of a **Braun Unsigned Multiplier** using **Gate Diffusion Input (GDI) technology**.  
By leveraging Tanner EDA tools (S-Edit, T-Spice, L-Edit), the design achieves:
- ⚡ **30% reduction in power consumption**  
- 📐 **20% reduction in area**  
- ⏱ Improved delay performance compared to CMOS multipliers  

The optimized layout highlights the advantages of GDI for **low-power VLSI applications**, making this design suitable for **embedded systems, IoT, and portable devices**.

---

## 🏛 Architecture
```mermaid
flowchart TD
    A[Input Operands] --> B[Partial Product Generation (GDI AND Gates)]
    B --> C[Adder Matrix (GDI XOR + Adders)]
    C --> D[Carry-Save Accumulation]
    D --> E[Final Output Product]
```
