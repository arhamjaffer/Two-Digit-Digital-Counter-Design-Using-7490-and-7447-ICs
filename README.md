# 🔢 Two-Digit Digital Counter Using 7490 & 7447 ICs

<div align="center">

![Digital Electronics](https://img.shields.io/badge/Digital-Electronics-blue?style=for-the-badge)

![PCB Design](https://img.shields.io/badge/PCB-Design-success?style=for-the-badge)

![TTL Logic](https://img.shields.io/badge/TTL-Logic-orange?style=for-the-badge)

</div>

---

## 📌 Project Overview

This project implements a two-digit decimal counter capable of counting from **00 to 99** using TTL logic ICs.

The design utilizes:

- 7490 Decade Counter IC
- 7447 BCD to Seven Segment Decoder IC
- Common Anode Seven Segment Displays

The counter automatically increments and displays the count on two seven-segment displays.

---

## ⚙️ Components Used

| Component | Quantity |
|------------|----------|
| 7490 Decade Counter IC | 2 |
| 7447 Decoder Driver IC | 2 |
| Common Anode Seven Segment Display | 2 |
| Clock Source | 1 |
| Resistors | Multiple |
| Power Supply (5V) | 1 |

---

## ✨ Features

- Counts from 00 to 99
- Automatic carry generation
- TTL Logic Implementation
- Seven Segment Display Output
- Educational Digital Electronics Project
- Expandable to Higher Digits

---

## 🧠 Working Principle

### Units Counter

The first 7490 counts clock pulses from 0 to 9.

### Tens Counter

After every 10 counts, a carry pulse increments the second 7490.

### Display Driver

Each 7447 converts BCD output into signals for the seven-segment displays.

This allows the count to be displayed as:

```text
00 → 01 → 02 → ... → 98 → 99
```

---

## 📷 Project Gallery

<h2 align="center">📷 Project Gallery</h2>

<h3 align="center">Circuit Schematic</h3>

<p align="center">
<img src="https://github.com/arhamjaffer/Two-Digit-Digital-Counter-Design-Using-7490-and-7447-ICs/blob/main/schematic.PNG" width="850">
</p>

<h3 align="center">PCB Layout</h3>

<p align="center">
<img src="https://github.com/arhamjaffer/Two-Digit-Digital-Counter-Design-Using-7490-and-7447-ICs/blob/main/pcb%20view.PNG" width="850">
</p>

<h3 align="center">3D PCB Views</h3>

<table align="center">
<tr>
<td align="center">
<img src="https://github.com/arhamjaffer/Two-Digit-Digital-Counter-Design-Using-7490-and-7447-ICs/blob/main/front%20pcb.PNG" width="450"><br>
<b>Front View</b>
</td>

<td align="center">
<img src="https://github.com/arhamjaffer/Two-Digit-Digital-Counter-Design-Using-7490-and-7447-ICs/blob/main/back%20pcb.PNG" width="450"><br>
<b>Back View</b>
</td>
</tr>
</table>
---

## 🎯 Learning Outcomes

✔ Digital Logic Design

✔ BCD Counting

✔ Seven Segment Display Interfacing

✔ TTL Logic Circuits

✔ Hardware Troubleshooting

✔ PCB Design

---

## 🚀 Applications

- Digital Counters
- Frequency Counters
- Event Counters
- Educational Electronics Labs
- Embedded System Prototyping

---

## 👨‍💻 Author

### Arham Jaffer

Electrical Engineering Student

PCB Designer | Embedded Systems Developer | IoT Enthusiast

---

⭐ If you found this project useful, please consider giving it a star.
