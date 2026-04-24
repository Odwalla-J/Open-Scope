# Open-Scope

The Open-Scope project is an open source effort designed to serve as a framework for the community to encourage the development and refinement for the (admittedly niche) use of LCD based scope systems for the broader DIY lightgun community.

This software + firmware + hardware stack includes the custom MAME plugin and host software, the ESP32 based scope, and a 3D printable rifle inspired by Konami's own arcade controller. 

Contributions and feedback can be given on my Discord in the corresponding channel:
[Odware Designs Discord](https://discord.gg/abWf68fpRK "https://discord.gg/abwf68fprk")

(insert picture)

The core idea is to simplify the addition of LCD scopes to existing lightguns using a simple 4 wire interface for use with Silent Scope or future projects.
Although this is an admittedly niche project, there weren't any compelling or clean solutions that felt practical or reliable outside of the use of small HDMI displays with all of their required cabling.
Using a cheap GC9A01 based round LCD and an ESP32-P4 it's possible to send the video signal as a byte array over serial to the display at it's native 240x240 and achieve a smooth 60fps.
With a bit of pre-planning or slight modification this can be implemented within existing USB based lightgun peripherals through the addtion of a cheap USB hub PCB that supports USB 2.0 High Speed.

## Shout Outs
Thanks to [McCutheon](https://github.com/mccutheon) for the initial inspiration and encouragement on the project, RG2020 for his invaluable feedback, and the rest of the OpenFIRE team for making all of this possible, free and accessible.
