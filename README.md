# XLAND Alien Invasion — Neon Edition

This is an unofficial community modification of the original Alien Invasion project. Original gameplay, assets, credits, and license files are retained; the XLAND layer is additive.

## Added in the XLAND edition

- Animated twinkling star particles layered over the original scrolling stage backgrounds.
- Neon ship halo, corner HUD marks, and a redesigned XLAND title treatment.
- Particle bursts on boss hits, boss defeat, and power-up collection.
- Score-triggered neon boss encounters with a health bar; defeating a boss awards 500 points.
- Collectible power-ups: multi-shot, temporary shield, and score bonus.
- Multi-shot temporarily fires up to three projectiles while respecting the existing projectile cap.
- Original movement, alien types, cargo, hearts, shield items, stage backgrounds, credits, and original assets remain in place.

## Controls

- WASD or arrow keys: move
- Mouse: aim and fire
- Q: quit

## Important notes

- This modification has not been play-tested on every operating system. Install the dependencies from `requirements.txt` and launch with `python alien_invasion.py`.
- The upstream project and bundled assets retain their original attribution/license notices. Review `LICENSE` and asset-specific license files before redistribution. Clearly identify your changes as an unofficial derivative and do not imply endorsement by the original authors.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

# XLAND Alien Invasion — Neon Edition

An unofficial XLAND enhancement pack for the open-source **Alien Invasion** Python/Pygame game. The goal is to preserve the original project while layering in neon visuals and new arcade mechanics.

## Features

- Animated twinkling stars, neon ship aura, and corner HUD accents.
- XLAND neon title treatment and control hint on the main screen.
- Particle bursts and neon boss encounters with a health bar.
- Collectible multi-shot, shield, and score power-ups.
- Original game systems, backgrounds, characters, sounds, and credits are retained.

## Run

```bash
python -m pip install -r requirements.txt
python alien_invasion.py
```

Controls: **WASD / arrow keys** to move, **mouse** to aim and fire, **Q** to quit.

## Credits and licensing

This is an unofficial community modification. The original `LICENSE`, upstream credits, and asset attribution/license files are retained. Please read them before redistributing. XLAND changes are not affiliated with or endorsed by the upstream authors.

## XLAND Expansion systems (additive)

The XLAND edition adds an optional expansion layer while retaining the original game systems and assets:

- **Ship classes:** `C` cycles Phantom (fast), Titan (extra hearts), and Spectre (extra damage) while in menus.
- **Multi-phase boss:** the Void Leviathan changes attack speed at 50% and 20% health; defeat it for credits.
- **Permanent upgrades:** open `U`, then press `1` for laser damage, `2` for armor, or `3` for special weapon cooldown. Credits and levels are saved locally.
- **Dynamic hazards:** asteroids and black holes appear during gameplay; the selected secret mission increases black-hole encounters.
- **Galaxy missions:** open `G`, choose with left/right, confirm with Enter.
- **Achievements and profile:** open `P` to see the best score, kills, bosses and earned achievement flags.
- **Tactical radar:** `R` toggles the radar.
- **XLAND AI Core / guide:** `H` opens the tactical guide; in-game hints appear briefly.
- **Special Nova:** press `V` during a run to damage the boss and clear nearby enemies; it has a cooldown.
- **Persistent save:** `xland_profile.json` is created beside the game entry point after saving progress. Keep this file if you want to retain your profile.

Controls added: `C`, `G`, `U`, `P`, `R`, `H`, `V`, `1`-`3`, `Left/Right`, `Enter`, and `Esc` as described above. Original movement, firing, credits, assets, and game systems remain in place.

The expansion code has been syntax-checked with Python's `compileall`. A full graphical runtime test still needs to be run on a machine with the dependencies installed.


-------------------------------------------------------------------------------------------------------------------------------------------------------------------

# We Can Make This Game Better!

Welcome to the Alien Invasion project. This is an open-source effort where serious developers, designers, and gamers come together to create something extraordinary. We’re focused on pushing the limits of what this game can be, and we need your expertise to make that happen.

The foundation is set, but now it’s time to build something even better. If you’re ready to contribute, collaborate, and help take this project to the next level, we’re excited to have you on board.

<div align="center" style="line-height: 1;">
  <a href="https://github.com/MatinAfzal/Alien-invasion/releases" target="_blank" style="margin: 2px;">
    <img alt="Homepage" src="https://img.shields.io/badge/Github-Latest%20release-7289da?logo=futurelearn&logoColor=white&color=7289da" style="display: inline-block; vertical-align: middle;"/>
  </a>
  <a href="https://discord.com/invite/jBhmM2j2GN" target="_blank" style="margin: 2px;">
    <img alt="Chat" src="https://img.shields.io/badge/Discord-MatinAfzal-7289da?logo=Discord&logoColor=white&color=7289da" style="display: inline-block; vertical-align: middle;"/>
  </a>
  <a href="https://github.com/MatinAfzal/Alien-invasion/discussions/43" target="_blank" style="margin: 2px;">
    <img alt="Chat" src="https://img.shields.io/badge/Discussions-TODO%20List-7289da?logo=todoist&logoColor=white&color=green" style="display: inline-block; vertical-align: middle;"/>
  </a>
</div> 

---

<table align="center">
  <tr>
    <th>Version</th>
    <th>Date</th>
    <th>Release</th>
  </tr>
    <tr>
    <td>V1.3.0</td>
    <td>May 3, 2025</td>
    <td>
      <a href="https://github.com/MatinAfzal/Alien-invasion/releases/tag/V1.3.0" target="_blank">
        <img src="https://img.shields.io/badge/Release-V1.3.0-7289da?logo=alienware&logoColor=green&color=violet" alt="Release Badge">
      </a>
    </td>
  </tr>
  <tr>
    <td>V1.2.0</td>
    <td>Feb 3, 2025</td>
    <td>
      <a href="https://github.com/MatinAfzal/Alien-invasion/releases/tag/V1.2.0" target="_blank">
        <img src="https://img.shields.io/badge/Release-V1.2.0-7289da?logo=alienware&logoColor=green&color=violet" alt="Release Badge">
      </a>
    </td>
  </tr>
  <tr>
    <td>V1.1.0</td>
    <td>Jan 8, 2025</td>
    <td>
      <a href="https://github.com/MatinAfzal/Alien-invasion/releases/tag/V1.1.0" target="_blank">
        <img src="https://img.shields.io/badge/Release-V1.1.0-7289da?logo=alienware&logoColor=green&color=violet" alt="Release Badge">
      </a>
    </td>
  </tr>
  <tr>
    <td>V1.0.0</td>
    <td>Nov 16, 2024</td>
    <td>
      <a href="https://github.com/MatinAfzal/Alien-invasion/releases/tag/V1.0.0" target="_blank">
        <img src="https://img.shields.io/badge/Release-V1.0.0-7289da?logo=alienware&logoColor=green&color=violet" alt="Release Badge">
      </a>
    </td>
  </tr>
</table>


## How to Contribute

- To contribute to the Alien Invasion project, please make your pull requests to the [develop](https://github.com/MatinAfzal/Alien-invasion/tree/develop) branch with a clear and detailed description in English of the changes you've made. 

- It's important to ensure your PRs are standardized, PEP8 compliant, and that you avoid large commits. Instead, break your changes into smaller, logical commits to make the review process smoother. 

- If you're adding new assets like sound effects, music, or textures, ensure that the sources are listed in the Copyright.txt file in the appropriate directory, and include the source links in your PR description if possible. 

- For ideas on what to work on, check the [TODO list discussion](https://github.com/MatinAfzal/Alien-invasion/discussions/43), or feel free to join our [Discord server](https://discord.com/invite/jBhmM2j2GN) to collaborate and share your progress. 

We appreciate your contributions and look forward to building something great.

## Project Setup

- Clone this [repository](https://github.com/MatinAfzal/Alien-invasion) or download the [latest version](https://github.com/MatinAfzal/Alien-invasion/releases).

- Next, navigate to the project directory:

```
   cd Alien-invasion
```

- Make sure you have Python 3 or later installed. Then, install the dependencies:
```
   pip install -r requirements.txt
```


- Finally, run the game:
  
```
   python3 alien_invasion.py
```

