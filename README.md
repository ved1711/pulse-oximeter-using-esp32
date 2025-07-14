Pulse Oximeter using ESP32
This project is a Pulse Oximeter built using the ESP32 microcontroller and the MAX30100/MAX30102 pulse sensor. It measures blood oxygen saturation (SpO₂) and heart rate (BPM) and displays the readings via serial monitor, OLED display, or web dashboard (optional). Ideal for IoT health monitoring and embedded systems projects.

🛠️ Features
✅ Real-time monitoring of SpO₂ and pulse rate

✅ Integration with MAX30100/MAX30102 sensor

✅ LED display support with I2c module

✅ Optional Wi-Fi dashboard using ESP32's web server

✅ Portable and low power

✅ Easy to build and modify

🔧 Hardware Requirements
ESP32 Dev Board

MAX30100 or MAX30102 Pulse Oximeter Sensor

16*2" LED Display  [Optional]

Breadboard and Jumper Wires

USB Cable for Programming

📦 Software Requirements
Arduino IDE

ESP32 Board Package

Required Libraries:

Adafruit_GFX

Adafruit_SSD1306

Wire

MAX30100_PulseOximeter or MAX30102 by SparkFun (as applicable)

WiFi and WebServer (for web dashboard)

🚀 Getting Started
Install Arduino IDE and configure it for ESP32.

Connect the MAX30100/MAX30102 to the ESP32 via I2C (default: SDA = GPIO21, SCL = GPIO22).

[Optional] Connect SSD1306 OLED display to the same I2C bus.

Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/pulse-oximeter-esp32.git
Open the code in Arduino IDE and upload it to your ESP32.

📊 Output Example
Heart Rate: 78 BPM

SpO₂ Level: 98%

LED / Serial Monitor displays real-time readings.

