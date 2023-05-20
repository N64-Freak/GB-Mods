[:arrow_left: Back to Table of Contents](/../../)

---

# Gameboy Pocket-Color

![](/Pocket-Color/Images/IMG_0426.jpg) 

## About this board
The Gamboy Pocket-Color is a mod board which basically is a Gameboy color in the shell of a Gameboy Pocket.
I designed this board so it only uses parts that Nintendo used in this time period. It is compatible with the original Gameboy Color Screen or IPS screens.

There no longer is curring and rewiring involved in building a Gameboy Pocket-Color!
The board just fits in a Gameboy Pocket Shell and feels like an officially released model.
To install the screen either an IPS mod with an IPS ready shell or some modification on the shell are required as for any IPS mod.

The BOM is available and is pretty much identical to the BOM for the Gameboy Color.

## The Screen
The pcb is designed so you can keeep using the original gameboy color screen but for the best result an IPS mod is prefered.  
The screen i am personally using is an unbranded Q5 ips mod.  
**Caution:** Do **NOT** use a laminated Q5 ips mod and also don't use a Q5 ips kit with the light up logo.  
The kits with the light up logo don't offer enough Y-position adjustment for the image!

## Additional Features
This board features some quality of life improvements which make the assembly easier and adds additional features

### Additional VIAs
There are added vias that can be used for sodlering the required signals (A, B, start and select) for the IPS mod. 
This way you can hide the wires behind the screen and they will not be visible in a clear shell.

![](/Pocket-Color/Images/IMG_1327.jpg) 

### Navigation wheel
The newer revision of the PCB does include a navigation wheel that can be used to for exmaple control the IPS mod.
Personally i wired it to the brightness and color palette selection to replace the touch buttons.
Just removing the touch buttons ans instead soldering to the provided pads of the navigation wheel should work just fine.
If you want to definitely make sure there are no accidential touch detection you can remove the touch ICs from the IPS mod and directly solder to pin 1 on the pcb.

![](/Pocket-Color/Images/NavWheel_connection.jpg) 

The Navigation wheel works like a switch and has different operations that can be triggered by rotating it up, down and pushing it in.
The Pads are named by the operation that is triggered by the user. When the operation is triggered the pad is connected to the "common" pad.
For the IPS mod the "common" pad has to be connected to the "GND" pad which is right next to it. To connect the pads an 0603 0-Ohm resistor or a piece of wire can be used.

If you want to have brightness change when rotating the navigation-wheel up you have to connect the brightness pad to "UP" on the MGBC board.
In my oppinion it makes sense to connect the color palette change to the down pad to allow changing the color palette when rotating the navwheel down.

**Hint:** For people hunting shiny pokemon you can wire the "PUSH" pad to the testpad "RES" on the MGBC board and reset the gameboy by pushing in the navwheel!

## BOM
The BOM and the mentioned component values and part names are identical to the retail boards and can be used to buy spare parts for your stock gameboy board.

The BOM can be found in the "BOM" folder or following the below link:

[Gameboy Pocket-Color BOM](/Pocket-Color/BOM/BOM_MGBC.xlsx)

## Example of an assembled board
More images can be found in the images folder.

![](/Pocket-Color/Images/Pocket_Color_Boards.jpg) 

![](/Pocket-Color/Images/IMG_0714.jpg) 

---
[:arrow_left: Back to Table of Contents](/../../)
