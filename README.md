# Welcome to MergeBot!
For support and suggestions, join my Discord Hangout - https://notpaldea.net

## This sysBot offers all of the features you could ever want <3

### Shoutout to all the amazing devs of SysBot!  

[@kwsch](https://github.com/kwsch), [@Lusamine](https://github.com/Lusamine), [@Koi-3088](https://github.com/Koi-3088), [@easyworld](https://github.com/easyworld), [@santacrab2](https://github.com/santacrab2), [@zyro670](https://github.com/zyro670), [@xiaolong11123](https://github.com/xiaolong11123), and everyone else that contributed, thank you for your hard work <3

### Supports The Following Games:  SV/BDSP/PLA/SWSH/LGPE
**__Please don't charge people to use this free program. Be nice <3__**

## __Beautiful Embeds__
  
![image](https://github.com/bdawg1989/MergeBot/assets/80122551/561fc354-aa6b-47ac-aec0-4b788ec7a650)

## __Additional Embed Text__
  
You can add any text you want for your embeds that will show above the pokemon info.

![image](https://github.com/bdawg1989/MergeBot/assets/80122551/6b45b883-427c-410b-9dc0-2edeb9c83efe)

## __Batch Trading__
This feature allows your users to batch trade pokemon.  You can set how many you'd like to allow in the settings, or turn it off completely.
```
.bt
[Showdown Template]
---
[Showdown Template]
---
[Showdown Template]
```

## __Mystery Eggs__
Who doesn't like a good mystery?
All of the Mystery Eggs are always Shiny, Perfect IVs, and have the Hidden Ability.  What Egg will you hatch?
Command:  `me` or `mysteryegg`.

## __Egg Trades__
Thanks to Koi, I have implemented Egg Trades in this as well.
To request an egg, you will type `egg <species>` instead of `trade`.
Example:  
```
.Egg Charmander
Shiny: Yes
```

![image](https://github.com/bdawg1989/MergeBot/assets/80122551/cd7158f9-3d05-4306-8ad9-5d7e97d28c5d)

## __Announcements__
Announcements allow the bot owner to broadcast a single announcement to every server the bot is in, allowing you to turn the bot off and on without having to worry about letting every server you share your bot in know what's going on.

![image](https://github.com/bdawg1989/MergeBot/assets/80122551/2367d387-0642-4691-ab55-02be03535742)

![image](https://github.com/bdawg1989/MergeBot/assets/80122551/367d78c5-5e9b-4df7-b1b4-8562b6e3044b)

There are many different settings that allows you to customize your Announcement embed the way **You** want!  You can choose from premade thumbnail images of cute Pokémon holding megaphones, pick your own embed color, or completely use your own custom thumbnail images via settings.

![image](https://github.com/bdawg1989/MergeBot/assets/80122551/83266efa-0449-4f9d-8212-4d197cad119c)

### Set up
First, let's sync your whitelist channels with the announcechannels.  Run the `sch` command and all of the channels in your ChannelWhitelist settings will be copied over.

If you don't have any whitelist channels set up, you will need to run the `aec` command in the discord channel that you want the announcements to show up in..

Then, run the `announce` command along with your chosen message, and it will send that announcement to all of your defined channels at once.

## __Server Blacklisting & Management__
Do you share your bot in several servers?  Is your bot a public bot where you allow anyone to add your bot?
Our advanced Server Management features allow you to easily blacklist any server.
Command `bls <serverid>` and `ubls <serverid>` to unblacklist them.
When you blacklist a server, this bot will automatically leave the server.  Adios!

## __Default Held Items__
Choose a popular default held item if the user doesn't provide one.  Choose from popular items like Ability Patch, Rare Candy, Fresh-Start Mochi, and more!

## __Events & BattleReady Folder__
If you would like to provide your amazing members with Home Tracked Battle-Ready Legendaries and Event Pokemon, just add the files to a folder on your local machine, and provide the path in the settings under **Trade > EventsFolder/BattleReadyPKMFolder**
You can download Home Tracked and Battle Ready Pokemon from my website that are ready to go!  (all .pk9 files)  Also, Thanks to all my discord users that contributed to these!  (Maddison, Marnie, Fly, Reedy, Newfie, Joseph11024)

Events: https://genpkm.com/tradebot/events.zip

BattleReady:  https://genpkm.com/tradebot/battleready.zip

Home Tracked Database (Various Generations provided by Joseph11024)
https://drive.google.com/drive/folders/1-6Z2A75-MRbxxsjT3GNvgtPKubeQLXgC

For your users to request, they will use the following commands:

`le` will list all the events.  This is filterable, too.  So you can do `le 2` for page 2 of the Events List, or, you can do `le <species>` for all the specific species events. Example:  `le mewtwo 2` will give me page 2 of the mewtwo events.
`brl` will list all of the Battle Ready Pokemon in your folder for users to choose from.  The same filter applies to this command as above.

The user will be DM'd a list and given the correct command with your bots prefix to allow them to request it.

![image](https://github.com/bdawg1989/MergeBot/assets/80122551/fd43fb3e-6bfc-472c-ac26-d55e59f94abf)

![image](https://github.com/bdawg1989/MergeBot/assets/80122551/107d3f4b-0f6a-4145-aaff-deebead6a09c)

## Utilizing VGCPastes Bot Commands

This guide is designed to help users efficiently utilize the commands introduced in our latest release. With these commands, users can generate Random VGC Teams directly from VGCPastes, enhancing their Pokémon battling experience.

# Generating a Random VGC Team

### Command:
- `.randomteam` or `.rt`

### Description:
Generates a random VGC team from the [VGCPastes spreadsheet](https://docs.google.com/spreadsheets/d/1axlwmzPA49rYkqXh7zHvAtSP-TKbM0ijGYBPRflLSWw/edit#gid=1837599752). The bot will create an embed with detailed information about the team, including the Team Description, Trainer Name, Date Shared, and a conditional display of the Rental Code—if available.

### Embed Display Features:
- **Team Description**: Offers an overview of the team's theme or strategy.
- **Trainer Name**: Indicates who created the team.
- **Date Shared**: Shows the recency of the team's share date.
- **Rental Code**: Provides a direct in-game access code, displayed only if available.

## Generating Full Teams from PokePaste URLs

### Command:
- `.pp` or `.Pokepaste`

### Description:
Allows users to generate full Pokémon VGC teams directly from PokePaste URLs. This feature streamlines the process of sharing and using teams.

### How to Use:
Type the command followed by the PokePaste URL containing the team you wish to use. For example:
```
.pp <PokePaste URL>
```

This command simplifies team sharing within your community or for personal exploration of new team builds.  Users can upload the .zip file to the trade channel with command `btz` (if **AllowBatchTrades** is on) and the bot will batch trade the full team.

### Support and Feedback

If you encounter any issues or have suggestions for improvement, please don't hesitate to reach out to us through our support channels. Your feedback is invaluable as we strive to enhance your experience with the bot.

**Happy Battling!**



# All of my Projects

## Showdown Alternative Website
- https://genpkm.com - An online alternative to Showdown that has legality checks and batch trade codes built in to make genning pokemon a breeze.

## Scarlet/Violet RaidBot

- [NotRaidBot](https://github.com/bdawg1989/NotPaldeaNET) - The most advanced RaidBot for Scarlet/Violet available, period.
  
## PKHeX - AIO (All-In-One)

- [PKHeX-AIO](https://github.com/bdawg1989/PKHeX-ALL-IN-ONE) - A single .exe with ALM, TeraFinder, and PokeNamer plugins included.  No extra folders and plugin.dll's to keep up with.

## MergeBot - The Ultimate TradeBot

- [Source Code](https://github.com/bdawg1989/MergeBot)

## Grand Oak - SysBot Helper
- A discord bot that helps with legality issues if someone submits a wrong showdown format.  [Join My Discord To Learn More](https://discord.gg/GtUu9BmCzy)
  
![image](https://github.com/bdawg1989/MergeBot/assets/80122551/0842b48e-1b4d-4621-b321-89f478db508b)



# License
Refer to the `License.md` for details regarding licensing.
