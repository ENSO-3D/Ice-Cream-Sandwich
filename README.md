# ICS.200 **(WIP)**

**!THIS PROJECT HAS THE CURRENT STATUS: WORK IN PROGRESS!**

A sweet CoreXY platform.

<p align="center" width="100%">
    <img width="100%" src="https://github.com/ENSO-3D/ICS.200/blob/main/Images/ICS200Panels312.png"> 
</p>

 ![Small Image of ICS.200](https://github.com/ENSO-3D/ICS.200/blob/main/Images/ICS200Panels312.png)
 ![Small Image of ICS.200](https://github.com/CORELabs3D/ICS.200/blob/main/Images/ICS.200.3.jpg)

ICS.200 is a fully enclosed CoreXY printer using The Ice Cream Factory's Ice Cream Sandwich build technique. The ICS.200 is built around MGN9H rails that are 200mm long with a build area of around 160x160x160mm, the design allows for it to be scaled easily. 

Ice Cream Sandwiches are parts made of laser cut aluminum (typically 2-3mm) sandwiching a central printed plastic core.  This is similar in construction to ACM panels such as DiBond which have an incredible strength to weight ration.  Nearly all load is carried by the much stiffer aluminum panels (75x as stiff as plastic).  The plastic core is merely to space the panels apart. Additionally for high load situations aluminum spacers also separate the plates. It should be possible to have the panels made by PCB houses using 2mm aluminum PCBs for about 20% the cost of laser cutting, making the construction technique quite inexpensive.

It utilises 200mm MGN9H rails all around and 6mm 2GT belts.
Electronics are mostly placed in the back, and AC parts are placed in the bottom.
Toolhead movement is provided by two 2504 or 2804 Nema17 stepper motors.
 
Part cooling is via CPAP.

The bed is 6mm cast aluminum lifted via 6mm 2GT belts by three 5:1 belt reduced drives or direct drive. It features proper Maxwell kinematic joints to allow for bed expansion while constraining other motion and to allow automatic bed leveling.   Bed levelling and mesh probing is done with a probe.

ICS.200 is fully enclosed with panels on all sides.

The project is being discussed on the CroXY Discord server: https://discord.gg/SeYrseguuf

The sister printer Quattro Gelato is found here: https://github.com/CroXY3D/Quattro-Gelato

The idea of using pins with sandwich for the Maxwell bed coupling comes from @whoppingochard:
https://github.com/tanaes/whopping_Voron_mods/tree/main/kinematic_bed

A prototype was built based on PCB plates, however it is no being redone fith updates and changes:
![Small Image of ICS.200 Prototype](https://github.com/CORELabs3D/ICS.200/blob/main/Images/ICS.200prototype.jpg)
![Small Image of ICS.200 Prototype](https://github.com/CORELabs3D/ICS.200/blob/main/Images/ICS200Prototypeprinting.gif)

This project is licensed as
![image](https://user-images.githubusercontent.com/37383368/139769027-7267da5b-7f58-499d-96bc-e41d164a3aac.png)

https://creativecommons.org/licenses/by-nc/4.0/
