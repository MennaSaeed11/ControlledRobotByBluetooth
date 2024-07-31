# Robot Control Code

This repository contains Arduino code for controlling a robot with motor drivers and Bluetooth control.

## Description

This Arduino sketch allows you to control a robot using serial commands sent over Bluetooth. The robot has functions for moving forward, backward, turning left, turning right, and stopping.

## Hardware Requirements

- Arduino board (Uno)
- Motor driver module (L298N)
- Bluetooth module (HC-05)
- Motors and wheels for the robot


## Commands

The following commands can be sent via serial communication (e.g., Bluetooth terminal):

- `F`: Move forward
- `B`: Move backward
- `L`: Turn left
- `R`: Turn right
- `S`: Stop
