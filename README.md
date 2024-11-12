# AI Project: Fantasy Battle Simulation in Prolog

## Overview

This project is a fantasy battle simulation implemented in **Prolog**. It models interactions between heroes and creatures in a game-like setting, using concepts such as vulnerabilities, attack types, and weapons or spells. The project showcases Prolog's strengths in declarative programming, logical inference, and rule-based systems, often used in artificial intelligence courses.

## Features

1. **Creature Vulnerabilities**:
   - Defines various creatures and their vulnerabilities to specific attack types (e.g., fire, ice, physical).
   - Vulnerabilities allow heroes to inflict more damage when using certain types of attacks.

2. **Damage Types**:
   - Models different types of damage (e.g., fire, ice, shadow, radiant) that can be inflicted by various weapons or spells.
   - Associates each attack type with spells or weapons to determine effectiveness.

3. **Hero Arsenal**:
   - Defines a list of available spells or weapons for each hero type, creating diverse strategies and capabilities for each hero.

4. **Battle Simulation**:
   - Calculates damage based on hero and creature statistics.
   - Checks if a creature is vulnerable to a hero's weapon or spell, which influences the outcome of the battle.

5. **Outcome Prediction**:
   - Simulates combat between a hero and a creature to determine the likely winner.
   - Computes damage based on the hero’s attack value, spell damage, and the creature's defense.

## Key Predicates and Their Functions

- **`vulnerable/2`**: Defines the types of damage that each creature is vulnerable to.
- **`damage_type/2`**: Specifies the damage type associated with each spell or weapon.
- **`arsenal/2`**: Lists the spells or weapons available to each hero class.
- **`creature/3`**: Generates random health and defense values for a creature.
- **`hero/2`**: Generates a random attack value for a hero.
- **`spell_damage/2`**: Assigns a random damage value for a spell.
- **`isVulnerable/2`**: Checks if a creature is vulnerable to a specific damage type.
- **`ktoJakiAtak/4`**: Determines which hero should use a specific weapon or spell against a creature.
- **`ktoWygra/4`**: Predicts the winner of a battle between a hero and a creature, based on vulnerabilities and damage calculations.
