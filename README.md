# Windows-Terminal-Settings

This repository contains the settings.json file I use in Windows Terminal. It changes the appearance of applications opened through Windows Terminal, including PowerShell and Kali Linux WSL (if installed).

*NOTE:* The JSON file references JetBrains Mono NL (Non-ligature) font. As is, the JSON file won't work properly unless JetBrains Mono NL fonts are installed on your device. If you don't want to install any fonts, you can replace all instances of "JetBrains Mono NL" in the JSON file with a font already installed on your device (e.g., "Consolas").

# How to install or copy the JSON file
  Option 1 - Copy text from repository and paste using Windows Terminal GUI <br><br>
    - Open Windows Terminal <br>
    - Click the down carat to the right of any tabs that are open <br>
    - Click "Settings" <br>
    - Click the gear icon at the bottom lefthand corner of the window. This will open the settings.JSON file in whichever program is configured as your default IDE for Windows. <br>
    - Overwrite all text in the JSON file by pasting all text from the JSON file in this repository. <br>
    - Save the file <br>
    - Open Windows Terminal to use your new themes <br><br>
  Option 2 - Download the JSON file and overwrite the local copy of your settings.json file

# How to install JetBrains Mono NL fonts:
  Visit <a>https://www.jetbrains.com/lp/mono/#how-to-install</a> and click the "Download font" link
  
  The following instructions come straight from JetBrains: <br>
    - Download font <br>
    - Unzip the archive and install the font: <br><br>
    **macOS** <br>
      - Select all font files in the folder and double-click the “Install Font” button. <br><br>
    **Windows** <br>
      - Select all font files in the folder, right-click any of them, then pick “Install” from the menu. <br><br>
    **Linux** <br>
      - Unpack fonts to ~/.local/share/fonts (or /usr/share/fonts, to install fonts system-wide) and fc-cache -f -v <br>
      - Restart your IDE. <br>
      - Go to Preferences/Settings → Editor → Font, and pick JetBrains Mono from the Font dropdown. <br>
