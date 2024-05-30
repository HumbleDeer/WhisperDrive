# WhisperDrive

> A 2-wire fan control board meant to silence the PWM noise.

A project aiming to create a PCB that provides the means to supply your 3D-printer's fans with a smoothed DC voltage using a PWM-controlled input signal.

The main filter circuit can also be used with an existing low-side switched MOSFET port on a 3D-printer motherboard, although there are no PCB files for this purpose at this time.

## Building the board

The board is (planned to be) designed with the DIY builder in mind. The component choice was made to be both easy to source, easy to design around, as well as still easy enough to solder with somewhat common tools.

### Tools

The required set of tools is fairly minimal and exists out of both essential tools as well as nice-to-have tools.  
If you're an experienced electronics builder, you may already plan to deviate from these tools and that is fine. You do you, you know you best.

The recommended toolset for this board consists of:

- A soldering iron  
  - A chisel tip is a must-have
  - 60W or more is recommended
- Leaded solder is preferred  
  - Sn/Pb 63/37 (eutectic mix) is ideal
  - Don't buy cheap solder from China!  
    It's easy to buy really crappy solder and feel disappointed in yourself, when in reality it's the solder being a royal pain in the arse.

### Tips

Tips are a great way to learn more. Good luck finding some tips! /s
(unfinished work)

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
- [Danger Klipper](https://github.com/DangerKlippers/danger-klipper)  
  Klipper but... Dangerous  
  > This is a community-maintained fork of the Klipper firmware. Our goal is to support features and behavior that could be "risky" if used incorrectly.
