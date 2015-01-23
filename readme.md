Translation files for Karsthafen minetest map.

Original map: 
https://forum.minetest.net/viewtopic.php?t=9706 - German thread
https://forum.minetest.net/viewtopic.php?f=12&t=6642 - English thread
CC-BY-SA - solars

These files contain the text for various signs in different languages.
Right now there is only the original German, and a rough English translation.

Format of a file:
Each sign file contains an even number of entries. An entry consists of two 
lines.

Line 1:
The actual text from the sign(s)

Line 2:
A comma separated list of the coordinates of signs on which the text appears.
x1, y1, z1, x2, y2, z2, ...
It follows that the number of sign nodes on which the given text appears will 
be the number of values / 3.
