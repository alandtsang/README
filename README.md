README
======
README use markdown syntax. GitHub's markdown syntax is on the basis of the
expansion of standard markdown syntax, called `GitHub Flavored Markdown`, acronym
`GFM`.

****

======


##Contents
* [Horizontal Rule](#Horizontal Rule)
* [Headers](#Headers)
* [Text](#Text)
	* [Highlighting](#Highlighting)
	* [Line Breaks](#Line Breaks)
* [Images](#Images)
* [Links](#Links)
	* [Links to external URL](#Links to external URL)
	* [Link to the URL in this repository](#Link to the URL in this repository)
* [Lists](#Lists)


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
### This is an H3
#### This is an H4
##### This is an H5
###### This is an H6


Text
--------
###Highlighting
```
`Linux` `Github`
```
Effect: `Linux` `Github`


Line Breaks
--------
Can't newline directly, you can fill two spaces in the back on a line of text, so the next line of text will be a new line.  
For example:
```
Live well, love lots, and laugh often.  
Keep trying no matter how hard it seems, it will get easier.
```
>Live well, love lots, and laugh often.  
Keep trying no matter how hard it seems, it will get easier.


Images
------
Image syntax looks like this:  
```
![Alt text](/path/to/img.jpg "Optional title")
```
- An exclamation mark: !
- Alt: text for the image
- The URL or path of the image
- An optional title attribute enclosed in double or single quotes.

For example:
```
![github-logo](https://github.com/alandtsang/README/blob/master/images/github-logo.png "Optional title")
```
![github-logo](https://github.com/alandtsang/README/blob/master/images/github-logo.png "Optional title")


Links
--------
###Links to external URL
|Syntax|Effect|
|----|----
|`[My Github][alandtsang Github]`|[My Github][alandtsang Github]
|`[alandtsang Github]:https://github.com/alandtsang`|

The first bracket is a identifier, and the second bracket is actual URL. `[identifier][URL]`

###Link to the URL in this repository
|Syntax|Effect|
|----|----
|`[images](/images)`|[images](/images)


Lists
--------
Markdown supports ordered (numbered) and unordered (bulleted) lists.

Unordered lists use asterisks, pluses, and hyphens — interchangably — as list
markers:

* Red
* Green
* Blue

is equivalent to:

+ Red
+ Green
+ Blue

and:

- Red
- Green
- Blue

Ordered lists use numbers followed by periods:

1. Elephant
2. Tiger
3. Monkey

------------------------------------
[alandtsang Github]:https://github.com/alandtsang "Aland's Github"
