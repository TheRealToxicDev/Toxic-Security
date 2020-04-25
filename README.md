# Toxic-Security
> Discords best Anti-Nuke Bot.

## Table of Contents
- [Default Prefix](#prefix)
- [Change Prefix](#newPrefix)
- [Command List](#commands)
- [Default Limits](#defLimits)
- [Screenshots](#examples)
- [Support](https://discord.gg/MbjZ7xc)


<a name="prefix"></a>
# Default Prefix
> ts/ `Customizable`

<a name="newPrefix"></a>
# Change Prefix
> ts/prefix {newPrefix} 

• Replace `{newPrefix}` with a prefix of your choice.

<a name="commands"></a>
# Commands List
> ts/help - Shows the bots Help Message and a list of commands

> ts/prefix - Shows the bots Current Prefix and how to change it.

> ts/limits - Shows the current Server Limit settings for the bot.

> ts/recent - Shows a list of Recent Events and the user who triggered them.

> ts/reset - Resets the Limits to Default.

<a name="defLimits"></a>
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

<a name="examples"></a>
# Bot in Action.

##### DM'S Owner when Limits are Reached.
![](https://i.imgur.com/gbVQrKP.png)

##### Up-To Date Event History
![](https://i.imgur.com/m2U4z2t.jpg)

##### Set Server Limits to avoid "Nukes".

![](https://i.imgur.com/3dmHUHj.jpg)
