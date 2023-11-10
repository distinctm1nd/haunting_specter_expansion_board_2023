# haunting_specter_expansion_board_2023

# About Haunting Specter Expansion Board

The Haunting Specter Expansion Board is designed to power and display up to 8 minibadges. Minibadges are a staple at the Saintcon conference that occurs every Fall in Utah. The expansion board can either be powered by connecting it directly to the main (Saintcon) conference badge or as a standalone badge with batteries. Additional expansion board can be attached to and powered from this board. This design was intentionally made easy for swapping out LEDs so that you could practice selecting resistor/LEDs for series circuits and /or so that you could try different color combinations. However, it is not required to swap anything out to build /enjoy this and you can simply build it with provided components. 

# Haunting Specter Expansion Board Instructions

Before starting, verify that you have all of the components. If anything is missing contact me (distinctm1nd) on discord. Also, contact me if you have any questions before / during the assembly process. 

Contact lavaman on discord if you would like a 3d printed back for this board. 

This board was available in two versions. One had multicolored LEDs and one had red / yellow LEDs. Both boards have instructions for swapping out different color LEDs (if desired). 

## Components:

### Multi-Color Version
- Haunting specter pcb 
- 1- through hole Green LED
- 1- through hole multicolor fast flash LED
- 3- Green 1206 SMD LEDs (marked with green marker)
- 1- yellow-green 1206 SMD LED
- 1- Red 1206 SMD LED (marked with red marker)
- 3- Orange 1206 SMD LEDs (marked with orange marker)
- 2- Pink 1206 SMD LEDs (mark with pink marker)
- 1- yellow 1206 SMD LED (marked with yellow marker)
- 1- blue 1206 SMD LED (marked with blue marker)
- 8- 1206 SMD 15 ohm resistors (marked with 15R0)
- 6- 1206 SMD 68 ohm resistors (marked with 68R0)
- 3- 20 pin connectors 2.54mm
- 16- 8 pin male headers 2.54mm
- AA battery holder
- 2- AA batteries



Red / Yellow Version
Haunting specter pcb 
1- 15 ohm SMD 1206 resistor (marked with 15R0)
13- 68 ohm SMD 1206 resistors (marked with 68R0)
9- Red 1206 SMD LEDs (marked with red marker)
3 - Yellow 1206 SMD LEDs (not marked)
1- through-hole 3mm Red LED
1- through-hole 3mm multicolor fast flash LED
3- 20 pin connectors 2.54mm
16- 8 pin male headers 2.54mm
AA battery holder
2- AA batteries

Optional:

I’m including a list of resistor / LED pairings so that you can customize the LED colors, if desired. You’ll need to supply your own LEDs/resistors for any changes. If you don’t wish to customize the LED colors, skip to the assembly instructions. There are separate assembly instructions for the red/yellow and the multi-color versions, so jump to whichever one you have. 

There are many calculators available to calculate the current limiting resistor for a series resistor/LED circuits such as this one: https://ledcalculator.net/

All of the resistors in the Haunting Specter Expansion Board are in series with their respective LED. For example, D1 is in series with R1, D2 is in series with R2, etc. This means that you can use the calculator above to calculate the new resistance for each resistor that is in series with the LED that you wish to change. 


So, for instance, if you want to change D1 from Red to Blue you will need the ‘forward voltage’ and ‘forward current’ of the Blue LED (forward voltage: 3-3.3v and forward current: 20mA). Note: this may not always be the case so consult the documentation for the specific LED you are using. You can then use the calculator to calculate the minimum required resistor. In this application, the Power Source is 3.3 volts, so you would enter:

Power supply voltage (V): 3.3
LED voltage drop (V): 3.0 (assuming this is the forward voltage of your LED)
LED current rating (mA): 20 (assuming this is the forward current of your LED)

Which gives 15 ohms. This is the minimum required resistance to guarantee that you will not burn up the LED. You can use a larger resistance than this and it will have the effect of dimming the LED. 

Contact me on discord if you have questions. 

LED
Resistor
Location - Color Provided
D1
R1
Left eye front pupil - through-hole LED
D2
R2
Right eye front pupil- through-hole LED
D3
R3
Right eye (from front)
D4
R4
Right eye (from front)
D5
R5
Left eye (from front)
D6
R6
Left eye (from front)
D7
R7
Nose
D8
R8
Nose
D9
R9
Nose
D10
R10
Mouth
D11
R11
Mouth
D12
R12
Mouth
D13
R13
Left eye (from front)
D14
R14
Right eye (from front)


Assembly Instructions (Multi-Color Version):

Verify correct orientation of all LEDs before soldering them. 

Start on the back: 
Solder a green LED to D3
Solder a yellow-green LED to D4
Solder a blue LED to D14
Solder a yellow LED to D13
Solder an orange LED to D6
Solder a red LED to D5
Solder a pink LED to D7
Solder an orange LED to D8
Solder a green LED to D9

Note: D9 is on the left side of the nose (on back) and the cathode is on the bottom side. I have marked it with a black dot.




Solder a pink LED to D12
Solder a green LED to D11
Solder an orange LED to D10

Move to the front:
Solder 68 ohm resistors to R4, R5, R6, R8, R10, R13
Solder 15 ohm resistors to R1, R2, R3, R7, R9, R11, R12, R14
Solder the through-hole multicolor fast flash LED to the left eye
Solder the through-hole green LED to the right eye

Solder the 3- 20 pin connectors to the front of the board. Make sure that they are all oriented so that the cut slot faces down. See image: 



Solder the 16- 8 pin headers for the minibadges. The easiest way to solder these is to clip the headers into a minibadge so that you can use the minibadge to angle them correctly. 

Move to the back:
Solder the battery holder. 
Trim the battery holder wires on the front. 

Optional but highly recommended: 
If you are planning to get a 3d printed back from Lavaman, hold off on this step until you have your back. You may not need to do this step to get good light coverage with the back on the badge. 
This step is to apply hot glue over the LEDs/mask area on the forehead and also hot glue over the LEDs/ mask on the right eye. 
The hot glue helps disperse the LED light so that it shines through the mask area with better coverage. 


Assembly Instructions (Red / Yellow Version):

Start on the back: 
Solder yellow LEDs to D3, D4 and D14
Solder red LEDs to D5, D6, D7, D8, D9, D10, D11, D12 and D13. 

Note: D9 is on the left side of the nose (on back) and the cathode is on the bottom side. I have marked it with a black dot.



Move to the front:
Solder 68 ohm resistors to R1, R3-R14
Solder the 15 ohm resistor to R2
Solder the red through-hole LED to the left eye (from front)
Solder the multi-color flash LED to the right eye (from front)

Solder the 3- 20 pin connectors to the front of the board. Make sure that they are all oriented so that the cut slot faces down. See image: 



Solder the 16- 8 pin headers for the minibadges. The easiest way to solder these is to clip the headers into a minibadge so that you can use the minibadge to angle them correctly. 

Move to the back:
Solder the battery holder. 
Trim the battery holder wires on the front. 

Optional but highly recommended: 
If you are planning to get a 3d printed back from Lavaman, hold off on this step until you have your back. You may not need to do this step to get good light coverage with the back on the badge. 
This step is to apply hot glue over the LEDs/mask area on the forehead and also hot glue over the LEDs/ mask on the right eye. 
The hot glue helps disperse the LED light so that it shines through the mask area with better coverage. 

How to Use:

You can either power the expansion board with a main conference badge or with batteries. If you power the extension board with your main conference badge, the clock pin will work. If you power with batteries, the clock pin will not work. 

To power with the main conference badge or another extension board, connect the top connector (labeled Badge) to your main badge. 

DO NOT CONNECT YOUR MAIN CONFERENCE BADGE TO THE CONNECTOR LABELED BATTERY (LOWER ONE). ONLY CONNECT THE MAIN BADGE TO THE TOP CONNECTOR. IF YOU CONNECT YOUR MAIN BADGE TO THE LOWER ONE WITH BATTERIES YOU MAY DAMAGE BOTH BADGES. 

To power with batteries, connect the connectors labeled Badge and Battery together.



You can add additional expansion boards by connecting them to the connector at the bottom left corner. 







