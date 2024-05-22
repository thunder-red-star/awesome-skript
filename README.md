# Awesome Skript [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of skript related things to make your Minecraft server awesome!

## Contents

- [Addons](#addons)
    - [General](#general)
    - [Databases and Storage](#databases-and-storage)
    - [Proxy Addons](#proxy-addons)
    - [Extend the Game](#extend-the-game)
    - [Display and Special Effects](#display-and-special-effects)
    - [Packet Manipulation](#packet-manipulation)
    - [Plugin Integrations](#plugin-integrations)
    - [External Platform Integrations](#external-platform-integrations)
    - [Advanced](#advanced)
- [Scripts](#scripts)
    - [Soon™️](#soon)
- [Resources](#resources)
    - [Documentation](#documentation)
    - [Community](#community)

## Addons

*Addons are plugins that extend the functionality of Skript and provide other useful functionality to your server. They might either hook into existing plugins (or are included within said plugins) or provide features that are not possible with Skript alone!*

### General
- [SkBee](https://github.com/ShaneBeee/SkBee) (by ShaneBeee) - A Skript addon that adds additional useful elements to Skript, like Scoreboards, Recipes, Bounds, and WorldCreators.
- [Skellett](https://github.com/TheLimeGlass/Skellett) (by TheLimeGlass) - "The most popular Skript addon", appears to provide hooks into both proxies and some popular plugins.
- [MundoSK](https://github.com/MundoSK/MundoSK) (by Tlatoani) - Another catch-all addon that provides a mix of both useful and niche features. 
- [SkQuery](https://github.com/SkQuery/SkQuery) (by LimeGlass) - Yet another catch-all addon that provides some useful features... you get the idea.
- [skRayFall](https://github.com/eyesniper2/skRayFall) (by eyesniper2) - Yet another catch-all addon, this time it hooks into various commonly-used plugins like Citizens and Votifier.
- [TuSKe](https://github.com/Tuke-Nuke/TuSKe) (by Tuke-Nuke) - Even more integrations with plugins (ProtocolSupport / ViaVersion, Marriage, etc).
- [SkEssentials](https://github.com/Tandhjulet/SkEssentials) (by Tandhjulet) - Hooks with LuckPerms, Essentials, and provides a few other syntaxes.
- [Skuishy](https://github.com/aabssmc/Skuishy) (by aabss) - DecentHolograms and Vulcan integrations, TickManager stuff, and lots of other random stuff.

### Databases and Storage
- [MongoSK](https://github.com/Romitou/MongoSK) (by Romitou) - An addon that allows you to interact with MongoDB databases from Skript.
- [skJSON](https://github.com/cooffeeRequired/skJson) (by cooffeeRequired) - Work with JSON objects and files in Skript, also provides methods to fetch data from websites
- [skript-yaml](https://github.com/Sashie/skript-yaml) (by Sashie) - Load and parse YAML files in Skript.
- [skript-db](https://github.com/btk5h/skript-db) (by btk5h) - Manipulate SQL databases (MySQL, SQLite, etc.) from Skript.
- [skUtilities](https://github.com/tim740/skUtilities) (by tim740) - Addon that adds lots of syntax related to file parsing, conversion between different native types, and more.
- [skent](https://github.com/Olyno/skent) (by Olyno) - More file management.

### Proxy Addons
> [!WARNING]  
> All of the below addons haven't been actively maintained. Use at your own risk, they might not work with more recent versions of Minecraft.
- [Skungee](https://github.com/Skungee/Skungee) (by TheLimeGlass) - Interact with BungeeCord's API and features from Skript.
- [BungeeSK](https://github.com/ZorgBtw/BungeeSK) (by ZorgBtw) - Same idea as Skungee.
- [skScraft](https://github.com/scraft-official/skScraft/) (by scraft-official) - Yet another BungeeCord addon for Skript.
- [ZulfBungee](https://github.com/Zulfen/ZulfBungee) (by Zulfen) - Proxy plugin for both BungeeCord and Velocity. Seems to have a more recent release than other plugins in the category.

### Extend the Game
- [skript-advancements](https://github.com/hotpocket184/skript-advancements/) (by hotpocket184) - Create custom advancements in Skript, do things when players make progress or complete them.
- [skript-placeholders](https://github.com/APickledWalrus/skript-placeholders) (by APickledWalrus) - Create custom placeholders that can be retrieved by other plugins through PlaceholderAPI, also get placeholders from other plugins.
- [skript-gui](https://github.com/APickledWalrus/skript-gui) (by APickledWalrus) - A better way to create "custom" GUIs without the hassle of cancelling inventory clicks, etc.
- [SkCheez](https://github.com/cheeezburga/SkCheez) (by cheeezburga) - Attribute Modifiers, set list of blocks placable in adventure mode.
- [Kosmos](https://github.com/TlatoaniHJ/Kosmos) (by Tlatoani) - An addon that allows you to manage your worlds, maybe even replace Multiverse-Core!

### Display and Special Effects
- [skDragon](https://www.spigotmc.org/resources/skript-addon-skdragon-free-emotes-particles-great-eula-perks.24173/) (by Sashie) - Draw complex particle-based shapes and effects with Skript. Outdated, use skript-particle instead.
- [skript-particle](https://github.com/sovdeeth/skript-particle) (by sovdeeth) - Draw complex particle-based shapes and effects with Skript.
- [SkImage](https://github.com/ItsTheSky/SkImage) (by ItsTheSky) - Really basic image manipulation in Skript, for god knows what reason.
- [Tablisknu](https://github.com/TlatoaniHJ/Tablisknu) (by Tlatoani) - Create custom tablists, layouts, nametags, and more.

### Packet Manipulation
- [PoaSK](https://github.com/Ekpoa/PoaSkRewritev2) (by Ekpoa) - Basically allows lots of packet manipulation and fun stuff involving client-sided things. Paper only.
- [ThatPacketAddon](https://github.com/TlatoaniHJ/ThatPacketAddon) (by Tlatoani) - Low-level packet manipulation for Skript. Doesn't seem to get updates, use skript-packet instead.
- [skript-packet](https://github.com/Anarchick/skript-packet) (by Anarchick) - Another low-level packet manipulation addon for Skript.

### Plugin Integrations
- [Diskuise](https://github.com/UnderscoreTud/diskuise) (by UnderscoreTud) - Set and manage LibsDisguises disguises from Skript.
- [Fawesk](https://github.com/TheLimeGlass/Fawesk) (by TheLimeGlass) - Interact with FAWE (FastAsyncWorldEdit) from Skript.
- [FunkySk](https://github.com/TheLimeGlass/FunkySk) (by TheLimeGlass) - Interact with the NoteBlockAPI from Skript. Play note block songs and stuff.
- [Graphisk](https://github.com/TheLimeGlass/Graphisk) (by TheLimeGlass) - Manage HolographicDisplays and DecentHolograms with your Skripts.
- [LiteBansSk](https://forums.skunity.com/resources/litebanssk.391/) (by PugaBear) - If you wanted to `ban player with reason "you suck"` instead of `execute console command "/ban player you suck"`, this is for you.
- [NoteSK](https://github.com/byPixelTV/NoteSK) (by byPixelTV) - Play NoteBlockAPI songs.
- [Parties](https://github.com/AlessioDP/Parties) (by AlessioDP) - A full-fledged teams plugin with integrated Skript syntax.
- [Plosk](https://github.com/ReportCardsMC/Plosk) (by ReportCardsMC) - PlotSquared management in Skript.
- [skGlow](https://github.com/MinecraftMan1013number2/skGlow) (by MinecraftMan1013number2) - Hook into and control eGlow from Skript.
- [Skript-Citizens](https://github.com/nylhus/skript-citizens) (by nylhus) - Hooks into and provides syntax for Citizens.
- [skript-itemsadder](https://github.com/Asleeepp/skript-itemsadder) (by Asleeepp) - Hook into the ItemsAdder plugin to handle ItemsAdder-related features like custom inventories and items.
- [skript-oraxen](https://github.com/Asleeepp/skript-oraxen) (by Asleeepp) - Hook into the Oraxen plugin, same idea as skript-itemsadder.
- [skript-towny](https://github.com/TheLimeGlass/skript-towny) (by TheLimeGlass) - Hook into Towny from Skript.

### External Platform Integrations
- [DiSky](https://github.com/DiSkyOrg/DiSky) (by SkyCraft78) - A Skript addon that allows you to control a bot with Skript with nearly the full range of API features from Discord.
- [LabySK](https://github.com/pqtriick/LabySK) (by pqtriick) - Interact with the LabyMod Server API and control certain aspects about the client from Skript.
- [Linky](https://github.com/linkymc/Plugin) (by UwUAroze and astridlol) - Discord-to-Minecraft linking, abstracted.
- [MCQQBot](https://gitee.com/msg_dw/McQQBot-Skript) (by msg_dw) - Control a QQ bot from Skript.
- [SkEmail](https://github.com/Olyno/SkEmail/) (by Olyno) - Send emails to your players with Skript.
- [skCord](https://github.com/Fedox-die-Ente/skCord) (by Fedox-die-Ente) - Control your Discord bot from Skript. Simpler than DiSky to a certain extent.
- [Skelegram](https://github.com/DereWah/Skelegram) (by DereWah) - Create a fully functional Telegram bot with Skript.
- [Skript-GPT](https://github.com/DereWah/Skript-GPT) (by DereWah) - Implement GenAI in Skript?!
- [SkriptWebAPI](https://github.com/faketunaPrivateCamp/SkriptWebAPI) (by faketunaPrivateCamp) - Send HTTP requests and parse their results.

### Advanced
- [skript-reflect](https://github.com/SkriptLang/skript-reflect) (by TPGamesNL) - A Skript addon that allows you to interact with Java objects and classes, as well as create custom syntax for Skript.
- [Hippo](https://github.com/Pesekjak/Hippo) (by Pesekjak) - An addon that compiles Java classes running Skript code during runtime. Requires skript-reflect.
- [Skester](https://github.com/Olyno/skester/) (by Olyno) - If you ever wanted to deploy "production-ready" Skript code, well, boy do you need this.
- [Biosphere2](https://github.com/bi0qaw/biosphere2) (by bi0qaw) - Location and vector manipulations.

## Scripts
<!-- todo: find motivation to even make this section-->
*Scripts are collections of Skript code that provide a specific feature or set of features. They are usually standalone and can be easily added to your server. Make sure to check if you have required addons or plugins installed before using them!*

### Soon™️

- [List item](http://example.com)
- [List item](http://example.com)

## Resources

*Websites, forums, and other resources that can help you learn Skript or find help with your Skript code.*

### Documentation
- [Skript Docs](https://docs.skriptlang.org/) - The official documentation for Skript, most detailed but only covers the core syntax.
- [SkriptHub](https://skripthub.net/) - A website that provides detailed documentation on Skript and addon-related syntax, as well as tutorials 
- [SkUnity Docs](https://docs.skunity.com/syntax/) - For use where SkriptHub lacks addons, another documentation site with syntax and examples.

### Community
- [SkUnity Forums](https://forums.skunity.com/) - An online forum for Skript users to ask questions, share resources, and discuss Skript-related topics.
- [SkUnity Discord](https://discord.gg/skript) - Official Discord for SkUnity Forums. Another place to get help with Skript, maybe even get spoonfed!

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
