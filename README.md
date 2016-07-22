# wackyponies
A few alternative .pony files for ponysay/ponythink (i.e. replacements for the default collection)

![dodo.pony](https://raw.githubusercontent.com/20goto10/wackyponies/master/screens/usage_screenshot.png)

Dependencies: ponysay https://github.com/erkin/ponysay 

Helpful: util-say (which includes img2ponysay, for converting the images into ANSI art): https://github.com/maandree/util-say

These files were created using img2ponysay on small, partly hand-edited transparent images found on the Internet. I offer them solely for your amusement. 

The inspiration for this came from here: https://tylercipriani.com/2014/05/22/creating-baller-useful-motd-ascii-art.html

Assuming you have fortune, you can add this to your .bashrc or (in Ubuntu) use it as the seed for a motd...

	export TERM='xterm-256color'
	figlet "$(hostname)"
	FORTUNE=`/usr/games/fortune`
	$(shuf -n 1 -e /usr/games/ponysay /usr/games/ponythink) $FORTUNE



I wiped out the /usr/share/ponysay/ponies and replaced them with the files here. 



Here's what we have so far:


![bender/dodo/homer.pony](https://raw.githubusercontent.com/20goto10/wackyponies/master/screens/set2.png)


![parrot/zippy/zoidberg.pony](https://raw.githubusercontent.com/20goto10/wackyponies/master/screens/set1.png)


Enjoy this pointlessness!

