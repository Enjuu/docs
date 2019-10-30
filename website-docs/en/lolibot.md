---
title: "LoliBot Commands"
old_id: 3
---
These are the commands supported by LoliBot, our chat bot.  

### General commands
- `!roll` - Returns a random number from 0 to 100  
- `!roll n` - Returns a random number from 0 to n  
- `!help` - Display help message  
- `!pp [mode]` - Show your current pp. If `mode` is not present, LoliBot will tell you the amount of PP for your current game mode. If mode is present (it can be `std/taiko/ctb/mania`), LoliBot will tell you the amount of PP for that gamemode. **This command works only in PMs**
- `!update` - Update the beatmapset you've `/np`ed in our beatmap mirror. Use this if you've just downloaded a beatmap from osu!direct and it shows as outdated or if a beatmap can't be downloaded from osu!direct because it's too new.
- `!bloodcat` - If osu!Direct is down, you can use this for get a map from multiplayer

### Faq commands
- `!faq rules`  
- `!faq swearing`  
- `!faq spam`  
- `!faq offend`  
- `!faq english`  
- `!faq github`  
- `!faq discord`  
- `!faq blog`  
- `!faq changelog`  
- `!faq status`  

### Tillerino-like commands
LoliBot has some commands similar to Tillerino. Those commands work only if you send them to LoliBot through a PM. Remember that PP system has been implemented only on osu!standard and osu!mania. The bot doesn't support beatmaps recommendations at the moment, that functionality wil come later, hopefully.

- `/np` - Show PP for the current playing song  (only if is a osu! standard song)  
- `!last` - Show info (and gained PP, if it was an osu! standard score) about the last submitted score  
- `!with <mods>` - Show PP for the previous requested beatmap with requested mods. Supported mods are `NF, EZ, HD, HR, DT, HT, NC, FL, SO.`. Don't use spaces for multiple mods (eg: `!with HDHR`)

### Admin commands
- `!system restart` - Restart the server. Everyone will be disconnected and reconnected automatically  
- `!system status` - Show server status  
- `!system reload` - Reload bancho settings (the one that are editable from EAP)  
- `!system maintenance on/off` - Turn on/off bancho maintenance mode  
- `!moderated on/off` - Turn on/off moderated mode for the current channel  
- `!silence <username> <count> <unit (s/m/h/d)> <reason>` - Silence a user  
- `!removesilence <target>` - Remove target's silence   
- `!kick <username>` - Kick an user from the server  
- `!ban <username>` - Ban and kick someone  
- `!unban <username>` - Unban someone  
- `!restrict <username>` - Restrict someone  
- `!unrestrict <username>` - Unrestrict someone  
- `!fokabot reconnect` - Reconnect LoliBot if he's not on online users list anymore  
- `!alert <message>` - Send a notification to every user connected to bancho  
- `!alertuser  <username> <message>` - Send a notification to a specific user
