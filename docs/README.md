# User Commands
Post these commands in any channel where the bot is present
* `!help`: Links to this help page
* `!imdb`: Search [IMDB](https://www.imdb.com) for movies. Example: `!imdb back to the future`
* `!y` or `!youtube`: Search [YouTube](https://www.youtube.com) for videos. Example: `!y amazing horse`
* `!roll`: Generate a random integer in the given range. Example: `!roll 5-10`. Default: `1-20`
* `!8ball`: Will answer any yes/no question. Example: `!8ball Am I a good person?`
* `!seen`: Posts when a given user was last seen in the channel. Example: `!seen Kenny`
* `!p` or `!poe`: Search [Path of Exile Wiki](https://pathofexile.gamepedia.com). Example: `!p zana`
* `!g` or `!google`: Search the web with google. Example: `!g the nicest place on the internet`
* `!i` or `!img`: Search google images. Example: `!i cute dogs`
* `!top`: Posts statistics about the most used commands.
* `!stats`: Posts the URL (if available) to the complete stats.
* `!addquote`: Adds a quote to the database. Example: `!addquote <Batman> Get in the batmobile!`
* `!quote`: Posts a random quote from the quote database. You can get specific quotes by providing an index. Example: `!quote 3`.
* `!roll`: Posts the URL (if available) to the complete quotes.
* `!uman`: ?

# Remote Control
You can remote control the bot to some extent by sending it private messages (queries).  
Your host must be listed under `adminHosts` in the `settings.json`.

## Supported Admin Commands
* `!join <channel>`: Joins the supplied `channel`. Example usage: `!join #otherChannel`
* `!part <channel>`: Leaves the supplied `channel`. Example usage: `!part #otherChannel`
* `!nick <nickname>`: Changes the nickname to the supplied `nickname`. Example usage: `!nick MyBot2`
* `!removequote <index>`: Removes the quote with the supplied `index` from the database. Example usage: `!removequote 3`
* `!say <target> <message>`: Sends the supplied `message` to the supplied `target`. Example usage: 
```
!say #myChannel Hello World!
!say username Hello friend!
```