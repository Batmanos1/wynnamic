<div align="center">

<h1><a href="https://modrinth.com/modpack/wynnamic">WynNamic</a> - Source, Wiki & Testing Hub</h1>

<p><b>Client-side performance & visual overhaul modpack for Wynncraft.</b></p>

<p>
  <a href="https://modrinth.com/modpack/wynnamic"><img src="https://img.shields.io/badge/Modrinth-Project_Page-2b3137?style=flat-square" alt="Modrinth" /></a>
  <a href="https://modrinth.com/modpack/wynnamic/versions"><img src="https://img.shields.io/badge/Modrinth-Official_Releases-2b3137?style=flat-square" alt="Downloads" /></a>
  <a href="https://www.reddit.com/r/WynNamic/s/TWqVeMdYdn"><img src="https://img.shields.io/badge/Reddit-r%2FWynNamic-2b3137?style=flat-square" alt="Reddit" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-CC_BY--NC--ND_4.0-2b3137?style=flat-square" alt="License" /></a>
</p>

</div>

---

### ⟡ About This Repository

This repository serves as the **config archive, testing ground, and documentation wiki** for **WynNamic**. 

Built and tuned on modest laptop hardware to prove Wynncraft can run smoothly without sacrificing atmosphere, the pack combines custom UI layouts, ready-to-use keybinds, and an offset third-person camera preset.

> **Hardware Note:** Default video settings are tuned for low-end systems. If you are running stronger hardware, feel free to raise render distances or switch between the bundled shader profiles.

---

### ⟡ Quick Start & Community

- **Official Builds:** Download ready-to-import `.mrpack` files from **[Modrinth Releases](https://modrinth.com/modpack/wynnamic/versions)** (or the **Releases** tab on this repository).
- **Bug Reports & Feedback:** Post issues, test feedback, or feature suggestions on **[r/WynNamic](https://www.reddit.com/r/WynNamic/s/TWqVeMdYdn)** or open a **GitHub Issue** here.
- **First Launch Tip:** Press **`Y`** in-game to toggle the custom third-person camera (recommended for full overlay visibility).

---

### ⟡ Pack Wiki — Included Features

#### Visuals & Atmosphere
- **Custom Biome Fog & Mist** — Powered by **Atmospherics**.
- **Extended Render Distance** — Distant terrain caching via **Voxy** and **wynnLODgrabber**.
- **Distant LOD Effects** — Smoke and off-map LOD management handled by **WynnVista**.

#### Audio & Immersion
- **NPC Voice Acting** — Full quest voiceover support via **Voices of Wynn**.
- **Dynamic Environment Audio** — Layered environmental soundscapes with **AmbientSounds**.
- **Acoustic Simulation** — Cave reverb and directional sound occlusion via **Sound Physics Remastered**.

#### Performance & Optimization
- **Network Packet Prioritization** — Reduced latency spikes using **Krypton**.
- **Entity & Sound Culling** — Filters off-screen entities (**Entity Culling**) and excessive overlapping audio (**Sound Culling**).

#### Gameplay Utilities
- **Wynntils** — Custom-tuned minimap, waypoints, streamlined UI, keybind spell casting, hold-to-autoattack, and custom screen overlays *(best viewed in third person)*.
- **Wynnmounts + Wynntoolz** — Mount training path analysis and stat tips.
- **Wynnmod** — Ability tree loadouts and loadout sharing, raid/world location pings for party members, and in-game chat emojis (`/emojis`).
- **Shoulder Surfing + Spatial GUI** — Offset third-person camera for clear aiming alongside spatial inventory rendering.
- **Wynn Bubbles** — Floating overhead chat bubbles for nearby players and player ghosts.

---

### ⟡ Controls Reference

*All keybinds can be customized in Minecraft's Controls menu.*

#### General & Navigation
| Action | Default Key | Notes |
| :--- | :--- | :--- |
| **Inventory** | `Z` | — |
| **Sprint** | `Mouse Side Button` | Rebind recommended if your mouse lacks side buttons |
| **Open Chat** | `/` | — |
| **Party Interface / Editor** | `O` | — |
| **Main Map** | `Z` | — |
| **Guild Territory Map** | `J` | — |
| **Ping Location** | `[` | Shares ping with other Wynnmod users |

#### Camera & Visuals
| Action | Default Key | Notes |
| :--- | :--- | :--- |
| **Toggle 3rd Person View** | `Y` | Switches between 1st person and offset 3rd person |
| **Camera Zoom** | Hold `C` + `Scroll` | Adjust zoom level while holding `C` |
| **Toggle Shaders** | `;` | Quickly toggle shaders on/off for performance |

#### Combat, Mounts & Misc
| Action | Default Key | Notes |
| :--- | :--- | :--- |
| **Cast Spells** | `Q`, `E`, `R`, `T` | See overlay note below if rebinding |
| **Auto-Attack** | Hold `Attack` | Enabled automatically via Wynntils |
| **Mount Auto-Ride** | `Ctrl` | — |
| **Analyze Mount in Feeder** | `Numpad /` | Rebind recommended on compact/TKL keyboards |
| **View Lootrun / Raid Lootpools** | `N` | — |

> **Rebinding Spell Keys:** If you change `Q`, `E`, `R`, or `T`, disable the custom keybind overlay so it doesn't show outdated keys:
> 1. Press **`Esc`** in-game → **Wynntils Menu** → **Overlay Management**
> 2. Open the **Custom** tab and locate **`Spell Keybind Info`**
> 3. Switch **`Enabled`** → **`Disabled`**

---

### ⟡ Modpack Structure & License

```text
LICENSE # CC BY-NC-ND 4.0 terms  
WunNamic 1.x.x-xx
├── overrides/            # Custom FancyMenu layouts, UI assets & tuned mod configs
└── modrinth.index.json   # Modrinth pack manifest & dependency hashes
