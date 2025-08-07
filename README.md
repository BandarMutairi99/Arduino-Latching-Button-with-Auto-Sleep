# Arduino-Latching-Button-with-Auto-Sleep

# Description

Arduino. The LED toggles its state (ON/OFF) with each button press. If no interaction occurs for a certain period, the Arduino automatically enters power-down sleep mode to save battery. When the button is pressed again, the Arduino wakes up and resumes operation.

#  Components Used


Arduino Uno (or compatible)

Push button

LED

220Ω resistor (for LED)

10kΩ resistor 

Jumper wires


# the circuit 

<img width="722" height="350" alt="Image" src="https://github.com/user-attachments/assets/530067f3-eb70-4a78-9c3e-14927559b845" />



 # Circuit Connections
 

Push Button:

One terminal → Arduino pin 3 (D3)

Other terminal → 5V

10kΩ resistor connected between pin 3 (D3) and GND (acting as a pull-down resistor)

LED:

Anode (long leg) → Arduino pin 8 (D8) through 220Ω resistor

Cathode (short leg) → GND


# Reverence 

https://youtu.be/UkKtalYsDws





























Breadboard

