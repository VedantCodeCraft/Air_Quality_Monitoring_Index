# Air_Quality_Monitoring_Index
"Air Quality Monitoring Index is an Arduino-based system designed to continuously monitor indoor air quality. Using a combination of sensors, including DHT11, MQ7, MQ135, and ACD10, the system provides real-time data on temperature, humidity, carbon monoxide, air quality, and carbon dioxide levels.

# Components
- Arduino Nano
- DHT11 (Temperature and Humidity Sensor)
- MQ7 (Carbon Monoxide Sensor)
- MQ135 (Air Quality Sensor)
- ACD10 (Carbon Dioxide Sensor)
- 20x4 LCD Display
- Breadboard
- Jumper Wires

# Usage
1. Connect the sensors and LCD display to the Arduino Nano according connection provided in other file. 
2. Upload the code to the Arduino Nano.
3. Open the serial monitor to view the real-time data.
4. Adjust the setBacklightBrightness function to control the LCD backlight brightness as needed.

# Credits
- [DHT library](https://github.com/adafruit/DHT-sensor-library) by Adafruit
- [LiquidCrystal_I2C library](https://github.com/johnrickman/LiquidCrystal_I2C) by Frank de Brabander
