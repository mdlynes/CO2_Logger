# CO2_Logger
FeatherM0 datalogger with SCD-30 NDIR CO2 sensor and 128x32 OLED display

This is Arduino code that I cobbled together to connect the Feather to the sensor and the screen via I2C.  The Feather logs the CO2 and the temperature to
the microSD card every XX seconds.  The display starts by showing the name of the file it's about to write to, then showing the current CO2 and temp.  If you 
click the reset button, it will create a new file to write to.
