# Open Controller

NOTE: Note even remotely finished!

## Description

A open-source controller for PC/Xbox/PS3/PS4/Switch based on the Pico and GP2040-CE

## Concept

A quality controller for everyone that can play on most modern systems.

The shell is 3D printed, the internals are modular and swappable, the sticks use HAL effects, and everything is open for modification.

The initial design is loosely based on a GameCube controller with a large main button, a smaller secondary button, and two extra buttons, arranged closer to that of an Xbox controller.

Now consider these situations:

- Say that the game you're playing uses a different button as primary. Well, you should be able to just pop it out, rotate it, and plug it back in.
- Say you just don't like the big button scheme. Replace it all together
- Say you want a different layout. Print a different shell. Same goes if you want a different grip.

Easy to modify and quality out of the build. That's the goal.

## Parts of the Repo

- Circuits go in pcb/
- Shell designs go in models/
- GP2040-DADE/ is a submodule containing a modified GP2040-CE to allow Dual Analog and D-Pad, instead of just one at a time

Everything can be modified with FOSS software (KiCAD, FreeCAD, and Pico-SDK), so anyone can contribute.

