# Driver Assistance System — Obstacle Detection

## Overview
Real-time obstacle detection system built on STM32F446RE microcontroller 
using 4 ultrasonic parking sensors communicating over CAN bus.

## Tech Stack
- MCU : STM32F446RE
- Protocol : CAN Bus
- Language : C
- IDE : STM32CubeIDE / VS Code

## Features
- Obstacle detection (rear, side zones)
- Event-triggered CAN messaging for low-latency alerts
- Detection range : 0.3 m to 3.5 m
- Less than 5% false-positive rate over 10+ test runs

## Hardware Components
- STM32F446RE microcontroller
- 4 x Ultrasonic parking sensors
- CAN transceiver
- Central display unit
