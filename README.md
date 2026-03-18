# 🔥 Fire Fighting Robot

## 🚀 Overview

This project is an autonomous fire fighting robot built using Arduino.  
It is capable of detecting fire, aligning itself towards the source, and activating a water pump to extinguish it.  
The system also includes obstacle avoidance and manual control via Bluetooth.

---

## ⚙️ Features

- 🔹 Bluetooth-controlled movement (Forward, Backward, Left, Right)
- 🔹 Obstacle detection using ultrasonic sensor
- 🔹 Automatic fire detection using flame sensors
- 🔹 Directional alignment towards fire source
- 🔹 Water pump activation using relay module
- 🔹 Priority-based control system (Fire > Obstacle > Manual)

---

## 🧠 System Logic

The robot follows a priority-based control system:

Fire Detection → Highest Priority
Obstacle Avoidance → Medium Priority
Manual Control → Lowest Priority

When fire is detected:
1. Robot stops manual operation  
2. Aligns toward the fire source  
3. Activates water pump  
4. Repeats until fire is no longer detected  

---

## 🔧 Components Used

- Arduino UNO  
- L298N Motor Driver  
- Flame Sensors  
- Ultrasonic Sensor  
- Relay Module  
- Water Pump  
- HC-05 Bluetooth Module  
- 18650 Lithium Batteries  

---

## ⚠️ Challenges Faced

- Power instability due to battery voltage drop  
- Bluetooth communication issues  
- Relay and water pump debugging  
- Sensor calibration and alignment  

---

## 🧪 Learnings

- Embedded systems debugging  
- Power management in hardware systems  
- Real-time control logic design  
- Sensor integration and calibration  

---

## 🎯 Future Improvements

- Mobile app integration  
- Live data monitoring dashboard  
- Camera-based fire detection  
- Improved targeting using feedback control  

---
