## OSBMX v2 Type M - 24mm + 30mm - Remix of the Open Source Button MX v2 by TheTrain
![OSBMX v2 01](Assets/OSBMX_v2_01.png)
![OSBMX v2 04](Assets/OSBMX_v2_04.jpg)
![OSBMX v2 06](Assets/OSBMX_v2_06.png)
![OSBMX v2 07](Assets/OSBMX_v2_07.JPG)

---

!!!WARNING!!!

I am not responsible for prints that do not turn out as intended or any damages that occur as a result of installation or usage of these buttons.

!!!WARNING!!!

There are a nearly endless number of MX switches floating around out there.  While you may be able to use all sorts of other switches in these, I cannot guarantee that any other switches will work.  It is highly recommended to try a switch or two out to ensure proper operation before buying a ton of them.


!!!WARNING!!!

The v6 boards from the original OSBMX (with built in connector prongs) are no longer supported due to multiple reports of the connectors breaking (very thin PCBs like to snap)

!!!WARNING!!!


---

## Attribution

Based on the OSBMX v2 by TheTrain.

Copyright © 2025 [TheTrain](http://x.com/thetrain24)<br/>

[Licensed under CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Changes from the original design:
  - Lowered the height of the ring and main body to accomodate SiTong and similar key caps
  - increased the space between the ring and main body by 0.2mm
  - increased the clearance between the main body and nut by 0.2mm

Anyone selling this commercially must include in the listing that this is an open source item, link to the original repo and include the copyright as well as the link to my X account.

---

## Summary

These are a remix of OSBMX v2 designed by TheTrain and made in Fusion 360.  

The changes were made to accomodate SiTong and similar sized key caps.

## Assembly

Assembly is quite straight forward on this board.  All that is needed is to solder the hot swap socket on and, if you choose, the 2.4mm or PH2.00mm 2pin connector(s)

Parts necessary for assembly of the PCBs:

1 x PCB<br/>
1 x MX hot swap socket (https://www.aliexpress.com/item/4001051840976.html)<br/>
1 x PH2.00mm 2pin vertical SMD connector (if connecting that way) (https://www.aliexpress.com/item/1005006027334406.html)<br/>
2 x 2.8mm prong connectors (if connecting that way) (https://www.aliexpress.com/item/1005002539360973.html) (Type: DJ610-2.8-2)<br/>
2 x M2 5mm Hex Hexagon Socket Cap Head Self Tapping Screws (https://www.aliexpress.com/item/10000350027047.html)<br/>

Parts necessary for assembly of 3D printed button:

1 x OSBMX v2 Plunger<br/>
1 x OSBMX v2 Rim<br/>
1 x OSBMX v2 Main Body<br/>
1 x OSBMX v2 Nut<br/>

Optionally you can also print a matching wrench to help with tightning and untighning.

You will also need an MX style switch to complete the button.

If connecting via 2.5mm prongs you will need to get a switch that has the LED cut out on there.  

If you are connecting via the PH2.00mm 2pin connector, pads, soldering to a hot swap socket or just soldering to the switch directly you can use any MX switch you like.

Not all switches have been tested, there may be some that do not follow the above rules.

---

## How to order a PCBs:

All of the boards so far have been ordered though JLCPCB.  Due to the size of the boards you can order quite a lot at very low cost.  I was able to order 125 of them and still meet their minimum shipping cost limits.  You do not need to get this many.  I have also opted not to do a panel for this since it appears to still be cheaper to get these done individually.  Also please note that recently JLCPCB changed some of their prices for the PCB color, ensure you choose a color like black or green to get the lowest possible cost.

1 - Go to JLCPCB.com<br/>
2 - Click on `Instant Quote`<br/>
3 - Click on `Add Gerber file` and choose the file named `Gerber - OSBMX v2.0 multi-connector.zip`<br/>
4 - Choose the following options for the board:<br/>
- Base Material = FR-4<br/>
- Layers = 2<br/>
- Dimensions = (should auto-populate) 22 * 22 mm<br/>
- PCB Qty = 100<br/>
- Product Type = Industrial/Consumer electronics<br/>
- Deburring/Edge Rounding = Yes<br/>
- Different Design = 1<br/>
- Delivery Format = Single PCB<br/>
- PCB Thickness = 1.6<br/>
- PCB Color = (up to you)<br/>
- Silkscreen = (defaults to white for all except white boards which is black)<br/>
- Surface Finish = HASL(with lead)<br/>
- Outer Copper Weight = 1oz<br/>
- Via Covering = Tented<br/>
- Min via hole size/diameter = 0.3mm/(0.4/0.45mm)<br/>
- Board Outline Tolerance = +/- 0.2mm(Regular)<br/>
- Confirm Production file = No<br/>
- Mark on PCB = Remove<br/>
- Flying Probe Test = Fully Test<br/>
- Gold Fingers = No<br/>
- Castellated Holes = No<br/>
- Edge Plating = No<br/>
- No advanced options<br/>

5 - Click on `SAVE TO CART`<br/>
6 - Go through checkout process, ensure to select economic shipping to keep costs low

---

## How to print the OSBMX v2:

A .3MF file is included which can be loaded into most slicers with a set of my recommended settings.  

To make each button you will need:
1 x OSBMX v2 Plunger<br/>
1 x OSBMX v2 Rim<br/>
1 x OSBMX v2 Main Body<br/>
1 x OSBMX v2 Nut<br/>

The rim should be printed flat side down.  The nut should also be printed flat side down.  

There are no supports needed for this print.  

It is recommended to print at the lowest print layer height your printer can do.  

I have extensivly printed and tested these on my BambuLabs X1C and P1S using both a 0.4mm and 0.2mm nozzle on normal and matte PLA.  

The recommended print setting are to do 4-6 wall loops and then enough top and bottom laters to have solid infill.  

You may need to adjust to achieve a good print on your own printer.  

!!!Please note - I am not responcible for missprints or any costs incured from missprints!!!

---

Revision History:

v1.0
- Original design
