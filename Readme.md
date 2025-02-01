# Gothic Tactical

Gothic Tactical is based on the COGITO Godot template, which is made by [Philip Drobar](https://www.philipdrobar.com) with help from [these contributors](https://github.com/Phazorknight/Cogito/graphs/contributors).

## Current Features

### Planned Features (prioritized)
- Game world
  - [1] NPC's
    - [2] Dialog system
    - [3] Shop & Trade UI
    - [4] Dynamic Sims-like AI using recursive decision-making to solve high-level problems
    - [5] Enemy AI (and grouping, squads, formations, and coordination)
  - [9] Starting area
- Items & Economy
  - [7] Medical system
  - [8] More weapons & ammunition types
  - [14] More realistic ballistics simulation
- Player controller & Engine
  - [6] Multiplayer support
    - Multiplayer gamemodes? (Deathmatch, S&D, Assassin, TTT)
  - Leaning mechanic
  - [11] Dynamic Lighting system for stealth
  - [10] Hacking & Computers
  - [12] Mantling
  - [13] Mounting & Cover system (COD:MW-like)

### Basic Cogito Features:
- First person player controller with:
  - Sprinting, jumping, crouching, sliding, stairs handling, ladder handling
  - Fully customizable attributes like Health, Stamina, Visibility (for stealth) - Component-based, so easy to add your own.
  - Lots of exposed properties to tweak to your liking (speeds, headbob, fall damage, bunnyhop, etc.)
  - Easy-to-use dynamic footstep sound system
- Inventory System
  - Flexible resource-based inventories
  - Inventory UI separate from inventory logic
  - Examples for multiple item types (consumables, keys, ammo, weapons, combinable Items)
  - Base class to easily add your custom item types
- Interaction System
  - Component-based interactions makes it easy to turn your own objects interactive quickly and customize existing ones
  - Examples for interactive objects like doors, drawers, carryables, turn-wheels, elevators, readable objects, keypads
- Basic Enemy
  - NavigationAgent based enemy with a simple state machine
  - Simple player detection system that uses detection areas + basic line-of-sight checks
- Full gamepad support!
- Systemic Properties (very WIP)
  - Give objects properties like "FLAMMABLE" or "WET" and they will interact with each other depending on their state and properties.
  - For example FLAMMABLE objects can be ignited by objects that are actively on fire. Can be extinguished by objects that are WET.
  - Straight forward system to add your own properties and behaviours, all handled in one script. Also easy to just ignore.
- Quest System
- Save and Load System as well as scene persistency
