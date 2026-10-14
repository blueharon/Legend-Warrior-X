# Legend Warriors X: Hero Signature Looks Edition

This edition gives each of the seven heroes a distinct procedural silhouette and armor details, while preserving the existing game, powers, realms, tournament, evolution, and endless modes. It does not use an imported custom 3D model.

## Run locally
1. Extract this ZIP.
2. Open a terminal/Command Prompt in this `lwx_allthree` folder.
3. Run `python -m http.server 8000`.
4. Open http://localhost:8000 in your browser.

An internet connection is needed for the Three.js CDN import.


## Hero animation upgrade
Each hero now has a distinct movement rhythm, idle stance, and ultimate finishing pose. Weapon Art effects remain hero-specific (lightning, void portals, titan ground slam, solar/aether bursts, and nature roots).

## Combo and ultimate upgrade
Normal attacks cycle through Quick Cut, Double Strike, Cross Slash, and Finisher Smash, with escalating hit effects and combo damage. Each hero also has a named ultimate cinematic and hero-specific signature effects, plus a finishing impact around the boss.

## Boss evolution upgrade
Guardians now gain visible phase armor as their health drops: an energized shoulder/crown silhouette in Phase II and a larger crown/halo form in Phase III. Enraged guardians can trigger a clearly telegraphed Apocalypse Shockwave with a wider danger radius, heavier impact effects, and stronger damage. Existing realm-specific signature attacks remain in place; move outside the warning ring to evade the shockwave.


## Legendary Equipment upgrade
- Equip four visible armor sets with unique color accents and stat bonuses.
- Select among the four weapons from the equipment panel; Q still cycles weapons in-game.
- Armor and weapon selections persist in the local save.
- Armor sets affect movement speed, damage, or incoming boss damage.


## Elemental Skill Tree & tougher bosses
- Boss health is increased substantially in normal mode and even more in Tournament Mode, with additional scaling as your hero levels up.
- Earn a skill point for each boss defeated and each level gained.
- Spend points in Lightning Mastery (strike/blast damage), Fire Core (ultimate/weapon-art damage), Void Veil (reduced boss damage taken), and Nature’s Vigor (more energy per attack). Each path has three ranks and progress is saved locally.
- Skill Tree is below Legendary Loot.

## Difficulty selection
Use the DIFFICULTY button on the start screen to cycle Story, Normal, Hard, and Nightmare. Difficulty changes boss maximum health, attack damage, and attack cadence. The current choice applies immediately while preserving the boss's remaining health percentage. Tournament Mode can be combined with any difficulty for an extra challenge.
