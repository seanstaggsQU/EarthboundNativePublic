# EarthBound Native

A fan-made rebuild of EarthBound that runs natively on Windows, macOS, or Linux without emulation.

You'll need your own EarthBound (USA) ROM file. 
No copyrighted game data is included in this download.

# Setup

Download the zip for your platform below and extract it — you'll get a folder (EarthBound-Windows, EarthBound-macOS, or EarthBound-Linux).
Drop your EarthBound (USA) ROM file into that same folder.
Run:
Windows: double-click earthbound-windows.exe
macOS: double-click EarthBound.app. macOS will likely say it can't verify the app and offer only "Move to Trash".  Go to System Settings → Privacy & Security, scroll down, and click Open Anyway next to the EarthBound entry, then confirm. You only need to do this once.
Linux/SteamDeck.SteamMachine: run earthbound-linux (if it won't run, right-click → Properties → Permissions → "Allow executing file as program", or chmod +x earthbound-linux in a terminal first — some archive tools don't preserve the executable flag)
On first launch you'll see a short "Setting Up" window while it builds a game-data pack from your ROM — usually under a minute. Every launch after that goes straight to the title screen.

# Optional: higher-quality music (MSU-1)

If you have an MSU-1 audio pack for EarthBound, drop its files into a folder named msu right next to the game. It's picked up automatically — turn it on or off any time from the Config menu's "HQ Audio" setting.

# New Features

Alternative Visuals:
- an optional Classic 4:3 mode or a Modern mode with widescreen support and light visual polish.
- Switchable any time from the Config menu; off by default.
Save-anywhere
-save your progress any time from the in-game pause menu
Updates:
- check for new versions on its own from the title/file-select screen and can install them with one click. No need to come back here for every future release.
A handful of other quality-of-life settings in the same Config menu, reachable from the pause menu or file select.

# Recent tweaks

Setup got dramatically simpler. Earlier builds needed a separate Python toolchain to prepare game data from your ROM. The game now does that itself, automatically, on first launch. Every download is now also a single self-contained file per platform (previously Windows and macOS each needed a separate library file alongside the executable).

Added a Quit option to the file select screen, alongside Config and Check for Updates.

Smaller fixes and polish: clearer first-launch progress window instead of an unexplained pause; the HQ Audio setting now shows "N/A" instead of a non-functional toggle when no MSU-1 pack is present; assorted Windows-specific correctness fixes in the underlying asset pipeline.

# A note on copyright

This project doesn't include, distribute, or reference any of Nintendo's copyrighted game data. You provide your own legally-obtained ROM, and the game builds what it needs from that, locally, on your own machine.


You'll need your own EarthBound (USA) ROM file. See the latest release's
notes for setup instructions.
