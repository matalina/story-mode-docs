---
{"dg-publish":true,"permalink":"/002-dungeon-crawler/dungeon-crawl/"}
---

# Dungeon Crawl

Setup a Game: 
* Generate a dungeon name
* Generate Objective
* Generate the number of rooms by rolling 3d6+2 (5-20).  If the first room you entered has 0 other door roll again.
* When you reach the last room you find your objective

When entering a room:
* Roll a new scene status
* Roll on contents
* Roll 1d4-1 doors
* Resolve what you find
* Roll to see the status of the door
* Roll against scene status to find any secrets

| d20          | Result       | Details                                  |
| ------------ | ------------ | ---------------------------------------- |
| 1            | Fail, and    | You find find and trigger a trap.        |
| 2 to DC-6    | Fail, but    | You find a trap, but it is not triggered |
| DC-5 to DC-1 | Success, but | You find a secret but its trapped        |
| DC to DC+4   | Success      | You found a secret                       |
| DC+5 +       | Success, and | You found 2 secrets                      |

## Dungeon Name

| d6  | Dungeon Name Patter       |
| --- | ------------------------- |
| 1-2 | The \[descriptor] \[type] |
| 3-4 | The \[type] of \[threat]  |
| 5-6 | \[adjective] \[type]      |

| d20 | Type      | Descriptor   | Threat       | Adjective  |
|-----|-----------|--------------|--------------|------------|
| 1   | Vault     | Forsaken     | Shadows      | Twisted    |
| 2   | Tomb      | Forgotten    | the Lost     | Cursed     |
| 3   | Labyrinth | Sunken       | Wrath        | Haunted    |
| 4   | Catacombs | Shattered    | the Forsaken | Ancient    |
| 5   | Temple    | Echoing      | Madness      | Abyssal    |
| 6   | Fortress  | Ruined       | the Damned   | Eldritch   |
| 7   | Mausoleum | Blackened    | Nightmares   | Dreaded    |
| 8   | Keep      | Hollow       | the Fallen   | Forgotten  |
| 9   | Caverns   | Burning      | Curses       | Shadowed   |
| 10  | Sepulcher | Icy          | the Betrayed | Forbidden  |
| 11  | Halls     | Crumbling    | Agony        | Sinister   |
| 12  | Shrine    | Weeping      | the Doomed   | Malevolent |
| 13  | Crypt     | Bloodstained | Elders       | Blighted   |
| 14  | Dungeon   | Whispering   | the Sealed   | Ominous    |
| 15  | Sanctum   | Desecrated   | the Banished | Eternal    |
| 16  | Ruins     | Chained      | Torment      | Infernal   |
| 17  | Caverns   | Unholy       | the Bound    | Hollow     |
| 18  | Asylum    | Silent       | Whispers     | Doomed     |
| 19  | Tower     | Wailing      | Chaos        | Malevolent |
| 20  | Spire     | Eldritch     | the Devoured | Black      |

## Objective

| d6  | Objective Pattern     |
| --- | --------------------- |
| 1   | Find \[artifact]      |
| 2   | Collect 2d4 \[things] |
| 3   | Kill the \[creatures] |
| 4   | Rescue \[someone]     |
| 5   | Clear the Dungeon     |
| 6   | Kill the \[Boss]      |

| d20 | Artifact             | Things               | Creatures           | Someone             | Boss                 |
|-----|----------------------|----------------------|---------------------|---------------------|----------------------|
| 1   | Orb of Eternity      | Ancient Tomes        | Skeleton Warriors   | Trapped Noble       | Vampire Lord         |
| 2   | Crown of Shadows     | Cursed Relics        | Wraiths             | Lost Scholar        | Demon Overlord       |
| 3   | Blade of the Void    | Stolen Soul Shards   | Specters            | Kidnapped Child     | Corrupted Paladin    |
| 4   | Phoenix Heart        | Dragon Scales        | Ghouls              | Fae Prisoner        | Fallen Knight        |
| 5   | Arcane Codex         | Ghostly Essences     | Restless Spirits    | Stolen Heir         | Mad Sorcerer         |
| 6   | Sunstone Amulet      | Mystic Runes         | Basilisks           | Trapped Mage        | Necromancer          |
| 7   | Bloodstone Dagger    | Forbidden Idols      | Undead Horrors      | Merchant's Daughter | Shadow Queen         |
| 8   | Rune-Carved Shield   | Essence Vials        | Infernal Hounds     | Sealed Guardian     | Ancient Dragon       |
| 9   | Shard of Oblivion    | Arcane Crystals      | Cultists            | Doomed Prince       | Warlock Lord         |
| 10  | Chalice of Ages      | Dark Artifacts       | Mummified Priests   | Forgotten Hero      | Lich-King            |
| 11  | Starforged Gauntlet  | Moonflower Petals    | Oozes               | Bound Celestial     | Chaos Entity         |
| 12  | Blackened Grimoire   | Fungal Spores        | Cursed Knights      | Fading Ghost        | Infernal Tyrant      |
| 13  | Heart of the Forest  | Enchanted Roots      | Poisonous Serpents  | Runaway Prince      | Bloodthirsty Warlord |
| 14  | Emberforged Helm     | Sacred Relics        | Elemental Guardians | Hidden Oracle       | Fey Trickster        |
| 15  | Mask of Whispers     | Phantom Eyes         | Cursed Beasts       | Captured Ranger     | Living Nightmare     |
| 16  | Crown of the Undying | Obsidian Shards      | Werewolves          | Forgotten Monk      | Undead Pharaoh       |
| 17  | Twilight Lantern     | Shattered Sigils     | Animated Statues    | Broken Construct    | Demon Prince         |
| 18  | Everfrost Crystal    | Fey Trinkets         | Harpies             | Wandering Scribe    | Eldritch Horror      |
| 19  | Doomforged Talisman  | Blood-Soaked Scrolls | Shadow Beasts       | Missing Alchemist   | The Devourer         |
| 20  | Tome of the Ancients | Warding Stones       | Arcane Sentinels    | Exiled Heir         | Fallen God           |


## Contents, Doors & Secrets

| d20   | Contents              |
| ----- | --------------------- |
| 1-3   | Nothing               |
| 4-5   | Trap                  |
| 5-9   | 1d4 Level 3 Creatures |
| 10-11 | Ally NPC              |
| 12-15 | Rival NPC             |
| 16-17 | Trick/First Encounter |
| 13-20 | Survivor              |

| d6  | Door                     |
| --- | ------------------------ |
| 1   | Regular unlocked door    |
| 2   | Regular locked door      |
| 3   | Trapped regular door     |
| 4   | Reinforced unlocked door |
| 5   | Reinforced locked door   |
| 6   | Trapped reinforced door  |

| d6  | Secrets        |
| --- | -------------- |
| 1   | Hidden Door    |
| 2   | Hidden Chest   |
| 3   | Hidden Room    |
| 4   | Dungeon Secret |
| 5   | World Secret   |
| 6   | Nothing        |
