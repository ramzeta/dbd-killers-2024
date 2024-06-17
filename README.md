# Let's create a README file for the best builds for killers in Dead by Daylight (DBD).
# This will include popular builds for some of the most used killers in the game.

readme_content = """
# Best Killer Builds for Dead by Daylight

This document provides some of the best builds for killers in Dead by Daylight. These builds are designed to optimize the effectiveness of each killer's unique abilities and playstyle.

## 1. The Trapper

**Perks:**
- **Corrupt Intervention**: Blocks the three generators furthest from you for 120/140/160 seconds at the start of the match.
- **Pop Goes the Weasel**: After hooking a survivor, the next generator you damage instantly loses 25% of its progress.
- **Barbecue & Chilli**: After hooking a survivor, all other survivors' auras are revealed to you for 4 seconds when they are further than 40 meters from the hook.
- **Hex: Ruin**: All generators regress at 200%/250%/300% of the normal regression speed while no survivor is working on them.

**Add-ons:**
- **Trapper Bag**: Start with and can hold 2 extra bear traps.
- **Trapper Gloves**: Decrease the setting time of bear traps.

## 2. The Hillbilly

**Perks:**
- **Enduring**: Reduces the duration of pallet stuns by 40/45/50%.
- **Spirit Fury**: After breaking 4/3/2 pallets, the next pallet you are stunned by is instantly broken.
- **Tinkerer**: When a generator is repaired to 70%, you receive a loud noise notification and your Terror Radius is reduced to 0 meters for 12/14/16 seconds.
- **Barbecue & Chilli**: After hooking a survivor, all other survivors' auras are revealed to you for 4 seconds when they are further than 40 meters from the hook.

**Add-ons:**
- **Spiked Boots**: Decreases the chainsaw sprint's steering penalty.
- **Heavy Clutch**: Increases chainsaw sprint steering.

## 3. The Nurse

**Perks:**
- **A Nurse's Calling**: The auras of survivors who are healing or being healed are revealed to you when they are within 20/24/28 meters.
- **Thanatophobia**: For each injured, dying, or hooked survivor, all survivors receive a 4%/4.5%/5% penalty to repair, healing, and sabotage speeds.
- **Stridor**: Increases the volume of survivors' grunts of pain by 25/50/50% and their regular breathing by 0/0/25%.
- **Pop Goes the Weasel**: After hooking a survivor, the next generator you damage instantly loses 25% of its progress.

**Add-ons:**
- **Pocket Watch**: Slightly increases the range of your Blink.
- **Fragile Wheeze**: Considerably decreases the cooldown of Blink attacks.

## 4. The Huntress

**Perks:**
- **Hex: Huntress Lullaby**: Survivors receive a 2/4/6% regression penalty when missing a skill check while healing or repairing.
- **Whispers**: You hear the Entity's whispers when within 48/40/32 meters of a survivor.
- **Iron Maiden**: You open lockers 30/40/50% faster. Survivors who exit lockers suffer from the Exposed status effect for 30 seconds and their location is revealed for 4 seconds.
- **Beast of Prey**: Grants the Undetectable status effect after gaining Bloodlust Tier I and lasts for as long as Bloodlust is active.

**Add-ons:**
- **Infantry Belt**: Start with 2 extra hatchets.
- **Bandaged Haft**: Moderately decreases the wind-up time for hatchet throws.

## 5. The Spirit

**Perks:**
- **Hex: Haunted Ground**: Two trapped Hex Totems spawn in the Trial. When one of the two trapped Hex Totems is cleansed by a survivor, all survivors suffer from the Exposed status effect for 40/50/60 seconds.
- **Rancor**: Each time a generator is completed, your obsession sees your aura for 3 seconds. Each time a generator is completed, all survivors' locations are revealed to you for 3/4/5 seconds. Once all generators are powered, the obsession suffers from the Exposed status effect.
- **Sloppy Butcher**: Basic attacks cause survivors to suffer from the Hemorrhage and Mangled status effects.
- **Spirit Fury**: After breaking 4/3/2 pallets, the next pallet you are stunned by is instantly broken.

**Add-ons:**
- **Mother-Daughter Ring**: Considerably increases Yamaoka's Haunting movement speed.
- **Father's Glasses**: Considerably increases the duration of Yamaoka's Haunting.

These builds are aimed at enhancing each killer's strengths and maximizing their potential in matches. Good luck and happy hunting!
"""

# Save to README.md
with open("/mnt/data/README.md", "w") as file:
    file.write(readme_content)

