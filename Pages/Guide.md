# Discord Bot Guide
><> = required, [] = optional

### How to setup the discord bot for your guild?
Everything in the discord bot is customizable and you can completly customize the bot to your liking.
To start of you can run the `/settings` command to view the current guild config.

#### Channels
>You can setup the all the channels for the discord bot by running the `/setup channels [setting] [channel]` command.
    
![image](https://user-images.githubusercontent.com/41522688/225132881-6dfb416d-b8a9-4edd-92f5-73d4cd4c8d24.png)


| Channel	| Option | |
--------------------|--------------|--------------|
| Welcome |`welcome-channel` | This the channel where all the join messages get send to. |
| Goodbye |`goodbye-channel` | This the channel where all the leave messages get send to. |
| Server Logs |`server-logs` | This the channel where all the servers logs are send to. |
| Suggestions |`suggestions-channel` | The is the channel where all the suggestions are send to. |
| Suggestions Logs |`suggestions-logs` | The is the channel where all the logs regarding suggestions are send to. |
| Tickets |`tickets-channel` | The is the channel where people can create a support ticket. |
| Ticket Logs |`ticket-logs` | The is the channel where all the logs regarding tickets are send to. |
| Ticket Logs |`ticket-logs` | The is the channel where all the logs regarding tickets are send to. |
| Tickets Category |`ticket-category` | The is the guild category where supports tickets are created. |
| Verification |`verification-channel` | The channel where new members can verify themself. |
| Verification Logs |`verification-logs` | The channel where all the logs regarding verification are send to. |
| Youtube Alerts |`youtube-channel` | The channel where all the youtube notifications get send to. |
| Twitch Alerts |`twitch-channel` | The channel where all the twitch notications get send to. |
| Medal Alerts |`medal-channel` | The channel where all the medal notifications get send to. |
    
#### Roles
>You can setup the all the roles for the discord bot by running the `/setup role [setting] [role]` command.
    
![image](https://user-images.githubusercontent.com/41522688/225133056-62dc7d88-53bd-473a-a5d2-f8376c7e9e2c.png)


 | Role	| Option | |
--------------------|--------------|--------------|
| Join |`join-role` | This the role that new members recieve on joining the server. |
| Suggestions |`suggestions-role` | Members with this role can accept/deny/reset-vote suggestions in the server. |
| Tickets |`tickets-role` | Members with this role can add/remove members from a support ticket. |
| Verification |`verification-role` | This the role that members recieving on passing the verification.  |
| Youtube Alerts |`youtube-role` | This the role that gets pinged when someones uploads a youtube video.  |
| Twitch Alerts |`twitch-role` | This the role that gets pinged when someones goes live on twitch.  |
| Medal Alerts |`medal-role` | This the role that gets pinged when someones uploads a medal video. |
    
#### Server Logs    
>You can setup the all the logs u want to log for your server with the `/setup server-logs [log] [boolean]` command.
    
![image](https://user-images.githubusercontent.com/41522688/225133357-f05a1325-0840-40c5-8af3-bdb5d5b5f1dc.png)
    
    
| Log	|  |
--------------------|--------------|
| MessageDelete | This will log whenever a message gets deleted. |
| MessageUpdate | This will log whenever a message gets edited. |
| ChannelCreate | This will log when a new channels gets created.  |
| ChannelDelete | This will log when a new channels gets deleted.  |
| ChannelUpdate | This will log when a new channels gets edited.  |
| GuildUpdate | This will log when a the guilds gets edited.  |
| MemberJoin | This will log when a new member joins the server.  |
| MemberLeave | This will log when a member leaves the server  |
| MemberUpdate | This will log when a members gets edited.  |
| EmojiCreate | This will log when a new emoji is added to the server.  |
| EmojiDelete | This will log when an emoji is deleted from the server.  |
| EmojiUpdate | This will log when an emoji gets edited.  |
| RoleCreate | This will log when a new roles is created in the server.  |
| RoleDelete | This will log when a roles gets deleted from the server.  |
| RoleUpdate | This will log when a roles gets edited.  |
| Enable All | This will enable all the above logs.  |
| Disable All | This will disable all the above logs.  |

#### Message Panels
>You can setup the all the panels for your server with the `/setup panel [panel]` command.
>Message panels are the embeds thats are send for verification/creating tickets/etc..

![image](https://user-images.githubusercontent.com/41522688/225137352-2e981ce3-7c2a-485d-a606-ccf78bbe3544.png)

| Panel	|  | Important |
--------------------|--------------|--------------|
| Tickets Panel | This is the panel where people can create tickets. | Make sure u have set the **Tickets Channel** before using this command. |
| Verification Panel | This is the panel where people can verify themself | Make sure u have set the **Verification Channel** before using this command. |

### Reset Setting
>If you ever want to reset or disable a setting, you can use the command `/setup reset [setting]` command to do so.
