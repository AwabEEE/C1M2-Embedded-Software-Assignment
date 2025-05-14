# C1M2 - Embedded Software Assignment

**University of Colorado – Embedded Systems Specialization**

## 💻 Author
**Name:** Awab  
**GitHub:** [AwabEEE](https://github.com/AwabEEE)

---

## 📁 Project Overview

This assignment demonstrates basic memory manipulation in embedded C for both `HOST` and `MSP432` platforms using a Makefile-based build system. It includes:

- Custom Makefile for flexible compilation
- Abstraction for memory operations in `memory.c/.h`
- Platform-specific configuration using preprocessor flags
- Version control with Git
- Successfully pushed to GitHub

---

## 📂 Project Structure


C1M2-Embedded-Software-Assignment/
│
├── Makefile
├── sources.mk
├── msp432p401r.lds
├── include/
│ ├── CMSIS/
│ ├── common/
│ └── msp432/
├── src/
│ ├── main.c
│ ├── memory.c
│ ├── system_msp432p401r.c
│ ├── interrupts_msp432p401r_gcc.c
│ └── startup_msp432p401r_gcc.c
└── README.md ← This file


---

## ⚙️ Build Instructions

### 🔹 For HOST Platform:
```bash
make clean
make build PLATFORM=HOST

🔹 For MSP432 Platform (if you have arm-none-eabi-gcc installed):
make clean
make build PLATFORM=MSP432

make clean
make build PLATFORM=HOST
make compile-all PLATFORM=HOST


🔖 License
MIT / Educational License (see original course note)
