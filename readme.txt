progs_dump Version 3.0.0
a Quake mapping devkit 
www.quakemapping.com
lango.lan.party@gmail.com
27 September 2022

***Please read the PDF manual for detailed information.***

******************************************************
******************************************************

ALWAYS START A NEW FOLDER WHEN USING PROGS_DUMP.
DO NOT COPY FILES OVER AN EXISTING VERSION.

******************************************************
******************************************************

The devkit consists of two elements:

First, there’s the "pd_300" mod folder. This holds all the sample maps,
mapping assets, source code and the documentation you are reading now.

The second element is the "my_mod" folder inside the "mod_template.zip" file.
This is a streamlined version of progs_dump with just the assets you need to
make your own mod.

The workflow is simple:

Use "pd_300" as a reference and learning tool, then create your own
Quake mod with the "my_mod" folder as a base.

NOTE: Your project should be  released as a stand-alone
mod and installed into its own folder in the Quake directory.

Please DO NOT include any of the sample maps in your mod.

==============================================================================

INSTALLATION:

Unzip this archive into your Quake directory. This should create a folder called
"pd_300" Run Quake with the following command line:

-game pd_300 +map start

or run Quake as usual and type

game pd_300

in the console and hit enter. Then use the menu to start a new game.

Some newer source ports like Ironwail have a "Mod" menu item that makes this even
easier.

Or use Simple Quake launcher to launch Quake with "pd_300" as the selected mod.
https://github.com/m-x-d/Simple-Quake-Launcher-2/releases

Take a tour and play the included sample maps. The sources are included for your
reference. pd_300.wad contains all textures from the sample maps.

Use the included FGD files with TrenchBroom or JACK or the DEF file with other
editors.

==============================================================================

This is a compilation of QuakeC code from various sources. Use at your own risk.
PLEASE contact me if you use progs_dump for a project, I'd love to see your
work!

-dumptruck_ds
lango.lan.party@gmail.com

The source for this mod is included in the development folder.

You can also inquire about progs_dump on the progs_dump dev Discord: 
https://discord.gg/bd7n4v2Xmj

or visit www.quakemapping.com

==============================================================================
progs_dump requires a modern Quake engine and was developed with Quakespasm.
==============================================================================

Recommended Quake Source Ports:

Quakespasm (0.96.3 and above) 
https://sourceforge.net/projects/quakespasm/files/
http://quakespasm.sourceforge.net/download.htm

Ironwail (0.8.0 and above)
https://github.com/andrei-drexler/ironwail/releases

vkQuake (1.31.3 or above) 
https://github.com/Novum/vkQuake/releases

Quakex 
(a.k.a. Quake Enhanced, Quake Remastered and  KEX Quake) 

Steam
https://store.steampowered.com/app/2310/QUAKE/

Epic Games Store
https://store.epicgames.com/en-US/p/quake


Other source ports:

Quakespasm-Spiked  (22-August-11 and above)
http://triptohell.info/moodles/qss/

FTEQW (Revision 6282 and above)
https://www.fteqw.org/

==============================================================================
We no longer recommend Darkplaces or MarkV for progs_dump. Although many 
features will work, these engines are untested and unsupported.
==============================================================================

==============================================================================

Known issues:

GENERAL ISSUES:

* progs_dump is untested in COOP
* Cutscenes display crosshairs if enabled.
* Using snd_hit on a style 4 or 5 monster_army will crash the game. Use style 3
  if you need a custom hit sound.

KEX ENGINE:

* Cutscenes "jitter" when mouse is moved.
* Some systems will have frame rate dips when Chthon is gibbed in the KEX engine.
* The sky in pd_cutscenes displays artifacts. This is an issue with the non-standard 
  sky texture used in this map.
* "Congratulations" graphics does not display when using info_intermissiontext.

FTEQW:

* Cutscenes "jitter" when mouse is moved unless host_maxfps is set to 72.
* Sleeping Zombies in pd_zombies spawn incorrectly but do not affect game play. 
  As a workaround do not cover sleeping zombies with any brushes if they are 
  touching the monster.
* Rendering issues in certain presets. We recommend using "Spasm, Vanilla"
  or "Normal" Graphics Presets in the Option menu.
* misc_model set to animate in reverse (speed -0.1) will not animate.
* A speed setting of -1 (change instantly) does not work on trigger_fog

==============================================================================

Distribution / Copyright / Permissions (verbiage courtesy of Arcane Dimensions)
------------------------------------------------------------------------------

Please do not use any of these assets in ANY COMMERCIAL PROJECT. And remember to
give credit if you use any of these assets.

The QC files in this MOD are based on 1.06 source files by ID Software. These
files are released under the terms of GNU General Public License v2 or later.
You may use the source files as a base to build your own MODs as long as you
release them under the same license and make the source available. Please also
give proper credit. Check http://www.gnu.org for details.

Quake I is a registered trademark of id Software, Inc.

All of these resources may be electronically distributed only at NO CHARGE to
the recipient in its current state and MUST include this readme.txt file.

===========================================================================
