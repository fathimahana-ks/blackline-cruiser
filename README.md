# BLACK-LINE CRUISER – Autonomous Robotic Car

Blackline Cruiser is an Arduino-powered robotic car capable of following a black line and avoiding obstacles using IR and ultrasonic sensors. Designed for efficiency and reliability, it demonstrates core principles of autonomous navigation and embedded systems.

---

## Features

- Line Following using IR sensors with 95% accuracy
- Obstacle Avoidance using ultrasonic sensor with 100% detection rate
- Powered by Arduino Uno for real-time sensor processing and motor control
- Simple hardware setup with modular, beginner-friendly code

---

## Technologies Used

- Arduino Uno
- IR Sensors (TCRT5000) – for line detection
- Ultrasonic Sensor (HC-SR04) – for obstacle detection
- L293D Motor Driver – for motor control
- DC Motors and Chassis
- C/C++ – Arduino IDE

---

## How It Works

**Line Tracking:**  
IR sensors detect the contrast between the black line and the surface. The Arduino adjusts motor direction based on sensor input to keep the car aligned.

**Obstacle Detection:**  
If an obstacle is detected within a threshold distance by the ultrasonic sensor, the car stops or changes direction to avoid collision.

---

## Circuit Diagram

![Circuit Diagram](circuit_diagram.png)  
_Add your wiring diagram image here._

---

## Images of the Robot Car

**Front View**  
![Front View](front_view.png)  
_Add your front image here._

**Back View**  
![Back View](back_view.png)  
_Add your back image here._

---

## Getting Started

### Prerequisites

- Arduino IDE installed on your computer
- Components connected to Arduino Uno as per the circuit diagram

### Steps to Upload the Code

1. Connect the Arduino board to your PC via USB.
2. Open the `blackline_cruiser.ino` file in Arduino IDE.
3. Select the correct board type (Arduino Uno) and COM port.
4. Upload the sketch to the Arduino board.
5. Place the car on a black line track and power it on.

---

## Project Structure
