[:arrow_left: Back to Table of Contents](/README.md)

# 40pin Board with some mods but without silkscreen
## Board features
This board is based on the AGB-CPU-02 revision and does not have the full silkscreen.
The silkscreen does only have some design elements printed but is missing all the component designators.
There are some mods added to the board but it can still be used as a direct replacement for a retail board.
As it has some mods already done to it some test points moved and it will not be compatible with all available mods anymore.

## BOM
As this board does not have any component designators there will not be a BOM available.
For anyone who wants to torture himself the board is *close* to the 40pin board with the silkscreen so you can order the parts and look for the component designators on the 40pin board with silkscreen

->Recommended is to move over all the parts one by one from a suitable donor console and add the extra parts after this.

## Added mods
The board does have a few mods added. Mainly this is the tactile buttons and the tantalum caps.

The tactile buttons add a clicky feeling to the buttons there's just the problem that you still have the long button travel and the squishy feeling of the membrane.
but there's a solution for it. XXX designed a 3D printable adapter that can be attached to the dpad and A/B buttons to omit the membrane and have a similar feeling to the tactile buttons of the GBA SP.

The tantalum caps are pretty self explanatory. The old electrolytic capacitors have simply been replaced by tantalum caps for better performance.

As the CPU power cleaner mod is a quite popular mod i also integrated that directly into the board so each supply pin of the CPU has some extra capacitors close to it.
- Note: Some of the pads were only planned for testing. If you populate these components some modifiction to the shell would be necessary!

Last but not least to help with the power distribution on the board i went for a 4 layer board so i had 2 extra layers for power and GND supply. This allowed for far wider traces which reduces the voltage drop on the traces and helps in combination with the power cleaner mod. 

The BOM for the added mod components is:

| No. | Description | Manufacturer Partnumber | Mouser partnumber |  
| --- | --- | --- | --- |  
| 1 | Tactile button (small) | SKRMAAE010 |  688-SKRMAA |  
| 2 | Tactile button (big) | SKRRAAE010 |  688-SKRRAA |  
| 3 |  |   |  |  
| 4 |  |   |  |  
| 5 |  |   |  |  
| 6 |  |   |  |  
| ... | ... | ... | ... |  

Will be extended once the parts are verified!

## Example of an assembled board
More images can be found in the images folder.

![](/Advance/40pin_without_silkscreen_tactile/Images/20220820_142645.jpg) 

## Additional information
One of the footprints is missing 2 pads. These 2 pads aren't used on the Layout and are not connected on the original Layout.
On most gameboys the part that is installed does not have this 2 extra pins but some consoles use a different part that has the 2 extra legs.
In case your donor has the component with the extra 2 legs it would have 2 pins floating like this. This is only an optical imperfection and will be fixed with the next board revision!

As i currently have no assembled board of this version i had to borrow the image from the 32pin board. Except for the silkscreen the layout in this part of the board is the same.

![](/Advance/32pin_with_silkscreen/Images/IMG_9725.jpg)

[:arrow_left: Back to Table of Contents](/README.md)
