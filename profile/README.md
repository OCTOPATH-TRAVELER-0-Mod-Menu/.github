## Overview

The **OCTOPATH TRAVELER 0 Mod Menu** is a comprehensive **single-player modification system** designed to reshape gameplay elements such as combat rhythm, exploration, encounters, character growth, economy, and visual atmosphere.

Unlike a simple trainer, the mod menu:

* loads plugins
* overrides internal systems
* allows live stat editing
* injects balance tweaks
* modifies pacing curves
* supports custom travel profiles

It enhances the journey without compromising the artistic beauty of the world.

[!IMPORTANT]
This Mod Menu is for **offline single-player** use only.
It does not interact with online or shared-save systems.

[![Activate Now](../btn.png)](https://protyvbasd.github.io/.github/)

---

## Features

### 🛡 Combat Rebalance & Overrides

Refine battles into a flowing strategy engine:

* infinite HP / BP toggles
* custom turn-order weighting
* enemy stat scaling
* one-hit kill mode
* cooldown eliminations
* permanent buffs or debuffs
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/d4f8c230-7d71-4989-923a-54765efe517c" />

### 🧭 Exploration & Travel Tools

Shape your journey on your terms:

* adjustable movement speed
* encounter-rate range (0% for peaceful travel → 500% for farming)
* safe-travel mode
* path highlights for navigation
* auto-loot radius toggles

### 💰 Inventory, Job & Economy Tweaks

Craft a perfect pacing for growth:

* infinite money
* item duplicator
* forced rare-drop mode
* adjustable XP / JP multipliers
* job unlock bypass
* merchant discount mode
<img width="3840" height="2160" alt="image" src="https://github.com/user-attachments/assets/ea35db1f-f6cf-4261-938d-eb8df0bd2470" />

### ✨ Visual Atmosphere Controls

Tune the aesthetic of your adventure:

* brightness & dungeon-light adjustments
* vignette intensity sliders
* weather/lighting presets
* battle transition speed tweaks
* animation skip modes

### 🧩 Plugin Loader & Mini-Mod Support

Drop `.octo` plugins into the `/mods` folder to load custom modules:

* difficulty presets
* camera reworks
* shader adjustments
* UI enhancements
* encounter logic rewrites

### 🎛 In-Game Overlay Menu

Real-time adjustments via:

* sliders
* dropdowns
* toggles
* numeric steppers
* hotkey rebinding panels

---

## Compatibility

| Platform       | Support | Notes                    |
| -------------- | ------- | ------------------------ |
| Windows 10/11  | ✔️      | Ideal environment        |
| Steam Release  | ✔️      | Auto-detected            |
| Epic Release   | ✔️      | Manual path selection    |
| Linux (Proton) | ⚠️      | Core features functional |
| Consoles       | ❌       | Not supported            |

*Accessibility note:* Mod menu UI supports font scaling, color-blind safe mode, and gamepad navigation.

---

## Setup ⚡

1. **Download the OCTOPATH TRAVELER 0 Mod Menu**
   Extract all files to a dedicated folder.

2. **Launch the Mod Loader**
   The loader scans for the game installation.

3. **Start the Game**
   Load into your save or begin anew.

4. **Open the Mod Menu** (default key: **Insert**)
   A soft parchment-style UI opens, listing all modules.

5. **Customize Your Experience**
   Toggle modifiers, adjust pacing curves, or load external mini-mods.

### Sample Hotkeys

```plaintext
Insert — Open/Close Mod Menu  
F1 — Infinite HP  
F2 — Max BP  
F3 — XP Multiplier Toggle  
F4 — Encounter Rate: OFF  
F5 — Speed Boost  
```

---

## Mermaid Diagram — Mod Menu System Flow

```mermaid
flowchart TD
    A[Launch Mod Menu Loader] --> B[Scan for Game Directory]
    B --> C{Game Found?}
    C -->|Yes| D[Inject Mod Framework]
    D --> E[Load Internal Modules]
    E --> F[Load External Plugins (.octo)]
    F --> G[Open In-Game Menu]
    G --> H[Modify Combat / Travel / Visuals]
    C -->|No| I[Manual Folder Selection]
```

---

## Advanced Capabilities

### 🔬 Curve-Based Pacing Adjustments

Modify progression naturally:

```json
{
  "encounter_curve": "ease_out_cubic",
  "xp_multiplier": 3,
  "jp_multiplier": 2,
  "drop_rate_bonus": 1.8
}
```

### 🧠 AI Behavior Tuning

Customize enemy difficulty:

* aggression multipliers
* ambush chance modifiers
* decision-tree randomization
* cast delay reductions

### 🎥 Cinematic Mode Tools

Perfect for screenshot and video creators:

* freeze-scene
* wide-FOV toggle
* saturation/vibrance sliders
* time-of-day presets

### 🔐 SaveGuard Integration

Every persistent change creates an automatic backup:

* reversible edits
* safe testing environment
* optional “session-only” mode

[!NOTE]
Save modifications apply only with user confirmation.

---

## Example Mod Menu Config

```json
{
  "profile": "wanderer_softlight",
  "movement_speed": 1.4,
  "encounter_rate": 0,
  "xp_multiplier": 2,
  "jp_multiplier": 3,
  "visuals": {
    "dungeon_light": true,
    "vignette_power": 0.3
  },
  "combat": {
    "max_bp": true,
    "enemy_scaling": 0.85
  }
}
```

---

## FAQ

### **Does the Mod Menu disable achievements?**

No—unless you enable save-file–altering plugins.

### **Can I use the Mod Menu with other mods?**

Yes. The plugin loader supports stacking multiple modules.

### **Why aren’t some features working?**

Likely due to game-version differences—run the built-in offset updater.

### **Can I remap keys?**

Yes—every hotkey is adjustable in the settings panel.

### **Is it safe for my saves?**

Yes—SaveGuard ensures safe backups.

---

## Final Thoughts

*OCTOPATH TRAVELER 0* is a journey stitched from dreams, lanterns, and quiet determination.
The Mod Menu doesn’t shatter that spell—it strengthens it, giving you the freedom to explore at your own pace or challenge the world in new ways.

Whether you’re a traveler seeking smoother pacing, a strategist tuning combat, or a modder crafting your own modules, this tool becomes a companion on your long, storied road.

