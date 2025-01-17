Seden UserBot
==

![GitHub repo size](https://img.shields.io/github/repo-size/DarkRulers0/Telegram-TomUserBot?color=red&style=plastic)
![GitHub](https://img.shields.io/github/license/TeamDerUntergang/Telegram-SedenUserBot?color=red&style=plastic)

Telegram Python Bot running on Python3 with a Postgresql Sqlalchemy database. It is an modular and simple to use bot.

```c
#include <std/disclaimer.h>
/**
    Your Telegram account may be banned.
    I'm not responsible for misuse of bot, responsibility belongs entirely to user.
    This bot is maintained for fun as well as managing groups efficiently.
    If you think you will have fun by spamming groups, you are wrong.
    In case of any spam ban, if you come and write that my account has been banned,
    I'll just laugh at you.
/**
```
## Run Bot
```bash
# Clone repo
git clone https://github.com/DarkRulers0/Telegram-TomUserBot.git
cd Telegram-SedenUserBot

# Install pip dependencies
pip3 install -r requirements.txt

# Generate session from session.py (skip if there is already)
python3 session.py

# Create config.env and fill variables
mv sample_config.env config.env

# Run bot
python3 seden.py
```

## Heroku Deploy
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/DarkRulers0/Telegram-TomUserBot/tree/seden)

## License

This project is licensed under the [AGPL-3](https://www.gnu.org/licenses/agpl-3.0.html).
