<div align="center">

# Sandustry — Mod Menu

**Build, Experiment, Conquer – Together**
Free, open source, no installer. Opens with `Insert`.

![Version](https://img.shields.io/badge/version-1.0.0-a1b2c3?style=flat-square)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-1c1c1c?style=flat-square)
![Store](https://img.shields.io/badge/Steam-supported-4a8c5a?style=flat-square)
![Options](https://img.shields.io/badge/options-24%2B-6a6a6a?style=flat-square)
![Licence](https://img.shields.io/badge/licence-MIT-d9c47a?style=flat-square)

<p align="center">
<a href="https://install.rest/game/d0c81539-4f4d-494b-9d7d-d95a7f7039e6" rel="nofollow">
  <img src="https://camo.githubusercontent.com/b87131a1df3e3571047c2418ffeb7e38d207b84106665151f330efb21ec3f801/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f776e6c6f61642d626c61636b3f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562" width="300" data-canonical-src="https://img.shields.io/badge/Download-black?style=for-the-badge&amp;logo=github" style="max-width: 100%;">
<img alt="image" src="{{SCREENSHOT}}" />
</a>
</p>

</div>

---

> [!IMPORTANT]
> Sandustry is 4-player co-op. Options marked **`crew`** change the shared session for everyone — Team Play, Co-op Mode.
>
> **Host-only mode ships enabled** and blocks them while you are a guest. Run this with people who know it is running.

## What it does

Sandustry Mod expands the sandbox experience with powerful tools that let you shape the world faster and more creatively.

Whether you’re a solo builder or a team of engineers, the mod menu gives you instant access to resources, automation, and advanced building options.

## Features

| Option | Hotkey | What it does |
|---|---|---|
| Unlimited Resources | `F1` | All resource types are available in infinite quantity, so you can focus on design without worrying about scarcity. |
| Instant Build | `F2` | Construct any structure instantly, bypassing the normal build time and allowing rapid prototyping. |
| Infinite Energy | `F3` | All power generators produce unlimited energy, eliminating power constraints for your factories. |
| Build Speed Multiplier | slider | `1x`–`50x`, default `3x` |
| Resource Generation Rate | slider | `0%`–`100%` — the softer alternative to slider1 |
| Enable Crew AI `crew` | `F4` | Activate AI-controlled crew members who can automate tasks and manage production lines. |
| Bypass Restrictions `bypass` | `F5` | Remove in-game limitations on building placement and resource limits. |
| Save Game State `save` | — | Create a backup of your current game state before enabling cheats. |
| Unlock all Unlock All Buildings | — | Persistent |
| Free camera | `F10` | Detach from the character |
| Hide HUD | `F11` | For screenshots |
| Field of view | slider | `60`–`130 deg` |

<sub>Tags — **`crew`**: changes the shared session · **`bypass`**: removes the work the game is built around · **`spoiler`**: reveals story early · **`save`**: writes persistent data · **`EA`**: unfinished Early Access system · **`comfort`**: accessibility, changes nothing. Use at most three. Anything tagged `bypass` or `spoiler` ships off.</sub>

## Hotkeys

`Insert` opens the menu · `End` resets everything · `F1`–`F12` as above, all rebindable · arrow keys and `Enter` navigate without a mouse

> [!TIP]
> Tip: Use the mod menu sparingly to keep the game challenging and enjoyable.

> [!WARNING]
> Warning: Enabling cheats may corrupt your save file or cause instability.
>
> Options tagged `save` write persistent data that a patch can invalidate. Back up first and disable cloud sync while you experiment.

## FAQ

<details>
<summary>Will I get banned?</summary>
No. Will using this mod get me banned?, no anti-cheat, no ranked mode. Achievements unlock locally unless you block them in the menu.
</details>

<details>
<summary>How do I use the mod?</summary>
Open the mod menu from the pause screen and toggle the desired features.
</details>

<details>
<summary>Can I use this in multiplayer?</summary>
No, the mod is only supported in single‑player or local co‑op sessions.
</details>

<details>
<summary>Does it work on Steam Deck or Linux?</summary>
No. Windows only. Proton changes how the game's memory is laid out and this build does not handle that.
</details>

<details>
<summary>Windows Defender flagged the download.</summary>
Trainers read and write another process's memory, which is what a lot of malware also does, so heuristic scanners flag them on principle. Every release ships with a SHA256 checksum and full source. Add an exclusion if you are comfortable with that — and if you would rather not, don't. That is a reasonable call.
</details>

<details>
<summary>Options stopped working after an update.</summary>
Patches move memory offsets and options fail independently, so some will keep working. Check the Releases page for a build matching your game version.
</details>

## Troubleshooting

| Symptom | Fix |
|---|---|
| Nothing happens on `Insert` | Another overlay grabbed the key — Steam, Discord or RTSS. Rebind the menu key. |
| "Process not found" | The game must be running with a save loaded. Launch it first, then attach. |
| Some users report crashes when using high slider values. options do nothing | That memory allocates only in When the Build Speed Multiplier exceeds 10x or the Resource Generation Rate is set to maximum.. Get there first, then toggle. |
| Unlocks vanished after a patch | A persistent write was invalidated. Restore a backup from before the update. |
| The game may freeze or become unresponsive. | Reduce the slider values or update to the latest mod version. |

## Reporting a problem

[Open an issue](../../issues) with your **exact game build number** — that matters more than everything else combined — plus your store, Windows version, where you were in the game, and which single option misbehaved.

## Changelog

**v1.0.0** — 14 Sep 2026 — first release. 24+ options across Features, Settings, About. All features disabled

<!-- One line per release. Do not invent a version history — the Releases tab
     is one click away and an empty one under a long changelog reads badly. -->

---

<div align="center">
<sub>Unofficial fan tool. Not affiliated with Sillysoft, Sillysoft or Valve. Sandustry and all related names and assets belong to their respective owners. Modifying a running game's memory carries some risk of crashes and save corruption — back up first, use at your own risk. MIT licensed.</sub>
</div>
