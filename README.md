# Force Subscribing Bot [@KGN_FORCE_BOT](https://t.me/KGN_FORCE_BOT)

> A star ⭐ from you means a lot to us!

<p align="center"><a href="https://www.github.com/KGN-BOTS/ForceSubscribeBot"><img src="https://telegra.ph/file/317f37f33c0055bfb34d6.jpg" width="2000"></a></p>

Telegram bot to force users to subscribe a particular chat.

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

## Usage

### Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/KGN-BOTS/ForceSubscribeBot)

1. Tap on above button and fill `API_ID`, `API_HASH`, `BOT_TOKEN` (and `MUST_JOIN`).
2. Then tap "Deploy App" below it. Wait till deploying is complete (will take atmost 2 minutes).
3. After deploying is complete, tap on "Manage App"
4. Check the logs to see if your bot is ready!

### Local Deploying

1. Clone the repo
   ```markdown
   git clone https://github.com/KGN-BOTS/ForceSubscribeBot
   ```
   
2. Get a DATABASE_URL. If you don't know how, deploy using Heroku Button only or delete database things as it's not a compulsion.
   
3. Edit `Config.py` and fill the needed variables

4. Enter the directory
   ```markdown
   cd ForceSubscribeBot
   ```
5. Run the file
   ```markdown
   python3 fsubbot.py
   ```

## Environment Variables

#### Mandatory Vars

- `API_ID` - Get this from [my.telegram.org](https://my.telegram.org/auth)
- `API_HASH` - Get this from [my.telegram.org](https://my.telegram.org/auth)
- `BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather)
- `DATABASE_URL` - Will be automatically added by Heroku.
- `MUST_JOIN` - Username/ID of your telegram channel/group.

## Functions

> More features soon if suggested by you :)

## To-Do

> That's on you mainly...

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

## Credits

- [ZAHID](https://github.com/KGN-BOTS) For Creating Codes
- [Dan Tès](https://github.com/delivrance) for his [Pyrogram](https://docs.pyrogram.org) Library

## Support

Channel :- [@KGN_BOTS](https://t.me/KGN_BOTS)

Group Chat :- [@KGN_BOTS_SUPPORT](https://t.me/KGN_BOTS_SUPPORT)

## :)

[![ForTheBadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://github.com/KGN-BOTS)

[![ForTheBadge makes-people-smile](http://ForTheBadge.com/images/badges/makes-people-smile.svg)](https://github.com/KGN-BOTS)
