# Three-Phase-AC-Sequence-Detector
Schematics and Arduino code for Three Phase AC Sequence Detector

Let’s start with the basics of 3 – Phase voltage.

In 1-Phase voltage you have to take care about only one phase. So during measurement you don’t have to worry about voltage angle. But in 3-phase system you have to take care of all three phases and their present angle as well. Angle of voltage is very important factor in 3-phase systems, it tells that which phase are we dealing with. At a identical time all three phases have different angles.

2 phases are 120 degrees apart to each other and 3rd phase is 240 degree apart to first phase. You can take these phase angles as -120,0,120 degrees as well.  It depends on the reference phase you take. So during measurement of 3 phase voltage, we have to measure these angles as well. "Reference Phase A to Phase B then Reference Phase A to Phase C.

To measure the angle I used the zero detection technique which is implemented through 3 Opto-coplers

Take a look on "fig1.jpg". Three white circles are basically neutral or zero points of three phases. We just have to measure the t1 and t2 which are time differences of three phases.  If we get these t1 and t2 then we can easily get the phase angles as well. Understand the coding attached and you will understand the whole scenario here.
