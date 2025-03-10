# Acorn BBC Micro 177x Disc Interface module
This module can be used in place of a 8271 disc controller in the BBC micro computer.

Some general notes:

* The source files are to be used with KiCAD v9.0.0 or later.
* The gerber files have been optimised for fabrication by JLCPCB. In particular, there is a 8mmx8mm silkscreen box on the rear of the PCB. This is to allow a 2D barcode, with unique serial number to be printed on the PCB.
* If you want the barcode to be added, then make sure to select this option in the 'Mark on PCB' field, and make sure to select 'Specify position' in the '2D Barcode Position' field, otherwise you will end up with a white 8mm x 8mm box printed on your PCB and a 8mm x 8mm barcode printed at a psotion of JLCPCBs choosing. Thrust me on this!
* If you don't want the barcode added, then remove the 8mm x 8mm box from the silkscreen layer and regenerate the gerbers. Otherwise you will end up with a white 8mm x 8mm box printed on your PCB.
* A combined CPL / BOM file is included in the gerber directory. Again, this is for use with JLCPCB, if you want to use their PCBA (PCB Assembly) to solder on all the SMD parts.
* You will need to source a suitable 1770 / 1772 disc controller IC to install on the board. These are becoming increasingly difficult to find at a reasonable price.
* Additional modifications (including the installation of additional ICs) may be required to the beeb motherboard. These modifications are detailed in the attached Acorn_1770DiscIFUpgradeKit.pdf document 

Please refer to the following discussion on Stardot for further details: [https://stardot.org.uk/forums/viewtopic.php?f=3&t=18815](https://stardot.org.uk/forums/viewtopic.php?t=30150)

## Author

The Disc Interface module is developed and maintained by Ken Lowe.
    
## Hardware License (Creative Commons BY-SA 4.0)

Please see the following link for details: https://creativecommons.org/licenses/by-sa/4.0/

You are free to:

Share - copy and redistribute the material in any medium or format
Adapt - remix, transform, and build upon the material
for any purpose, even commercially.

This license is acceptable for Free Cultural Works.

The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms:

Attribution - You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

ShareAlike - If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

No additional restrictions - You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.
