# 🤖 Robot Movement and Vision System 👁️

---

## 🚀 Overview

This project contains **two independent systems** running in parallel:

- 🔧 **Arduino Robot Control:** Controls the robot’s movement.
- 👀 **Vision System:** Processes visual data separately, with **no communication** to the Arduino.

Both systems operate **independently** without exchanging data.

---

## 🛠️ Components

### 1️⃣ Arduino Robot Control

- **Platform:** Arduino microcontroller  
- **Function:** Controls motors & movement with embedded code  
- **Communication:** ❌ No connection with Vision System  
- **Code Location:** `/arduino/`  

### 2️⃣ Vision System

- **Platform:** PC / external processor  
- **Function:** Runs vision algorithms on camera/video input  
- **Communication:** ❌ No interaction with Arduino  
- **Code Location:** `/vision/`  

---

## ▶️ How to Run

### Arduino Robot Control

```bash
1. Open Arduino IDE  
2. Load `/arduino/robot_control.ino`  
3. Upload to your Arduino board  
4. Robot starts moving based on programmed logic
```

---

## Vision System

1. Go to `/vision/` folder  
2. Run vision script (e.g. `recognition.py`)  
3. Vision system processes video independently

---

## 📂 Project Structure
/
├── arduino/
│ └── robot_control.ino
├── vision/
│ └── vision_processing.py
└── README.md

---

### Software Requirements
- Arduino IDE (for robot control)
- Python 3.x
- Computer vision libraries (OpenCV, etc.)
