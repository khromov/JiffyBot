# Setup
## Requisites
* [Python 2.7](http://www.python.org/download/)
* requests (available via pip)
* The latest version of praw (available via pip)
	* Alternatively use [my fork of praw](https://github.com/drkabob/praw)
* youtube-dl (available via pip)
* [ffmpeg](http://www.ffmpeg.org/download.html)
* [gifsicle](http://www.lcdf.org/gifsicle/)

## Download
You can either download a ZIP from the GitHub repo or do `git clone https://github.com/drkabob/JiffyBot.git`

## Configuration
First, copy the file `jiffy-sample.cfg` to `jiffy.cfg`. You can use the command `cp jiffy-sample.cfg jiffy.cfg`.

Then follow the directions within the config to setup the new bot.

Then create two empty files named `blacklist.txt` and `readlist.txt`. You can use the command `touch blacklist.txt readlist.txt`.

## Running
The bot has a shebang line at the beginning, so it can be run with the command `./youtubetogif.py`.
However, if your system is set up so that your default Python interpreter is not Python 2.7, you should use the command `python2.7 youtubetogif.py`.

It is also strongly recommended that you run the bot in a screen session.

Finally, if you find the need to blacklist a particular subreddit, put the name of the subreddit (minus the /r/ part) in a separate line in the `blacklist.txt` file.

For example, if you wanted to ban /r/JiffyBot and /r/pics your `blacklist.txt` would look like this:
```
JiffyBot
pics
```

**You're done!**