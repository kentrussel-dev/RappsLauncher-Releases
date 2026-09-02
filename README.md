<div align="center">
  <img src="assets/app_icon.png" width="128" height="128" alt="Rapps Launcher Logo" />
  <h1>Rapps Launcher - Releases & Downloads</h1>
  <p>Official pre-built releases, installers, and distribution packages for <a href="https://github.com/kentrussel-dev/RappsLauncher">Rapps Launcher</a>.</p>

  <p>
    <a href="https://github.com/kentrussel-dev/RappsLauncher-Releases/releases"><img src="https://img.shields.io/badge/Release-v1.1.0-blue?style=flat-square&logo=github" alt="Latest Release" /></a>
    <a href="https://github.com/kentrussel-dev/RappsLauncher-Releases"><img src="https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0078D4?style=flat-square&logo=windows11&logoColor=white" alt="Platform" /></a>
    <a href="https://github.com/kentrussel-dev/RappsLauncher/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square" alt="License: MIT" /></a>
  </p>
</div>

---

## Downloads (Version 1.1.0)

| Package | Format | Architecture | Download Link |
|---|---|---|---|
| **Rapps Launcher Installer & Portable (v1.1.0)** | `.zip` | Windows x64 | **[Download RappsLauncher-v1.1.0-win-x64.zip](releases/RappsLauncher-v1.1.0-win-x64.zip)** |

---

## What's New in Version 1.1.0

- **Custom Workspace Images**: Workspaces can now use custom image files (PNG, JPG, ICO, WebP, SVG) as their icon with live preview in the workspace editor.
- **Black & White Brand Theme**: UI accent palette updated to match the monochrome aesthetic of the brand logo.
- **Responsive Settings Page**: Redesigned settings view with flexible layout, categorized cards, and auto-expanding input controls without text truncation.
- **Clean Browser Tab Visualization**: Browser tab groups now display with structured title pills and clean URLs instead of raw storage strings.

---

## Installation Guide

### Option 1: Automated Installer (Recommended)
1. Download `RappsLauncher-v1.1.0-win-x64.zip` and extract its contents.
2. Run `Install-RappsLauncher.bat` (or execute `Install-RappsLauncher.ps1`).
3. The installation script will automatically:
   - Copy application binaries to the local application directory
   - Create a Desktop shortcut with the application icon
   - Create a Start Menu shortcut for Windows Search indexing
   - Configure Windows Startup registration
   - Launch Rapps Launcher

### Option 2: Portable Deployment
1. Extract `RappsLauncher-v1.1.0-win-x64.zip` to your preferred directory.
2. Execute `RappsLauncher.exe` directly.

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
