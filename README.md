# Simple-Voting--System
A hardware-based simple voting system designed using 3-to-8 decoders (74HC138) and logic gates without memory elements.
# Simple Voting System 🗳️

## About the Project
This project is a hardware-based four-input simple voting system. It was designed as part of the EEE205 Logic Design LaboratoryThe circuit determines specific voting outcomes using purely combinational logic, without the use of memory elements. Two 3-to-8 decoders process the inputs to generate signals for the conditions.

## Hardware Components (BOM)
The system was implemented and tested on a breadboard. The following components were required:
* IC 74HC138 (3-to-8 Decoder) 
* IC 7432 (OR Gate) 
* IC 7404 (NOT Gate) 
* LEDs (to visually represent winning and tie conditions) 
* Switches and Connecting Wires 

## System Logic
The system processes 4 binary inputs (A, B, C, D) representing the participants' votes.
* **Win Condition:** If three or more participants vote, the WIN LED activates.
* **Tie Condition:** If exactly two participants vote, the TIE LED activates.
* **Other Combinations:** Scenarios with zero or one vote result in no LED activation.

## Implementation & Testing
* Theoretical Design:** K-Maps and Boolean algebra were utilized to derive the minimized expressions for Win, Tie, and Lose conditions[cite: 90, 93, 96, 100].
* Simulation:** The logic circuit was simulated and verified visually[cite: 118].
* Hardware:** The final design was wired on a breadboard, and all possible input combinations were tested to verify the truth table[cite: 70, 78, 79].
