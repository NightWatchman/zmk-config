# About
This config for a lily58 KB outputs separate files for the left and right halves. The left is the master half, and the right is the slave. The right half will not work without the left.


# Power notes
The right-half of the keyboard will not work without power. It can be plugged into USB, powered by a cell, or powered via TRRS cable.
If using a TRRS cable, the ZMK "external power" *must* be turned on before the right-half will work. An `EP_ON` binding has been included
in the left (master) half for this purpose.
