# Markdown Overview
Updated 20-5-2023

# Markdown Documentation & Tools
* [In-browser Markdown Editor](https://stackedit.io)
* [Markdown Guide](https://www.markdownguide.org)
* [Markdown Here - Chrome Extension](https://markdown-here.com/index.html)
* [Markdown Interactive Tutorial](https://www.markdowntutorial.com)
* [Markdown Monster - The Markdown editor for Windows](https://markdownmonster.west-wind.com)
* [Markdownpad - Editor for Windows](https://markdownpad.com)
* [Markdown Software](https://kde.github.io/ghostwriter/)
* [Online Markdown Writer Tool](https://dillinger.io)

# Markdown Cheatsheet
* [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

<!-- Headings -->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

<!-- Alternate headings notation -->
Heading 1 Alternative Notation
===

Heading 2 Alternative Notation
---

<!-- Paragraphs -->
This is a paragraph

This is a paragraph (2 or more space + return = `<br />` (line break)   
This is another paragraph with 2 or more space and a return at the end.


<!-- Italics & Escape-->
*This text* is italic

_This text_ is italic

<!-- Strong -->
**This text** is strong/bold

__This text__ is strong/bold

<!-- Bold and Italic Variants -->

***Important*** text

___Important___ text

__*Important*__ text

**_Important_** text

<!-- Strikethrough -->
~~This text is not italic~~ (2x ~~ on each side)

<!-- Horizontal rule -->
___

<!-- Block quotes --> 
> This is a quote

> Multi-line
> Block quote
> Looks nice


> This the first paragraph.
>
>> And this is the nested block quote.

<!-- Hyperlinks -->
[Markdown to HTML converter](https://www.browserling.com/tools/markdown-to-html)

[Web developer tools](https://www.browserling.com/tools/ "Web developer tools")

<!-- Inline code block -->
`<p>This is a piece of code.</p>`

<!-- Images -->
![Markdown logo](https://markdown-here.com/img/icon128.png)

or

```html
<img src="drawing.jpg" alt="drawing" width="200">
```

<!-- Footnote-->
Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### What is markdown?
<!-- Unordered list -->
* Lightweight markup language with a plain text formatting syntax
* Can be converted into HTML/XHTML and other formats
* Its main purpose is readability and ease of use

### What Is It Used For?
* Readme files (Github, etc.)
  * Forum and blog posts
    * Used in many static site generators

### Some Things You Can Format
<!-- Ordered list -->
1. Headings
1. Lists
1. Emphasis
1. Links
1. Blocks of code
1. Images
1. Blockquotes
1. Horizontal rules

___
## Github Markdown

<!-- Code block  -->
```bash
npm install sass -g
```

```javascript
function count(num1, num2) {
  return num1 + num2;
}
```

Simulate console/terminal:
```console
npm install
``` 

<!-- Tables -->
| Name  | Email
|-------|---------|
| John  | Email   |
| John  | Email   |

<!-- Task lists -->
* [x] Item 1
* [x] Item 2
* [ ] Item 3

## Notes Novi Hogeschool
* `index.html` Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. (Highlight filename or code)

`[Link to a header in the same document](#)`
[Link to a header in the same document](#) - Typing # will give you a menu with all the headers in the document. # is home. To top.
