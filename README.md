# OpenAmiga600RamExpansion
OpenAmiga600RamExpansion is an Open Hardware 1 MB Chip RAM Expansion for the Commodore Amiga 600 Computer with optional Real Time Clock, by SukkoPera https://github.com/SukkoPera/OpenAmiga600RamExpansion/.

This project is a different layout of the board, with almost the same BOM :
- smaller board, no space for ram chips sockets,
- inverted connector, so that components are facing downside and the solder joints do not touch the trapdoor,
- footprint for CR1220 in addition to the CR2032.

# Disclaimer
This is a hobbyist project, it comes with no warranty and no support.

This version is not connected to SukkoPera, please don't bother him with issues you might have because of it.

I publish this work using the same license as the original project : CERN OHL v1.2.

If you find it useful, please reward the original author. See the original repository.

# Making it
You should refer to the original repository where SukkoPera provides excellent advice about connector availability, RAM chips to use (I personally installed V53C16256HK40) and RTC. I confirm that AmigaTestKit is a must to check that the board is working fine (among other test).

Check for shorts at least between 5V and GND traces before applying power !

# Using it
- Install the battery,
- Plug to the motherboard,
- Power on the system.

