# CO2_Logger
FeatherM0 datalogger with SCD-30 NDIR CO2 sensor and 128x32 OLED display

This is Arduino code that I cobbled together to connect the Feather to the sensor and the screen via I2C.  The Feather logs the CO2 and the temperature to
the microSD card every XX seconds.  The display starts by showing the name of the file it's about to write to, then showing the current CO2 and temp.  If you 
click the reset button, it will create a new file to write to.

Materials:
Feather M0 datalogger (get it with stacking headers if you want to avoid soldering): https://www.adafruit.com/product/2796
SCD-30: https://www.adafruit.com/product/4867
Screen: https://www.adafruit.com/product/4440
Cable for screen to sensor: https://www.adafruit.com/product/4210
Cable for sensor to feather:https://www.adafruit.com/product/4209 or https://www.adafruit.com/product/4397
microSD card

