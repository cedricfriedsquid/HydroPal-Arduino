# HydroPal: Arduino Branch

## Description
This is the Arduino code for the HydroPal smart water bottle JA company. The code will primarily allow the Arduino Nano board to read the ml/sec of liquids going though the nozzle of the bottle in order to measure the millitres of water that a person drinks throughout the day.

## Setting up
1. Download the Arduino IDE from here: https://www.arduino.cc/en/Main/Software
2. If you are using a Mac with an Arduino with a CH34x USB chip, install the driver above
3. Change any pin numbers as required
4. Upload code to Arduino board, make sure the right port and model of the board is selected

## Current Functionality
- [x] Checks sensor reading every second to find ml/sec passing through sensor
- [x] Adds sensor reading to total ml of liquid consumed throughout the day
- [x] Converts ml to L after 1 L is reached
- [x] LED indicators for total volume consumed, for 5 LEDs

## To-do
- [ ] Reset total counter midnight every day
- [ ] Indicate total consumption and/or percentage of goal achieved everyday
- [ ] Simple serial calibration for more accurate readings

## Changelog:

### Alpha 2.0
- LEDs can indicate how much has been consumed, one for each 1 L
- LEDs in progress of being filled up blink

### Alpha 1.0
- Initial release
- Measures flowrate in ml/sec and adds up to total water consumed
