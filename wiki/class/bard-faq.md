---
title: 'Bard FAQ and Mechanics for Project Quarm'
description: 'Comprehensive guide covering Bard-specific questions, mechanics, and strategies for Project Quarm, including stats, races, swarming, charm kiting, song rotations, instruments, and more.'
keywords:
  - 'Project Quarm'
  - 'Quarm Guides'
  - 'Quarm Wiki'
  - 'Bard'
  - 'FAQ'
  - 'swarming'
  - 'songs'
  - 'instruments'
  - 'melody'
  - 'charm kiting'
  - 'mechanics'
date: 2025-02-28
author: Bardlings Community (compiled by DoctorRobinson)
toc: true
resize_images: true
published: true
sitemap: true
---
# Bard FAQ and Mechanics

This guide was compiled from the Project Quarm Discord (Gameplay & Mechanics — Bard channel) as community knowledge during the Luclin era. Special thanks to vaalkryst, longmont, viskar, peetar, maerg, aycee, JohnnyCash, and all contributing bards. It is not an end-all-be-all guide, but rather a supplement to [existing bard resources](https://wiki.project1999.com/Bard) with information specific to the Project Quarm server.

## Starting stats?

Short answer: most bards go full STA. But here's the deep dive.

#### Most popular: Full STA (Stamina)

* 100+ STA prevents stat penalties when fatigued (-10 STR/DEX/AGI)
* Extra HP is useful for leveling and swarming
* STA is hardest to cap in Velious/Luclin without raid gear

#### Alternative: All INT or CHA

* Most other stats cap easily with gear and buffs
* CHA provides +1% blur chance per 10 points
* INT slightly increases mana pool
* Mainly for min-maxing end-game builds

**Note:** Stats matter less at end-game due to gear, but STA gives immediate leveling benefits.

## "Best" race?

* **Half-Elf:** Highest overall melee stats (most popular choice)
* **Wood Elf:** Trades strength for agility
* **Human:** Consistent stats, no night vision

Race choice has minimal long-term impact due to gear.

## Core mechanics every bard should know

#### /melody

The `/melody` command auto-restarts songs on fizzles. This is essential quality of life for bards. Example: `/melody 1 2 3` will cycle through spell gems 1, 2, and 3 continuously.

#### Instrument swapping

Critical for maximizing song effectiveness. Use Zeal's "right click to equip" feature for quick swaps. Primary-hand instruments (Velious+) reduce swap complexity.

#### Song stacking

Songs don't stack with similar effects — the higher version overwrites the lower. Use the [Bard Pro Song Calculator (by peetar)](https://pqdi.cc) to check stacking and optimize melodies. Red highlights indicate conflicts.

#### Flowing Thought (FT)

Essential for mana regen because mana songs don't work on bards. Prioritize FT gear.

## How does swarming work?

Swarming (also called AoE kiting or PBAoE kiting) is the bard's signature solo technique — pulling a pack of mobs and running in circles while PBAoE DoT songs kill them.

### Swarm limits (critical)

* **12 mobs maximum** can be damaged by AoE at once
* **15 mobs on your aggro list** triggers mobs porting on top of you
* This means you can safely have **14 mobs max**. At 15 = porting = death
* These limits are enforced in open world (instances may differ)

### Swarm technique (step-by-step)

1. Bind Zeal slow turn to a key (use slow turn **left** — slow turn right is offensive and nobody should do that)
2. Refresh JBoots if you don't have Run Speed 3 AA
3. Turn on Selos (optional outside, but makes pulling faster)
4. Pull 12 mobs (maximum that a PBAoE will hit at once). You can aggro up to 14 before auto-summon triggers
5. Run manual big circles to group mobs together
6. Click off Selos buff (from buff window)
7. Press and hold slow turn key
8. Press Enter twice while holding slow turn to "lock it in" — this activates the chat bar method (some people use alt-tab, but Enter is safer)
9. Adjust weight to match your ping and mob speed:
    * ~40 lbs encumbrance with Run Speed 3 AA (recommended). Use throwing boulders and unstack them in inventory
    * ~45–50 lbs with JBoots only
    * Run Speed 2 may need little or no encumbrance
    * Test and adjust for your specific lag and ping

### Common swarm deaths (and how to avoid them)

1. **Too many mobs (15+):** Mobs summon or warp on you = instant death. Fix: Charm and suicide one into the pack to drop under 15, or use Song of Highsun to port one away
2. **Lag or server issues:** Not much you can do. Accept it happens
3. **Other players training mobs near you:** Adds to your aggro list. Be aware of surroundings and pick quiet areas
4. **Multitasking:** Do at your own risk. Click into a chat box when returning to EQ to avoid accidental turn interruption
5. **Clicking back into game from another window:** Can interrupt slow turn = mobs catch you. Fix: Click into a chat box instead of the game window
6. **Pressing CTRL:** Interrupts turning. If you hotkey single-select boulders from a stack, it can kill you. Watch hotkeys when chatting (Ctrl+A, Ctrl+C, Ctrl+V)
7. **Editing macros mid-swarm:** Can cause issues and deaths. Fix: Make multiple macro versions and keep them on the hotbar

## What are the PBAoE DoT songs?

The four PBAoE DoT songs are your core swarming toolkit:

| Level | Song | Instrument | Notes |
|-------|------|------------|-------|
| 2 | Chords of Dissonance | String | -100 MR modifier, rarely resists |
| 18 | Denon's Disruptive Discord | Brass | DoT + AC debuff |
| 48 | Selo's Chords of Cessation | String | DoT + attack speed slow |
| 59 | Denon's Bereavement | String | DoT + poison + stun + MR debuff |

### Swarm melody by level

* **Levels 2–17:** `/melody 1` (just Chords of Dissonance)
* **Levels 18–47:** `/melody 1 2 2` (Chords, Discord, Discord)
* **Levels 48–58:** `/melody 1 2 3` (Chords, Discord, Cessation)
* **Level 59+:** `/melody 1 2 3 4` (all four PBAoE DoTs)

### Instrument swapping for swarm rotation

* **String** for Chords of Dissonance
* **Brass** for Denon's Disruptive Discord
* **String** for Selo's Chords of Cessation
* **String** for Denon's Bereavement
* Epic in offhand provides 80% bonus to all instrument types
* Use Zeal's right-click equip for quick swaps

## Mobs keep hitting me while kiting. What's wrong?

Common causes:

* Server or connection lag
* Running in straight lines (delays position updates to server — run curves instead)
* Particle effects enabled (turn them off)
* FPS or frame rate issues
* Some zones (like Fungus Grove) have resource problems

**Fix:** Reduce pull size, check connection, disable particles, and make sure Zeal has a Windows Defender exclusion.

If mobs are warping or bouncing (common with 7+ mobs), keep weight at the proper level. Some players need to go lighter (31 lbs vs 40 lbs).

## What is the PBAoE XP penalty?

Starting at level 55, there's an XP penalty for killing mobs with PBAoE damage:

* If a mob is level 40+ and you deal >50% of its HP with PBAoE damage, you get a **negative XP penalty**
* Penalty scales with level difference: 0% when mob is within 5 levels, ~93% at 20 level difference
* Applies to both regular XP and AA XP

### What this means in practice

* Level 60 doing level 45 mobs = bad (massive penalty)
* Level 60 needs **level 55+ mobs minimum** (ideally 55–59)
* Level 55–59: Consider charm swarming instead of PBAoE (no penalty)
* Level 59+ with Denon's Bereavement: PBAoE becomes viable again with 4 DoTs

### Approximate penalty math (for level 60 bard)

* ~6% XP loss per level under 55
* Level 50 mobs = ~30% XP penalty
* Level 45 mobs = ~60% XP penalty

### Workaround: Enchanter memblur

Group with an enchanter who memblurs packs after you PBAoE. This removes the "PBAoE damage" flag from mobs and you get full XP as if you didn't use PBAoE.

### Ideal level 60 AA swarm spots

* **Fungus Grove:** Shik'nar workers and foragers (53), mutants and bandits (49–53)
* **Chardok:** Indoor 50+ mobs (risky)
* **Maiden's Eye:** Higher level mobs — goranga scout camps, mind burrowers, reanimated drudge, ravenous beasts (not Umbrous Toilers)

## How does charm swarming (reverse charm kite) work?

Pull 10–12 mobs, charm one and send it at another, have the pack kill it. This avoids the PBAoE XP penalty entirely.

### Body pulling technique

**Critical:** Body pull mobs (get into range without doing damage). If you DoT or damage mobs before charming, they attack you instead of the charmed pet.

**Flow:** Charm a mob → have it attack another → run aggro'd mobs over the pet so they attack it when in range.

### Songs used

* **Selo's Accelerating Chorus:** Movement speed
* **Charm:** Lower levels are 18 seconds; higher-level charm uses mana and lasts ~60s
* **Single-target DoTs (stacking):**
    * Chant of Flame (Lv 38, Percussion)
    * Chant of Frost (Lv 46, Percussion)
    * Fufil's Curtailing Chant (Lv 39, Percussion) — includes MR debuff
* **Direct damage for finishing low HP pets:**
    * Brusco's Boastful Bellow (Lv 12, Singing)
    * Sorrowsong Boots click (333 DD)
    * Blazing Bracer click

### Typical charm swarm flow

1. Body pull 10–12 mobs (do no damage)
2. Charm one mob
3. Have the charmed pet attack another mob
4. Run remaining mobs over the pet
5. Monitor pet HP — break charm at ~3–5% for safety
6. Click invis (Invis vs Animals) to break charm:
    * **Mosquito Boots** (inventory click, preferred)
    * **Gazughi Ring** (must equip)
    * If you have neither, use invis song (3s cast)
    * Note: Mosquito Boots are strongly preferred over Gazughi Ring because they're an inventory click
7. Load DoTs or DD depending on HP left
8. Repeat on next mob

## What's a good hotbar layout?

JohnnyCash's personal setup (keys 1–8):

1. **Largos** (snare or slow)
2. **Charm**
3. **Flex** (lull, DD, invis, etc.)
4. **Mez**
5. **Heal or regen** (usually Cantata)
6. **Flex** (mana pulse, buffs, DS, etc.)
7. **Attack buff** (McVaxious)
8. **Selos or resist buffs**

## What songs should I play in a group?

### Group support (haste, regen, DS)

* **Attack speed and DS:** McVaxius' Berserker Crescendo (Lv 58, Brass). Note: Epic proc provides 55% haste, so you can often replace the haste song with stats or resists
* **Regen:** Cantata or Chorus of Soothing

### Resist songs

Use Peetar's app to determine what stacks for your group. Typically Guardian Rhythms and Elemental Chorus or Purifying, depending on group makeup.

### Utility songs

* **Invulnerability:** Kazumi's Note of Preservation (Lv 60, Singing) — group invulnerability for 12 seconds. Group cannot cast spells or play songs while active. Apply movement speed before using since you can't recast Selos while invuln
* **Movement:** Selo's Accelerating Chorus (multiple levels)

### Solo kiting (fear or chant kite)

* Snare (Largos preferred)
* Angstlich's Appalling Screech (Lv 26, Brass) — PBAoE fear
* Chant of Flame (Lv 10, Singing)
* Chant of Frost (Lv 34, Singing)

## What equipment should I prioritize?

### Essential clickies (priority order per longmont)

1. **Journeyman Boots (JBoots)** — movement speed
2. **Voice of the Serpent (VotS)** — +60% singing mod
3. **Tiny Cloak of Darkest Night** — short cast invis (1.5s vs 5.5s)
4. **Worker's Sledgemallet** — dispel fodder + Eye of Zomm trick (Beads trick: Holgresh Elder Beads → cast Eye of Zomm → hit Eye pet with hammer)
5. **Blazing Bracer of Fennin Ro** — DD click
6. **Pegasus Feather Cloak** — levitate
7. **Velious faction BP**
8. **AoN**
9. **Illusion masks** (all races)
10. **Sorrowsong Boots or Blazing Bracer** — DD click
11. **Mosquito Boots** — IVa from inventory, replaces Gazughi Ring

### Additional useful items

* **Drums of the Beast** — Enduring Breath insta-cast
* **Flowers** — DR/CR
* **Blazing Arms** — insta DS
* **Fungi Tunic and Fungi Staff** — regen
* **Fishbone Earring** — Enduring Breath
* **Manastone** — breaks roots in classic zones

### Instrument progression

#### Percussion
vendor drums (100%) → Tambourine of Rituals (120%) → Walrus Skin Drum (130%) → Selo's Drums (140%) → Drums of the Beast (160%)

#### Stringed
vendor lute (100%) → Lute of Gypsy Princess (110%) → Combine Lute (120%) → Lyran's Mystical Lute (150%)

#### Brass
vendor horn (100%) → McVaxious Horn of War (130%) → Denon's Horn of Dissonance (140%)

#### Wind
Generally not important, but helps with charm breaks on high MR mobs.

## Technical tips and Zeal setup

### Zeal configuration

* Enable **right-click to equip** (for instrument swapping)
* Enable **slow turn** (for swarming)
* Add a **Windows Defender exclusion** for the Zeal folder (reduces lag)
* Check FPS settings (cap background FPS)

### Melody and instrument skills

* Melody auto-retries fizzles rapidly
* Having the correct instrument equipped levels that instrument skill
* Wrong or no instrument levels the Singing skill instead

### Swarm limit mechanics

* The 12-mob AoE cap triggers on damage, not just aggro
* 15 mob aggro list = summon ("You will not evade me")
* Guild instances may have no limit (needs confirmation)

## Leveling speed run path

* **2–8:** Trainer Hill
* **18–23:** EK Spiders
* **25–35:** Iceclad
* **35–49:** Katta Guards (Legos)
* **49–60:** Fungus Grove / Maiden's Eye

### Important leveling notes

* **ZEM** = Zone Experience Modifier (affects XP gain)
* 12 mob AoE damage cap enforced in open world
* 15 mob aggro limit = auto-summon/death
* Guild instances may have different rules (needs verification)
* PBAoE penalty at 55+: See PBAoE XP penalty section above

## Jam Fest breakpoints

These are the effective song levels with Jam Fest AAs:

| Song | Base | JF1 | JF2 | JF3 | JF1 | JF2 | JF3 |
|------|------|-----|-----|-----|-----|-----|-----|
| Player Level | 60 | 61 | 63 | 65 | 66 | 68 | 70 |
| Assonance | 25 | | 26 | | 27 | | 28 |
| Frost/Flame | 31 | | 32 | 33 | 34 | 35 | 36 |
| Discord | 19 | | | 20 | | 21 | |
| Dissonance | 17 | | | 18 | | 19 | |
| Cessation | 32 | | 33 | 34 | 35 | 36 | 37 |
| Fufils | 21 | | 22 | | 23 | | 24 |
