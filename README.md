<div align="center">
  <img src="assets/app_icon.png" width="128" height="128" alt="Rapps Launcher Logo" />
  <h1>Rapps Launcher - Releases & Downloads</h1>
  <p>Official pre-built releases, installers, and distribution packages for <a href="https://github.com/kentrussel-dev/RappsLauncher">Rapps Launcher</a>.</p>

  <p>
    <a href="https://github.com/kentrussel-dev/RappsLauncher-Releases/releases"><img src="https://img.shields.io/badge/Release-v1.2.0-blue?style=flat-square&logo=github" alt="Latest Release" /></a>
    <a href="https://github.com/kentrussel-dev/RappsLauncher-Releases"><img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0078D4?style=flat-square&logo=windows11&logoColor=white" alt="Platform" /></a>
    <a href="https://github.com/kentrussel-dev/RappsLauncher/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square" alt="License: MIT" /></a>
  </p>
</div>

---

## Downloads (Version 1.2.0)

| Package | Format | Architecture | Download Link |
|---|---|---|---|
| **Windows Setup Wizard (Recommended)** | `.exe` | Windows x64 | **[Download RappsLauncher-Setup-v1.2.0.exe](releases/RappsLauncher-Setup-v1.2.0.exe)** |
| **Portable Zip Package** | `.zip` | Windows x64 | **[Download RappsLauncher-v1.2.0-Portable-win-x64.zip](releases/RappsLauncher-v1.2.0-Portable-win-x64.zip)** |

---

## Showcase

### Multi-Application Workspace Orchestration
Group applications, terminals, web dashboards, and development servers with customized staggered execution delays:

<p align="center">
  <img src="assets/showcase-workspace.png" width="850" alt="Multi-Item Developer Workspace" />
</p>

### Daily Workflow & Custom Icons
Organize your daily communication tools, browser tab sessions, and project boards with custom workspace logos:

<p align="center">
  <img src="assets/showcase-comms.png" width="850" alt="Daily Workflow and Comms" />
</p>

### Modern Fluent Settings
Configure startup behaviors, theme preferences, execution thresholds, Unity Hub paths, and diagnostics with an adaptive, responsive interface:

<p align="center">
  <img src="assets/showcase-settings.png" width="850" alt="Responsive Fluent Settings" />
</p>

---

## What's New in Version 1.2.0

- **Workspace Import & Export**: Export single or all workspaces to `.rapps.json` files; import configs with automated validation, user profile path warnings, and collision handling (Rename / Overwrite / Skip).
- **Workspace Search & Live Filter**: 150ms debounced live search in the sidebar with clean no-match feedback and drag-and-drop safety protection.
- **Per-Workspace Windows Startup**: Toggle individual workspaces to launch automatically on Windows startup via dedicated Windows Task Scheduler tasks (`RappsLauncher-Startup-<id>`).
- **Launch History & Status Tracking**: Persistent rolling 200-entry history logging with relative timestamps, success counts, item durations, and an expandable History Dialog.
- **Silent Auto-Update Checks**: Background update checking against GitHub Releases with an in-app banner, download link, and "Skip This Version" suppression.

---

## Installation Guide

### Option 1: Windows Setup Wizard (Recommended)
1. Download **`RappsLauncher-Setup-v1.2.0.exe`**.
2. Run the executable and follow the setup wizard.
3. The wizard will automatically install Rapps Launcher, create Desktop & Start Menu shortcuts, configure Windows Search indexing, and launch the application.

### Option 2: Portable Deployment
1. Download and extract **`RappsLauncher-v1.2.0-Portable-win-x64.zip`** to any directory.
2. Run `RappsLauncher.exe` directly.

---

## Windows SmartScreen Notice

Because Rapps Launcher is distributed as a self-published open-source application, Windows SmartScreen may display an unrecognized application prompt during initial launch.

### How to Run:
1. On the Windows SmartScreen dialog, select **More info**.
2. Select **Run anyway**.

---

## Source Code

The complete C# and .NET 8 WPF source code repository is available at:  
[https://github.com/kentrussel-dev/RappsLauncher](https://github.com/kentrussel-dev/RappsLauncher)
