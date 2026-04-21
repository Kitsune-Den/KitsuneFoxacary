# KitsuneFoxacary

![KitsuneFoxacary banner](assets/KitsuneFoxacary-banner.jpg)

[![Latest Release](https://img.shields.io/github/v/release/Kitsune-Den/KitsuneFoxacary?style=flat&color=teal)](https://github.com/Kitsune-Den/KitsuneFoxacary/releases)
[![Twitter](https://img.shields.io/badge/Twitter-@AdaInTheLab-1DA1F2?style=flat&logo=x&logoColor=white)](https://x.com/AdaInTheLab)
[![License](https://img.shields.io/github/license/Kitsune-Den/KitsuneFoxacary?style=flat)](LICENSE)

Fox-crafted pharmacy expansion for 7 Days to Die. Think KitsuneKitchen, but for the topical, injected, and bandaged side of survival.

## Why

Vanilla 7D2D has some real gaps in the medical tree:

- You can't cure a sprain without dumping a point into Physician. For Agility archetypes or pure loot-runners, that perk isn't a priority, so they get to walk slowly for ten minutes instead.
- Blood bags exist as loot items with literally zero vanilla uses. You sell them to traders because the game wired up nothing else for them.
- Queen Bees are the same story. Real loot drop from beehives. Zero recipe uses. Pure vendor filler.
- Testosterone extract is harvested constantly and used in only two recipes.

Foxacary fills those gaps. Every item uses a resource that's either underused or completely wasted in vanilla, and slots into the existing `craftingMedical` journal progression so it feels like it was always part of the game.

## Design rules

- **Kitchen owns the mouth.** Ingested infection cures (honey tea, etc.) live in KitsuneKitchen.
- **Foxacary owns the skin and the needle.** Topical, injected, and applied items.
- **Honey always cures infection.** Any Foxacary item using honey has an infection-cure property, per the Kitsune brand.
- **Nothing strictly beats vanilla.** Items fill gaps, not replace working stuff.

## Items (draft)

| Item | Ingredients | Effect | Unlock |
|---|---|---|---|
| Field Brace | thread + cloth + wood | Removes sprained leg/arm, no Physician perk required | Medical journal lvl 3 |
| Suture Kit | thread + sewing kit + alcohol | Instant stop bleeding and abrasion | Medical journal lvl 15 |
| Honeyed Battle Dressing | honey + bandage + cloth | Stops bleeding + blocks next infection catch | Medical journal lvl 25 |
| Royal Jelly Salve | queen bee + beeswax + cloth | Strong heal-over-time, finally uses the queen bee | Medical journal lvl 35 |
| Transfusion Kit | blood bag + duct tape + ??? | Big instant HP restore, finally uses blood bags | Medical journal lvl 65 |

Numbers, exact ingredient counts, and recipe costs are being tuned.

## Install

1. Drop the `KitsuneFoxacary/` folder into `<7D2D install>/Mods/`
2. Launch the game

XML-only mod. No DLL, no Harmony. Works on both client and server.

## Compatibility

Needs to be installed on both server AND clients since it adds new items. This is normal for any 7D2D content mod.

Built against V2.6.14.

## License

MIT.
