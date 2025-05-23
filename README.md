Universal Power Supply Circuit

This project is an electronic power supply circuit that can be powered by either 12V (AC or DC) or 220V AC, and outputs regulated 5V or 3.3V DC. It includes input protection, voltage regulation, and indicators for status and output selection.

🧩 Features
Dual Input Power:
220V AC (via HLK-PM12 module)
12V input (can be AC or DC)
Selectable Output:
5V or 3.3V regulated DC output
Power Mode Switch:
Toggle between AC or DC mode using a manual switch
Safety Features:
Diodes for reverse polarity protection (especially for 12V DC input)
Bridge rectifier to convert 12V AC to DC
Status Indicator:
LED to indicate that the circuit is powered ON


🔌 Circuit Components
HLK-PM12 : AC-DC module to convert 220V AC to 12V DC
Bridge Rectifier: Converts 12V AC input to DC
7805 Regulator: Outputs regulated 5V
7833 Regulator: Outputs regulated 3.3V
2x Electrolytic Capacitors: For filtering and stabilizing DC output
2x Protection Diodes: Prevents damage if user reverses DC input polarity
Power Mode Switch: Selects between AC and DC input modes
Output Selector Socket: Allows user to choose between 5V and 3.3V output
3x Sockets: 1 for 220V AC input, 1 for 12V input (AC/DC), 1 for output
Power Indicator LED: Lights up when power is supplied to the circuit


⚙️ Working Principle
1-Input:
  If using 220V AC, the circuit powers through HLK-PM12, which outputs 12V DC.
  If using 12V, it can be AC or DC:
  AC: Passed through a bridge rectifier.
  DC: Goes directly to the regulators, with diode protection in case of reversed polarity.
2-Stabilization:
  Capacitors filter and stabilize the voltage before reaching the regulators.
  Output Regulation:
  You can select between 5V (via 7805) or 3.3V (via 7833) using a selector socket.
3-LED Indicator:
  A simple LED indicates that the circuit is powered and active.

  
🛠️ Use Cases
Powering microcontrollers (like Arduino or ESP8266)
Embedded systems
Low voltage control circuits
DIY electronics projects needing stable 5V or 3.3V


📦 Files in This Repo
README.md — You’re reading it now
circuit_diagram — 

🧠 Notes
Always double-check your power source before switching modes.
Make sure proper heat sinking is used for the regulators if high current is expected.
DO NOT touch the board while connected to 220V AC for safety.

.

