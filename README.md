# my3dChameleon

A Configuration file for Klipper to use the 3dChameleon.
I use it on a Sovol SV06 Plus, you will need to adjust some things to make this work for your printer, even if you have the same printer.

If you have the SV06 / Plus you can find printable parts here:
https://www.printables.com/model/371141-3dchameleon-mk3-mounts-for-the-sovol-sv-06-and-plu
I also uploaded a Remixed version of the extruder bracket without the bar to hold the y-adapter, I used a M6 PTFE coupler instead

Please follow the instructions of 3dChameleon from https://www.3dchameleon.com/instructions


This set of macros are designed to work **WITHOUT a slicer specific toolchange gcode**. 
Just place mmuStart in your Start-Gcode and mmuEnd in the End-Gcode (or to your corresponding macros).
Toolchanges are handled internally and are triggered by T0, T1, T2, T3 which is the default behaviour of Prusa Slicer and its forks. 

>[!NOTE]
>This is work in progress. If you find any errors please open a issue or create a pull request.



