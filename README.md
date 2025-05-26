#AI-Powered Agricultural Robot
Project Overview:
The AI-Powered Agricultural Robot is an innovative, low-cost solution designed to enhance eco-friendly farming. Built using Arduino UNO R3 and ESP32-CAM, it leverages AI to detect plant diseases and spray pesticides precisely when needed. The robot monitors environmental conditions using sensors and provides real-time data visualization through a Firebase-based cloud dashboard.

Features:
AI Disease Detection: Utilizes ESP32-CAM for AI-based plant disease identification.
Environmental Monitoring: Employs DHT22, soil moisture, and ultrasonic sensors for comprehensive monitoring.
Automated Spraying: Servo-controlled pump for targeted pesticide application.
Autonomous Movement: Stops upon plant detection for precise operation.
Cloud Dashboard: Real-time data visualization using Firebase.

Hardware Requirements:
Arduino UNO R3
ESP32-CAM
DHT22 Temperature and Humidity Sensor
Soil Moisture Sensor
Ultrasonic Sensor (HC-SR04)
Servo Motor
Water Pump
DC Motors with Wheels
Robot Chassis
Battery Pack (e.g., 9V or 12V)

Software Requirements:
Arduino IDE
TensorFlow (for AI model training)
Google Colab (for model development)
Firebase SDK (for cloud dashboard)
Web browser (for accessing the dashboard)

Setup Instructions:
Hardware Assembly:
Connect sensors (DHT22, soil moisture, ultrasonic) to Arduino UNO.
Attach ESP32-CAM for AI processing and camera input.
Mount servo motor and water pump for spraying mechanism.
Assemble DC motors and wheels on the robot chassis.
Power the system with a battery pack.


AI Model Training:
Use Google Colab to train a TensorFlow model for plant disease detection.
Export the trained model to the ESP32-CAM.


Software Setup:
Install Arduino IDE and required libraries (e.g., ESP32, Firebase).
Upload the Arduino sketch to the UNO for sensor and motor control.
Configure ESP32-CAM with the AI model and camera settings.


Firebase Integration:
Set up a Firebase Realtime Database project.
Integrate Firebase SDK into the Arduino code for data syncing.
Develop a web/mobile dashboard using Firebase SDK.


Testing and Deployment:
Test the robot on sample plants in a controlled environment.
Deploy in field conditions, monitoring performance and refining as needed.



Webpage Documentation:
The project includes a responsive webpage built with HTML, Tailwind CSS, and JavaScript.
Features a multilingual interface (English, Bengali, Hindi, Punjabi, Bhojpuri, Telugu, Malayalam, Tamil, Marathi).
Includes a contact form powered by Web3Forms API for user inquiries.
Access the webpage here (replace with actual URL if hosted).

Usage:
Power on the robot and ensure all sensors are operational.
Use the cloud dashboard to monitor environmental data and disease alerts.
The robot autonomously navigates fields, stops at plants, detects diseases, and sprays pesticides as needed.
Access the webpage to view project details, gallery, and contact the developer.

Contributing:
Contributions are welcome! Please fork the repository, make changes, and submit a pull request. For major changes, open an issue to discuss your ideas.
License:
This project is licensed under the MIT License. See the LICENSE file for details.
Contact:
For inquiries, use the contact form on the project webpage or reach out via email at sksujonhaque@gmail.com.
© 2025 Sujon | Lovely Professional University
