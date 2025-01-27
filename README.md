# LOVE-VSCode-Starter-Template
A minimalistically configured VSCode template for LOVE

## Features
- 📄 Rich Lua language features with [Lua Language Server](https://github.com/LuaLS/lua-language-server)
- 🔧 Debugging with [Local Lua Debugger](https://github.com/tomblind/local-lua-debugger-vscode)
- 🔗 Extensible and configurable for your needs

## Prerequisites
- [Visual Studio Code](https://code.visualstudio.com/download)
- [LÖVE 11.x](https://love2d.org/)

**LÖVE should be in your PATH environment variable.**

## Setup
1 - [Use this template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) to create a new repository for your game, then clone that repository locally.\

2 - Open the folder with Visual Studio Code.
You will be prompted that there are recommended extensions and if you want to install these. Click 'Install'.\
If this does not happen, install [Sumneko's Lua extension](https://marketplace.visualstudio.com/items?itemName=sumneko.lua) and [Local Lua Debugger](https://marketplace.visualstudio.com/items?itemName=tomblind.local-lua-debugger-vscode) manually.

3 - Configure the `conf.lua` with the settings specific for your game.\
**NOTE**: Make sure to keep `t.console` set to `false` in `love.conf`. Local Lua Debugger will not work otherwise.

4 - Change the `LICENSE` file to your liking and/or swap out my name for your name.

In case you need help, feel free to send me (Keyslam) a message in the [LÖVE Discord server](https://discord.com/invite/rhUets9). There's also a bunch of other cool people there who are always willing to help.

## Running
Press `F5` to launch the game in 'Debug mode'. In debug mode you can use breakpoints and inspect variables. This does have some performance impact though.\
You can switch to 'Release mode' in the 'Run and Debug' tab (`Ctrl+Shift+D`).\
Alternatively, you can run `lovec game` in the terminal, but you will have debugging capabilities.