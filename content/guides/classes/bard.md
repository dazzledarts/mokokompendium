---
title: Bard Guide
class: Mage
subclass: Bard
class_id: 204
description: In-progress guide for Bard including Desperate Salvation (Support) and True Courage (DPS) builds with Ark Grid variants.
identity:
  name: Serenade of Courage / Serenade of Salvation
  description: Bard has an identity gauge that can be used to cast a party heal or party damage buff. This identity gauge is filled by hitting an enemy with your skills. Certain skills fill your identity gauge much faster than other skills. This identity gauge is often referred to as Bard's 'meter', with the individual bars often referred to as 'bubbles.'
synergy:
  name: Note Brand
  description: Increases damage received by all party members by 10%.
  skills:
    - Sonatina
    - Sound Shock
builds:
  - name: True Courage (DPS)
    engraving: True Courage
    description: Non-directional damage class with melee positioning.
    playstyle: Build identity gauge and buff yourself to unlock a large damaging skill.
    difficulty: easy
    identity:
      name: Serenade of Courage / Tempest
      description: DPS Bard builds an identity gauge that is used for a self-damage buff and unlocks a high damaging skill on recast. The identity gauge is filled by hitting an enemy with your skills. The identity gauge is often referred to as individual 'bars' or 'bubbles.'
    synergy:
        name: Defense Reduction
        description: Reduces defense of enemies by -12%.
        skills:
          - Sonatina
    preArkGrid:
      description: Pre-Ark Grid setup follows the same build as 112 Ark Grid Build. See Ark Passive Tips for Crit stat allocation.
    engravings:
      - name: Grudge
        priority: required
      - name: Adrenaline
        priority: required
      - name: Keen Blunt Weapon
        priority: required
      - name: Raid Captain
        priority: required
      - name: Cursed Doll
        priority: recommended
      - name: Mass Increase
        priority: recommended
      - name: Stabilized Status
        priority: optional
    variants:
      - name: 11x
        difficulty: 1
        recommended: true
        description: Standard True Courage build. Sound Blitz core Recommended. Flexibile sending consistent 2-bars or saving up to 3-bars for burst windows.
        arkgrid_cores: Serenade of Fortitude + Pious Serenade + Sound Blitz (112 Soundholic) | Serenade of Fortitude + Pious Serenade + Sonic Enhancement (111 Sonic Vibration + Harp)
        priorities:
          - Upkeep your damage synergy, Sonatina and maintain Adrenaline stacks.
          - Damage skills must be cast within Heavenly Tune window (8 seconds).
          - Sync your Heavenly Tune with Sonic Vibration.
          - Cast Serenade of Courage and Tempest at 2 or 3 bars.
          - You have 5 seconds to send Tempest. DO NOT MISS.
          - Reposition Harp of Rhythm if necessary.
          - Cast meter generation skills during downtime.
        arkPassiveTips:
          - Adjust your crit rate as close to 100% without overcapping. It is fine to have 97-99%. Heavenly Tune provides +20% crit rate.
          - Swap to Keen Sense 1 if you need additional crit rate. Use Master + Critical if you need more.
          - 1115 Crit = 53% with High CritRate% rings (Recommended).
          - Raid Captain is efficient with 136% movement speed, or 1281 Swiftness plus a 5% Feast. Excess stats should be placed into Swiftness (Recommended) or Specialization.
          - Specialization only increases Serenade meter generation. This does not increase buff efficiency or skill damage for True Courage Bard.
          - Hymn of Combat turns Serenade of Courage into another damage ability, but requires sticking close to the boss on cast.
          - You may take 3/3 Stormfield and 2/5 Mad Dash for a slight DPS loss, if the boss is mobile, or if you don’t like the shackle.
        arkPassives:
          - name: Crit
            points: 0
            category: evolution
            tier: 1
          - name: Swiftness
            points: 21
            category: evolution
            tier: 1
          - name: Limit Break
            points: 3
            category: evolution
            tier: 2
          - name: Unlimited Magick
            points: 2
            category: evolution
            tier: 3
          - name: Critical
            points: 1
            category: evolution
            tier: 4
          - name: Pulverize
            points: 1
            category: evolution
            tier: 4
          - name: Standing Striker
            points: 2
            category: evolution
            tier: 5
          - name: True Courage
            points: 1
            category: enlightenment
            tier: 1
          - name: "Hymn: Tempest"
            points: 3
            category: enlightenment
            tier: 2
          - name: Hymn of Combat
            points: 5
            category: enlightenment
            tier: 3
          - name: Maestro
            points: 3
            category: enlightenment
            tier: 3
          - name: Stormfield
            points: 2
            category: enlightenment
            tier: 4
          - name: Mad Dash
            points: 1
            category: enlightenment
            tier: 4
          - name: Transcendent Power
            points: 5
            category: leap
            tier: 1
          - name: Unleashed Power
            points: 4
            category: leap
            tier: 1
          - name: Instant Spell
            points: 2
            category: leap
            tier: 1
          - name: Ostinato
            points: 3
            category: leap
            tier: 2
        skills:
          - name: Heavenly Tune
            level: 10
            tripods:
              - Quick Prep
              - Tough Tune
              - Tune for Me
            rune: Galewind
            rune_rarity: legendary
            notes: |-
              **Self Buff, Crit Rate Buff, Mana Regeneration, Paralysis Immune**
              - Increases your Attack Power by 25%.
              - <tripod>Courageous Tune</tripod> can be used over <tripod>Tough Tune</tripod> to provide raidwide damage mitigation on hit.
              - Tough Tune is mandatory if you are running Mass Increase engraving.
              - Heavenly Tune's mana regeneration does NOT stack with Support Bards in the same party. You still gain the support AP buff.
          - name: Sonatina
            level: 14
            tripods:
              - Quick Prep
              - Note Brand
              - Increase Melody
            rune: Wealth
            rune_rarity: rare
            notes: |-
              **Synergy, Weakpoint, Meter Generation, Paralysis Immune**
              - <tripod>Note Brand</tripod> applies -12% defense down synergy on enemies.
              - Keep this applied at all times.
              - Swap to Purify rune if the raid calls for self-cleanse.
          - name: Sonic Vibration
            level: 14
            tripods:
              - Tenacity
              - Chain Vibration
              - Spreading Vibration
            rune: Galewind
            rune_rarity: legendary
            notes: |-
              **Main Damage Skill, High Weakpoint, Paralysis Immune, Optional Push Immunity**
              - Cast inside Heavenly Tune window.
              - Full damage if initial cast and lingering ball hits.
              - <tripod>Tenacity</tripod> can be replaced with <tripod>Agile Cast</tripod> (NOT Recommended).
          - name: Wind of Music
            level: 10
            tripods:
              - Quick Prep
              - Melody Increase
              - Superspeed Cast
            rune: Wealth
            rune_rarity: legendary
            notes: |-
              **Highest Meter Generator, Stagger, Paralysis Immune**
              - Cast this skill off cooldown (close range).
              - Good burst stagger.
          - name: Soundholic
            level: 14
            tripods:
              - Sound Concentration
              - Sustain Enhancement
              - Melody Increase
            rune: Wealth
            rune_rarity: epic
            notes: |-
              **High Meter Generator, Damage Skill, Stagger, Paralysis Immune**
              - <tripod>Focus Fire</tripod> and damage gem MANDATORY for Sound Blitz core (Recommended).
              - Back Attack with Sound Blitz core whenever possible. Do not delay your casts to chase Back.
              - Inputting another skill or movement will preemptively cancel Soundholic.
          - name: Harp of Rythmn
            level: 14
            tripods:
              - Summoning Will
              - Melody Increase
              - Giant Harp
            rune: Bleed
            rune_rarity: legendary
            notes: |-
              **Meter Generator, Damage Skill, NO Immunity**
              - <tripod>Agile Rapid Fire</tripod> and damage gem MANDATORY for Sonic Enhancement core. Replace Soundholic damage gem.
              - Harp of Rhythm is entirely stationary. Recast harp if the boss moves out of range.
              - Press Shift on desired target to change the skill's target for raids with multiple minions. Active target has an orange ring around their feet.
              - Swap to <tripod>Note Brand</tripod> at a damage loss, if you are struggling with synergy upkeep.
          - name: Rhythm Buckshot
            level: 10
            tripods:
              - Melody Increase
              - Tenacity
              - Agile Cast
            rune: Wealth
            rune_rarity: epic
            notes: |-
              **Meter Generation, Counter, Weak Point, Stagger, Push Immune**
              - One of the two available counters (Melee, Cone)
              - Should be used off cooldown primarily for meter generation.
              - Yes, this skill is loaded.
          - name: Prelude of Storm
            level: 10
            tripods:
              - Quick Prep
              - Melody Increase
              - Powerful Prelude
            rune: Wealth
            rune_rarity: rare
            notes: |-
              **Meter Generation, Counter, NO Immunity**
              - One of the two available counters (Melee, AOE)
              - Inferior to Rhythm Buckshot as a counter, but similar meter gain with a small cooldown advantage.
              - Initial hit accounts for 50% of the meter generation, <tripod>Powerful Prelude</tripod> generates 16.7% per tick over 2 seconds.
          - name: Vivace
            level_label: Hyper Awakening Technique
            notes: |-
              **Main Damage Skill, Stagger, Paralysis Immune**
              - Ostinato (Leap Tree) turns Vivace into a Normal cast.
              - Fits inside every 4th Heavenly Tune cast.
          - name: Symphonia / Symphony Melody
            icon: Symphonia
            level_label: Awakening / Hyper Awakening
            notes: |-
              **Fixed Meter Generation Skill**
              - Provides 1 bar upon completion. Hitting the boss is optional.
              - Allows more Tempest casts over the course of the fight.
              - Casting Hyper Awakening will block the next lethal attack within 30 seconds (excluding wipe mechs).
        gems:
          - skill: Tempest
            type: damage
            priority: 1
          - skill: Sonic Vibration
            type: damage
            priority: 2
          - skill: Soundholic
            type: damage
            priority: 3
          - skill: Heavenly Tune
            type: cooldown
            priority: 1
          - skill: Sonic Vibration
            type: cooldown
            priority: 2
          - skill: Wind of Music
            type: cooldown
            priority: 3
          - skill: Soundholic
            type: cooldown
            priority: 4
          - skill: Rhythm Buckshot
            type: cooldown
            priority: 5
          - skill: Sonatina
            type: cooldown
            priority: 6
          - skill: Prelude of Storm
            type: cooldown
            priority: 7
          - skill: Harp of Rhythm
            type: cooldown
            priority: 8
        dps_distribution:
          - name: Tempest
            dmg: 51
          - name: Vivace
            dmg: 14
          - name: Sonic Vibration
            dmg: 9
          - name: Serenade of Courage
            dmg: 9
          - name: Soundholic
            dmg: 7
          - name: Harp of Rhythm
            dmg: 4
          - name: Sonatina
            dmg: 1
          - name: Heavenly Tune
            dmg: 0.5
          - name: Wind of Music
            dmg: 0.5
          - name: Prelude of Storm
            dmg: 0.4
          - name: Rhythm Buckshot
            dmg: 0.4
        rotation_sections:
          - title: Damage Rotation Priority
            steps:
              - Heavenly Tune
              - Serenade of Courage
              - Tempest
              - Vivace
              - Sonic Vibration
              - Soundholic
              - Harp of Rhythm
          - title: Meter Generation Priority
            steps:
              - Wind of Music
              - Soundholic
              - Prelude of Storm
              - Rhythm Buckshot
              - Harp of Rhythm
      - name: !!str 222
        difficulty: 1
        recommended: false
        description: Unable to cast 3-bar Tempest, but significantly increases 2-bar and normal skill damage. More downtime between Tempests due to Sun core. Similar playstyle to 11x (Recommended).
        arkgrid_cores: Tempest Refrain + Second Impact + Sound Blitz
        priorities:
          - Upkeep your damage synergy, Sonatina and maintain Adrenaline stacks.
          - Damage skills must be cast within Heavenly Tune window (8 seconds).
          - Sync your Heavenly Tune with Sonic Vibration.
          - Cast Serenade of Courage and Tempest at 2 bars.
          - You have 5 seconds to send Tempest. DO NOT MISS.
          - Reposition Harp of Rhythm if necessary.
          - Cast meter generation skills during downtime.
        arkPassiveTips:
          - Adjust your crit rate as close to 100% without overcapping. It is fine to have 97-99%. Heavenly Tune provides +20% crit rate.
          - Swap to Keen Sense 1 if you need additional crit rate. Use Master + Critical if you need more.
          - 1115 Crit = 53% with High CritRate% rings (Recommended).
          - Raid Captain is efficient with 136% movement speed, or 1281 Swiftness plus a 5% Feast. Excess stats should be placed into Swiftness (Recommended) or Specialization.
          - Specialization only increases Serenade meter generation. This does not increase buff efficiency or skill damage for True Courage Bard.
          - Tempest, Vivace, and Hymn of Combat are not buffed by 17p Sun core, therefore we use 3/3 Stormfield instead.
        arkPassives:
          - name: Crit
            points: 0
            category: evolution
            tier: 1
          - name: Swiftness
            points: 21
            category: evolution
            tier: 1
          - name: Limit Break
            points: 3
            category: evolution
            tier: 2
          - name: Unlimited Magick
            points: 2
            category: evolution
            tier: 3
          - name: Critical
            points: 1
            category: evolution
            tier: 4
          - name: Pulverize
            points: 1
            category: evolution
            tier: 4
          - name: Standing Striker
            points: 2
            category: evolution
            tier: 5
          - name: True Courage
            points: 1
            category: enlightenment
            tier: 1
          - name: "Hymn: Tempest"
            points: 3
            category: enlightenment
            tier: 2
          - name: Maestro
            points: 3
            category: enlightenment
            tier: 3
          - name: Stormfield
            points: 3
            category: enlightenment
            tier: 4
          - name: Mad Dash
            points: 2
            category: enlightenment
            tier: 4
          - name: Transcendent Power
            points: 5
            category: leap
            tier: 1
          - name: Unleashed Power
            points: 4
            category: leap
            tier: 1
          - name: Instant Spell
            points: 2
            category: leap
            tier: 1
          - name: Ostinato
            points: 3
            category: leap
            tier: 2
        skills:
          - name: Heavenly Tune
            level: 10
            tripods:
              - Quick Prep
              - Tough Tune
              - Tune for Me
            rune: Galewind
            rune_rarity: legendary
            notes: |-
              **Self Buff, Crit Rate Buff, Mana Regeneration, Paralysis Immune**
              - Increases your Attack Power by 25%.
              - <tripod>Courageous Tune</tripod> can be used over <tripod>Tough Tune</tripod> to provide raidwide damage mitigation on hit.
              - Tough Tune is mandatory if you are running Mass Increase engraving.
              - Heavenly Tune's mana regeneration does NOT stack with Support Bards in the same party. You still gain the support AP buff.
          - name: Sonatina
            level: 14
            tripods:
              - Quick Prep
              - Note Brand
              - Increase Melody
            rune: Wealth
            rune_rarity: rare
            notes: |-
              **Synergy, Weakpoint, Meter Generation, Paralysis Immune**
              - <tripod>Note Brand</tripod> applies -12% defense down synergy on enemies.
              - Keep this applied at all times.
              - Swap to Purify rune if the raid calls for self-cleanse.
          - name: Sonic Vibration
            level: 14
            tripods:
              - Tenacity
              - Chain Vibration
              - Spreading Vibration
            rune: Galewind
            rune_rarity: legendary
            notes: |-
              **Main Damage Skill, High Weakpoint, Paralysis Immune, Optional Push Immunity**
              - Cast inside Heavenly Tune window.
              - Full damage if initial cast and lingering ball hits.
              - <tripod>Tenacity</tripod> can be replaced with <tripod>Agile Cast</tripod> (NOT Recommended).
          - name: Wind of Music
            level: 10
            tripods:
              - Quick Prep
              - Melody Increase
              - Superspeed Cast
            rune: Wealth
            rune_rarity: legendary
            notes: |-
              **Highest Meter Generator, Stagger, Paralysis Immune**
              - Cast this skill off cooldown (close range).
              - Good burst stagger.
          - name: Soundholic
            level: 14
            tripods:
              - Sound Concentration
              - Sustain Enhancement
              - Melody Increase
            rune: Wealth
            rune_rarity: epic
            notes: |-
              **High Meter Generator, Damage Skill, Stagger, Paralysis Immune**
              - <tripod>Focus Fire</tripod> and damage gem MANDATORY for Sound Blitz core (Recommended).
              - Back Attack with Sound Blitz core whenever possible. Do not delay your casts to chase Back.
              - Inputting another skill or movement will preemptively cancel Soundholic.
          - name: Harp of Rythmn
            level: 14
            tripods:
              - Summoning Will
              - Melody Increase
              - Giant Harp
            rune: Bleed
            rune_rarity: legendary
            notes: |-
              **Meter Generator, Damage Skill, NO Immunity**
              - Harp of Rhythm is entirely stationary. Recast harp if the boss moves out of range.
              - Press Shift on desired target to change the skill's target for raids with multiple minions. Active target has an orange ring around their feet.
              - Swap to <tripod>Note Brand</tripod> at a damage loss, if you are struggling with synergy upkeep.
          - name: Rhythm Buckshot
            level: 10
            tripods:
              - Melody Increase
              - Tenacity
              - Agile Cast
            rune: Wealth
            rune_rarity: epic
            notes: |-
              **Meter Generation, Counter, Weak Point, Stagger, Push Immune**
              - One of the two available counters (Melee, Cone)
              - Should be used off cooldown primarily for meter generation.
              - Yes, this skill is loaded.
          - name: Prelude of Storm
            level: 10
            tripods:
              - Quick Prep
              - Melody Increase
              - Powerful Prelude
            rune: Wealth
            rune_rarity: rare
            notes: |-
              **Meter Generation, Counter, NO Immunity**
              - One of the two available counters (Melee, AOE)
              - Inferior to Rhythm Buckshot as a counter, but similar meter gain with a small cooldown advantage.
              - Initial hit accounts for 50% of the meter generation, <tripod>Powerful Prelude</tripod> generates 16.7% per tick over 2 seconds.
          - name: Vivace
            level_label: Hyper Awakening Technique
            notes: |-
              **Main Damage Skill, Stagger, Paralysis Immune**
              - Ostinato (Leap Tree) turns Vivace into a Normal cast.
              - Fits inside every 4th Heavenly Tune cast.
          - name: Symphonia / Symphony Melody
            icon: Symphonia
            level_label: Awakening / Hyper Awakening
            notes: |-
              **Fixed Meter Generation Skill**
              - Provides 1 bar upon completion. Hitting the boss is optional.
              - Allows more Tempest casts over the course of the fight.
              - Casting Hyper Awakening will block the next lethal attack within 30 seconds (excluding wipe mechs).
        gems:
          - skill: Tempest
            type: damage
            priority: 1
          - skill: Sonic Vibration
            type: damage
            priority: 2
          - skill: Soundholic
            type: damage
            priority: 3
          - skill: Heavenly Tune
            type: cooldown
            priority: 1
          - skill: Sonic Vibration
            type: cooldown
            priority: 2
          - skill: Wind of Music
            type: cooldown
            priority: 3
          - skill: Soundholic
            type: cooldown
            priority: 4
          - skill: Rhythm Buckshot
            type: cooldown
            priority: 5
          - skill: Sonatina
            type: cooldown
            priority: 6
          - skill: Prelude of Storm
            type: cooldown
            priority: 7
          - skill: Harp of Rhythm
            type: cooldown
            priority: 8
        rotation_sections:
          - title: Damage Rotation Priority
            steps:
              - Heavenly Tune
              - Serenade of Courage
              - Tempest
              - Vivace
              - Sonic Vibration
              - Soundholic
              - Harp of Rhythm
          - title: Meter Generation Priority
            steps:
              - Wind of Music
              - Soundholic
              - Prelude of Storm
              - Rhythm Buckshot
              - Harp of Rhythm
      - name: !!str 333
        difficulty: 1
        recommended: false
        description: Spreads damage amongst Normal Skills at the cost of limited meter generation. Sound Shock becomes your bread and butter skill. Not forced to play in melee range. "Note:" As of July 2026, this build lacks significant damage (upwards of 12% compared to 11x) and NOT recommended. Play this build only because you want to.
        arkgrid_cores: Shock Loop + Harmonious Confluence + Binary Shock
        priorities:
          - Upkeep your damage synergy, Sonatina and maintain Adrenaline stacks.
          - Damage skills must be cast within Heavenly Tune window (8 seconds).
          - Destiny buffs your next two Sound Shock casts via Heavenly Tune.
          - Cast Serenade of Courage and Tempest at 2 or 3 bars.
          - You have 5 seconds to send Tempest. DO NOT MISS.
          - Reposition Harp of Rhythm if necessary.
        arkPassiveTips:
          - Adjust your crit rate as close to 100% without overcapping. It is fine to have 97-99%. Heavenly Tune provides +20% crit rate.
          - Swap to Keen Sense 1 if you need additional crit rate. Use Master + Critical if you need more.
          - 1115 Crit = 53% with High CritRate% rings (Recommended).
          - Raid Captain is efficient with 136% movement speed, or 1281 Swiftness plus a 5% Feast. Excess stats should be placed into Swiftness (Recommended).
          - Sun Core reduces meter generation by 100%. This means Specialization has no use for this build.
          - More priority on Normal Skills for damage, therefore we take 3/3 Stormfield and 2/5 Mad Dash.
        arkPassives:
          - name: Crit
            points: 0
            category: evolution
            tier: 1
          - name: Swiftness
            points: 21
            category: evolution
            tier: 1
          - name: Limit Break
            points: 3
            category: evolution
            tier: 2
          - name: Unlimited Magick
            points: 2
            category: evolution
            tier: 3
          - name: Critical
            points: 1
            category: evolution
            tier: 4
          - name: Pulverize
            points: 1
            category: evolution
            tier: 4
          - name: Standing Striker
            points: 2
            category: evolution
            tier: 5
          - name: True Courage
            points: 1
            category: enlightenment
            tier: 1
          - name: "Hymn: Tempest"
            points: 3
            category: enlightenment
            tier: 2
          - name: Maestro
            points: 3
            category: enlightenment
            tier: 3
          - name: Stormfield
            points: 3
            category: enlightenment
            tier: 4
          - name: Mad Dash
            points: 2
            category: enlightenment
            tier: 4
          - name: Transcendent Power
            points: 5
            category: leap
            tier: 1
          - name: Unleashed Power
            points: 4
            category: leap
            tier: 1
          - name: Instant Spell
            points: 2
            category: leap
            tier: 1
          - name: Ostinato
            points: 3
            category: leap
            tier: 2
        skills:
          - name: Heavenly Tune
            level: 10
            tripods:
              - Quick Prep
              - Tough Tune
              - Tune for Me
            rune: Galewind
            rune_rarity: legendary
            notes: |-
              **Self Buff, Crit Rate Buff, Mana Regeneration, Paralysis Immune**
              - Increases your Attack Power by 25%.
              - <tripod>Courageous Tune</tripod> can be used over <tripod>Tough Tune</tripod> to provide raidwide damage mitigation on hit.
              - Tough Tune is mandatory if you are running Mass Increase engraving.
              - Heavenly Tune's mana regeneration does NOT stack with Support Bards in the same party. You still gain the support AP buff.
              - Optional Quick Recharge (epic)
          - name: Sonatina
            level: 11
            tripods:
              - Quick Prep
              - Note Brand
              - Recital
            rune: Bleed
            rune_rarity: legendary
            notes: |-
              **Synergy, Weakpoint, Paralysis Immune**
              - <tripod>Note Brand</tripod> applies -12% defense down synergy on enemies.
              - Keep this applied at all times.
          - name: Sound Shock
            level: 14
            tripods:
              - Maintained Explosion
              - Shock Enhancement
              - Rapid Fire
            rune: Quick Recharge
            rune_rarity: legendary
            notes: |-
              **Highest Meter Generator, Damage, High Stagger, Paralysis Immune (Star Core)**
              - Main source of meter generation. This is a fixed amount of meter, about ~50% on crit.
              - MUST CRIT to generate any meter.
              - Activating Destiny buffs the next 2 casts of Sound Shock.
          - name: Sonic Vibration
            level: 14
            tripods:
              - Tenacity
              - Chain Vibration
              - Spreading Vibration
            rune: Galewind
            rune_rarity: legendary
            notes: |-
              **Main Damage Skill, High Weakpoint, Paralysis Immune, Optional Push Immunity**
              - Cast inside Heavenly Tune window.
              - Full damage if initial cast and lingering ball hits.
              - <tripod>Tenacity</tripod> can be replaced with <tripod>Agile Cast</tripod> (NOT Recommended).
          - name: Stigma
            level: 14
            tripods:
              - Sustain Enhancement
              - Storm Stigma
              - Stigma of Pain
            rune: Galewind
            rune_rarity: epic
            notes: |-
              **Damage, Stagger, Paralysis Immune**
              - Long casting skill, ramping damage over time.
              - Homing skill will chase after the boss due to <tripod>Storm Stigma</tripod>
              - Can animation cancel into Sonic Vibration to reduce casting time.
              - Requires "Skills Instant Cast" to be turned off (Settings, Gameplay, Control Settings).
          - name: Soundholic
            level: 14
            tripods:
              - Sound Concentration
              - Sustain Enhancement
              - Focus Fire
            rune: Vision
            rune_rarity: legendary
            notes: |-
              **Damage, Stagger, Paralysis Immune**
              - Lowest priority damage skill.
              - Do not delay your casts to chase Back.
              - Inputting another skill or movement will preemptively cancel Soundholic.
          - name: Harp of Rythmn
            level: 14
            tripods:
              - Summoning Will
              - Melody Increase
              - Giant Harp
            rune: Bleed
            rune_rarity: legendary
            notes: |-
              **Fixed Meter Generator, Damage, NO Immunity**
              - <tripod>Melody Increase</tripod> provides a fixed 1% meter/second, NOT reduced by Destiny.
              - Harp of Rhythm is entirely stationary. Recast harp if the boss moves out of range.
              - Press Shift on desired target to change the skill's target for raids with multiple minions. Active target has an orange ring around their feet.
              - Swap to <tripod>Note Brand</tripod> at a damage loss, if you are struggling with synergy upkeep.
          - name: Rhythm Buckshot
            level: 7
            tripods:
              - Mind Enhancement
              - Tenacity
            rune: Purify
            rune_rarity: legendary
            notes: |-
              **Counter, Weak Point, Stagger, Push Immune**
              - You can hold this skill as a counter or emergency push immunity.
          - name: Vivace
            level_label: Hyper Awakening Technique
            notes: |-
              **Main Damage Skill, Stagger, Paralysis Immune**
              - Ostinato (Leap Tree) turns Vivace into a Normal cast.
              - Fits inside every 4th Heavenly Tune cast.
          - name: Symphonia / Symphony Melody
            icon: Symphonia
            level_label: Awakening / Hyper Awakening
            notes: |-
              **Fixed Meter Generation Skill**
              - Provides 1 bar upon completion. Hitting the boss is optional.
              - Allows more Tempest casts over the course of the fight.
              - Casting Hyper Awakening will block the next lethal attack within 30 seconds (excluding wipe mechs).
        gems:
          - skill: Tempest
            type: damage
            priority: 1
          - skill: Sonic Vibration
            type: damage
            priority: 2
          - skill: Sound Shock
            type: damage
            priority: 3
          - skill: Stigma
            type: damage
            priority: 4
          - skill: Soundholic
            type: damage
            priority: 5
          - skill: Heavenly Tune
            type: cooldown
            priority: 1
          - skill: Sonic Vibration
            type: cooldown
            priority: 2
          - skill: Sound Shock
            type: cooldown
            priority: 3
          - skill: Stigma
            type: cooldown
            priority: 4
          - skill: Sonatina
            type: cooldown
            priority: 5
          - skill: Harp of Rhythm
            type: cooldown
            priority: 6
        dps_distribution:
          - name: Tempest
            dmg: 42
          - name: Vivace
            dmg: 17
          - name: Sonic Vibration
            dmg: 12
          - name: Sound Shock
            dmg: 8
          - name: Stigma
            dmg: 7
          - name: Soundholic
            dmg: 6
          - name: Harp of Rhythm
            dmg: 5
          - name: Sonatina
            dmg: 1.5
        rotation_sections:
          - title: General Damage Rotation
            steps:
              - Serenade of Courage
              - Heavenly Tune
              - Sound Shock
              - Tempest
              - Vivace
              - Stigma
              - Sonic Vibration
              - Sound Shock
              - Soundholic
          - title: Meter Generation Priority
            steps:
              - Sound Shock
              - Harp of Rhythm


---
