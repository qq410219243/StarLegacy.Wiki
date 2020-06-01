# Blueprints

Blueprints are files that store the data of ships, reproduced using ship factories.

## Creating a blueprint

> **Saving blueprints of ships you didn't design (without permission) is illegal!!**

You can make a blueprint from a ship by piloting it and using the command.

1. Pilot the ship
2. Run the command: `/blueprint save <name>` (replace `<name>` with the name of the blueprint)

## Ship Factory

A ship factory is a machine that automatically builds a ship in front of you.

![Image](https://i.imgur.com/igESO3u.png)

### Multiblock

Materials: 2 Iron Blocks, 1 Furnace, 1 Sign, 1 Chest

### Setting Up the Factory

A ship factory takes materials from the multiblock's chest and prints the ship, taking blocks from the chest and placing them down. For the factory to begin taking items from the chest, place a focusing lens (prismarine crystal) in the bottom AND top slot of the furnace.

### Adding a Blueprint to a Ship Factory

First, make sure you have the name of the blueprint. If you forgot it, check `/blueprint list`.

For the ship factory sign, put `[shipfactory]` on line 1 and `<name>` on line 2.
(replace `<name>` with the name of your blueprint)

> You'll need enough free space to print.
> Factories print above, to the right, and in front of the furnace.
