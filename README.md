# Tiny-M_SSB_1010
Smol Stealthburner Toolhead for Tiny-M

<img src="Images/Tiny-M_SBB_1010.png" width="800">

# This repo is a combination of different mods to get the Smol Stealthburner working on the Tiny-M. 

Original Smol Stealthburner 1010 by Maverick on the Doomcube Discord. <a href="https://discord.com/channels/825469421346226226/909858082841067591/951228478278230057"/> Direct link to post.</a> The 1010 version uses a 3010 hotend fan, instead of the common 3007 fan from the Voron 0.1 toolheads.

Maverick's previous SSB version repo <a href= "https://github.com/PrintersForAnts/Crucible/tree/main/Smol%20Stealth%20Burner"> can be found here. </a>

# SSB 1010 for Tiny-M not fully tested

I have printed the SSB 1010 to verify fitment of parts, but it has not actually extruded any filament yet. 

**Print and use at your own caution.**

# MGN-12H Carriage Mod for Tiny-M

Tiny-M carriage is based on <a href="https://github.com/flyespresso/antpower/tree/main/SMOL%20Stealth%20Burner%20MGN9C%20V0%20Gantry%20Mod"> flypower's MGN9C Carriage mod for the SSB.</a> There are three versions of the carriage mod included in this repo: 

1. Carriage with a single 6x3 magnet made for the original Dragon hotend adapter. 
2. Carriage with two 6x3 magnets made for the Revo Voron hotend adapter. 
3. Low profile endstop carriage for Revo Voron (x endstop lowered for clearance with toolhead PCBs). 

# Revo Voron Mount

Revo Voron mount was designed from Maverick's original Dragon mount. Desgined with E3D's reference CAD available on their website.

# Assembly Notes

The fan shroud has wire routing for the hot end and part cooling fans. The SSB was designed with QD connects for the fans, but you can run the wires if you don't want the added expense. I mounted two Wago 221s on the back side of the fan shroud for ease of future maitenance.

This toolhead **is shorter than the original Tiny-M V4 toolhead.** That means you must verify your Z axis leadscrew is long enough to raise the bed far enough for the nozzle to trigger the z endstop. Your leadscrew nut should also be mounted on the bottom of your nut mount on the bed carraige, instead of on top of the leadscrew nut mount like I had it before. Belted Z Tiny-M owners, you're in uncharted waters. Let me know how it goes.

I'm using an extended X axis endstop as a left over from my previous toolhead. I've left in the CAD here as I've verified that the SSB triggers it correctly. The Original X-endstop may work with the SSB, but you will have to test it out yourself.