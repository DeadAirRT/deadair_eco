# DeadAir Eco
## Dynamic Universe
Minimalized diff mod for economy changes in X4. Readme is often out of date on features or numbers so feel free to contact me on the Egosoft Discord or check patch notes on pushes.
## AiScripts\Build.Shiptrader.xml
- Added chance for player to get rookies or veterans on hiring.
- Increased amount of ships assigned to trade for NPC shipyards and wharves.
- Added logic for traders to be assigned to Xenon shipyards.
## Structure Macro Changes
- Doubled capacity of drones for build modules to prevent AI from having too few drones to build ships at full speed.
- Increased Terran habitation modules to have same worker capacity as other factions.
- Updated threatscore for several xenon modules.
## Map Changes
- Added asteroid fields to cluster 403, 406
- Added gas field to cluster 403, 406
## Libaries\Baskets.xml
- Adjusted wares in baskets used by AI.
## Libraries\Constructionplans.xml
- Replaced 1M6S dock modules at important stations with 3M6S modules to improve ship docking capacity.
## Libaries\Defaults.xml
- Adjusted threatscore for different ships and increased station threatscore.
## Libaries\God.xml
- Increases allowed stations per zone to accomodate higher density.
- Removes Argon and Paranid stations from Split DLC sectors so they stop wasting resources and CPU cycles.
- Removes several quotas that cause smaller stations but does not change total production module count.
## Libraries\Jobs.xml
- Adjusted baskets used by traders to improve trader efficiency.
- Adjusted trade ships to use traderoutine instead of distributewares aiscript so they will actually respond to trade imbalances on demand side instead of supply side.
- Added jobs for silicon mining and ore mining for Xenon.
- Added missing water trader jobs for Antigone.
## Libraries\Loadoutrules.xml
- Increased weighting values for imprortant drones (transport drones for traders and build drones for construction ships).
- Attempted to reduce NPC ships loading up on deployables that serve no purpose other than to tank the economy.
## Libraries\mapdefaults.xml
- Adjusts sector economy ratings to remove undocumented effect on station size generation.
## Libraries\Modulegroups.xml
- Added new groups for Advanced Schematics, Military Schematics, and Labor Union Contracts.
## Libraries\Modules.xml
- Increased amount of modules that NPC are allowed to build on a single station. This greatly reduces the number of stations required for a functional economy.
## Libraries\Parameters.xml
- Increased amount of modules that NPC are allowed to build on a single station.
- Increased default level of drone loadout to prevent ships without enough drones to function effectively.
## Libraries\People.xml
- Increased fill percentage of certain NPC crews.
- Ships with Regular crews will have 50%+ of the ships capacity.
- Ships with Veteran crews will have 75%+ of the ships capacity.
- Ships with Elite crews will have 90%+ of the ships capacity.
- The higher importance the ship is to the faction, the higher the amount and ability of the crew.
## Libaries\Region_Definitions.xml
- Increased resource yields of several areas that are vital to the factions economic stability.
## Libaries\Regionyields.xml
- Reduced the replenish time of all resource areas. Areas that have low or worse density will replenish over 180 minutes. Areas with higher density will replenish over longer time periods.
## Libraries\Ships.xml
- Adjusted the crews used by different ships.
## Libraries\Wares.xml
- Adjusts ware pricing to balance credits / m3 so traders will be rewarded for prioritizing shipping needed resources.
- Adjusts ware production cycles to standard increments. Scales required resources to match ratio from vanilla (Station calculator will still be accurate for ratio of modules not including workforce).
- Adjusts workforce effects to be more pronounced. This allows fewer stations for increased performance and increases the importance of food and medical supplies to a healthy economy.
- Adds three new types of wares (Advanced Schematics, Military Schematics, and Labor Union Contracts). These are using placeholder station modules for now. The wares are secondary resources that stations can use to double production amount and are produced in modules. The modules produce a very small amount without workforce but have the highest workforce impact of any wares in the game.
- The amount of secondary resources required at each station is balanced based on ware type and potential profit of the production cycles.
- Adds a separate production method of energy cells for Xenon with values balanced for lack of workforce.
- Reduces construction time of modules so that the majority of the wait is for resources.
- Removes hullparts from station construction resources. This reduces the chance of a hull part shortage from building ships causing an entire economy to seize. Amount of claytronics and energy cells increased to match pre-change average credit cost.
## Md\Factionlogic_economy.xml
- Stations built after game start by NPC will have more modules.
## Md\Factionlogic_stations.xml
- Reduced desired wharves for Argon, Paranid, and Split to 1.
## Md\Finalisestations.xml
- Nudges station generation to use more horizontal connections than vertical.
- Increases station desired storage capacity to at least 2Mil M3 container and/or 1Mil M3 solid/liquid.
## Md\Inituniverse.xml
- Added several ship production wares to tradestations.
- Reduces rng for station initial fill.
## Dependencies
- No mod dependencies at this time.
- Requires Split, Terran, Pirate, and Boron DLC.
## Installation Info
- This mod is not compatible and must not be used with the older versions of Jobs, Gate, and Ware.
- Folder must be named "deadair_eco" or filepath's for added assets will fail and cause issues.
## Requesting Help
- It is very helpful to have a debug log with the debug options enabled.
- Include your mod list in any bug reports. There are a lot of poorly written mods out there.
- Best place to contact me is via @ on Egosoft Discord modding channel.
## Why the mods were combined
The more separate mods I maintain, the more work it is and the more things I have to consider when making changes which greatly limits potential changes. I am not a programmer by trade and am not supported by anyone. This is purely an interest and hobby of mine. If you like some changes but not others, there are ways to remove some of them without affecting other changes.
