## [v1.2.1](../../tree/1.2.1) (16.07.2019)
* :bug: **Bugfix** Racial Template Variant now editable 
* Note: Race2 includes explanation of erronous statblocks at level 1 for custom races, compared to in-game experience
* The sheet will now warn you that you are illegal at any point where you have not taken the mandatory first three levels of a class in sequence

## [v1.2.0](../../tree/1.2.0) (16.07.2019)
* :bug: **Bugfix** Superior Skill Affinity Bluff now grants +6 instead of +7
* Consistent sorting of important/other racial feats to make sure all mechanically essential feats are registered
* Implemented Racial Templates to cover Arelith custom races that may be taken with various base races
* Implemented Arelith races: Aasimar, Tiefling, Genasi, Vampire
* Racial template ability score changes are applied after base race and gifts.

## [v1.1.2](../../tree/1.1.2) (15.07.2019)
* :bug: **Bugfix** ECL calculation was off-by-one row when selecting gifts
* :bug: **Bugfix** Gift validation list no longer offering empty values
* (Epic) Skill Focus Listen/Spot now grants its bonus to both skills
* (Epic) Skill Focus Hide/Move Silently now grants its bonus to both skills
* Moved racial weapon proficiencies to important feats; otherwise they don't register
* Gifts now show up in output

## [v1.1.1](../../tree/1.1.1) (14.07.2019)
* Class feat summary will no longer hide enumerated feats taken repeatedly, i.e. Harper Mage shows Automatic Quicken Spell at both level 1 + 5
* Master Harper's bonus feat Skill Focus Perform now grants the appropriate skill bonus
* Quarterstaff and katana now finessable
* Removed XP penalty nonsense

## [v1.1](../../tree/1.1) (14.07.2019)
* Chosen gifts now affect ECL
* Racial Spell Resistance implemented as feats where static; otherwise based on race
* Skills now include bonuses granted by free class feats, including Detection and Skill Focuses

* Implemented Arelith Classes (abbr.): Healer (Cl), Totem Druid (Dr), Harper Mage (Ha), Harper Priest (Ha), Harper Paragon (Ha), Master Harper Ha), Archer (R), True Flame (So), Wild Mage (W), Spellsword (SS), Shadow Wizard (W), Shadow Sorcerer (So)
* Totems are implemented similarly to cleric domains, assuming totem choice at Druid level 1, granting only hard ability score changes. 
* Paladin gains +1 wisdom every 7th level
* Pale Master AC bonus halved
* Monk speed limited to +50
* Rogue gains Detection I at level 10 if already has Keen Sense; otherwise gains only Keen Sense
* Fighter/Spellsword discipline bonus implemented as low-display class feats
* Shadow Mages granted low-display class feat "Shadow Adept" to handle increased Enchantment/Illusion/Necromancy DC
* Shadowdancer's granted +1 hide/level (mimics bardic knowledge)
* Harper Paragon granted appropriate saves bonuses (similar to Sacred Defense) 
* Harper Priest stacks with divine classes for Turn Undead
* Master Harper stacks with Bard for bard song

## [v1.0](../../tree/1.0) (14.07.2019)
* All Arelith gifts implemented with appropriate bonuses to ability scores, skills, and saves.
* Gifts options are based on ECL from race

* Implemented Arelith races: Deep Imaskari, Gold Dwarf, Wild Dwarf, Duergar, Sun Elf, Wood Elf, Wild Elf, Drow, Forest Gnome, Svirfneblin, Strongheart Halfling, Ghostwise Halfling, Fey, Imp, Kobold, Goblin, Hobgoblin, Gnoll, Orog, Ogre, Troglodyte, Yuan-ti, Derro, Rakshasa. 
* Implemented Shield Dwarf, Moon Elf, Rock Gnome, and Lightfoot Halfling as aesthetic alternatives to generic races. 
* Half-Elf granted Dodge
* Half-Orc granted Ambidexterity, Power Attack, and "Intimidating" (+5 Intimidate)
* Added ECL column for races

* Implemented Arelith classes (abbr.): Fiend Warlock (Wa), Fey Warlock (Wa)
* Assassin and Ranger skill points increased to 6/level
* Arcane Archer now accepts Ranger as class prerequisite
* Bards now lawful
* Blackguard now only requires +6 BAB
* Dwarven Defender no longer requires Dodge
* Dwarven Defender grants Dodge at level 1
* Harper Scout grants appropriate sneak attack and skill feats
* Champion of Torm renamed to Divine Champion (CT) 
* Purple Dragon Knight now only requires Skill Focus: Discipline
* Purple Dragon Knight renamed to Knight (K)
* Monk granted a pathological plethora of feats
* Paladin granted Detect Evil at level 1
* Ranger granted Track, Defensive Dual Wielding, Uncanny Dodge, Woodland Stride, Evasion, and HiPS
* Rogue granted Lightly Armored, Weapon Finesse, Keen Sense, Detection, Sword and Dagger, Shady Deals, and Specialty Weapons
* Shadowdancer's HiPS moved to level 5
* Shadowdancer granted Shadow Fear and Shadow Stun
