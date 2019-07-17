## Adafruit METRO M0 Express - designed for CircuitPython - ATSAMD21G18 PCB

<a href="http://www.adafruit.com/products/3505"><img src="assets/3505.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit METRO M0 Express - designed for CircuitPython - ATSAMD21G18. Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/3505

### Description

Metro is our series of microcontroller boards for use with the Arduino IDE. This new **Metro M0 Express** board looks a whole lot like our [original Metro 328](https://www.adafruit.com/product/2488), but with a huge upgrade. Instead of the ATmega328, this Metro features a ATSAMD21G18 chip, an ARM Cortex M0+. It's our first Metro that is designed for use with CircuitPython! CircuitPython is our beginner-oriented flavor of MicroPython - and as the name hints at, its a small but full-featured version of the popular Python programming language specifically for use with circuitry and electronics.

Not only can you use CircuitPython, but the Metro M0 is also usable in the Arduino IDE.

At the Metro M0's heart is an ATSAMD21G18 ARM Cortex M0 processor, clocked at 48 MHz and at 3.3V logic, the same one used in the new [Arduino Zero](https://www.adafruit.com/products/2843). This chip has a whopping 256K of FLASH (8x more than the Atmega328) and 32K of RAM (16x as much)! This chip comes with built in USB so it has USB-to-Serial program & debug capability built in with no need for an FTDI-like chip.

 * **Power the METRO** with 7-9V polarity protected DC or the micro USB connector to any 5V USB source. The 2.1mm DC jack has an on/off switch next to it so you can turn off your setup easily. The METRO will automagically switch between USB and DC.
 * **METRO has 25 GPIO pins**, 12 of which are analog in, and one of which is a true analog out. There's a hardware SPI port, hardware I2C port and hardware UART. Logic level is 3.3V
 * **Native USB**, there's no need for a hardware USB to Serial converter as the Metro M0 has built in USB support. When used to act like a serial device, the USB interface can be used by any computer to listen/send data to the METRO, and can also be used to launch and update code via the bootloader. It can also act like a keyboard, mouse or MIDI device as well.
 * **Four indicator LEDs and one NeoPixel**, on the front edge of the PCB, for easy debugging. One green power LED, two RX/TX LEDs for data being sent over USB, and a red LED connected. Next to the reset button there is an RGB NeoPixel that can be used for any purpose.
 * **2 MB SPI Flash** storage chip is included on board. You can use the SPI Flash storage like a very tiny hard drive. When used in Circuit Python, the 2 MB flash acts as storage for all your scripts, libraries and files. When used in Arduino, you can read/write files to it, like a little datalogger or SD card, and then with our helper program, access the files over USB.
 * **Easy reprogramming**, comes pre-loaded with the [UF2 bootloader](https://learn.adafruit.com/adafruit-metro-m0-express-designed-for-circuitpython/uf2-bootloader), which looks like a USB storage key. Simply drag firmware on to program, no special tools or drivers needed! It can be used to load up CircuitPython, PXT/MakeCode or Arduino IDE (it is bossa-compatible)
Comes fully assembled with headers, tested, and with the UF2 bootloader loaded on. We also include 4 rubber bumpers to keep it from slipping off your desk. No soldering required to use, plug and play!

Good news, CircuitPython now comes preloaded!

[Check out our full guide for pinouts, schematics, drivers, instructions, Fritzing object, and more!](https://learn.adafruit.com/adafruit-metro-m0-express-designed-for-circuitpython)

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
