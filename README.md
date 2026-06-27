# smart-agriculture-robot
“ESP8266-based agriculture robot with RemoteXY cloud control, soil monitoring, relays &amp; servo actuation.”

# Smart Agriculture Robot (ESP8266 + RemoteXY)

IoT-enabled agriculture robot built on ESP8266, controlled via RemoteXY Cloud.
Includes:
- RC car movement with joystick
- Servo-based seed sowing & soil sensor insertion
- Soil moisture monitoring
- Automated & manual relay control for water pump

## 📦 Features
✅ Remote control via RemoteXY app  
✅ Soil moisture feedback & visualization  
✅ Manual/auto water pump control  
✅ Servo actuation for mechanical tasks

## 🛠 Hardware Used
- ESP8266 NodeMCU
- L298N Motor Driver
- Servo Motors (SG90)
- Soil Moisture Sensor
- Relays
- Power source

## 🧰 Software & Libraries
- Arduino IDE / PlatformIO
- RemoteXY Library
- Servo.h
- ESP8266WiFi.h

## 📌 Pinout
| Function       | ESP8266 Pin |
|----------------|------------:|
| Motor IN1      | D1          |
| Motor IN2      | D2          |
| Motor IN3      | D3          |
| Motor IN4      | D4          |
| Servo 1        | D5          |
| Servo 2        | D6          |
| Relay 1        | D7          |
| Relay 2        | D8          |
| Soil sensor    | A0          |
