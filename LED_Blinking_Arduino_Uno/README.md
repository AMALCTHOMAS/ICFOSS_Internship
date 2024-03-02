# Arduino LED Blinking

This project demonstrates how to blink an LED connected to an Arduino Uno using a simple Arduino sketch. The LED blinks on and off at regular intervals determined by a specified delay.

## Components Used
1. Arduino Uno
2. LED
3. Resistor (220 Ohm or similar)

## Folder Structure
- **/program:** Contains the Arduino sketch for the LED blinking project.
- **/documentation:** Contains any additional documentation related to the project, such as circuit diagrams or project notes.

## Circuit Connections
- Connect the longer leg (anode) of the LED to digital pin 7 of the Arduino Uno.
- Connect the shorter leg (cathode) of the LED to the ground (GND) of the Arduino Uno through a current-limiting resistor (330 Ohm).

## Operation
The Arduino sketch uploaded to the Arduino Uno instructs the microcontroller to turn the LED on and off at regular intervals. The duration of each on and off period is determined by a specified delay in milliseconds.

## Instructions
1. Connect the components as per the circuit connections mentioned above.
2. Upload the provided Arduino sketch to the Arduino Uno using the Arduino IDE.
3. Once uploaded, the LED connected to pin 7 of the Arduino Uno will start blinking on and off at regular intervals.
