# Blitzcrank Discord Bot
a League of Legends Discord bot that monitors specified players and tracks of their live games and ranked progress.

# Features

- Monitors a list of summoners and sends a Discord embed when they join a game / finish a game
- Automatically edits the embed when the game finishes with the match duration and the KDA scoreboard
- Monitors the summoners' LP loss and gains

> Optional Emojis to replace Champion Names!<br>
![cmdline](https://i.imgur.com/QS3hOMc.png)

> When that summoner is found in a game, it will send a Discord embed to a specified Discord channel.
> <br>Eventually, when the game finishes, it will react with a W or an L (depending on the summoner's side)
![cmdline](https://i.imgur.com/2xsBbGJ.png)

> Multisearch feature (copy and paste the lobby join messages)
![cmdline](https://i.imgur.com/6pGBliH.png)

> **Update 4/21/2021** <br>The embed now changes when the game finishes with the match duration and everyone's scores
![cmdline](https://i.imgur.com/oHTYONq.gif)

> Now monitor's everybody's LP gains/loss<br>
![cmdline](https://i.imgur.com/9eOMPEv.png)

# Instructions

- Install the required libraries, one of them is https://github.com/meraki-analytics/role-identification
- Edit the lines under BOT SETTINGS in the discordbot.py
- Run the .py

To enable emoji support, follow instructions in /icondownloader in this repo

# Requirements

- Python
- Riot API Key (obtained from Riot Developer Portal)
- Discord Bot Token with INTENTS ENABLED
