# IoT-Based Smart Cabinet for Preventive Healthcare

This repository contains the conceptualization, design, and functional prototype of an **IoT-Based Smart Cabinet** designed to bridge the gap between daily nutrition and preventive healthcare. The system automates food inventory management, monitors dietary habits, and provides real-time health insights through AI and IoT integration.

---

## 🚀 Project Overview

Imbalanced diets and food waste are significant issues stemming from a lack of accurate dietary tracking. This project addresses these challenges by creating a data-driven solution that integrates with healthcare systems to aid in the early diagnosis of nutritional deficiencies.

### Key Objectives

* **Automated Inventory Management**: Utilizes AI image recognition and weight sensors for real-time tracking.

* **Healthy Habit Promotion**: analyzes eating patterns and offers personalized recipe suggestions.

* **Healthcare Integration**: Shares nutrient consumption reports with medical professionals for personalized treatment.

* **Smart User Experience**: Features remote mobile access and touch-activated **electrochromic glass** for cabinet transparency.


## 🛠️ System Design & Implementation

### Hardware Architecture

The system is built on an **ESP32-based IoT core** integrated with several specialized components:

* **ESP32-CAM**: Captures internal images for AI identification.
* **HX711 Load Cell**: Measures food weight to track consumption levels.
* **Electrochromic Glass**: Provides an interactive, touch-activated viewing panel.
* **Relay Module**: Controls LED lighting to optimize image recognition quality.
* **Smartwatch Integration**: Includes pulse and temperature sensors for monitoring user health parameters.


### Software & Cloud Integration

* **AI Processing**: Employs the **YOLOv9 model** for precise food item recognition.
* **Cloud Infrastructure**: Uses a **Flask (Python) Web Server** to handle communication between ESP32 devices and the cloud.
* **Data Management**: All system data is logged into **Firebase** for remote analysis and mobile app access.
* **Frontend**: A web dashboard developed with HTML, CSS, JavaScript, and Python displays health analytics and inventory updates.


## 🧩 Challenges & Engineering Solutions

| Challenge | Solution Implemented |
| --- | --- |
| **ESP32-CAM Image Quality** | Optimized lighting with LED strips and black foam to minimize overexposure. |
| **High Voltage Requirements** | Used a relay-controlled power supply to regulate the 20V–34V required for electrochromic glass. |
| **Sensor Data Noise** | Applied a **Kalman filter** to pulse sensor readings to enhance accuracy. |
| **Communication Stability** | Standardized socket messaging protocols for reliable ESP32-to-server connections. |



## 📈 Outcomes & Impact

* **Waste Reduction**: Real-time tracking ensures better nutrition and significantly reduces food waste.
* **Proactive Healthcare**: Direct integration with healthcare providers allows for faster medical interventions.
* **Scalability**: The system is designed for potential integration into large-scale smart home automation networks.


## 🔮 Future Enhancements

* **Multi-User Support**: Expanding access control for larger households.
* **Voice Assistance**: Integrating Google Assistant or Alexa for hands-free cabinet management.
* **Advanced AI**: Using machine learning to suggest meal plans tailored to specific health conditions.
* **Blockchain Integration**: Enhancing security and privacy for shared medical and health records.
