
🌱 Smart Irrigation System using Raspberry Pi Pico
This project is a Smart Irrigation System developed using a Raspberry Pi Pico and soil moisture sensors, coded in MicroPython. It automates the plant watering process based on real-time soil moisture data—ensuring efficient water usage and healthier plants.

🚀 Features
🌡️ Real-time soil moisture monitoring

💧 Automatic watering based on soil conditions

🛡️ Prevents overwatering and underwatering

📦 Lightweight codebase using MicroPython

💡 Designed for home gardens, pots, and indoor plants

🛠️ Hardware Components
Raspberry Pi Pico (or Pico W)

Soil moisture sensor (capacitive or resistive)

Water pump or solenoid valve

Relay module or transistor circuit (to control pump)

5V Power supply or battery

Jumper wires and breadboard/tubing as needed

🧠 System Overview
Soil moisture sensor reads the current moisture level of the soil.

Raspberry Pi Pico processes the moisture value.

If the value is below a certain threshold, the system turns on the pump to water the plant.

Once the soil reaches sufficient moisture, the pump turns off.

💻 Software Setup
Requirements
MicroPython firmware installed on Raspberry Pi Pico

Thonny IDE or any MicroPython-compatible editor

Code Files
main.py – Core logic to read moisture levels and control the pump

config.py (optional) – Set thresholds and pin configurations

Installation Steps
Flash MicroPython to your Pico from official site

Open Thonny IDE and connect your Pico

Upload main.py and other files to the Pico

Power the system and test sensor values via serial output
🧪 Future Improvements
Add Wi-Fi connectivity using Pico W to log data or control remotely

Integrate a web dashboard or mobile app

Add temperature and humidity sensors for better climate analysis

