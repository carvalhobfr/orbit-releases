<div align="center">

# Orbit

**One app. Many tools. You decide what to focus on.**

A command center for your Mac, built around the idea that you shouldn't open six apps to get one day done. Pick a workspace, and Orbit becomes the thing you are doing right now: your apps and folders, your tasks, your timer, your Mac's health, even your iPhone.

[**Download the latest release**](../../releases/latest) · macOS 14 or later

</div>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/dashboard-dark.png">
  <img src="images/dashboard-light.png" alt="Orbit's main window: favorites of the current workspace">
</picture>

## Your focus, one click away

Orbit is not a single-purpose utility. It is a hub with a lot of rooms, and **you choose which one is open**.

- **Workspaces set the scene.** "Work", "Studio", "Side project": each one is a set of apps, folders and links. Switch workspace and everything you need is a click away. Switching never launches anything by itself.
- **The menu bar panel is yours to arrange.** Drag its blocks into the order you want, remove the ones you don't use, add them back later. Today it can hold your workspace switcher, favorites, a currency converter, Mac Health readings, the busiest apps, a running timer, your clipboard status and your iPhone's battery.
- **A command palette for everything.** Press **⌃⌥Space** and type: jump to a workspace, convert `100 eur in brl`, find a note, add a task, ask the assistant.
- **The sidebar shows what is relevant.** The iPhone section appears only while a phone is connected, unless you ask to keep it.

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
- **Clock**: countdown timers (`25m`, `1h30`, `10:00`), a pomodoro with your own lengths or presets (Classic 25/5, Deep work 50/10, Sprint 15/3), a sound for each timer, and world clocks by city.
- **Currency** with daily ECB reference rates, cached for offline use, and exact decimal math (no floating-point rounding).
- **Clipboard history**, opt-in and local.
- **Widgets** for currency, tasks, favorites, an overview and the clock.

### Ask, by text or voice
- A **rule-based assistant** that understands plain English and Portuguese commands, by typing or by voice (hold **⌃⌥V**; recognition runs on the device).
- An optional **AI research panel** (**⌃⌥A**) that can use your **Claude** or **ChatGPT** plan, or your own API keys. AI is off until you turn it on.
- An optional **[Conclave](https://github.com/carvalhobfr/conclave-ai)** companion that opens its local review cockpit for a folder you grant.

### Look after your Mac
- **Live readings**: CPU, memory, storage, battery, network, thermal state.
- **Checkup**: memory pressure, crashes, drive and battery health, and protection checks (FileVault, firewall, Gatekeeper, updates, Time Machine), each with a plain explanation.
- **Disk map**: a treemap of your home folder you can walk into, with search, category filters and a ranking of your largest files.
- **Clean up safely**: caches, build folders, duplicates and old large files go to the **Trash**, never straight to deletion, and only after you review a preview and confirm.
- **Apps**: sizes, last use, clear caches, uninstall, broken startup items, system extensions, and update checks (Sparkle, the App Store and Homebrew).
- **Smart scan**: one button that runs the checks and tells you where to look first.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="images/health-map-dark.png">
  <img src="images/health-map-light.png" alt="The disk map: a treemap of the home folder with the largest folders highlighted">
</picture>

### Look after your iPhone
- **Battery**: charge, cycles and maximum capacity. **Storage** and **apps by size**, with the data and caches each app keeps.
- It shows up over a **cable or Wi-Fi sync**. Reading is the default: nothing is installed, copied or paired from here.
- You can switch on **removing an app** from the Mac. It is off by default, asks for a confirmation that names the app, and refuses Apple's own apps.

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
- **Permissions are asked for when a feature needs them**: notifications, microphone, Full Disk Access (only to map your whole home folder without prompts) and Bluetooth (only if you look for paired phones). macOS may ask again after an update.
- **Widgets** show "Open Orbit to sync" in these builds, because sharing data with a widget needs an Apple developer team in the signature.
- **Administrator actions** (removing a broken system startup item) are off by default. Turn them on in Settings; macOS then asks for your password in its own window, and Orbit never sees it.

## About this repository

This repository only holds the downloadable builds. Orbit's in-app update check reads the latest release here. Screenshots are made from sample data and will be refreshed.

---

# Orbit (pt-BR)

Uma central de comando para o seu Mac: espaços de trabalho, barra de menu que você arruma do seu jeito, paleta de comandos, tarefas, relógio, moeda, saúde do Mac e do iPhone, e um assistente por texto ou voz. **Um app, muitas ferramentas, e você decide o foco.** Dados locais, sem telemetria.

Baixe a [última versão](../../releases/latest), descompacte, mova o `Orbit.app` para Aplicativos e, na primeira abertura, vá em **Ajustes do Sistema → Privacidade e Segurança → Abrir Mesmo Assim** (os builds não são notarizados pela Apple). Requer macOS 14 ou mais recente.
