# mini-b
Toolhead for [Voron Design v0.1](https://vorondesign.com/voron0.1)

**Still in early dev. User at own risk.**

![demo](https://user-images.githubusercontent.com/11328522/154850398-ead0e8c0-f2e9-40af-bacc-247a68ce8bda.gif)
<img src="https://user-images.githubusercontent.com/11328522/154849858-c1b2f472-fc35-4eb4-90dc-ad13413cff0b.png" height=320>


**4010 Heater Fan** with **5015 parts blower fan**. Requires **different X-carriage** included. Accepts LGX lite with mounting plate (untested). Tested with [Kami extruder](https://github.com/intositeme/kami-mini).

Works with both Dragon & Mosquito hotends with *different* stls specific for each. Dragon's cowling is 2mm thicker thus will reduce Y by 2mm vs the Mosquito hotend.

**Note:** 4010 heater fan, the toolhead mounting screws passed 2 of the fan's holes, GDStime 4010 fans have a recessed hole which needs to be filled in to be flushed, if not the cowling plastic will break when tightened down. I used washers, printed part would do fine.

Initially thought toolhead will loose ~5mm in X/Y travel. Please check this on your printer, I some how managed to get more travel, ~ 3mm in X and 2mm in Y.

Known Issues, I might/might not fix
- ~~Fan ducts angle is pretty steep and hard to print properly (i just sand it down for cosmetic sake)~~
- ~~5015 front inlet cutout might not be centered to the fan, though it is in cad, could be due to GDStime fans being different?~~ Won't be fixing, been told some other fans sit nicely centered.
- ~~There might be a small gap in some corners of the print (new to CAD)~~



## Xcarriage

Added in X-carriage with different variations. Initial carriage was working with a different toolhead, but seems to be breaking with the added weight of this toolhead. 
- `X_Carriage - for v2.stl` - Standard to use with `lgx-mount.stl`

These following x-carriages requires the `lgx-mount-recessed.stl` and only the LGX-lite extruder
- `X_Carriage-extra beef.stl` - Extra thick +3mm 
- `X_Carriage-extra -extra beef.stl` - 5.5mm thick, requires 2 m3x4.2(diameter)x5 heat insert & 25mm BTS screw, screws go in from the front.
- `X_Carriage-extra -extra beef - mgn9.stl` - Used with mgn9 rails. Requires 2 m3x4.2(diameter)x5 heat insert & 30mm BTS screw, screws goes in from the back, ensure when tighten, the screws does not extend past the front and cause toolhead mounting issues.
