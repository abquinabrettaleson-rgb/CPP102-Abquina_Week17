## Simulated Device Monitoring and Alert System
 
Student Name: (Abquina, BrettALeson B.)
Student Number: (2601299)
Section: (1CPE-A)
 
## Project Description
Write 2 to 4 sentences. Example: This program monitors simulated sensor readings and processes each value based on the given conditions. It classifies the readings, counts the results, and calculates the required statistics. Finally, it displays a summary of the processed data.
 
## Features
-This program allows users to view and add temperature readings within the range of 0 to 100. It classifies each reading and shows a summary of the results, including the overall status. It also checks for invalid inputs and menu choices to make sure the program runs properly
 
## Requirements
-This program is made using Python 3 and does not require any additional packages to run. It uses built-in Python functions to manage temperature readings, classify them, and display the summary
 
## How to Run
1. Open a terminal inside the Week17 folder.
2. Type: python device_monitor.py
   (On macOS or Linux, type: python3 device_monitor.py)
 
## Sample Output
```
(paste a short part of your REAL program output here)
```
 
## Test Cases
I performed 10 tests. __ passed and __ failed.
Full details are in test_cases.md.
 
## Known Limitations
- Example: Readings are lost when the program closes.
- (add your own)
 
## Reflection
The hardest part was making sure each temperature reading was classified correctly based on the given conditions. I fixed a bug in the input validation by checking if the reading was a whole number between 0 and 100. Next, I would improve the program by making the menu easier to use and the results easier to understand