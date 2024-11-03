# GasGuard - IoT-Based Gas Detection System

**GasGuard** is a real-time IoT gas detection system that monitors gas levels and sends alerts via the Blynk app if dangerous levels are detected.

## Features
- Real-time monitoring through the Blynk app
- Instant notifications and local buzzer alerts on leak detection
- Configurable detection threshold

## Setup Instructions

### Prerequisites
- **Arduino IDE**: Download and install the [Arduino IDE](https://www.arduino.cc/en/software).
- **Blynk Library**: Install via Arduino Library Manager or download from [Blynk GitHub](https://github.com/blynkkk/blynk-library).
- **ESP8266 Board Library**: Install using `http://arduino.esp8266.com/stable/package_esp8266com_index.json` as described below.

### Installing ESP8266 Board in Arduino IDE
1. Open **Arduino IDE** and go to **File > Preferences**.
2. Under "Additional Boards Manager URLs", add:
    http://arduino.esp8266.com/stable/package_esp8266com_index.json

3. Go to **Tools > Board > Boards Manager** and search for "ESP8266".
4. Click "Install" for the ESP8266 package.

### Cloning the Repository
```
git clone https://github.com/HarshilMalhotra/GasGuard-IoT.git
```

