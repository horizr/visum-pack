![horizr ❯ visum](./banner.png)

# horizr ❯ visum
> A Vanilla+ pack with a focus on aesthetics.

## Notable changes
### Charm
- Amethyst shards to item frame for invisibility
- Witches drop Luck potions
- Snow accumulates in cold biomes
- A crafting table can be used from the inventory
- Crops can't be trampled
- Bats in buckets for glowing 24 blocks 20s
- Stackable: 16x Enchantment books, Potions

## Development
[horizr CLI](https://github.com/horizr/cli) is used for pack management.

### To do
- `/gamerule reducedDebugInfo true` by default
- Find Inspecio replacements
- Configure Zoomify
- Configure Keybinds
- Configure Debugify (telemetry fix off)

### Interoperability entry-points
When new items/blocks/entities/structures are added, the configuration files of the following mods should be adjusted (if necessary).

- Charm: replantable crops, Bookcase items, structures on maps
- WTHIT: blacklisted blocks and entities
