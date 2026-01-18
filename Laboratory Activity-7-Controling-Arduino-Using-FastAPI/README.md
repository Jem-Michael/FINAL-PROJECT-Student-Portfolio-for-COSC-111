Laboratory Activity #4
Arduino Serial Connection Using FastAPI

Course
COSC 111 – Internet of Things

Objective

The objective of this laboratory activity is to demonstrate Serial communication between an Arduino and a FastAPI web application for controlling LEDs remotely.

Description

This activity uses Serial communication to connect an Arduino with a FastAPI-based Python application. The FastAPI server sends commands through the Serial port, allowing the Arduino to turn LEDs on or off and toggle individual LEDs.

This setup demonstrates how web technologies can be integrated with microcontrollers, a fundamental concept in Internet of Things (IoT) systems.

Activity Overview

The system performs the following functions:

Establishes Serial communication between Arduino and computer

Uses FastAPI to send control commands

Controls multiple LEDs (ON, OFF, Toggle)

Enables remote device control through web requests

Components Required

Arduino Uno

Red, Green, and Blue LEDs

Resistors

Breadboard and jumper wires

Computer with Python and FastAPI

Arduino IDE

Serial Configuration
SERIAL_PORT = "COM3"
BAUD_RATE = 9600

Command Summary
Command	Function
R / G / B	Turn LED ON
r / g / b	Turn LED OFF
1 / 2 / 3	Toggle LED
