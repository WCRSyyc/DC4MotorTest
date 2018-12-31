# DC4MotorTest

This sketch provides a simple check of which motor numbers are being used, and which direction is forward and back, for (up to) 4 DC motors connected to an Adafruit motor shield. It was written as a utility to use during the construction of a WCRS [carbot](https://github.com/WCRSyyc/carbot).

The code sequences (repeatedly) through the 4 possible motors, ramping the motor from zero to maximum and back to zero speed forward, then the same again backwards.  Which motor number is being exercised, and direction changes are reported over the serial line (Serial Monitor).