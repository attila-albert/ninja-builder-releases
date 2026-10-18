# Ninja Builder — downloads

Ninja Builder is a local chat app that drives your own logged-in Claude Code to build websites, plans, wireframes and documents. This repository holds only the released installers and the update files the app checks. The source code is not here.

## Download

| Computer | File |
|---|---|
| Mac with Apple Silicon (M1 and later) | [Ninja-Builder-macOS-AppleSilicon.pkg](https://github.com/attila-albert/ninja-builder-releases/releases/latest/download/Ninja-Builder-macOS-AppleSilicon.pkg) (or the [.dmg](https://github.com/attila-albert/ninja-builder-releases/releases/latest/download/Ninja-Builder-macOS-AppleSilicon.dmg)) |
| Mac with Intel | [Ninja-Builder-macOS-Intel.pkg](https://github.com/attila-albert/ninja-builder-releases/releases/latest/download/Ninja-Builder-macOS-Intel.pkg) (or the [.dmg](https://github.com/attila-albert/ninja-builder-releases/releases/latest/download/Ninja-Builder-macOS-Intel.dmg)) |
| Windows 10/11 (64-bit) | [Ninja-Builder-Setup.exe](https://github.com/attila-albert/ninja-builder-releases/releases/latest/download/Ninja-Builder-Setup.exe) |
| Linux (x64) | [Ninja-Builder-Linux-x64.tar.gz](https://github.com/attila-albert/ninja-builder-releases/releases/latest/download/Ninja-Builder-Linux-x64.tar.gz) |

All versions and release notes: [Releases](https://github.com/attila-albert/ninja-builder-releases/releases).

## Install

- **Mac**: open the `.pkg` and click through. Ninja Builder lands in Applications.
- **Windows**: run `Ninja-Builder-Setup.exe`. It installs for your user only and needs no admin rights.
- **Linux**: one line in a terminal:

  ```sh
  curl -fsSL https://github.com/attila-albert/ninja-builder-releases/releases/latest/download/Ninja-Builder-install.sh | sh
  ```

You need [Claude Code](https://docs.claude.com/en/docs/claude-code) installed and logged in. Ninja Builder uses your own account.

## Updates

The app checks this repository by itself and offers new versions. Your chats, projects and settings live in `~/.ai-builder` and are kept on update and on uninstall.

## Files in this repository

- `app-manifest.json`: the newest app version and its download links, read by the app's update check.
- `kit-manifest.json` and `kit.json`: the newest Builder Kit (agents, playbooks, skills), read by the app's kit update.

These files are published automatically with each release.
