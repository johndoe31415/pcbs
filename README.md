# pcbs
This is a collection of PCBs that I created, with everything from the schematic
to Gerber/Drill files for manufacture.

## Projects
  * stm32f103cx: Cortex-M3 STM32F103Cx (e.g., STM32F103C8T6) based core board.
    Includes breakout for the TQFP48 IC, crystal provisions, an MP2307-based
    input SMPS IC circuit that can generate 3.3V, a ULN2003AD output driver and a
    74HC4050 input level shifter. The idea is that you only populate what you need
    and just leave everything off that you don't. Created as a 100x100mm so that it
    fits Seeed Studio or other low-cost prototyping manufacturers.
  * stm32f103rx: Cortex-M3 STM32F103Rx (e.g., STM32F103RBT6) based core board.
    Includes breakout for the TQFP64 IC, crystal provisions, an MP2307-based
    input SMPS IC circuit that can generate 3.3V, a ULN2003AD output driver and a
    74HC4050 input level shifter. The idea is that you only populate what you need
    and just leave everything off that you don't. Created as a 100x100mm so that it
    fits Seeed Studio or other low-cost prototyping manufacturers.
  * stm32f030kx: Cortex-M0 STM32F030Kx (e.g., STM32F030K6T6) based core board.
    Includes breakout for the TQFP32 IC, crystal provisions, an MP2307-based
    input SMPS IC circuit that can generate 3.3V, a ULN2003AD output driver and a
    74HC4050 input level shifter. The idea is that you only populate what you need
    and just leave everything off that you don't. Created as a 100x100mm so that it
    fits Seeed Studio or other low-cost prototyping manufacturers.
  * softoff: A soft-off circuit using CD4011 for extremely low off-power
    consumption and an added ATtiny13 microcontroller to allow for features
    such as auto-off after a specific time. A simulation of the circuit is
    [available here](https://circuitverse.org/simulator/embed/softoff). It
    basically is an RS flipflop that drives a P-Fet and avoids invalid states
    (i.e., even when nR and nS are asserted at the same time, the behavior of the
    circuit is well-defined).

## Useful links
  * [Circuitmaker to Seeed Studio](http://support.seeedstudio.com/knowledgebase/articles/1187692-how-to-generate-gerber-files-from-circuitmaker)

## License
CC-0.
