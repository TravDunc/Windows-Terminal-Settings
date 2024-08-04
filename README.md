# Windows-Terminal-Settings

This repository contains the settings.json file I use in Windows Terminal. It changes the appearance of applications opened through Windows Terminal, including PowerShell and Kali Linux WSL (if installed).

# How to install or copy the JSON file
  Option 1 - Copy text from repository and paste using Windows Terminal GUI
  Option 2 - Download the JSON file and overwrite the local copy of your settings.json file

The JSON file references JetBrains Mono NL (Non-ligature) font. That font will need to be installed on your device for this JSON file to work properly. Alternatively, you can change all instances of "JetBrains Mono NL" to something that is already installed on your device (such as "Consolas").

# How to install JetBrains Mono NL fonts:
  Visit: https://www.jetbrains.com/lp/mono/#how-to-install
  Click the "Download font" link
  The following instructions come straight from JetBrains:
    - Download font
    - Unzip the archive and install the font:
    **macOS**
      - Select all font files in the folder and double-click the “Install Font” button.
    **Windows**
      - Select all font files in the folder, right-click any of them, then pick “Install” from the menu.
    **Linux**
      - Unpack fonts to ~/.local/share/fonts (or /usr/share/fonts, to install fonts system-wide) and fc-cache -f -v
      - Restart your IDE.
      - Go to Preferences/Settings → Editor → Font, and pick JetBrains Mono from the Font dropdown.
