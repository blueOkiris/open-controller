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

## Ordering Parts

### Thumb Sticks

Thumbsticks don't come HAL effect, so we have to mod them :/

Not to worry I've got you covered!

Buy some [XBOX 360 sticks with buttons in them](https://www.aliexpress.us/item/2255799933721604.html?spm=a2g0o.productlist.main.5.436b7klq7klqh7&algo_pvid=a678abce-1754-4e64-b07f-d5fa097f90cc&algo_exp_id=a678abce-1754-4e64-b07f-d5fa097f90cc-2&pdp_npi=3%40dis%21USD%213.91%212.58%21%21%21%21%21%40210217c716860326154822728d073c%2110000000329388606%21sea%21US%211790934586&curPageLogUid=7TsMjnnQSlwR)

Also get [XBOX One caps](https://www.aliexpress.us/item/3256801227675996.html?spm=a2g0o.productlist.main.17.436b7klq7klqh7&algo_pvid=a678abce-1754-4e64-b07f-d5fa097f90cc&algo_exp_id=a678abce-1754-4e64-b07f-d5fa097f90cc-8&pdp_npi=3%40dis%21USD%214.05%213.24%21%21%21%21%21%40210217c716860326154822728d073c%2112000015991068349%21sea%21US%211790934586&curPageLogUid=fputmQWZwgBL) for the buttons

Then get [HAL effect sensors](https://www.mouser.com/ProductDetail/Texas-Instruments/DRV5053EAQLPG?qs=U0ECReq1GB%2FEJedkxMZGLA%3D%3D) and [magnets](https://www.kjmagnetics.com/proddetail.asp?prod=DH1H1)

What we're going to do is we're going to pull off the potentiometers of the sticks (they just pop off), carefully glue the magnet horizontally so that it will rotate with the stick, and then assemble the pcb so there's about 2mm between the magnet and the HAL sensor.

![picture](./img/hal-effect-assembly.jpg)

