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
* Uses same Resistor values for RED/GREEN/BLUE/BRIGHT as ZX Max 128/PlusD/3/2A

V1.1
* Joystick can be disabled by removing J18
* Option to supply +/-12V to edge connector for IF1 Serial support using PS1

V1.2
* Routed AY3-8910 IOB Bits0-7 to header J18 Pins 1(Bit0)- 8(Bit7)
* Routed AY3-891X IOA Bits0-7 to header J20 Pins 1(Bit0)- 8(Bit7)
* Changed ROM select header to 2 pin rather than 3 pin.


See https://github.com/konkotgit/ZX-48-Spider Rev 1.1 for original information on the ZX Spider, especially if you have issues
1) with BRIGHT being low or not visible - Might not, see above
2) Tape loading issues




