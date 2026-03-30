# Boardoza SAM-M10Q GNSS Breakout Board

The **Boardoza SAM-M10Q GNSS Breakout Board** is a high-performance global navigation satellite system (GNSS) solution based on the **u-blox SAM-M10Q** module. Featuring an integrated patch antenna, SAW filter, and LNA (Low Noise Amplifier), this board delivers exceptional sensitivity, fast acquisition time, and robust interference immunity for reliable positioning.

Built on the **u-blox M10 standard precision GNSS platform**, the SAM-M10Q supports concurrent reception of **GPS, GLONASS, Galileo, and BeiDou** signals. With multi-constellation support and advanced anti-jamming and anti-spoofing detection, this breakout board is ideal for applications such as asset tracking, drone navigation, smart agriculture, robotics, fleet management, wearable tracking devices, and IoT positioning systems.

## [Click here to purchase!](https://www.ozdisan.com/ureticiler/boardoza)

| Front Side | Back Side |
|:---:|:---:|
| ![Boardoza SAM-M10Q Front](./assets/UBLOX_SAM_M10Q%20Front.png) | ![Boardoza SAM-M10Q Back](./assets/UBLOX_SAM_M10Q%20Back.png) |

---

## Key Features

- **Multi-GNSS Support:** Concurrent reception of GPS, GLONASS, Galileo, and BeiDou signals.
- **Integrated Patch Antenna:** Built-in antenna design for compact and simplified integration.
- **High Sensitivity Reception:** Excellent satellite acquisition even in weak signal environments.
- **Advanced Jamming & Spoofing Detection:** Reports interference attempts directly to the host MCU.
- **Flexible Communication:** Supports both **UART** and **I²C** interfaces.    
- **Wide Input Voltage Range:** Operates with both **3.3V and 5V** systems.

---

## Technical Specifications

**Model:** u-blox SAM-M10Q  
**Manufacturer:** Boardoza     
**Manufacturer IC:** u-blox AG  
**GNSS Platform:** u-blox M10  
**Input Voltage:** 3.3V – 5.5V  
**Power Input Type:** 4-pin 2.50mm header  
**Voltage Logic Level:** 3.3V (PPS, RST, INT, SAFE pins), other pins are both compitable with 3.3 and 5V      
**Communication Interfaces:** UART, I²C   
**Concurrent GNSS:** GPS, GLONASS, Galileo, BeiDou  
**Integrated Components:** Patch Antenna, SAW Filter, LNA  
**Position Accuracy:** ~1.5 m CEP (typical, open sky)  
**Cold Start Time:** ~23 s (typical)  
**Hot Start Time:** ~1 s (typical)  
**Operating Temperature:** -40°C to +85°C  
**Board Dimensions:** 40mm x 40mm   

---

## Board Pinout

### ( J1 ) UART Connector

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | VCC | Power Supply (3.3V – 5.5V) |
| 2 | RXD | UART Receive Data |
| 3 | TXD | UART Transmit Data |
| 4 | GND | Ground |

---

### ( J2 ) I²C Connector

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | VCC | Power Supply (3.3V – 5.5V) |
| 2 | SCL | I²C Serial Clock |
| 3 | SDA | I²C Serial Data |
| 4 | GND | Ground |

---

### ( J3 ) Control & Timing Pins

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | PPS (TIMEPULSE) | Precision timing output (PIO4, 2 mA drive capability) |
| 2 | RST | System Reset (Active Low, ≥1 ms pulse) |
| 3 | INT | External Interrupt Input |
| 4 | SAFE | Safeboot Mode (Active Low, leave open if unused) |

---

## Board Dimensions

<img src="./assets/UBLOX_SAM_M10Q Dimensions.png" alt="Board Dimensions" width="450"/>

---

## Step Files

[Boardoza SAM-M10Q.step](./assets/UBLOX_SAM_M10Q%20Step.step)

---

## Datasheet

[SAM-M10Q Datasheet (UBX-22013293)](./assets/UBLOX_SAM_M10Q%20Datasheet.pdf)

---

## Version History

- V1.0.0 - Initial Release

---

## Support

- If you have any questions or need support, please contact **support@boardoza.com**

---

## **License**

This repository contains both hardware and software components:

### **Hardware Design**

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

All hardware design files are licensed under [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

### **Software/Firmware**

[![BSD-3-Clause][bsd-shield]][bsd]

All software and firmware are licensed under [BSD 3-Clause License][bsd].

[bsd]: https://opensource.org/licenses/BSD-3-Clause
[bsd-shield]: https://img.shields.io/badge/License-BSD%203--Clause-blue.svg
