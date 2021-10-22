# -NP-Operator
SaverFile - [?] NP OPERATOR [BOT] Transaction
Jobs: Secure Server, Watch over Members
  Commands: 

1. clean
Clean up NP OPERATORS commands.
?clean (optional number)
2. diagnose
Diagnose any command or module in the bot to determine if there are any problems.
?diagnose [command or module]
3. kick
Kick a member
?kick [user] [reason]
4. ignored
List channels and users where commands are ignored.
?ignored
5. ban
Ban a member, optional time limit
?ban [user] [limit] [reason]
6. ban save
Ban a user and save their messages in chat.
?ban save [user] (limit) (reason)
7. ban match
Ban members who sent messages matching the text, up to 100 messages. (Must be enabled in dashboard)
?ban match [match text]
8. mute
Mute a member so they cannot type or speak.
?mute [user] [limit] [reason]
9. moderations (Unactive)
Get a list of active moderations (timed) and remaining time.
10. undeafen
Undeafen a member
?undeafen [user]
11. members
List members in a role(s) (max 90)
?members [role]
12. rolepersist
Assign/unassign a role that persists if the user leaves and rejoins.
?rolepersist [user] [role], [optional reason]
13. rolepersist add
Adds a rolepersist to a user
?rolepersist [user] role, (reason)
14. rolepersist remove
Removes a rolepersist from a user
?rolepersist remove [user] role, (reason)
15. unmute
Unmute a member
?unmute [user] (optional reason)
16. softban
Softban a member (ban and immediate unban to delete user messages)
?softban [user] [reason]
17. warn
Warn a member
?warn [user] [reason]
18. deafen
Deafen a member
?deafen [user]
19. lock
Lock a channel with optional timer and message.
?lock [channel] (time) (message)
20. reason
Supply a reason for a mod log case
?reason [case num] [reason]
21. modlogs
Get a list of mod logs for a user
?modlogs [user] (page #)
22. unlock
Unlock a previously locked channel.
?unlock [channel] (message)
23. unban
Unban a member
?unban [user or id] [optional reason]
24. warnings
Get warnings for a user
?warnings [user]
25. case
Show a single mod log case
?case [Case ID]
26. notes
Get notes for a user
?notes [user]
27. delnote
Delete a note about a member
?delnote [user] [note ID]
28. note
Add note(s) about a member
?note [user] [text]
29. temprole
Assign/unassign a role that persists for a limited time.
?temprole [user] [time] [role], [optional reason]
30. temprole remove
Removes a temprole from a user
?temprole remove [user] role, (reason)
31. clearnotes
Delete all notes for a member
?clearnotes [user]
32. delwarn
Delete a single warning for a member
?delwarn [warning ID]
33. editnote
Edit a note about a member
?editnote [user] [note ID] [note]
34. modstats
Get moderation statistics for a mod/admin (may take up to 30 minutes to update)
?modstats [user]
duration
35. Change the duration of a mute/ban.
?duration [modlog ID] [limit]
36. lockdown
Lock channels defined in moderation settings.
?lockdown
lockdown end
End lockdown of multiple channels
?lockdown end
37. star
Shows some starboard stats for a message
?stars [message ID/link]

  Permissions: 
Talk [On]
Kick [On] 
Ban [On]
Warn [On]
Mute [On] 
 Voice Permissions:
Connect [On]
Speak [Off]
Use Voice Activity [On]
Move Members [On]
Mute Members [On]

Manager Commands: 

addmod
Add a moderator role.
?addmod [role]
addrole
Add a new role, with optional color and hoist.
?addrole [name] [hex color] [hoist]
announce
Send an announcement using the bot.
?announce [channel] [message]
announce everyone
Send an announcement with @everyone.
?announce everyone [channel] [message]
announce here
Send an announcement with @here.
?announce here [channel] [message]
announce role
Send an announcement with a role mention.
?announce role [role] [channel] [message]
ignorerole
Toggles command usage for a role. (Does not affect mods and managers)
?ignorerole [role]
delrole
Delete a role
?delrole [role]
delmod
Remove a moderator or mod role.
?delmod [user or role]
modules
List available modules
?modules
ignorechannel
Toggles command usage for a channel. (Does not affect mods and managers)
?ignorechannel [channel]
prefix
Get or set the command prefix for this server.
?prefix (prefix)
mentionable
Toggle making a role mentionable on/off
?mentionable [role name]
rolecolor
Change the color of a role.
?rolecolor [role] [hex color]
setnick
Change the nickname of a user.
?setnick [user] [new nickname]
nick
Change the bot nickname.
?nick [new nickname]
role
Add/remove a user to a role or roles.
?role [user] [role name]
role add
Add a user to a role or roles.
?role add [user] [role]
role toggle
Toggle a user from a role or roles.
?role toggle [user] [role]
role removeall
Remove all roles from a user
?role removall [user]
role all
Add/remove all users to or from a role. (Limit 1 role)
?role all [role]
role bots
Add/remove all bots to or from a role.
?role bots [role]
role humans
Add/remove all humans to or from a role.
?role humans [role]
role in
Add/remove users to or from a role that are in a role. (Limit 1 role)
?role in [in role], [role]
role status
Check current role assignment status
?role status
role cancel
Cancel current role assignment
?role cancel
module
Enable/disable a module.
?module [module name]
rolename
Change the name of a role.
?rolename [role], [new name]
customs
List, enable, disable custom commands.
?customs
customs list
List custom commands
?customs customs list
customs show
Show a custom command
?customs customs show [command]
customs enable
Enable a custom command
?customs customs enable [command]
customs disable
Disable a custom command
?customs customs disable [command]
clearwarn
Clear warnings for a user.
?clearwarn [user]
ignoreuser
Toggles command usage for a user.
?ignoreuser [user] [reason]
listmods
List moderators
?listmods
purge
Delete a number of messages from a channel. (limit 1000)
?purge
purge user
Delete messages for a user in the channel.
?purge [count] [user or id]
purge match
Delete messages containing text. (Limit 100)
?purge match [text] [count]
purge not
Delete messages not containing text. (Limit 100)
?purge not [text] [count]
purge startswith
Delete messages that start with text. (Limit 100)
?purge startswith [text] [count]
purge endswith
Delete messages that ends with text. (Limit 100)
?purge endswith [text] [count]
purge links
Delete a number links posted in the channel. (Limit 100)
?purge links [count]
purge invites
Delete server invites posted in the channel. (Limit 100)
?purge invites [count]
purge images
Delete a number of images in the channel. (Limit 100)
?purge images [count]
purge mentions
Delete messages with mentions in the channel. (Limit 100)
?purge mentions [count]
purge embeds
Delete messages containing rich embeds in the channel.
?purge embeds [count]
purge humans
Delete messages sent by humans (ignores bots).
?purge humans [count]
purge bots
Delete messages sent by bots.
?purge bots [count]
purge text
Delete messages containing text, ignoring images/embeds.
?purge text [count]
command
Enable/disable a command.
?command [command name]
automod
Configure automod settings.
?automod help
automod blacklist
Add a links to url blacklist (seperated by commas)
?automod automod blacklist [link1], [link2]
automod whitelist
Add a links to url whitelist (seperated by commas)
?automod automod whitelist [link1], [link2]
automod banword
Add banned words to the list (seperated by commas)
?automod automod banword [word1], [word2]
automod banexact
Add exact banned words to the list (seperated by commas)
?automod automod banexact [word1], [word2]
automod ignorechannel
Ignore/unignore a channel
?automod automod ignorechannel [channel|name]
automod ignorerole
Ignore/unignore a role
?automod automod ignorerole [role|name]
automod ignored
List ignored channels and roles
?automod automod ignored
giveaway
Make and manage giveaways
?giveaway help
giveaway create
Creates a new giveaway.
?giveaway giveaway create [channel] [winners] [duration] [name]
giveaway end
Ends a Giveaway immediately.
?giveaway giveaway end [message ID/message link]
giveaway reroll
Rolls a new winner for a ended giveaway.
?giveaway giveaway reroll [message ID/message link] (winner to reroll)

Info Commands: 
afk
Set an AFK status to display when you are mentioned
?afk
afk set
Set an AFK status shown when you're mentioned, and display in nickname.
?afk set [status]
afk ignore
Use in a channel to not return from AFK when talking in that channel.
?afk ignore [channel]
afk reset
Reset the AFK status message to default for a member.
?afk reset [user]
afk clear
Remove the AFK status of a member.
?afk clear [user]
afk list
List AFK statuses. (moderator only)
?afk list
remindme
Set a reminder
?remindme [time] [reminder]
color
Show a color using hex.
avatar
Get a users' avatar.
?avatar [user]
dynoavatar
Generates a Dyno-like avatar.
?dynoav
randomcolor
Generates a random hex color with preview.
?randomcolor
whois
Get user information.
?whois [user mention]
distance
Get the distance between two sets of coordinates
?distance [coords] [coords]
membercount
Get the server member count.
?membercount
discrim
Gets a list of users with a discriminator
?discrim 1234
emotes
Gets a list of server emojis.
?emotes
serverinfo
Get server info/stats.
?serverinfo
covid
Get COVID-19 stats.
?covid
covid country
Get stats for a country.
?covid country [country]
covid state
Get stats for a US state.
?covid state [state]
covid top
List top countries by cases.
?covid top
