# Installation instructions for Windows
1. [Download and install Node.js](https://nodejs.org/en/), version 12.3.0 and up is required.

2. Run these 3 commands in a command prompt ran as administrator (press Windows + X then click PowerShell (Administrator) or Command Prompt (Administrator))
```shell
npm i -g --add-python-to-path --vs2015 --production windows-build-tools
npm i -g node-gyp@latest
```

Once that's finished, close the command prompt or powershell, open the bot folder with explorer and click the file path and type in cmd

In the command prompt run
```shell
npm i
```

3. Rename the .env.example file to .env and modify the file with the necessary API keys (The only required ones are token and prefix)

# Getting a token

[Go to this link](https://discord.com/developers/applications)

Click new application

Name your bot

Save your application ID for later

Click Bot

Click Add Bot

Copy the token and put it in your .env file

Scroll down to priviliged intents

Turn on presence intent and server members intent

Save your changes

# Starting the bot
Run this command in a command prompt to start the bot
```shell
node index.js
```

# Inviting your bot
[Go to this link](https://discordapi.com/permissions.html#8589934591) and enter your application ID from earlier
