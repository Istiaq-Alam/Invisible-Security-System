# Invisible Security System 🔒

A DIY laser-based security system that detects unauthorized entry using a laser beam and LDR (Light Dependent Resistor), integrated with IoT via NodeMCU ESP8266 for remote control.

---

## 📘 Project Overview

- **Course:** Microprocessor & Assembly Language Programming Lab (CSE 3106)
- **Institution:** Notre Dame University Bangladesh
- **Batch:** CSE 19+20
- **Project Timeline:** August 26, 2024 – November 9, 2024

### 👥 Team Members

- [Istiak Alam](https://github.com/Istiaq-Alam) (ID: 0692230005101005)
- [Sazzad Jelani](https://github.com/Saz-Jelani) (ID: 0692220005101003)
- [Nafisa Tabassum](https://github.com/NafisaTabassumNeha) (ID: 0692220005101008)
- Sadia Islam Mim (ID: 0692220005101010)

---

## 📌 Objective

To build a low-cost, efficient, and remotely controlled laser-based intrusion detection system using Arduino Uno, NodeMCU ESP8266, and basic electronics components.

---

## 🎯 Features

- **Laser + LDR Detection** for triggering intrusion alerts.
- **Passive Buzzer** for sound alarm.
- **LCD Display (16x2)** to display real-time status messages.
- **NodeMCU ESP8266 Web Interface** for remote laser ON/OFF control.
- **Portable Power Supply** using a power bank.

---

## 🔧 Hardware Components

| Component              | Quantity | Cost (BDT) |
|------------------------|----------|------------|
| Arduino UNO R3         | 1        | 1050/-     |
| NodeMCU ESP8266        | 1        | 420/-      |
| Laser Module           | 2        | 200/-      |
| Passive Buzzer         | 1        | 15/-       |
| LCD Display (16x2)     | 1        | 230/-      |
| Breadboard (830 point) | 1        | 150/-      |
| Breadboard (400 point) | 1        | 85/-       |
| Mirrors                | 6        | 50/-       |
| LDR                    | 2        | 60/-       |
| Resistors              | 2        | 10/-       |
| Jumper Wires           | 10       | 100/-      |
| Misc Wires + Power     | As req.  | 150/-      |

---

## 🧠 Software and Libraries

### Tools Used:
- **Arduino IDE** for microcontroller programming.
- **Tinkercad** for 3D simulation and circuit design.

### Programming Languages:
- C / C++

### Arduino Libraries:
- `LiquidCrystal_I2C`
- `SoftwareSerial`

### NodeMCU Libraries:
- `ESP8266WiFi`
- `ESP8266WebServer`

---

## 🧬 System Architecture

1. **Arduino Uno** controls the laser and buzzer.
2. **LDR** detects laser interruption (intrusion).
3. **NodeMCU** acts as a web server to control the laser.
4. **LCD** shows status messages.
5. **Mirrors** reflect the laser beam.
6. **Power Bank** supplies portable power.

---

## 💻 Code Highlights

### Arduino Sketch (Main Logic)
- Reads LDR values.
- Activates buzzer on laser interruption.
- Displays "Access Denied" or "Authorized Only" on LCD.
- Responds to NodeMCU serial commands (`ON`, `OFF`).

### NodeMCU Sketch
- Connects to Wi-Fi.
- Hosts a web server with Laser ON/OFF buttons.
- Sends serial commands to Arduino.

---

## 🖼️ Project Output (Visual Summary)

- Laser beam visible with smoke.
- LCD showing real-time status.
- Circuit shows back/front view.
- Working model simulated in Tinkercad.

---

## ⚠️ Challenges Faced

- Laser beam alignment using mirrors.
- Sensor calibration to avoid false positives.
- Wi-Fi and serial communication instability.
- Power fluctuations during operation.

---

## 🚀 Future Enhancements

- Facial recognition and AI integration.
- Mobile app with camera stream and remote control.
- PIR sensor for better intrusion accuracy.
- Solar backup and tamper detection.
- Push notifications and cloud logging.
- Integration with smart home ecosystems.

---

## 📅 Timeline

- **Start Date:** 26th August 2024
- **End Date:** 9th November 2024

---

## 📚 References

- [Optex Pinnacle](https://www.optexpinnacle.com) – For LiDAR-based inspiration
- Arduino Tutorials & Sketches
- Tinkercad Circuit Simulation

---

## 📸 Screenshots (Optional in README)

> Image will include later:
> ```
> ![Front View](images/front_view.jpg)
> ![Circuit Diagram](images/circuit.jpg)
> ```

---

## 🏁 Conclusion

The Invisible Security System successfully showcases a responsive, real-time laser-based security solution with IoT integration. With room for scalability and future enhancements, it's a solid foundation for modern DIY security systems.

