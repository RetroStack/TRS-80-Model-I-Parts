# TRS-80 Model 1 - Keyboard Shield (for ALPS Keyboard)

The keyboard shield has a few functions:
- Protects the keyboard PCB and mainboard PCB from extenal factors.
- Keeps the keycaps at a specified place and distance to the case.
- Separates the keyboard PCB from the main PCB

![View 1](Images/Keyboard_Shield_1.png)
![View 2](Images/Keyboard_Shield_2.png)

There are a few versions for this part:

## STEP

This is a sheet metal version of the keyboard shield replica. You can use the STEP file to submit it to online sheet metal fabs like SendCutSend, Fabworks, or PCBWay.

[STEP](Keyboard_Shield_ALPS_v1.step)

## STL

[STL](Keyboard_Stem_ALPS.stl)

## 3D Printer-Friendly STL

Here is also a 3D printer friendly version.

![View 1](Images/Keyboard_Shield_Printable_1.png)
![View 2](Images/Keyboard_Shield_Printable_2.png)

The original STL is broken down into two STLs to simplify printing on smaller printers (min. 165x136.1x18.3mm). Only the keyboard (central) STL is important as these are the only 4 points where the keyboard is stabilized from.

[Keyboard STL](Keyboard_Shield_Printable_Main.stl)
[Number Pad STL](Keyboard_Shield_Printable_Num.stl) (Optional)

### Print Instructions

- Print both items vertically.
  - The number pad should stand on the flat side. This flat side is a bit longer than the other one as it will add required distace to the keyboard PCB. This is not on the original part, but because of splitting the STL, there is no spacer available and there is another way required to add spacing to the PCB to keep it upright when assembled.
  - The main part of the keyboard should stand flat on either side of the board. Parts of it is cut-off because it would require a pretty wide printer. However, this shield will add regidity to the central part of the keyboard - the most used parts. The sides will already be largerly supported by the PCB itself and the spacers below the keyboard PCB.
- Add support for for the keycap holes. This support will need to be removed afterward to fit the buttons in.

![Print](Images/Print.png)

## Use Cases

![Top](Images/DSC00079_Small.JPG)
![Bottom](Images/DSC00080_Small.JPG)

### Assembled

![Top](Images/DSC00110_Small.JPG)
![Bottom](Images/DSC00107_Small.JPG)
