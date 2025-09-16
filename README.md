# Zephyr: Smoke Detector and Weather Station 🚨🌦️

## 📌 Project Overview
**Zephyr** is a smart system that integrates a **smoke detection module** with a **weather monitoring station** to enhance safety and environmental awareness.  
The smoke detector identifies fire hazards in real time, while weather sensors measure parameters such as **temperature, humidity, and air quality**. Data is processed and displayed for easy monitoring, providing timely alerts for potential risks.

This project demonstrates the use of **IoT sensors and embedded systems** to ensure both **safety and environmental tracking**.

---

## ✨ Features
- 🔥 **Smoke Detection** – Detects fire/smoke hazards in real-time.  
- 🌡️ **Weather Monitoring** – Tracks temperature, humidity, and air quality.  
- ⏱️ **Real-Time Alerts** – Provides instant notifications on abnormal readings.  
- 📊 **Data Display** – Sensor values shown on screen/serial monitor.  
- 🛠️ **IoT-based Design** – Combines safety and environmental awareness.  

---

## 🖥️ Tech Stack
- **Hardware**: Arduino / ESP32 (depending on what you used), MQ-2 Smoke Sensor, DHT11/DHT22, Air Quality Sensor.  
- **Software**: Arduino IDE / Embedded C / C++  
- **Communication**: Serial / WiFi (if IoT enabled)  

---

## ⚙️ How It Works
1. The **smoke sensor** continuously monitors air for smoke particles.  
2. **DHT sensor** collects temperature and humidity values.  
3. (Optional) **Air quality sensor** tracks pollution levels.  
4. Data is processed by the microcontroller (Arduino/ESP32).  
5. Alerts are triggered if values cross safe thresholds.  

---

## 🚀 Getting Started
### Prerequisites
- Arduino IDE installed  
- Required libraries: `DHT`, `MQUnifiedsensor` (if used)  

### Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/zephyr-smoke-weather.git
2.Open the .ino file in Arduino IDE.

3.Connect your Arduino/ESP32 board via USB.

4.Upload the code and monitor sensor outputs via the Serial Monitor.
