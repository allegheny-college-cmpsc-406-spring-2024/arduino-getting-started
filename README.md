# Getting Started with Arduino and MicroPython

## References

- [MicroPython Documentation](https://docs.micropython.org/en/latest/micropython-docs.pdf)
- [Arduino Nano RP2040 Connect DataSheet](https://content.arduino.cc/assets/ABX00053-datasheet.pdf)
- [MicroPython Firmware](https://micropython.org/download/ARDUINO_NANO_RP2040_CONNECT/)
- [Arduino Labs IDE](https://labs.arduino.cc/en/labs/micropython)
- [Getting Started Instructions on Code Motion](https://www.codemotion.com/magazine/backend/getting-started-with-micropython-on-arduino-nano-rp2040-connect/)

## Step One: Install MicroPython Firmware

1. Plug your Arduino Nano 2040 Connect into your laptop with a MicroUSB data cable.
2. Download the latest stable `.uf2` file [at this link](https://micropython.org/download/ARDUINO_NANO_RP2040_CONNECT/).
3. Double-tap the little white reset button on your Arduino. The board will move into bootloader mode and will show up on your computer (with a name like `RPI...`)
4. Drag the `.uf2` from Step 2 onto your device. The device will disconnect and the firmware is now loaded. (Don't worry if you get an ejection error!)

## Step Two: Install an IDE

The Arduino Labs IDE is a good choice. [Find and install it here!](https://labs.arduino.cc/en/labs/micropython)

## Step Three: Start programming your MicroController. 
> [!IMPORTANT]  
> Make sure that you copy and paste any code you want to keep in a separate folder on your computer. Unfortutely IDEs compatible with Arduino don't include great versioning support.

1.  Scroll down to find two code examples [here](https://www.codemotion.com/magazine/backend/getting-started-with-micropython-on-arduino-nano-rp2040-connect/). Try both of them and see what happens when you change some of the code around.
2.  See if you can write a program that changes the blinking LED output based on the accelerometer and/or gyroscope functionality.
3. When you are done, show your professor your progress! 
4. EXTRA CHALLENGE: see if you can make the light blink based on input from the onboard microphone, using the resources listed in the references at the top of this document. 
