View this project on [CADLAB.io](https://cadlab.io/project/29902). 

# Electronic Fuse (e-Fuse) & Over-Current Protection PCB

Comparator-Based Smart Load Disconnect for 24V Systems

---

## 📌 Project Overview
This project implements an electronic fuse (e-Fuse) system that protects a load from over-current and short-circuit conditions.

Instead of a traditional fuse that must be replaced after failure, this design detects excessive current in real time, disconnects the load using a MOSFET, and allows reset via a push button.

The board demonstrates current sensing, analog decision making, and power switching techniques used in industrial and embedded hardware.

---

## 🎯 Features
- Designed for 24V DC systems
- Real-time current monitoring
- Adjustable fault threshold
- Automatic load shutdown during over-current
- Manual reset using push button
- Fault indication LED
- Comparator-based fast response
- Reusable protection (no fuse replacement)

---

## 🧠 Working Principle
1. Load current flows through a shunt resistor.
2. Voltage across the shunt is proportional to current.
3. Comparator checks this voltage against a reference.
4. If current exceeds limit:
   - MOSFET is turned OFF
   - Load disconnects
   - Fault LED turns ON
5. Pressing reset allows system restart.

---

## 🔧 Main Components
- LM393 – Voltage comparator
- N-MOSFET – High current switching
- Shunt resistor – Current sensing
- Reference divider – Threshold setting
- Pull-up resistor – Comparator output
- LED – Fault indication
- Push button – Reset control

---

## ⚡ Electrical Flow
24V Input → Shunt → MOSFET → Load
↓
Comparator Decision → Shutdown


---

## 🛡 Protection Capabilities
- Over-current protection
- Short-circuit response
- Controlled restart
- Reduced downtime
- No consumable fuse element

---

## 📐 PCB Design Highlights
- High current path separated from signal area
- Wide copper for load current
- Kelvin-like sensing approach
- Clean comparator routing
- Designed with manufacturable rules
- ERC / DRC verified

---

## 🧪 Applications
- Industrial power distribution
- Robotics
- Battery systems
- Automotive electronics
- Embedded controllers
- Lab power outputs

---

## 🚀 Skills Demonstrated
- Current sensing techniques
- Analog comparator design
- MOSFET gate control
- Fault logic implementation
- Power electronics layout practice

---

## 🧰 Tools Used
- KiCad for schematic and PCB
- GitHub for version control

---

## 👤 Author
GOWTHAMA SAI RAJ R T

Electronics & Communication Engineering  
Focused on Embedded & Hardware Design

---

## 📜 License
Open-source for learning and academic use.
