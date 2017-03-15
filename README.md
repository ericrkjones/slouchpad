# slouchpad
A simple joypad for easy assembly in different types of enclosures.  

The joypad is broken into four main components:  
* Left pad, containing one joystick, d-pad, the select button, the menu buttor
* Right pad, containing one joystick, six primary buttons, and the start button
* Two shoulder pads, each containing two buttons.  

Signal List:
* 5 analog signals
* 13 digital signals
* VCC
* GND

## Hardware
Hardware designs are located in the "slouchpad_pcb" directory.
### Components
* Buttons
  * The buttons on all the pads are the Soft Tactile Buttons distributed by Adafruit Industries:
    * [Soft Tactile Button (8mm)](https://www.adafruit.com/products/3101)
  * These buttons provide the feel of a conductive silicone pad button without the expense and difficulty of producing the silicone parts.
* Joysticks
  * Joysticks are Mini 2-Axis Analog Thumbsticks distributed by Adafruit Industries:
    * [Mini 2-Axis Analog Thumbstick](https://www.adafruit.com/products/2765)
  * These joysticks have a feel that is very similar to a PSP joystick, but are available in a through-hole package.  

## License Information
The slouchpad hardware is released under [Creative Commons ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).  

The Mini Analog Thumbstick part layout was obtained from the [Adafruit-Mini-Analog-Thumbstick-Breakout-PCB](https://github.com/adafruit/Adafruit-Mini-Analog-Thumbstick-Breakout-PCB), designed by Ladyada for Adafruit Industries and released under the [Creative Commons Attribution-ShareAlike license](https://creativecommons.org/licenses/by-sa/3.0/).  Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from Adafruit!
