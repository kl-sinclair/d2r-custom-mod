# d2r-custom-mod

## How to use

```sh
$ cd ${D2R_HOME}/mods
$ git clone git@github.com:kl-sinclair/d2r-custom-mod.git custom
```

and set additional command line args

```
-mod custom
```

## Features

- [Arrow to Magic Arrow for visibility](./custom.mpq/data/hd/missiles/arrow.json)
- [Ethereal color to Dark Green](./custom.mpq/data/global/ui/layouts/_profilehd.json#304)
- [Use D3 Legendary drop sound for Rune drop](./custom.mpq/data/hd/global/sfx/item/item_rune_hd.flac#)
- [Horadric light for item drop](./custom.mpq/data/hd/items/)
    - [Rune](./custom.mpq/data/hd/items/misc/rune/)
    - [Circlet (disabled)](./custom.mpq/data/hd/items/armor/circlet/)
- [Custom item labels](./custom.mpq/data/local/lng/strings/)
    - [Runes](./custom.mpq/data/local/lng/strings/item-runes.json)
        - more visible from (21) Pul rune
    - [Potions](./custom.mpq/data/local/lng/strings/item-names.json)
        - Super Healing/Mana Potion
        - Full Rejuvenation Potion
    - [Gems](./custom.mpq/data/local/lng/strings/item-names.json)
        - [some other gems](./custom.mpq/data/local/lng/strings/item-nameaffixes.json)
