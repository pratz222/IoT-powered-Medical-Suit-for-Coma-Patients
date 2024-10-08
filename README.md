# IoT-Powered Medical Suit for Coma Patients

This innovative medical suit seamlessly integrates an array of sensors to gather vital data on a patient's heart rate, brain activity, muscle movement, body temperature, and even position. The real-time information is securely transmitted to a cloud platform for remote access by authorized personnel, including doctors, family members, and caregivers, through a user-friendly mobile app.

## Features

- 👁️ **Eye Blink Sensors:** Enable non-verbal communication for coma patients.
- 🧠 **EEG Monitoring:** Provides critical insights into brain activity.
- ❤️ **ECG & SpO₂ Sensors:** Ensure continuous heart and oxygen saturation tracking.
- 💪 **EMG Sensors:** Assess muscle activity for comprehensive health analysis.
- 🌡️ **Temperature Sensors:** Monitor vital body parameters.
- 🔄 **Accelerometers & Gyroscopes:** Prevent falls by detecting body movement and posture changes.

## Hardware Setup

### Components:
- **ESP32 Microcontroller**: For data processing and transmission.
- **Eye Blink Sensor (IR-based)**: To detect eye movements.
- **ECG & SpO₂ Sensors**: To monitor heart rate and blood oxygen levels.
- **EEG Sensor**: To capture brain activity.
- **EMG Sensor**: To assess muscle activity.
- **Temperature Sensor**: To monitor body temperature.
- **Accelerometer & Gyroscope**: For fall detection and posture monitoring.

### Pin Configurations:

- **ESP32 Pin Mapping:**
  - **Eye Blink Sensor**: Connected to GPIO 16.
  - **ECG Sensor**: Connected to GPIO 32.
  - **SpO₂ Sensor**: Connected to GPIO 33.
  - **EEG Sensor**: Connected to GPIO 34.
  - **EMG Sensor**: Connected to GPIO 35.
  - **Temperature Sensor (DS18B20 or similar)**: Connected to GPIO 4.
  - **Accelerometer & Gyroscope (MPU6050)**: I2C SDA connected to GPIO 21, SCL connected to GPIO 22.
  
### Power Requirements:
- Ensure that the ESP32 and all sensors are powered appropriately, either through a common 5V source or through an external power supply if required by specific sensors.

## Data Transmission

All collected data from the sensors is transmitted in real-time to a cloud platform via the ESP32 microcontroller using Wi-Fi. The data is securely stored and can be accessed by healthcare professionals and family members via a mobile app.

### Wi-Fi Configuration:
- Connect the ESP32 to a Wi-Fi network by entering your SSID and password in the source code.
- Ensure stable internet connectivity for real-time data transmission.

## Mobile Application

The Android app allows remote monitoring of vital signs and records all treatments and medications administered. This feature facilitates:
- Easy analysis of patient treatment history.
- Transparent communication between the patient's family and the healthcare providers.

## Cloud Platform

- **Cloud Integration**: Data is sent to a cloud server for real-time access and storage.
- The cloud platform allows authorized users to monitor patient health metrics from anywhere.

## Conclusion

The **IoT-Powered Medical Suit for Coma Patients** aims to enhance patient care through continuous, real-time monitoring, enabling healthcare providers and families to stay informed of the patient’s condition at all times.

![test](https://github.com/pratz222/IoT-powered-Medical-Suit-for-Coma-Patients/assets/53640877/5d7b330d-c748-43f2-a29e-92e5ae16a59e) ![suit](https://github.com/pratz222/IoT-powered-Medical-Suit-for-Coma-Patients/assets/53640877/1aa17f25-c322-43af-b46f-5d1b4d5cf153)

