Zygos Mask Lights project

ZML NODEMCU BOX
===============

### Summary

plan for a box for the NodeMCU card, made with MDF cutted by laser.


Abstract
--------

This repository is part of the Zygos Mask Lights project, inserting leds into masks and control them over a wifi network.

This part contains the Inkscape SVG plan of a box for a NodeMCU card.

The other parts are:
- [zml_wsserver](https://github.com/joliclic/zml_wsserver): code of the microcontroller listening the network via WebSocket, and command the leds inside the mask.
- [zml_webcontrol](https://github.com/joliclic/zml_webcontrol): an html page for sending commands via WebSocket.


What is ZYGOS MASKS LIGHTS ?
----------------------------

The [Zygos Brass Band](http://zygos.fr) uses for its show named "Trybz" masks made with polypropylene sheet cutted with laser (original plans by Wintercroft). This project add some leds (WS2812 plugged into a NodeMCU card) inside them, and control them with a tablet/smartphone over a wifi network via WebSocket.


The box
-------

The box is a assembly of MDM plates, cutted by Laser.
Some plates are 3mm thick (the box_mdm_3mm.svg file), others are 6mm (the box_mdm_6mm.svg file). 
So you can convert them in the format needed by your Laser cutting device.

You can find an assembly plan too (pdf).

TODO:
describe more precisely the other material needed to build the box.


All the code is under the MIT license.
