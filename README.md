Smart Blind Stick Using Arduino Uno

Introduction
The Smart Blind Stick is an assistive device designed to help visually impaired individuals navigate their surroundings more easily. 
This project utilizes an Arduino Uno microcontroller along with various sensors like an ultrasonic sensor, a buzzer, and a vibration motor to detect obstacles and provide auditory and tactile feedback.

Features
Obstacle Detection: Detects obstacles in front of the user using an ultrasonic sensor and provides alerts.
Auditory Feedback: A buzzer sounds when an obstacle is detected within a certain distance.
Vibrational Feedback: A vibration motor activates to provide tactile feedback when an obstacle is too close.
Light Detection: The stick includes an LDR (Light Dependent Resistor) to detect if the environment is dark and triggers an LED to assist in low-light conditions.


Components Required

Arduino Uno
Ultrasonic Sensor (HC-SR04)
Buzzer
Vibration Motor
LDR (Light Dependent Resistor)
LED
Battery or Power Source (5V)
Jumper Wires
Stick (for mounting components)
Circuit Diagram

How It Works

The smart blind stick works by continuously checking for obstacles in front of the user using an ultrasonic sensor. 
If an obstacle is detected within a set threshold distance (e.g., 100 cm), the buzzer sounds, and the vibration motor activates,
alerting the user of the danger ahead. Additionally, if the environment is dark (as detected by the LDR), an LED will light up to provide additional visual assistance.
