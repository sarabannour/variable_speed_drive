# Variable Speed Drive

A complete electronic **Variable Speed Drive (VSD)** designed to control the **speed and rotation direction of a DC motor** using Pulse Width Modulation (PWM). The project covers the entire development process, from theoretical analysis and circuit simulation to PCB design, routing, fabrication, soldering, and hardware validation.

# Features

- Adjustable DC motor speed using PWM
- Forward and reverse motor rotation
- Start, Stop, and Emergency Stop controls
- Stable regulated 12V power supply
- Protection against electrical faults
- Complete PCB design and routing
- Circuit simulation before hardware implementation
- Physical PCB fabrication and testing

---

# Project Architecture

The Variable Speed Drive is divided into the following functional blocks:

- Power Supply & Voltage Regulation
- PWM Speed Control
- Control Logic
- Direction Control
- Protection Circuit
- H-Bridge Driver
- Motor Output

---

# Tools Used

| Tool | Purpose |
|------|---------|
| Proteus Design Suite | Circuit design, simulation, PCB routing and 3D visualization |

---

# Electronic Components

Main components used in the project include:

- NE555 Timer
- LM358 Operational Amplifier
- LM393 Voltage Comparator
- CD4011 CMOS NAND Gate
- 7812 Voltage Regulator
- MOSFET Transistors
- Rectifier Diodes
- Zener Diodes
- Electrolytic Capacitors
- Potentiometer
- Heat Sink
- LEDs
- Resistors

---

# Development Process

1. Circuit analysis
2. Component selection
3. Theoretical calculations
4. Proteus simulation
5. PCB schematic design
6. PCB routing
7. PCB fabrication
8. Component soldering
9. Hardware testing and validation

---

# Project Preview

## PCB Layout`
board.png
## 3D PCB View

images/pcb_3d.png

## Final Hardware

final_board.jpg

# What I Learned

This project allowed me to strengthen both my theoretical understanding and practical skills in electronic design.

During its development, I learned:

- Designing analog and digital electronic circuits
- PWM generation using the NE555 timer
- Operational amplifier and comparator applications
- Logic design using CMOS NAND gates
- Power supply design and voltage regulation
- PCB schematic capture and routing
- Signal simulation and verification with Proteus
- PCB fabrication workflow
- Component soldering techniques
- Hardware debugging and testing
- Technical documentation using LaTeX

---

# Repository Structure

```text
.
├── Documentation/
│   └── Project_Report.pdf
├── Proteus/
│   ├── Simulation
│   ├── PCB
│   └── Schematic
├── Images/
├── PCB/
├── README.md
└── LICENSE
```

# Future Improvements

- Manufacture the complete double-layer PCB.
- Add microcontroller-based digital control.

# Author

**Sara Bannour**

Electrical Engineering Student  
National Engineering School of Monastir (ENIM)

---

# License

This project is intended for educational and research purposes.
