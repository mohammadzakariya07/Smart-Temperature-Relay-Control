# 🔥 Smart Temperature Relay Control System with EEPROM Persistence
(Boiler Element Temperature Controller)

## 📌 Overview
The Smart Temperature Relay Control System is an embedded temperature-based automation solution designed for boilers, heaters, and industrial thermal systems. It uses a thermocouple sensor for accurate temperature measurement and controls five relays using hysteresis logic to ensure stable operation.

The system integrates EEPROM memory to retain relay states even after power failure or reset, making it reliable for safety-critical and industrial applications.

---

## 🎯 Key Features
- Hysteresis-based relay control
- EEPROM state persistence
- Configurable temperature thresholds
- Five independent relay outputs
- Real-time serial monitoring
- Fault handling for invalid sensor readings
- Industrial-grade PCB design

---

## 🌡 Relay Temperature Configuration

| Relay | ON (°C) | OFF (°C) |
|------|--------|---------|
| Relay 1 | ≤ 40 | ≥ 45 |
| Relay 2 | ≤ 45 | ≥ 50 |
| Relay 3 | ≤ 50 | ≥ 55 |
| Relay 4 | ≤ 55 | ≥ 60 |
| Relay 5 | ≤ 60 | ≥ 65 |

Thresholds can be modified according to application requirements.

---

## 💾 EEPROM Functionality
- Restores relay states after power loss
- Updates EEPROM only when relay state changes
- Prevents unsafe startup behavior

---

## 🧩 System Components
- Thermocouple sensor (SPI based)
- Microcontroller (Arduino compatible)
- 5-channel relay module
- Serial interface for monitoring
- Custom PCB (195mm × 105mm)

---

## 🚀 Applications
- Boiler temperature control
- Industrial heater automation
- HVAC systems
- Thermal safety shutdown systems
- Energy management solutions

---

## 👤 Author
**Mohammad Zakariya**  
Embedded Systems & IoT Enthusiast
----

