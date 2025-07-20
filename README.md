# Micro-Radar-System
An Arduino-based Micro Radar System that scans for objects using an ultrasonic sensor mounted on a servo motor. The project visualizes object detection in real time like a radar screen using **Processing IDE**.

---

## 🎥 Demo Video

[![Watch on YouTube](https://img.youtube.com/vi/F3C1LtXdQ7Q/0.jpg)](https://youtube.com/watch?v=F3C1LtXdQ7Q)

---

## 🧠 Key Features

- Real-time radar scanning from 0° to 180°
- Object distance detection using HC-SR04 ultrasonic sensor
- Visual radar output on PC using Processing IDE
- Basic embedded system using Arduino Uno

---

## ⚙️ Hardware Used

- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor
- Breadboard & Jumper wires
- USB Cable
- (Optional) LCD Display, Buzzer, LEDs

---

## 💻 Project Files

| File Name | Description |
|-----------|-------------|
| `radar.ino` | Arduino source code for radar system |
| `radar_visualization.pde` | Visualization code using Processing |
| `Micro_Radar_System_Project_Report.docx` | Full project report |
| `circuit_diagram.jpg` | Circuit diagram (add if available) |

---

## 🖥️ How It Works

1. Arduino rotates the servo motor from 15° to 165°
2. Ultrasonic sensor emits a pulse and receives echo
3. Distance is calculated using:  
   `Distance = (Time × Speed of Sound) / 2`
4. Data is sent via Serial to PC
5. Processing IDE visualizes the radar sweep

---

## 🔭 Future Scope

- Add Bluetooth/Wi-Fi for wireless data
- Connect buzzer/LEDs for real-time alerts
- 3D scanning with vertical rotation
- Integration with robots for obstacle avoidance
- Display radar output on LCD or mobile app

---

## 👨‍🎓 Author

- Rishabh Rawat (2315195504)  

Under guidance of **Mr. Naresh Pathak**,  
Surajmal College of Science and Technology

---

## 📚 References

- Arduino Servo Library  
- Processing.org – Radar Visualization  
- [Instructables Radar Project](https://www.instructables.com/Arduino-Radar-System/)
