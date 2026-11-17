
# Non-Blocking Traffic Light System

## Project Description
This project demonstrates non-blocking programming using Arduino Uno.

It controls three traffic LEDs and one independent indicator LED.

## Components
- Arduino Uno
- Red, yellow and green LEDs
- One indicator LED
- 4 x 220 ohm resistors
- Breadboard and jumper wires

## Connections
- Red LED: Pin 8
- Yellow LED: Pin 9
- Green LED: Pin 10
- Indicator LED: Pin 11

## Working
- Red light: 5 seconds
- Green light: 3 seconds
- Yellow light: 2 seconds
- Indicator LED toggles every 500 milliseconds.

## Timer Used
The millis() function uses Arduino's internal Timer0 timekeeping.

## Why Non-Blocking Code?
The program does not use delay().
It allows the traffic light and indicator LED tasks
to run independently at different rates.

## Expected Output
Traffic lights change automatically while the
indicator LED blinks independently.
