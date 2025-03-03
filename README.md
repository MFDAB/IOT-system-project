# IoT-Based Smart Cabinet for Preventive Healthcare

# Introduction
As part of our IoT System Project coursework, my teammates and I embarked on a journey to conceptualize, design, and develop an innovative IoT-based Smart Cabinet. The objective was to bridge the gap between everyday nutrition and preventive healthcare through IoT technology.

Our project aimed to automate food inventory management, monitor dietary habits, and provide real-time health insights. We envisioned a smart cabinet that could track food consumption, recommend healthier choices, and integrate with healthcare providers to aid in early diagnosis of nutritional deficiencies​
.

# Problem Statement & Motivation
Despite increasing awareness of the importance of proper nutrition, imbalanced diets and food waste remain significant issues. Many individuals struggle to keep track of their dietary habits, leading to malnutrition and preventable health issues.

Traditional diet tracking and inventory management methods are time-consuming, inaccurate, and lack integration with healthcare systems. Our project addressed these issues by leveraging IoT and AI technologies to create an automated, data-driven solution.

# Project Objectives
The primary goal of our project was to enhance preventive healthcare through real-time dietary monitoring. Our specific objectives included:

Automate Inventory Management:

Use AI-powered image recognition and weight sensors to identify and track food items in the cabinet.
Provide users with a live feed and dashboard for real-time updates​
.
Promote Healthy Eating Habits:

Offer personalized recipe suggestions based on available food.
Track and analyze eating patterns to encourage healthier choices.
Facilitate Healthcare Integration:

Share nutrient consumption reports with doctors for better diagnosis and personalized treatment.
Allow users to maintain an accurate health record with insights into their dietary intake​
.
Enhance User Experience with Smart Features:

Enable remote access to the cabinet using a mobile app.
Use electrochromic glass to provide a touch-activated transparent view of the cabinet’s contents​
.
# System Design & Implementation
To bring our concept to reality, we developed a functional prototype consisting of hardware components, software architecture, and cloud-based data management.

## Hardware Components
The Smart Cabinet was built using an ESP32-based IoT system integrated with multiple sensors and actuators:

ESP32-CAM: Captured images of stored food for AI-based identification​

Load Cell (HX711): Measured the weight of food items to track consumption​

Electrochromic Glass Panel: Enabled touch-activated transparency for an interactive user experience.

Relay Module: Controlled the activation of LED lighting for improved image recognition.

Pulse Sensor & Temperature Sensor (Smartwatch Integration): Monitored real-time health parameters of users​

## Software & Cloud Integration
The software stack was designed to ensure seamless communication between hardware and the cloud:

### Web Dashboard & Mobile App:

#### Developed using HTML, CSS, JavaScript, and Python (Flask).
#### Displayed real-time inventory updates, food expiration alerts, and health analytics​

### AI-Based Image Processing:

#### Used YOLOv9 model to recognize food items inside the cabinet​
.
#### Implemented custom-trained AI models for better accuracy.
### Cloud-Based Data Storage & API Integration:

#### Flask Web Server handled communication between ESP32 devices and the cloud.
#### Data logged into Firebase, allowing remote access and analysis​
.
### Health Monitoring & Doctor Integration:

#### Health data was automatically shared with doctors for improved diagnosis.
#### Implemented a smartwatch prototype to track heart rate, temperature, and blood glucose levels​.

# Challenges & Solutions
Throughout the project, we faced several technical and operational challenges:

Challenge	Solution Implemented
ESP32-CAM image quality issues	Optimized lighting conditions using LED strips and black foam to reduce overexposure​
.
Electrochromic glass required high voltage	Used a relay-controlled power supply to regulate voltage (20V-34V)​
.
Data noise in pulse sensor readings	Implemented a Kalman filter to reduce noise and improve accuracy​
.
Inconsistent server communication	Standardized socket messaging protocols to ensure stable connections between ESP32 devices and the server​
.
# Outcomes & Impact
The Smart Cabinet successfully demonstrated the potential of IoT and AI in preventive healthcare. Our key achievements include:

Accurate real-time food tracking, reducing waste and ensuring better nutrition.
Seamless integration with healthcare providers, enabling proactive medical interventions.
User-friendly web dashboard for monitoring health data and inventory.
Scalability potential for integration into large-scale smart home automation systems​
.
# Future Enhancements
Although our prototype was functional, future developments could further improve its real-world applicability:

Multi-User Support: Expand access control for households with multiple members.
Voice-Activated Assistance: Integrate Google Assistant or Alexa for hands-free operation.
Advanced AI Prediction: Use machine learning models to suggest meal plans based on health conditions.
Blockchain-Based Health Records: Enhance data security and privacy when sharing medical information.
8. Conclusion
This IoT System Project was an immensely rewarding experience, allowing us to apply theoretical knowledge into a real-world solution. From ideation to prototyping, our team successfully designed, built, and tested an IoT-enabled Smart Cabinet that could redefine preventive healthcare and nutrition tracking.

By collaborating as a team, overcoming challenges, and integrating feedback from industrial partners, we transformed an idea into a working prototype. This project showcased the power of IoT, AI, and cloud computing in revolutionizing healthcare and smart living solutions.
