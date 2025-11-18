FOSSEE Winter Internship Task 2 - IoT Data Logging (ESP32 + DHT11 + Blynk Cloud)

## Overview

This project logs data from a DHT11 temperature/humidity sensor using an ESP32 microcontroller, sending the data to Blynk Cloud every 10 seconds for live visualization. The dashboard displays real-time sensor readings and historical graphs.

## Components Used:

- ESP32 Dev module
- DHT11 sensor
- Breadboard, jumper wires

## How It Works:

- ESP32 reads DHT11 sensor values every 10 seconds
- Data is sent via WiFi to Blynk Cloud using the Blynk IoT library
- Blynk dashboard displays live data on web/mobile app

## How to Run:

1. Set up Blynk account, create template (copy Template ID, Name, Auth Token)
2. Connect hardware as shown
3. Upload code to ESP32 (see `main.ino`)
4. Open Serial Monitor and Blynk dashboard to view data
