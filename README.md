# Universal Analog Interrupter 1.0
#### Version 2.0 : coming soon (fully analog with MIDI)
#### Version 2.1 : https://github.com/Caraffa-git/Universal-Analog-Interrupter-2.1
#### Version 2.2 : coming soon (fully based on STM32f4)
## :no_entry_sign: PCB is being tested :no_entry_sign:

## Features:
* Burst Mode (BME)
* Independent frequency and duty cycle control for BME and main signal
* Ability to limit duty cycle in BME
* Additional output for weaker tesla coils

## IMPORTANT INFO
~~The kicad design and simulation that I posted here were for my private use only, so~~ they may not be 100% correct and they do not completely look like any open-source project should look. ~~I also put a version of the kicad project that was meant for this, but I didn't finish it (the diagram in this version is much more readable - possible mistakes).~~
I improved the private version which is tested so, everything should look better now.

##### Some pads are not intended for direct soldering to the PCB.

### Specification:
- Standard output (red):
  - pulse length: 4-255 µs
  - frequency:    12-105 Hz
- Longer output (green):
  - pulse length: 2-600 ms
  - frequency:    0.22-4 Hz
- Combined (blue):
  - look above 

### Recommendations and Informations:
* If you want to use BME output directly, BME shouldn't be connected to 555 reset pin because it's lowering the voltage 
* Button near the output is optional
* Fiberoptic connector [footprint](https://www.snapeda.com/parts/IF-E91A/Industrial%20Fiberoptics/view-part/?company=me&t=Fiber+Optic&ref=search#) is for IF-E91A but i wanted to use IF-E96E (I'm not sure about the footprint compatibility yet but according to the datasheets, both transmitters have the same dimensions)

## Schematic:
![schematic](https://raw.githubusercontent.com/Caraffa-git/Universal-Analog-Interrupter-1.0/main/interrupter.jpg)
## Possible outputs:
![possible-outputs](https://raw.githubusercontent.com/Caraffa-git/Universal-Analog-Interrupter-1.0/main/output.png)

[Based on](https://www.stevehv.4hv.org/drsstc_interrupter.htm)
