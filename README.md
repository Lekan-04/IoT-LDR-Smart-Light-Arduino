# LDR Smart Lighting System using Arduino

## Objective
This project demonstrates how a microcontroller communicates with a sensor and performs an action based on the sensor input.

## Sensor Used
Light Dependent Resistor (LDR)

## Components
- Arduino UNO
- LDR
- 10k Resistor
- LED
- 220Ω Resistor
- Breadboard

## Working
The LDR senses light intensity and sends an analog signal to Arduino.

If the environment becomes dark, the Arduino turns ON the LED.

If sufficient light is present, the LED turns OFF.

## Circuit Diagram
![Circuit](circuit_diagram.png)

## Code
The Arduino program reads the sensor value and controls the LED accordingly.
