<div align="center">

# Orbit

**One app. Many tools. You decide what to focus on.**

A command center for your Mac, built around the idea that you shouldn't open six apps to get one day done. Pick a workspace, and Orbit becomes the thing you are doing right now: your apps and folders, your tasks, your timer, your Mac's health.

[**Download the latest release**](../../releases/latest) · macOS 14 or later

**English** · [Português (BR)](README.pt-BR.md)

</div>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/dashboard-dark.png">
  <img src="images/dashboard-light.png" alt="Orbit's main window: favorites of the current workspace">
</picture>

## Your focus, one click away

Orbit is not a single-purpose utility. It is a hub with a lot of rooms, and **you choose which one is open**.

- **Workspaces set the scene.** "Work", "Studio", "Side project": each one is a set of apps, folders and links. Switch workspace and everything you need is a click away. Switching never launches anything by itself.
- **The menu bar panel is yours to arrange.** Drag its blocks into the order you want, remove the ones you don't use, add them back later. It can hold your workspace switcher, favorites, a currency converter, Mac Health readings, a running timer and your clipboard status.
- **A command palette for everything.** Press **⌃⌥Space** and type: jump to a workspace, convert `100 eur in brl`, find a note, add a task, ask the assistant.

<table>
<tr>
<td width="50%" valign="top">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/menubar-dark.png">
  <img src="images/menubar-light.png" alt="The menu bar panel with the blocks you chose">
</picture>
<br><sub><b>The menu bar panel</b>, arranged your way</sub>
</td>
<td width="50%" valign="top">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/palette-convert-dark.png">
  <img src="images/palette-convert-light.png" alt="The command palette converting a currency while you type">
</picture>
<br><sub><b>The command palette</b>: convert, search, jump</sub>
</td>
</tr>
</table>

## What's inside

### Get things done
- **Tasks** with due dates written the way you say them (English and Portuguese), **quick notes** and **snippets**, with export to Obsidian and Apple Notes.
- **Clock**: countdown timers (`25m`, `1h30`, `10:00`), a pomodoro cycle with your own lengths, and world clocks by city.
- **Currency** with daily ECB reference rates, cached for offline use, and exact decimal math (no floating-point rounding).
- **Clipboard history**, opt-in and local.
- **Widgets** for currency, tasks, favorites, an overview and the clock.

### Ask, by text or voice
- A **rule-based assistant** that understands plain English and Portuguese commands, by typing or by voice (hold **⌃⌥V**; recognition runs on the device).
- An optional **AI research panel** (**⌃⌥A**) that can use your **Claude** or **ChatGPT** plan, or your own API keys. AI is off until you turn it on.
- An optional **[Conclave](https://github.com/carvalhobfr/conclave-ai)** companion that opens its local review cockpit for a folder you grant.

### Look after your Mac
- **Live readings**: CPU, memory, storage, battery, network, thermal state.
- **Disk map**: a treemap of your home folder you can walk into, with live progress while it scans and the last map kept to open at once.
- **Clean up safely**: caches and build folders go to the **Trash**, never straight to deletion, and only after you review a preview and confirm.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/health-map-dark.png">
  <img src="images/health-map-light.png" alt="The disk map: a treemap of the home folder with the largest folders highlighted">
</picture>

## Coming in the next release

Already built and being checked before it ships. Not in the current download yet.

- **Devices.** Your iPhone and iPad over a cable or Wi-Fi sync: battery health (charge, cycles, maximum capacity), storage, apps by size with the data each app keeps, the Finder backups on this Mac, an hourly battery and storage history, a battery widget and a menu bar block, and opt-in low and charged notifications. Reading is the default: nothing is installed, copied or paired. Removing an app from the phone is opt-in, asks for a confirmation that names the app and refuses Apple's own apps.
- **Accessories** (opt-in): the charge of your AirPods, Magic Keyboard, Mouse and Trackpad, and game controllers.
- **Mac Health, further:** a checkup (memory pressure, crashes, drive and battery health, and protection checks such as FileVault, firewall, Gatekeeper, updates and Time Machine, each with a plain explanation); a smart scan that tells you where to look first; app sizes, last use, uninstall and update checks (Sparkle, the App Store and Homebrew); startup items and system extensions; duplicates and old large files; disk map search, category filters, a largest-files ranking and external drives.
- **Menu bar and clock:** a "Busiest apps" block, pomodoro presets (Classic 25/5, Deep work 50/10, Sprint 15/3) and a sound for each timer.

## Principles

- **Local first.** Your data stays on your Mac. **No telemetry, no accounts, no analytics.**
- **Read first, change second.** Scans only measure. Anything that removes something is explicit, previewed and, where possible, recoverable from the Trash.
- **Secrets stay in the Keychain**, never in the app's database.
- **Native.** SwiftUI and AppKit, a monochrome design that respects Reduce Motion and Increased Contrast, English and Brazilian Portuguese.

## Install

1. Open the [latest release](../../releases/latest) and download `Orbit-<version>.zip`.
2. Unzip it and move `Orbit.app` to your **Applications** folder.
3. These builds are **not notarized by Apple**, so the first time you open Orbit macOS will refuse. Go to **System Settings → Privacy & Security** and choose **Open Anyway**.

Requires **macOS 14 or later**.

## Good to know

- **Updating:** Orbit tells you when a newer version is published (Settings → Updates) and opens its release page. Download it and replace the app in Applications. Orbit never downloads or installs anything by itself.
- **Permissions are asked for when a feature needs them**: notifications, microphone and Full Disk Access (only to map your whole home folder without prompts). macOS may ask again after an update.
- **Widgets** show "Open Orbit to sync" in these builds, because sharing data with a widget needs an Apple developer team in the signature.

## About this repository

This repository only holds the downloadable builds and this page; the source code is private. Orbit's in-app update check reads the latest release here. Each release lists what changed and how to install it. Screenshots are made from sample data.
