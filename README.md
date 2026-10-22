# 30 Yards — Dead Air

**30 Yards** is an original, fast-paced corridor-survival horror game built as a self-contained browser experience. The empty corridor changes as you run. Learn the entities' tells, dodge the hazards, collect the echoes, and try to make it through all thirty yards.

## Play

The game is a single static file: **index.html**. It does not need a build step, framework, external assets, or a backend.

### Run locally
Download **index.html** and open it in a modern browser. Progress, recovered lore, achievements, and Vault purchases are saved in that browser's local storage.

### Publish with GitHub Pages
1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then save.
4. Once GitHub Pages finishes publishing, open the site URL shown on that page.

## Controls

| Action | Keyboard | Touch |
| --- | --- | --- |
| Move between lanes | **A / D** or **← / →** | ◀ / ▶ |
| Vault over gaps | **Space** or **W / ↑** | JUMP |
| Slide under beams | **Shift, C, or ↓** | SLIDE |
| Look behind you | Hold **R** (or **Q**) | Hold R |
| Pause / resume | **Esc** or **P** | — |

## Gameplay

- **Three run modes:** Standard (thirty-yard finish), Nightmare (faster, tougher runs), and Marathon (endless survival).
- **Procedural corridor hazards:** debris, broken floor plates, low beams, spikes, echo pickups, and hidden data fragments.
- **Three original entity rules:** avoid the Peeler's marked lane, stop making inputs when the Listener warns you, and hold your nerve and look back when the Rearward comes close.
- **Run upgrades:** choose an upgrade at each fifth-yard milestone in Standard and Nightmare.
- **Persistent progression:** bank echoes, unlock field commendations, collect six lore fragments, and buy permanent upgrades in the Vault.
- **Atmosphere:** a custom canvas-rendered pseudo-3D corridor, procedural warning sounds, hit feedback, vignette, static, and optional screen shake.
- **Responsive controls:** keyboard and on-screen touch controls.
- **No dependencies:** all gameplay logic, visuals, styles, and synthesized audio are contained in **index.html**.

## Notes

This is an original work inspired by high-speed, rule-learning corridor horror. It does not use Roblox assets or require Roblox. If you clear browser storage, your local progression will also be cleared.
