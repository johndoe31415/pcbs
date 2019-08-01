# TODO

  * The SMPS circuit is entirely unverified and I'm not sure if it even can be
    stable.
  * Board outline could be a bit smaller, 1 thou seems okay.
  * MP2307 silkprint isn't centered around part, could move a bit more to the 
    left
  * Remove top silkscreen "johndoe31415" in favor of bottom silkscreen (it's
    already there and having it twice indicates narcissism) and put some more
    pads there (possibly some GND pads as well, could be useful)
  * Silkprint and schematic are wrong for the main MCU. It's not the
    STM32F103xC, but the STM32F103Cx. I'm not sure how I could miss that.
