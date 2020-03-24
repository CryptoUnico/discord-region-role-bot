# Discord Region Role Bot

A Discord bot that allows users to self-assign regional country roles using flag emojis.

On load, the bot will prune regional country roles that have no member associated to them.

<div align="center">
  <img src="https://raw.githubusercontent.com/peterthehan/assets/master/repositories/discord-region-role-bot/regionRole.gif" />
</div>

## Setup

1. Adapt and follow the steps found in [create-discord-bot](https://github.com/peterthehan/create-discord-bot).

> Follow the [Create Bot](https://github.com/peterthehan/create-discord-bot#create-bot) and [Get Bot](https://github.com/peterthehan/create-discord-bot#get-bot) sections. Remember to replace with the correct project name in step 1 of the [Get Bot](https://github.com/peterthehan/create-discord-bot#get-bot) section!

> Don't forget to give your bot the `Manage Roles` permission!

2. Open [src/config.js](https://github.com/peterthehan/discord-region-role-bot/blob/master/src/config.js) to configure your own settings:

```js
regionRoleLimit: 1,
guilds: [
  'GUILD_1_ID',
  'GUILD_2_ID',
  // ...Add as many guilds as you want.
]
```

> `regionRoleLimit` is the maximum number of regional country roles a user is able to have.

> List of flag emojis can be found at https://emojipedia.org/flags/.

> The maximum number of roles in a server is [250](https://twitter.com/discordapp/status/954189000285270016).

Visit for more help or information!

<a href="https://discord.gg/WjEFnzC">
  <img src="https://discordapp.com/api/guilds/258167954913361930/embed.png?style=banner2" title="Discord Server"/>
</a>
