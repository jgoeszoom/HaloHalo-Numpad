# Halo-Halo Numpad!
A custom PCB implementation of a numpad that I designed for my girlfriend. 
(The name comes from a popular Filipino dessert; we thought it would be a fun name)

## Specifications
This numpad includes a 5x4 matrix of MX-style key switches along with a column of 
rotary encoders with a push-on switch built-in. 

At the moment, the board is still a WIP. The final board will include headers to attach a microcontroller that
will be chosen later. There should also be space for a small OLED/LCD screen. 

### To-do: 
	- [] Choose a microcontroller to use
	- [] Add headers for microcontroller chosen 
	- [] Add space on PCB for the small screen

## Schematic

![Schematic of Numpad](/imgs/Numpad_Sch.png)

## PCB

![PCB of Numpad](/imgs/Numpad_Brd.png)

## Render

![Render of PCB](/imgs/HaloHalo_Numpadv2.png)

## Bill-of-Materials

| References | Value | Footprint | Quantity |
| ---------- | ----- | --------- | -------- |
| C1-C20     | 0.1uF | 0805      | 20       |
| R1-R7, R9  | 4.7k  | Axial DIN0204 | 8    |
| R8         | 470   | Axial DIN0204 | 1    |
| D1-D20     | N/A   | SK6812 Mini | 20     | 
| D21-D40    | N/A   | SOD-123F  | 20       |
| SW1-SW20   | N/A   | Cherry MX | 20       |
| SW21-SW23  | Rotary| Alps EC11E| 3        |

C - Capacitors
R - Resistors
D - Diodes
SW - Switches

[Interactive BOM](/bom/bom.html)
