# ![logo](https://raw.githubusercontent.com/azerothcore/azerothcore.github.io/master/images/logo-github.png) AzerothCore

## mod-guildhouse

![Latest Release](https://img.shields.io/github/v/release/araxiaonline/mod-guildhouse?label=current%20version)
![GitHub Release Date](https://img.shields.io/github/release-date/araxiaonline/mod-guildhouse)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/araxiaonline/mod-guildhouse/build-release.yml?branch=araxia-main&event=push&label=build%20status)

<p align="left">
  <img src="https://github.com/araxiaonline/docs/blob/main/docs/media/logo-sm.png?raw=true" alt="Araxia Online" width="70" style="vertical-align: middle;"/>
  <span style="font-size: 20px; vertical-align: middle;">Player Tested By Araxia Online</span>
</p>


## Description

This is a phased guild house system for AzerothCore, it allows players from the same guild to visit their guild house.

All guilds will get their own phasing system and then the guild master can purchase NPC creatures and other stuff to complete the Guild House.

### Purchasables

- Class Trainers (all available in Wrath)
- Primary Profession Trainers (all available in Wrath)
- Secondary Profession Trainers (all available in Wrath)
- Vendors: Reagents Vendor, Food & Drink, Trade Goods, Ammo & Repair Vendor, and Poisons Vendor
- Portals to Neutral, Horde and Alliance cities
- Spirit Healer
- Guild Bank and Personal Bank access
- Auctioneer/Neutral Auctioneer
- Stable Master

## How to use ingame

1) After installation, as GM you will need to: `.npc add 500030` -> somewhere public and accessible by other players.
2) Players can purchase a guild house from the added NPC, then either teleport to the guildhouse via the NPC or chat: `.guildhouse tele` or `.gh tele`
3) Each new Guild House starts with a portal to either Orgrimmar or Stormwind, based on Team (ALLIANCE / HORDE), and the Guild House Assistant.
4) Speak with the Guild House Assistant to begin purchasing additions to your Guild House!
5) Players in guild with proper rank will be able to spawn the Assistant with chat commands `.guildhouse butler` or `.gh butler`

## Installation

```
1) Place the module under the `modules` directory of your AzerothCore source.
2) Re-run cmake and launch a clean build of AzerothCore.
```

## Edit module configuration (optional)

If you need to change the module configuration, go to your server configuration folder (where your `worldserver` or `worldserver.exe` is), copy `mod_guildhouse.conf.dist` to `mod_guildhouse.conf` and edit that new file.

## Credits

- [Talamortis](https://github.com/talamortis) (Original author of the module)
- [Rochet2](https://github.com/Rochet2/): Thanks for the help with the phasing situation & General support
- [rbedfordpro](https://github.com/rbedfordpro) & [WiZZy](https://github.com/wizzymore)
- [Nelnamara - Porkserver](https://github.com/Porkserver) & [SoulSeekkor](https://github.com/SoulSeekkor) 2022 rework, crash fixes and new additions
- [Bogir](https://github.com/Bogir) For being amazing and forever helpful

AzerothCore: [repository](https://github.com/azerothcore) - [website](http://azerothcore.org/) - [discord chat community](https://discord.gg/64FH6Y8)
