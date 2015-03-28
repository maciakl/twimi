# Twimi #

Twimi is a minimalistic command line twitter updater using, bash, curl and figlet.

### What does it do? ###

Twimi is a simple bash script which will ask you for a status update and then submit it via curl to twitter. It does not check twitter updates, it does not do private messages or anything of that sort. It is minimalistic, and simple and you can probably write a better one in 5 minutes but nevertheless it is here if you want to use it.

### How do you pronounce it? ###

I don't really care. I pronounce it TIMMAY like on South Park but then again, what the hell do I know.

### Can I contribute? ###

Sure you can. Drop me an email and I'll add you to the project. I don't particularly care about the direction of this thing. If you want to rewrite it, knock yourself out.

### System Requirements ###

  * bash
  * curl
  * figlet (optional)
  * base64 (optional)

Figlet is used for displaying the fancy font. You can also use toilet, or cowsay or whatever else you want. Simply set $whatlet (line 22) to appropriate program. Note that if you don't have figlet installed twimi will still work - you just won't get to see the logo like in the screenshots.

### Usage ###

Untar and run. Type /help for more options and /quit to exit. There is not much more to it.

### Config ###

Twimi will create a .twimi file in your home directory the first time you run it and will store your username and password there. The username is stored in plain text, but the password is base64 encoded. Note that this is for obfuscation purposes only - your password is not encrypted just scrambled. Also if you don't have the base64 package installed twimi will store your password in plain text. You may or may not want that so keep it in mind.

### Screenshots ###

It is a cli application but I know that people **need** to see screenshots before downloading anything so here you go:

![http://twimi.googlecode.com/svn/trunk/img/twimi.png](http://twimi.googlecode.com/svn/trunk/img/twimi.png)

_twimi with figlet_

![http://twimi.googlecode.com/svn/trunk/img/twimi_toilet.png](http://twimi.googlecode.com/svn/trunk/img/twimi_toilet.png)

_twimi with toilet_