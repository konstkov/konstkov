## Hi, I'm Konstantin Kovalev  👋


## Featured Embedded Projects 
## About my project contributions

For the group projects below, I developed my assigned functionality independently on a separate feature branch. The implementations shown here are my own work and were fully functional and testable independently. During the final integration, the team lead refactored and consolidated the different team members' implementations into the project's main branch.

The linked branches therefore represent my individual contributions, while the full project repositories show the final integrated versions.

### 🌱 Greenhouse CO₂ Controller

![Greenhouse CO2 Controller](images/greenhouse.jpg)

- Implemented UART-based Modbus RTU communication in C++ for Raspberry Pi Pico, enabling reliable communication with industrial sensors and a Modbus-controlled ventilation system.
- Developed a UART command interpreter (console interface) for system monitoring and configuration, supporting commands for sensor readings, network credentials, and system control.
- Integrated communication with Vaisala CO₂, temperature and humidity sensors, as well as a Produal MIO controller for ventilation fan control.
- Contributed to an embedded FreeRTOS-based greenhouse automation system featuring sensor monitoring, CO₂ regulation, EEPROM-based persistent configuration, and cloud connectivity through ThingSpeak REST API.

🔗 [My implementation (UART / Modbus Communication & Console)](https://github.com/kiannumax/Greenhouse/tree/ControlTask) 
🔗 [Full Project Repository](https://github.com/kiannumax/Greenhouse)


### 🚪 Garage Door Opener 

- Implemented  mechanical door motion system in C++ for Raspberry Pi Pico, including stepper motor control and interrupt-driven rotary encoder implementation for precise position tracking.
- Designed the motion-control logic with consideration for real-time behavior and fault conditions, integrating stepper motor control and encoder feedback into the larger MQTT/EEPROM-based system.

🔗 [My implementation (Motion Control Branch)](https://github.com/kiannumax/Embedded-Garage-Door-/tree/konstantin-motor)
🔗 [Full Project Repository](https://github.com/kiannumax/Embedded-Garage-Door-)

### 💊 Pill Dispenser

- Developed firmware in C for Raspberry Pi Pico to communicate with an external device over LoRaWAN. Implemented a message protocol ensuring robust and synchronized data exchange.
- Created comprehensive state machines for system logic, led hands-on testing, and produced documentation for maintainable and reliable embedded software
- Contributed to a system that integrates stepper motor and persistent state storage (EEPROM), ensuring coordinated operation across components.

🔗 [My implementation (MQTT/LoRaWAN communication)](https://github.com/kiannumax/Embedded-Project/tree/lorawan)
🔗 [Full Project Repository](https://github.com/kiannumax/Embedded-Project)

### ❤️  Heart Rate Monitor

- Developed heart rate measurement and signal processing algorithms in Python, converting raw pulse sensor data into BPM and HRV metrics (RMSSD, SDNN, mean HR).
- Fixed a non-functional implementation by redesigning the signal processing pipeline, including noise filtering, peak detection, and sampling optimization for reliable pulse detection.
- Worked within a larger system featuring OLED display user interface, MQTT-based cloud integration and Kubios analysis for advanced heart health insights.

🔗 [My implementation (Signal Processing / Pulse Detection)](https://gitlab.metropolia.fi/ngoctngu/hr-monitor/-/tree/hr_measurement_old_file_edited?ref_type=heads)
🔗 [Full Project Repository](https://gitlab.metropolia.fi/ngoctngu/hr-monitor/-/tree/main?ref_type=heads)
