<div align="center">

**English** · [Português (Brasil)](README.pt-BR.md) · [Español](README.es.md)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="media/aioncore-logo-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="media/aioncore-logo-light.svg">
  <img alt="AionCore" src="media/aioncore-logo-light.svg" width="340">
</picture>

### See your Party's DPS, find Hidden Cubes and control it all from a bar over the game.<br>A free companion app for Aion 2 on Windows.

[![Version](https://img.shields.io/github/v/release/filvoch/AionCoreUpdate?label=version&color=1a9bbd)](https://github.com/filvoch/AionCoreUpdate/releases/latest)
![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows&logoColor=white)
![Free](https://img.shields.io/badge/price-free-2ea44f)

<a href="https://github.com/filvoch/AionCoreUpdate/releases/latest/download/AionCore-Setup.exe"><img alt="Download AionCore for Windows (AionCore-Setup.exe)" src="https://img.shields.io/badge/Download_for_Windows-AionCore--Setup.exe-1a9bbd?style=for-the-badge&logo=windows&logoColor=white"></a>

<sub>About 160 MB installer · updates itself · Windows 10 or 11, 64-bit · [All versions](https://github.com/filvoch/AionCoreUpdate/releases) · [Website](https://aioncore.app/en) · [Discord](https://aioncore.app/discord)</sub>

<img alt="Screenshot of the Cube radar, north up: you in the center with an arrow for where you are facing, three Hidden Cubes around you, the nearest one highlighted with a line, and the text &quot;Cube 38 m northeast&quot; and &quot;+2 more · ahead, to the right&quot; (app in English, sample data)" src="media/shot-radar.jpg" width="820">

</div>

> [!NOTE]
> The meter needs [Npcap](https://npcap.com) (the installer checks and tells you if it is missing), and Aion 2 must run in **Borderless window** or **Windowed** mode. See [Install in 3 steps](#install-in-3-steps).

## Why download it

- **See who carried the fight.** Damage, DPS and share for every player in your Party, skill by skill.
- **Never lose a fight.** Every fight is saved in the history on your PC, so you can compare it with your next attempt.
- **Find the Hidden Cube.** The radar opens by itself when the game shows a cube nearby and tells you where to go.
- **Everything in one bar over the game.** One button per window, a lock that lets clicks through, and nothing in the way when you open the map or the inventory.

## What's new from 1.17 to 1.20

- **Game map in the app:** a new, free **Map** tab with gathering, monsters, teleports, dungeon entrances, cubes and field bosses. Live, it shows your position and can notify you when a field boss respawns.
- **Connect with Discord from your browser:** the button opens the browser and brings you back to AionCore connected, with no code to type.
- **Bigger and better radars:** the pet radar now has the map on top and a list below, both radars zoom and resize freely, the Cube radar marks a cube that is well above or below you, and the game map shows behind the dots.
- **Interface scale from 75% to 200%** (Ctrl +, Ctrl − and Ctrl 0) and a meter that can grow upward.
- **More numbers, free:** a new **APS** (hits per second) tab, effective healing and overheal, and tooltips that explain every metric. Supporters also get **Skill analysis** and a revamped **Supporter** tab.

[Everything that changed](https://github.com/filvoch/AionCoreUpdate/releases/latest) · [The new screens on the website](https://aioncore.app/en/features)

## Party DPS meter

- **The whole Party at a glance:** one row per player with damage, DPS and share. **HPS**, **APS** (hits per second) and **Taken** tabs for healing, hits and damage taken. Scope **Me**, **Party**, **Raid** or **Automatic**.
- **Skill breakdown:** click a name to see hits, crits, back attacks, multi-hits, average, min and max, a chart and the hit log.
- **Boss timers:** Boss HP in numbers, **Kill in** (estimate from how fast the HP is dropping) and **Enrage in** for bosses with a known enrage timer.
- **Every fight saved on your PC:** **History**, a summary of each fight, **Compare fights**, **Boss runs**, death recap, and export to JSON, CSV or PNG.
- **Floating party:** your Party's health in a small window.
- **Five free looks:** Stripes, Classic, Dense, Panel and Glass, plus the **Glass finish** over Dense, Panel and Stripes.
- **Bottom bar, free in every look:** copy the Party's DPS to the chat (AionCore only copies; you paste it) and a screenshot of the meter only.

<p align="center"><img alt="Screenshot of the AionCore Meter in the Stripes look during a boss fight: boss HP with Kill in and Enrage in at the top, then one row per player for six players with damage, DPS and share (app in English, sample data, invented names)" src="media/shot-meter.jpg" width="400"></p>

## Hidden Cube radar

A small window that opens by itself when the game reports a Hidden Cube near you, and hides again when none are left.

- **Automatic:** it opens when an unopened cube appears and hides about 3 seconds after the last one is gone. Prefer to always see it? Turn on **Keep the radar always visible**.
- **North up**, like the in-game minimap, or **Turns with you**.
- **Several cubes:** the cube you are tracking gets the big dot and the line; the text shows "+N more".
- **Height, zoom and size:** a cube 3 m or more above or below you gets a ▲ or ▼ mark and the text says how many meters. Unlock the radar to zoom with the wheel and drag its edges.
- **Alerts that tell you where to go:** within 80, 50, 25 and 10 m, whether the cube is to your right, ahead or behind, and when another player has already opened it.

The radar shows only cubes the game sends. The game reports your own position only when you use a skill or dash, so without a recent position the radar shows "Cube detected" and asks you to move. Everything is in **Settings › Alerts and events**.

<p align="center"><img alt="Animated demo of the Cube radar: a Hidden Cube to the northeast, ahead of you, gets closer as you move toward it, from 85 m down to 18 m (app in English, sample data)" src="media/demo.gif" width="720"></p>

## Top bar and main window

- **Top bar:** one button each for the meter, the floating party, the checklist, the timers, the pet radar, the mechanic alerts, the dungeon guide and YouTube. The padlock locks everything and clicks go straight through to the game. Opacity from 20% to 100% and a collapsed mode.
- **Main window:** Home with the countdown to the daily and weekly reset, your characters, upcoming events and your last fight; Ctrl+K searches screens and commands. Open it from the bar, the Windows tray or with Ctrl+Alt+A.
- **Out of the way:** the bar and the overlays hide when another program is in front and when a game menu opens (Esc, map, inventory). With **Open AionCore as administrator** on, AionCore checks only whether the Alt and Esc keys are pressed, only while the game is in front; no other key, and nothing is recorded or sent. Without administrator mode, it goes by the game's cursor. Turn it off in **Settings › In-game**.
- **Ctrl+Alt shortcuts** that work over the game (M meter, G party, H collapse the bar, L lock, K click-through, D hide everything). If another program already uses one, AionCore offers to change it.
- Threat, PvP target and Arena appear dimmed on the bar: **coming soon**. The **Map** is a free tab in the main window.

<p align="center"><img alt="Screenshot of the AionCore bar: the name on the left, a row of icon buttons, the opacity control at 100%, the lock and the collapse, settings and close buttons (app in English)" src="media/shot-bar.jpg" width="880"></p>

<p align="center"><img alt="Screenshot of the main window on Home: side menu with Home, Checklist, Meter, Dungeons, Schedule and Pets, the daily and weekly reset countdown, what not to miss, two characters, upcoming events and the last fight (app in English, sample data, invented names)" src="media/shot-home.jpg" width="820"></p>

## Boss mechanics

- **Mechanics panel:** what the boss does and what you should do, by dungeon. Free. Coverage grows with each version, and mechanics not yet checked in game are marked.
- **On-screen mechanic alerts:** one to three words at the top of the screen before the hit. Supporters get them first; everyone gets them starting **November 10, 2026**.

## In validation

These already ship with the installer and passed the automated tests, but have not been checked live in game yet:

- **Checklist:** daily and weekly tasks per character. Duty Missions, today's Kinah limit, this week's Abyss Points and Odyle energy are read from the game; you tick the rest.
- **Schedule and Timers:** the week's events with a countdown, and field bosses read from the game when you open the world map.
- **Pets:** your collection by family, the souls you still need and where to farm them. The **pet radar** lists nearby monsters that drop a soul you still need; it comes turned off.

<table>
  <tr>
    <td width="50%"><img alt="Screenshot of a character's Checklist: Odyle energy, gain limits, daily and weekly tasks, some read from the game and others ticked by hand (app in English, sample data, invented names)" src="media/shot-checklist.jpg"></td>
    <td width="50%"><img alt="Screenshot of the Schedule: the week's events with times and a countdown, and the field bosses block waiting for the in-game map to be opened (app in English, sample data)" src="media/shot-agenda.jpg"></td>
  </tr>
  <tr>
    <td align="center"><sub>Checklist</sub></td>
    <td align="center"><sub>Schedule</sub></td>
  </tr>
  <tr>
    <td width="50%"><img alt="Screenshot of the Pets tab: the collection by family, the farm map with spawn points for each family and the pets closest to their next level (app in English, sample data)" src="media/shot-pets.jpg"></td>
    <td width="50%"><img alt="Screenshot of the pet radar: nearby monsters that drop a soul you still need, with approximate distance and a mini radar (app in English, sample data)" src="media/shot-petradar.jpg"></td>
  </tr>
  <tr>
    <td align="center"><sub>Pets</sub></td>
    <td align="center"><sub>Pet radar</sub></td>
  </tr>
</table>

Something looks wrong? Tell us on [Discord](https://aioncore.app/discord) or open an [issue](https://github.com/filvoch/AionCoreUpdate/issues).

## Install in 3 steps

Requirements: Windows 10 (1809 or newer) or 11, 64-bit.

1. [Download the installer](https://github.com/filvoch/AionCoreUpdate/releases/latest/download/AionCore-Setup.exe) and run it. It installs for your user only. If Windows says "Windows protected your PC", click **More info**, then **Run anyway** ([why](#faq)).
2. Install [Npcap](https://npcap.com) once, with *Install Npcap in WinPcap API-compatible Mode* and *Support loopback traffic* checked. If it is missing, the AionCore installer tells you and opens the Npcap website at the end.
3. Open AionCore from the shortcut. In Aion 2, use **Borderless window** or **Windowed**: Windows doesn't let anything show over exclusive full screen.

The first time you open it, you pick your language and region and read the usage and data notice. Connecting your Discord account is optional. App and website in 6 languages: English, Portuguese, Spanish, German, French and Russian (German, French and Russian are reviewed machine translations, not yet checked by native speakers).

AionCore updates itself: it verifies the installer's digital signature and does not install by itself while Aion 2 is open (if you click **Update** with the game open, it asks you first, and the meter loses the fight in progress). Your settings and fight history are kept between versions.

## For supporters

AionCore is free. If you want to help keep it running, you can chip in any amount on Ko-fi. A one-time payment of **US$ 15 or more, in US dollars** (the Ko-fi shop item or a one-time donation) makes you a **Supporter for 12 months**, **with no auto-renewal**. Smaller amounts are a thank-you with no perks. **Everything already released for free stays free forever.**

What supporters get today:

- **AionCore Theme:** the new meter look, with a two-line header, a trend arrow on every player row, up to 4 columns per role (Tank, DPS and Healer) and **Only me** with your best skills.
- **Out-of-game alerts:** alt-tabbed out or game minimized? Party invites, Expedition invites, calls to join and join requests pop up over any window. Click one and AionCore brings the game to the front; it never clicks or accepts anything for you. Free for everyone from January 11, 2027.
- **Room panel:** who is in the room, their GS and Combat Power, and who is ready. Free for everyone from February 11, 2027.
- **Applicant card:** whoever asks to join your room shows up in a small window with class, level, GS and the fights you already had together, and you can look up their public profile summary on the website.
- **Color themes** for the meter.
- **Skill analysis:** a tab in each player's details, live and in History, with estimated uses, damage per use, active DPS, peaks and a timeline for every skill.
- **Supporter badge:** a badge on your own meter row with a gem, a style and a motion, plus an Aether bar in the color of your bar. Only you see it on your meter.
- **Arena report:** in the Summary of an Arena fight, a card with result, score, duration, kills and deaths (anything the game has not reported yet stays blank; today only a win is recognized).
- **Before everyone else:** boss mechanic alerts (until November 10, 2026) and boss guard bar notices (until November 11, 2026).

<table>
  <tr>
    <td width="50%"><img alt="Screenshot of three stacked out-of-game alert cards: a Call to join, an Expedition invite and a Party invite, each with the player's class, level, GS, Combat Power and server (app in English, sample data, invented names)" src="media/shot-alerts.jpg"></td>
    <td width="50%"><img alt="Screenshot of the Room panel: four members with GS, Combat Power, level and ready status, one open slot and two join requests (app in English, sample data, invented names)" src="media/shot-room.jpg"></td>
  </tr>
  <tr>
    <td align="center"><sub>Out-of-game alerts</sub></td>
    <td align="center"><sub>Room panel</sub></td>
  </tr>
</table>

[Support AionCore](https://aioncore.app/en/support)

<sub>No paid advertising. On Home and in Settings › About there is a partner card (affiliate link), flagged on screen: AionCore may earn a commission at no extra cost to you.</sub>

## Your data

Your fights stay on your PC. Without connecting an account, no fight leaves it. Connecting an account (through Discord) is optional; when you connect, a notice shows what goes to [aioncore.app](https://aioncore.app/en) and uploading boss fights and inspections turns on. Turn it off with one click in **Settings › Account and upload**. Details in the [privacy policy](https://aioncore.app/en/privacy).

## FAQ

<details>
<summary><b>Can I get banned?</b></summary>

AionCore reads your PC's network traffic and the game window title. It does not change game files or game memory. It sends no keys or clicks to the game: copying the DPS to the chat only copies it, and you paste it yourself. Even so, no tool of this kind can guarantee what the game's policy decides: use it at your own risk.
</details>

<details>
<summary><b>Does AionCore read what I type?</b></summary>

No. With **In the game menus** on and AionCore running as administrator, it checks only whether the Alt and Esc keys are pressed, and only while Aion 2 is in front, to know whether a game menu opened. No other key is read, and nothing is recorded or sent. Turn it off in **Settings › In-game**.
</details>

<details>
<summary><b>Which servers and regions work?</b></summary>

Built and tested on Aion 2 Global (South America servers). Other regions (Taiwan, Korea) may work, but are not guaranteed yet.
</details>

<details>
<summary><b>Is the meter accurate?</b></summary>

It counts what the game sends. In some cases the meter cannot see everything, and it tells you when it is not reading the game. The website explains how it measures: [accuracy](https://aioncore.app/en/accuracy).
</details>

<details>
<summary><b>Do I need to run it as administrator?</b></summary>

Not by default: AionCore installs for your user only and opens without asking for administrator rights. Three cases change that:

- If your Npcap was installed with *Restrict Npcap driver's access to Administrators only*, the meter shows a **Reopen as administrator** button (that time only). To never need it, reinstall Npcap without that option.
- **In the game menus** (hide the bar and the overlays when a game menu opens): to see whether Alt and Esc are pressed while the game is in front, AionCore must run as administrator. Without that, it goes by the game's cursor.
- If Aion 2 runs as administrator, clicking an out-of-game alert brings the game to the front only when AionCore runs as administrator too.

For these cases there is **Settings › General › Open AionCore as administrator**, off by default. When you turn it on, Windows asks for permission (UAC).
</details>

<details>
<summary><b>The bar or the meter disappears when the game is in front.</b></summary>

The game is in exclusive **Full screen**, and Windows shows no window on top of it. In Aion 2's video options, switch to **Borderless window**.
</details>

<details>
<summary><b>Windows or my antivirus warned me during install.</b></summary>

The installer has no paid code-signing certificate, so Windows does not know the publisher and shows "Windows protected your PC". Click **More info**, then **Run anyway**. An antivirus may ask for confirmation for the same reason. To check that the file is the original, compare the `sha256` value in `latest.json` (in the Assets of the [latest release](https://github.com/filvoch/AionCoreUpdate/releases/latest)) with the output of:

```powershell
Get-FileHash .\AionCore-Setup.exe
```
</details>

<details>
<summary><b>What leaves my PC?</b></summary>

Without a connected account, no fight leaves your PC. AionCore downloads skill icons from the game's CDN and checks this repository for new versions. With an account connected, boss fights and inspections go to aioncore.app, as the notice says before it turns on; turn it off in **Settings › Account and upload**. The profile lookup on the applicant card sends only name and server (turn it off in **Settings › Alerts and events › Party invite**).
</details>

<details>
<summary><b>How do I uninstall? Do I lose my data?</b></summary>

*Windows Settings › Installed apps › AionCore*. The uninstaller asks whether to delete your data too (history, settings); by default it keeps them. Installing a new version over the old one also keeps everything.
</details>

<details>
<summary><b>Is it official? Is the code open?</b></summary>

No to both. AionCore is an independent project made by a player, not affiliated with NCSOFT. The source code is not public: this repository holds the published installers, this page and the translation files, which are open to contributions.
</details>

## Contribute

- **Bugs and ideas:** open an [issue](https://github.com/filvoch/AionCoreUpdate/issues/new/choose) and pick a template (bug report, feature request or translation suggestion). Never paste character names, logs or packets without removing the names first.
- **Translations:** the app's text is in the [`i18n/`](i18n/README.md) folder. To fix a word, open a *Translation suggestion* issue; for a whole language, send a pull request.
- **Security:** report vulnerabilities in private by writing to contato@aioncore.app, not in a public issue. See [SECURITY.md](SECURITY.md).

## Community and contact

- **Discord:** [aioncore.app/discord](https://aioncore.app/discord)
- **Bugs:** open an [issue](https://github.com/filvoch/AionCoreUpdate/issues) or write to contato@aioncore.app.
- **In the app:** **Settings › Help and diagnostics**.

## Credits

AionCore by **Simavi**.
Independent fan project, not affiliated with NCSOFT. Aion 2 and its icons, names and art belong to NCSOFT and its licensors.

