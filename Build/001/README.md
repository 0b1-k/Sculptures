# Model 001 - Talking Clock

![Model 001 Talking Clock](/Build/001/013.jpg "Model 001 - Talking Clock")


**'Model 001'** is a free-formed 'Talking Clock' with a strong 'Star Wars' audio theme. It also acts as a complete MP3 player.

The clock was designed as a gift to my son and reacts to a set of dates and times specific to him. An hourly chime function announces the current time using my voice and personalized messages to him.

The clock is interactive, providing a text-based interface and menus, accessible over a serial Bluetooth interface. To keep the interface secure, the clock uses a one-time password login scheme, using its OLED display to present the required login code needed from the user.

The menus hide many personal 'Easter Eggs', waiting to be discovered. It reacts to good and bad input with 'Star Wars' sound effects.


The clock's main structure is built using 2mm copper welding rods, 0.8mm brass rods and 20 AWG bare copper wire were used for wiring components. The clock's electronics are commonly found electronic components, such as a Raspberry Pi Pico RP2040, a DS3231 RTC, a HC-06 serial Bluetooth module, a DFPlayer Mini MP3 player chip, a small HW-404 amplifier and a 128x64 SSD1306 blue OLED display. Two 4 Ohm / 3 Watt speakers are connected to the HW-404 amplifier and provide a crisp audio ouput.

The square wooden base of the clock provides illumination, thanks to an RGB LED as well as power for the clock itself.

The firmware for this clock was written in Go / TinyGo, along with a pure Go driver for the DFPlayer Mini MP3 chip.

## Build diary

![first attempt at a cube](/Build/001/000.jpg "First attempt at building a simple cube")

![first attempt at a cube](/Build/001/001.jpg "First attempt at building a simple cube")

![first attempt at a cube](/Build/001/002.jpg "The test cube on the base providing power and illumination")

![Building the clock's structure with weighted companion cubes ;)](/Build/001/003.jpg "Using patent cube paper weights as ad-hoc tools to keep things in place while building")

![The final structure](/Build/001/004.jpg "The final clock's structure")

![The clock's guts on a breadboard](/Build/001/005.jpg "Writing and testing the firmware on a breadboard before building the free-formed circuit")


![The clock's guts on a protoboard](/Build/001/007.jpg "Placing the main components on their base protoboard")

![Wiring with brass rods](/Build/001/006.jpg "Starting the wiring process with brass rods")

![Tapping into the base's power](/Build/001/008.jpg "Adding the clock's power leads to the illumination base")


![Loading firmware](/Build/001/010.jpg "Loading the firmware and first boot")

![Top side](/Build/001/011.jpg "Top side")


![Left side](/Build/001/012.jpg "Left side")

![Right side](/Build/001/013.jpg "Right side")
