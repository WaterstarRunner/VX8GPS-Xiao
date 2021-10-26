# VX-8DR GPS - Seeeduino Xiao Edition
### Outline
There's not a whole lot to this project. Just a text parser for generic GPSs to connect to the Yaesu VX-8DR.

### Advantages of this codebase
Using the Sededuino Xiao allows the whole project to be powered from the radio. In the minimalist implementation, only a Yaesu CT-M11 cable, a GPS module (eg Beitian BN-220 works well), a Seeedunino Xiao, and some minor soldering are required.

Additionally, the codebase will accept arbitrary field-lengths and decimal precision in the NMEA input. This means a very wide array of GPS modules (other than the recommended UBlox-chipset ones) will work without modifying the code.

### Documentation

Full documentation is available at the link below, including schematics, related projects, and far more than you ever wanted to know about the Yaesu GPS format.

https://blog.waterstar.run/2021/03/a-simplified-vx-8dr-gps-design.html

### Hardware versions

An extended version of the hardware (with a MOSFET to power/depower the GPS) is currently pending opensource release. It is designed to depower the GPS module during headset jack transmission to prevent noise from the module. In addition the GPS can be soft-switched off when the circuit is used purely as a headset adaptor.

EasyEDA project for the enhanced version is available at the link below:

https://easyeda.com/WaterstarRunner/vx8-gps-audio-module

### Software versions

Basic version:


Extended version:

Pending
