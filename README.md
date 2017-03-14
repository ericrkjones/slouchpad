# slouchpad
A simple Arduino joypad for easy assembly in different types of enclosures.  

The joypad is broken into four main components:  
* Left pad, containing one joystick, d-pad, the select button, the menu button, and the controller
* Right pad, containing one joystick, six primary buttons, and the start button
* Two shoulder pads, each containing two buttons.  

## Hardware
Hardware designs are located in the "slouchpad_pcb" directory.
### Components
* Controller
  * The joypad controller is an Arduino Pro Micro developed by SparkFun Electronics:
    * [SparkFun Pro Micro GitHub Page](https://github.com/sparkfun/Pro_Micro)
    * [SparkFun Pro Micro 5V/16MHz](https://www.sparkfun.com/products/12640)
    * [SparkFun Pro Micro 3.3V/8MHz](https://www.sparkfun.com/products/12587)
  * Initially, the slouchpad will be a shield for the Pro Micro
* Buttons
  * The buttons on all the pads are the Soft Tactile Buttons distributed by Adafruit Industries:
    * [Soft Tactile Button (8mm)](https://www.adafruit.com/products/3101)
  * These buttons provide the feel of a conductive silicone pad button without the expense and difficulty of producing the silicone parts.
* Joysticks
  * Joysticks are Mini 2-Axis Analog Thumbsticks distributed by Adafruit Industries:
    * [Mini 2-Axis Analog Thumbstick](https://www.adafruit.com/products/2765)
  * These joysticks have a feel that is very similar to a PSP joystick, but are available in a through-hole package.  

## Software
Arduino code for the controller depends on [Matthew Heironimus's](https://github.com/MHeironimus) [ArduinoJoystickLibrary](https://github.com/MHeironimus/ArduinoJoystickLibrary).  The key binding is intended to be similar to the input bindings of a PlayStation 2 Analog controller.  

## License Information
The slouchpad hardware is released under [Creative Commons ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).  

The SparkFun Pro Micro design was released under [Creative Commons ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).  

The Mini Analog Thumbstick part layout was obtained from the [Adafruit-Mini-Analog-Thumbstick-Breakout-PCB](https://github.com/adafruit/Adafruit-Mini-Analog-Thumbstick-Breakout-PCB), designed by Ladyada for Adafruit Industries and released under the [Creative Commons Attribution-ShareAlike license](https://creativecommons.org/licenses/by-sa/3.0/).  Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from Adafruit!
