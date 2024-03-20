# Troubleshooting
This should go without saying, but **do not** contact mod authors regarding issues with this modlist.

There are many individual stages to the operation of Wabbajack, each with their own possibility to raise a issue. Most of the time, the issues fix themselves when re-running Wabbajack - don't worry though, you will not lose any progress towards the modlist install, Wabbajack will check how far it got when it restarts.

### Could not download `x`:
Mods often get updated and the old version that this modlist was running is deleted, meaning Wabbajack can no longer download the mod. In this case, you will have to wait until the modlist is updated with the new versions of the mod included.

### `x` is not a whitelisted download:
This error will happen usually when the modlist gets an update. Check to see if a new update is available for download but if there isn't, you will need to wait until there is.

### Wabbajack is unable to find my game folder:
Wabbajack will not work with pirated versions of Skyrim VR. If you didn't follow the advice in the preinstallation steps, I'd seriously advise you to do so now. [Here's a handy link to take you there automagically.](README.md\#Preparation)

### Wabbajack is unable to continue because of unknown files
Move your downloads folder outside of your Tahrovin installation folder, ensure that the Tahrovin installation folder is clear of any and all files and then close and restart Wabbajack. Remember to point it to the new location of the downloads folder! Don't want to have to download everything again.

### Missing nexusapikey:
This usually happens when Nexus Mods is having trouble on their server end. Check if you can reach the website in your browser. Unfortunately, this is usually fixed by just waiting for Nexus Mods issues to be fixed.

### LoversLab downloads keep failing
LoversLab can be difficult when it comes to automated downloads, especially to those of us located outside of the US. Try using a VPN with a location somewhere in the US. If you don't like the idea of a VPN, you'll need to grab the mods from LoversLab manually and place them in your downloads folder that you specified to Wabbajack when starting the modlist installation.

### Game won't start
1. Make sure you have the prerequisites installed as per the readme. Ensure you add your Tahrovin installation folder to your antivirus exceptions list, sometimes antivirus programs flag the virtual file system that MO2 uses even though it is completely safe.

2. If it still crashes check Tahrovin/Stock Game and make sure openvr_api.dll is present. If it is not open OC swapper in MO2 using the dropdown and click the swap button twice to regenerate it.

3. If you are using SteamVR binaries make sure SteamVR is open before you launch the game.

4. If you are not using a 20xx or newer series Nvidia graphics card or if you are using an AMD graphics card you will need to change skyrim upscaler from DLSS to FSR. Instructions for doing so are in the Skyrim Upscaler section of the main ReadMe page.