# What is this?

![Photo of the full assembly](/photo.jpg)

This is a PCB for the "Elektronik-Retro-Sound Adventskalender" by Franzis press.

The original kit is built on breadboard but I wanted a more durable solution taking less space and made a quick PCB design for it.

# Parts

All parts are included in the kit except for an optional power switch (SW5) and optional terminal blocks for speaker and battery. I would recommend to at least add pin headers and a jumper for SW5 when soldering the battery pack directly. Otherwise you can't turn the device off without removing the batteries from the holder.

When not using SW5, solder JP1 closed. This will bridge SW5 to be always closed.

| Reference | Value     | Notes                                             |
| --------- | --------- | ------------------------------------------------- |
| C1-C4     | 104       |                                                   |
| C5, C6    | 100uF     | white - mark facing left (direction of pots)      |
| D1-D8     | LED       | short leg facing left                             |
| R1, R5    | 1kΩ       |                                                   |
| R2        | 100kΩ     |                                                   |
| R3        | 560Ω      |                                                   |
| R4        | 15kΩ      |                                                   |
| RV1-RV3   | 10kΩ pot  |                                                   |
| SW1-SW4   | button    |                                                   |
| U1        | soundchip |                                                   |
| U2        | LM386     |                                                   |
| BT1       | battery   | solder directly or add screw terminal (5mm pitch) |
| LS1       | speaker   | solder directly or add screw terminal (5mm pitch) |
| SW5       |           | (optional, not included originally) add a 2.54mm pitch switch or jumper to switch the battery power on and off |
| JP1       |           | solder closed if not using SW5 to force it closed |

# License

[CC0](https://creativecommons.org/share-your-work/public-domain/cc0/)

But please drop me a note if you do something fun with it :)
