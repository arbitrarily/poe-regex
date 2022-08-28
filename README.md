# Path of Exile Regen Collection
A collection of Path of Exile regex usable in search fields in game.

---

![image](https://user-images.githubusercontent.com/899183/187089726-24c49ef7-833e-4ebb-a442-0dad08d1696a.png)

## Stash

> ### 6 Link
> <pre>"sockets: ([rgbw]-){5}[rgbw]"</pre>

> ### 6 Socket
> <pre>"sockets: ([rgbw][ -]){5}[rgbw]"</pre>

> ### Item Level 1-78
> <pre>"item level: ([1-9]$|[1-6][0-9]$|7[0-8])"</pre>

> ### Item Level 80+
> <pre>"item level: ([1-9]\d{2,}|[8-9]\d)"</pre>

> ### Quality
> <pre>"quality: \+([1-9][0-9])"</pre>

> ### 70+ Life
> <pre>"([1-9]\d{2,}|[7-9]\d).+life"</pre>

> ### Chaos Recipe
> <pre>"rare"|"item level: ([6][0-9]|[7][0-4])"</pre>

> ### +1 Wand
> <pre>"ll g"</pre>

> ### Physical damage
> <pre>Glint|Heav</pre>

> ### Flat Elemental Damage
> <pre>Heat|roste|Humm</pre>

> ### Flat Spell Damage
> <pre>"e to Sp"</pre>

> ### Increased Spell Damage
> <pre>Appre</pre>

> ### Str/Dex
> <pre>"!(^(str|dex))"</pre>

> ### Intelligence Items
> <pre>"!(^(str|dex))"</pre>

> ### Dexterity Items
> <pre>"!(^(str|int))"</pre>

> ### Strength Items
> <pre>"^str" "!(^dex)"</pre>

> ### Strength & Dexterity Items
> <pre>str: dex:</pre>

> ### Strength & Intelligence Items
> <pre>dex: str:</pre>

> ### Dexteroty & Intelligence Items
> <pre>dex: int:</pre>

---

> ## Show Maps
> No Elemental Reflect
> <pre>"!tal d"</pre>

> ### No Physical Reflect
> <pre>""!f ph""</pre>

> ### No Cannot Regen
> <pre>"!ege"</pre>

> ### No Cannot Leech
> <pre>"!eec"</pre>

> ### Rare Monsters each have a Nemesis Mod X% more Rare Monsters
> <pre>"neme"</pre>

> ### Slaying Enemies close together has a X% chance to attract monsters from Beyond
> <pre>"yi"</pre>

> ### Area contains two Unique Bosses
> <pre>"two"</pre>

> ### Magic Monster Packs each have a Bloodline Mod X% more Magic Monsters
> <pre>"packs"</pre>

> ### Slaying Enemies close together has a X% chance to attract monsters from Beyond
> <pre>"yi"</pre>

> ### Give Me the Juice
> <pre>"yi|neme|two|packs|rog|tot"</pre>

> ### Give Me the Juice, 40%+ Monster Pack Size
> <pre>"yi|neme|two|packs|rog|tot" "iz.*([4-9]\d|\d{3})"</pre>

> ### 30 Quantity+
> <pre>"m q.*([3-9]\d|\d{3})"</pre>

---

> ## Flasks
> ### Grants Immunity to Bleeding for # seconds if used while Bleeding Grants Immunity to Corrupted Blood for # seconds if used while affected by Corrupted Blood or Immunity to Bleeding and Corrupted Blood during Flask Effect #% less Duration
> <pre>"g an|af"</pre>

> ### Immunity to Poison during Flask Effect #% less Duration or Grants Immunity to Poison for # seconds if used while Poisoned
> <pre>"n fo|on d"</pre>

> ### Grants Immunity to Chill for # seconds if used while Chilled Grants Immunity to Freeze for # seconds if used while Frozen or Immunity to Freeze and Chill during Flask Effect #% less Duration
> <pre>"ze a|l f"</pre>

> ### Instant Recovery #% reduced Amount Recovered or Instant Recovery when on Low Life #% reduced Amount Recovered
> <pre>"see|y w"</pre>


---

## Expedition

> ### Gwennen Super Rare Unique Gambling
> <pre>"der m|nt ro|fien|r be|vy b|int'|n j|amp|pid"</pre>

> ### Gwennen Super Rare Unique Gambling - Belts Only
> <pre>"r be|vy b"</pre>
