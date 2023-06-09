# Discord Bot Commands

>All the Bot's commands are slash commands

><> = required, [] = optional

| Category	| |
--------------------|--------------|
| Admin Commands | [Page](https://github.com/LucasV12/Bot-Guide/blob/main/Pages/Commands.md#admin-commands) |
| Fun Commands | [Page](https://github.com/LucasV12/Bot-Guide/blob/main/Pages/Commands.md#fun-commands) |
| General Commands | [Page](https://github.com/LucasV12/Bot-Guide/blob/main/Pages/Commands.md#general-commands) |
| Invite Commands | [Page](https://github.com/LucasV12/Bot-Guide/blob/main/Pages/Commands.md#invite-commands) |
| Level Commands | [Page](https://github.com/LucasV12/Bot-Guide/blob/main/Pages/Commands.md#level-commands) |
| Moderation Commands | [Page](https://github.com/LucasV12/Bot-Guide/blob/main/Pages/Commands.md#moderation-commands) |
| Suggestion Commands | [Page](https://github.com/LucasV12/Bot-Guide/blob/main/Pages/Commands.md#suggestion-commands) |
| Ticket Commands | [Page](https://github.com/LucasV12/Bot-Guide/blob/main/Pages/Commands.md#ticket-commands) |

## Admin Commands:

|	Command	| Description	| Permission | 
--------------------|--------------|-----
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
|	Command	| Description	| Permission | 
--------------------|--------------|-----
| `/minesweeper`      | Play a game of minesweeper in discord.        | `UseApplicationCommands` |
| `/snake`      | Play a game of snake in discord.        | `UseApplicationCommands` | 
| `/wordle`      | Play a game of wordle in discord.        | `UseApplicationCommands` | 


## General Commands:
|	Command	| Description	| Permission | 
--------------------|--------------|-----
| `/avatar [member]`      | Displays the avatar of a member.        | `UseApplicationCommands` | 
| `/botinfo`      | Displays some information about the discord bot.        | `UseApplicationCommands` | 
| `/discrim [discrim]`      | Displays all the member with the same discriminator.        | `UseApplicationCommands` |
| `/info guild`      | Displays information about the guild.        | `UseApplicationCommands` | 
| `/info user [member]`      | Displays information about a member.        | `UseApplicationCommands` | 
| `/info role [role]`      | Displays information about a role.        | `UseApplicationCommands` | 
| `/info channel [channel]`      | Displays information about a channel.        | `UseApplicationCommands` | 
| `/info emoji [emoji]`      | Displays information about an emoji.        | `UseApplicationCommands` | 
| `/members [role]`      | Displays all the members with a certain role.        | `UseApplicationCommands` | 
| `/ping`      | Displays the current websocket latency        | `UseApplicationCommands` | 
| `/uptime`      | Displays the bots uptime.        | `UseApplicationCommands` | 


## Invite Commands:
|	Command	| Description	| Permission | 
--------------------|--------------|-----
| `/invite-rank add [role] [#invites]`      | Add a new invite rank.        | `Administrator` | 
| `/invite-rank remove [role]`      | Remove an invite rank.       | `Administrator` | 
| `/invite-ranks`      | Displays all the invite ranks for the guild.       | `UseApplicationCommands` | 
| `/invites [member]`      | Displays the invites of a member of the guild.        | `UseApplicationCommands` |


## Level Commands:
|	Command	| Description	| Permission | 
--------------------|--------------|-----
| `/level-rank add [role] [#level]`      | Add a new level rank.        | `Administrator` | 
| `/level-rank remove [role]`      | Remove a level rank.       | `Administrator` | 
| `/level-ranks`      | Displays all the level ranks for the guild.       | `UseApplicationCommands` | 
| `/rank [member]`      | Displays the level of a member of the guild.        | `UseApplicationCommands` | 

## Moderation Commands:
|	Command	| Description	| Permission | 
--------------------|--------------|-----
| `/purge all [#amount] <channel>`      | Purge all the messages from a channel.        | `ManageMessages` | 
| `/purge attachments [#amount] <channel>`      | Purge all the attachments from a channel.        | `ManageMessages` | 
| `/purge bots [#amount] <channel>`      | Purge all the bot messages from a channel.        | `ManageMessages` | 
| `/purge links [#amount] <channel>`      | Purge all the links from a channel.        | `ManageMessages` | 
| `/purge user [member] [#amount] <channel>`      | Purge all the messages from a user in a channel.        | `ManageMessages` | 

## Suggestion Commands:
|	Command	| Description	| Permission | 
--------------------|--------------|-----
| `/suggestion create [suggestion]`      | Create a new suggestion        | `UseApplicationCommands` | 
| `/suggestion view [suggestion ID]`      | Lookup a suggestion       | `UseApplicationCommands` | 

## Ticket Commands:
|	Command	| Description	| Permission | Extra | 
--------------------|--------------|----- | ---- |
| `/ticket add [member]`      | Add someone to the support ticket.        | `UseApplicationCommands` | You need to have **suggestions-role** to use this command!
| `/ticket remove [member]`      | Remove someone from the support ticket.       | `UseApplicationCommands` | You need to have **suggestions-role** to use this command!
