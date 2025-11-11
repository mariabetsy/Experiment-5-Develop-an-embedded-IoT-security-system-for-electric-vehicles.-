# Experiment-5-Develop-an-embedded-IoT-security-system-for-electric-vehicles.-

## AIM
To develop and implement an Embedded IoT Security System for an Electric Vehicle (EV) that includes secure access authentication, intrusion detection, and encrypted communication, using MATLAB for simulation and visualization.
 
## APPARATUS REQUIRED
✅ Software & Hardware Components
•	MATLAB (for simulation & graph visualization)
•	Microcontroller (ESP32/Arduino) (for real-world implementation)
•	RFID Module / Keypad (for secure access)
•	PIR Motion Sensor (for intrusion detection)
•	IoT Communication Protocol (e.g., MQTT, LoRa, or WiFi if implemented in hardware)
 
## THEORY
1. Secure Access Authentication
•	Uses a predefined password-based system for vehicle unlocking.
•	If the entered access code matches the stored password, access is granted; otherwise, it is denied.
2. Intrusion Detection
•	A PIR motion sensor (or simulated random input) detects unauthorized movement around the vehicle.
•	If motion is detected, an intrusion alert is triggered.
3. Secure Communication Protocol
•	Encrypts and transmits security status messages.
•	Simulated data exchange between the embedded system and the monitoring station.
4. Graphical Representation
•	MATLAB generates a bar graph with: 
o	Green bar → Access Granted ✅
o	Red bar → Intrusion Detected ⚠️
 
## PROCEDURE
Step 1: User Authentication
1.	The system prompts the user to enter the vehicle access code.
2.	If the password matches, access is granted; otherwise, it is denied.
Step 2: Intrusion Detection
3.	The system simulates motion detection (randomized).
4.	If motion is detected, an intrusion alert is generated.
Step 3: Secure Communication
5.	The system sends an encrypted security message.
6.	The message is displayed on the receiver end (simulated in MATLAB).
Step 4: Visualization
7.	A bar chart is generated in MATLAB, showing the status of: 
o	Access Control
o	Intrusion Detection

## Features of This Code
✅ User Authentication – Checks vehicle access code.
✅ Intrusion Detection – Simulates motion sensor input.
✅ Secure Communication – Simulated encryption and message transmission.
✅ Graphical Visualization – Displays security status in a bar chart.
 
## PROGRAM
 
 
## RESULT
The MATLAB program successfully simulates an Embedded IoT Security System for Electric Vehicles, demonstrating:
✅ Access Control System – User authentication mechanism
✅ Intrusion Detection – Motion sensor alert system
✅ Secure Communication – Encrypted security message transmission
✅ Graphical Representation – Real-time security status visualization
📊 Graph Output
•	Green Bar (1) → Access Granted ✅
•	Red Bar (1) → Intrusion Detected ⚠️
•	Bars at 0 → No intrusion or incorrect password
 

