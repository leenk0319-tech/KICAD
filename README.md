# KICAD
서로 다른 전압(5V / 3.3V)을 사용하는 MCU와 센서 간 안정적인 I2C 통신을 위해 PCA9306 기반 양방향 레벨 시프터 PCB를 설계하고, Gerber/BOM까지 제작한 프로젝트.
## Overview
This project is a 5V ↔ 3.3V bidirectional I2C level shifter PCB based on the PCA9306 (Texas Instruments).  
It enables safe communication between 5V MCUs (e.g., Arduino) and 3.3V sensors.

---

## Key Features
- Bidirectional I2C level shifting using PCA9306
- Supports 5V ↔ 3.3V voltage translation
- Pull-up resistors for SDA and SCL lines
- Decoupling (0.1µF) and bulk capacitors (10µF)
- 2-layer PCB with bottom GND plane
- Gerber and BOM files included

---

## Tools Used
- KiCad 9
- PCA9306 (TI)

---

## Repository Structure

---

## Schematic Preview
(Add schematic image here)

---

## PCB Preview
(Add PCB top / 3D image here)

---

## Manufacturing
Gerber and Drill files are included and ready for fabrication.

---

## Applications
- Arduino ↔ 3.3V sensor interface
- MCU ↔ OLED / IMU / I2C peripherals



