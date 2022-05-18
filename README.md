# Fab Touchprobe 
*By Frikk H Fossdal, May 2022*

![](./img/hotplate_probe.gif)

## What is it

A fabrication friendly design of a 3-DOF touch probe. At the heart of the design is a circuit board that lights up leds on probe contact. 

## How to use it

The probe acts as a digital switch. Connect it to your favorite machine controller and start probing. 

**NB! First batch of circuits has wrong labeling on connector input. Ground and input voltage is switched. Study circuit before connecting and chech yourself!**

## How to make it

The repo contains all the files that are necassary to print the parts and make the circuit. There are currently two circuit designs: one that is pcb mill friendly and one that is meant for fabrication houses. I'm using the latter. Some notes: 

- Originally the probe uses [threaded steel-balls]() and dowels to form the kinematic mount but this could be modified to only use screws and dowels for easier sourcing.
- I print the probe casing with two different filaments, one transparent for making the circuit leds visible and one solid gray. If you rather print the casing as one solid merge the two casing bodies. 
- If you want to use a different probing stylus change the "nut diameter" of the nut on the *probe base* to fit your chosen diameter. 

## BOM

| **Part Name**       | **Description**                   | **Quantity** | **Link**                                                                                  |
|---------------------|-----------------------------------|--------------|-------------------------------------------------------------------------------------------|
| threaded steel ball | typically found in delta printers | 6            | [amazon](https://www.amazon.com/Bolsen-Threaded-Kossel-3D-Printer-Magnetic/dp/B07HQ72H1R) |
| steel dowels 5x10mm |                                   | 3            | [mcmaster](https://www.mcmaster.com/93600a511/)                                           |
| probe stylus m3x50  |                                   | 1            | [ebay](https://www.ebay.com/itm/132811711640)                                             |
| m4button x 8mm      |                                   | 6            | [mcmaster](https://www.mcmaster.com/93600a511/)                                           |
| m3button x 14mm     |                                   | 3            | [mcmaster](https://www.mcmaster.com/92095A168/)                                           |
| m3_locknut          |                                   | 3            | [mcmaster](https://www.mcmaster.com/90576A102/)                                           |

## Develop notes 

- After discussing with Jake we agreed that the design of the probe needs to be modified with some way of offsetting the centering of the probe. Revision will follow in near future. 
- Spring force matters. I have to do more research to find good sensitivity.

<iframe src="https://myhub.autodesk360.com/ue29e30e9/shares/public/SH9285eQTcf875d3c539d67aaeaef3a23b4d?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


