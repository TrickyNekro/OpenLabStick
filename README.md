# OpenLabStick
by El. Provatos

During the pandemic a lot of us had to leave spaces like schools, offices, laboratories behind and of course 
<b>all the nice equipment that is available in those!!!</b> That´s exactly what this projects aim to alleviate!

This is not going to replace your +5k$ Scope or ten times as much Spectrum Analyzer or even your lab power supply!
But it can enable people who are now only beginning to develop code, learn electronics and / or robotics,
to have access to a system that can give them:

  - An up to 20V I²C programmable power supply.
  - 4 High power outputs for controlling any kind of motor or other kind of device
  - 8 GPIO of the microcontroller directly accessible as well as all the standard.
    communication protocols that come with it ( I²C, USART, SPI ).
  - 16 General Purpose I / O through an I / O expander.
  - On-Board EEPROM, Super-Cap backed RTC, Temperature Sensor.
  - A Joystick for basic inputs connected through a single Analog channel.
  - Native USB connection with PD Protocol Support through I²C controlled IC.
  - Being able to power it either from USB or as low as a single LiPo Cell!
  - Being also able to force select the power input of your motors and or board as a whole!
  - Possible feature: And accelerometer / gyroscope sensor, if it fits without too much drama.
  
And all that is package in a rather long but breadboard friendly PCB ( 600mil wide, as wide as a 40pin DIP! ).

The core of the project is based on an ATmega32U4. Some would say this is perhaps underpowered for such a board,
others maybe do not mind. The case is that this microcontroller is used in Arduino Nano projects so there is a
big community which can assist people now beginning with electronics and programming!
  
This repository will contain, the board schematics on EAGLE Cad, the libraries to use the On-Board ICs and
probably a couple of examples that might be interesting.
