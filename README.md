
## Community 
[YouTube Channel](https://www.youtube.com/channel/UCIoVs12F-A5FZLN2NSEokWg)

[Discord Community Server](https://discord.gg/drDBTyKnRG)


## **Features** : 
- Invite joiner [Single Invite/Multiple Invites] with delays to bypass Anti-Raid bots
- Mass DM Advertisement 
- Single DM Spam
- Reaction Adder
- Token format changer
- Token Checker
- Guild Leaver
- Token Onliner
- Scraping [3 Modes to get the maximum users including an Opcode 8 Scraper]
- Name Changer
- Avatar Changer
- Checks if tokens are in a server
- Multi-threaded and supports high number of simultaneous accounts
- Proxyless / HTTP(s) Proxies
- Can ping users
- Can send Embeds
- Supports multiple messages, sends one randomly
- Can receive messages from people it messaged
- Uses safe requests to prevent phone locks
- Free & Open source
- Compatible with all major OS and Architectures
- Highly documented to help the user run it without problems

### Example configuration
```json
{
    "individual_delay": 60,
    "rate_limit_delay": 60,
    "offset": 100,
    "skip_completed": true,
    "remove_dead_tokens": true,
    "remove_completed_members": true,
    "stop_dead_tokens": true,
    "check_mutual": false,
    "friend_before_DM": false,
    "online_tokens": true,
    "online_scraper_delay": 1000,
    "call": false,
    "proxy_from_file": false,
    "max_dms_per_token": 0,
    "receive_messages": true,
    "use_proxy_for_gateway": false
}
```
This is the config I'd use, with ofcourse the offset calculated accordingly. 


### Example message 1 : Single Message, No Embed
```json
[
  {

  }
]
```

### Example message 2: Multiple messages, No Embeds. 
```json
[

  {
    "content": "We had a discord but it got terminated"
  },
  {
    "content": "We might make one again but too lazy to do so"
  }
]
```

### Example message 3: Single Message with Embed. 
```json
[
  {
    "content": "Hi TOS Followers",
    "embeds": [
      {
        "title": "This is the example message",
        "description": "You can use [links](https://discord.com) or emojis :smile: 😎 and use \\n to change lines",
        "color": 39129,
        "thumbnail": {
          "url": "https://www.freepnglogos.com/uploads/discord-logo-png/concours-discord-cartes-voeux-fortnite-france-6.png"
        },
        "image": {
          "url": "https://i.imgur.com/wybANM4.png"
        },
        "footer": {
          "text": "Discord does not like us :( ",
          "icon_url": "https://www.freepnglogos.com/uploads/discord-logo-png/concours-discord-cartes-voeux-fortnite-france-6.png"
        }
      }
    ]
  }
]
```


## Support my Journey!
Leave a star on the repository, helps out intensively! You can also buy me a cookie on these addresses if I helped you out in any way :) 

- *ETH*: 0x5A1d454c37c72d4e18102C1274C2827268dF2229

- *BTC*: bc1q45kx96j2fvtv30sc0kz2m8hw36dvdhrhnm0a6y

- *SOL*: 9VaQiD6zeuepVufmg4of8maUy7ZmeGeSuZck4soE2hbS

- *LTC*: LcnQG7UsrbC87AEzB3ychxwqVL9RDnb5XC



