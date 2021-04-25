# Music Bot By **CPTN**
***This a music bot crafted in discord.js master, a discord api wrapper. So far, this plays music from youtube only.***

Looking for a code for a music bot ? This fully open source code is made for your project !

If you need help with this project, to get support faster you can join the help server by just clicking [here](https://discord.gg/gDwHcXSqkb).

### 🛠 **Installation Process**

Well, let's start by downloading the code.
Go to the folder ***`config`*** then the file **`bot.js`**.
For the bot to be able to start, please complete the file with your credentials as follows :

- **For emojis**

```js
emojis: {
    off: ':x:',
    error: ':warning:',
    queue: ':bar_chart:',
    music: ':musical_note:',
    success: ':white_check_mark:',
}
```

- **For configuration**

```js
discord: {
    token: 'YOUR BOT TOKEN',
    prefix: 'PREFIX',
    activity: 'ACTIVITY',
}
```

- **`token`**, the token of the bot available on the [Discord Developers](https://discordapp.com/developers/applications) section.
- **`prefix`**, the prefix that will be set to use the bot.
- **`activity`**, the activity of the bot.

In the console, type **`npm install`** to install all dependencies.

- To start the bot :

```
#With Node
node index.js
npm start #Indicated in package.json

#With pm2
pm2 start index.js --name "MusicBot"
```

All you have to do is turn on your bot !

### 🎶 **MUSIC COMMANDS**

```
play <name/URL>, play music in a voice channel.
search <name>, open a panel to choose a music and then play it.
pause, pause the current music.
resume, puts the current music back on.
queue, see the next songs.
clear-queue, remove music in the queue.
shuffle, to mix the queue.
nowplaying, see music in progress.
loop, to enable or disable the repeat function.
volume <1 - 100>, change the volume.
skip, skip to next music.
stop, stop all music.
filter <filter>, add / remove filter.
w-filters, see filters.
```

### 💡 **GENERAL COMMANDS**

```
ping, see the bot latency.
help, see the list of available commands.
debug, see number of voice connections.
```

### 🎵 **BOT CODE LISENCE**

- GIVE OUR SEVRER NAME IN BOT STATUS **WITH BOT HOMETOWN**
