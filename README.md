# 5bot
### Custom bot for [5YLJ Discord Server](https://discord.com/invite/hFmuqXM9Jn) made with Lua

## Setup
Install [Luvit](https://luvit.io/) <br>
Install [Discordia](https://github.com/SinisterRectus/Discordia#installation) (This is the library used for the bot)

## Self-Hosting
To host the bot you need to make a `envVars.lua` file in the `src` folder, and put this code in it:
```lua
local env =
{
    TOKEN = "BOT TOKEN HERE",
}

return env
```
This file is not provided by default for safety causes.

You can of course change the structure/name/other stuff if you know what you are doing. 

To run the bot, go to the source folder, and execute `luvit main.lua` in your CMD/Terminal. <br>
**The main bot will be on the server.**

## FaQ
**Q: Why Lua?** <br>
A: Lua is a really light-weight, but still powerful language, with a large community, due to it's wide use for modmaking.