# :: CHANGELOG ::

## :: Version 1.1.3

### Changes:

- Updated starter saves - Starter Eridian Blaster now has a scope.
- All legendary Eridian weapons with special blades provide +500% melee damage bonus.
- Intercessor now deals pure normal damage.
- Removed damage penalty on Peacekeeper's scoped firing mode.
- Removed increased shot cost for Perforator.
- Removed fire rate bonus and clip penalty on Pocket Assassin. Added single fire burst on non scoped shots.
- Removed clip size and damage bonus on Rainbow.
- Reworked Binary Cannon - now it fires slower, but deals more damage.
- Reduced recoil on Spinner SMGs by 80%.
- Updated Wave Machineguns bullet particles. Increased tech level by +3. Increased damage by +30%.
- Decreased Flinger's cooldown delay by 50%.
- Updated elemental effect texts for Rainbow.
- Updated red text of Focus.
- Updated red text of X-Ray.
- Added a tooltip 'Penetrates enemies' to weapons that do so.
- Infinity now penetrates enemies.
- Locust and Bloodsucker buzz sound should no longer spam when projectile gets stuck.
- Reworked Firestorm - Added working tech proc system, x3 and x4 procs deal more damage. Reduced damage by -30%, reduced tech pool by 6.
- Blade Rifles, Disc Blasters, Pocket Assassin and Impaler now have a chance to apply status effects with their projectiles.
- Impaler now leaves blade stuck into enemy for a few seconds.
- Reworked Corruptor - Doubled melee damage spread range, reduced melee status effect damage per second by -35%. Increased damage by +30%, clip size by +35% and tech level by +3. Now launches grenades when scoped.
- Updated Reverser's bullet particles.

### Bug Fixes:

- Fixed a bug which caused Action4_Fusion for Carbines to slow down bullets instead of speeding them up.
- Fixed a bug which caused Perforator do wrong procs on x3 and x4.
- Fixed a bug which caused rare variations of Eridian SMGs be not affected by awesome level,
 which caused them to drop very rarely. Duplex, Spinner and Mangler SMGs should drop more often now.

## :: Version 1.1.2

### Changes:

- Reworked Vanguard - It fires now one more bullet per shot. Removed damage bonus. Updated bullet and explosion particles.
- Reworked Accelerator - Increased damage by +500%, reduced fire rate by -50%, and added huge knockback (+10000%).
- Reworked Stampending Spatter Gun - Projectiles now behave more lively, and their behaviour looks more like a stampede.
- Reworked Plasma Cutter - Now fires 3 projectiles instead of 5, updated firing pattern making bullets spawn more thightly, increased damage by 100%, updated bullet particles.
- Increased Gun Action1_Torpor damage by +50%.
- Increased Carbine Action2_Maverick damage by +100%.
- Increased Carbine Action4_Fusion damage by +50%.
- Reduced Surge's damage by -20%.
- Increased Laser Shotgun scoped firing mode damage by +50%.
- Increased base damage of all Eridian Blasters by +20%.
- Increased Fiery Flower's damage by +100%.
- Removed Thunderstorm's increased projectile shot cost, and increased accuracy by +30%.
- Reduced Exactor's tech proc cost.
- Reduced Ember's accuracy by -30%.
- Reduced Tormentor's damage by -30%.
- Increased Devourer's damage by +50%, it should be more reliable as a shotgun if you can hit sweet spot.
- Eridian Lightning now has bigger explosions.
- Updated Eridian Lightning explosion particles.
- Reduced grenade ammo regen rate that Eridian grenades provide from 6.4 grenades per minute to 3.2 grenades per minute.

### Bug Fixes:

- Fixed a bug where Mordecai's starter sniper rifle weapon would spawn with level 48.
- Fixed a bug where corrosive Sharpshooter would penetrate enemies.
- Fixed Desolator projectiles not properly playing sounds.
- Fixed a bug where Reverser bounce bullet was spawning 3 bullets instead of 1.
- Fixed a bug where Corruptor's melee status effect was not applying right damage.

## :: Version 1.1.11

### Changes:

- Reduced Forgotten Eridian Ruins portal spawn chance from 0.1% to 0.01%.

## :: Version 1.1.1

### Changes:

- Forgotten Eridian Ruins shop now scales to player's level.
- Updated font on Forgotten Eridian Ruins map card.
- Updated Forgotten Eridian Ruins portal spawning particle, now it should be more noticeable.
- Forgotten Eridian Ruins portal now auto saves player's progress when approached.
- Reduced sound volume on Acid Storm's explosions.

### Bug Fixes:

- Fixed awesome level for Eridian shop, now item of the day has greatly increased awesome level instead of normal items.

## :: Version 1.1.0

### New stuff:

- Added Eridian grenade mods:
	- There are 11 new grenade mods in total, 4 legendary and 1 pearlescent.
	- All Eridian grenade mods slowly regenerate grenades over time.
	- Some grenade mods cost more than 1 grenade ammo per throw.

- Enemies now have a small chance (roughly 0.1%) of spawning a Portal that will take player to Forgotten Eridian Ruins map.
	- Portal is single use, if you want to revisit the shop you will need to get another portal to spawn.
	- Map contains Eridian vendor with high awesome level (meaning weapons will more likely spawn with better parts).
	- Item of the day is guaranteed to be a legendary (with also decent chance for pearlescent).
	
### Changes:

- Updated weapon binary prefix name generation system - first 3 numbers represent weapon's body number, and remaining numbers represent weapon's magazine number.
- Marker:
	- Now has laser firing mode when scoped.
	- Slighly increased tech pool.
- Updated Flamefury's bullet particles.
- Updated Locust's explosion particles.
- Updated Maelstorm's bullet particles.
- Updated Delirium's melee particle.
- Updated Caladbolg's melee particle.
- Illuminator:
	- Added fire whoosh sound to melee attack.
	- Updated melee particle.
- Corruptor:
	- Added corrosive sizzle sound to melee attack.
	- Updated spreading explosion sound.
	- Updated spreading explosion particle.
	- Updated bullet particle.
	- Updated melee particle.
- Added screen particles if player is hit by Blade (both for projectile, and melee slash).
- Added screen particles if player is hit by Disc projectile.

### Bug Fixes:

- Fixed Illuminator burn duration.
- Fixed broken normal map texture for body6 and various other model6 parts.
- Fixed Corrosive Laser sometimes procing normal bullets when using normal firing mode.

## :: Version 1.0.3

### Changes:

- Added Big Bang's pull damage variation. Now it deals between 0.1% and 0.2% of total weapon damage.
- Increased overall damage done by Scatterguns by 20%.
- Reduced damage of Repulser by 30%
- Reduced damage of Fire Storm by 20%
- Increased Mega Blaster MKII's damage by 10%.
- Updated red text for Focus and Perforator.
- Increased accuracy on Extender's scoped shot.
- Increased damage of Ray's bounced bullet by 30% to reward trick shots.
- Reworked Beams to differentiate them from Rays - now they penetrate targets instead of bouncing of surfaces.
- Removed Polytehnitis Tech level boost, and decreased burst fire to 1 shot.
- Changed Material 3 prefix from Refined to Stellar.
- Removed increased shot cost from Warped Action part.
- Reduced shot cost of Lightning.
- Added gd_globals.INT file to mod files. This file changes the font size of item description, so it allows to fit more information on item card.

### Bug Fixes:

- Fixed a bug that prevented normal damage Eridian weapons to benefit from explosive damage boosts.
- Fixed a bug what caused Corrosive Spread Cannons to shoot energy rockets.
- Fixed Devastator's spawned projectiles to sometimes explode right after they spawned.
- Fixed a typo in Duality's red text
- Fixed a bug where Delirium could spawn with Bladed Action part.
- Fixed a bug where Supernova was doing ridiculous amount of damage.

## :: Version 1.0.2

### Changes:

- Increased Big Bang's recharge rate.
- Changed Vanquisher's accuracy bonus to apply only when scoped. Reduced cooldown delay and shot cost by 50%. Increased fire rate by 50%.
- Increased damage of Flaregun by 85%.
- Added constraint to Extender accessory, now it should spawn only on inaccurate Scatterguns.
- Increased size of particle for Rainbow's explosive proc to be on par with other elements.
- Updated particle of Shock Interceptor projectile.
- Slightly optimized Eridian_Weapons_Overhaul_Materials.upk file so it weights less.
- Added normal map to swirly lines on high tier materials, now they should have more depth.
- Increased density of swirly lines on Trinity's material.
- Added Disc projectile damage variation +/-10% after it attaches to enemy.

### Bug Fixes:

- Fixed weapon part rarity issue with high quality parts, there should be no more normal weapons of legendary rarity, and legendary weapons of pearlesecent rarity. Also this should cause to spawn way less purple rarity weapons on endgame.
- Fixed bug with Shock Interceptor spawning wrong shock explosion upon direct hit.
- Added missing UE3ShaderCompileWorker.exe file from Dr. Zed's patch to mod files. Lack of this file was rarely causing crashes upon loading save with Eridian weapons equipped.

## :: Version 1.0.1

### Changes:

- Updated scope-in animations for Blasters and Shooters.
- Updated Phasers to use revolver firing animations.
- Reduced Flinger grenade shot cost by 25%
- Increased damage of Blade projectile by 150%, and reduced fire rate by 45%
- Increased damage of Impaler by 30%, and critical hit damage by 100%
- Doubled lifetime on Recharger's shield restoring projectiles
- Changed Mysterious Artifact inventory category from Insta Health to Elemental Artifact
- Sticky Lobber projectiles now detonate upon contact with enemy, but will still stick to surfaces.
- Dusty material will stop spawning on weapons after certain level.
- Added 6th tier of scope to all weapon types.
- Increased Extender scoped shot range before splitting.
- Increased Torpor damage by 60%
- Eridian Lasers and Eridian Blade rifles are slightly more rare.

### Bug Fixes:

- Fixed bug where Sticky Lobber direct hit didn't grant extra damage.
- Fixed X-Ray not penetrating targets.
- Fixed issue with Impaler, where barrel was granting increased cooldown delay instead of decrased cooldown delay.
- Fixed issue where Disc title could get overriden by other titles.
