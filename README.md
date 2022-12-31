# Tiny-M_SSB_1010
Smol Stealthburner Toolhead for Tiny-M

<img src="Images/Tiny-M_SSB_1010.png" width="800">

## Print and use at your own caution.

I have printed the Revo Voron/LGX Lite version of SSB 1010 to verify fitment of parts, but I haven't printed anything with it yet. Other hotend and extruder combos are so far untested.

## Change Log

- **12-30-2022**
	- Cleaned up and combined separate CAD files.
	- Reorganized STL directory
	- Added hotend adapters for Sherpa-Micro and Orbiter V2 extruders.

- **2022-11-08**
	- Added Sherpa Extruder support for Dragon and Revo Voron Adapters.
	- Replaced Adapter_Dragon STL with new version.
	- Removed MGN12 carriage for original Dragon Adapter.
	- Added separate STEP file for just the toolhead with updates.
	
## BOM

- 3010 hotend cooling fan
- 30mm blower part cooling fans X2
- 6x3 magnets x2
- Hotend specific mounting screws (refer to your hotend specs)
- M3x40mm screws x2


## Assembly Notes

The fan shroud has wire routing for the hot end and part cooling fans. The SSB was designed with QD elctrical connections for the fans, but you can just run the wires if you don't want the added expense. I mounted two Wago 221s on the back side of the fan shroud for ease of future maitenance.

This toolhead **is shorter than the original Tiny-M V4 toolhead.** That means you must verify your Z axis leadscrew is long enough to raise the bed far enough for the nozzle to trigger the z endstop. Your leadscrew nut should also be mounted on the bottom of your leadscrew nut mount (on the bed carriage), instead of on top of the leadscrew nut mount (like I had it before). Belted Z Tiny-M owners, you're in uncharted waters. Let me know how it goes.

I'm using an extended X axis endstop as a left over from my previous toolhead. I've left in the CAD here as I've verified that the SSB carriage triggers it correctly. The Original X-endstop block may work with the SSB carriage, but you will have to test it out yourself.

## Credits
- <a href="https://discord.com/channels/825469421346226226/909858082841067591/951228478278230057"/> Original Smol Stealthburner 1010 by Maverick on the Doomcube Discord.</a> 
- Tiny-M carriage is based on <a href="https://github.com/flyespresso/antpower/tree/main/SMOL%20Stealth%20Burner%20MGN9C%20V0%20Gantry%20Mod"> flypower's MGN9C Carriage mod for the SSB.</a>
- <a href="https://github.com/Annex-Engineering/Sherpa_Mini-Extruder"/> Sherpa Mini </a> and <a href="https://github.com/Annex-Engineering/Sherpa_Micro-Extruder"/> Sherpa Micro </a> by Annex Engineering.
- <a href="https://e3d-online.zendesk.com/hc/en-us/articles/4444939320093-Revo-Voron-Reference-CAD"/> Revo Voron reference CAD </a> by E3D Online
- Thanks to riccardoer on Discord for the Sherpa Micro adapter.