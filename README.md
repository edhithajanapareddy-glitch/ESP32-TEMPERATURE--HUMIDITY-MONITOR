# ESP32-TEMPERATURE--HUMIDITY-MONITOR
ESP32-based temperature and humidity monitoring system using a DHT22 sensor, I2C LCD display, and a built-in web server.


A real-time environmental monitoring system built with an ESP32 and DHT22 sensor.
Displays live temperature, humidity, and heat index on an I2C LCD and a 
self-hosted web dashboard accessible over WiFi.

## Features
- Live temp, humidity & heat index readings
- 16x2 I2C LCD display
- Web dashboard served directly from the ESP32
- Auto-refreshes every 3 seconds

## Hardware
- ESP32
- DHT22 sensor
- 16x2 I2C LCD (address 0x27)

## Simulation
Built and tested on Wokwi
https://wokwi.com/projects/465260358521178113


## Libraries Used
- WiFi.h
- WebServer.h
- DHT.h
- LiquidCrystal_I2C.h
