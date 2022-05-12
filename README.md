# The_Planet_Crafter_Mods
BepInEx+Harmony plugin/patcher/mods for the Unity/Steam game The Planet Crafter

Steam: https://store.steampowered.com/app/1284190/The_Planet_Crafter/

## Version <a href='https://github.com/askar0/The_Planet_Crafter_Mods/releases'><img src='https://img.shields.io/github/v/release/askar0/The_Planet_Crafter_Mods' alt='Latest GitHub Release Version'/></a>

:arrow_down_small: Download files from the releases: https://github.com/askar0/The_Planet_Crafter_Mods/releases/latest

```
Note: 6th May 2022 - (Mods/Plugins Under Construction) - Only Sample files uploaded. 
          These will need major modifications to make a mod/plugin don't download/use yet.
     12th May 2022 - Readme.md Updated with proper formatting and extended information, 
          more info still to come as the mods/plugins progresses to new stages of development.
```

## Currently Intended Support for Game Versions: 0.4.008 Early Access / 0.4.009 Beta

:warning: I'll do my best to keep my mods up-to-date in case something drastic changes inside the main game.

:warning: I have not tested my mods with any of the developer/preview/demo releases. They might work just fine or suddenly break.

:warning: I cannot promise to fix my mods for these other versions as they can get quite out-of-sync with the public release.

**Note:** I am still in the process of creating the form and code for my mods/plugins and current cannot build a working release yet. Please be patient.

## Preparation

In order to use my or anyone else's mods at this time, you need to install BepInEx first. The wiki has a guide for this:

Planet Crafter Modding Wiki pages: https://planet-crafter.fandom.com/wiki/Modding#Using_Mods

Guide on dnSpy-based manual patches: https://steamcommunity.com/sharedfiles/filedetails/?id=2784319459

## Installation

When installing my mods, unzip the mod into the `BepInEx\Plugins` directory, including the folder inside the zip file.

You should end up having a directory structure like this:

```
`BepInEx\Plugins\BepInEx.Askar0.Minimap\Screenshot.png`
`BepInEx\Plugins\BepInEx.Askar0.Minimap\Readme.txt`
`BepInEx\Plugins\BepInEx.Askar0.Minimap\Changelog.txt`
`BepInEx\Plugins\BepInEx.Askar0.Minimap\Minimap-Core_v1-0\Askar0.Minimap.Core_v1-0.dll`
`BepInEx\Plugins\BepInEx.Askar0.Minimap\Minimap-UI_v1-0\Askar0.Minimap.UI_v1-0.dll`
`BepInEx\Plugins\BepInEx.Askar0.Minimap\Minimap-GUI_v1-0\Askar0.Minimap.GUI_v1-0.dll`
`BepInEx\Plugins\BepInEx.Askar0.Minimap\Minimap-Mod-Helper_v1-0\Askar0.Minimap.Mod-Helper_v1-0.dll`
`BepInEx\Plugins\BepInEx.Askar0.Minimap\Minimap-Mod-Helper_v1-0\mods\` #Any addition modding directories/files/images here.
```

Doing this helps avoid overwriting each others' files if they happen to be named the same as well as allows removing plugin files together 
by deleting the directory itself.


# Mods

## Minimap Mod Description

```
BepInEx.Askar0.Minimap
 - Core Library: The main code for the minimap plugin mod.
 - UI: Any user interfaces other then the main minimap display itself.
 - GUI: The displayed minimap and any attached icons/buttons/borders etc.
 - Mod-Helper: A modding library and instructions for altering the minimap itself. 
               New borders, additional commands/scripts, user interface modifications etc.
```

### Configuration

Any configuration files generated with the mod:
```
1. `BepInEx.Askar0.Minimap-Core_v1-0.cfg`
2. `BepInEx.Askar0.Minimap-UI_v1-0.cfg`
3. `BepInEx.Askar0.Minimap-GUI_v1-0.cfg`
4. `BepInEx.Askar0.Minimap-Mod-Helper_v1-0.cfg`
```

Basic settings that will be available in all cfg's for the plugin mod:

```
[General]

## Is this mod enabled?
# Setting type: Boolean
# Default value: true
Enabled = true

## Is Logging in this mod enabled?
# Setting type: Boolean
# Default value: true
Enabled = true

```


