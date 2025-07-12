# Integrated-Gas-Leak-Detection-and-Alert-System
🔍 Project Overview
This project is a real-time gas leakage detection and alert system designed for residential, industrial, and commercial use. It uses sensors, microcontrollers, and communication modules to detect the presence of hazardous gases like LPG, methane, carbon monoxide, and ammonia, and responds with audible, visual, and digital alerts to prevent accidents.

🧠 Key Components
MQ-135 Gas Sensor – Detects various harmful gases.

Arduino UNO – Processes sensor data and controls the system.

GSM Module – Sends SMS alerts to users in case of gas detection.

Buzzer & LED – Triggers audible and visual alarms.

Relay Module – Automatically cuts off gas and power supply to prevent accidents.

IoT (Blynk App) – Optional remote monitoring and alert system via smartphone.

⚙️ Working Process
MQ-135 continuously monitors air for gas concentration.

If gas exceeds a safe threshold, Arduino:

Activates buzzer and LED.

Sends SMS to the user via GSM module.

Uses relay to turn off the gas regulator and electrical supply.

Optionally, data can be sent to the Blynk IoT app for real-time cloud monitoring and notifications.

💡 Features
Real-time gas leak detection

Auto shut-off for gas and electricity

SMS alert system for remote notification

IoT support via Blynk (mobile app)

Low-cost and easy to implement

🛠️ Technologies Used
Arduino IDE

Embedded C / C++

Blynk IoT Platform

GSM Communication

Sensor Integration

📱 Future Scope
Add temperature & flame sensors for extended safety

Integrate Wi-Fi for more advanced cloud features

Enable mobile app controls and analytics dashboard

🔗 Project Status
✅ Working Prototype Developed
📤 Ready for GitHub Upload
📱 Optional IoT Interface via Blynk App
