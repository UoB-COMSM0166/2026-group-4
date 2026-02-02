# Project Outlines

- searching the recent legendary and basic version of the game
- analyze key elements,features and key technique interm of mapping and classes needed in the game
- Game development in ~5 weeks
- Plan expansions for extra time

## Game Ideas

### Idea 1 — Contra: Reloaded (More Detailed Concept Draft)

Inspiration

Contra and classic arcade run-and-gun pacing: fast, punishing, skill-forward

Side-scrolling shooters with memorable set pieces, enemy “patterns,” and high replay value

Modern action polish: tighter input feel, clearer readability, deeper build variety

High Concept

A modern run-and-gun that preserves the pressure and immediacy of arcade shooters while adding build depth, branching upgrades, and replay-driven progression. Sessions are short and intense (10–20 minutes), but mastery can go deep (S-ranks, no-hit runs, speedruns).

Core Gameplay Pillars
1) Side-scrolling Momentum + Mobility Layer

Movement toolkit: sprint, crouch, slide/dodge, climb/ledge-grab, jump (optional double-jump/wall-kick)

Shooting model: either 8-direction aiming (classic) or move+aim dual-stick (modern accessibility toggle)

Emergency action: short-cooldown dash/roll with minimal invulnerability frames to keep the pacing strict

Environmental interactions: breakables, explosive barrels, switches, moving platforms, collapsing terrain to create risk/reward routes

2) Enemy Waves Built as “Compositions,” Not Just Quantity

Enemies are designed by battlefield roles:

Pressure units (shield/armor) force flanks or armor-piercing solutions

Disruptors (nets, slows, smoke) punish autopilot play

Air threats (drones/helicopters) demand vertical aiming and target priority

Rushers/suicides enforce spacing and timing

Wave logic: trigger-based spawns plus dynamic reinforcements if the player stalls

Elite variants with modifiers (regen shield, split shots, death burst) to increase tactical variance

3) Boss Fights as Mechanics Exams

Every boss has 3+ phases: learn → adapt → execute under pressure

Arena changes matter: shifting platforms, hazards, visibility gimmicks—but always readable and fair

Boss depth via: breakable parts, interrupt windows, exposed weak points, pattern manipulation through player positioning

Systems That Add Depth (Without Losing Arcade Clarity)
Weapon Ecosystem (Roles + Tradeoffs)

Weapons aren’t just cosmetic—each has a job and a cost:

Burst rifle (reliable mid-range), shotgun (close clear), beam/rail (pierce armor/lines), homing (anti-air), explosives (area denial)

Choose one: ammo economy (encourages swapping/scavenging) or heat management (forces rhythm and burst discipline)

Modular Upgrades & Build Paths

In-run mods create build identity (pierce+crit, AoE+burn, homing+chain lightning)

Weapons branch into 2–3 upgrade paths (e.g., shotgun: spread control vs armor shred vs knockback control)

Power is balanced by drawbacks: recoil, overheat rate, movement penalty, reduced accuracy—forcing meaningful choices

Characters & Abilities (Especially for Co-op)

2–4 characters with distinct passives and skills:

Assault (armor break/dash), Engineer (turret/explosives), Scout (weak-point mark/crit), Medic (shield/fast revive)
Co-op becomes coordination, not just “more bullets.”

Nice-to-Haves (Expanded)
Co-op (Local/Online)

2-player baseline (scalable to 4)

Downed state + revive, shared vs personal loot toggles

Synergy actions (mark+volley, crowd-control combo)

Difficulty scales by behavior complexity, not only HP

Level Structure & Replayability

8–12 main missions: push → set piece (holdout/escape/vehicle) → mini-boss → boss

Branching high-risk routes with better rewards (challenge rooms)

Scoring loop: time, damage taken, kill ratio, secrets, S-rank grading

Presentation & Theme

Retro pixel/16-bit vibe + modern VFX (particles, screen shake, lighting)

Music: synth + rock percussion, with dynamic boss layering

Light narrative via logs and environmental storytelling (sci-fi military + biotech/mech horror blend)

Difficulty & Fairness (Non-negotiables)

Attacks must be readable: telegraphs, audio cues, consistent projectile logic

Multiple difficulty tiers: approachable baseline, high ceiling for mastery

Checkpoints and resource drops tuned so failure feels earned—not random or unavoidable
### Idea 2 - Gold Miner Prospector

Inspiration:

- Building upon the timeless mechanics of the classic "Gold Miner," this enhanced version transitions from a dusty mine to a vibrant underwater world. Players take on the role of a deep-sea diver or a high-tech fishing vessel, utilizing a motorized hook to retrieve rare marine life and sunken treasures.
- Casual arcade game

Fundamentals:

- Hook-and-Reel Mechanic: A precision-based system where a claw/hook oscillates at a fixed pivot point, waiting for the player to launch it toward a target.
- Time-Based Progression: Players must meet a specific monetary quota within a set time limit to advance to the next level.
- Economic System: A post-level shop allows players to purchase upgrades and consumables using the currency earned during the mission.

New Items & Mechanics:

Rare Fish Bait:

- A consumable item that triggers the appearance of the "Diamond Swordfish" or "Golden Koi" in the subsequent level. These rare creatures move rapidly across the screen and provide massive rewards if caught.

Laser Sight Upgrade:

- A tactical enhancement that lasts for three levels, providing a real-time trajectory beam to visualize the exact grab point, significantly increasing accuracy.

Reinforced Fishing Line:

- A single-use power-up that allows the hook to latch onto and retrieve "Colossal Ancient Statues"—high-value, high-weight objects that ordinary lines cannot pull.

Reinforced Claw:

- A single-use power-up for the next level. It enables the claw to successfully latch onto and pull "Massive Ore"—a special, high-value, high-weight obstacle.

Massive Obstacle Mechanic:

- Large underwater volcanic rocks act as barriers; standard hooks will bounce off them, but the Reinforced Line allows players to harvest the treasures hidden directly beneath them.

Environmental Modifiers (Level Dynamics)

- Ocean Currents: Visualized through background bubble flows indicating direction (Left/Right).

- Flow Boost: The hook moves 20% faster when launched in the direction of the current and 20% slower against it.

- Strategic Goal: Forces players to time their launches with the current to maximize efficiency.

Dynamic Hazards

- The Great White Patrol: A shark swims horizontally across the mid-section of the level.

- Interception Mechanic: If the shark collides with a fish being reeled in, the fish is consumed, and the player retrieves an empty hook.

- Fair Play: The player's hook and line are unaffected by the shark if empty, focusing the challenge purely on timing and protection of the catch.

Nice to haves:
Two-Player Mode:

- Dual-Hook Setup: Two players control hooks from the top-left and top-right corners of the screen.

- Co-op Pull: Players can hook the same massive object together to double the reeling speed.

### Idea 3 - Homework Slasher

Inspiration:

- A twist on the classic "Fruit Ninja" game, replacing the blade with a pen and fruits with homework assignments from various subjects. Players slash through floating homework papers to score points.
- Casual arcade game

Fundamentals:

- Mouse tracking and collision detection
- Time-based levels
- Reward items and scores

Core Mechanics:

Standard Assignment:

- When the player's pen touches a standard homework sheet, a green checkmark (✓) appears on it. The paper then shatters into pieces (similar to sliced fruit in the original game) after a 0.5-second visual delay, and points are awarded.

Combo Bonus:

- A consecutive slash of three or more assignments triggers a combo, granting bonus points.

"Hard Subject" (Bomb Equivalent):

- One particularly difficult subject (e.g., "Advanced Calculus") replaces the role of bombs. If the player's pen touches this paper, a red cross (✗) appears on it. The paper does not shatter. This action results in a score penalty and breaks any ongoing combo.

Power-up:

- Golden Pen: Upon contact with a special floating "Golden Pen" item, the player enters a powered-up state for a limited time (e.g., 5 seconds). During this time, the pen can slice through any type of assignment (including the "Hard Subject") without penalty, with all assignments displaying the green checkmark and shattering for points.

Scoring & Progression:

- The total score determines the number of stars earned at the end of a level or session (e.g., 1-3 stars). Higher scores unlock more stars.

## Challenges

Different difficulty levels, high score list, two-player mode, physics engine, map generation, collision detection
