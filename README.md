# Sevenbound: Chimera Islands

**Sevenbound: Chimera Islands** is a playable browser prototype for a survival monster-taming RPG concept by **Marcelo Collado**.

You are sent to abandoned islands where genetically modified monsters evolved without human control. Survive the island, collect suit cores, weaken wild monsters, tame them with the Sevenbound Bracelet, send extra specimens to the lab for disease-cure research, and escape after securing your seven-monster mission team.

## Play the prototype

Open `index.html` in a modern browser.

For the best local experience, you can also run a small local server from the repository folder:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Current prototype version

This repository contains the **v8 Bracelet + World Upgrade** prototype.

### Major gameplay systems

- Seven-slot monster bracelet system
- Wild monster taming after weakening targets to **46% HP or lower**
- Nexarion Equinox apex monster mission
- Four suit cores: Heatwave, Nival-Tide, Void, and Cosmic
- Bracelet upgrades with coins and relics
- Normal bracelet shot and charged bracelet blaster
- Tamed monsters recover automatically inside the bracelet
- Real-time automatic monster skills and indefinite skill learning
- Lab NPCs and research console messages
- Reserve monsters sent to lab for non-lethal research
- People-helped / disease-cure progress tracking
- Lost scientist diaries, survivor notes, and wall inscriptions
- Abandoned homes, broken interiors, loot, maps, doors, windows, and ruins
- Random island biomes, weather, and procedural monster variation
- Extraction ship shield that opens only after mission success
- Keyboard and gamepad support

## Mission objective

1. Survive the abandoned island.
2. Collect the four suit cores.
3. Capture **Nexarion Equinox**.
4. Capture enough monsters to make a total of **7 mission specimens**.
5. Reach the extraction point and return to the Genova Lab.

## Controls

### Keyboard

| Action | Input |
|---|---|
| Move | WASD / Arrow Keys |
| Normal bracelet shot | Tap J / Space |
| Charged bracelet blaster | Hold J / Space, then release |
| Dodge | K |
| Tame / collect / interact | E or F |
| Materialize / recall selected monster | R |
| Select monster slot | 1-7, Q / L |
| Use supply | H |
| Map | M |
| Lore archive | C or Tab |
| Pause | P or Esc |

### Gamepad / Steam Deck

| Action | Input |
|---|---|
| Move | Left Stick |
| Attack / confirm | A or right trigger on many controllers |
| Dodge / cancel | B |
| Tame / collect / interact | X |
| Materialize / recall | Y |
| Slot previous / next | LB / RB |
| Map | Back / View |
| Lore archive | D-pad Up |
| Pause | Start / Menu |

## Repository structure

```text
.
├── index.html                 # Playable browser prototype
├── assets/                    # Monster sprites and integrated concept images
├── docs/                      # Game design, roadmap, and GitHub upload notes
├── .github/workflows/pages.yml# Optional GitHub Pages deployment workflow
├── LICENSE.md                 # Current rights/license notice
└── README.md                  # Repository overview
```

## GitHub Pages

This repo includes a GitHub Actions workflow for GitHub Pages.

After pushing the repo to GitHub:

1. Go to **Settings → Pages**.
2. Choose **GitHub Actions** as the source.
3. Push to the `main` branch.
4. GitHub will deploy the static prototype automatically.

## Project status

This is a playable prototype, not a finished commercial game. The current build is made as a browser-based proof of concept so the systems can be tested quickly before moving to a full engine like Godot, Unity, or Unreal.

## Creator

Concept and game direction: **xatusbetazx17**

