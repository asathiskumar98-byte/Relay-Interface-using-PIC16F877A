# 💡 Relay Interface using PIC16F877A

## 🔧 Project Overview
This project demonstrates controlling a relay using a PIC16F877A microcontroller.  
A push button connected to RB0 acts as the input. When pressed, the relay connected to RB1 is turned ON; when released, the relay turns OFF.

## ⚙️ Hardware & Software Requirements

### Hardware:
- PIC16F877A Microcontroller
- Relay Module
- Push Button
- 1kΩ Resistor (for button pull-down if needed)
- Diode (for flyback protection across relay)
- Breadboard / Proteus simulation board
- Connecting wires

### Software:
- MPLAB X IDE
- XC8 Compiler
- Proteus 8 Professional (for simulation)

🧩 Proteus Circuit Setup

Controller: PIC16F877A

Oscillator: 20 MHz Crystal (pins 13 & 14)

Input Button: Connect to RB0 with pull-down resistor

Relay: Connect control pin to RB1, diode across relay coil for protection

Power: +5V to VDD, GND to VSS

▶️ Simulation Steps

Open Proteus_Design.pdsprj in Proteus 8.

Load the compiled .hex file from MPLAB X.

Run the simulation — pressing the button turns the relay ON, releasing turns it OFF.

📸 Output

Relay follows the button input:

Button Pressed → Relay ON
Button Released → Relay OFF

🧰 Future Expansion Ideas

Add multiple relays with different control buttons.

Interface with LCD to display relay status.

Add delay timers or toggle modes for advanced control.
