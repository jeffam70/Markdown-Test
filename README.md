# Markdown Viewer Test
Different viewers (like Minimalist Markdown Editor and GitHub) may display markdown differently.  This is a test for different viewers - view the source in a text editor while comparing output from markdown viewers.  Note: Some differences are only in how markdown appears in the text editor, but produces the same output when displayed in viewer.

# Headers

This is a Header 1
==================
This is a Header 2
------------------
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
Here's *italicized* text  
Here's __bold__ text  
Here's *__bold italicized__* text  

# Unordered lists 
- (-) list item
- (-) list two
  - (-) sublist one
+ (+) list item
  + (+) sublist item
    + (+) subsublist item
* (*) list item
* (*) list two
* (*) list three  

# Ordered lists 
1. numbered item without double-space line ending plus
Another non-bulleted item
1. numbered item with double-space line ending plus  
Another non-bulleted item
    1. sublist item

# Formatting (horizontal rules)
-----
- - -
*****
# Blockquote
> This is something someone said a while ago that's an interesting quote that is so long that it wraps on the screen in the browser and still appears fine on-screen continuing to be a run-on sentence that is almost not understandable in a normal sense.

> This is something  
someone said  
a while ago (with double-space line endings)

> This is something someone said a while ago that
>
>> quotes someone interesting as well
>
> and finishes afterward.
>
> #### Also, Headings...
> - and lists
> 1. can be included
> 2. too, as well as
>     `other markdown`

# Code  
Text with `inline code` included.
```
block of
source
code
```
Normal text   
```
    block of
    indented
    source code
```
Normal text   

    block of
    preformatted
    code

# Special Characters
&copy;
&reg;
&larr;
&uarr;
&asymp;
&#8212;
(See [HTML Characters](https://www.whatsmyip.org/html-characters/))

# Links
This is an inline [Google](https://www.google.com) link.  
This is a hinted inline [Google](https://www.google.com "See this 'title' hint?") link.  
This is an inline image link. ![alt-text-image](https://w3.org/Icons/valid-xhtml10)  
This is a hinted inline image link. ![alt-text-hinted-image](https://w3.org/Icons/valid-xhtml10 "See this 'title' hint on image?")  
Here is a reference link to [a Search Site][Google].  
Here is a reference link to [Microcontrollers][Parallax].  
Here is a reference link to an image: ![alt-text-hinted-image][W3C].

[Google]: https://www.google.com "Google - a popular search engine"
[Parallax]: https://www.parallax.com "Parallax - an educational electronics company"
[W3C]: https://w3.org/Icons/archive.png "See this 'title' hint on image?"

# Tables <small>(with embedded HTML formatting)</small>
|     |Column 1|Wrapped and <br/>Centered Column 2 |Right-justified<br/>Column 3 |
|-----|:-------|:---------------------------------:|----------------------------:|
|Row 1|Cell 1  |Cell 2                             |Cell 3                       |
|Row 2|Cell 4  |<small>Small Cell 5</small>        |Cell 6                       |
|Row 3|Cell 7  |Cell 8                             |Long Cell<br>Contents 9      |
|Row 4|Cell 10 |Cell 11 w/superscript<sup>123</sup>|Cell 12                      |
<small><sup>123</sup> Table note describing a special thing about a cell.</small>

# Oddities
Text followed by
This is a Header 1
==================
This is a Header 2
------------------
- (-) list item
+ (+) list two (spaced a bit further than prev (-) list item)
* (*) list three (spaced a bit further than prev (+) list item)
1. numbered item with double-space line ending followed by  
    4-space indented `inline code` statement
1. numbered item without double-space line ending followed by blank line then

    4-space indented `inline code` statement
1. numbered item without double-space line ending followed by two blank lines then


    4-space indented `inline code` statement

This is supposed to be _bold_ text  
This is supposed to be **strong italicized** text   

|-------------------------------------------|  
|          | Column 1 | Column 2 | Column 3 |
|----------|----------|----------|----------|
|  Row 1   |  Cell 1  |  Cell 2  |  Cell 3  |
|----------|----------|----------|----------|
|  Row 2   |  Cell 4  |  Cell 5  |  Cell 6  |  
|          |          |          |          |
|  Row 3   |  Cell 7  |  Cell 8  |  Cell 9  |  
|  Row 4   |  Cell 10 |  Cell 11 |  Cell 12 |
|-------------------------------------------|  
``` Some statement before
block of
source
code
``` And statement after  
Then another line
