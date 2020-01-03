This is a sample of research done to learn best practice in how to write a ReadMe, and to learn Markdown Language

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

*Numbered List*
1. list item 
2. list item 
3. list item 

*Bullet List*
- list item 
- list item 
- list item 

*Bullet List with Nested and Sub-nested bullet*



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

Adding an image: (http://via.placeholder.com/50)

Image with an alt and title 
![alt text](http://via.placeholder.com/50 "Image Title")


### Code and Syntax Highlighting
 
 - Inline code has back-ticks around it (alt numberpad 9 and 6 together `) =  `code`
 - Create a block of code by fencing in with 3 back ticks ```
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


### Adding HTML
- Inline HTML

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>
  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

### Adding Line Breaks

 - Horizontal line: Add hyphens and space - - - - 
 - Asterisks ***
 - Underscores ___
 - Line breaks = hit enter, 3 hyphens and enter to create a line break

### Adding Videos
 - Can't be added directly but you can add an image with a link to the video like this:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

Or, in pure Markdown, but losing the image sizing and border:

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

### Referencee:

<adam-p/markdown-here>
<https://help.github.com/en/github/writing-on-github>
<https://www.webfx.com/tools/emoji-cheat-sheet/>
<https://dillinger.io/>
