# MR-Adapter-X
MicroRally automative wiring harness helper boards.
Includes different adapters and converters. All made for soldering directly in-line of your harness branch. Made with slort for wire strain relief. Optionaly can be fitted with 2.0mm pitch connectors, like Molex MicroLatch series.

##List of adapters

Adapter 1:
2 channel pull-up/down or voltage divider or filter board.

Adapter 2:
Ecumaster EMU MUX switch resistor board. For connecting 3 low side switches to single analog input.

Adapter 3:
Variable relucatnce (VR) to sqare wave (Hall like) signal converter board. 5V supply only.

Adapter 4:
Variable relucatnce (VR) to sqare wave (Hall like) signal converter board. With 12V supply.

Adapter 5:
2 channel diode OR-ing board.

Adapter 6:
PWM duty cycle to analog voltage (0-5V) converter board.

## File structure
In each foder you will find files for understaning schematics and manufactuirng PCB.

All files ar formated in this fassion:
-AAA_rN_BBB
-AAA - project name
-N - board revision number
-BBB - document content

###Standart documents

-Schematits - PDF of schematics.
-PCB - PDF of PCB and assembly drawings. (Assembly - location of components)
-MODEL - 3D step model of board.
-BOM - Bill of Materials. List of all components on PCB. NL means Not Load - do not solder, not neccesery.
-GERBERS - Files that you send to PCB manufacturer.
-PNP - Pick and Place files for automated assembly.
-PANEL_PCB - PDF of panel drawing. Panel is for cheaper mass production.
-PANEL_GERGERS - Files that you send to PCB manufacturer, to produce bunch of boards as a single board with V-CUTs.
