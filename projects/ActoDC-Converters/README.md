# 12V AC to DC Converter

## 1. Introduction
This project converts **12V AC to DC** using a **bridge rectifier** and a **capacitor filter**, providing a stable DC output. It is commonly used for powering electronic circuits that require a steady DC voltage.

## 2. Components
- **J1, J2** - Screw Terminals (Input/Output)
- **D1-D4 (1N4007)** - Bridge Rectifier Diodes
- **C1 (1000µF)** - Smoothing Capacitor
- **R1 (10KΩ), R2 (2.2KΩ)** - Resistors for LED indication
- **D5 (LED)** - Power Indicator

## 3. Circuit Operation
### 3.1 AC Input Stage
- The **12V AC input** is connected via **J1**.
- The alternating current flows into the bridge rectifier stage.

### 3.2 Rectification Stage
- **D1-D4 (1N4007 diodes)** form a **bridge rectifier**, converting **AC to pulsating DC**.
- The rectified output consists of only positive voltage cycles.

### 3.3 Filtering Stage
- The **1000µF capacitor (C1)** smooths the pulsating DC, reducing ripples.
- This results in a more stable **DC output**.

### 3.4 LED Indicator
- **R1 (10KΩ) and R2 (2.2KΩ)** limit current to **D5 (LED)**.
- The LED lights up when power is available, indicating proper circuit operation.

## 4. Applications
- Powering DC circuits
- Battery charging
- LED lighting systems
- Embedded system power supplies

  
<img width="400" alt="AC-DC 12V PCB-Circuit" src="https://github.com/user-attachments/assets/68d456fc-b50e-4428-9792-6d6c42ca4573" />

## 5. How to Use
1. Connect **12V AC** to **J1**.
2. The bridge rectifier and capacitor convert AC to **DC**.
3. A stable **DC voltage** is available at **J2**.
4. The **LED indicator (D5)** confirms operation.
