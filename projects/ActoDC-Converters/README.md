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

## 5. Schematic Diagram
Below is the circuit schematic for the **12V AC to DC converter**:
<img width="400" alt="Schematic Circuit" src="https://github.com/user-attachments/assets/025d0fe9-a32c-459b-a3b8-9f783927a350" />



## 6. PCB Layout
The PCB layout of the converter is designed to be compact and efficient.

<img width="400" alt="AC-DC 12V PCB-Circuit" src="https://github.com/user-attachments/assets/3cc5e951-0055-4d89-b015-4d9bb22bcb65" />


## 7. How to Use
1. Connect **12V AC** to **J1**.
2. The bridge rectifier and capacitor convert AC to **DC**.
3. A stable **DC voltage** is available at **J2**.
4. The **LED indicator (D5)** confirms operation.

## 8. Project Report
### 8.1 Design Considerations
- The **diodes (1N4007)** were chosen for their **high voltage and current handling capacity**.
- A **large capacitor (1000µF)** ensures minimal ripple and stable DC output.
- The **LED indicator** provides a quick status check for power availability.

### 8.2 Testing and Results
- The output voltage was measured at **approximately 12V DC**.
- Ripple voltage was found to be **within acceptable limits (~1V peak-to-peak under load)**.
- The circuit successfully powered **LED strips and small DC motors**.

### 8.3 Improvements and Future Work
- Adding a **voltage regulator (e.g., 7812 or LM317)** for precise voltage control.
- Implementing **overcurrent protection** to prevent damage from short circuits.
- Designing a **more compact SMD version** for efficient PCB manufacturing.

## 9. Conclusion
The **12V AC to DC Converter** is a simple yet effective circuit for obtaining stable DC voltage from an AC source. It can be used in various applications, including power supplies and embedded systems. Future improvements can enhance efficiency and add safety features for more robust operation.

---

*Author: [Your Name]*
