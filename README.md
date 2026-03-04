# 🚗 Smart WiFi Surveillance System

An IoT-based Smart Vehicle Surveillance and Remote Control System built using ESP32-CAM.  
This project enables real-time video streaming, remote vehicle movement control, and smart monitoring through WiFi connectivity.

---

## 📌 Project Overview

The Smart WiFi Surveillance System integrates IoT technology with vehicle automation to provide:

- 📡 Real-time video streaming
- 🎮 Remote vehicle movement control
- 💡 Speed and light adjustment
- 🌐 Web-based control interface
- 📱 Blynk app integration

The system enhances vehicle security and allows users to monitor and control the vehicle from anywhere within the WiFi network.

---

## 🛠 Hardware Components Used

- ESP32-CAM Module (WiFi + Camera)
- L298N Motor Driver
- 4 DC Motors
- Battery Pack
- Chassis
- Connecting Wires

---

## 💻 Software Requirements

- Arduino IDE
- Embedded C
- ESP32 Board Package
- CH340 Drivers
- Blynk Library

---

## 🚗 Hardware Setup

![Hardware Setup](images/Smart_WiFi_Surveillance_Hardware_Setup.png)

![Hardware Setup 2](images/Smart_WiFi_Surveillance_Hardware_Setup_2.jpeg)

---

## 💻 Web Interface

![Web Interface](images/Smart_WiFi_Surveillance_Web_Interface.jpeg)

The web interface allows:
- Forward / Backward movement
- Left / Right steering
- Speed control slider
- Light intensity control
- Live video streaming

---

## ⚙️ Working Principle

1. ESP32-CAM connects to WiFi network.
2. Camera captures live video feed.
3. Web server streams video to browser.
4. User sends control commands via web interface.
5. ESP32 processes commands and controls motors through L298N driver.
6. Blynk app updates speed and light parameters.

---

## 📂 Project Structure
Smart-Wifi-Surveillance-System/

│── Docs/

│ Final documentation.pdf

│── Images/

│ Smart_WiFi_Surveillance_Hardware_Setup_2.jpeg

│ Smart_WiFi_Surveillance_Web_Interface.jpeg

│── app_code.ino

│── README.md

---

## 📘 Documentation

Full documentation available in:

`Docs/Final documentation.pdf`

---

## 👩‍💻 Developed By

- D. Varsha Reddy  

---

## 📜 License

This project is developed for academic purposes.
