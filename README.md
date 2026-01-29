## 🥗 Project Overview: IoT-Based Smart Cabinet

The **Smart Cabinet** is an innovative IoT system designed to bridge the gap between daily nutrition and preventive healthcare. By automating food inventory management and monitoring dietary habits, the system provides real-time health insights and facilitates early diagnosis of nutritional deficiencies.

> **The Vision:** To transform a standard kitchen cabinet into a data-driven health assistant that reduces food waste and integrates seamlessly with professional healthcare providers.

---

## 🛠 System Architecture

### 1. Hardware Integration (ESP32 Ecosystem)

The prototype utilizes an **ESP32-based** core to manage a suite of sensors and actuators:

* **Computer Vision:** An **ESP32-CAM** captures images for AI-powered food identification.
* **Weight Sensing:** A **Load Cell (HX711)** tracks food consumption by measuring weight changes.
* **Interactive UI:** An **Electrochromic Glass Panel** provides a touch-activated transparent view of the contents.
* **Health Monitoring:** Integrated sensors track heart rate, temperature, and blood glucose via a smartwatch prototype.

### 2. Software & AI Stack

* **Object Detection:** Implements the **YOLOv9** model to recognize and categorize food items.
* **Backend:** A **Flask (Python)** web server handles communication between hardware and the cloud.
* **Data Management:** **Firebase** is used for real-time data logging and remote access.
* **Dashboard:** A custom web/mobile interface built with **HTML, CSS, and JavaScript** displays alerts and analytics.

---

## 🚧 Challenges & Engineering Solutions

| Technical Challenge | Solution Implemented |
| --- | --- |
| **Image Quality:** Overexposure in ESP32-CAM | Optimized lighting with LED strips and black foam insulation. |
| **High Voltage:** Electrochromic glass power needs | Utilized a relay-controlled supply to regulate **20V – 34V**. |
| **Data Noise:** Pulse sensor instability | Implemented a **Kalman filter** to smooth readings and improve accuracy. |
| **Connectivity:** Unstable socket communication | Standardized messaging protocols for reliable ESP32-to-server links. |

---

## 📈 Key Outcomes & Future Roadmap

* **Healthcare Integration:** Nutrient consumption reports are shared directly with doctors for proactive intervention.
* **Waste Reduction:** Live inventory feeds and expiration alerts minimize food spoilage.
* **Scalability:** The system is designed for easy integration into broader smart home automation ecosystems.

### **Next Steps for Development:**

* **Voice Control:** Integration with Google Assistant or Alexa.
* **Enhanced Security:** Moving medical records to a **Blockchain-based** system for privacy.
* **Advanced AI:** Predictive meal planning based on specific medical conditions.

---

## 👤 About the Lead Engineer

**R Sanjeev** is an Engineering student from **Nanyang Polytechnic** specializing in **Electronic & Computer Engineering**. With a proven track record in mechatronics and competitive hacking, he focuses on leveraging AI and IoT to solve real-world sustainability and healthcare challenges.

**Would you like me to help you format the "System Design & Implementation" section into a more technical specification list for your repository's Wiki?**
