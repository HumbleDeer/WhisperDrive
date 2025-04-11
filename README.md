# WhisperDrive

> A 2-wire fan control board meant to silence the PWM noise.

A project aiming to create a PCB that provides the means to supply your 3D-printer's fans with a smoothed DC voltage using a PWM-controlled input signal.

The main filter circuit can also be used with an existing low-side switched MOSFET port on a 3D-printer motherboard, although there are no PCB files for this purpose at this time.

## Documentation

- [Building the board](docs/build.md)
- [Configuration](docs/config.md)

## Get in touch

You can get in touch with me and other people affiliated with this project through our Discord server for Armchair Heavy Industries.

[![Discord Invite](https://discordapp.com/api/guilds/1029426383614648421/widget.png?style=banner2)](https://discord.com/invite/armchairengineeringsux)

## License

This source describes Open Hardware and is licensed under the CERN-OHL-S v2 or any later version.  
You may redistribute and modify this source and make products using it under the terms of the CERN-OHL-S v2. (<https://ohwr.org/cern_ohl_s_v2.txt>)

This source is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A PARTICULAR PURPOSE. Please see the CERN-OHL-S v2 for applicable conditions.

Source location: <https://github.com/HumbleDeer/WhisperDrive>

As per CERN-OHL-S v2 section 4, should You produce hardware based on this source, You must where practicable maintain the Source Location visible on the PCB.

## Other projects

Some other projects that may be worth checking out. These are probably friends of the communities I hang out in.

- [NyoomiesKME](https://github.com/comradef191/NyoomiesKME)  
  A Pico or BlackPill powered expansion board for Klipper, with support for four motors running in SPI or UART, and ability to run higher currents than most mainboards.
- [Kalico](https://github.com/KalicoCrew/kalico)  
  Formerly known as DangerKlipper
  > This is a community-maintained fork of the Klipper firmware. Our goal is to support features and behavior that could be "risky" if used incorrectly.
