Welcome to QSouls2! (Quake 2 mod)

Common Deliverables:
(Done)	• Separate Project Folder
(Done)	• A README file describing how to play your mod
(Done)	• A shortcut that automatically launches your mod
(Done)	• User Interface updates to reflect the changes made to the game
  
Custom Deliverables:
(Done)	• Souls system
(Done)	• Upgrade system
(Part)	• Weapons:
	Melee
(Done)		> Caestus - fist weapon
(Prog)		> Greatsword of Artorias
	Bow
(Prog)		> Dragonslayer Greatbow
		
(Part)	• Weapon damage scale based on stats, (dex, str, etc)

===============| HOW TO PLAY |====================================================================================================
 	Qsouls 2 is meant to be used in singleplayer, but it is also functional in multiplayer, albiet without the hud elements.
This mod is meant to mimick From Software's game series, Dark Souls, and in order to do that, a souls-based rpg system 
has been implemented. In addition, the default weapon, the blaster, has been removed, and replaced with the Caestus, 
a melee weapon.
  
 There are 3 stats:
  	> Vitality  - Controls the player health, 1 VIT = 10 health
	> Strength  - Scales player damage, 1 STR = 10% of base attack value (DS weapons only)
	> Dexterity - Scales weapon attack speed, 1 DEX = ~10% of base attack speed (DS weapons only)
	
 Additionally, there are two values you need to know about:
	> Souls - The currency used for level-ups
	> Level - The player's level
	
 The stats are shown on the player's hud, on the bottom right corner. From bottom up, the values displayed are:
	> Souls
	> Vitality
	> Strength
	> Dexterity
	> Level
	
To level up open the console and type the command: 'levelup' followed by a space, followed by the stat you wish to level.
Type 'vit' for vitality, 'str' for strength, and 'dex' for Dexterity.
	e.g. 'levelup vit'
In case you feel like cheating, there is a command to give souls (30) to the player.
	> 'givesouls'
