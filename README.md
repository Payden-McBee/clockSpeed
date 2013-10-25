clockSpeed
==========

this sets the clock speed of the MSP430 

There are four possible clock speeds of the MSP430, 16MHz, 12MHz, 8Mhz, 1MHz. 
This code provides four functions to choose from to set the clock speed to one of those frequencies. 
This allows the program on the MSP430 to run on a different frequency than the computer running it,
which is pretty awesome!

The functions are

void RunAt1Hz();
void RunAt8Hz();
void RunAt12Hz();
void RunAt16Hz();

Enjoy!
