## Adafruit Slider Trinkey PCB

<a href="http://www.adafruit.com/products/5021"><img src="assets/5021.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Slider Trinkey. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5021

### Description

It's half USB Key, half Adafruit Trinket, half mini slide pot... it's Slider Trinkey, the circuit board with a Trinket M0 heart, NeoPixel glow, and a 35mm long 10KΩ slide potentiometer.

The PCB is designed to slip into any USB A port on a computer or laptop. There's an ATSAMD21 microcontroller on board with just enough circuitry to keep it happy. One pin of the microcontroller connects to the middle of the slide potentiometer as an analog input. Another connects to two NeoPixel LEDs. The third pin can be used as a capacitive touch input. A reset button lets you enter bootloader mode if necessary. That's it!

The SAMD21 can run CircuitPython or Arduino very nicely - with existing NeoPixel and our FreeTouch libraries for the capacitive touch input. Over the USB connection, you can have serial, MIDI, or HID connectivity. The Slider Trinkey is perfect for simple projects that can use a few user inputs and colorful output. Maybe you'll set it up as a monitor brightness adjuster, or volume control, or color picker.

Please note this board DOES come with a pre-soldered slide pot (there's really only one that fits and we happen to stock it) Since we use a PCB with a USB A shape, its possible to accidentally yank the board out if you push the potentiometer all way, way out and then keep pushing out. So be kind and careful with your Slider Trinkey! It isn't meant for yanking.

We think it's just an adorable little board, small and durable and inexpensive enough that it could be a first microcontroller board, or inspiration for advanced developers to make something simple and fun.

* ATSAMD21E18 32-bit Cortex M0+ - 48 MHz 32 bit processor with 256KB Flash and 32 KB RAM
* Native USB supported by every OS - can be used in Arduino or CircuitPython as USB serial console, MIDI, Keyboard/Mouse HID, even a little disk drive for storing Python scripts.
* Can be used with Arduino IDE or CircuitPython
* Two reverse-mount RGB NeoPixel LEDs
* One Capacitive Touchpad
* One 35mm slide potentiometer with nubbin
* Reset switch for starting your project code over or entering bootloader mode
* Cute & keychain-friendly!

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
