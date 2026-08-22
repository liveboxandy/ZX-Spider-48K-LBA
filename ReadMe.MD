# ZX 48 Spider rework by liveboxandy
## ZX Spectrum 48 clone built on the basis of the ZX Max 48 design.

The board is designed to fit into the standard ZX Spectrum 48k or ZX Spectrum + housing.

## Characteristic:

* ULA based on the CPLD system from the Altera Max7000 family (EPM7128SLC84),
* 48KB RAM,
* AY-3-8910 or AY-3-8912 sound system with stereo output,
* Kempston standard joystick interface,
* RGB video output,
* possibility of using a power supply with any polarity,
* ROM bank switch,
* board fully adapted for through hole mounting


V1.0
* Uses MiniDIN 9 Pin for RGB same as ZX Max 128 & ZX MAx PLusD rather than MinDIN 8.
* Uses same Resistor values for RED/GREEN/BLUE/BRIGHT as ZX Max 128/PlusD/3/2A. 

V1.1
* Joystick can be disabled by removing J18.
* Option to supply +/-12V to edge connector for IF1 Serial support using PS1.

V1.2
* Routed AY3-8910 IOB Bits0-7 to header J18 Pins 1(Bit0)- 8(Bit7).
* Routed AY3-891X IOA Bits0-7 to header J20 Pins 1(Bit0)- 8(Bit7).
* Changed ROM select header to 2 pin rather than 3 pin so added pullup resistor.

V1.3
* Move MiniDIN 9 Pin right by ~2mm so it aligns better with the Video hole in the 14/48K and 48K+
* cases. 

V1.4 
* Correct value of R58 to 470R
* Add jumper J9 to select either 27C256 or 28C256
* Buffer 14Mhz clock more. Use all spare gates
* Label all jumpers

V1.5
* Move position and rotation Q2
* Slight repositioning of J6 (9Pin MiniDIN), R15/16/17/18/73 and J18

V1.6
* Move J6 MiniDIN 9 right by 0.5mm and down by 1mm to better align with 48K+ case.
* Move J11 Ear/Mic right by 0.5mm to better align with 48K+ case.
* Move components below J6 and J5 down to give more space.
* Move Edge Connector left by 0.8mm to centre within 48K+ case cutout.
* Add liveboxandy's Spider 48K V1.6 to silkscreen to try to track different revisions of PCB.

See https://github.com/konkotgit/ZX-48-Spider Rev 1.1 for original information on the ZX Spider, especially if you have issues.
1) with BRIGHT being low or not visible - Might not, see above.
2) Tape loading issues.




