# Lesson 01 — How a mod is built

A mod is a small program attached to a game through a loader.

## Core parts
- Entry point: starts the mod
- Patches: hook game methods
- Logic: decides what the mod does
- State: stores temporary values
- UI: displays information if needed

## Typical flow
1. Loader starts the mod
2. Core initializes
3. Patches are applied
4. Game methods trigger the mod
5. Mod logic runs
6. UI updates if needed

## Key idea
A mod does not replace the game.
It connects to the game, watches events, and changes behavior.
