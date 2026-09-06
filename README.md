# ESP32 IoT Monitoring System
An ESP32-based temperature and humidity monitoring project using a DHT11 sensor.

## Project Overview
This project reads temperature and humidity values from a DHT11 sensor connected to an ESP32 and displays the readings through the Serial Monitor.

## Components
- ESP32 Development Board
- DHT11 Temperature and Humidity Sensor
- Jumper Wires

## Technologies
- Arduino C/C++
- ESP32
- DHT11
- Wokwi
- GitHub

## Features
- Temperature monitoring
- Humidity monitoring
- Serial Monitor output
- Sensor error handling
- Wokwi simulation

## Pin Connection
| DHT11 | ESP32 |
|---|---|
| VCC | 3.3V |
| GND | GND |
| DATA | GPIO 4 |

## Expected Output
The Serial Monitor displays temperature and humidity readings.

Example:
Temperature: 25 °C
Humidity: 60 %

## Project Structure
ESP32-IoT-Monitoring/
├── src/
│   └── main.ino
├── wokwi/
│   └── diagram.json
├── libraries.txt
└── README.md

## Future Improvements
- Add an OLED display
- Add Wi-Fi connectivity
- Send sensor data to a cloud platform
- Create a web dashboard
- Store sensor readings in a database

## Author
Kamesh




