---
title: How to Install Mods Using a Mod Manager
description: ""
---
First you need to download a mod manager.
- [Simple Deadlock Mod Manager](https://github.com/Gabri3445/simple-deadlock-mod-manager/releases) Very simple and lightweight mod manager. Avalible in the [AUR](https://aur.archlinux.org/packages/simple-deadlock-mod-manager). As far as I am aware no generative AI was used to create it.
- [Grimoire](https://github.com/Slush97/grimoire/releases/latest) Has a nice ui, has a very nice means of selecting a character's skins, refers to them as a locker. Generative AI was used in the creation of it.
- [Deadlock Mod Manager](https://github.com/Stormix/deadlock-modmanager/releases/latest) Most popular community mod manager. Every time I launch it it makes every line of gameinfo.gi end with ``^M`` which pisses me off. Generative AI is cited in the cost of upkeep but I do not know if it was used.

You may then open the mod manager, select a mod to download, and then, enable it. Next time you launch the game mods should be applied. If they aren't applied consider checking if ``citadel/addons`` is listed in the searchpaths of the file Steamapps/common/Deadlock/game/citadel/gameinfo.gi
