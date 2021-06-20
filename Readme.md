# Diablo 2 Simple Loot Filter

## Introduction

This is a loot filter that I created for Lower Kurast superchest runs in mind, but can be used in any location. I had issues with another popular loot filter and decided to make my own. This particular one was created for Diablo 2 Lord of Desctuction version 1.14d with intension to work with newest PlugY mod. Should work with the newest (14.02) or any future version of PlugY, but ***will only work with Diablo 2 Lord of Desctuction version 1.14d***.

Note that PlugY mod dosen't have to be installed in order for filter to work. Will work on unmodded version as well. Other mods that work based on altering `Patch_D2.mpq` file ***will not work***.

## Features

It removes all junk that you shouldn't be interested from being displayed on the ground. All below item names are replaced with empty strings:
- Large Charm
- Healing Potion
- Greater Healing Potion
- Minor Mana Potion
- Light Mana Potion
- Greater Mana Potion
- Antidote Potion
- Rejuvenation Potion
- Thawing Potion
- Scroll of Town Portal
- Scroll of Identify
- Bolts
- Gold (numerical amount of gold is still displayed)
- Chipped Amethyst
- Flawed Amethyst
- Amethyst
- Chipped Topaz
- Flawed Topaz
- Topaz
- Chipped Sapphire
- Flawed Sapphire
- Flawed Emerald
- Emerald
- Chipped Ruby
- Chipped Diamond
- Flawed Diamond
- Diamond
- Exploding Potion
- Chipped Skull
- Skull

While item names were replaced with empty strings they still get that residual "rectangle" which when clicked will pick up the item. This rectanle can be seen on screenshots.

Some names are altered:
- Super Healing Potion -> HP5
- Super Mana Potion	-> MP5
- Full Rejuvenation Potion -> RP


## Installation

Just copy `Patch_D2 - Loot filter.mpq`, `disable_filter.bat` and `enable_filter.bat` to your Diablo II installation directory. You should find there `Patch_D2.mpq` file - make a copy in the same directory and rename it to `Patch_D2 - Original.mpq`. If you are super cautious you can even copy original `Patch_D2.mpq` to some other location.

Now you can enable it by running `enable_filter.bat` and disable it by running `disable_filter.bat`. I suggest making shortcuts to these files either on Desktop or in Start Menu.

# What do these bat files do actually?

`enable_filter.bat` just replaced original `Patch_D2.mpq` file with modified one. `disable_filter.bat` replaces modified file with original one.

# How to uninstall

Just run `disable_filter.bat` and then remove `Patch_D2 - Loot filter.mpq`, `disable_filter.bat` and `enable_filter.bat`. 

## License
Loot filter is provided As-Is. You can freely copy it and modify as you wish. No attribution needed.