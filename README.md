# DeadAir Eco
## Dynamic Universe
Reworked all diff based mods into a single mod that contains improved versions of God, Ware, Gate, and Jobs. Readme may be out of date on features or numbers at times so feel free to contact me on the Egosoft Discord.
## AiScripts\Build.Shiptrader.xml
- Added chance for player to get rookies or veterans on hiring.
- Increased amount of ships assigned to trade for NPC shipyards and wharves.
- Added logic for traders to be assigned to Xenon shipyards.
## Structure Macro Changes
- Doubled capacity of drones for build modules to prevent AI from having too few drones to build ships at full speed.
- Increased Terran habitation modules to have same worker capacity as other factions.
## Map Changes
- Added asteroid fields to cluster 403, 406
- Added gas field to cluster 403, 406
## Libaries\Baskets.xml
- Adjusted wares in baskets used by AI.
## Libraries\Constructionplans.xml
- Replaced 1M6S dock modules at important stations with 3M6S modules to improve ship docking capacity.
- Added larger plans for Shipyards and Wharves. Shipyards gained 2L Storage, 2M storage, 2L Ship building modules, 2L Habitats, and 1 3-dock Pier. Wharves gained 2L Storage, 2M Storage, 2L Habitats, and 1 3-dock Pier.
## Libaries\Defaults.xml
- Adjusted threatscore for different ships and increased station threatscore.
## Libaries\God.xml
- Increases allowed stations per zone to accomodate higher density.
- Increases number of defence stations for xenon in cluster 16, 25, and 32; and for Split in cluster 400, 402, and 404.
- Increases loadout level of several important stations.
- Removes Argon and Paranid stations from Split DLC sectors so they stop wasting resources and CPU cycles.
- Increases economies of AI to be mostly self sustaining so they can actually accomplish something without the player.
## Libraries\Jobs.xml
- Adjusted jobs for economy ships. Ships will generally be more evenly spread across galaxy for anchor location and use improved baskets.
- L and M ships will generally use traderoutine instead of distributewares aiscript so they will actually respond to trade imbalances on demand side instead of supply side.
- Added jobs for silicon mining and ore mining for Xenon to improve their economy.
## Libraries\Loadoutrules.xml
- Increased weighting values for imprortant drones (transport drones for traders and build drones for construction ships).
- Attempted to reduce NPC ships loading up on deployables that serve no purpose other than to tank the economy.
## Libraries\mapdefaults.xml
- Adjusts sector economy and security ratings of sectors to change station location preference and station size preference.
- Fixes undocumented "feature" where station module count is affected by economy value of sector.
## Libraries\Modulegroups.xml
- Added new groups for Advanced Schematics, Military Schematics, and Labor Union Contracts.
## Libraries\Modules.xml
- Increased amount of modules that NPC are allowed to build on a single station. This greatly reduces the number of stations required for a functional economy.
- Reintroduced several mixed product stations to reduce station count.
## Libraries\Parameters.xml
- Increased amount of modules that NPC are allowed to build on a single station.
- Increased default level of drone loadout to prevent ships without enough drones to function effectively.
## Libraries\People.xml
- Increased fill percentage of certain NPC crews.
- Ships with Regular crews will have 50%+ of the ships capacity.
- Ships with Veteran crews will have 75%+ of the ships capacity.
- Ships with Elite crews will have 90% of the ships capacity.
- The higher importance the ship is to the faction, the higher the amount and ability of the crew.
## Libaries\Region_Definitions.xml
- Increased resource yields of several areas that are vital to the factions economic stability.
## Libaries\Regionyields.xml
- Reduced the replenish time of all resource areas. Areas that have low or worse density will replenish over 60 minutes. Areas that have medium density will replenish over 120 minutes. Areas that have high density or greater will replnish over 240 minutes.
## Libraries\Ships.xml
- Adjusted the crews used by different ships.
## Libraries\Stationgroups.xml
- Changed the construction plans of shipyards and wharves to use the upgraded designs.
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
- Adjusted station generation logic to use fewer but higher capacity dock modules.
- Adjusted station generation logic to consider only the lowest relation faction nearby when determining how many defense modules they want on a station.
## Md\Inituniverse.xml
- Added several ship production wares to tradestations.
## Custom script
- Added custom script to drain all Advanced Schematics, Military Schematics, and Labor Union Contracts on game start.
## Dependencies
- No mod dependencies at this time.
## Installation Info
- This mod is not compatible and must not be used with the older versions of Jobs, Gate, and Ware.
## Requesting Help
- It is very helpful to have a debug log with the debug options enabled.
- Include your mod list in any bug reports. There are a lot of poorly written mods out there.
- Best place to contact me is via @ on Egosoft Discord
## Why the mods were combined
The more separate mods I maintain, the more work it is and the more things I have to consider when making changes which greatly limits potential changes. I am not a programmer by trade and am not supported by anyone. This is purely an interest and hobby of mine. If you like some changes but not others, there are ways to remove some of them without affecting other changes.
