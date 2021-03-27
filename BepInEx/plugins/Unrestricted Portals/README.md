___________________________________________________________________________________
What is it?:

Unrestricted Portals is a mod that allows players to take any item through portals. The mod is highly customizable, allowing players to restrict, unrestrict, or add multipliers for every item.
___________________________________________________________________________________
Why install it?:

Because Valheim has so many resources that are separated by tons of land and water, it makes grinding certain resources a pain. Having to go from one point ﻿to another takes lots of time. It is a useless grind. The developers fixed this by adding portals. This would be a solution, but they then blacklisted certain items. The blacklist of certain items forced players to go back to doing the useless grind.

If you think being able to take every item across portals is too overpowered or easy, then you can edit the configuration file to:


    Make every item restricted. (Can be overridden by individual item entries .)
    Make every item unrestricted. (Can be overridden by individual item entries.)

    Make individual items restricted.
    Make individual items unrestricted.

    Add a multiplier for all items on entering a portal. (Can be overridden by individual item entries.)
    Add a multiplier for all normally restricted items on entering a portal. (Can be overridden by individual item entries.)

___________________________________________________________________________________
How do you install it?:

1) ﻿Go to BepInExPack Valheim
2) Download it and follow the installation manual
3) Drag the unzipped Unrestricted Portals folder into -> <Steam Location>\steamapps\common\Valheim\BepInEx\plugin

The next time you start your game, the mod will be enabled. To disable it, just remove it from the mods folder or change the configuration.
___________________________________________________________________________________
How do you use it?:

The mod is client side.

By default, the mod will let you take 100% of previously restricted items through a portal with no multiplier.


    Make every item restricted. (Can be overridden by individual item entries .) -> Restrict All
    Make every item unrestricted. (Can be overridden by individual item entries.) -> Restrict None

    Make individual items restricted. Example -> [Name = TinOre, Restricted = True, Multiplier = 1.0, OverridesRestricted = True, OverridesMultiplier = False]
    Make individual items unrestricted. Example -> [Name = item_copperore, Restricted = False, Multiplier = 0.5, OverridesRestricted = True, OverridesMultiplier = True]

    Add a multiplier for all items on entering a portal. (Can be overridden by individual item entries.) -> Base Item Multiplier
    Add a multiplier for all normally restricted items on entering a portal. (Can be overridden by individual item entries.) -> Base Restricted Item Multiplier


Item names need to use either token syntax or prefab syntax.

The configuration files are located at -> <Steam Location>\steamapps\common\Valheim\BepInEx\plugin\﻿Unrestricted Portals\Config


    The General.txt file is for the base percentage. This is for every item. Each option in here can be overriden by specific item entries from the Items.txt file.
    The Items.txt file is for specific item entries.

___________________________________________________________________________________