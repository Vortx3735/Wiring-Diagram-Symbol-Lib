# FRC Wiring Diagram Symbol Library
This is a symbol library for KiCad 8.0.0 with symbols that represent various common FRC electrical components. A symbol in KiCad represents any electrical component.<br>
<br>
This library's purpose is to allow teams to easily create wiring diagrams that can be printed out and quickly looked at during meetings and competitions.<br>

# Notes
- Power wires (positive and negative/red and black) and CAN wires are condensed into one pin/wire for the sake of clarity. That would be very ugly on paper.
- NEO symbols have two pins, "Phase" and "Sensor". Phase represents the black, red, and white wires, and Sensor represents the wires in the braided cable sleeve. Sensor connects to "Encoder" on a SparkMAX symbol.

# Symbols
Here are the symbols/components the library currently has:
- Kraken X44
- Kraken X60
- REV MPM 
- NEO 550
- NEO V1.1
- REV PDH
- roboRIO 2.0
- SparkMAX
- Systemcore<br>

# Usage
If you are unfamiliar with KiCad, watch the 1st video of [this KiCad tutorial](https://youtube.com/playlist?list=PLUOaI24LpvQPls1Ru_qECJrENwzD7XImd&si=i5BihdeC9z7nC0Tp). Again, this library is meant for designing schematics, so the bulk of your work will be in KiCad's Schematic Editor.<br>
<br>
Here is how you can add the library to your Schematic Editor:
1. Download the latest version of the library
2. In the top left of the KiCad home menu, go to "Preferences" -> "Manage Symbol Libraries"
<img width="635" height="267" alt="image" src="https://github.com/user-attachments/assets/c5c20649-2494-4e95-b1cb-54a158226302" /><br>
3. Once in this menu, press the folder icon
<img width="1430" height="917" alt="704518515-8871f3f0-2861-4ced-8fa3-ef2cd025d78e" src="https://github.com/user-attachments/assets/8993fd8d-0c1c-45aa-8d75-9ecc120f1696" /><br>
4. Navigate to where your downloaded library is and select it<br>
5. The library's symbols should now be in the Schematic Editor


