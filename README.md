# Raspberry Pi Pico Rubber Ducky

## Overview
This project demonstrates how to transform a Raspberry Pi Pico into a Rubber Ducky USB device. By using the Pico to run Ducky Script payloads, we can automate tasks and exploit vulnerabilities in target systems. The project includes various payloads such as disabling firewalls, managing tasks, and exploiting BitLocker.

## Components
- **Raspberry Pi Pico** - The microcontroller used for this project.
- **Data cable** - To connect the Raspberry Pi Pico to the computer.

## Project Objectives
1. Create a malicious Ducky Script.
2. Inject the script into the Raspberry Pi Pico.
3. Use the Pico as a USB Rubber Ducky on target systems.

## How It Works
- When connected, the Raspberry Pi Pico acts as a human interface device (HID), like a keyboard, and executes pre-programmed keystrokes.
- The payloads can silently run commands, modify system settings, disable security measures, and potentially compromise the system.
