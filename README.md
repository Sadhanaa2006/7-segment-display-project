💡 **7-Segment Display using 8051 Microcontroller**  
An embedded systems mini project developed using Embedded C in Keil uVision and simulated in Proteus Design Suite.

🚀 **Project Overview**  
This project demonstrates interfacing of a 7-segment display with the 8051 microcontroller. The display is used to show digits from 0 to 9 sequentially using Embedded C programming.

The project was created to understand:

-> 8051 port operations  
-> 7-segment display interfacing  
-> Lookup table (array) concept in Embedded C  
-> Delay generation in embedded systems  
-> Keil to Proteus simulation workflow  

🛠️ **Tools and Technologies**  
-> Embedded C  
-> Keil uVision  
-> Proteus Design Suite  
-> AT89C51 / 8051 Microcontroller  

📂 **Repository Contents**  
-> sevenseg.c – Source code  
-> tech.hex – Compiled output file  
-> 7SEGMENT_ANODE.pdsprj – Proteus simulation project  

⚙️ **Working Principle**  
The 7-segment display is connected to Port 1 (P1) of the 8051 microcontroller.

A lookup table (array) is used to store hexadecimal values for digits 0 to 9:

-> 0 → 0xC0  
-> 1 → 0xF9  
-> 2 → 0xA4  
-> 3 → 0xB0  
-> 4 → 0x99  
-> 5 → 0x92  
-> 6 → 0x82  
-> 7 → 0xF8  
-> 8 → 0x80  
-> 9 → 0x90  

These values are sent continuously to the port, making the display show digits from 0 to 9 in a loop.

🎯 **Learning Outcomes**  
-> Basic Embedded C programming  
-> Microcontroller port interfacing  
-> 7-segment display working principle  
-> Lookup table usage in embedded systems  
-> Circuit simulation using Proteus  
-> GitHub project documentation   
