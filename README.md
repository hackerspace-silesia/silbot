# Silbot

[Hubot](http://hubot.github.com/) for silesia hackerspace https://lists.hackerspace.pl/mailman/listinfo/silesia

## Usage

More scripts can be found at https://github.com/github/hubot-scripts/tree/master/src/scripts
Just add chosen to `hubot-scripts.json` (eventually add dependencies to `package.json`)

## Development

Install [Node](http://nodejs.org/) (i.e. via [nvm](https://github.com/creationix/nvm))

Install dependencies:

```
npm install
```

Run (choose you own IRC room):

```
HUBOT_IRC_UNFLOOD=true HUBOT_IRC_NICK=hubot-silesia HUBOT_IRC_ROOMS="#hubot-irc" HUBOT_IRC_SERVER="irc.freenode.net" bin/hubot -a irc
```

## Deployment

Push your changes to Heroku app (ask for permissions if don't have already)
