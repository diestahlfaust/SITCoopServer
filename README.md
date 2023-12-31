# Stay in Tarkov Coop Multiplayer Installation Instructions
SIT (Stay in Tarkov) Coop Installation Instructions and Client Modpack for stahlfaust's SIT Coop Server.
## [Version 1.0.0 Release](https://github.com/blayne-eyster/StahlfaustSITCoopServer/releases/tag/v1.0.0)
All BepInEx mods on included in the modpack were ported by [Lacyway](https://github.com/Lacyway/SIT-Mod-Ports). Big thanks to him!
# What is SIT?
[SIT (Stay in Tarkov)](https://github.com/paulov-t/SIT.Core) is an Escape From Tarkov BepInEx module designed to be used with the [SPT-AKI (Single Player Tarkov)](https://www.sp-tarkov.com/#features) server with the ultimate goal of "Offline" Coop.
# Using the AIO Installer and Patching Your Game Files
**Before you attempt to install SIT, please update Tarkov through the BSG launcher and then start the game.**
**Take note of your game version in the lower left corner of the screen. This version number will be important in a future step.**
1. Unzip `stahlfaust's SIT-Coop Server.zip` to an easily accessible place like your Desktop.

2. Open the `stahlfaust's SIT-Coop Server` folder, then the `Stay in Tarkov AIO Installer + Troubleshooter` folder and run `SIT-AIO-Installer.exe`  **as an administrator**.

	* Select your live Escape from Tarkov folder (this is usually under `X:\Battlestate Games\EFT`)

	* Select a destination folder for the SIT installation. I recommend creating a folder named `SIT` under your `C:\` drive (root directory) but any drive will work.

	* Click the `INSTALL - CLIENT ONLY` button. Wait for the installer to finish. If the program stops responding, **DO _NOT_ CLOSE IT!** This is normal and the program should still complete the installation. You should have two folders after completion: `X:\SIT\SIT-EFT-Install` and `X:\SIT\SIT-Launcher`.

	* If you would also like to run your own server instead of joining a friend's, click the `INSTALL - SERVER ONLY` button after the client finishes installing. After completion of the server installation you can view the documentation on configuring it [here](https://github.com/paulov-t/SIT.Core/wiki/Step-By-Step-Installation-Guide-English#configuring-the-server). **The file path will be slightly different due to the way that the installer names the folders.**

3. The installer will then prompt you to patch your new game files. Select a patcher [here](https://hub.sp-tarkov.com/files/file/204-aki-patcher/#versions) that will downgrade the current version of your newly-copied, unmodified EFT files to **13.1.3.25206 SPT**.

	* Extract the contents of the zip file, then copy `patcher.exe` and the `Aki_Patches` folder into `X:\SIT\SIT-EFT-Install` (so they are in the same folder as EscapeFromTarkov.exe)

	* Run `patcher.exe` **as an administrator**. The patching process will take several minutes. Once completed, move on to the next step.

4. Navigate to `X:\SIT\SIT-Launcher` and run `SIT.Launcher.exe`  **as an administrator**.

	* The first time you run the launcher it will prompt you:
"_No OFFLINE install found. Would you like to install now?_"

	* Click "Yes".

	* Select `X:\SIT\SIT-EFT-Install` as the installation directory.

	* Let the launcher copy your game files, this can take a few minutes.

# How to use the SIT Launcher
1. Enter the server address into the "Server" field. To join my server enter http://beyster.duckdns.org:6969.

2. Enter your desired username.

3. Enter your desired password (don't use any password you care about).

4. Click the `Launch` button to test your installation! If your game loads proceed to the next section. If your game does not load please [click here](https://github.com/blayne-eyster/StahlfaustSITCoopServer/wiki#need-help).
# Installing Client Side Mods
1. Open the `stahlfaust's SIT-Coop Server` folder that you unzipped earlier.

2. Open the `Client Mods` folder.

3. Drag and drop the `BepInEx` folder into your `X:\SIT\SIT-EFT-Install` folder. Click "Yes" to any prompts that require overwriting files.
* **If you are joining my server please do not modify any of the SAIN presets as it will cause de-sync**.
* You can modify other mods like [Amands' Hitmarker](https://hub.sp-tarkov.com/files/file/798-amands-s-hitmarker/), [Amands' Sense](https://hub.sp-tarkov.com/files/file/1361-amands-sense/) or [Fontaine's Combat Stance Overhaul](https://hub.sp-tarkov.com/files/file/1098-fontaine-s-combat-stance-overhaul/) using the "F12" key.
## Realistic Lighting Mod
If you would like to install the Realistic Lighting for EFT mod, open the `Optional Amands' Graphics + Reshade` folder and follow the installation instructions below. If you do not want to use the Reshade preset you can configure [Amands' Graphics](https://hub.sp-tarkov.com/files/file/813-amands-s-graphics/) to your liking via the "F12" key.
![Instructions](https://github.com/blayne-eyster/StahlfaustSITCoopServer/assets/135766383/15a0c6a1-a398-4a22-924e-8cc6da00db9b)
# Need Help?
* Try to run `SIT-Patcher-Troubleshooter.exe` if you're running into problems loading the game after installation.
Please DM me on Discord: "[stahlfaust](https://discord.com/users/588465573009162251)" for futher assistance.
