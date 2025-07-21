

Weather Forecasting using Arduino ESP32
This project demonstrates how to build a simple IoT-based Weather Forecasting System using the ESP32 microcontroller. It fetches real-time weather data from an online API and displays it on an OLED screen or serial monitor. This setup is ideal for hobbyists, students, or IoT enthusiasts looking to learn about APIs, sensors, and microcontrollers.

Features

•	Connects to Wi-Fi and fetches real-time weather data using OpenWeatherMap API

•	Location-based weather updates (via city name or geographic coordinates)

•	Displays temperature, humidity, weather condition, and forecast

•	Optional integration with sensors (like DHT11/DHT22) for local data

•	Output to OLED display or serial monitor

•	Compact, low-power, and customizable design

Hardware Required:

•	ESP32 Development Board

•	OLED Display (SSD1306 - 128x64) (optional but recommended)

•	DHT11/DHT22 sensor (optional)

•	USB cable and power supply

•	Breadboard and jumper wires

•	Software Requirements
•	Arduino IDE

•	ESP32 Board Package installed

Required libraries:

•	WiFi.h

•	HTTPClient.h

•	ArduinoJson.h

•	Adafruit_SSD1306.h (for OLED)

•	DHT.h (if using temperature/humidity sensor)
