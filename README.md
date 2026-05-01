📏Arduino Ultrasonic Distance Measurement System
📌 Overview

This project uses an ultrasonic sensor (HC-SR04) with Arduino to measure the distance of an object in real time. The measured distance is displayed in the Serial Monitor.

⚙️ Components Used
Arduino UNO
Ultrasonic Sensor (HC-SR04)
Breadboard
Jumper Wires
🔧 Working Principle

The ultrasonic sensor emits a sound wave using the trigger pin. The wave reflects off an object and returns to the sensor. The Arduino measures the time taken for the echo to return and calculates the distance using the speed of sound.

📐 Formula Used

Distance = (Time × 0.034) / 2

💻 Code Explanation
Trigger pin sends a 10µs pulse
Echo pin receives reflected signal
pulseIn() measures time duration
Distance is calculated and printed

📊 Output
<img width="1584" height="671" alt="Screenshot 2026-05-01 111239" src="https://github.com/user-attachments/assets/993c97c2-9060-43e7-b2b6-43d37467f71d" />


Distance values are displayed  on the Serial Monitor in real time.

🚀 Future Improvements
Add buzzer for distance alert (parking sensor)
Add LED indicators for distance range
Display output on LCD screen

👩‍💻 Author
SATVIKA SARASWATHI

