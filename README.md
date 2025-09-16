🌱 Smart Irrigation System using ESP8266                                                                                 
📌 Overview

The Smart Irrigation System is an IoT-based project designed to automate plant watering using the NodeMCU ESP8266 microcontroller, a soil moisture sensor, and a relay-controlled water pump. The system monitors real-time soil moisture levels and activates the water pump only when needed, ensuring efficient water usage and reduced manual intervention.

The project is also integrated with the Blynk IoT platform, allowing users to remotely monitor soil conditions and control the water pump through a smartphone app. An LCD display provides live feedback of moisture levels and pump status.

🎯 Objectives

Automate irrigation using soil moisture detection.

Provide real-time monitoring via an LCD and the Blynk mobile app.

Enable remote control of the water pump from anywhere.

Promote water conservation by irrigating only when required.

⚙️ Components Used

NodeMCU ESP8266 (Wi-Fi enabled microcontroller)

Soil Moisture Sensor

Relay Module

Water Pump

16x2 LCD (I2C Module)

Power Supply (5V/12V depending on pump)

Breadboard, jumper wires

🛠️ Working Principle

The soil moisture sensor continuously monitors soil conditions.

If moisture falls below the threshold → Relay activates water pump.

Moisture level and pump status are displayed on the LCD screen.

The Blynk app allows:

Real-time monitoring

Manual ON/OFF control of the water pump

🔌 Circuit Connections

Soil Moisture Sensor → A0 (NodeMCU)

Relay IN → D5 (NodeMCU)

Water Pump → Relay Output (NO/COM)

LCD (I2C) → SDA (D2), SCL (D1)

💻 Software Requirements

Arduino IDE

Blynk IoT Library

ESP8266WiFi Library

LiquidCrystal_I2C Library

📱 Blynk App Setup

Create a new project in Blynk.

Add:

Gauge → Soil moisture percentage

Button → Water pump ON/OFF

Copy the Auth Token into your Arduino code.

🚀 Future Enhancements

Weather-based irrigation using forecast APIs.

Multi-sensor setup for larger fields.

Solar-powered system for remote use.

Cloud-based data storage and analytics.

Automatic fertilizer dispensing.

Integration with voice assistants (Google Alexa)
