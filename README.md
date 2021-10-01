# Reol 2.0

**About this branch**

This branch of MusicBot is only compatible with the `rewrite` version of the discord.py library, which can be installed using `python3 -m pip install -U git+https://github.com/Rapptz/discord.py@rewrite#egg=discord.py[voice]`. It is also a dependency in `requirements.txt`, so should be automatically installed by the bot if you run `update.py`.

---

Reol 2.0 is a private Discord music bot for my servers to use. Reol 1.0 was another fork of MusicBot and heavily outdated, so I'm reviving this project due to the recent YouTube takedowns of Groovy and Rythm bots. It plays requested songs, from YouTube and other services, into a Discord server (or multiple servers) and if the queue becomes empty it will play through a list of existing songs, if configured to do so. The bot features a permissions system allowing owners to restrict commands to certain people. As well as playing songs, MusicBot is capable of streaming live media into a voice channel (experimental).

This behaves almost the same way the original MusicBot functions, only heavily modified to make it how I want it to act.
