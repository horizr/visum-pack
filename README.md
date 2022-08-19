![horizr ❯ visum](./banner.png)

# horizr ❯ visum
> A Vanilla+ pack with a focus on aesthetics.

[**📄 Included mods**](./docs/mods.md)

## Notable changes
- Click an item frame with an amethyst shard to make it invisible
- Witches drop Luck potions
- Snow accumulates in cold biomes
- A crafting table can be used from the inventory
- Crops can't be trampled
- Bats can be caught in buckets and let nearby entities glow for 20s when they are released
- Enchantment books and potions are stackable (16)

## Development
[horizr CLI](https://github.com/horizr/cli) is used for pack management.

### To do
- `/gamerule reducedDebugInfo true` by default
- Find a solution for default options

### Interoperability entry-points
When new items/blocks/entities/structures are added, the configuration files of the following mods should be adjusted (if necessary).

- Charm: replantable crops, Bookcase items, structures on maps
- WTHIT: blacklisted blocks and entities
