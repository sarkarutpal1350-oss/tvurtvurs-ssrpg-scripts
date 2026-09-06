# tvurtvurs-ssrpg-scripts
A collection of custom automation and combat scripts for SSRPG. These scripts handle equipment swapping, ability activations, cooldown tracking, and utility routines across various locations and combat encounters.

---

## 📜 Table of Contents
- [Overview](#overview)
- [Scripts List](#scripts-list)
  - [Essentials SSRPG](#1-essentials-ssrpg)
  - [Rocky Script](#2-ssrpg-rocky-script)
  - [Caves Script](#3-ssrpg-caves-script)
  - [Deadwood Script](#4-ssrpg-deadwood-script)
  - [Temple Script](#5-ssrpg-temple-script)
  - [Additional Utilities](#6-additional-utilities)
- [How to Use](#how-to-use)

---

## 🎮 Scripts List

### 1. Essentials SSRPG
**Purpose:** Core UI integrations, stunlock automation, and shield management routines.
```stonescript
// Imports & UI Setup
import UI
import UI Boo
import UI Dog
import UI BetterInfo2
import UI FancyUI
import UI BossHealthBar
import UI BetterText

// Main Routine
// using this script you dysangleos stunlock and Unmake acronians times
item 3 equipL left right state shield 
item Boo import Dog
print "hello m script friend"

if foe.hp <= 0 {
    // State management & timer routines
    StateL 25 0 26
    item 18 string 19
}

2. SSRPG Rocky Script
Purpose: Handling elemental fire routines, Quarterstaff/Sword swapping, and Æther summoning.
pot var foe debuffs string hp
var quarterstaff equipL comp freezedys abilities
summon your Æther & R activate CD & item distance skeleton CD hyfre equipL state & here

p1 fire type2 fire Æther 15 element1 6 Æther
func staff_fire insert not rn sword state equipR sword regen here state foe mind &

3. SSRPG Caves Script
Purpose: Stun/debuff rotations, crossbow/hammer switching, heavy foe management, and bardiche skills.
item var fdt var CD CanActive wand sword hp vigor debuff staff equipR comp
func break o & left moon func func heavy foes 120 string arm activate CD CD

bard mask dash fight ShHeal unstable closemain 10
crossbow 15 equipL hammer equipR GetCount 0 ShHeal fdc bardiche CD 7 ice fight equipL

4. SSRPG Deadwood Script
Purpose: Moondial timing, pickpocketing, healing, and void weaver / talisman of æther synergy.
var state item right state string foe var sword hp equipL CD pickup funk CD item & equipL
func moondial R CD arm hp pick_pocket func

bard bardiche CanActive break voiweaver comp item unstable aether equipR func 10 10
equipR func 7 hp heal 0 & talisman_æther 0 dist sword foe 32 compound

5. SSRPG Temple Script
Purpose: Ice elemental control, ice crossbow mechanics, star/moon blade triggers, and heavy stun sequences.
var item fdt GetTime CD CanActive element2 13 ShHeal vigor debuff equipL
star ice 11 activate func 2 item moon BladeAct CanActive heavy CD CD foes hp break CD

talisman_aether CD activate func CD comp crossbow_ice fdf string equip dist stun 10 ice 7 300 6
GetCount activate count 15 & & mind

6. Additional Utilities & Pet UI
Purpose: Pet management, cooldown tracking, and grappling hook routines.
Pets UI UI CDTime import BetterText
foe loc fo foe string p3fre var element1 fdc 17 dist CD func staff comp comp your 0 6 activate activate break func skeleton_arm 2 875 o addon2
foe chill freezedys string ice Æther equipL func 0 grappling GetCount & mask blade humanoid equipL activate L state 115

🛠️ How to Use
 * Copy the script corresponding to the zone or function you need.
 * Open your in-game script editor.
 * Paste the script into your main script file or reference it using import.
 * Adjust item IDs, equip slots, or cooldown variables to match your current gear set.