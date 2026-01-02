# PDS Utilities

Install the apk above.

For the best experience, install Shizuku and run it as root from AyaSettings

A hub-style launcher for the **AYANEO Pocket DS**. One clean “Utilities” app up front, with individual tool apps running underneath hidden from the launcher for ease of use.

## What it is

PDS Utilities is a single hub app with 4 buttons, one per tool:

- **Bottom Screen Keyboard**
- **Magnifier**
- **Screen Brightness Sync**
- **Split Screen Volume**

Each tool remains seperate in the background (so each app keeps full functionality without being rewritten), while the hub handles install, update, and launch.

## How it works

When you tap a tool button:

- **Not installed** → downloads & installs the latest APK from this repo’s **GitHub Releases**, then you tap again to launch
- **Installed + up-to-date** → launches immediately
- **Installed but out-of-date** → shows an **Update** button
  - **Update** installs the latest version
  - the main button still launches without updating

## Why separate APKs?

This project is intentionally designed as a **modular tool suite**:

- Each tool app stays focused and independent and each can be downloaded seperately as standalone apps from my Github.
- Updates can ship per-tool without touching the others
- The hub stays simple: “download, install, launch”

## Hidden tools (launcher + Recents)

The tool apps are installed normally, but are configured to be:

- **Hidden from the launcher** (no app drawer icons)
- **Excluded from Recents**

This keeps the experience tidy: users interact with **PDS Utilities** only.

## Shizuku support

PDS Utilities can use **Shizuku** to install/update tool APKs more smoothly.

- If Shizuku is available and permission is granted, installs/updates can be handled via `pm install` (silent style).
- If not, the hub falls back to the standard Android install flow.

> You’ll need Shizuku set up on your device to use the Shizuku install path.

## Releases

Tool APKs are delivered via **GitHub Releases**.

The hub checks the **latest release**, compares installed versions, and prompts updates when needed.

## Compatibility

Built for Android on the AYANEO Pocket DS.  
Some functionality may rely on overlay permissions, accessibility services, or vendor behavior depending on the tool.

I dont charge for any of my projects and make them free for the communities they are in. If you like my stuff, id appreciate a tip!

https://ko-fi.com/yesitskira
