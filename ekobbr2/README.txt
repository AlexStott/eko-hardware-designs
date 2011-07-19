Energy Kiosk Observer - Revision 1 AC sensor board 230V/5A
==========================================================

Design: Charith Amarasinghe

Designs
-------
Baseboard.brd/baseboard.sch - Revision 3 of the generic EKO sensor board

Features
********
PIC24F16KA102 in SOIC packaging
Integrated 32.768kHz crystal oscillator
3x Diagnostic LEDs (Power,TX,RX)
RX/TX can be disconnected from SP483E driver
Transient Voltage Suppressors on All Bus Lines
Interrupt Line


Changes from R2
***************
Included chip 7407D, 6x buffer instead of single buffer
Included Interrupt line connected to Pic AN2
Removed 2x debug LEDs
Removed end of sensor cable jumpers + resistors

Changes from R1
***************
All SMT components
PCB Stacking vs. Wire Connectors



Libraries
---------

eko-parts.lbr   - main eko-parts eagle library
