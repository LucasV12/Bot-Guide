# Discord Bot Commands

>All the Bot's commands are slash commands

><> = required, [] = optional

## Admin Commands:

|	Command	| description	| Permission | Example
|---------------|--------------------|--------------|-----
| `/alerts add youtube [channel] [member]`      | Add a new youtube channel to the notifications list.        | `Administrator` | 
| `/alerts remove youtube [channel]`      | Remove a youtube channel from the notifications list.        | `Administrator` | 
| `/alerts add twitch [channel] [member]`      | Add a new twitch channel to the notifications list.        | `Administrator` | 
| `/alerts remove twitch [channel]`      | Remove a twitch channel from the notifications list.        | `Administrator` | 
| `/alerts add medal [user-id] [member]`      | Add a new medal user to the notifications list.        | `Administrator` | 
| `/alerts remove medal [user-id]`      | Remove a medal user from the notifications list.        | `Administrator` | 
| `/alerts view youtube`      | View all the youtube channels on the notifications list.        | `Administrator` | 
| `/alerts view twitch`      | View all the twitch channels on the notifications list.        | `Administrator` | 
| `/alerts view medal`      | View all the medal users on the notifications list.        | `Administrator` | 




## Fun Commands:
|	Command	| description	| Permission | Example
|---------------|--------------------|--------------|-----|
| `/minesweeper`      | Play a game of minesweeper in discord.        | `UseApplicationCommands` | `/minesweeper` |
| `/snake`      | Play a game of snake in discord.        | `UseApplicationCommands` | `/snake` |
| `/wordle`      | Play a game of wordle in discord.        | `UseApplicationCommands` | `/wordle` |


## General:
|	Command	| description	| Permission | Example
|---------------|--------------------|--------------|-----|
| `/avatar [member]`      | Displays the avatar of a member.        | `UseApplicationCommands` | `/avatar @!L#9702` |
| `/botinfo`      | Displays some information about the discord bot.        | `UseApplicationCommands` | `/botinfo` |
| `/discrim [discrim]`      | Displays all the member with the same discriminator.        | `UseApplicationCommands` | `/discrim #0001` |
| `/info guild`      | Displays information about the guild.        | `UseApplicationCommands` | `/info guild` |
| `/info user [member]`      | Displays information about a member.        | `UseApplicationCommands` | `/info user @!L#9702` |
| `/info role [role]`      | Displays information about a role.        | `UseApplicationCommands` | `/info role @Guest` |
| `/info channel [channel]`      | Displays information about a channel.        | `UseApplicationCommands` | `/info channel #general` |
| `/info emoji [emoji]`      | Displays information about an emoji.        | `UseApplicationCommands` | `/info emoji <:twitter:1083364994403541092>` |
| `/members [role]`      | Displays all the members with a certain role.        | `UseApplicationCommands` | `/members @Guest` |
| `/ping`      | Displays the current websocket latency        | `UseApplicationCommands` | `/ping` |
| `/uptime`      | Displays the bots uptime.        | `UseApplicationCommands` | `/uptime` |


## Invite Commands:
|	Command	| description	| Permission | Example
|---------------|--------------------|--------------|-----|
| `/invite-rank add [role] [#invites]`      | Add a new invite rank.        | `Administrator` | `/invite-rank add @Tier1 10` |
| `/invite-rank remove [role]`      | Remove an invite rank.       | `Administrator` | `/invite-rank remove @Tier1` |
| `/invite-ranks`      | Displays all the invite ranks for the guild.       | `UseApplicationCommands` | `/invite-ranks` |
| `/invites [member]`      | Displays the invites of a member of the guild.        | `UseApplicationCommands` | `/invites @!L#9702` |


## Level Commands:
|	Command	| description	| Permission | Example
|---------------|--------------------|--------------|-----|
| `/level-rank add [role] [#level]`      | Add a new level rank.        | `Administrator` | `/level-rank add @Level10 10` |
| `/level-rank remove [role]`      | Remove a level rank.       | `Administrator` | `/level-rank remove @Level10` |
| `/level-ranks`      | Displays all the level ranks for the guild.       | `UseApplicationCommands` | `/level-ranks` |
| `/rank [member]`      | Displays the level of a member of the guild.        | `UseApplicationCommands` | `/rank @!L#9702` |