# PSYCHRONIC_EnemyClassesMZ

**RPG Maker MZ Plugin**

Adds class system to enemies (Minimal Interference)

## What It Does

Enemy Class Plugin This plugin allows you to assign classes to enemies using note tags.

## Plugin File

- `PSYCHRONIC_EnemyClassesMZ.js`
- Version: `1.2`
- Target: RPG Maker MZ
- Author: Psychronic
- URL: https://psychronic.itch.io

## Installation

1. Download `PSYCHRONIC_EnemyClassesMZ.js`.
2. Place it in your RPG Maker MZ project's `js/plugins/` folder.
3. Enable it from the RPG Maker Plugin Manager.
4. Configure any plugin parameters or commands listed below.

## Full Plugin Help

Enemy Class Plugin
This plugin allows you to assign classes to enemies using note tags.

Note Tag Usage:
<enemy class: ID> - Assigns class with specified ID to the enemy
Example: <enemy class: 21> - Gives the enemy class #21

The enemy's parameters will be influenced by the class's parameters
and traits in addition to their base stats.

Note: Class parameters are applied as if the enemy is level 1.
Traits from the class are added to the enemy's existing traits.
Enemy action patterns are preserved and unaffected by class assignment.

## Source

This standalone repository is generated from the latest PSYCHRONIC plugin source in the RPG Reactor Complex template.

## License

MIT. See `LICENSE`.
