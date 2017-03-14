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
  * The joypad controller is an Arduino Pro Micro developed by SparkFun Electronics and released under [Creative Commons ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/):
    * [SparkFun Pro Micro GitHub Page](https://github.com/sparkfun/Pro_Micro)
    * [SparkFun Pro Micro 5V/16MHz](https://www.sparkfun.com/products/12640)
    * [SparkFun Pro Micro 3.3V/8MHz](https://www.sparkfun.com/products/12587)
  * Initially, the slouchpad will be a shield for the Pro Micro
* Buttons
  * The buttons on all the pads are the Soft Tactile Buttons distributed by Adafruit:
    * [Soft Tactile Button (8mm)](https://www.adafruit.com/products/3101)
  * These buttons provide the feel of a conductive silicone pad button without the expense and difficulty of producing the silicone parts.
* Joysticks
  * Joysticks are Mini 2-Axis Analog Thumbsticks distributed by Adafruit:
    * [Mini 2-Axis Analog Thumbstick](https://www.adafruit.com/products/2765)

## Software
Arduino code for the controller depends on [Matthew Heironimus's](https://github.com/MHeironimus) [ArduinoJoystickLibrary](https://github.com/MHeironimus/ArduinoJoystickLibrary).  The key binding is intended to be similar to the input bindings of a PlayStation 2 Analog controller.  

## License Information
The hardware is released under [Creative Commons ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).  
