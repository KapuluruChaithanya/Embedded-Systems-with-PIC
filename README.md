# Embedded-Systems-with-PIC 

A learning repo for embedded-C programming on PIC microcontrollers.  
This repository contains a collection of small but fundamental embedded-systems projects — blinking LEDs, switch interfaces, peripheral drivers, and examples of UART, SPI, I2C, ADC, PWM, timers, and interrupt handling.  
Designed to showcase firmware-level understanding, hardware-software interfacing, and microcontroller fundamentals.

---

## Why This Repo Exists

Many embedded-systems engineers start with tutorials or isolated code snippets — but this repo is an **organized, progressively growing collection** of embedded experiments.  
Whether you're a beginner exploring microcontroller peripherals, or someone evaluating a firmware developer’s foundational skills, this collection demonstrates **clean C code, peripheral control, and driver-level programming** on PIC MCUs.

It reflects my own learning journey — and serves as a public demonstration of what I can build at a hardware-software level.

---

## Current Contents / Modules

| Module / Folder Name          | Purpose / Features                                                                         |
|------------------------------|--------------------------------------------------------------------------------------------|
| **1_LED_BLINKING/**          | Basic LED toggle example — MCU port output configuration & GPIO control                    |
| **2_Switch_Interface/**      | Reading switch/button inputs and toggling outputs — shows debouncing & GPIO input handling |
| *(future)* **ADC_Demo/**     | ADC-based sensor reading (planned)                                                         |
| *(future)* **UART_Comm/**    | UART driver example + communication routines (planned)                                    |
| *(future)* **SPI_I2C_Demo/** | SPI / I2C peripheral initialization & data exchange (planned)                             |
| *(future)* **PWM_Timer/**    | PWM generation & timer-based control (planned)                                            |
| *(future)* **Interrupts/**   | External/interupts-based event handling (planned)                                         |

>  Modules marked “planned” are under development — roadmap section below.

---

## Technologies, Tools & Microcontroller Setup

- **Language:** Embedded C  
- **Platform:** PIC microcontrollers (useable with MPLAB / MPLAB X or similar IDE) :contentReference[oaicite:1]{index=1}  
- **Build / Flash Tools:** Compiler & programmer as per PIC MCU family (e.g. PIC16, PIC18, etc.)  
- **Hardware Interfaces Covered:** GPIO, Switches, Timer, ADC, UART, SPI, I2C, PWM  
- **Code Style:** Modular — separate driver, application and utility layers to simulate real-world firmware structure  

---

## How to Use / Run / Experiment

1. Clone the repository:  
   ```bash
   git clone https://github.com/KapuluruChaithanya/Embedded-Systems-with-PIC.git

2.Navigate to a module folder, for example:
  cd Embedded-Systems-with-PIC/1_LED_BLINKING

3.Open in your PIC IDE (MPLAB / MPLAB X) — configure MCU, oscillator, and compile.

4.Program the compiled firmware onto a target PIC microcontroller.

5.Observe expected behavior (LED blinking / switch response / UART output, etc.).

I encourage you to first try implementing the problem statement on your own. If you get stuck or something doesn’t work as expected, feel free to refer to the solutions in this repository.

If you'd like to discuss embedded systems or collaborate on projects, feel free to reach out:

**Email:** chaithanyakrd@gmail.com  
**LinkedIn:** https://www.linkedin.com/in/kapuluru-chaithanya  
