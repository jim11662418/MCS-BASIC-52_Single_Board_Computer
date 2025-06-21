# MCS-BASIC-52 Single Board Computer
Single Board Computer with Intel's MCS-BASIC-52. Although schematic shows an Analog Devices/Maxim DS803C323 MCU, the SBC has been tested using an Intel 8052 and an Atmel AT89S52 so any MCU that is pin compatible with the 8052 should work. Just as an aside, the DS803C323 runs the 'clock.basic' program in 27.75 seconds. The 8052 and AT89S52 each require 56.69 seconds to run the same program.

Due to the changes I've made to the firmware, alas, the object code no longer fits into an 8K EPROM; hence the use of a 27256 EPROM. Assemble the source with the [Macro Assembler AS](http://john.ccac.rwth-aachen.de:8000/as/)
<p align="center"><img src="/images/MCS-BASIC-52.JPG"/>
<p align="center">MCS-BASIC-52 SBC</p><br>
<p align="center"><img src="/images/MCS-BASIC-52 SBC.png"/>
<p align="center">MCS-BASIC-52 SBC</p><br>
<p align="center"><img src="/images/MCS-BASIC-52.png"/>
<p align="center">MCS-BASIC-52</p><br>

