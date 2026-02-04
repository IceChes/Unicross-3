# Unicross
Unicross is a highly reliable cross-gantry 3D printer built with accessible parts and simple design practices.

![IMG_2609](https://github.com/user-attachments/assets/1313b09d-3dec-41d6-b2d4-59fb3f87c02a)

For up to date CAD: https://cad.onshape.com/documents/4eb1484887fc2987f4944e2c/w/5df6581cff3116f0fb19b47b/e/0f43dcdbef88a724da59cfd0

This project is IN PROGRESS and subject to change at any time without notice.

### Features:
- 180mm printing area
- Printable in PETG
- Direct drive extruder and Bambu hotend
- Accessible BOM
- Assembly manual
- Quality part cooling
- Self replicating
- Open source hardware (through Onshape)
- Runs Klipper

### Coming eventually:
- Prusaslicer configs
- Klipper configs
- Wiring guide

# What's the point?
My Unicross 3 build, after ironing out some first-assembly issues, has never broken. Cross gantry 3D printers are known for their speed, yes, but the dead-simple geometry and the overbuilt mechanics of the kinematics system in general makes it an unbelievably reliable basis for a 3D printer. 

# Sourcing components
This isn't a Voron or something that you can just buy a kit for, but the components are really easy to get. Due to tariffs, however, I cannot accurately estimate a price for this machine. 

I do not recommend spending more than $350 to build this thing. It's just not worth it, even with the reliability. I implore you to do your own shopping and come to your own conclusions.

**Cost cutting tips:** 
- If you have a couple old Monoprice Maker Selects lying around (this is a surprisingly common situation?) then the price drops dramatically as many of the motion components (and the bed!) can be repurposed.
- Both X motors must be identical, and both Y motors must be identical. However, the X motors and Y motors don't have to be the same as each other.
- The entire electronics enclosure can be PLA.
- There's a huge list of compatible beds to choose from. Pick any one that will fit! Alternatively, pop into Onshape and design your own - the design is uncomplicated.
- The power supply mounts are designed for an LRS-350-24 from meanwell. However, the Ender 3 power supply is exactly the same size, just thicker.
- Short on LM8LUUs? You can use regular LM8UUs for the Z axis with a small quality sacrifice, just not for the X/Y axes.

# Features, in detail
### X/Y axes
Unicross is based on linear rods due to their low cost and mechanical simplicity. They aren't super rigid or anything, so the machine isn't terribly fast, but it's cheap and it works. The belts are regular GT2 belts.

### Z axis
The Z axis is a single-motor dual-screw system driven with a belt. This isn't perfect, but it gets Z axis quality that's up to my standards. 

### Electronics
It has them. Requires bending pins for assembly, but it's not actually that big of a deal.

### Toolhead
The toolhead is a very simple plastic brick, designed for simplicity and durability. There isn't much to say here. 

# Questions you may have
### I don't like <thing>. Can it be changed?
Sure. Just copy the Onshape document or download the assembly STEP and make whatever changes you want. I would love if you'd also DM me @iceches on Discord and I'll see if I can implement it in the main repository.

### What can I print?
PLA, PETG, TPU without an enclosure. If you have an enclosure or you cover up the sides and top, ABS, ASA, and PA are also printable.

### What can't I print?
I have no idea. Every filament I've tried has worked.

### Are there any known issues with this design?
Certainly. The idler mounting is suboptimal, and the Z axis is imperfect. I was unable to fix these two issues, but you might be able to!
