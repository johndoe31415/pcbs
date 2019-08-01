# pcbs
This is a collection of PCBs that I created, with everything from the schematic
to Gerber/Drill files for manufacture.

## Projects
  * stm32f103cx: STM32F103Cx (e.g., STM32F103C8T6) based core board. Includes
    breakout for the TQFP48 IC, crystal provisions, an MP2307-based input SMPS
	IC circuit that can generate 3.3V, a ULN2003AD output driver and a 74HC4050
    input level shifter. The idea is that you only populate what you need and just
    leave everything off that you don't. Created as a 100x100mm so that it fits
    Seeed Studio or other low-cost prototyping manufacturers.

## Useful links
  * [Circuitmaker to Seeed Studio](http://support.seeedstudio.com/knowledgebase/articles/1187692-how-to-generate-gerber-files-from-circuitmaker)

## License
CC-0.
