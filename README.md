**Electronics & Electrical Engineering @ UCL** | PCB design, embedded firmware and FPGAs. I like to play poker in my free time

I have been designing boards for about 3 years now, everything from a Battery Management System for an exoskeleton startup to an NFC business card that plays Flappy Bird. Some of my work is up on [hackster.io/Vertrex](https://hackster.io/Vertrex).

![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![Espressif](https://img.shields.io/badge/ESP--IDF-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion_360-F57C00?style=for-the-badge&logo=autodesk&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-1E8449?style=for-the-badge&logo=v&logoColor=white)

## Currently working on

- Out of order x86 processor 
- A new NFC business card powered by an STM32 which can play flappy bird on a custom 8x8 Led Matrix.
  
## Featured projects

| Project | What it is | Stack |
|---|---|---|
| **[Jane Street ASIC reverse engineering](https://github.com/Vertrex-star/jane-street-challenge)** | Reverse engineered a Jane Street puzzle ASIC starting from a raw GDS layout; extracted the netlist, built every standard cell in Verilog, spatially clustered ~700 gates, and used a SAT solver to derive the winning 122 bit input sequence. | Verilog, Python, SAT, Quartus Prime, ModelSim |
| **Hippos Exoskeletons** | Redesigned their Battery Management System; 60% smaller PCB with added protection features. Also did the MCU/IMU boards, overall hardware topology and IMU firmware. | KiCAD, ESP-IDF, embedded C |
| **Flipper Zero reverse engineering** | Two months and ~80 pages of documentation covering superheterodyne receivers, FM/AM/IQ modulation, SDR principles and the STM32 at its core. Learned a lot about EMI, impedance matching and why 4 to 6 layer boards exist. | STM32, SDR |
| **[UCL Combat Robotics; Team Artemis](https://www.hackster.io/Vertrex/combat-robotics-team-artemis-b70139)** | PCB for our antweight combat robot (150g, 100mm cube limit). Six layer stackup with dedicated power/ground planes around an ESP32-MINI-1, kept compact but still hand solderable with 0805 parts. | ESP32, KiCAD |
| **[Runaway alarm clock; HackLDN 2026](https://www.hackster.io/Vertrex/runaway-hackldn-583737)** | 24h hackathon build: an alarm clock on wheels that drives off when it rings so you have to chase it. Ultrasonic obstacle avoidance + Android app for setting alarms. | Arduino Uno Q, C++, Android Studio |
| **[NFC/PCB business card V3](https://www.hackster.io/Vertrex/nfc-business-card-v3-420ffe)** | Third revision of the PCB business card; adds a 1S LiPo + USB-C charging circuit and an onboard LED matrix driven via shift registers, with UP/DOWN buttons for cycling animation modes alongside the NFC tap to share function. | STM32, KiCAD, shift registers |
| **[How to make an Arduino](https://www.hackster.io/Vertrex/how-to-make-an-arduino-8a2955)** | Built a DIY Arduino from scratch around a bare ATmega328 PU; burning the bootloader, getting the FT232R talking to the chip, and writing up a full guide on how it all works. | ATmega328, FT232R |
| **[RC plane](https://www.hackster.io/Vertrex/rc-plane-project-9ee7b1) + 5 axis robot arm** | Custom transmitter/receiver boards with nRF24L01, and a 3D printed robot arm with torque analysis done in CAD before printing. | Arduino, Fusion 360 || **[Microprocessor Basic ISA](https://github.com/Vertrex-star/Microprocessor-basic-ISA)** | Single cycle 8 bit microprocessor with a custom 10 instruction ISA (and/or/add/sub, andi/ori/addi, beq). Built the ALU, register file, instruction memory, control unit, and PC/branch logic from scratch, with self-checking ModelSim testbenches. | Verilog, Quartus Prime, ModelSim |

## Tools I use

- **EDA:** KiCAD, EasyEDA: 3+ years of schematics, layout, footprints
- **Firmware:** C, C++, embedded C, ESP-IDF, STM32
- **FPGA:** SystemVerilog, Quartus Prime and ModelSim
- **CAD:** Fusion 360

## Get in touch

[![Email](https://img.shields.io/badge/Email-paulvincentbezzina%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:paulvincentbezzina@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Paul_Vincent_Bezzina-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/paulvincentbezzina)
[![Hackster](https://img.shields.io/badge/Hackster.io-Vertrex-2E9FE6?style=for-the-badge)](https://hackster.io/Vertrex)

Always happy to talk hardware, PCBs or FPGA stuff; feel free to reach out.
