A collection of Path of Exile regex usable in search fields in game.

# poe-regex
regex patterns usable in Path of Exile

### 6 Link
```"sockets: ([rgbw]-){5}[rgbw]"```

### 6 Socket
"sockets: ([rgbw][ -]){5}[rgbw]"

### Item Level 1-78
```"item level: ([1-9]$|[1-6][0-9]$|7[0-8])"```

### Item Level 80+
```"item level: ([1-9]\d{2,}|[8-9]\d)"```

### Quality
```"quality: \+([1-9][0-9])"```

### 70+ Life
```"([1-9]\d{2,}|[7-9]\d).+life"```

### Chaos Recipe
```"rare"|"item level: ([6][0-9]|[7][0-4])"```

### +1 Wand
```"ll g"```

### Physical damage
```Glint|Heav```

### Flat Elemental Damage
```Heat|roste|Humm```

### Flat Spell Damage
```"e to Sp"```

### Increased Spell Damage
```Appre```

### Str/Dex
```"!(^(str|dex))"```

### Intelligence Items
```"!(^(str|dex))"```

### Dexterity Items
```"!(^(str|int))"```

### Strength Items
```"^str" "!(^dex)"```

### Strength & Dexterity Items
```str: dex:```

### Strength & Intelligence Items
```dex: str:```

### Dexteroty & Intelligence Items
```dex: int:```

### Show Maps, No Elemental Reflect
```"!tal d"```

### Show Maps, No Physical Reflect
```""!f ph""```

### Show Maps, No Cannot Regen
```"!ege"```

### Show Maps, No Cannot Leech
```"!eec"```

### Show Maps, Rare Monsters each have a Nemesis Mod X% more Rare Monsters
```"neme"```

### Show Maps, Slaying Enemies close together has a X% chance to attract monsters from Beyond
```"yi"```

### Show Maps, Area contains two Unique Bosses
```"two"```

### Show Maps, Magic Monster Packs each have a Bloodline Mod X% more Magic Monsters
```"packs"```

### Show Maps, Slaying Enemies close together has a X% chance to attract monsters from Beyond
```"yi"```

### Show Maps, Give Me the Juice
```"yi|neme|two|packs|rog|tot"```

### Show Maps, Give Me the Juice, 40%+ Monster Pack Size
```"yi|neme|two|packs|rog|tot" "iz.*([4-9]\d|\d{3})"```

### Show Maps, 30 Quantity+
```"m q.*([3-9]\d|\d{3})"```

### Expedition, Gwennen Super Rare Unique Gambling
```"der m|nt ro|fien|r be|vy b|int'|n j|amp|pid"```

### Expedition, Gwennen Super Rare Unique Gambling - Belts Only
```"r be|vy b"```

### Flasks, Grants Immunity to Bleeding for # seconds if used while Bleeding Grants Immunity to Corrupted Blood for # seconds if used while affected by Corrupted Blood or Immunity to Bleeding and Corrupted Blood during Flask Effect #% less Duration
```"g an|af"```

### Flasks, Immunity to Poison during Flask Effect #% less Duration or Grants Immunity to Poison for # seconds if used while Poisoned
```"n fo|on d"```

### Flasks, Grants Immunity to Chill for # seconds if used while Chilled Grants Immunity to Freeze for # seconds if used while Frozen or Immunity to Freeze and Chill during Flask Effect #% less Duration
```"ze a|l f"```

### Flasks, Instant Recovery #% reduced Amount Recovered or Instant Recovery when on Low Life #% reduced Amount Recovered
```"see|y w"```
