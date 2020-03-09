# Youtube Notification Bot
Simple and easy to use discord bot to notify members whenever a video is posted on a YouTube channel.

# Packages Used
- **[discord.js](https://npmjs.com/package/discord.js "View on npmjs")**
- **[quick.db](https://npmjs.com/package/quick.db "View on npmjs")**
- **[rss-parser](https://npmjs.com/package/rss-parser "View on npmjs")**

# config.js

```js
module.exports = {
    token: "YOUR_DISCORD_BOT_TOKEN", // discord bot token
    channel: "DISCORD_CHANNEL_ID", // channel id of a channel to send message
    messageTemplate: "Hello @everyone, **{author}** just now uploaded a video **{title}**!\n{url}", // message to send on discord
    channel_id: "YOUTUBE_CHANNEL_ID", // youtube channel id
    watchInterval: 30000 // Check every 30 seconds
};
```
