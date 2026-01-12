This is a hub-style launcher for the **AYANEO Pocket DS**. One clean “Utilities” app up front, with individual tool apps running underneath hidden from the launcher and home page for ease of use.

# **Install the APK above to use!**

---

## What tools are available?

### *Bottom Screen Keyboard:*
  - This adds a keyboard to the DS that stays on the bottom screen.
  - Has dark and light modes.
  - An option to add an a toggle to open the keyboard with a button on the DS.
  - Has alternative characters for a few other languages.

### *Split Screen Volume:*
  - This tool lets you control the volume of the apps on each screen seperately.
  - It replaces the stock volume UI with an updated one with multiple sliders.

### *Brightness Sync:*
  - This app allows you to sync the brightness of the bottom screen to the top screen.
  - Has a calibration screen to help you match the brighnesses irl.
  - You can still adjust the bottom screen brightness seperately with the slider in Ayawindow.

### *Refresh Rate Tool:*
  - Allows you to set the top screen to a range of refresh rates 60hz, 90hz, 120hz, 144hz and 165hz.
  - As stock, the top screen defaults to 120hz at all times. This tool adds 144hz and 165hz options too.
  - 60hz is great for saving battery.

### *Bottom Screen Colour Corrector:*
  - This tool adds an overlay to help you correct the yellow tint of the bottom screen.
  - Lets you calibrate to get the screens to match a little more closely.

### *Bottom Screen Magnifier:*
  - This is a tool that lets you magnify part of the top screen onto the bottom screen.
  - For games that dont make use of the bottom screen, you can magnify the minimap to the bottom.

---

## Why separate APKs?
This project is intentionally designed as a **modular tool suite**:
- The tools remain seperate in the background, while the hub handles install, update, and launch.
- Each tool app is modular and independent and each can be downloaded seperately.
- Updates can ship per-tool without touching the others.
- The hub stays simple: “download, install, launch”

## Hidden tools (launcher + Recents)
The tool apps are installed normally, but are configured to be:
- **Hidden from the launcher** (no app drawer icons)
- **Excluded from Recents**

## Shizuku requirements:

PDS Utilities uses **Shizuku** to install/update tool APKs more smoothly and alot of the tools themselves need Shizuku too.
If Shizuku is available and permission is granted, installs/updates can be handled silently.


## Releases:
Tool APKs are delivered via **GitHub Releases**.
The hub checks the **latest release**, compares installed versions, and prompts updates when needed.

## Compatibility:
Built for Android on the AYANEO Pocket DS.  
Some functionality may rely on overlay permissions, accessibility services, or vendor behavior depending on the tool.


## Credits:
I dont charge for any of my projects and make them free for the communities they are in. If you like my stuff, id appreciate a tip!

https://ko-fi.com/yesitskira
