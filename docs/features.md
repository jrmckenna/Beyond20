# Virtual Tabletops supported
* [Roll 20](https://roll20.net)
* [Foundry VTT](https://foundryvtt.com)
* [Discord Integration](https://discord.com) -- [Instructions](/discord)
* D&D Beyond Dice Roller

# Feature list

See the [Screenshots](screenshots) page for a video tour of all the features listed here.

## Character Sheet
* Ability checks
* Saving throws
* Skill checks
  * Custom skills (if no ability is specified, the player is queried in the VTT)
* Initiative rolls
  * Rolls with Advantage if the character has the feat
  * Adds the initiative to the tracker
* Support for custom roll and damage dice bonuses
* Mellee weapon attacks
* Ranged weapon attacks
  * Support for Two-handed damage
  * Support for weapons dealing more than one type of damage
  * Support for custom weapons
  * Support for critical damage
* Attack spells
  * Support for multiple damages
  * Support spells with saving throw or To-Hit, or with straight damage
  * Can display the spell instead of rolling it if wanted
* Hit dice
  * Supports multi-classing
* Death saving throws
* `+ X` modifier in descriptions (Will roll a `1d20 + X`)
* The attack spell modifiers can be clicked to roll the dice if needed
* Dice formulas in descriptions can be clicked to roll the dice
  * Dice formulas are detected in items, spells, actions or custom actions, class features, racial traits or Feats
  * The dice formula is clickable in the D&D beyond side panel, as well as in the VTT chat text
  * The clickable dice can be disabled to not show in the D&D Beyond page or in the VTT text, separately
* Roll Superiority Dice
* Roll Bardic Inspiration Dice
* Condition tracking
* Creatures stat blocks
* Vehicles stat blocks
* Tools

## Monsters and Character creatures
* Hit points
* Initiative roll
* Ability checks
* Saving throws
* Skills
* Dice formulas in features/action descriptions
* Ranged and Melee weapon attacks
* Display spells from tooltip information
* Monsters from the My Encounters page directly supported

## Vehicles
* Ability checks

## Spell Compendium Pages
* Dice formulas from description
* Display button to display the spell card

## Information sharing
* Spell cards can be displayed in VTT
  * Higher level casts will be detected and shown
* Attack spells can also be displayed instead of rolled
* Attack spells with material components will have the material printed
* Equipment Items
* Weapons can also be displayed instead of rolled
* Actions and custom actions
* Class feature
* Racial traits
* Feats
* Character traits

## Special Class Features/Racial Traits/Feats supported
* Feat: Sharpshooter
* Feat: Great Weapon Master
* Feat: Elven Accuracy (Via super advantage option)
* Feat: Polearm Master
* Artificer: Arcane Firearm
* Barbarian: Rage
* Barbarian: Brutal Critical
* Bard: Blade Flourish
* Bard: Psychic Blades
* Bard: Jack of All Trades
* Bloodhunter: Crimson Rite
* Cleric: Disciple of Life (Life domain)
* Cleric: Divine Strike
* Fighter: Maneuvers
* Fighter: Improved Critical and Superior Critical (Champion)
* Fighter: Rune Knight's Giant Might (UA)
* Fighting Style: Great Weapon Fighting
* Paladin: Legendary Strike (UA)
* Paladin: Improved Divine Smite
* Ranger: Dread Ambusher
* Rogue: Sneak Attack
* Rogue: Assassinate
* Sorcerer: Elemental Affinity
* Warlock: Hexblade's Curse
* Half-Orc: Savage Attacks

# Special Spells supported
* Chromatic Orb: Macro to ask which damage type to use
* Chaos Bolt: Damage type set to 'chaotic energy' instead of rolling for each damage (Roll20) or query damage type depending on roll result.
* Absorb Elements: Damage type is set to 'Absorbed type' instead of rolling each
* Toll the Dead: Queries the player if the enemy is missing hit points
* Life Transference: Healing is shown equal to the necrotic damage


## Configurable options
* Whisper rolls (yes, no, query the user)
* Whisper rolls for monster pages
* Incognito rolls for monster pages
* Roll types (normal, roll twice, roll thrice, query the user, roll with advantage, roll with disadvantage, roll with super advantage, roll with super disadvantage)
* Auto roll damage and crit
* Add initiative to the tracker (requires token to be selected)
* Automatically update HP and Temp HP in the VTT sheets and tokens
* Roll20 Character Sheet Template to use
  * D&D 5E By Roll20
  * Other Templates
* Replace dice formulas in VTT text
* Add dice formulas roller icon to D&D Beyond spell page and character sheet
* Add dice formulas roller icon to D&D Beyond stat blocks
* Add roll buttons to monster, creature and vehicle stat blocks
* Prefix to add to critical hit damage
* Critical hit additional damage rules
  * Standard PHB rule (reroll dice)
  * Homebrew Rule: Perfect rolls
  * Homebrew Rule: Add modifiers to rolls
  * Homebrew Rule: Reroll all the damages
* Components to display during a spell attack
  * All components (V, S, M)
  * Only material components if needed
  * No components
* Prefix to display with spell components during an attack
* VTT tab specific options
  * Select a tab to send all rolls to
  * Select the campaign (Roll2) or world (Foundry VTT) to send the rolls to
  * Send rolls to All tabs, Only Roll20 Tabs, Only Foundry VTT Tabs
* D&D Beyond character specific options
  * Custom roll dice formula bonus
  * Custom damage dice formula bonus
  * Versatile weapon choice (one-handed, two-handed, roll both options)
  * Send sneak attack damage (Only Rogues)
  * Send Disciple of Life healing bonus (Only Life domain Cleric)
  * Add Jack of all Trades bonus to raw ability checks (Only Bards >= 2nd level)
  * Apply Sharpshooter Feat for the next roll (Only if Feat is available)
  * Apply Great Weapon Master Feat for the next roll (Only if Feat is available)
  * Add Brutal Critical and Savage Attacks damage to critical hits (Only Barbarians with the feature, or Half-Orcs)
  * Add Rage damage and advantage on STR checks (Only Barbarians)

## Roll20 Character Sheet Templates
* D&D 5e By Roll20
  * This is the official character sheet template I used and developed for and the one I recommend
* Fallback option for all other templates


## Misc
* Chrome support
* Firefox support
* Friendly developer :)
