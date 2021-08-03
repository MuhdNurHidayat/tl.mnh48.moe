---
title: Divisional Translations
description: Details on divisional translation works.
lang: en
layout: article
needbtt: true
---

- [Cities: Skylines](#cities-skylines)
  - [Malay Translation Mod for Base Game](#malay-translation-mod-for-base-game)
  - [MacSergey's Mods](#macsergeys-mods)
    - [MacSergey's Mods Common](#macsergeys-mods-common)
    - [Node Controller Renewal](#node-controller-renewal)
  - [Quistar's Mods](#quistars-mods)
    - [Unlimited Trees: Reboot](#unlimited-trees-reboot)
- [Minetest](#minetest)
  - [Minetest (engine)](#minetest-engine)
  - [Mod: Hopper](#mod-hopper)
  - [Mod: Jukebox](#mod-jukebox)
  - [Mod: Lapis Lazuli](#mod-lapis-lazuli)
  - [Mod: Storage Drawers](#mod-storage-drawers)
  - [Mod: Minetest Game Internationalization](#mod-minetest-game-internationalization)
  - [App: Minetest Mods for Android](#app-minetest-mods-for-android)
- [Project SEKAI](#project-sekai)
  - [Sekai Viewer](#sekai-viewer)
    - [Project Sekai Game Data](#project-sekai-game-data)
    - [Sekai Viewer Interface](#sekai-viewer-interface)
  - [Project Sekai Melayu](#project-sekai-melayu)
    - [Twitter: Project Sekai Melayu ملايو](#twitter-project-sekai-melayu-ملايو)
{: .toc id="toc"}

[← Back to Main Page](/en)



&nbsp;



This page lists current translation status for projects that are grouped together based on certain criteria because it has gotten too big or because the translation will require many works and the list would be too long to be included as a section in the other categories. Each division has a mix of continuous translation and one-time translation, since some part of the division is available on certain translation management platform while the other isn't.

Go back to the page earlier for links to view current status for other types of translations.

&nbsp;



## Cities: Skylines

![Cities: Skylines <](https://img.mnh48.moe/tl/citiesskylines/citiesskylines-128.png "Cities: Skylines")

Cities: Skylines is a 2015 city-building game developed by Colossal Order and published by Paradox Interactive. The game is a single-player open-ended city-building simulation. Players engage in urban planning by controlling zoning, road placement, taxation, public services, and public transportation of an area. The game is proprietary.

Officially available for PC, PS4, Xbox One and Nintendo Switch. The PC version is available for Windows, Linux, and macOS, and purchasable through Steam and Epic Games Store. There is also Windows 10 edition purchasable through Microsoft Store. The game is not available on Android or iOS officially, but some people managed to run it under Android using the Linux version with some tweaks. The Steam version integrates well with user-created mods and it is the recommended platform to play this game.

The game itself does not accept translation, however I started making a locale mod to add Rumi Malay translation from 18 July 2021, 11:12 pm. I also added Rumi Malay translation to some of other mods in parallel to making the Rumi Malay locale mod. There is no plan for Jawi Malay because the game itself does not support any Arabic text processing. Translation is still ongoing.

[Official Website](https://www.citiesskylines.com?utm_source=tl.mnh48.moe&utm_medium=referral) + [PS4 US](https://store.playstation.com/product/UP4139-CUSA06548_00-CITIESPS4GAME002?utm_source=tl.mnh48.moe&utm_medium=referral) + [PS4 EU](https://store.playstation.com/product/EP4139-CUSA06407_00-CITIESPS4GAME001?utm_source=tl.mnh48.moe&utm_medium=referral) + [XBOX ONE](https://www.microsoft.com/p/cities-skylines-xbox-one-edition/c4gh8n6zxg5l?utm_source=tl.mnh48.moe&utm_medium=referral) + [Nintendo Switch](https://www.nintendo.com/games/detail/cities-skylines-nintendo-switch-edition/?utm_source=tl.mnh48.moe&utm_medium=referral) + [Windows 10 Edition](https://www.microsoft.com/en-my/p/cities-skylines-windows-10-edition/9nwvc7xp3pfd?utm_source=tl.mnh48.moe&utm_medium=referral) + [Epic Games Store](https://www.epicgames.com/store/product/cities-skylines/home?utm_source=tl.mnh48.moe&utm_medium=referral) + [Steam Store](https://store.steampowered.com/app/255710/Cities_Skylines/?utm_source=tl.mnh48.moe&utm_medium=referral) + [Steam Workshop](https://steamcommunity.com/app/255710/workshop/?utm_source=tl.mnh48.moe&utm_medium=referral)

&nbsp;


### Malay Translation Mod for Base Game

The base game is not natively translatable, however someone by the name of [daniel.mantione](https://steamcommunity.com/profiles/76561198074517378?utm_source=tl.mnh48.moe&utm_medium=referral) who made the [Dutch language mod](https://steamcommunity.com/sharedfiles/filedetails/?id=517574710?utm_source=tl.mnh48.moe&utm_medium=referral) had made a [guide](https://steamcommunity.com/workshop/filedetails/discussion/517574710/365163686083172898/?utm_source=tl.mnh48.moe&utm_medium=referral) on Steam workshop including the tools he used to create locale file to support additional translation.

I had used the tools he created to generate translatable version of files, with some modification. Specifically, the Makefile is edited to include `-r:UnityEngine.dll` and the additional appropriate file `UnityEngine.dll` is copied from the game installation folder itself into the folder for build process, none of the actual game files are distributed with the mod.

[Mod page on Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2550720381?utm_source=tl.mnh48.moe&utm_medium=referral)

Current status:

- Rumi Malay: ![Rumi Malay translation status of Base Game Locale](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.mnh48.moe%2Fstatus%2Fmyown%3Fname%3Drumi-CitiesSkylines)
- Jawi Malay is not planned because the base game does not support Arabic text system, which is needed to support Jawi script.

&nbsp;


### MacSergey's Mods

MacSergey is a mod creator of Cities: Skylines from Russia. This section lists the mods he made that I had created Malay translations for.

[Steam Profile](https://steamcommunity.com/profiles/76561198063330220?utm_source=tl.mnh48.moe&utm_medium=referral) + [Released Mods](https://steamcommunity.com/profiles/76561198063330220/myworkshopfiles/?appid=255710&utm_source=tl.mnh48.moe&utm_medium=referral)

&nbsp;

#### MacSergey's Mods Common

This is the common locale files that are used across all MacSergey's mods, it contains common strings that are used across all of his mods for Cities: Skylines. The files are used by the different mods and they are not usable on their own.

[Repository (GitHub)](https://github.com/MacSergey/ModsCommon?utm_source=tl.mnh48.moe&utm_medium=referral) + [Translation (Crowdin)](https://crowdin.com/project/macsergey-mods-common?utm_source=tl.mnh48.moe&utm_medium=referral)

Current status:

- Rumi Malay: ![Rumi Malay translation status of MacSergey's Mods Common](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.mnh48.moe%2Fstatus%2Fcrowdin%3Fname%3Drumi-MacSergeyModsCommon)
- Jawi Malay is not planned because the base game does not support Arabic text system, which is needed to support Jawi script.

&nbsp;

#### Node Controller Renewal

![Node Controller Renewal <](https://img.mnh48.moe/tl/citiesskylines/nodecontrollerrenewal-64.png "Node Controller Renewal")

Node Controller Renewal by MacSergey is the renewed version of the [Node Controller](https://steamcommunity.com/sharedfiles/filedetails/?id=2085403475&utm_source=tl.mnh48.moe&utm_medium=referral) mod by [kian.zarrin](https://steamcommunity.com/profiles/76561198109315306/myworkshopfiles/?utm_source=tl.mnh48.moe&utm_medium=referral) with improved user interface and design. It allowed the editing of a node, such as changing the type of node, the slope direction, and much more. It also allow you to add crossing into existing road.

[Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2472062376&utm_source=tl.mnh48.moe&utm_medium=referral) + [Repository (GitHub)](https://github.com/MacSergey/NodeController30?utm_source=tl.mnh48.moe&utm_medium=referral) + [Translation (Crowdin)](https://crowdin.com/project/node-controller-renewal?utm_source=tl.mnh48.moe&utm_medium=referral)

Current status:

- Rumi Malay: ![Rumi Malay translation status of Node Controller Renewal](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.mnh48.moe%2Fstatus%2Fcrowdin%3Fname%3Drumi-NodeControllerRenewal)
- Jawi Malay is not planned because the base game does not support Arabic text system, which is needed to support Jawi script.

&nbsp;


### Quistar's Mods

Quistar is a mod creator of Cities: Skylines. This section lists the mods they made that I had created Malay translations for.

[Steam Profile](https://steamcommunity.com/profiles/76561198050938697?utm_source=tl.mnh48.moe&utm_medium=referral) + [Released Mods](https://steamcommunity.com/profiles/76561198050938697/myworkshopfiles/?appid=255710&utm_source=tl.mnh48.moe&utm_medium=referral)

&nbsp;

#### Unlimited Trees: Reboot

![Unlimited Trees: Reboot <](https://img.mnh48.moe/tl/citiesskylines/unlimitedtreesreboot-64.png "Unlimited Trees: Reboot")

Unlimited Trees: Reboot, also known as Tree Anarchy, by Quistar is a complete rewrite of both the original [Unlimited Trees](https://steamcommunity.com/sharedfiles/filedetails/?id=455403039&utm_source=tl.mnh48.moe&utm_medium=referral) mod by [knighthawkGP](https://steamcommunity.com/id/KnighthawkGP?utm_source=tl.mnh48.moe&utm_medium=referral) that uses [Detour library](https://github.com/sschoener/cities-skylines-detour?utm_source=tl.mnh48.moe&utm_medium=referral) by [Sebastian Schöner](https://github.com/sschoener?utm_source=tl.mnh48.moe&utm_medium=referral) and maintained by [BloodyPenguin](https://steamcommunity.com/id/bloody_penguin?utm_source=tl.mnh48.moe&utm_medium=referral) and hosted by [DRen72](https://steamcommunity.com/id/DRen72?utm_source=tl.mnh48.moe&utm_medium=referral) with some fixes by [thale5](https://steamcommunity.com/profiles/76561197993041956?utm_source=tl.mnh48.moe&utm_medium=referral) and was based on [Unlimiter](https://github.com/mabako/cities-skylines-unlimiter?utm_source=tl.mnh48.moe&utm_medium=referral) by [mabako](https://github.com/mabako?utm_source=tl.mnh48.moe&utm_medium=referral), and the patched [Unlimited Trees: Revisited](https://steamcommunity.com/sharedfiles/filedetails/?id=2378914031&utm_source=tl.mnh48.moe&utm_medium=referral) by [GMH](https://steamcommunity.com/id/gmhamidy?utm_source=tl.mnh48.moe&utm_medium=referral) that was maintained by [kjmci](https://steamcommunity.com/id/kjmci?utm_source=tl.mnh48.moe&utm_medium=referral). Tree Anarchy has taken out code bloats, fixed some bugs, and streamlined the serialization process. The concept of the framework is almost the same as the original mod, and this mod would not be coded this fast without the original Unlimited Trees mod.

[Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2527486462&utm_source=tl.mnh48.moe&utm_medium=referral) + [Repository (GitHub)](https://github.com/Quistar-LAB/TreeAnarchy?utm_source=tl.mnh48.moe&utm_medium=referral) + [Translation (Crowdin)](https://crowdin.com/project/my-mods?utm_source=tl.mnh48.moe&utm_medium=referral)

Current status:

- Rumi Malay: ![Rumi Malay translation status of Unlimited Trees: Reboot](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.mnh48.moe%2Fstatus%2Fcrowdin%3Fname%3Drumi-MyMods)
- Jawi Malay is not planned because the base game does not support Arabic text system, which is needed to support Jawi script.

&nbsp;



## Minetest

![Minetest <](https://img.mnh48.moe/tl/minetest/minetest-128.png "Minetest")

Minetest is an open-source voxel game engine and game developed by a team of volunteers with contributions from its own community. The engine and game was first released by Perttu Ahola (celeron55) on 10 October 2010, its source code was then made public on 26 November 2010 and the community expanded from there. Minetest was originally an attempt to recreate the gameplay of Minecraft using C++ because Java-based Minecraft could not run on celeron55's computer, however it has since became an independent project not aiming to be associated with Minecraft anymore, although many players still using it as an alternative of Minecraft.

Officially available for Windows, Linux, macOS and Android, all sharing the same backend. For example, players on Android can play with players on Windows, and people can host Minetest servers on Raspberry Pi like what some schools in certain country did to teach mathematics due to its catchy and children-friendly nature. Unofficially available on iOS by third-party maintainers although it is technically illegal since Minetest's license (LGPLv2) contradicts with Apple's App Store terms and services, and vice versa.

The works for Rumi Malay translation for Minetest has started on 3 February 2017 and has been completed after a few months, and has since been kept up to date on Weblate side. The works for Jawi Malay translation is paused because of some issue.

[Website](https://www.minetest.net?utm_source=tl.mnh48.moe&utm_medium=referral) + [Repository (GitHub)](https://www.github.com/minetest?utm_source=tl.mnh48.moe&utm_medium=referral) + [Translation Base (Hosted Weblate)](https://hosted.weblate.org/projects/minetest?utm_source=tl.mnh48.moe&utm_medium=referral)

&nbsp;


### Minetest (engine)

![Minetest Engine <](https://img.mnh48.moe/tl/minetest/minetest-64.png "Minetest Engine")

The core of Minetest is the engine of the same name, it is the base for any Minetest games out there and lays out the fundamental functions needed by the games. It is also the layer that connect the gap of communication between the Lua-based game and mods with the C++-based engine.

[Website](https://www.minetest.net?utm_source=tl.mnh48.moe&utm_medium=referral) + [Repository (GitHub)](https://www.github.com/minetest/minetest?utm_source=tl.mnh48.moe&utm_medium=referral) + [Translation (Hosted Weblate)](https://hosted.weblate.org/projects/minetest/minetest?utm_source=tl.mnh48.moe&utm_medium=referral)

Current status:

- Rumi Malay ![Rumi Malay translation status of Minetest engine](https://hosted.weblate.org/widgets/minetest/ms/minetest/svg-badge.svg)
- Jawi Malay ![Jawi Malay translation status of Minetest engine](https://hosted.weblate.org/widgets/minetest/ms_Arab/minetest/svg-badge.svg)

Translation to Jawi Malay is put on hold because the support of complex text rendering seemed to be broken. This has been reported on the issue tracker for other languages, such as [this](https://github.com/minetest/minetest/issues/4637?utm_source=tl.mnh48.moe&utm_medium=referral) for Hebrew and [this](https://github.com/minetest/minetest/issues/11455?utm_source=tl.mnh48.moe&utm_medium=referral) for Arabic.

&nbsp;


### Mod: Hopper

![Mod: Hopper <](https://img.mnh48.moe/tl/minetest/mod-hopper-64.png "Mod: Hopper")

Hoppers are nodes that can transfer items to and from the inventories of adjacent nodes. This mod is based on jordan4ibanez's original hoppers mod, optimized by TenPlus1 and FaceDeer, with chutes and sorters by FaceDeer. This mod is maintained in the minetest-mods repository.

[ContentDB Page](https://content.minetest.net/packages/FaceDeer/hopper/?utm_source=tl.mnh48.moe&utm_medium=referral) + [Repository (GitHub)](https://github.com/minetest-mods/hopper?utm_source=tl.mnh48.moe&utm_medium=referral) + [Forum Thread](https://forum.minetest.net/viewtopic.php?t=20058&utm_source=tl.mnh48.moe&utm_medium=referral) + [Translation (Hosted Weblate)](https://hosted.weblate.org/projects/minetest/mod-hopper/?utm_source=tl.mnh48.moe&utm_medium=referral)

Current status:

- Rumi Malay ![Rumi Malay translation status of Mod: Hopper](https://hosted.weblate.org/widgets/minetest/ms/mod-hopper/svg-badge.svg)
- Jawi Malay ![Jawi Malay translation status of Mod: Hopper](https://hosted.weblate.org/widgets/minetest/ms_Arab/mod-hopper/svg-badge.svg)

&nbsp;


### Mod: Jukebox

![Mod: Jukebox <](https://img.mnh48.moe/tl/minetest/mod-jukebox-64.png "Mod: Jukebox")

Jukebox adds a block that can play music in an area when a music disc is inserted. The mod can be configured to have up to 90 songs as it have 9 discs and each disc can have 10 songs. By default, only 6 songs on 1 disc is provided in the mod. This mod is maintained in the minetest-mods repository.

Not available on ContentDB + [Repository (GitHub)](https://github.com/minetest-mods/jukebox?utm_source=tl.mnh48.moe&utm_medium=referral) + [Forum Thread](https://forum.minetest.net/viewtopic.php?t=13505&utm_source=tl.mnh48.moe&utm_medium=referral) + [Translation (Hosted Weblate)](https://hosted.weblate.org/projects/minetest/mod-jukebox/?utm_source=tl.mnh48.moe&utm_medium=referral)

Current status:

- Rumi Malay ![Rumi Malay translation status of Mod: Jukebox](https://hosted.weblate.org/widgets/minetest/ms/mod-jukebox/svg-badge.svg)
- Jawi Malay ![Jawi Malay translation status of Mod: Jukebox](https://hosted.weblate.org/widgets/minetest/ms_Arab/mod-jukebox/svg-badge.svg)

&nbsp;


### Mod: Lapis Lazuli

![Mod: Lapis Lazuli <](https://img.mnh48.moe/tl/minetest/mod-lapis-64.png "Mod: Lapis Lazuli")

This mod adds lapis lazuli ore, items and blocks. The only use of it is to craft dye with it or build something blue like a swimming pool. This mod is maintained in the minetest-mods repository.

Not available on ContentDB + [Repository (GitHub)](https://github.com/minetest-mods/lapis?utm_source=tl.mnh48.moe&utm_medium=referral) + [Forum Thread](https://forum.minetest.net/viewtopic.php?t=11287&utm_source=tl.mnh48.moe&utm_medium=referral) + [Translation (Hosted Weblate)](https://hosted.weblate.org/projects/minetest/mod-lapis-lazuli/?utm_source=tl.mnh48.moe&utm_medium=referral)

Current status:

- Rumi Malay ![Rumi Malay translation status of Mod: Lapis Lazuli](https://hosted.weblate.org/widgets/minetest/ms/mod-lapis-lazuli/svg-badge.svg)
- Jawi Malay ![Jawi Malay translation status of Mod: Lapis Lazuli](https://hosted.weblate.org/widgets/minetest/ms_Arab/mod-lapis-lazuli/svg-badge.svg)

&nbsp;


### Mod: Storage Drawers

![Mod: Storage Drawers <](https://img.mnh48.moe/tl/minetest/mod-drawers-64.png "Mod: Storage Drawers")

This mod adds simple item storages showing the item's inventory image in the front. By left- or right-clicking the image you can take or add stacks. If you also hold the shift-key only a single item will be removed/added. This mod is maintained in the minetest-mods repository.

[ContentDB Page](https://content.minetest.net/packages/LNJ/drawers/?utm_source=tl.mnh48.moe&utm_medium=referral) + [Repository (GitHub)](https://github.com/minetest-mods/drawers?utm_source=tl.mnh48.moe&utm_medium=referral) + [Forum Thread](https://forum.minetest.net/viewtopic.php?t=17134&utm_source=tl.mnh48.moe&utm_medium=referral) + [Translation (Hosted Weblate)](https://hosted.weblate.org/projects/minetest/mod-storage-drawers/?utm_source=tl.mnh48.moe&utm_medium=referral)

Current status:

- Rumi Malay ![Rumi Malay translation status of Mod: Storage Drawers](https://hosted.weblate.org/widgets/minetest/ms/mod-storage-drawers/svg-badge.svg)
- Jawi Malay ![Jawi Malay translation status of Mod: Storage Drawers](https://hosted.weblate.org/widgets/minetest/ms_Arab/mod-storage-drawers/svg-badge.svg)

&nbsp;


### Mod: Minetest Game Internationalization

![Mod: Minetest Game Internationalization <](https://img.mnh48.moe/tl/minetest/minetest-64.png "Mod: Minetest Game Internationalization")

Minetest Game Internationalization, with technical name `mtg_i18n`, was a mod that added translation support to Minetest Game, the default game shipped with Minetest engine. Minetest engine does not originally support native translation of games and mods, and only had support for engine's own translation. However, Minetest has since added translation support for games and mods on the engine side, followed by the game side adding the function needed for translation, and it has since made this mod obsoleted. This mod is maintained in the minetest-mods repository.

Not available on ContentDB + [Repository (GitHub)](https://www.github.com/minetest-mods/mtg_i18n?utm_source=tl.mnh48.moe&utm_medium=referral) + [Forum Thread](https://forum.minetest.net/viewtopic.php?t=17388&utm_source=tl.mnh48.moe&utm_medium=referral) + [Translation (Hosted Weblate)](https://hosted.weblate.org/projects/minetest/mtg_i18n?utm_source=tl.mnh48.moe&utm_medium=referral)

Current status:

- Rumi Malay ![Rumi Malay translation status of Mod: Minetest Game Internationalization](https://hosted.weblate.org/widgets/minetest/ms/mtg_i18n/svg-badge.svg)
- Jawi Malay ![Jawi Malay translation status of Mod: Minetest Game Internationalization](https://hosted.weblate.org/widgets/minetest/ms_Arab/mtg_i18n/svg-badge.svg)

There is a possibility that the maintainer is abandoning the mod, the translation directory has been locked and no more translations could be added or modified.

&nbsp;


### App: Minetest Mods for Android

![App: Minetest Mods for Android <](https://img.mnh48.moe/tl/minetest/app-mtmods4android-64.png "App: Minetest Mods for Android")

Minetest Mods for Android, also known as Minetest Mod Manager and its internal name `com.rubenwardy.minetestmodmanager` is an Android app developed by rubenwardy as a way to download Minetest mods on Android as there was no way to do so automatically back then. The app has since be made obsolete by the release of Minetest 5.0 as it now contain in-game explorer to search and install mods, games and texture packs. This app is maintained by rubenwardy.

[Website](https://rubenwardy.com/mtmods4android?utm_source=tl.mnh48.moe&utm_medium=referral) + [Play Store](https://play.google.com/store/apps/details?id=com.rubenwardy.minetestmodmanager&utm_source=tl.mnh48.moe&utm_medium=referral) + [F-Droid](https://f-droid.org/packages/com.rubenwardy.minetestmodmanager?utm_source=tl.mnh48.moe&utm_medium=referral) + [Repository (GitHub)](https://www.github.com/rubenwardy/mtmods4android?utm_source=tl.mnh48.moe&utm_medium=referral) + [Translation (Hosted Weblate)](https://hosted.weblate.org/projects/minetest/mtmods4android?utm_source=tl.mnh48.moe&utm_medium=referral)

Current status:

- Rumi Malay ![Rumi Malay translation status of App: Minetest Mods for Android](https://hosted.weblate.org/widgets/minetest/ms/mtmods4android/svg-badge.svg)
- Jawi Malay ![Jawi Malay translation status of App: Minetest Mods for Android](https://hosted.weblate.org/widgets/minetest/ms_Arab/mtmods4android/svg-badge.svg)

There is a possibility that the app owner is abandoning the app, the translation directory has been locked and no more translations could be added or modified.

&nbsp;



## Project SEKAI

![Project SEKAI <](https://img.mnh48.moe/tl/projectsekai/projectsekai-128.png "Project SEKAI")

Project SEKAI, or officially Project SEKAI COLORFUL STAGE! feat. Hatsune Miku (プロジェクトセカイ カラフルステージ！ feat. 初音ミク, *Purojekuto Sekai Karafuru Suteeji! feat. Hatsune Miku*), is a Japanese rhythm game released by SEGA. The game itself is only available in Japanese market of Google Play Store and Apple App Store as of now. You need Japanese account to install the game legally, or you can install from third party stores but the legality there is unknown.

[Website](https://pjsekai.sega.jp?utm_source=tl.mnh48.moe&utm_medium=referral) + [Twitter](https://twitter.com/pj_sekai?utm_source=tl.mnh48.moe&utm_medium=referral) + [YouTube](https://www.youtube.com/channel/UCdMGYXL38w6htx6Yf9YJa-w?utm_source=tl.mnh48.moe&utm_medium=referral) + [Anthology](https://pjsekai.sega.jp/anthology/index.html?utm_source=tl.mnh48.moe&utm_medium=referral) + [Guideline for Fan Contents](https://pjsekai.sega.jp/news/article/index.html?hash=4294aa774d50be788fcaed45092491c17f9e163d&utm_source=tl.mnh48.moe&utm_medium=referral) + [App Store](https://apps.apple.com/jp/app/id1489932710?utm_source=tl.mnh48.moe&utm_medium=referral) + [Google Play](https://play.google.com/store/apps/details?id=com.sega.pjsekai?utm_source=tl.mnh48.moe&utm_medium=referral)

&nbsp;


### Sekai Viewer

![Sekai Viewer <](https://img.mnh48.moe/tl/projectsekai/sekaiviewer-64.png "Sekai Viewer")

Sekai Viewer is the Web Database Viewer of Project Sekai, created by [DNARoma](https://github.com/dnaroma?utm_source=tl.mnh48.moe&utm_medium=referral). It aims to simplify the way people view the game data, and to be reference website by all Project SEKAI players. It also featured translations contributed by the community, so that people from all over the globe could use it to understand game content.

[Website](https://sekai.best/?utm_source=tl.mnh48.moe&utm_medium=referral) + [Repository (GitHub)](https://github.com/Sekai-World/sekai-viewer?utm_source=tl.mnh48.moe&utm_medium=referral) + [Patreon](https://www.patreon.com/SekaiViewer?utm_source=tl.mnh48.moe&utm_medium=referral) + [Twitter](https://www.twitter.com/SekaiViewer?utm_source=tl.mnh48.moe&utm_medium=referral) + [Discord](https://discord.gg/xcDBRMd?utm_source=tl.mnh48.moe&utm_medium=referral) + [Translation (Transifex)](https://www.transifex.com/dnaroma/?utm_source=tl.mnh48.moe&utm_medium=referral)

&nbsp;


#### Project Sekai Game Data

Translation of Project Sekai Game Data.

[Translation (Transifex)](https://www.transifex.com/dnaroma/project-sekai-i18n/?utm_source=tl.mnh48.moe&utm_medium=referral)

Current status:

- Rumi Malay: ![Rumi Malay translation status of Project Sekai Game Data](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.mnh48.moe%2Fstatus%2Ftransifex%3Fname%3Drumi-SekaiViewer)
- Jawi Malay is not decided yet.

&nbsp;

#### Sekai Viewer Interface

Translation of Sekai Viewer interface.

[Translation (Transifex)](https://www.transifex.com/dnaroma/sekai-viewer/?utm_source=tl.mnh48.moe&utm_medium=referral)

Current status:

- Rumi Malay: ![Rumi Malay translation status of Sekai Viewer Interface](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.mnh48.moe%2Fstatus%2Ftransifex%3Fname%3Drumi-SekaiViewer)
- Jawi Malay is not decided yet.

&nbsp;



### Project Sekai Melayu

![Project Sekai Melayu <](https://img.mnh48.moe/tl/projectsekai/pjsmly-64.png "Project Sekai Melayu")

Project Sekai Melayu, also known as PJsekai MLY, is the Malay fan translation project for media, information and tutorials related to Project SEKAI. The game itself is only available in Japanese as of now, and while there is a chance for it to be released in English at a later date, there's no hope for it to be released in Malay, so this fan translation project will be staying here.

The works of Malay translation in Project Sekai Melayu has started on 22 November 2020, 8:12PM and still ongoing as of writing.

[PJsekai MLY website](https://pjsekai.mnh48.moe?utm_source=tl.mnh48.moe&utm_medium=referral) + [PJsekai MLY Twitter](https://twitter.com/PJsekai_MLY?utm_source=tl.mnh48.moe&utm_medium=referral) + PJsekai MLY YouTube coming soon

&nbsp;

#### Twitter: Project Sekai Melayu ملايو

![Project Sekai Melayu ملايو <](https://img.mnh48.moe/tl/projectsekai/pjsmly-64.png "Project Sekai Melayu ملايو")

The Twitter account of Project Sekai Melayu, named as "Project Sekai Melayu ملايو" with the handle "@‌PJsekai_MLY", serves as the main way to relay information in Malay in both Rumi and Jawi scripts. This account translates the Japanese tweet from Project SEKAI's official account, named as "プロジェクトセカイ カラフルステージ！ feat. 初音ミク【プロセカ】" with the handle "@‌pj_sekai". Translation of tweet will be posted when I'm free. This account also translates a few other related contents as well as keeping people informed on other Malay translation activities on other platforms that are related to Project SEKAI.

I accept external help in managing the account, as long as you follow [these conditions](helpcondition). Contact me for screening to get access to the account.

[Twitter](https://twitter.com/PJsekai_MLY?utm_source=tl.mnh48.moe&utm_medium=referral)

&nbsp;

