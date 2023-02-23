![Eridian Weapons Overhaul](https://user-images.githubusercontent.com/26903692/220933230-54cdbd34-0a90-4d53-95d6-d2361e3445e0.png)

# ERIDIAN WEAPONS OVERHAUL

### ***WARNING! THIS MOD DOES NOT WORK ON ENHANCED VERSION OF BORDERLANDS.***

Eridian Weapons Overhaul mod completely changes Eridian Weapons gameplay experience. 

I really love idea of alien guns in Borderlands, but it was really poorly executed.

This is the mod that lets you experience Eridian Weapons in their full glory!

## What exactly is wrong with vanilla Eridian weapons?

- They slow you down by 20% when equiped
- They have really small ammo pool
- They take ages to recharge (even when you max out proficiencies)
- Their scopes don’t provide any zoom
- They don’t have any part diversity
- They don't use tech pool
- Their code is broken. For example all corrosive Eridian guns from DLC3 deal exactly 0 damage due to wrong damage scalling. All damage you see is Corrosive DOT damage.
- They are treated like legendary weapons – being very rare, but they are not that great (with exception of Thunderstorm).

## MOD FEATURES

All problems mentioned above are fixed. Eridian Weapons Overhaul introduces custom part generation system made from scratch.
This system allows to generate even more guns than vanilla weapon generator, including all rarity colors from white to pearlecent.

This mod features **`12 weapon types`**, **`48 Eridian Legendary weapons`** and **`12 Eridian Pearlescent weapons`**.

With version 1.1.0 Eridian Weapons Overhaul introduced **`11 new grenade mods in total`**, **`14 legendary`** and 1 **`pearlescent`**.

### Changes to how Eridian Weapons look and behave:

- Magazines now display elemental color of the weapon
- Eridian Weapons now have 5 tier materials. Credit to Tha Campin Dutchman for help with material
- Weapons now have custom muzzle flash particles for each element (Sniper Rifles have special particle for their unique barrel).
- On screen scope particles also match the weapon elemental type
- All weapon types can spawn with elemental blade.
- Weapons that use projectiles (Cannons, Lobbers etc.) deal additional damage when scoring direct hit, and they are capable of scoring critical hits.
- They are using pistol animations for small sidearms like Blasters, and revolver animations for Phasers.

### Few words about biggest issue vanilla Eridian Weapons have - recharge delay, and recharge rate:

Recharge rate is now almost instant.
Recharge delay is now roughly the same like reload time of the same normal weapon type.
For example normal repeater pistol by default takes 2 seconds to reload, so Eridian Blaster has default 2 second delay before recharging.
This time is shortened by better quality parts.
There is also a bonus - if you don't use all ammo weapon will recharge 25% faster

All Eridian weapons are elemental. They come in 4 elements:

- Incendiary
- Corrosive
- Shock
- Energy

Energy weapons work exactly like explosive weapons, except they deal normal damage instead of explosive.
Sadly weapon card still displays explosive element, because elemental icons are hardcoded.
These weapons _`do benefit`_ from any skills/classmods that increase explosive damage.

### All Eridian weapons have dual proficiencies. What does that mean?

When for example you are using Eridian Sniper Rifle you will level up both Eridian proficiency and Sniper Rifle proficiency.
You also benefit from both proficiency bonuses.
This also applies to skills and classmods. For example Roland's Scattershot skill will increase damage and accuracy of Eridian Shotguns.

### Eridian Grenade Mods

All Eridian Grenade Mods slowly regenerate grenade ammo with **`3.2 grenades`** per minute rate.
Some grenade mods cost more than 1 grenade ammo to use.

### There are 4 starting saves included as optional file.

They allow you to do a full Eridian only playthrough!

- Save0036.sav - Roland
- Save0037.sav - Mordecai
- Save0038.sav - Brick
- Save0039.sav - Lilith

Roland starts with Eridian Rifle and Eridian Blaster.
Mordecai starts with Eridian Sharpshooter and Eridian Blaster.
Brick starts with Eridian Shotgun and Eridian Blaster.
Lilith starts with Eridian Gun and Eridian Blaster.

Each save contains Mysterious Eridian Artifact item.
Use it to enable enemies to have a chance to drop Eridian items.
You have to use it each time you load a save.

## INSTALLATION

This mod includes Dr.Zed Path.

Place all **`.upk`** files to:
```
<YourSteamDirectory>\SteamLibrary\steamapps\common\Borderlands\WillowGame\CookedPC
```
Place **`UE3ShaderCompileWorker.exe`** file to:
```
<YourSteamDirectory>\SteamLibrary\steamapps\common\Borderlands\Binaries
```
Place **`gd_globals.INT`** file to:
```
<YourSteamDirectory>\SteamLibrary\steamapps\common\Borderlands\WillowGame\Localization\INT
```
In case of optional starter saves place them to:
```
C:\Users\<username>\Documents\my games\borderlands\savedata
```
## MYSTERIOUS ERIDIAN ARTIFACT

This item allows enemies to drop Eridian Loot.
If you want to start looting Eridian Weapons with your exisiting save you need to add Mysterious Eridian Artifact via WillowTree.﻿
It works exactly like vials from The Arsenal mod.
You need to activate it once from your inventory like a health kit, when activated it plays distinct sound.
If everything works correctly all killed enemies should show vault symbol particle.

Credit to Tha Campin Dutchman for his vial system.

WillowTree code:
```
Eridian_Weapons_Overhaul.A_Spawner.Grade.ItemGrade_Eridian_Mysterious_Artifact
Eridian_Weapons_Overhaul.A_Spawner.A_Item.Item_Mysterious_Artifact
None
None
None
None
gd_manufacturers.Manufacturers.Eridian
Eridian_Weapons_Overhaul.A_Spawner.Prefix.Prefix_Mysterious
Eridian_Weapons_Overhaul.A_Spawner.Title.TitleP_Eridian_Artifact
9999999
5
0
0
```
## WHAT ARE THE CHANCES OF GETTING ERIDIAN LOOT

Afer activating Mysterious Eridian Artifact enemies have **`4% chance`** to drop a weapon.

Then when you get a drop you have:

**`0.5% chance`** of drop to be a **Legendary**.
**`0.1% chance`** of drop to be a **Pearlescent**. 

## FORGOTTEN ERIDIAN RUINS PORTAL

Enemies have a small chance (roughly **`0.01%`**) of spawning a Portal that will take player to **Forgotten Eridian Ruins** map.

- Portal is single use, if you want to revisit the shop you will need to get another portal to spawn.
- Portal has a build in checkpoint that should save your progress.
- Map contains Eridian vendor with high awesome level (meaning weapons will more likely spawn with better parts).
- Item of the day is guaranteed to be a legendary (with also decent chance for pearlescent).
- After exiting the map, make sure to reactivate **Mysterious Eridian Artifact**, because teleporting to the map disables it.

## ERIDIAN WEAPONS OVERHAUL AND THE ARSENAL

These mods are compatible, as long as you have both mods installed.
Use vial to spawn loot both from **The Arsenal** and **Eridian Weapons Overhaul**.
Vials and Mysterious Eridian Artifact _`do not`_ stack, if you use vial you won't be able to activate artifact and vice versa.

## ERIDIAN GUN NAMES TRANSLATION

- **Eridian Blaster** - Repeater Pistol
- **Eridian Shooter** - Machine Pistol
- **Eridian Phaser** - Revolver
- **Eridian Shotgun** - Assault Shotgun
- **Eridian Scattergun** - Combat Shotgun
- **Eridian Sharpshooter** - Sniper Rifle
- **Eridian Sniper Rifle** - Semi-Auto Sniper Rifle
- **Eridian Rifle** - Support Machinegun
- **Eridian Carbine** - Combat Rifle
- **Eridian Gun** - SMG
- **Eridian Cannon** - Rocket Launcher
- **Eridian Lobber** - Grenade Launcher
