SMPS LED Driver
---------------

This project provides a small LED driver circuit using a common switch mode
IC MC34063 in a constant current configuration. The circuit is designed to
deliver up to 1.5A, the maximum current of the MC34063. An opamp is provided to
amplify the current sense voltage to the required 1.25V of the MC34063.

An extra resistor is provided to allow adaptation of the circuit as a buck
converter. This must be omitted for the constant current application. Two
resistors must be shorted and the opamp omitted for the buck converter
application. See notes on the schematic diagram.

More information is provided at [Jiggerjuice](http://www.jiggerjuice.info/electronics/projects/power/LED-drivers.html).

(c) K. Sarkies 07/02/2018

