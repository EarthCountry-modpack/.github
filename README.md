
# EarthCountry Modpack 

EarthCountry is a multiplayer modpack for Minecraft created to play with our friends on a pseudo-political server It was tech based and the server was hosted with an Earth terrain recreation map (EarthCountry V1)

Today, it's the same as before, but updated to 1.19.2 for the V2.5, named Aetheria Politics, is now with mod modifications (through KubeJS and recipe manipulation inside the .jar when necessary)

![PackVersion](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2FEarthCountry-modpack%2FMinecraft-Instance-Files%2FDev%2FV&query=%24.Version&label=PackVersion%20&color=)

## Acknowledgements

 - Lights for his ideas and co-founding
 - You that awaits the release
 - Every Forge and former Forge mod creators in 1.16 (V1) and 1.19.2 (v2.5)
 - [Forge team](https://files.minecraftforge.net/) for their modloader
 - [Mojang, Notch and Microsoft](https://www.minecraft.net/) for Minecraft as a whole
 - [Crafty Controller](https://wiki.craftycontrol.com/en/4/) for the easy gui setup server and monitoring
 - [NKN1396](https://github.com/NKN1396/Discord-EmojiToRole) for it's Reaction Role bot
 - [jagrosh](https://github.com/jagrosh/MusicBot) for it's Music bot
 - [Arisamiga](https://github.com/Arisamiga/Discord-Ticket-Bot) for it's Support Ticket bot
 - [PetyXbron](https://github.com/PetyXbron/minecraft-bot) for it's Server Status bot

## Authors

- [@Nikki Devil](https://github.com/nikki-devil)
- [@TheLightyy](https://github.com/TheLightyy)

## FAQ

#### What will be the release/server date ?

No dates are given but you can expect it to release just before January 2025

#### 




## License

[WTFPL](http://www.wtfpl.net/)

[MIT](https://choosealicense.com/licenses/mit/) (ReactionRole bot)

[GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.fr.html) (ServerStatus bot)

[Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) (SupportTicket bot)

## Roadmap

- Custom crafts
- Custom tags
- Reworked tags (is necessary)
- Questbook
- Guidebook
- Wiki
- New machineries

.

.
## Run Locally
You'll need either gitgui or replace git steps by downloading yourself the repo
### For the server :
Install Java JDK 17
```
sudo apt update && apt install openjdk-17-jdk openjdk-17-jre
```
or on windows :
```
winget install Oracle.JDK.17
```

Clone the project

```bash
  git clone Link
```
(Link can be copied on the repo page)

Launch the run.sh or run.bat according to your operating system

Alternatively you can see Crafty Controller to also have a webpage to administrate the server.
[Crafty Controller](https://wiki.craftycontrol.com/en/4/)

.
### For the discord bots :

The music bot uses, for the time being, JMusicBot from jagrosh. Go see it on his page.
[JMusic Bot by jagrosh](https://github.com/jagrosh/MusicBot)

Install npm
```
sudo apt update && apt install nodejs npm
```
or on windows :
```
winget install openjs.nodejs
```

Clone the project

```bash
  git clone Link
```
(Link can be copied on the repo page)

Go to the project directory

```bash
  cd ProjectDirectoryCreated
```

Install dependencies

```bash
  npm i
```

Change the token by your bot token and edit the config file to match your needs (see the readme in the corresponding repo)

Start the bot

```bash
  npm start
```

