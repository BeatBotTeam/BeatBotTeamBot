# BeatBotTeamBot

# This bot based on [GroupButler](https://github.com/RememberTheAir/GroupButler)

##Setup
You **must** have Lua (5.2+) installed, plus some modules: LuaSocket, LuaSec, Redis-Lua, Lua term and Lua serpent. And, to upload files, you need Curl installed too.

How to install LuaRocks and set-up the modules:

```bash
# Download and install LuaSocket, LuaSec, Redis-Lua, Lua-term and serpent

$ wget http://luarocks.org/releases/luarocks-2.2.2.tar.gz
$ tar zxpf luarocks-2.2.2.tar.gz
$ cd luarocks-2.2.2
$ ./configure; sudo make bootstrap
$ sudo luarocks install luasocket
$ sudo luarocks install luasec
$ sudo luarocks install redis-lua
$ sudo luarocks install lua-term
$ sudo luarocks install serpent
$ cd ..
```

Install Curl, only if missing:
```bash
$ sudo apt-get install curl
```

Clone the github repository:
```bash
# Clone the repo and give the permissions to start the launch script

$ git clone https://github.com/BeatBotTeam/BeatBotTeamBot.git
$ cd BeatBotTeamBot && sudo chmod 777 launch.sh
```

**First of all, take a look to your bot settings:**

> • Make sure that privacy is disabled (more info in the [official Bots FAQ page](https://core.telegram.org/bots/faq#what-messages-will-my-bot-get)). Write `/setprivacy` to [BotFather](http://telegram.me/BotFather) to check the current setting.

**Before you do anything, open config.lua in a text editor and make the following changes:**

> • Set bot_api_key to the authentication token you received from the [BotFather](http://telegram.me/BotFather).

Before start the bot, you have to start Redis. Open a new window and type:
```bash
# Start Redis

$ sudo service redis-server start
```


# BeatBot Team
-----------------

# Owner : [Amirho3inf](http://telegram.me/amirho3inf)

# BeatBot Team Channels
-----------------

# Fa : [BeatBot_Team](http://telegram.me/beatbot_team)
# En : [BeatBotTeam](http://telegram.me/beatbotteam)
