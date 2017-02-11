# RickysWeatherstation
Reads Temperatur and Humidity from AOSONG AM3202 and displays it on a GM009605 Display.

Components: 
- Arduino (I used a MEGA 2560)
- Display: GM009605
- Sensor module: AOSONG 2302

Hardware Setup
===============
Display:
Wire the I2C interface as following

Display    Arduino
SCK        SCL
SDA        SDA
VDD        3.3V
GND        GND

See also:
https://www.instructables.com/id/How-to-use-DHT-22-sensor-Arduino-Tutorial/

Software Setup
===============
Download DHT library (un-rar it) and include it to the Arduino libraries (On my mac: Users/'MyUserName'/Documents/Arduino/libraries)

http://www.electroschematics.com/wp-content/uploads/2015/02/DHT.rar

