# AIR-QUALITY-MONITORING-SYSTEM
# 🌍 Air Quality Monitoring System using ESP32

## 📌 Overview
The Air Quality Monitoring System is an IoT-based project that continuously monitors air quality, temperature, and humidity using an ESP32 microcontroller. The collected sensor data is displayed on an LCD and sent to the Blynk mobile application for real-time monitoring. If the air quality becomes unhealthy, the system activates a buzzer and sends an alert notification to the user.

---

## 🚀 Features
- Real-time air quality monitoring
- Temperature and humidity monitoring
- Live data on Blynk mobile app
- LCD display for local monitoring
- Buzzer alert for poor air quality
- Wi-Fi enabled using ESP32
- Easy to monitor from anywhere

---

## 🛠️ Components Used

| Component | Quantity |
|-----------|----------|
| ESP32 Development Board | 1 |
| MQ-135 Gas Sensor | 1 |
| DHT11 Temperature & Humidity Sensor | 1 |
| 16x2 LCD with I2C Module | 1 |
| Buzzer | 1 |
| Breadboard | 1 |
| Jumper Wires | As required |
| USB Cable | 1 |

---

## ⚙️ Working Principle

1. ESP32 reads data from the MQ-135 gas sensor.
2. DHT11 measures temperature and humidity.
3. Sensor values are displayed on the LCD.
4. ESP32 sends the data to the Blynk Cloud using Wi-Fi.
5. Users can monitor the data through the Blynk mobile app.
6. When the air quality exceeds the threshold value, the buzzer turns ON and an alert is sent.

---

## 📲 Blynk Dashboard

The Blynk application displays:
- Air Quality
- Temperature
- Humidity
- Alert Status

---

## 📷 Project Images

### Hardware Setup

![Hardware](AIR QUALITY MONITORING SYSTEM.jpg)




---

## 📁 Project Structure

```
Air-Quality-Monitoring-System/
│
├── code/
│   └── AirQualityMonitoring.ino
│
├── images/
│   ├── hardware.jpg
│  
│
├── README.md
```

---

## 💻 Software Used

- Arduino IDE
- Blynk IoT Platform
- ESP32 Board Package

---

## 📊 Future Improvements

- Add PM2.5 and PM10 sensors
- Store data in cloud database
- Email/SMS notifications
- Mobile app improvements
- AI-based air quality prediction

---

## 👩‍💻 Author

**Vasavi Vema**

B.Tech - Electronics and Communication Engineering (ECE)

KL University

---

## 📜 License

This project is developed for educational purposes.
