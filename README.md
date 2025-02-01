# ELF-II-Very-Simple-Sound-Card

Very Simple Sound card for the ELF II

This board uses the CDP1863 8-Bit Programmable Frequency Generator to create the tones that drives a small speaker via a single transistor amplifier. 
There is reset circuitry via a 74HC14 Hex Schmitt−Trigger Inverter that resets the CDP1863 upon power up and also allows reset via a buttton.

A more complex tone output can be done via CHIP-8X via the Fx15, Fx18 commands but simple code like EE 64 7B will cause the CDP chip load up it's data with whatever value is in the resgister E and be toggled on via Q
