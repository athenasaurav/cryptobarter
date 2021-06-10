# Arbitrage Trading Bot Between Binance and Open Source Peatio Deployed Exchange

## On Linux

If you are using Linux as your OS then you can follow the below-mentioned steps:-

Run ```pip install -r requirments.txt``` (Python 2), or ```pip3 install -r requirments.txt``` (Python 3)

Then Run ```pip freeze > requirments.txt```

Finally run ```python3 app.py``` (on Python 3)


## On Windows

If you are using Windows as your OS then use the following steps:-
```
python -m pip install -U pip setuptools
```

Run ```pip install -r requirments.txt``` (Python 2), or ```pip3 install -r requirments.txt``` (Python 3)

Finally run ```python3 app.py``` (on Python 3)


## On Ubuntu Server

If you are using Linux as your OS then you can follow the below-mentioned steps:-

Copy all the files on the server in a folder.

Enter into the folder.

# Installing requirments

Check first if Tmux is installed or not by trying to install tmux ```sudo apt-get install tmux```

Run ```pip install -r requirments.txt``` (Python 2), or ```pip3 install -r requirments.txt``` (Python 3). Prefer to use Python3

# Change Config File

Update the Config file data as per this tutorial i.e [botdetails](https://github.com/athenasaurav/cryptobarter/blob/main/botdetails.md).

We will use tmux for running this program forever.

# Deploying using Tmux

Firstly use command ```tmux``` to open a tmux screen. 

By default tmux start the screen numbering from 0. You can specify name parameter to name something different the screen which will be easy to remember.

To create a Tmux session with a custom name easy to remember use the following command ```tmux new -s <sessionname or sessionnumber>```

then in the new screen run ```python3 app.py``` (on Python 3)

Voila! you bot has started running.

You can now close the SSH window or come out of screen by pressing `ctrl`+`b` and then `d`

If you would like to see whats happening in your program you can write ```tmux attach <screenname or screennumber>```

To kill the screen, run command ```tmux kill-session```

To see the list of all the session, run command ```tmux list-sessions```

You can check the Tmux commands cheatsheet [here](https://github.com/athenasaurav/cryptobarter/blob/main/tmux.md)
