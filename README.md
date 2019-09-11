# discord-music-player

[![NPM](https://img.shields.io/npm/l/discord-music-wrapper)](https://github.com/Ztumpie905509/discord-music-wrapper/blob/master/LICENSE)   [![npm](https://img.shields.io/npm/v/discord-music-wrapper)](https://www.npmjs.com/package/discord-music-wrapper)   [![GitHub repo size](https://img.shields.io/github/repo-size/Ztumpie905509/discord-music-wrapper)](https://github.com/Ztumpie905509/discord-music-wrapper)   [![GitHub language count](https://img.shields.io/github/languages/count/Ztumpie905509/discord-music-wrapper)](https://github.com/Ztumpie905509/discord-music-wrapper/search?l=JavaScript)   [![npm](https://img.shields.io/npm/dm/discord-music-wrapper)](https://www.npmjs.com/package/discord-music-wrapper)

This is currently under heavy development.

This package can help you with playing music in a discord.js bot.

## musicClientOptions

| Option |Default|Description|
|---|---|---|
|`earProtections`|`true`|Using `false` will by pass the limit on the volume command, accepting volumes higher than `100`.|
|`loop`|`false`|Using `true` will set the loop setting enabled upon queue creation|
|`volume`|`30`|Volume based on `100`, such that the default setting will be `30/100` and thus make the volume safe for turning the music bot volume in discord to 100%. Tuning up the volume higher than `50` is not recommended. |
