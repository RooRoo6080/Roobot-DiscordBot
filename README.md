# Roobot - A Discord Bot
A python-based Discord bot that can play games and integrate with OpenAI for a chat bot.

***

## Features:

#### ```_help``` for the help dialogue
* use ```_roast``` for a roast
* use ```_ttt``` to play tic-tac-toe
* use ```_test``` for a typing speed test
* use ```_hangman``` to play hangman
* use ```_2048``` to play 2048
* use ```_poll``` question: option; option; etc. (up to 10)
- use ```_feedback``` and a review for feedback
- use ```_share``` for the link to add the bot to your server

#### Unlisted in help dialogue
* use ```_.``` and a message to command the bot to say anything you want
* use ```_chat``` to talk to the OpenAI chatbot

#### Other
* logs when a user leaves the server

#### Edit before using
* Line ```421``` Discord application API key
* Line ```388-389``` OpenAI API org and key

#### Moderator code features
* Line ```387``` Ban users from chatbot (replace 0 with Discord user id)

***

## Install modules
```pip install openai```

```pip install discord.py```

```pip install random-word```
