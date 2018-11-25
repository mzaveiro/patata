# 🥔 patata 🥔

A pomodoro timer for the shell with [Taskwarrior](https://taskwarrior.org)
connection.
A fork from [potato.sh](https://github.com/Bladtman242/potato) with tweeks.

## How it work

```sh
patata -h

usage: potato [-s] [-m] [-w m] [-b m] [-p i] [-t t] [-h]
    -s: simple output. Intended for use in scripts
		        When enabled, potato outputs one line for each minute, and doesn't print the bell character
		        (ascii 007)

    -m: mute -- don't play sounds when work/break is over
    -w m: let work periods last m minutes (default is 25)
    -b m: let break periods last m minutes (default is 5)
    -p i: let iterate of pomodori bevor the big break (default is 4)
    -t t: let task ID from Taskwarrior to start (default is the most urgent task)
    -h: print this message
```

How the Pomorore Technique works read and learn it on
[Wikipedia](https://en.wikipedia.org/wiki/Pomodoro_Technique).

Learn also to use [Taskwarrior](https://taskwarrior.org) and you can use them
until this script run.

## Credits
Origin forket from the potato script from [Bladtman242](https://github.com/Bladtman242/).

Notification sound (notification.wav, originally
zapsplat\_mobile\_phone\_notification\_003.mp3 decoded and saved as wav with
mpg123)
obtained from [zapsplat.com](https://www.zapsplat.com/) under Creative Commons
CC0.

## License
MIT
