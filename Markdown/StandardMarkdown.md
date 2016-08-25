
Standard Markdown
====

##Header
~~~~
This is an H1
=============
~~~~
ex)
>This is an H1
>=============

##Header Font
~~~~
# This is an H1

## This is an H2

###### This is an H6
~~~~
ex)
># This is an H1
>## This is an H2
>###### This is an H6

##Blockquotes
~~~~
> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.
~~~~
ex)
> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

##Lists

~~~~
1. red
2. green
3. blue
~~~~
ex)
> 1. red
2. green
3. blue

~~~~
* Red
* Blue
* Green
~~~~

~~~~
+ Red
+ Blue
+ Green
~~~~

~~~~
- Red
- Blue
- Green
~~~~
ex)
> * Red
* Blue
* Green


##Code blocks
~~~~
    This is codeblock (-4 spaces)
~~~~
ex)

    This is codeblock (-4 spaces)

##Horizontal Rules
~~~~
* * *

***

*****

- - -

---------------------------------------
~~~~

ex)
* * *
***
*****
- - - -
---------------------------------------

##Links
~~~~
This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.
~~~~

ex)
>This is [an example](http://example.com/ "Title") inline link.
[This link](http://example.net/) has no title attribute.
<br>

~~~~
I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].

  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"
~~~~
ex)
>I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].

  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"

##Emphasis
~~~~
*single asterisks*

_single underscores_

**double asterisks**

__double underscores__
~~~~
ex)
>*single asterisks*
_single underscores_
**double asterisks**
__double underscores__

##Code
     Use the `printf()` function.
ex)
>Use the `printf()` function.

##Email
    Contact to <example@example.com>.
ex)
>Contact to <example@example.com>.

##Images
~~~~
![Alt text](/path/to/img.jpg)

![Alt text](/path/to/img.jpg "Optional title")

![Alt text][id]
[id]: /path/to/img.jpg "Optional title"
~~~~

<br><br>
* * *
Standard Markdown Syntax References : http://pad.haroopress.com/page.html?f=syntax