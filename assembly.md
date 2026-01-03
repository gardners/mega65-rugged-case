## Lower Half

0. Laser cut each of the panels.
1. Solder ~50cm leads onto two momentary action switches for the POWER and BOOT buttons (I used https://www.jaycar.com.au/dpdt-quality-pushbutton/p/SP0714).
   Put female dupont (0.1" female header) connectors on the ends of these leads.  They should be short-circuit when the buttons are pressed and
   open circuit when not pressed.
2. Assemble the keyboard panel (lower-laser-cut.svg) and fit either a MEGA65 retail keyboard or a MEGA65 DIY keyboard and the two push-buttons from the previous step.
3. Assemble the floppy drive panel (lower-deck-2-laser-cut.svg), fitting a standard PC 1.44MB floppy drive.
   Yoo should also add floppy data cable and floppy power cable at this point, as feeding them through later may be difficult.
   If you don't have a floppy drive, you will need a spacer of the same height.
4. Use M3x6mm screws to connect the two together where the holes line up with threaded hexes from the other panel.
5. Solder a header onto J2 of a https://github.com/svenpetersen1965/C64---Cart64out board. You don't need any other parts on it.
6. Solder ~30cm leads onto one or two speakers. I'm lazy and just used more female dupont connectors.
   But you can use the correct JLC connectors for J19 and J22 on a MEGA65 R3 board.
7. Fit the MEGA65 main board to the panel, by inserting the M3x15 screws from the rear, fitting the HEX6.3s and then lowering the mainboard onto the produding screws.
   Use nylon NUT+WASHERs to fix the board in place.
8. Use M3x15 screws and HEX6.3s to screw the speakers into the panel, and then connect to J19 and/or J22 as desired.
9. Fit the TE0790 JTAG adapter now (if you did it before, it would have blocked access to a screw).
10. Fit the retaining M3x25 for the expansion breakout board from the rear, then put a HEX6.3 + NUT+WASHER to hold that in place and vertically space the support for the expansion board. 
