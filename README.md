# Toxic-Security
> Discord Anti-Nuke Bot.

# Default Prefix
> ts/ `Customizable`

# Change Prefix
> ts/prefix {newPrefix} 

• Replace `{newPrefix}` with a prefix of your choice.

# Commands List
> ts/help - Shows the bots Help Message and a list of commands

> ts/prefix - Shows the bots Current Prefix and how to change it.

> ts/limits - Shows the current Server Limit settings for the bot.

> ts/recent - Shows a list of Recent Events and the user who triggered them.

> ts/reset - Resets the Limits to Default.

# Default Server Limit Settings 

• If any user attempts to Nuke the Server by triggering the following events and reaches or exceeds the following limits the bot will remove **ALL** their roles. 

```jsx harmony
 limits: {
        user_removals: {
            per_minute: 8,
            per_hour: 24
        },
        role_creations: {
            per_minute: 4,
            per_hour: 12
        },
        channel_creations: {
            per_minute: 4,
            per_hour: 12
        },
        role_deletions: {
            per_minute: 4,
            per_hour: 12
        },
        channel_deletions: {
            per_minute: 4,
            per_hour: 12
        },
        unbans: {
            per_minute: 8,
            per_hour: 24
        }
    }
```

# Bot in Action.

##### DM'S Owner when Limits are Reached.
![](https://i.imgur.com/gbVQrKP.png)

##### Up-To Date Event History
![](https://i.imgur.com/m2U4z2t.jpg)

##### Set Server Limits to avoid "Nukes".

![](https://i.imgur.com/3dmHUHj.jpg)
