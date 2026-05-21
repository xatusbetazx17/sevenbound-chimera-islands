# Sevenbound: Chimera Islands — Playable Prototype + Game Design v2

A survival monster-taming RPG concept built around genetically modified immortal monsters, a seven-slot hand materialization device, abandoned islands, lost scientist diaries, wall inscriptions with Bible verse references, final survivor notes, disease-cure research, tournaments, and procedurally unique creatures.

This prototype uses the three uploaded monster images as placeholder art, adds a fourth mixed form called **Nexarion Equinox**, and now integrates the generated key-art and mission-complete concept images directly into the game UI for the title, controls preview, lab, and mission-success screens.

## How to play the prototype

Open `index.html` in a modern browser.

Mission goal:
1. Survive the abandoned island.
2. Tame 7 unique specimens.
3. Recover optional lost records from ruins: scientist diaries, wall verse inscriptions, and final survivor notes.
4. Find all 4 suit modules: Heatwave Core, Nival-Tide Seal, Void Dampener, Cosmic Halo Lens.
5. Weaken and tame **Nexarion Equinox**.
6. Escape through the extraction circle.
7. Return to the lab for decontamination, research rewards, tournaments, and future islands.

Keyboard controls:
- Move: WASD / Arrow Keys
- Attack / command monster: J or Space
- Dodge: K
- Scan, tame, collect: E or F
- Materialize / recall selected monster: R
- Select monster slot: 1-7, Q / L
- Use supply: H
- Map: M
- Lore archive: C or Tab
- Pause: P or Esc

Gamepad controls:
- Move: Left Stick
- Attack / confirm: A / RT on many controllers
- Dodge / cancel: B
- Scan, tame, collect: X
- Materialize / recall: Y
- Slot previous / next: LB / RB
- Map: Back / View
- Lore archive: D-pad Up
- Pause: Start / Menu

## Full game pitch

**Title:** Sevenbound: Chimera Islands  
**Genre:** Creature-taming action RPG + survival + tournament battler  
**Core fantasy:** You are a field tamer-researcher sent to abandoned islands where genetically modified monsters evolved without human control. You tame monsters, materialize them with a wrist device, survive extreme environments, investigate cures for diseases, and prove your team in tournaments.

## Main systems

### Seven-slot materialization device

The player wears a wrist device called the **Sevenbound Brace**.

It can:
- Scan wild monsters.
- Stabilize unstable DNA patterns.
- Store up to 7 active partner monsters.
- Materialize one selected monster when needed.
- Recall monsters before they are critically injured.
- Send extra tamed monsters to the lab for research.

The seven-slot limit creates strategy: players must choose their field team, while unwanted or extra monsters still matter because they help the lab design cures, habitats, and countermeasures.

### Taming loop

To tame a monster:
1. Scan it.
2. Survive its behavior pattern.
3. Lower its HP without destroying its stability.
4. Keep its stress from going too high.
5. Use the Sevenbound Brace at close range.
6. If the brace overheats, wait or retreat.

Tamed monsters can be kept in the 7 active slots or sent to the lab.

### Survival loop

On abandoned islands, no one is alive. The player must manage:
- Health
- Stamina
- Hunger
- Hydration
- Temperature
- Infection / bio-risk
- Suit integrity
- Supplies
- Device heat
- Monster stress

The player can die. Death reloads the last **Recovery Beacon** save, preserving progress only up to that save.


### Lost records and island story

Abandoned islands now contain interactive lore objects near ruins:
- **Scientist diaries** explain the genetic experiments, the Sevenbound Brace, Nexarion stress behavior, cure research, and habitat ethics.
- **Wall verse inscriptions** show Bible verse references left by survivors, with original in-game notes written beside the references. These are meant to create a survival-horror mystery tone without locking the game to one Bible translation.
- **Final survivor notes** reveal the last moments of civilians, lab assistants, guards, and island workers before the monsters overran the facility. The notes can point toward supplies, safe routes, boss clues, or future locked-door puzzles.

In the prototype, blue diary icons, gold wall-verse plates, and red survivor-note markers can be read with **E/F**. Recovered records grant small research rewards and are stored in the **Lost Records Archive**, opened with **C/Tab** or from the lab/pause menu.

### Lab loop

After extraction, the lab disinfects the player and all gear. The lab also:
- Heals monsters.
- Studies reserve monsters.
- Builds safer habitats.
- Creates disease-cure research from monster DNA.
- Unlocks better suits and devices.
- Opens tournaments.
- Prepares the next abandoned island expedition.

### Tournaments

Tournaments are controlled battles outside the survival islands. They test:
- 1v1 monster control
- 3v3 tactical teams
- Full 7v7 elite battles
- Special hazard arenas
- Boss-rematch simulations

Tournaments reward reputation, money, research points, rare supplies, and device upgrades.

## The preset monster in the images

The uploaded monster is designed as one preset monster with multiple states.

### Name

**Nexarion Equinox**  
Also known as: **The Four-Core Chimera**

### State 1: Heatwave Rupture Form

Visual identity: black armored body, red molten cracks, explosive lava aura.

Powers:
- Heatwave breath
- Magma claws
- Thermal shockwaves
- Temperature overload
- Suit-melting aura

Gameplay condition:
- Appears in volcanic zones or when Nexarion is enraged.
- Raises player temperature and damages suit integrity.

### State 2: Void Armor Form

Visual identity: black and purple armor, crystal horns, void particles.

Powers:
- Gravity pull
- Void blink
- Energy drain
- Brace overheating
- Stress amplification

Gameplay condition:
- Appears in shadow ruins, caves, or when the device is unstable.
- Pulls the player and increases Sevenbound Brace heat.

### State 3: Cosmic Halo Form

Visual identity: blue celestial body, halo rings, star wings, gold constellation energy.

Powers:
- Cosmic beams
- Healing light
- Starlight barrier
- Radiation bursts
- Long-range tracking attacks

Gameplay condition:
- Appears during clear sky, meteor storms, or when Nexarion is calm but focused.
- Creates bio-risk and ranged pressure.

### State 4: Equinox Fusion Form

Visual identity: all three images fused together: heat, nival-tide, void, and cosmic power in one unstable form.

Power mix:
- Heatwave temperature spikes
- Nival-tide cooling and movement slow
- Void gravity pull and energy drain
- Cosmic radiation and long-range beams
- DNA fusion shockwave when stress is too high

Taming condition:
- Requires the completed 4-core suit.
- Requires Heatwave, Nival-Tide, Void, and Cosmic modules.
- Nexarion must be below 20% HP.
- Suit integrity must be high enough.
- Brace heat must be low enough.
- The player must survive the Equinox Bond attempt.

After taming:
- Nexarion becomes a partner or is sent to the lab if all 7 slots are full.
- The lab builds an accommodation habitat, so the player does not need to wear the full special suit around it in safe zones.
- At maximum mixed power, the suit or a lab containment field is still required.

## Monster generation system

Every wild monster is generated with a unique DNA seed.

Generated properties:
- Name
- Body type
- Element genes
- Temperament
- Aggression level
- Cure potential
- Biome preference
- Stress response
- Evolution path
- Mutation rate
- Taming difficulty

No two monsters should be exactly the same.

## Eternal evolution system

Monsters are practically immortal because their DNA was modified.

They have:
- No level cap
- No final evolution limit
- Environment-based evolution
- Stress-based mutation
- Bond-based stabilization
- Infinite rank growth

Balance rule: power can grow forever, but instability grows too. If the player ignores stress, hunger, habitat, or bond, a monster can become dangerous and temporarily fuse forms in combat.

## Disease-cure research

Monsters are not just weapons. Their modified DNA can help cure diseases.

Research examples:
- Heat monsters: fever regulation and thermal antibodies
- Nival-tide monsters: tissue preservation and inflammation control
- Void monsters: energy absorption and radiation countermeasures
- Cosmic monsters: cell repair, light-based diagnostics, rare mutation mapping
- Toxic monsters: antidotes and toxin resistance
- Alloy monsters: bone repair and protective tissue studies

Ethic rule: tamed monsters are partners. Research is non-lethal and habitat-based.

## Recommended full production structure

Best engine choices:
- Godot 4 for an indie 2D/2.5D version
- Unity for a larger 3D action RPG version
- Unreal for a high-budget 3D version

Suggested first production milestone:
1. One island biome
2. Seven-slot brace system
3. Ten generated monster families
4. One boss: Nexarion Equinox
5. Basic survival stats
6. Lab decontamination
7. One tournament mode
8. Keyboard + gamepad + Steam Input action mapping
9. Lost Records Archive with readable diaries, wall notes, and survivor notes
10. Save / load system
11. Options and accessibility menu

## Steam-ready input actions

Use actions instead of hardcoded buttons:
- Move
- Camera
- Confirm
- Cancel
- AttackCommand
- Dodge
- TameScan
- Interact
- MaterializeRecall
- SlotPrevious
- SlotNext
- Slot1 through Slot7
- UseSupply
- Map
- LoreArchive
- Pause
- MenuNavigate

This lets the final game support keyboard, mouse, gamepad, Steam Deck, and Steam Input remapping.


## v4 prototype additions
- Upgraded pseudo-3D environment rendering and improved HUD panels
- Golden ruined wall style and darker island atmosphere
- Player weapon: **VX-46 Stabilizer Carbine** for weakening monsters into the 46% HP taming zone
- Real-time partner auto-battle: materialized monsters attack automatically
- Visible monster skill list for the active slot
- Indefinite skill growth: monsters can keep learning new adaptive skills over time


## v5 bracelet recovery fix
- Tamed monsters now regenerate HP automatically while stored inside the Sevenbound Bracelet.
- If a materialized partner is defeated, it enters a short recovery timer, reforms at partial HP, and continues healing until full.
- Damaged monsters also heal when recalled/dematerialized back into the bracelet.
- Team slots now show clear status text: Recovering, Brace healing, or Ready.
- Existing v4 saves are supported; older monsters receive the new recovery and skill defaults when loaded.


## v6 prototype additions
- Genova Lab now shows NPC scientists when you arrive after decontamination.
- Added an arrival briefing/dialogue sequence advanced with Enter/A or Down.
- Added a Research Console with a scrollable scientist message feed.
- Console shows reserve specimens sent to the lab: type, level, form, DNA, bond, recovery, and skill data.
- Research breakthroughs unlock as you send more monsters and more monster types to the lab.
- People helped/saved estimate grows from reserve monsters, type diversity, total captures, research points, and Nexarion data.
- Up/Down scrolls the console, Enter/A moves down, Left/Right jumps, Esc/B returns to lab.


## v7 apex taming fix
- Nexarion / the island apex monster now follows the same clear taming rule: weaken it to **46% HP or lower** and press **E/F**.
- The hidden **20% HP** requirement was removed so the boss is no longer confusing to tame.
- Apex taming range was increased because the boss is huge; standing near its body now counts, not only standing close to its center point.
- Suit modules now make the Apex Bond safer and can guarantee the tame, but missing modules no longer silently block the tame attempt.
- Failed Apex Bond attempts no longer heal Nexarion back up; the HP stays low so the player can try again after the bracelet cools.
- Nexarion now shows a clear **APEX TAME READY** prompt when it can be tamed.


## v8 additions
- Bracelet upgrade economy: coins and relics from captures, crates, modules, and abandoned homes.
- Bracelet can evolve indefinitely with stronger attack profiles.
- Tap J/Space for normal stabilizer shots; hold and release J/Space for charged Apex blaster shots.
- Extraction rule restored: all 4 suit cores + Nexarion captured + 7 total monsters.
- Procedural island biomes and weather.
- Generated broken homes with doors, windows, cracks, maps, textures, and loot.
