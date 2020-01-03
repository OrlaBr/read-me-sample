
Table of Contents

Headers
Emphasis
Lists
Links
Images
Code and Syntax Highlighting
Tables
Blockquotes
Inline HTML
Horizontal Rule
Line Breaks
YouTube Videos
Headers

# H1  or ======== (below H1 text)
## H2  or --------- (below H2 text)
### H3
#### H4
##### H5
###### H6


### Highlighting Text

 - Emphasis = Add asterisk or underscore either side of the word to create emphasis: *asterisks* or _underscores_.

 - **bold** = 2 asterisk or underscore either side of the word: **asterisks** or __underscores__.

 - Combined emphasis with bold =  **asterisks and _underscores_**.

 - Strikethrough uses two tildes ~ ~. ~~Scratch this.~~

### Creating Lists

*Ordered List* =  use a number 1. or 1). Use \. for no number
1. list item 
2. list item 
3. list item

*Unordered List* =  use a * + -
- list item 
- list item 
- list item 

*List with Nested and Sub-nested bullet*
+ list item 
    1. list item 
    2. list item
        + list item


*Other List ttributes*
 - Unordered List can use * or - or +
 - ⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅



### Links

There are different ways to create links.

 - Inline Named Link = add square brackets [Named Link] 
 - Inline Named Link with title = add square brackets and parentheses brackets [NamedLink]  (https://www.google.com)
 - Inline Named Link to Item on Page = [heading-1](#heading-1 "Goto heading-1")
 - Reference Link with other link = [reference link][case-insensitive reference text]
 - Reference link to repository file = [relative reference to a repository file](../blob/master/LICENSE)
 - Reference Link with number = [reference][1]
 - Direct link = [link text itself]

  **Direct Links**
  - URLs in angle brackets get turned into links.<http://www.example.com> 


### Images

- [alt](http://via.placeholder.com/50)
- ![alt text](http://via.placeholder.com/50 "Image Title")
- ![alt][id]    (In reference [id]:placeholder 'Placeholder')


### Code and Syntax Highlighting
 
 - Inline code has back-ticks around it (alt numberpad 9 and 6 together `) =  `code` 
 -     or Indent 4 spaces
 - Create a block of code by fencing in with 3 back ticks ``` (code block, code fence)```
 - Add in angle brackets to create an <b>emphasis <b>
 
 
Markup: `code()`

Markup: ```javascript
        ```
Markup: ```python
        ```


### Tables

| and -- can be used to create a table 

|    Header 1    |    Header 2    |    Header 3   |
  --------------   --------------   -------------


| Header 1      | Header 2      | Header 3    |
| ------------- |:-------------:| -----------:|
| Content       | Content       | Content     |
| Content       | Content       | Content     |
| zebra stripes | are neat      | Content     |


Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

### Tick Boxes
 [ ] an uncompleted tast
 [x] a completed task

### Adding Quotes and other Features

**Blockquotes**

> Blockquotes are very handy in email to emulate reply text.
>> Nested Blockquote. 


**Adding HTML**
- Inline HTML

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>
  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

**Adding Line Breaks**

 - Line Break Adding a backslash or 2 blank spaces at the end of the line to create a line break \\
 - Line breaks = hit enter, 3 hyphens and enter to create a line breakHorizontal line: 
 - Add hyphens and space - - - - 
 - Asterisks ***
 - Underscores ___
 

**Adding Videos**
 - Can't be added directly but you can add an image with a link to the video like this:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

Or, in pure Markdown, but losing the image sizing and border:

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

**Adding Emojis**
 - Emoji codes can be found on <emoji-cheat-sheet.com> <https://www.webfx.com/tools/emoji-cheat-sheet/>
 - Code appears between colons :EmojiCode:

### References:

<adam-p/markdown-here>
<https://help.github.com/en/github/writing-on-github>
<https://www.webfx.com/tools/emoji-cheat-sheet/>
<https://dillinger.io/>
https://www.makeareadme.com/
https://commonmark.org/help/
