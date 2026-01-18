Laboratory Activity #4
Arduino Serial Connection Using FastAPI

Course: COSC 111 – Internet of Things

📌 Objective

To demonstrate Serial communication between an Arduino and a FastAPI web application for remotely controlling LEDs.

📖 Description

This project connects an Arduino to a FastAPI-based Python application using Serial communication. The FastAPI server sends control commands through API endpoints, allowing LEDs connected to the Arduino to be turned ON, OFF, or toggled individually.

This project demonstrates basic Internet of Things (IoT) concepts by integrating hardware control with web-based APIs.

⚙️ Features

Serial communication between Arduino and FastAPI

Web API endpoints for LED control

Turn all LEDs ON or OFF

Toggle individual LEDs (Red, Green, Blue)

🧰 Components Used

Arduino Uno

Red, Green, and Blue LEDs

Resistors

Breadboard and jumper wires

Computer with Python and FastAPI

Arduino IDE

🔌 Serial Configuration
SERIAL_PORT = "COM3"
BAUD_RATE = 9600

🎮 Command Reference
Command	Action
R / G / B	Turn LED ON
r / g / b	Turn LED OFF
1 / 2 / 3	Toggle LED
