Blynked Brilliance: Controlling Lights with EOG-Driven Signals

Project Overview
Blynked Brilliance is an IoT-based assistive technology that enables hands-free control of a light bulb using Electrooculography (EOG) signals. By detecting eye blinks, the system processes EOG signals and wirelessly toggles the bulb's state using an ESP8266 microcontroller and a relay module.

Features
Eye-blink-based control of a light bulb using EOG signals.
Wireless communication via ESP8266 and Blynk API.
Real-time signal processing for accurate blink detection.
Low-cost, assistive solution for individuals with mobility impairments.

Hardware Requirements
Electrooculography (EOG) Sensor – Captures eye movement signals.
ESP8266 Module – Processes signals and connects to WiFi.
330 kΩ Resistor – For signal conditioning.
Transistor & Relay Module – Controls the bulb based on processed signals.
Light Bulb – The target output device.
Power Supply – To operate the circuit.

Software Requirements
Arduino IDE – For coding and uploading firmware to ESP8266.
Blynk App – Enables wireless connectivity and remote control.
Processing Libraries – For signal filtering and analysis.
Working Principle
The EOG sensor detects eye blinks and converts them into electrical signals.
The ESP8266 processes these signals and sends control commands to the relay.
The relay toggles the light bulb ON or OFF based on blink patterns.
The Blynk platform enables real-time monitoring and remote access.

Applications
Assistive technology for people with physical disabilities.
Hands-free smart home automation.
Research in biosignal-controlled IoT systems.

Future Enhancements
Implementing machine learning for better blink pattern recognition.
Expanding control to multiple appliances using different blink sequences.
Integrating voice and gesture recognition for enhanced usability.
