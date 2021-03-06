## [v2.1.0](../../tree/2.1.0) (06.09.2019)
* :bug: **Bugfix** Paragon now does not gain both Divine Grace and unisave boost unless it has paladin levels
* :bug: **Bugfix** Now validating all classes for prereqs, not just the first 26
* :bug: **Bugfix** All select buttons in Character are now changed to only highlight up to level 30
* :bug: **Bugfix** Spellcasting now manages to calculate again, phew

* Wood Elf now gains Weapon Focus: Longbow

## [v2.0.0](../../tree/2.0.0) (17.08.2019)
* :bug: **Bugfix** Ranger/Archer receives Uncanny Dodge at level 8, not 7
* Re-implemented harper classes as independent classes rather than references to Harper Scout (many various changes)
* Harper Scout no longer receives improved sneak attack, but does receive trackless step
* Harper Mage now receives spell penetration feats instead of automatic quicken spell
* Renamed Dwarven Defender to Earthkin Defender
* Updated class abbreviations

* Bonus feats set for Harper Scout
* Bonus feats set for Harper Mage
* Bonus feats set for Harper Paragon

* Updated class skills for harper classes and fighter
* Granted craft skills as universal class skills

* Fixed fixed base race notations
* Shaved off levels 31-40 as they don't exist on Arelith (the sheet is now approx. 20% lighter)

## [v1.2.3](../../tree/1.2.3) (03.08.2019)
* Output now shows "Minor Gift" and "Major Gift" placeholders
* Racial templates now accept subraces of applicable base races
* Changed naming conventions of racial skill affinities
* Spell focuses in Enchantment now grant cumulative bonus to Persuade, Perform, and Bluff

## [v1.2.2](../../tree/1.2.2) (23.07.2019)
* :bug: **Bugfix** No longer warns "0 = illegal" when starting a new class
* :bug: **Bugfix** Class validation now checks for 11+ Intelligence if wizard level is taken at level 1
* Racial Template + Variant now included in ECL calculation before gift options open
* Character now granted missing skill points at level 2 if granted a bonus to its intelligence score from gifts/racial templates
* Prestige class validation will now ignore you if you take shadowdancer levels with shadow mage
* Implemented shadow wizard specialists, shadow illusionist etc etc
* Added "base race" column to show what Arelith races are created from
* Prestige class validation now accept subraces for race prereqs, by looking at base race

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
