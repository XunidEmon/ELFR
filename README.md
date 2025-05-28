# ELFR
# ESP32 DC Motor Control with L298N

This project shows how to control a DC motor using an ESP32 and an L298N motor driver.

## Features
- Control motor direction (forward and backward)
- Control motor speed with PWM
- Serial output to monitor motor status

## Hardware Needed
- ESP32 board
- L298N motor driver
- DC motor
- Power supply for motor
- Wires

## Connections
| ESP32 Pin | L298N Pin | Purpose          |
|-----------|-----------|------------------|
| GPIO 27   | IN1       | Motor direction  |
| GPIO 26   | IN2       | Motor direction  |
| GPIO 14   | ENA       | PWM speed control|

## How to Use
Upload the code to your ESP32. The motor will run forward, stop, run backward, stop, then increase speed forward gradually. Open Serial Monitor at 115200 baud to see status messages.

