<!-- Logo -->
<p align="center">
  <img src="Images/DigitalParking_Logo.png" alt="Digital Parking Logo" width="500"/>
</p>

<!-- Title Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%9A%97%20Digital%20Parking%20System&fontSize=36&width=1200&height=150&color=0:36BCF7,100:0f2027"/>
</p>

<h3 align="center">
  <b style="color:purple;">🚗 Arduino-Based Smart Parking Solution</b>
</h3>

<h3 align="center">
  <b>📊 Real-Time Parking Slot Detection Using Ultrasonic Sensors</b>
</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Arduino-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Language-C%2B%2B-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Sensors-Ultrasonic-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Actuator-Servo%20Motor-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Functional-success?style=for-the-badge">
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Overview Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%93%8C%20Overview&fontSize=32&width=1200&height=130&color=0:9D50BB,100:6E48AA" width="100%">

**Digital Parking System Using Arduino** is an interactive project demonstrating **real-time parking slot detection** using **ultrasonic sensors and servo motors**.  

It detects whether a parking slot is occupied and displays the status via LEDs or an LCD screen, providing a **hands-on learning platform for sensor integration, actuator control, and embedded system programming**.

**Key Highlights:**
- Monitors multiple parking slots in real-time  
- Detects slot occupancy using ultrasonic sensors  
- Controls servo motors for automated actions (optional barrier control)  
- Displays parking availability on LEDs or LCD  
- Simple, modular Arduino-based hardware design  
- Ideal for learning, prototyping, or small-scale parking automation  

**Keywords:** Arduino parking system, ultrasonic sensor, servo motor, smart parking, real-time detection, embedded systems, automation

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Objectives -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%8E%AF%20Objectives&fontSize=32&width=1200&height=130&color=0:FF416C,100:FF4B2B" width="100%">

- 🎯 Design and implement a basic digital parking system using Arduino  
- 🔄 Understand the operation of ultrasonic sensors for distance measurement  
- 📊 Create a system that detects available parking slots and displays the status  
- 🤖 Demonstrate actuator control using servo motors for automation  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Components & Cost -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%92%B0%20Components%20and%20Cost&fontSize=32&width=1200&height=130&color=0:00F260,100:0575E6" width="100%">

<div align="center">

| Component | Quantity | Approx. Cost (BDT) |
|-----------|---------|------------------|
| Arduino UNO | 1 | 760 |
| Ultrasonic Sensor (HC-SR04) | 2-4 | 200 |
| Servo Motor | 1 | 130 |
| LCD Display / LEDs | 1 | 150 |
| Jumper Wires | 10 | 25 |
| Breadboard | 1 | 50 |
| Power Supply / USB | 1 | 100 |
| **Total Cost** |  | **1,415+** |

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">


<!-- Features -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%E2%9C%A8%20Key%20Features&fontSize=32&width=1200&height=130&color=0:FC5C7D,100:FF416C" width="100%">

- 🚗 Real-time parking slot monitoring  
- 🔊 Distance detection using ultrasonic sensors  
- ⚙ Servo motor automation for barriers (optional)  
- 💡 LED/LCD display for slot availability  
- 🛠 Easy Arduino integration for prototyping  
- 📚 Educational and hobby-friendly project  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- System Implementation -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=System%20Implementation&fontSize=32&width=1200&height=130&color=0:6A82FB,100:FC5C7D" width="100%">

### 📷 Hardware Setup & Screens
The system integrates Arduino UNO, ultrasonic sensors, servo motors, and LEDs/LCD for real-time parking detection.

**Circuit Components:**
- Arduino UNO  
- Ultrasonic Sensors (HC-SR04)  
- Servo Motor (90°-180°)  
- LCD Display / LEDs  
- Jumper Wires & Breadboard  
- Power Supply  

**Circuit Diagram:**
<div align="center">
<img src="circuit_diagram.png" width="500" />
<p><b>Digital Parking System Circuit</b></p>
</div>

**Operation:**
- Ultrasonic sensors continuously measure the distance to detect cars in parking slots  
- LEDs or LCD indicate whether slots are available or occupied  
- Servo motor can operate a barrier or indicator based on slot occupancy  

<div align="center">
  <img src="parking_demo.jpg" width="300" />
  <p><b>Digital Parking System in Action</b></p>
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Project Structure -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%93%82%20Project%20Structure&fontSize=32&width=1200&height=130&color=0:36BCF7,100:0f2027" width="100%">

```bash
DigitalParkingSystem/
│── Arduino_Code/
│ ├── ParkingSystem.ino
│── Circuit_Diagram/
│ ├── circuit_diagram.png
│── Images/
│ ├── parking_demo.png
│ ├── parking_demo2.png
│── README.md
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"> 


<!-- Setup & Usage --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%9A%80%20Setup%20&%20Usage&fontSize=32&width=1200&height=130&color=0:00F260,100:0575E6" width="100%">

Steps to Run:
```bash
1. Connect ultrasonic sensors to Arduino UNO as per the circuit diagram
2. Mount servo motor (if using barriers)
3. Connect LEDs or LCD for display
4. Upload ParkingSystem.ino to Arduino using Arduino IDE
5. Power Arduino via USB or external supply
6. Test slot detection by placing objects or cars in slots
7. Observe LED/LCD status and servo motor response
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"> 

<!-- Future Work --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%94%AE%20Future%20Enhancements&fontSize=32&width=1200&height=130&color=0:FF416C,100:FF4B2B" width="100%">

📡 Integrate multiple sensors for large parking lots  
🤖 Automated mobile app notification for available slots  
💬 Cloud-based monitoring and analytics   
🔋 Energy-efficient design with battery monitoring  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"> 

<!-- Conclusion --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=%E2%9C%85%20Conclusion&fontSize=32&width=1200&height=130&color=0:6A82FB,100:FC5C7D" width="100%">

Digital Parking System Using Arduino is a hands-on, deployable project demonstrating real-time parking detection and automation.

It serves as an educational platform, hobby project, or small-scale prototype for smart parking systems, while being modular and expandable for future enhancements.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"> 

<!-- Author --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%91%A8%E2%80%8D%F0%9F%92%BB%20Author&fontSize=32&width=1200&height=130&color=0:00F260,100:0575E6" width="100%">

### A. K. M. Masudur Rahman (Gaurab)

🎓 Department of Computer Science and Engineering (CSE)   
🏫 Bangladesh Army University of Science and Technology (BAUST), Saidpur   
📧 Email: akmmasudurrahmangaurab@gmail.com   

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"> 

<!-- Support --> 
<img src="https://capsule-render.vercel.app/api?type=waving&text=%E2%AD%90%20Support&fontSize=32&width=1200&height=130&color=0:FF416C,100:FF4B2B" width="100%"> 

If you like this project, consider giving it a ⭐ on GitHub!
