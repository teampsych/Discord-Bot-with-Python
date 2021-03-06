# Discord-Bot-with-Python
![Kitten!!!](./img/readme.png "Kitten!!!")

A simple Discord Bot for testing purposes created with Python 3

## 1. Set up the bot and enter some servers
Documentation here [https://github.com/reactiflux/discord-irc/wiki/Creating-a-discord-bot-&-getting-a-token]

## 2. Install discord.py (with python 3 as default)
*Without voice support*
```
python -m pip install -U discord.py
```

*With voice support*
```
python -m pip install -U discord.py[voice]
```

## 3. Configure token and other profile options in test.py
```
token = ''  # HERE
avatar = './img/kitty.jpg'
nickname = 'Kitten'
```

## 4. Run the bot
```
python test.py
```

## 5. Test commands
Can be send from the discord server or private message
* __!test__: Counts user messages
* __!sleep__: Sleeps for 5 seconds 
* __!info__: Shows sample message 
* __!setnick__: Sets profile username
* __!setavatar__: Sets profile avatar

# More examples
Official docs [https://github.com/Rapptz/discord.py/blob/async/examples/]