# Room lighting project

## Components used

- Arduino Uno
- Jumper wires
- MOSFET
- Strip of 4-pin RGB LEDs
- Rechargeable Battery

## About the program

The sourcecode is in the directory [Project_adv](./Project_adv/).

1. Compile and upload the sketch to the Arduino.
2. Open the Serial Monitor.
3. Send a 4 character code consisting of characters between `'0'` and `'9'`.  
The first 3 characters specify the intensity of the R-G-B colours and the last character is for mode.
    - 0 - off,
    - 1 - constant colour,
    - 2 - bloom to bright,
    - 3 - rainbow scroll (RGB),
    - 4 - rainbow scroll (natural),
    - 5 - blink in succession (Disco night).

### Help! The Arduino is receiving characters I did not send

Turn off Line Endings (CR LF / LF / CR) in the Serial Monitor before sending.

## Demonstration

The directory [Videos](./Videos/) contains videos recorded during a project run.

## Simulation and schematic

// TODO
View on [TinkerCAD](https://google.com/404).

## Members

Akshay Pratap Singh and Swastik Pal
