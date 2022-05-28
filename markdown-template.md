[This is a comment that will be hidden. Place a space before and after.]: # 

https://devhints.io/vimscript - Great resource


# Logo Product line

# Introduction

**Lorem ipsum** dolor *sit amet*. 

- Single asterisks italicize text *like this*. 
- Double asterisks embolden text **like this**.

Start a new paragraph with a blank line separating paragraphs.

- This will start an unordered list environment, and this will be the first item.
- This will be a second item.
- A third item.
    - Four spaces and a dash create a sublist and this item in it.
- The fourth item.
    
1. This starts a numerical list.
2. This is no. 2 in the numerical list.
    
# This Starts A New Section
## This is a Subsection
### This is a Subsubsection
#### This starts a Paragraph Block.

> This will create a block quote, if you want one.

Want a table? This will create one.

Table Header  | Second Header
------------- | -------------
Table Cell    | Cell 2
Cell 3        | Cell 4 

Note that the separators *do not* have to be aligned.

Want an image? This will do it.

![caption for my image](path/to/image.jpg)

`fig_caption: yes` will provide a caption. Put that in the YAML metadata.

Almost forgot about creating a footnote.[^1] This will do it again.[^2]

[^1]: The first footnote
[^2]: The second footnote

Want to cite something? 

- Find your biblatexkey in your bib file.
- Put an @ before it, like @smith1984, or whatever it is.
- @smith1984 creates an in-text citation (e.g. Smith (1984) says...)
- [@smith1984] creates a parenthetical citation (Smith, 1984)

That'll also automatically create a reference list at the end of the document.

[In-text link to Google](http://google.com) as well.

Horizontal rules
Three or more dashes or asterisks: 

    ---

    ***

    - - - -

 
### Badges
 
### Gif of end product

### Pre-Reqs
Drop downs for Software with redirect to Repo with information.

<details>
<summary>Linux</summary>
Redirect to that repository
</details>

<details>
<summary>macOS</summary>
</details>

### Installation


### Command Guide

### Break Page

`<br>`

### Emoji

Click here for [**Emoji!**](https://gist.github.com/rxaviers/7360908)

### Images
Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

### Escaping Pipe Characters in Tables
You can display a pipe (|) character in a table by using its HTML character code (`&#124;`)

### Code and Syntax Highlighting
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

## Heading IDs
Custom ID for customization
`### My Great Heading {#custom-id}` <br>
**or HTML** <br>
`<h3 id="custom-id">My Great Heading</h3>`

### Markdown Anchor Links
Click on a link to move to different sections in your README.md
`[Heading IDs](#heading-ids)`
`<a href="#heading-ids">Heading IDs</a>`

### Foot Notes

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

### Citations - References
#### Parenthetical
[@Citation-key_2016, p. 35]
#### In-text


### Links
[homebrew]: https://formulae.brew.sh/formula/zoxide
[emacs]: https://www.gnu.org/software/emacs/

## API Documentation
See full docs at: [API Docs](docs/api.md)

## Contributing
See [contributing guide](.github/CONTRIBUTING.md)

## Notes and Miscellaneous

* *Markdown Here* uses [Github Flavored Markdown](http://github.github.com/github-flavored-markdown/), with the limitation that GFM special links are not supported ([issue #11](https://github.com/adam-p/markdown-here/issues/11)); nor will they be, as MDH is not Github-specific.

* Available languages for syntax highlighting (and the way they should be written in the fenced code block) can be seen on the [highlight.js demo page](http://softwaremaniacs.org/media/soft/highlight/test.html).

* Images embedded inline in your Markdown will be retained when you "Markdown Toggle". Gmail allows you to put images inline in your email -- this can be much easier than referencing an external image.

* Email signatures are automatically excluded from conversion. Specifically, anything after the semi-standard `'-- '` (note the trailing space) is left alone.
  * Note that Hotmail and Yahoo do *not* automatically add the `'-- '` to signatures, so you have to add it yourself.

* The "Markdown Toggle" menu item shows up for more element types than it can correctly render. This is intended to help people realize that they're not using a rich editor. Otherwise they just don't see the menu item and don't know why.

* Styling:
  * The use of browser-specific styles (-moz-, -webkit-) should be avoided. If used, they may not render correctly for people reading the email in a different browser from the one where the email was sent.
  * The use of state-dependent styles (like `a:hover`) don't work because they don't match at the time the styles are made explicit. (In email, styles must be explicitly applied to all elements -- stylesheets get stripped.)

* For more tweaky features, visit the [Tips and Tricks](https://github.com/adam-p/markdown-here/wiki/Tips-and-Tricks) section.

