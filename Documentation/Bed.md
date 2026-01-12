# Bed stuff 
Unicross 3 was originally designed to use the Kingroom KP3S bed. However, this printer is discontinued. Some alternatives have been offered instead.
- Kingroon KP3S: The original bed. The PID tuning will work out of the box.
- Custom Unicross: Custom 200W PCB bed. Gerber files included. See documentation below.
- Lerdge IX: 180mm bed from the little-known Lerdge IX printer. These are pretty cheap online.
- Monoprice: Monoprice Maker Select bed. Oversized, but very common. Uses 12 volts, however, so some PID tuning may be in order.

### Notes
The BOM assumes that you have ALL necessary mounting hardware and electronics. This means that if you are using, for example, the custom Unicross bed, you will need to supply your own long M3 bolts, springs, and knobs. 
All Unicross beds MUST be able to be leveled using springs.
Also, remember to print the cooresponding mounts for whatever bed you pick.

### Custom bed
The custom Unicross bed is not a particularly economical option due to the cost of one-off manufacturing of boards this large. However, it is by far the most powerful bed.

The PCB has been designed for 1oz copper. It should be ordered in as thick of an FR4 substrate as reasonable, or ~3mm aluminum substrate. 

Kicad and gerber files are attached in the /Files/Bed Files/ directory.
