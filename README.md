# NRF24L01 Functional Remote Control Board 🎮📡

A custom-designed wireless remote control PCB based on the **Arduino Nano** and **NRF24L01+PA+LNA** wireless communication module.

This board is designed to provide a compact and functional controller with **dual-axis joysticks**, push buttons, and wireless communication for robotics and embedded systems projects.

## 🚀 Features

* 🎮 **2 × Dual-Axis Joysticks**
* 📡 **NRF24L01+PA+LNA** wireless communication
* 🧠 **Arduino Nano** controller
* 🔘 **2 × Push Buttons**
* 🟢 **5mm Green Status LED**
* ⚡ **9V Power Input**
* 🔧 Custom PCB designed with **EasyEDA**
* 🛠️ Through-hole components for easy assembly
* 📐 Custom PCB layout with labeled components

## 🧩 Bill of Materials

| # | Component             | Footprint                            | Qty |
| - | --------------------- | ------------------------------------ | --: |
| 1 | K4-6×6_TH Push Button | `KEY-TH_4P-L6.0-W6.0-P4.50-LS6.5`    |   2 |
| 2 | 5mm Green LED         | `LED-TH_BD5.0_GREEN`                 |   1 |
| 3 | 330Ω Resistor         | `R_AXIAL-0.3`                        |   1 |
| 4 | Arduino Nano          | `COMM-TH_ARDUINO_NANO`               |   1 |
| 5 | NRF24L01+PA+LNA       | `COMM-TH_L41.0-W15.5-P2.54_NRF24L01` |   1 |
| 6 | 252A503A40TA Joystick | `JOYSTICK-TH_252BXXXXXXB`            |   2 |
| 7 | 9V Power Connector    | `HDR-F-2.54_1X2`                     |   1 |

## 🔌 Main Components

### Arduino Nano

The Arduino Nano acts as the main microcontroller of the remote control. It reads the joystick and button inputs and controls the wireless communication.

### NRF24L01+PA+LNA

The NRF24L01+PA+LNA module provides wireless communication between the controller and the receiving device.

It can be used for:

* 🤖 Robot control
* 🚗 RC vehicle projects
* 🦾 Robotic arms
* 📡 Custom wireless embedded systems

### Dual Joysticks

Two analog joysticks are used to provide multiple control axes. This allows the controller to send independent directional commands to a robot or other remote-controlled system.

### Push Buttons

Two push buttons are included for additional digital commands such as:

* Mode selection
* Start/stop
* Special functions
* Robot actions

## 🖥️ PCB Design

The PCB was designed using **EasyEDA** with a custom board layout.

The design includes:

* Component placement
* Power routing
* Signal routing
* Arduino Nano interface
* NRF24L01 interface
* Dual joystick connections
* Status LED
* Control buttons

## 📷 PCB Preview

The current PCB layout includes all major components and routed connections.

> The PCB design is currently intended as a custom prototype/functional controller board.

## 🛠️ Design Software

* **EasyEDA** — Schematic & PCB Design
* **Arduino IDE / PlatformIO** — Firmware Development
* **GitHub** — Version Control & Project Documentation

## 📁 Repository Structure

```text
NRF24L01-Functional-Remote-Control-Board/
│
├── README.md
├── PCB/
│   └── PCB Design Files
│
├── Schematic/
│   └── Schematic Files
│
├── BOM/
│   └── Bill of Materials
│
└── Firmware/
    └── Arduino Source Code
```

## 🎯 Project Goal

The main goal of this project is to develop a **custom, reusable wireless controller PCB** that can be used in different robotics and embedded systems projects.

The modular design allows the same controller to be adapted for different robots and applications by changing the firmware.

## 🔮 Future Improvements

* [ ] Add battery charging and protection circuit
* [ ] Add power switch
* [ ] Add battery voltage monitoring
* [ ] Improve PCB power distribution
* [ ] Add an enclosure
* [ ] Develop NRF24L01 transmitter firmware
* [ ] Develop compatible receiver firmware
* [ ] Test the final assembled PCB
* [ ] Produce the PCB as a physical prototype

## 👨‍💻 Author

**Enes Baran Doğan**

Electronics • Embedded Systems • Robotics • PCB Design

---

⭐ If you find this project useful, consider giving the repository a star!
