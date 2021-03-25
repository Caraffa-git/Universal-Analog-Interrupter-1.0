# Universal Analog Interrupter 1.0
## Features:
* Independent frequency and duty cycle control for BME and main signal
* Ability to limit duty cycle in BME
* Additional output for weaker tesla coils

## IMPORTANT INFO
The kicad design and simulation that I posted here were for my private use only, so they may not be 100% correct and they do not look like any open-source project should look. I also put a version of the kicad project that was meant for this, but I didn't finish it (the diagram in this version is much more readable - possible mistakes).
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

## Schematic:
![schematic](https://raw.githubusercontent.com/Caraffa-git/Universal-Analog-Interrupter/main/interrupter.jpg?token=AQ5JNBV2XGWVYSPHOGANWC3ALRMNK)
## Possible outputs:
![possible-outputs](https://raw.githubusercontent.com/Caraffa-git/Universal-Analog-Interrupter/main/output.png?token=AQ5JNBTVJI2KCRVSOW2Z67DALRLIW)

[Based on](https://www.stevehv.4hv.org/drsstc_interrupter.htm)

