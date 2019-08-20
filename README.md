# <a name="top" id="top"></a>Stuff of The Magi

<strong>Original Author:</strong> Victor Straffe<br />
<strong>Version:</strong> 6.0.0<br />
<strong>Language:</strong> English, <a href="README-FR.md">French</a><br />
<strong>Platforms:</strong> Windows

<strong>Mod Website and Forum:</strong> <a href="http://www.shsforums.net/topic/34134-stuff-of-the-magi/">Spellhold Studios</a></p>


<center><a href="#intro">Overview</a> &#x2B25; <a href="#compat">Compatibility</a> &#x2B25; <a href="#installation">Installation</a> &#x2B25; <a href="#components">Components</a> &#x2B25; <a href="#credits">Credits</a> &#x2B25; <a href="#version">Version History</a></center></br></br>


<hr>


## <a name="intro" id="intro"></a>Overview

This mod adds the Stuff of the Magi set to some creatures. Please read <a href="https://raw.githubusercontent.com/GwendolyneFreddy/StuffOfTheMagi/master/stuffofthemagi/readme/sotm-spoilers.txt">sotm-spoilers.txt</a> for details.

Also, if you have all items, you will meet someone in the Pocket Plane who will want to speak with you...

Note: If you choose the original items you will only end up with 7 items instead of 9, no cape nor ring.

<strong>Never forget:</strong> All the original work was done by Victor Straffe at Sorcerer's Place.


<hr>


## <a name="compat" id="compat"></a>Compatibility

This mod is designed to work on the following Infinity Engine games: the original Baldur's Gate II (BG2 or just SoA) with the Throne of Bhaal (ToB) expansion, Baldur's Gate II: Enhanced Edition (BG2EE), the conversion projects Baldur's Gate Trilogy (BGT) and Enhanced Edition Trilogy (EET).

This is a <acronym title="Weimer Dialogue Utility">WeiDU</acronym> mod, and therefore should be compatible with all WeiDU mods. If you encounter any bugs, please report them on the forum!<br>
<div style="text-align:right"><a href="#top">Back to top</a></div>


<hr>


## <a name="installation" id="installation"></a>Installation

#### Notes

<em>If you've previously installed the mod, remove it before extracting the new version. To do this, run <strong>setup-stuffofthemagi.exe</strong>, uninstall all previously installed components and delete the stuffofthemagi folder.</em>

<em>When installing or uninstalling, <strong>do not close the <acronym title="Disk Operating System">DOS</acronym> window</strong> by clicking on the <strong>X</strong> button! Instead, press the <strong>Enter</strong> key whenever instructed to do so.</em>

<strong>Disable any antivirus</strong> or other memory-resident software before installing this or any other mod. Some (particularly avast and Norton!) have a tendency to report false positives with mod activity, resulting in failed installs.

## 

#### Enhanced Editions Note

The Enhanced Editions are actively supported games. Please note that every patch update will wipe your current mod setup! If in the middle of a modded game you might want to delay the patch update (if possible) as even after reinstalling the mods, you might not be able to continue with your old savegames. Alternatively, copy the whole game's folder into a new one that can be modded and will stay untouched by game patches. It is important that you install the mod to the language version you are playing the game in. Otherwise, the dialogues of the mod will not show but give error messages.

## 

#### <a name="config" id="config">:warning: Warning: new installation process

##### As of version 6.0.0, options needed for installation are read from <a href="https://raw.githubusercontent.com/GwendolyneFreddy/StuffOfTheMagi/master/stuffofthemagi/stuffofthemagi.ini"><em>stuffofthemagi.ini</em></a> file, or <em>stuffofthemagi_user.ini</em> if it exists.

As interrupting installation with plain text prompts allowing players to customise components to their liking, those variables have been moved into <a href="https://raw.githubusercontent.com/GwendolyneFreddy/StuffOfTheMagi/master/stuffofthemagi/stuffofthemagi.ini">stuffofthemagi.ini</a> file in <strong>stuffofthemagi</strong> folder. This file provides a '<em>standard</em>' installation.

If you want to define your own customized installation, you have to modify the variables involved in <strong><em>stuffofthemagi.ini</em></strong>, then save this file as <strong><em>stuffofthemagi_user.ini</em></strong>.

The installation process will read both ini files and prioritize user values. If a value is not set or mismatched in stuffofthemagi_user.ini, any installation failure will be prevented by reverting it back to its default value.</br>

Here is a chart listing the variables related to the installation process:<br>

<table style="margin-left: 80px" summary="Installation variables listing">
	<tr>
		<th>Variables</th>
		<th>Description</th>
		<th>Type</th>
		<th>Scope values</th>
		<th>Default value</th>
	</tr>
	<tr>
	<tr>
		<td style="padding-left:5px;padding-right:5px"><span style="color: #FFCC33">sotm_use</span></td>
		<td style="padding-left:10px;padding-right:10px;text-align: justify">Items Power</td>
		1 = Use new, less cheesy items (recommended).<br>
		2 = Use original, overpowered items.<br>
		<td>integer</td>
		<td>1 or 2</td>
		<td><strong><span style="color: #FFCC33">1</span><strong></td>
	</tr>
	<tr>
		<td style="padding-left:5px;padding-right:5px"><span style="color: #FFCC33">sotm_equip</span></td>
		<td style="padding-left:10px;padding-right:10px;text-align: justify">Where to find items</td>
		<td>integer</td>
		1 = Add items to creature's equipment (recommended, enemies will use these items against you).<br>
		2 = Add items to creature's inventory (does not change difficulty of fights).<br>
		<td>1 or 2</td>
		<td><strong><span style="color: #FFCC33">1</span><strong></td>
	</tr>
</table>

## 

#### Windows

Extract the contents of the mod archive into the folder of the game you wish to modify, using <a href="http://www.7-zip.org/download.html">7zip</a>, <a href="http://www.rarlab.com/download.htm">WinRAR</a>, or another file compression utility that handles .zip files. On successful extraction, there should be an stuffofthemagi folder and a setup-stuffofthemagi.exe file in your game folder. To install, simply double-click <strong>setup-stuffofthemagi.exe</strong> and follow the instructions on screen.

Run <strong>setup-stuffofthemagi.exe</strong> in your game folder to reinstall, uninstall or otherwise change components.

## 

#### Note for Complete Uninstallation

In addition to the methods above for removing individual components, you can completely uninstall the mod using <strong>setup-stuffofthemagi --uninstall</strong> at the command line to remove all components without wading through prompts.</br>
<div style="text-align:right"><a href="#top">Back to top</a></div>


<hr>


## <a name="components" id="components"></a>Components

The installer includes the following components. The number of each is the component DESIGNATED number which gives it a fixed install position, lets other components detect it and allows automated installers like the BiG World Setup specify component choices.
<div style="text-align:right"><a href="#top">Back to top</a></div>


<hr>


## <a name="credits" id="credits"></a>Credits and Acknowledgements

#### Author: Victor Straffe (at Sorcerer's Place)


#### Special Acknowledgements to (alphabetical order):

- Cmorgan: Help with bugsquishing/tidiness/etc.
- Deratiseur: Made it compatible with translations, wrote the French translation, and provided the EE compatible version.
- Kevmus: Updated the mod to WeiDU, added the more balanced items, and bug fixed.
- Rastamage: Item stories/Erevain's talk
- Tassadar88: Help with coding
<div style="text-align:right"><a href="#top">Back to top</a></div>


<hr>


## <a name="versions" id="versions"></a>Versions History

##### Version 6.0.0 - Month day, 2019

- Removed unnecessary files: handle_charsets.tpa, .
- Removed unnecessary backup folder.

- stuffofthemagi.ini:
- Removed READLN to support ALIEN's "Project Infinity".

- Added compatibility with 1PP and ToBEx.
- Added Detectable Spells variables.
- Appended items to tooltip.2da file.
- Fixed remaining glitches and bugs.
- Scroll Case (wzrdbag1): Fixed wrong Storage capacity (made it botomless as per its description).
- Option 1: Use new, less cheesy items.
	- Cape of the Magi (wzrdrobe)
		- Removed useless Chain Contingency ability that did not do anything and was not described in identified description string.
		- Replaced missing description icon CCLCK02 with CCLCK01.
		- Replaced wrong GCLCK02 ground icon (robe) with GCLCK01 (cloak).
	- Ring of the Magi (wzrdring)
		- Added missing opcodes #267 (Text: Protection from Display Specific String) and #169 (Graphics: Immunity Special Effect Icon).
		- Added missing DS value: opcode #282 (Script: Scripting State Modifier): parameter1 = 1 - parameter2 = 2 [158 SCRIPTINGSTATE3 aka LEVEL_DRAIN_IMMUNITY].
		- Decided not to add opcode #142 Display portrait icon (90 : Negative Plane Protection).
	- Robe of the Magi (wzrdclck)
		- Fixed opcode #142 (Display portrait icon): replaced wrong 76 icon (Protected from the Elements) with 63 (Magic Resistance).
	- Amulet of the Magi (wzrdamul)
		- Replaced Protection from spell opcodes (#206) with full effects granting immunity to Petrification.
		- Removed all inaccurate opcodes #206 (Protection from Spell) protecting from Polymorph Other spells.
		- Removed useless #142 opcodes (Display portrait icon): 63 (Magic Resistance) and 70 (Protection from Normal Weapons).
		- Added DS values (176 LOCKPICKINGMTPBONUS = 176 WIZARD_PROTECTION_FROM_PETRIFICATION) for classical games and Set State PROTECTION_FROM_PETRIFICATION (107) for EE games.
	- Boots of the Magi (wzrdboot)
		- Fixed description string: same movement rate as Boots of Speed instead of "Movement rate increased by 50%", and replaced "Aura cleansed after each spell" with "Improved Alacrity one per day".
		- Fixed ability icon (SPWI921B) and replaced opocde #148 with opcode #146.
		- Appended tooltip.2da: Improved Alacrity.
	- Staff of the Magi (wzrdstaf)
		- Fixed wrong damages.
		- Modified opcode #20 (Invisibility) resistance: set to 3-Dispel/Bypass resistance.
		- Added missing opcode #296 Graphics: Protection from Specific Animation (SPNWCHRM).
		- Added opcodes #247 (Text: Protection from Display Specific String): 8364 (dominated), 14672 (charmed), 14780 (dire charmed).
		- Fixed opcode #142 (Graphics: Display Special Effect Icon) = replaces wrong parameter2 28 (Protection from Magic) with 52 (Mind Shield).
		- Removed ugly Protection drom Evil glowing colors: Glow Pulse [9] effect
		- Replaced Dispel magic effects with more accurate BG2 Fixpack ones.
		- Added DS values (117 PROTECTION_FROM_EVIL).
		- Fireball-Lightning ability: added Break Sanctuary flag for EE games.
		- Spel trap ability: replaced with STAF11.spl.
		- Added Glowing staff animation (and colors) for EE game or if 1PP is installed.
		- Appended tooltip.2da
	- Gauntlets of the Magi (wzrdbrac)
		- Updated description (was missing +1 Intelligence)
	- Circlet of the Magi (wzrdhelm)
		- Added circlet animation (and color) for EE game or if 1PP is installed.
		- Replaced Protection from spell opcodes (#206) with full effects granting immunity to Petrification.
	- Girdle of the Magi (wzrdbelt)
		- Added opcode #142 (Display portrait icon): 11 (Protection from Missiles).
		- Fixed wrong coding in opcodes #83: parameter1 and parameter2 were inverted.
		- Added Protection from missing projectiles if they exist in game: spear, 1arow01, 1bolt01, 1dagg05, 1dart01.
		- Added missing 25 % Magic resistance.
		- Added DS values (179 PICKPOCKETMTPBONUS = 179 WIZARD_PROTECTION_FROM_NORMAL_MISSILES) for classical games and Set State BUFF_PRO_WEAPONS (64) and PROTECTION_FROM_NORMAL_MISSILES (109) for EE games.
- Option 2: Use original, overpowered items.
	- Robe of the Magi (wzrdclck)
		- Added DS value #133 Stat: Proficiency (CLERIC_REGENERATION - 124).
		- Added DS value for EE games: Set State BUFF_PRO_DAMAGE (65).
	- Amulet of the Magi (wzrdamul)
		- Replaced Protection from spell opcodes (#206) with full effects granting immunity to Petrification.
		- Removed all inaccurate opcodes #206 (Protection from Spell) protecting from Polymorph Other spells.
		- Removed useless #142 opcodes (Display portrait icon): 63 (Magic Resistance) and 70 (Protection from Normal Weapons).
		- Added DS values (176 LOCKPICKINGMTPBONUS = 176 WIZARD_PROTECTION_FROM_PETRIFICATION) for classical games and Set State PROTECTION_FROM_PETRIFICATION (107) for EE games.
		- Added DS values (181 DETECTILLUSIONSMTPBONUS = 181 PROTECTION_FROM_NORMAL_WEAPONS) for classical games and Set State PROTECTION_FROM_NORMAL_WEAPONS (111) and BUFF_PRO_WEAPONS (64) for EE games.
	- Boots of the Magi (wzrdboot)
		- Added opcode #142 (Display portrait icon): 159 (Improved Alacrity).
		- Added DS value (#282 Scripting State Modifier): 165 WIZARD_IMPROVED_ALACRITY.
	- Gauntlets of the Magi (wzrdbrac)
		- Added DS value #133 Stat: Proficiency (CLERIC_REGENERATION - 124).
		- Added DS value for EE games: Set State BUFF_PRO_DAMAGE (65).
	- Circlet of the Magi (wzrdhelm)
		- Added circlet animation (and color) for EE game or if 1PP is installed.
		- Fixed Feeblemind Ability.
		- Feeblemind ability: added Break Sanctuary flag for EE games.
		- Appended tooltip.2da
	- Girdle of the Magi (wzrdbelt)
		- Removed useless ability header.
		- Added opcode #142 (Display portrait icon): 11 (Protection from Missiles).
		- Fixed wrong coding in opcodes #83: parameter1 and parameter2 were inverted.
		- Added Protection from missing projectiles if they exist in game: spear, 1arow01, 1bolt01, 1dagg05, 1dart01.
		- Added missing magic projectiles.
		- Added DS values (179 PICKPOCKETMTPBONUS = 179 WIZARD_PROTECTION_FROM_NORMAL_MISSILES) for classical games and Set State BUFF_PRO_WEAPONS (64) and PROTECTION_FROM_NORMAL_MISSILES (109) for EE games.
- Updated French translation.
- Updated English item descriptions to allow WeiDU to automatically remove usability restrictions for EE games.
- Renamed Setup-StuffofTheMagi.tp2 -> stuffofthemagi.tp2 to support ALIEN's "Project Infinity".
- Added stuffofthemagi.ini with mod info metadata to support ALIEN's "Project Infinity".
- Updated to Weidu 246.

## 

##### Version 5

- Added BG2EE compatibility. Thanks, Deratiseur! ( again :) )

## 

##### Version 4

- Apparently, a version of 1.3 had gotten out into the wild labeled v3. This should remove any doubt as to which version is latest.
- Fixed: original gauntlets gave +2 ninth level spells permanently. This was also in the nonweidu SOTM.
- Fixed: Unidentified cape had description of a belt. Oops.
- Added: French Translation! Thanks, Deratiseur!

## 

##### Version 2.4

- Fixed a bunch of bugs.

## 

##### Version 2

- Added balanced items, encounter in Pocket plane.

## 

##### Version 1.3

- Fixed the No wizard amulet from Demogorgon bug.

## 

##### Version 1.2

- Fixed the 2 staffs from Layene bug.

## 

##### Version 1.1

- Updated to WEIDU.
<div style="text-align:right"><a href="#top">Back to top</a></div>
