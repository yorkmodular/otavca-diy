# OTAVCA revision 2: Dual LM13700 linear VCA (6HP)

*IMPORTANT:* this module is designed for use with modular-level signals.

An updated version of my old OTA VCA - this one has been rejigged so that the layout is a bit more user-friendly and the module as a whole is a bit more viable for those people who insist on using absurdly shallow cases -

The LM13700 is one of those chips that has been knocking around for years, minding its own business, despite the fact that it is a mind-bogglingly useful and versatile piece of silicon. Granted, it can be a bit of a pain to work with, but it's still useful nonetheless.

This is a dual VCA, each channel of which uses one of the transconductance amplifiers on the 13700. Other than the addition of a couple of linear current sources for CV control this isn't massively different from the circuit you'll find in the datasheet. It works best with signals in the 0-5V range, although it's relatively unbothered by particularly hot CVs from envelope generators.

Is it as good as, say, something built round a THAT2180 or similar? No ... but it's a hell of a sight cheaper.

On a technical note, the CV LEDs are driven through the on-board buffers on the LM13700, so require a fairly high voltage (~4V) to illuminate, so if the CV level is particularly low you may not see any illumination, even with low forward voltage LEDs - if this bothers you then I recommend setting the CV level put fully clockwise and adjusting the output using the gain pot.

MODDER'S NOTE: as supplied, the gain stage tops out at 2x - this is sufficient for most purposes. If it isn't enough for you, you can replace resistors R19 and R20 (both 47k) with smaller values. 0805 resistors are relatively easy to hand-solder.
