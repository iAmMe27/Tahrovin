# Tahrovin

First things first: **this list contains adult content and you must be of legal age in your country. This means 18+ in most countries, 21+ in others. It is up to you to be sure of the age requirement in your country.**

---
## What is Tahrovin?
Tahrovin is a NSFW Skyrim VR modlist that aims to improve and add upon the Skyrim VR experience. The list features most, if not all, of the fundamental mods needed for any Skyrim VR mod list. The list offers plenty of eye candy paired with everyone's favourite jiggle physics. Yes, this means plenty of slooty outfits and selectively crafted bodyslides - and no, it's not supposed to be immersive. Don't worry for those who prefer to play as a male character, males have also received attention in this list.

---
## Before You Start
Before you dive in, there's a couple things you need to be sure of first:

### Hardware Requirements
I run a relatively powerful PC with the following specs:
  * CPU: Ryzen 7 5800X
  * RAM: 32GB DDR4 @ 3600MHz
  * GPU: RTX 3080

I use an Oculus Quest 2 headset with an Oculus link cable for the best potential performance. 

Now, I have not built this list to be as graphically intensive as possible but I have taken some liberties in installing higher resolution textures as well as offering a couple of the more demanding ENB presets available. With that in mind, I'd recommend at least the following specs for the best experience:
  * CPU: Intel 7th gen *OR* AMD Ryzen 3000 series 
  * RAM: 16GB of DDR4
  * GPU: GTX 1080 *or the AMD equivalent with at least 6GB of VRAM*

You will need at least `XYZ GB` of disk space on an SSD. It doesn't have to be an NVMe SSD, but a HDD of any kind will make the list painfully unplayable. 

### Accounts
In terms of accounts you will need:
  * Nexus Premium Account
  * LoversLab Account

Whilst you don't *need* a Nexus premium account to install the modlist, you'll have a considerably better time of it if you do.

---

## Installation
Please follow all of steps below if it is your first time installing this modlist, if you're updating you can jump straight to that part.

### Preparation

#### Install Microsoft Visual C++ Redistributable Packages
This package is a must as it is needed by MO2 - you may already have it, especially if you've used MO2 before. You want to download the x64 version under "Visual Studio 2015, 2017 and 2019".

[Download Visual C++ Redistributable Package.](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170)

#### Configuring Steam
In both global and game settings within Steam and Oculus settings you must ensure the following is set:
  * Supersampling is *OFF*
  * Render Resolution to 100% (1.0 if you're looking at Oculus settings)

#### Disable Steam Overlay
The Steam overlay is known to cause issues for both Skyrim VR and regular Skyrim SE/AE, especially when using ENBs. I recommend you turn it off to be sure that it doesn't interfere in any way and you can do so by heading into Steam, right
clicking on Skyrim VR in your game library and clicking **Properties** > **General** > **Deselect "Enable Steam Overlay while in-game"**.

#### Set game language to English
Wabbajack and some/most of the modding tools out there only support English language versions of Skyrim. Setting the language to English in Steam will stop issues like Wabbajack file verification failures when installing. As with disabling the overlay, right click on Skyrim VR in your game library and click **Properties** > **Language** > **Select English**.

#### Change Steam's Updating Behavior
If for some reason Bethesda decide to release an update for Skyrim VR, everything will probably break. Well, not *everything* but something will definitely break until mods can be updated to suit. To stop this from happening, you need to tell Steam that you only want to update when you tell it to. You can do this by right clicking on Skyrim VR in your game library and clicking **Properties** > **Updates** > **Change Automatic Updates to "Only update this game when I launch it"**. Whilst you're in here, it's also recommended to disable Steam Cloud too.

#### Clean current Skyrim VR installation
If you have not yet installed Skyrim VR, you can skip this part.

1. Right click on Skyrim VR in your game library and click **Properties** > **Local Files** > **Browse**. 
2. Uninstall the game via Steam - right click on Skyrim VR in your game library and click **Manage** > **Uninstall**.
3. Check the explorer window for any left over files - if there are any, delete them.
4. Open Windows start menu/search and type in `%LOCALAPPDATA%`.
5. Delete the Skyrim VR folder.
6. Head to `Documents\My Games` and delete the Skyrim VR folder.

#### Install Skyrim VR
Once you've done the steps above, you can now set Steam to download Skyrim VR again but ***do not*** install Skyrim VR to a protected folder, such as `Desktop`, `Downloads` or `Program Files` of any kind. It's best to create a new, dedicated folder for it using the Steam Library function somewhere on the root of your drive such as `C:\SteamLibrary`. A lot of people have a dedicated secondary drive for their games, keeping the OS install separate; using this secondary drive will also work.

#### Start Skyrim VR
That's right - start the game. Let the game launcher do its initial system checks and graphics settings and then start the game. Once you've gotten to the main menu you can close the game again.

### Wabbajack
Installing the list is straight forward, Wabbajack will do most of the heavy lifting for you - you only have to tell it where to put stuff. Grab the `Tahrovin.wabbajack` file from [Releases](https://github.com/iAmMe27/Tahrovin/releases). Double-click it and Wabbajack should open. Wabbajack will have 2 things for you to do - fill in the installation location and the download location. 

Set the installation location to a folder on the root of a drive, something like `C:\Tahrovin`. Do not install it to one of the protected folders as mentioned earlier. The download location will have likely been filled in for you too - ensure it matches the directory you set for the installation location. 

Before you hit **GO**, a quick tip:
*To get the best performance with Wabbajack, it is recommended that you have the install folder for Wabbajack, the modlist folder and the downloads folder on an SSD, ideally the same SSD.* After the installation is complete, you can move the downloads folder to a storage HDD or other storage medium to save space on your game installation drive. It's not recommended to allow your drive to exceed 90% of its storage space used - Windows Explorer will show a red bar under your drive if you do go over 90% so you need to be sure that you have enough space on your installation drive so that you won't exceed this 90% storage level.

Once you have everything set in Wabbajack, hit **GO** and let it do its thing. It might take a while as there is a fair bit to download and the speed of this will depend on your internet performance as well as your CPU in the later stages for hashing and unpacking the downloads.

#### Troubleshooting
If you're having issues with installation, check the [troubleshooting page](Troubleshooting.md). 

## Post-Installation
Almost there but we're not out of the woods yet! After Wabbajack has given you the installation successful screen, you're free to close it. Navigate to the Tahrovin installation folder and run MO2 by double-clicking `ModOrganizer.exe`.

***DO NOT, UNDER ANY CIRCUMSTANCES, RUN LOOT. The load order is exactly as intended out of the box and you do not need to change it.***

### ENB Selection
For instructions on choosing your ENB, head to the [ENB Selection page](ENB%20Selection.md). **NOTE:** if you don't follow these steps, your game will launch with no ENB enabled.