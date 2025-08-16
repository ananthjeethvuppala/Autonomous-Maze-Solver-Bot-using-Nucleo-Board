# 🤖 Autonomous Maze-Solving Robot using STM32F446RE  

## 📌 Project Overview  
This project focuses on building an **autonomous robot** capable of navigating through a maze environment without human intervention. The robot uses an **STM32F446RE microcontroller** along with **ultrasonic sensors** to detect obstacles and make real-time navigation decisions.  

Such a system has potential applications in **military reconnaissance, disaster response, and explosive ordnance disposal**, where navigating unknown or hazardous terrains is crucial.  

---

## 🎯 Objectives  
- Develop a robot that can **autonomously solve a maze**.  
- Implement **obstacle detection and avoidance** using ultrasonic sensors.  
- Achieve **real-time decision-making** with STM32.  
- Demonstrate applications in **defense and rescue missions**.  

---

## 🛠️ Hardware Requirements  
- STM32F446RE Nucleo Board  
- Ultrasonic Sensors (HC-SR04)  
- Motor Driver (L298N / equivalent)  
- DC Motors with wheels / geared motors  
- Power Supply (Battery Pack)  
- Robot Chassis  

---

## 💻 Software Requirements  
- **STM32CubeIDE / Keil uVision** (for embedded programming)  
- Embedded C (HAL libraries)  
- Serial Monitor (for debugging)  

---

## ⚙️ Working Principle (Algorithm)  
1. The robot starts from the initial position and moves forward.  
2. If an **obstacle is detected ahead**:  
   - The robot turns **right**.  
   - If the **right side is blocked**, it makes a **180° turn** (goes back).  
   - If the **left is also blocked**, the robot **moves backward**.  
3. If the path is clear, the robot continues forward.  
4. The algorithm repeats until the robot reaches the **endpoint**.  

---

## 🚀 Applications  
- **Military Operations** → Building clearance, reconnaissance, hazard navigation.  
- **Disaster Response** → Search and rescue operations.  
- **Explosive Ordnance Disposal (EOD)** → Identifying and mapping explosive devices.  

---

## 👨‍💻 Contributors  
- **Ananth Jeeth Vuppala**  
- **Phani Anirudh**  
- **Sujana**  
- **Mouli**  
- **Pavan Raju**  
- **Mani Chand**  
- **Madar**  
