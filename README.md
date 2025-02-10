In this tutorial I show how to run Diablo mod The Hell 3 under Linux with proton-ge-custom and Heroic Games Launcher.
=============================================

You will need:

* Heroic Games Launcher installation
* DIABDAT.MPQ file from original Diablo game. You can buy Diablo on [GOG](https://www.gog.com/eng/game/diablo) or copy file from CD version.
* The Hell 3 mod. Can be downloaded from official website [here](https://www.patreon.com/thmod/about) or [here](https://www.moddb.com/mods/diablo-the-hell-3).

Installation of Heroic Games Launcher
---------------------------------------------
Install it by downlading binaries from official website [here](https://heroicgameslauncher.com/downloads). I recommend to install from .deb file or AppImage.
Remember to update from time to time Your installation to have latest version of Heroic Games Launcher.

Installation of The Hell 3 mod
---------------------------------------------
First download mod from [here](https://www.patreon.com/thmod/about) or [here](https://www.moddb.com/mods/diablo-the-hell-3/downloads/th3). Remember to download [music](https://www.moddb.com/mods/diablo-the-hell-3/downloads/the-hell-3-music-pack) too. After that unpack everything to one folder. Copy DIABDAT.MPQ to that folder with mod files.
In config.ini file setup everything what You like mod to be. Important: leave "set DDraw off" setting in video section.

Add The Hell 3 mod to Heroic Games Launcher
---------------------------------------------
In Heroic Games Launcher click "Add game" in main screen of Your games library. The window screen popup with settings.
Setup it like that:
* Game/App Title: TH3 or The Hell 3
* App Image: https://github.com/zaisty/thmod-linux/blob/f437a36355cff4a562c6c918c2e03a32da78c170/the_hell_3_mod_custom_logo.png or download it and paste path to file.
* Platform version to install: Windows
* Show Wine settings: Change only the Wine version to proton-ge-latest. Download it on Heroic Games Launcher with Wine manager (choose Proton-GE latest version).
* Select Executable: Choose TH3.exe from mod folder.
* Click Finish (not "Run Installer first")

Run The Hell 3 mod
---------------------------------------------
On Heroic Games Launcher click on poster with mod and then click play now.
That's it. Enjoy Your game!

Issues
---------------------------------------------
The only known issue is that main menu in mod don't work properly. You must use keyboard to cycle through menu and choose Your character and game settings. After that mod runs smoothly.
