# MusicBot

<<<<<<< HEAD
[![GitHub stars](https://img.shields.io/github/stars/Just-Some-Bots/MusicBot.svg)](https://github.com/Just-Some-Bots/MusicBot/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Just-Some-Bots/MusicBot.svg)](https://github.com/Just-Some-Bots/MusicBot/network)
[![Python version](https://img.shields.io/badge/python-3.8%2C%203.7%2C%203.6-blue.svg)](https://python.org)
[![Discord](https://discordapp.com/api/guilds/129489631539494912/widget.png?style=shield)](https://discord.gg/bots)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

MusicBot is the original Discord music bot written for [Python](https://www.python.org "Python homepage") 3.8+, using the [discord.py](https://github.com/Rapptz/discord.py) library. It plays requested songs from YouTube and other services into a Discord server (or multiple servers). If the queue is empty, MusicBot will play a list of existing songs that is configurable. The bot features a permission system, allowing owners to restrict commands to certain people. MusicBot is capable of streaming live media into a voice channel (experimental).

![Main](https://i.imgur.com/FWcHtcS.png)

## Setup
Setting up the MusicBot is relatively painless - just follow one of the [guides](https://just-some-bots.github.io/MusicBot/). After that, configure the bot to ensure its connection to Discord.

The main configuration file is `config/options.ini`, but it is not included by default. Simply make a copy of `example_options.ini` and rename it to `options.ini`. See [`example_options.ini`](./config/example_options.ini) for more information about configurations.

### Commands

There are many commands that can be used with the bot. Most notably, the `play <url>` command (preceded by your command prefix), which will download, process, and play a song from YouTube or a similar site. A full list of commands is available [here](https://just-some-bots.github.io/MusicBot/using/commands/ "Commands").

### Further reading

* [Support Discord server](https://discord.gg/bots)
* [Project license](LICENSE)
=======
## What does it do?

It plays music in a plug.dj "request" style and if nothing is left it will play through a list of existing songs!

## How do I set it up?

Install Python here - https://www.python.org/downloads/

Install Git here - https://git-scm.com/download/win

make sure you select this option in the Python install - https://i.gyazo.com/2c06a7ee35afda3383185916fd2a94d3.png

and this option in the Git install - https://cdn.discordapp.com/attachments/129489631539494912/129505383223001088/pic.png

It was coded in 3.5.1 but 3.5 will work fine.


Make sure you have installed the required modules by running `fixnupdate.bat`

Make sure you meet the non-code requirements of having existing accounts for
both discord.

##Options.txt set up

Line 1: Email address

Line 2: Password

Line 3: accepts "0" or "1", enables or disables the whitelist. 0 turning it off, 1 turning it on

Line 4: the number of days until a person can freely interact with the bot and not be on the whitelist

Line 5: The Owner's User ID

Line 6: The number of votes to skip for it to actually skip


## What are its commands?

`!whatismyuserid` will tell you your user ID!

`!whitelist [@username]` will whitelist people (and you if the server is new!) so they can play music

`!blacklist [@username]` will disallow a person from interacting with the bot!

`!play help` will summon a list of commands accepted by the bot!

`!play [youtube link]` will allow me to play a new song or add it to the queue.

`!play playlist` will print out all links to youtube videos currently in the queue!

`!play pause` will pause the playing of music! Will NOT pause the song but rather the playing of songs. Only usable by the bot's owner

`!play resume` will resume the playing of songs! Only usable by the bot's owner

`!play shuffle` will shuffle the songs in the playlist! Only usable by the bot's owner

`!play skip` will make it skip to the next song after 2 people vote! Instant skip though if used by the Bot's Owner

`!play volume [volume % in decimal form]` will change the volume level! Default is 0.15 (15%) **HAS TO BE A NUMBER FROM 0-1**

## Sounds cool, How do I use it?
Simply download the bot, set everything up, then run `runbot.bat`!

It'll let you know if it's connected and what channels are connected.

Once started, its good to go. If you have any errors, report them here or on my discord and then restart the bot

Rhino Bot Discord - https://discord.gg/0iqN3da4zqrSz036

#FAQ

Q:`'pip' is not recognized as an internal or external command`

A: http://stackoverflow.com/questions/23708898/pip-is-not-recognized-as-an-internal-or-external-command

Q:`Bot prints 'no, not whitelisted and new' when I try and play something`

A: Add yourself to the whitelist!

Q:`I'm getting this error! http://puu.sh/m6hkf/40eec0910c.png`
A: The bot needs permission to delete messages. I'll be adding an options file to toggle this later though

Q: `I'm having an issue with the Discord installation / It doesn't say anything when I run it`

A: Run `fixnupdate.bat`

Q:`I'm having other errors with the bot, it has to be broken`

A: If Rhinobot is running in my discord, the bot isn't broken. I keep everything as updated as possible! 


