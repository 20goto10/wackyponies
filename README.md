# wackyponies
A few alternative .pony files for ponysay/ponythink (i.e. replacements for the default collection)

Dependencies: ponysay https://github.com/erkin/ponysay
Helpful: util-say (which includes img2ponysay, for converting the images into ANSI art): https://github.com/maandree/util-say

These files were created using img2ponysay on small, partly hand-edited transparent images found on the Internet. I offer them solely for your amusement. If you tack this script into your .bashrc you can enjoy this silliness every time you open a console. The inspiration for this came from here: https://tylercipriani.com/2014/05/22/creating-baller-useful-motd-ascii-art.html

'''
export TERM='xterm-256color'

figlet "$(hostname)"
FORTUNE=`/usr/games/fortune`
$(shuf -n 1 -e /usr/games/ponysay /usr/games/ponythink) $FORTUNE

I wiped out the /usr/share/ponysay/ponies and replaced them with the files here. You can also just use cat in the terminal to see what they'll look like, e.g. "cat zippy.pony".

Enjoy this pointlessness.

