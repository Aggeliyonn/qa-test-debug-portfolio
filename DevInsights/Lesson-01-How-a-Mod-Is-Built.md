# Lesson 01 — How a Mod Is Built

A mod is a small program attached to a game through a loader.

---

## Concept

A mod connects to a game and interacts with its systems without replacing it.

It observes what the game is doing and can modify behavior by injecting logic at specific moments.

Mods are commonly used to add features, fix behavior, or enhance gameplay.

---

## Core Parts

- Entry point: starts the mod  
- Patches: hook into game methods  
- Logic: defines what the mod does  
- State: stores temporary values  
- UI: displays information if needed 

---

## Example

    // Entry point of the mod

    public override void OnInitializeMelon()
    {
        MelonLogger.Msg("Mod Loaded");
        HarmonyInstance.PatchAll();
    }


---

## What Happens Here

1. The mod is loaded by the loader  
2. The entry point method is executed  
3. A message confirms the mod is active  
4. Harmony applies all patches  
5. The mod is now connected to the game 

---

## Why It Is Useful

- Allows modifying game behavior without changing original files  
- Enables adding features or fixing issues  
- Used as the foundation for all mods  
- Required to understand before creating any mod logic 

---

## Key Idea

> A mod connects to the game, observes events, and changes behavior without replacing the game.

---

## What I Learned

- I understood how a mod is structured  
- I learned that a mod needs an entry point and patches  
- I now see how a mod connects to the game instead of replacing it 

---

## What I Still Need to Practice

- I need to practice creating a full mod structure  
- I want to better understand how patches are triggered  
- I should test a simple mod from start to finish  

---

## Link to Real Project Use

- PhoneOnSkate → explain usage  
- ProfitCalculator → explain usage  
