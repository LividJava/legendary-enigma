---
id: zt2b4jmlfq0ddalfyaqppyx
title: Homebrew Rework/System Change
desc: ''
updated: 1692403194746
created: 1692223142677
---
<font size="5" color="red">This document is subject to change</font>

<details>
<summary>To-Do</summary>  

- [x] Character Conversion Process
  - [x] Attribute Equivalents
  - [x] Skill Equivalents (Dropped in favor of 5E skills)
- [x] Pokerole Move Table Conversion
  - [x] Type Weakness and Advantage
  - [x] Conversion Formula
  - [x] Ability (Dropped in favor of Classes)
- [x] Pokemon Racial Stats
  - [x] Movement (Using D&D Pokemon 5E)
  - [x] Extra Abilities (no plans)
  - [x] Natures? (Dropped for Alignments Which are also dropped)
- [ ] Homebrew Conversions
- [x] Homebrew Additions
  - [x] DC Gradient (Just because you failed the check, doesn't mean you've failed entirely)
</details>

# Scope
The goal of this document is to integrate certain functions of the Pokerole system and the PMD Add-on module within the D&D 5E system. It will largely express the current problems I have with the current Pokerole system and hope to address them. This will be run in sections to explain each core concept of both 5E and Pokerole, how they are planned to be merged, as well as a conversion system for the Moves.

For context this will only assume the setting is for the PMD Add-on and all player characters will be assuming the role of Pokemon.

# Character Creation
For the process of character creation, you'll largely follow the process of 5E for creating a character. Depending on your DM's preference of either Point Buy or Rolls. 

There are exceptions. Due to the nature of Magic using classes and Pokemon, it's advised that they be avoided where possible. As most magic casting could be replaced for Pokemon using Moves.

## Character Conversion
If you already have a character. You'll need to make a character from scratch effectively. Work with your DM to see what level you'd start at, what bonuses (if any) can be applied to character creation, and other things such as that. Your Character concept should remain largely unaffected.

## 5E Specific Stats
For this, Use [This site](https://pokedex-5e.herokuapp.com/) but ignore references to Moves, this is an incomplete list. Take note of the Hit Die and Movement Speeds and Size Class, which is required for the remainder of your character creation. 

# Pokemon Moves
This will heavily utilize the Pokerole rulebook, with adaptations to 5E See the table below for Equivalent Stats.

|Pokerole|D&D 5E|
|-:|:-|
|Strength|Strength|
|Dexterity|Dexterity|
|Vitality|Constitution|
|Special|Intelligence|
|Insight|Wisdom|
|Social Attributes[^1]|Charisma|
[^1]:Social attributes in this case are **Tough**, **Cool**, **Beauty**, **Cute**, and **Clever**. These are all rolled into the Charisma stat.

The moves a pokemon may learn are equal to their CL + WIS Modifier.
The Level of theses moves are also determined by CL using rank conversion.

## Using Moves
All moves are run against the AC of your opponent. To use a move Roll a 20-sided die and add the appropriate Attribute from the move's accuracy pool.

Below is an example using the move Tackle.
<details>
<summary>Tackle</Summary>

![Tackle. Power 2. Type Normal. Accuracy Pool, Dexterity+Brawl. Damage Pool, Strength+2.](image.png)

Seen above is the card for the move Tackle. When rolling to hit, take the Accuracy pool, and drop the Skill portion of it (Usually the second value), and Match it with the appropriate base Attribute.

If you hit, Roll the damage pool using your Hit Die + the Listed Attribute. (If no attribute is listed for the move or if the move specifies a specific damage type, just roll your hit die with no modifiers.)

#### Example
In a greater example. lets say you have a D&D Dexterity of 14 and Strength of 16. this would give you a +2 and +3 respectively as modifiers. And your Hit Die is a d8

You want to use the move Tackle, Roll to hit against the opponents AC, You rolled a 14 add the 2 from your DEX for a total of 16 to hit!

The attack hits! you roll a D8 for damage and add your STR. You rolled a 7 for a total of 10!
</details>

### Special Cases
In the event the move you want to use uses a Social Attribute (see [^1]) you simply replace it with your Charisma Modifier.

## Weakness, Resistance, and STAB
This section will cover how to calculate for your weakness, resistance, and STAB

#### Weakness
If you are weak against a certain move you take more damage than you normally would (+2, and +4 in cases of Double attack.)

#### Resistance
If you resist a certain move you take less damage (-2, and -4 in cases of double resistance, unless you are immune in which you take no damage)

#### STAB
Same Type Attack Bonus will let you add your CL divided by 4 rounded down.


## Difficulty Class Gradient
Due to my DMing Style, I am a Narrative First DM, meaning above all else, the story, the player's interactions with the world, and how the world reacts around them, come first.

In "Rules as Written" DC checks are largely you either Hit the DC or you fail. Frankly speaking, this sucks. and I much prefer utilizing this.

When interacting with an NPC, if you do not succeed the skill check *but fall within a few points short* things will swing in your favor, but not entirely. Just because you didn't pass the check doesn't mean your words did nothing.

This rule will be applied at the DMs discretion and when it applies will be largely unknown to the player for full immersion.



[^2]:*[CL]: Character Level 
*[WIS]: Wisdom Modifier
*[DEX]: Dexterity Modifier
*[STR]: Strength Modifier
*[DC]: Difficulty Class
*[AC]: Armor Class
*[STAB]: Same Type Attack Bonus