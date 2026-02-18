🚨 Raspberry Pi Motion Detection System using PIR Sensor

This project implements a simple motion detection system using a PIR (Passive Infrared) sensor and an LED with a Raspberry Pi. When motion is detected, the LED turns ON automatically. When no motion is detected, the LED turns OFF.

📌 Overview

The program uses the gpiozero library in Python to interface with:

PIR Motion Sensor connected to GPIO pin 4

LED connected to GPIO pin 16

The system works using event-driven programming, where specific actions are triggered automatically when motion is detected or stops.

🔄 How It Works

The PIR sensor continuously monitors infrared radiation changes in its surroundings.

When motion is detected:

The when_motion event is triggered.

The LED turns ON.

When motion stops:

The when_no_motion event is triggered.

The LED turns OFF.

The pause() function keeps the program running continuously.

🛠️ Hardware Requirements

Raspberry Pi

PIR Motion Sensor (HC-SR501 or similar)

LED

220Ω resistor

Breadboard

Jumper wires

⚙️ Technologies Used

Python

GPIOZero library

Raspberry Pi GPIO pins

🎯 Learning Outcomes

Understanding motion detection using PIR sensors

Using GPIO input and output devices

Implementing event-driven programming

Building basic home automation/security systems

🚀 Applications

Home security systems

Automatic lighting systems

Intrusion detection systems

Energy-saving smart systems
