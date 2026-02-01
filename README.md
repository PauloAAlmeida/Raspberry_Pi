# 🍓 Raspberry Pi Projects: Sense HAT & LED Exploration

This repository is dedicated to projects developed for the **Raspberry Pi** ecosystem, focusing on environmental sensing with the **Sense HAT** and physical computing with **LEDs**.

## 🚀 Overview
The goal of this repo is to document experiments and tools that bridge the gap between software and the physical world using Python.

---

## 💡 Project Ideas & Examples

### 🌡️ Sense HAT Projects (Sensors & Matrix)
* **IoT Weather Station:** Reads temperature, humidity, and pressure, displaying the data on the LED matrix and logging it to a cloud dashboard.
* **Digital Spirit Level:** Uses the accelerometer to display a "bubble" on the 8x8 matrix that moves as you tilt the Raspberry Pi.
* **Star Compass:** Utilizes the magnetometer to ensure an LED arrow always points toward Magnetic North.
* **Humidity Alert:** Monitors air quality and displays a blue "drop" icon for high humidity or a red "sun" for dry conditions.
* **Impact Data Logger:** Records a log entry to the SD card whenever the accelerometer detects a sudden drop or sharp movement.
* **Binary Clock:** Displays hours, minutes, and seconds in binary format using the rows of the LED matrix.
* **Real-time CPU Monitor:** Uses the LED matrix as a live bar chart to visualize the processing load across the Raspberry Pi's cores.

### 💡 GPIO & LED Projects (External Hardware)
* **Smart Traffic Light:** A prototype using Red, Yellow, and Green LEDs that changes timing based on a GPIO button press.
* **Email Notification Light:** An external LED that pulses or stays lit whenever an unread "High Priority" email is detected.
* **Visual LED Thermometer:** A LED strip that illuminates more bulbs as the temperature rises, mimicking a mercury thermometer.
* **Visual Morse Code:** A script that translates keyboard input into light signals (flashes) using an external LED.
* **Automatic Night Light:** Uses a Light Dependent Resistor (LDR) to turn on LEDs only when the room becomes dark.

### 🎮 Hybrid Projects (Mix of Hardware)
* **LED Tic-Tac-Toe:** A game played against the AI using the Sense HAT joystick to navigate and select squares.
* **Virtual Pet:** A digital "creature" on the LED matrix that needs to be "fed" by moving the Pi or pressing buttons.
* **Music Spectrum Analyzer:** The Sense HAT LEDs "dance" in sync with the rhythm of ambient sound captured via microphone.

---

## 🔧 Installation & Setup
1. **Enable I2C and GPIO:**
   ```bash
   sudo raspi-config
   (Go to Interface Options -> I2C/GPIO -> Enable)

Install Sense HAT libraries:

Bash
sudo apt-get update
sudo apt-get install sense-hat
