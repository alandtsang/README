README
======
README use markdown syntax. GitHub's markdown syntax is on the basis of the
expansion of standard markdown syntax, called `GitHub Flavored Markdown`, Acronym
`GFM`.

****

======


##Contents
* [Horizontal Rule](#Horizontal Rule)
* [Headers](#Headers)



Horizontal Rule
--------
You can produce a horizontal rule tag by placing three or more hyphens, asterisks, or underscores on a line by themselves. 
***
---
___


Headers
--------
Markdown supports two styles of headers, Setext and atx.

Setext-style headers are “underlined” using equal signs (for first-level headers) and dashes (for second-level headers).
For example:

This is an H1
=============
This is an H2
-------------

Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6.
For example:

# This is an H1
## This is an H2
###### This is an H6

Optionally, you may “close” atx-style headers. This is purely cosmetic — you can use this if you think it looks better.

The closing hashes don’t even need to match the number of hashes used to open the header. (The number of opening hashes determines the header level.) :

# This is an H1 #
## This is an H2 ##
### This is an H3 ######

