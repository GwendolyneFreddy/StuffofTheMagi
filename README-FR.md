# <a name="top" id="top"></a>L'Arsenal du mage (WIP)

<strong>Auteur original :</strong> Victor Straffe<br />
<strong>Version :</strong> 6.0.0<br />
<strong>Langues :</strong> <a href="README.md">anglais</a>, fran�ais<br />
<strong>Platforme :</strong> Windows

<strong>Site et forum du mod :</strong> <a href="http://www.shsforums.net/topic/34134-stuff-of-the-magi/">Spellhold Studios</a></p>


<center><a href="#intro">Pr�sentation</a> &#x2B25; <a href="#compat">Compatibilit�</a> &#x2B25; <a href="#installation">Installation</a> &#x2B25; <a href="#components">Composants</a> &#x2B25; <a href="#credits">Cr�dits</a> &#x2B25; <a href="#versions">Historique des versions</a></center></br></br>


<hr>


## <a name="intro" id="intro"></a>Pr�sentation

Ce mod ajoute l'arsenal du mage dans l'inventaire des cr�atures suivantes :
- Robe : Vongoethe
- Amulette : D�mogorgon
- Bottes : Kangaxx (une demiliche sans corps avec des bottes ? remarque, elle porte bien un anneau :confused:)
- B�ton : Layene � la Rune Tordue
- Bracelets : Firkraag
- Bandeau : Sendai
- Ceinture : M�re matrone Ardulace
- Cape : Temple de Rillifane dans Suldanessellar
- Anneau : Lavok


Si vous poss�dez tous les objets, celui qui les porte tous obtient un bonus exceptionnel, et vous rencontrerez quelqu'un qui voudra vous parler dans l'antichambre....

Note du traducteur : Si vous choisissez les objets "surpuissants", vous n'en aurez que 7 (pas de cape, ni d'anneau).

<strong>N'oubliez jamais :</strong> Ce mod a �t� con�u et publi� par Victor Straff sur le site Sorcerer's Place.


<hr>


## <a name="compat" id="compat"></a>Compatibilit�

Ce mod est con�u pour fonctionner sur les jeux Infinity Engine suivants : le jeu original Baldur's Gate II (Les Ombres d'Amn : BG2-SoA) avec son extension Tr�ne de Bhaal (Throne of Bhaal : ToB), Baldur's Gate II: Enhanced Edition (BG2EE), les mods de conversion Baldur's Gate Trilogy (BGT) et Enhanced Edition Trilogy (EET).

C'est un mod <acronym title="Weimer Dialogue Utility">WeiDU</acronym> et devrait par cons�quent �tre compatible avec n'importe quel mod WeiDU. Si vous rencontrez des bugs, veuillez les signaler dans le forum, s'il vous pla�t.<br>
<div style="text-align:right"><a href="#top">Haut de page</a></div>


<hr>


## <a name="installation" id="installation"></a>Installation

#### Mise en garde

<em>Si une ancienne version de ce mod est d�j� install�e, il est n�cessaire de la d�sinstaller d'abord. Pour cela, lancez <strong>setup-stuffofthemagi.exe</strong> et d�sinstallez le composant principal pr�c�demment install�. Une fois la d�sinstallation achev�e, supprimez le r�pertoire stuffofthemagi.</em>

<em>Lorsque vous installez ou d�sinstallez, <strong>ne fermez pas la fen�tre <acronym title="Disk Operating System">DOS</acronym></strong> en cliquant sur le bouton <strong>X</strong> ! Au lieu de cela, appuyez sur la touche <strong>Entr�e</strong> lorsque l'invite de commandes vous le demande.</em>

Par pr�caution, <strong>d�sactivez les antivirus</strong> ou tout logiciel r�sidant en m�moire avant d'installer ce mod, ou tout autre mod. Certains (en particulier avast et Norton !) ont une f�cheuse tendance � d�clarer les ex�cutables des mods comme des faux positifs, provoquant ainsi l'�chec de la proc�dure d'installation.

## 

#### Note pour les jeux en �dition Am�lior�e (EE)

Les �ditions am�lior�es sont des jeux que le d�veloppeur fait encore �voluer, notamment par l'ajout de capacit�s suppl�mentaires destin�es � la cr�ation de mods et par l'ajout de contenus. N'oubliez pas que chaque patch de mise � jour effacera les mods que vous avez install�s ! Ce mod ne fera pas exception � la r�gle.

Si vous pouvez retarder la mise � jour du patch en plein milieu d'un partie modd�e (si vous en avez la possibilit�, notamment chez Beamdog et Good Old Games), n'oubliez pas que m�me apr�s avoir r�install� les mods sur un nouveau patch, vous ne pourrez peut-�tre pas continuer le jeu avec vos anciennes sauvegardes, en particulier � cause de noms de personnages, de lieux, etc, qui pourraient �tre incorrects. Pour y rem�dier, copiez tout le dossier du jeu dans un nouveau dossier dans lequel vous installerez vos mods, et qui ne sera pas modifi� par les patches de mise � jour. Il est important que vous installiez le mod dans la version linguistique dans laquelle vous jouez. Sinon, les dialogues du mod ne s'afficheront pas et provoqueront des messages d'erreur.

## 

#### <a name="config" id="config">:warning: Avertissement : nouvelle proc�dure d'installation

##### � partir de la version 6.0.0, les variables n�cessaires � l'installation sont lues dans le fichier <a href="https://raw.githubusercontent.com/GwendolyneFreddy/StuffOfTheMagi/master/stuffofthemagi/stuffofthemagi.ini"><em>stuffofthemagi.ini</em></a>, ou dans le fichier <em>stuffofthemagi_user.ini</em>, si ce dernier existe.

Pour �viter d'interrompre la proc�dure d'installation par de nombreux messages vous permettant de personnaliser certains composants � votre convenance, ces choix d'options ne sont plus d�termin�es par la proc�dure d'installation, mais ont �t� externalis�s dans le fichier <a href="https://raw.githubusercontent.com/GwendolyneFreddy/StuffOfTheMagi/master/stuffofthemagi/stuffofthemagi.ini"><em>stuffofthemagi.ini</a> situ� dans le r�pertoire <strong>stuffofthemagi</strong>. Ce fichier d�finit une installation � <em>standard</em> �.

Si vous souhaitez choisir d'autres options d'installation, il vous suffit de modifier, avec Notepad ou un autre �diteur de texte, les options de configuration de la section <strong><em>[Mod_content]</em></strong> dans le fichier <strong><em>stuffofthemagi.ini</em></strong>, puis de sauvegarder ce dernier sous le nom <strong><em>stuffofthemagi_user.ini</em></strong>.

Chaque ligne de ce fichier comprend une option de configuration, suivie de � = �, puis d'un chiffre. Tout ce que vous avez � faire, c'est modifier la valeur du chiffre.

Le programme d'installation lira les valeurs des variables dans les deux fichiers ini et donnera la priorit� aux v�tres. Si le fichier stuffofthemagi_user.ini contient une variable non conforme, ou si une variable est manquante, il la remplacera par sa valeur par d�faut (celle correspondant � l'installation � <em>standard</em> �).</br>

Voici le tableau des variables concern�es (ne modifiez pas les variables non list�es ; elle font partie de l'architecture de debugging et de test) :<br>

| Variable | Signification de l'option d'installation | Type | Valeurs | D�faut |
| :---: | --- | :---: | :---: | :---: |
| sotm_use | Puissance des objets<br> 1 = Utiliser les nouveaux objets, moins grobillesques (recommand�).<br>2 = Utiliser les objets originaux, surpuissants (pas de cape ni d'anneau dans ce cas).<br> | num�rique | 1 ou 2 | <strong>1<strong> |
| sotm_equip | O� trouver les objets<br>1 = Ajouter les objets � l'equipement des cr�atures (recommand�, les ennemis les utiliseront contre vous)<br>2 = Ajouter les objets � l'inventaire des cr�atures (ne change en rien la difficult� des combats).<br> | num�rique | 1 ou 2 | <strong>1<strong> |

## 

#### Windows

Vous devez extraire les fichiers de l'archive dans votre r�pertoire de jeu (<em>le dossier qui contient le fichier CHITIN.KEY</em>) � l'aide de <a href="http://www.7-zip.org/download.html">7zip</a>, de <a href="http://www.rarlab.com/download.htm">WinRAR</a> ou de tout autre utilitaire de compression g�rant les fichiers zip. Une fois l'archive extraite correctement, vous devriez trouver le r�pertoire stuffofthemagi et le fichier setup-stuffofthemagi.exe dans votre r�pertoire de jeu. Pour installer le mod, il suffit de double-cliquer sur <strong>setup-stuffofthemagi.exe</strong> et de suivre les instructions affich�es � l'�cran.

Vous pouvez lancer <strong>setup-stuffofthemagi.exe</strong> dans votre r�pertoire de jeu pour r�installer, d�sinstaller, ou encore modifier les param�tres du composant.

##

#### Note pour effectuer une d�sinstallation compl�te

En plus des m�thodes d�taill�es plus haut pour supprimer des composants, il est possible de d�sinstaller compl�tement le mod en tapant <strong>setup-stuffofthemagi --uninstall</strong> dans une ligne de commandes, ce qui supprimera tous les composants sans devoir ingurgiter tous les messages.</br>
<div style="text-align:right"><a href="#top">Haut de page</a></div>


<hr>


## <a name="components" id="components"></a>Composants

Le programme d'installation ne comprend qu'un seul composant, le composant principal.
<div style="text-align:right"><a href="#top">Haut de page</a></div>


<hr>


## <a name="credits" id="credits"></a>Cr�dits et remerciements

#### Auteur : Victor Straffe (sur le site Sorcerer's Place)


#### Remerciements (par ordre alphab�tique):

- Cmorgan : Help with bugs-quishing/tidiness/etc.
- Deratiseur : Made it compatible with translations, wrote the French translation, and provided the EE compatible version.
- Gwendolyne : Fixed French translation and released version 6.0.0
- Kevmus : Updated the mod to WeiDU, added the more balanced items, and fixed bugs.
- Rastamage : Item stories/Erevain's talk.
- Tassadar88 : Help with coding.
- Anastasya Zakharova : <a href="https://www.artstation.com/artwork/AznzX">Matatel portrait</a> for Erevain Berask�na.

Si vous avez une suggestion, ou si vous rencontrez un bogue, veuillez en informer les mainteneurs dans le <a href="http://www.shsforums.net/topic/34134-stuff-of-the-magi/">forum du mod</a>.</br>
<div style="text-align:right"><a href="#top">Haut de page</a></div>


<hr>


## <a name="versions" id="versions"></a>Historique des versions

Note du traducteur : l'historique n'est volontairement pas traduit afin de faciliter la mise � jour continue du mod.

##### Version 6.0.0 - Month day, 2019

- Major updates:
	- Renamed Setup-StuffofTheMagi.tp2 -> stuffofthemagi.tp2 to support AL|EN's "Project Infinity".
	- Installation options have been moved into stuffofthemagi.ini file and replaced READLN actions to support AL|EN's "Project Infinity".
	- Reorganized mod architecture tree: created lib and readme folders, renamed script and language folders as baf and lang folders.
	- Removed unnecessary or unused files : wzrdlic2.baf, wzrdlichold.cre and wzrdbag.itm.
	- Split setup.tra file into separate thematic files for more comfortable readability.
	- Provided compatibility with 1PP and TobEx.
	- Added Detectable Spells variables.
	- Appended items (wzrdboot, wzrdhelm and wzrdstaf) to tooltip.2da file.
	- Provided a portrait to Erevain Berask�na.
	- Fixed an installation issue preventing the player wearing whole Stuff of the Magi set to gain an extra bonus if Option 2 (Use original, overpowered items) was selected.
	- Fixed remaining glitches and bugs.
	- Hard-coded item unidentified names and descriptions in .itm files to avoid writing them in installation process.
	- Updated English item descriptions for compatibility with GW_UPDATE_ITM_DESCRIPTION_TO_EE WeiDU function requirements which automatically removes usability restrictions for EE games.
	- Added stuffofthemagi.ini metadata file to support AL|EN's "Project Infinity".
- Scroll Case (wzrdbag1): Fixed wrong Storage capacity (made it bottomless as per its description) and fixed a typo and wrong scroll code (was adding 2 scrolls of Freedom instead of 1 Freedom and 1 Imprisonment).
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
		- Fixed wrong weight (3 replaces 2).
	- Amulet of the Magi (wzrdamul)
		- Replaced Protection from spell opcodes (#206) with full effects granting immunity to Petrification.
		- Removed all inaccurate opcodes #206 (Protection from Spell) protecting from Polymorph Other spells.
		- Removed useless #142 opcodes (Display portrait icon): 63 (Magic Resistance) and 70 (Protection from Normal Weapons).
		- Added DS values (176 LOCKPICKINGMTPBONUS = 176 WIZARD_PROTECTION_FROM_PETRIFICATION) for classical games and Set State PROTECTION_FROM_PETRIFICATION (107) for EE games.
	- Boots of the Magi (wzrdboot)
		- Fixed description string: same movement rate as Boots of Speed instead of "Movement rate increased by 50%", and replaced "Aura cleansed after each spell" with "Improved Alacrity one per day".
		- Fixed ability icon (SPWI921B) and replaced opcode #148 with opcode #146.
		- Appended tooltip.2da: Improved Alacrity.
	- Staff of the Magi (wzrdstaf)
		- Fixed wrong damages.
		- Modified opcode #20 (Invisibility) resistance: set to 3-Dispel/Bypass resistance.
		- Added missing opcode #296 Graphics: Protection from Specific Animation (SPNWCHRM).
		- Added opcodes #247 (Text: Protection from Display Specific String): 8364 (dominated), 14672 (charmed), 14780 (dire charmed).
		- Fixed opcode #142 (Graphics: Display Special Effect Icon) = replaces wrong parameter2 28 (Protection from Magic) with 52 (Mind Shield).
		- Removed ugly Protection from Evil glowing colors: Glow Pulse [9] effect
		- Replaced Dispel magic effects with more accurate BG2 Fixpack ones.
		- Added DS values (117 PROTECTION_FROM_EVIL).
		- Fireball-Lightning ability: added Break Sanctuary flag for EE games.
		- Spell trap ability: replaced with STAF11.spl.
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
		- Fixed wrong weight (3 replaces 2).
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
- Updated readmes.
- Updated French translation (Gwendolyne).
- Updated WeiDU installer to v246.

## 

##### Version 5

- Added BG2EE compatibility. Thanks, Deratiseur! ( again :) )
- Removed unnecessary backup folder.

## 

##### Version 4

- Apparently, a version of 1.3 had gotten out into the wild labeled v3. This should remove any doubt as to which version is latest.
- Fixed: original gauntlets gave +2 ninth level spells permanently. This was also in the non-WeiDU SOTM.
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

- Updated to WeiDU.
<div style="text-align:right"><a href="#top">Haut de page</a></div>
