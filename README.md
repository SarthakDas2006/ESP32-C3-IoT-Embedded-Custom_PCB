# ESP32-C3-IoT-Embedded-Custom_PCB
4-layer ESP32-C3 based custom embedded IoT PCB featuring onboard temperature & humidity, light, and audio sensing, USB Type-C, Li-Po charging, and external flash memory. Designed for smart embedded systems, wireless IoT applications, portable sensing, automation, and edge device prototyping.
A professionally designed 4-layer ESP32-based IoT development board created using KiCad.
This project was developed to explore real-world PCB engineering concepts including multilayer routing, power management, USB-C integration, sensor interfacing, and signal integrity practices.



# 📸 Project Preview

## 3D PCB Render
<img width="632" height="433" alt="image" src="https://github.com/user-attachments/assets/e5e45aa2-12ac-408f-b5a5-f8a30977bfbf" />



# 🚀 Features

- ESP32-C3-WROOM module with onboard antenna
- 4-layer PCB stackup
- USB Type-C interface
- Li-Ion battery charging circuit
- Onboard voltage regulation
- SD card interface
- External SPI flash memory
- Temperature and humidity sensor interface
- Photo sensor interface
- Microphone and amplifier circuitry
- Reset and Boot buttons
- Ground plane optimization
- Decoupling and filtering capacitors
- Test points for debugging



# 🧠 PCB Stackup

| Layer | Function |
|---|---|
| Top Layer | Signal Routing |
| Inner Layer 1 | Ground Plane |
| Inner Layer 2 | Power Plane |
| Bottom Layer | Signal Routing |

The multilayer architecture was designed to improve:
- signal integrity
- grounding
- EMI performance
- power distribution



# 🛠️ Tools Used

- KiCad
- NextPCB DFM tool (HQDFM)
- SnapEDA
- ESP32-C3 Ecosystem
- Multiple datasheets


# 🔌 Hardware Blocks

## ESP32-C3 Module
Main microcontroller responsible for:
- WiFi/Bluetooth communication
- sensor interfacing
- data processing
- IoT applications

## USB Type-C Interface
Used for:
- power input
- USB communication
- firmware flashing

Includes:
- filtering capacitors
- protection circuitry
- proper VBUS routing

## Li-Ion Charging Circuit
Portable power management section featuring:
- battery charging
- regulated power delivery
- charging indication circuitry

## SD Card Interface
SPI-based SD card module used for:
- data logging
- external storage
- sensor data recording

## Sensor Interfaces
The PCB includes provisions for:
- temperature and humidity sensing
- ambient light sensing
- audio input through microphone amplifier circuitry


# 📂 Repository Structure

```text
ESP32-C3-IoT-Embedded-Custom-PCB/
│
├── BOM files/
├── Datasheets/
├── Drill files/
├── Gerber files/
├── Images/
├── custom 3d model libraries/
├── custom footprint libraries/
├── custom symbol libraries/
│
├── ESP32_IoT_4-layer_PCB.kicad_pcb
├── ESP32_IoT_4-layer_PCB.kicad_pro
├── ESP32_IoT_4-layer_PCB.kicad_sch
│
└── README.md
```


# 🎯 Project Objectives

This project was built to gain practical experience in:

- multilayer PCB design
- signal routing
- power integrity
- USB-C hardware implementation
- grounding techniques
- schematic hierarchy
- PCB manufacturing workflow



# 🧪 Key Design Considerations

- Ground plane continuity
- Proper decoupling capacitor placement
- Power filtering and stabilization
- Analog and digital section separation
- Pull-up and pull-down resistor implementation
- Modular schematic organization



# 📦 Manufacturing Ready

The project includes:
- PCB layout
- schematic
- Gerber files
- drill files
- BOM support

Compatible with manufacturers such as:
- JLCPCB
- PCBWay
- NextPCB



# 🔮 Future Improvements

- OTA firmware updates
- CAN bus support
- additional onboard sensors
- low-power optimization
- enclosure design
- impedance-controlled routing



# 📚 Learning Outcomes

Through this project, I developed understanding of:

- multilayer PCB stackups
- copper pours and ground planes
- signal routing
- ESP32 hardware integration
- USB-C implementation
- PCB manufacturing workflow
- hardware debugging concepts



# 👨‍💻 Author

**Sarthak Das**  
Electrical and Electronics Engineering Student at VIT Chennai



# ⭐ Support

If you like this project:
- Star the repository
- Fork the project
- Share feedback and suggestions


