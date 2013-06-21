# JiffyBot

## What is JiffyBot?
This is the source code for the popular reddit bot [/u/JiffyBot](http://www.reddit.com/u/JiffyBot/).

JiffyBot searches for reddit comments which mention its username or contains the string "Jiffy!", and a time range in the form ww:xx-yy:zz.
If the comment contains a YouTube link, Jiffy will make a GIF out of the YouTube link based on the specified time range.
If not, the bot will see if the post is a YouTube link, and use that link as the source for the GIF.

You can find out more [on this reddit post.](http://www.reddit.com/r/JiffyBot/comments/1fvyi5/rjiffybot_information_directory/)

## Setup
You can find info on setting the bot up in the [docs/SETUP.md](https://github.com/drkabob/JiffyBot/blob/master/docs/SETUP.md) file.

### Help! The bot isn't working or I can't set it up or I'm getting weird errors or I've grown a third arm!
You can find help by posting something on JiffyBot's [subreddit](http://www.reddit.com/r/JiffyBot).
If nobody gets to it you might want to [contact the bot's developer on reddit](http://www.reddit.com/message/compose?to=drkabob).

## How can I help?
We're actively looking for new features, bug fixes, etc. for JiffyBot. If you want to help you can fork the repo on GitHub and submit a pull request when you're done.

As far as guidelines go we aren't too picky, just try to follow PEP8, comment your code so everyone knows what it does. (I'll be sure to do the same in the future.)
Also, try to stick with the modules that are currently loaded or are in the standard library. If you do need or want functionality that is in external library, don't be discouraged, just be sure to mention it in the pull request.

If you submit a change that is super awesome you might be added to the [docs/CONTRIBUTORS.md](https://github.com/drkabob/JiffyBot/blob/master/docs/CONTRIBUTORS.md) list along with what you contributed!

### But **what** should I do to help?
If you're looking for something to do look at the todo list in [docs/TODO.md](https://github.com/drkabob/JiffyBot/blob/master/docs/TODO.md)

## License
The bot is licensed under GPL v3 with the following stipulations. Please view the license file in [docs/LICENSE](https://github.com/drkabob/JiffyBot/blob/master/docs/LICENSE).

* Your derivative work or copy of work must link to either this GitHub page or [this subreddit](http://www.reddit.com/r/JiffyBot). This link must be visible to any users of your derivative work.
* You must credit both Nathan Hakkakzadeh and John O'Reilly somewhere public relating to your derivative work.
* You must contact both Nathan Hakkakzadeh and John O'Reilly describing your derivative work if it becomes public. You **do not** need a reply to continue work and publish it.

Furthermore, these stipulations supersede any conflicting rules in the GPL v3.

(Don't stress about it too much, we're not going to hunt you down.)

## Who are the people behind JiffyBot?
JiffyBot was originally conceived by John O'Reilly. He manages the [subreddit](http://www.reddit.com/r/JiffyBot), bug tests, requests features, and pretty much everything that isn't writing code.
You can find him on [twitter](http://twitter.com/John_O_Really), [reddit](http://www.reddit.com/u/GoogaNautGod), and you can check out [his webcomic](http://purplejottedtittles.com/).

JiffyBot is written by Nathan Hakkakzadeh. He writes code and makes sure the bot doesn't crash (it does anyway). If you have any technical questions or advice, he's the one who takes them.
You can find him on [twitter](http://twitter.com/drkabob), [reddit](http://www.reddit.com/u/drkabob), and [his website](http://www.welcometonathan.com/) (try to find all the secrets!).

Finally, [check out these awesome guys who contributed.](https://github.com/drkabob/JiffyBot/graphs/contributors)