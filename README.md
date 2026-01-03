# SOS Emergency Button for Elderly Users

## Overview
This project is a simple SOS emergency alert system designed for elderly users.  
When the button is pressed, the system displays emergency messages on an LCD screen and activates a buzzer to alert nearby people.

The project focuses on accessibility, simplicity, and reliability, making it suitable for assistive technology prototyping and beginner embedded systems learning.

---

## Features
- One-press SOS activation
- Emergency messages displayed on a 16x2 LCD
- Audible buzzer alert
- Stable button input using internal pull-up resistor
- Beginner-friendly Arduino C++ logic
- Expandable for GSM or IoT integration

---

## Hardware Components
- Arduino Uno
- 16x2 LCD Display
- Push Button
- Active Buzzer
- Potentiometer (LCD contrast)
- Breadboard
- Jumper wires

---

## CAD Design (Onshape)
- Custom button enclosure designed in Onshape
- Designed for easy pressing with minimal force
- Simple enclosure suitable for elderly users
- Space allocated for wiring and electronics

---

## Arduino Wiring
- Button wired using INPUT_PULLUP configuration
- Button connected between digital pin and GND
- Buzzer connected to a digital output pin
- LCD connected in 4-bit mode
- Common ground shared across all components

This wiring method prevents floating inputs and accidental triggering.

---

## Arduino C++ Code
- System waits for a button press
- SOS mode activates once pressed
- LCD displays:
  - SOS
  - Calling 000
  - SMS to Emergency Contact
- Buzzer beeps repeatedly after activation
- Uses millis() for non-blocking timing

---

## Limitations
- This prototype does not place real calls or send SMS
- GSM or cellular modules are required for real emergency communication
- Intended as a functional prototype and learning project

---

## Future Improvements
- Integrate GSM module for real calls and SMS
- Add reset or cancel button
- Add battery power and portable enclosure
- Improve ergonomics and accessibility
- Add wearable or mobile alert support

---

## Purpose
This project was created as an assistive technology prototype combining:
- Onshape CAD design
- Arduino wiring and embedded C++ logic
- Human-centred design for elderly users
