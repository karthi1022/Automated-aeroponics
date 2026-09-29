# Automated Precision Aeroponics System

A closed-loop soilless agricultural control unit that manages atomized misting intervals and root zone climate.

##  Hardware & Components
- Microcontroller: ESP32 
- Actuators: High-pressure mist pump & solenoid valves
- Sensors: DHT22 (Temp/Humidity), Water Level, and TDS/pH sensors

## Tech Stack
- Firmware: Embedded C
- Control Logic: Non-blocking timer loops for high-frequency short-burst misting

## Key Features
- High-efficiency root hydration cycles to minimize water consumption.
- Automated nutrient concentration monitoring and water reservoir cutoffs.
- Sensor logging for optimal root-zone temperature and humidity.
