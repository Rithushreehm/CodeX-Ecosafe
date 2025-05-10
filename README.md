Team : CodeX
College : Government Engineering College Hassan
Domain : Sustainability
Topic : EcoSafe 5G Infrastructure

 "As the world moves toward advanced connectivity, sustainability must 
be at the heart of innovation. 5G networks promise speed and efficiency, 
but what about environment ?”
 5G networks offer unprecedented speed, lower latency, and increased 
capacity, but using 5G impacts on environment by high energy consumption, resource 
depletion, and electronic waste.

# EcoSafe 5G - Sustainable 5G Infrastructure Prototype

EcoSafe 5G is a smart, energy-efficient 5G support infrastructure prototype designed for sustainable deployment in remote or sensitive environments. It leverages renewable energy sources (solar and wind) to power sensors and communication modules.

## Features

- *Renewable-powered 5G support*
- Monitors:
  - Temperature and Humidity (DHT11)
  - Solar Power (via voltage reading)
- Web dashboard for monitoring via ESP8266 Wi-Fi
- Eco-friendly and suitable for defense, rural, and disaster recovery areas

## Hardware Components

- ESP8266
- OLED Display (SSD1306)
- DHT11 Sensor
- Lithium-Ion Battery
- Solar Panel
- TP4056 Charging Module
- (Optional) Wind Turbine


## Installation

1.Install Arduino IDE
2. Copy the repo path from github https://arduino.esp8266.com/stable/package_esp8266com_index.json
3. In board manager install ESP8266 and then install NodeMCU 1.0(ESP 12E-module)
4. Install required libraries:
    - Adafruit SSD1306
    - Adafruit GFX
    - DHT Sensor Library
    - ESP8266WiFi

5. Upload code to ESP8266 board.

## Web App Access

- Connect ESP8266 to Wi-Fi.
- Check Serial Monitor for IP Address.
- Open IP in browser to view sensor data.

## Use Case

This prototype is designed to:
- Reduce 5G carbon footprint
- Support smart cities and surveillance in remote zones
- Function during grid outages

## Future Improvements

- Integrate battery management ICs
- Add more environmental sensors
