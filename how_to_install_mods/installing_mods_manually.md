---
title: How to Manually Install Mods
description: ""
---
1. Open the file ``Steamapps/common/Deadlock/game/citadel/gameinfo.gi`` with a text editor 
2. Locate the segment ``SearchPaths`` In most text ediors the keybind to search for text in a file is Ctrl+F
3. Add ``Game citadel/addons`` beneath ``Game_language``
Ideally it should look something like this
```
SearchPaths
        {  
            Game_Language       citadel_*LANGUAGE*
            Game                citadel/addons
            Mod                 citadel
            Write               citadel          
            Game                citadel
            Mod                 core
            Write               core
            Game                core        
        }
```
4. Then create the folder ``citadel/addons`` so the directory looks like ``Steamapps/common/Deadlock/game/citadel/addons/``
5. Download a mod. This can typically be done from a site such as [Gamebanana](https://gamebanana.com/games/20948). For demonstration purposes I will be linking [Trans Flag on Ivy's Right Shackle and Leaf](https://gamebanana.com/mods/626730).
6. Unzip the mod, and place the .vpk extracted into the previously created ``citadel/addons``
7. If the file doesn't follow the naming scheme of ``pak01_dir.vpk`` (it can be any number 01-99) it will not work and will need to be renamed to follow that format.  

It bears mentioning that mods will be loaded starting at 01. So if you have two skin mods, both changing yamato, the one with the lower number will be applied first. This is why QOLLock asks you to name it ``pak01_dir.vpk``, so as to prevent potential conflicts.
