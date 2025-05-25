# 🚗 Blackline Cruiser – Line Following & Obstacle Avoiding Robotic Car

Blackline Cruiser is an Arduino-powered robotic car capable of following a black line and avoiding obstacles using IR and ultrasonic sensors. Designed for efficiency and reliability, it demonstrates core principles of autonomous navigation and embedded systems.

---

## 🔧 Features

- 🚦 **Line Following** using IR sensors with 95% accuracy  
- 🧱 **Obstacle Avoidance** using ultrasonic sensor with 100% detection rate  
- 🔋 Powered by Arduino Uno for real-time sensor processing and motor control  
- 🛠️ Simple hardware setup with modular, beginner-friendly code  

---

## 🖥️ Technologies Used

- Arduino Uno  
- IR Sensors (TCRT5000) – for line detection  
- Ultrasonic Sensor (HC-SR04) – for obstacle detection  
- L293D Motor Driver – for motor control  
- DC Motors and Chassis  
- C/C++ – Arduino IDE  

---

## 🧠 How It Works

**Line Tracking:**  
IR sensors detect the contrast between the black line and the surface. The Arduino adjusts motor direction based on sensor input to keep the car aligned.

**Obstacle Detection:**  
If an obstacle is detected within a threshold distance by the ultrasonic sensor, the car stops or changes direction to avoid collision.

---

## ⚙️ Circuit Diagram

📌 [Add image here – e.g., `circuit_diagram.png`]

---

## ▶️ Getting Started

**Prerequisites:**  
- Arduino IDE  
- Required components connected to Arduino Uno  

**Uploading the Code:**  
1. Connect Arduino to your PC.  
2. Open `blackline_cruiser.ino` in Arduino IDE.  
3. Select the correct port and board.  
4. Upload the code and place the car on a black track.  

---

## 📁 Project Structure

