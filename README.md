# 🏠 Smart Home Automation using Arduino

A low-cost, IoT-based home automation system using Arduino and various sensors/modules to control electrical appliances remotely via smartphone or voice assistant.

---

## 📌 Features

- ✅ Remote control of appliances via smartphone (Blynk / Bluetooth)
- 🎤 Voice control using Google Assistant (via IFTTT)
- 🌡️ Temperature and humidity-based fan control
- 🌞 Automatic light control using LDR
- 🕵️ Motion-based security alerts
- 🕒 Scheduled operations using real-time clock or app

---

## 🔧 Components Used

| Component                     | Description                          |
|------------------------------|--------------------------------------|
| Arduino Uno/Nano             | Microcontroller                      |
| Relay Module (2/4 Channel)   | Switch AC appliances                 |
| ESP8266 / HC-05              | Wi-Fi / Bluetooth Module             |
| DHT11                        | Temperature & Humidity Sensor        |
| PIR Motion Sensor            | Detects movement                     |
| LDR                          | Light detection                      |
| Smartphone + Blynk / IFTTT   | Control Interface                    |
| Jumper wires, Breadboard     | Connections                          |

---

## ⚙️ How It Works

1. Sensors collect real-time data (motion, temperature, light).
2. Arduino processes the input and triggers appropriate outputs (e.g., relay ON/OFF).
3. Wi-Fi/Bluetooth modules connect the system to your smartphone or internet.
4. Control appliances manually or through automated triggers.

---

## 🚀 Getting Started

### 📁 Folder Structure


### 🖥️ Uploading the Code

1. Open `smart_home.ino` in the Arduino IDE.
2. Select the correct board (Arduino Uno/Nano).
3. Choose the right port and upload.

---

## 📱 Mobile App Setup

### 🔹 mit app inventor (for Wi-Fi)

- Add a new project.
- Add buttons linked to Virtual Pins (V1, V2, etc.).
- Enter your Auth Token in the Arduino code.

### 🔹 IFTTT + Google Assistant (for voice)

- Create applets with “Say a phrase” trigger.
- Connect to a Webhooks request that triggers your ESP module.

---

## 🧠 Future Improvements

- Alexa integration  
- Mobile notifications for motion or fire detection  
- Energy usage analytics  
- Touch or gesture-based controls

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## ✍️ Author

**Ayan Munshi**  

