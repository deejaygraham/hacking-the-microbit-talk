## Notes

Mu Editor

http://codewith.mu

MicroPython and Microbit documentation
Examples and API documentation

https://microbit-micropython.readthedocs.io/en/latest/


* Micro:bit:developer community - http://tech.microbit.org/


mbed online IDE and compiler
https://developer.mbed.org/platforms/Microbit/


Microbit DAL
https://github.com/lancaster-university/microbit-dal


Microbit runtime docs
https://lancaster-university.github.io/microbit-docs/

* Lancaster University Github - https://github.com/lancaster-university/


* Eddystone protocol spec - https://github.com/google/eddystone

Building offline code

http://docs.yottabuild.org/#installing

https://lancaster-university.github.io/microbit-docs/offline-toolchains/
https://github.com/lancaster-university/microbit-samples/tree/master/source/examples/bluetooth-eddystone-url

https://github.com/showio/microbit-physicalweb


Mac OS

https://github.com/dermike/slide-beacon-app
https://github.com/dermike/slide-beacon-app/releases/download/0.4.1/SlideBeacon.zip

https://github.com/dermike/physical-web-scan-app
https://github.com/dermike/physical-web-scan-app/releases/download/0.3.0/PhysicalWebScan.zip

https://itunes.apple.com/gb/app/lightblue/id639944780?mt=12

To determine your Mac's Bluetooth version

    Click the  menu. Select About This Mac. Click on the More Info... button. Click on the System Report... button. Select Bluetooth from the sidebar on the left, underneath "Hardware." Scan down the list of information until you find "LMP Version."

If your Mac is equipped with Bluetooth 4.0, LMP Version will say 0x6. Anything lower than that is an older version of Bluetooth.

Does your Mac come with Bluetooth 4.0, or are you going to need a new system to take full advantage of Yosemite and iOS 8 when they're released this fall? Post your thoughts in the comments.

http://rexstjohn.com/bluetooth-smart-ble-scanning-on-osx-xcode-6/

https://github.com/adafruit/adafruit-bluefruit-le-desktop



## Notes

Can be programmed with high-level online IDEs using the BBC's website at http://www.microbit.co.uk/create-code including:
Microsoft TouchDevelop IDE
Microsoft Blocks
CodeKingdoms Javascript
MicroPython
mbed enabled
Online IDE at developer.mbed.org
Easy to use C/C++ SDK
Dedicated micro:bit runtime libraries for rapid development (developed by Lancaster University)
Nordic nRF51822 Multi-protocol Bluetooth® 4.0 low energy/2.4GHz RF SoC
32-bit ARM Cortex M0 processor (16MHz)
16kB RAM
256kB Flash
Bluetooth Low Energy Master/Slave capable
Input/Output
25 LED Matrix
Freescale MMA8652 3-axis Accelerometer
Freescale MAG3110 3-axis Magnetometer (e-compass)
Push Button x2
USB and Edge connector Serial I/O
2/3 reconfigurable PWM outputs
5 x Banana/Croc-clip connectors
Edge connector
6 x Analog In
6-17 GPIO (configuration dependent)
SPI
i2c
USB Micro B connector
JST power connector (3v)



eddystone



Append firmware with new python program and download whole thing.


[mbed compiler](https://developer.mbed.org/platforms/Microbit/)


using google url shortener: https://goo.gl/

https://deejaygraham.github.io
becomes
https://goo.gl/RjUKnV

create eddystone url

https://www.mkompf.com/tech/eddystoneurl.html

0x03,  // Length of Service List
  0x03,  // Param: Service List
  0xAA, 0xFE,  // Eddystone ID
  0x13,  // Length of Service Data
  0x16,  // Service Data
  0xAA, 0xFE, // Eddystone ID
  0x10,  // Frame type: URL
  0xF8, // Power
  0x03, // https://
  'g',
  'o',
  'o',
  '.',
  'g',
  'l',
  '/',
  'R',
  'j',
  'U',
  'K',
  'n',
  'V',
