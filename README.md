markdown
Copy code
# DHT11 Temperature and Humidity Sensor with Arduino

## Overview

This project demonstrates how to use the DHT11 temperature and humidity sensor with an Arduino. The sensor readings (temperature in Celsius and humidity in percentage) are printed to the serial monitor.

## Prerequisites

- **Hardware**:
  - Arduino board (e.g., Arduino Uno)
  - DHT11 temperature and humidity sensor
  - Connecting wires

- **Software**:
  - Arduino IDE
  - DHT library for Arduino

## Installation

1. **Set Up the Hardware**:
    - Connect the DHT11 sensor to the Arduino:
      - VCC to 5V
      - GND to GND
      - Data pin to digital pin 0 (can be changed if needed)

2. **Install the DHT Library**:
    - Open the Arduino IDE.
    - Go to **Sketch** > **Include Library** > **Manage Libraries**.
    - Search for "DHT" and install the library by Adafruit.

3. **Upload the Code**:
    - Copy the provided code into the Arduino IDE.
    - Select the appropriate board and port from the **Tools** menu.
    - Click the **Upload** button.

## Usage

1. **Open the Serial Monitor**:
    - After uploading the code, open the Serial Monitor from the Arduino IDE (**Tools** > **Serial Monitor**).
    - Set the baud rate to 9600.

2. **View the Output**:
    - The Serial Monitor will display the current temperature and humidity readings from the DHT11 sensor.


