Please not that this is not an original work:
The efforts have been put by https://github.com/kkrypt0nn/Python-Twitch-Bot-Template




# Python Twitch Bot Template
<p align="center">
  <a href="//github.com/kkrypt0nn/Python-Twitch-Bot-Template/releases"><img src="https://img.shields.io/github/v/release/kkrypt0nn/Python-Twitch-Bot-Template"></a>
  <a href="//github.com/kkrypt0nn/Python-Twitch-Bot-Template/commits/main"><img src="https://img.shields.io/github/last-commit/kkrypt0nn/Python-Twitch-Bot-Template"></a>
  <a href="//github.com/kkrypt0nn/Python-Twitch-Bot-Template/releases"><img src="https://img.shields.io/github/downloads/kkrypt0nn/Python-Twitch-Bot-Template/total"></a>
  <a href="//github.com/kkrypt0nn/Python-Twitch-Bot-Template/blob/main/LICENSE.md"><img src="https://img.shields.io/github/license/kkrypt0nn/Python-Twitch-Bot-Template"></a>
  <a href="//github.com/kkrypt0nn/Python-Twitch-Bot-Template"><img src="https://img.shields.io/github/languages/code-size/kkrypt0nn/Python-Twitch-Bot-Template"></a>
  <a href="//github.com/kkrypt0nn/Python-Twitch-Bot-Template/issues"><img src="https://img.shields.io/github/issues-raw/kkrypt0nn/Python-Twitch-Bot-Template"></a>
  <a href="//python.org"><img src="https://img.shields.io/badge/python-3.6%20%7C%203.7%20%7C%203.8-orange"></a>
</p>

This repository is a template that everyone can use for the start of their twitch bot.

When I first started creating my twitch bot it took me a while to get everything setup and working with cogs and more. I would've been happy if there were any template existing. But there wasn't any existing template. That's why I decided to create my own template to let <b>you</b> guys create your twitch bot in an easy way.

Please note that this template is not supposed to be the best template, but a good template to start learning how TwitchIO works and to make your own bot in a simple way.

If you plan to use this template to make your own template or bot, please give me credits, it would be greatly appreciated.

## Authors
* **[Krypton (@kkrypt0nn)](https://github.com/kkrypt0nn)** - The only and one developer

## Support

If you need some help for something, do not hesitate to join my discord server [here](https://discord.gg/HzJ3Gfr).

All the updates of the template are available [here](UPDATES.md).

## How to download it

This repository is now a template, on the top left you can simple click on "**Use this template**" to create a GitHub repository based on this template.

Alternatively you can do the following:
* Clone/Download the repository
    * To clone it and get the updates you can definitely use the command
    `git clone`

## How to setup

To setup the bot I made it as simple as possible. I now created a [config.yaml](config.yaml) file where you can put the needed things to edit.

Here is an explanation of what everything is:

| Variable                      | What it is                                                                                                                                                            |
| ------------------            | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| authentication_bearer         | This will be generated when you need it, so don't touch it.                                                                                                           |
| bot_version                   | This the current bot version                                                                                                                                          |
| channel                       | The name of the channel that you want your bot to manage.                                                                                                             |
| channel_id                    | This will be generated when you need it, so don't touch it.                                                                                                           |
| client_id                     | You need to create a console application [here](https://dev.twitch.tv/console/apps/create) and then a client id will be given.                                        |
| client_secret                 | Click on "Manage" for your bot [here](https://dev.twitch.tv/console/apps) and then click "New Secret", a secret "token" will be shown.                                |
| colored_logs                  | When logging the logs can be colored or not. I recommend to put `true` only if you are running the bot on MacOS, Linux or Windows 10 with Windows Terminal installed  |
| nick                          | The nickname that you want to give to your bot (I recommend to give the same name as the twitch account)                                                              |
| prefix                        | The prefix that can be used for the bot, it is made for one prefix only. Soon you I will make multiple prefixes possible                                              |
| startup_cogs                  | Â list of cogs that are being automatically loaded when starting the bot.                                                                                             |
| token                         | An OAuth token for the twitch account can be generated [here](https://twitchapps.com/tmi/), please keep `oauth:`.                                                     |


## How to start

To start the bot you simply need to launch, either your terminal (Linux, Mac & Windows) or your Command Prompt (Windows).

If you have multiple versions of python installed (2.x and 3.x) then you will need to use the following command:
```
python3 bot.py
```
or eventually
```
python3.8 bot.py
```
<br>

If you have just installed python today, then you just need to use the following command:
```
python bot.py
```

## Requirements
All the requirements can be found in the [requirements.txt](requirements.txt) file.

To install them simply run the following command in either your terminal (Linux, Mac & Windows) or your Command Prompt (Windows)
```
pip install -r requirements.txt
```

## Built With

* [Python 3.8](https://www.python.org/)

## Issues or Questions

If you have any issues or questions of how to code a specific command, you can:

* Join my discord server [here](https://discord.gg/HzJ3Gfr)
* Post them [here](https://github.com/kkrypt0nn/Python-Twitch-Bot-Template/issues)

Me or other people will take their time to answer and help you.

## Versioning

We use [SemVer](http://semver.org) for versioning. For the versions available, see the [tags on this repository](https://github.com/kkrypt0nn/Python-Twitch-Bot-Template/tags). 

## Bots who used this template

*DM Krypton#7331 to get yourself in this list*

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE.md](LICENSE.md) file for details
