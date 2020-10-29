**Metadata:**
| Key       | Value                                                                                                                                        |
| :-------- | :------------------------------------------------------------------------------------------------------------------------------------------- |
| Title     | MySQL Quick-reference guide / revision guide / Cheat-sheet                                                                                   |
| Author    | Mrunal Nachankar <mrunalmn4@gmail.com>                                                                                                       |
| Reference | <ul><li>https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet </li><li> https://www.markdownguide.org/cheat-sheet/</li><li>https://www.markdownguide.org/basic-syntax/</li></ul> |

---
**Todo / Pending list / Future Scope:**
- [ ] Verify everything

---

**Table of Contents:**

- [1. Headings or Headers](#1-headings-or-headers)
- [2. Emphasis (Bold, Italics, Bold and Italics and Strikethrough)](#2-emphasis-bold-italics-bold-and-italics-and-strikethrough)
- [3. Lists](#3-lists)
  - [3.1. Ordered List (+,-,*)](#31-ordered-list--)
  - [3.2. Unordered List](#32-unordered-list)
- [4. Links](#4-links)
- [5. Images](#5-images)
- [6. Code and Syntax Highlighting (Fenced Code Block)](#6-code-and-syntax-highlighting-fenced-code-block)
- [7. Tables](#7-tables)
- [8. Blockquotes](#8-blockquotes)
- [9. Inline HTML](#9-inline-html)
- [10. Horizontal Rule](#10-horizontal-rule)
- [11. Line Breaks](#11-line-breaks)
- [12. Link / Hyperlinks](#12-link--hyperlinks)
- [13. YouTube Videos](#13-youtube-videos)
- [14. TeX Mathematical Formulae](#14-tex-mathematical-formulae)
- [15. Footnote](#15-footnote)
- [16. Heading ID](#16-heading-id)
- [17. Definition List](#17-definition-list)
- [18. Task List](#18-task-list)
- [19. Escaping Backticks](#19-escaping-backticks)
- [20. URLs and Email Addresses](#20-urls-and-email-addresses)
- [21. Container](#21-container)
- [22. Colors via html tags](#22-colors-via-html-tags)
- [23. markdown-it-abbr](#23-markdown-it-abbr)
- [24. Tips and Tricks](#24-tips-and-tricks)
  - [24.1. List inside blockquotes](#241-list-inside-blockquotes)
  - [24.2. List inside Table](#242-list-inside-table)
    - [24.2.1. Using html tag break: `<br>`](#2421-using-html-tag-break-br)
    - [24.2.2. Using html lists:](#2422-using-html-lists)
      - [24.2.2.1. Unorder list: `<ul><li></li></ul>`](#24221-unorder-list-ulliliul)
      - [24.2.2.2. Order list: `<ol><li></li></ol>`](#24222-order-list-olliliol)

---


---

# 1. Headings or Headers
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------
```

H1
H2
H3
H4
H5
H6

Alternatively, for H1 and H2, an underline-ish style:
Alt-H1
Alt-H2

| Markdown                              | HTML                                           | Rendered Output                   |
| :------------------------------------ | :--------------------------------------------- | :-------------------------------- |
| `# Heading 1` | <code>`<h1>Heading 1</h1>`</code> | <code><h1>Heading 1</h1></code> |
| `# Heading 2` | <code>`<h2>Heading 2</h2>`</code> | <code><h2>Heading 2</h2></code> |
| `# Heading 3` | <code>`<h3>Heading 3</h3>`</code> | <code><h3>Heading 3</h3></code> |
| `# Heading 4` | <code>`<h4>Heading 4</h4>`</code> | <code><h4>Heading 4</h4></code> |
| `# Heading 5` | <code>`<h5>Heading 5</h5>`</code> | <code><h5>Heading 5</h5></code> |
| `# Heading 6` | <code>`<h6>Heading 6</h6>`</code> | <code><h6>Heading 6</h6></code> |

---

# 2. Emphasis (Bold, Italics, Bold and Italics and Strikethrough)

```
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
```

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Very Strong Emphasis, aka bold italics, with ***asterisks*** or ___underscores___.

Strikethrough uses two tildes. ~~Scratch this.~~

| Markdown                              | HTML                                           | Rendered Output                   |
| :------------------------------------ | :--------------------------------------------- | :-------------------------------- |
| `*Italics*` | <code>`<i>Italics</i>`</code> | <code>*Italics*</code> |
| `**Bold**` | <code>`<b>Bold</b>`</code> | <code>**Bold**</code> |
| `__Bold__` | <code>`<b>Bold</b>`</code> | <code>__Bold__</code> |
| `***Bold and Italics***` | <code>`<b><i>Bold and Italics</i></b>`</code> | <code>***Bold and Italics***</code> |
| `___Bold and Italics___` | <code>`<b><i>Bold and Italics</i></b>`</code> | <code>___Bold and Italics___</code> |
| `Underline` | <code>`<h4>Underline</h4>`</code> | <code>_Underline_</code> |
| `Content` | <code>`<h5>Content</h5>`</code> | <code>Content</code> |
| `Content` | <code>`<h6>Content</h6>`</code> | <code>Content 6</code> |


---

# 3. Lists
```
1. First ordered list item
2. Another item
  * Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
4. And another item.  
   
   Some text that should be aligned with the above item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses
```

1. First ordered list item
2. Another item
  * Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
4. And another item.  
   
   Some text that should be aligned with the above item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses


## 3.1. Ordered List (+,-,*)

1. First item
2. Second item
3. Third item

## 3.2. Unordered List

- First item
- Second item
- Third item


---

# 4. Links
```
There are two ways to create links.

[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
```
There are two ways to create links.

[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

---

# 5. Images
```
Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
```

Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

---

# 6. Code and Syntax Highlighting (Fenced Code Block)

Code blocks are part of the Markdown spec, but syntax highlighting isn't. However, many renderers -- like Github's and Markdown Here -- support syntax highlighting. Markdown Here supports highlighting for dozens of languages (and not-really-languages, like diffs and HTTP headers); to see the complete list, and how to write the language names, see the highlight.js demo page.


```
Inline `code` has `back-ticks around` it. 
```

Inline `code` has `back-ticks around` it. 

Blocks of code are either fenced by lines with three back-ticks ```, or are indented with four spaces. I recommend only using the fenced code blocks -- they're easier and only they support syntax highlighting.
<pre>
<code>
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

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
</code>
</pre>

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

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

Again, to see what languages are available for highlighting, and how to write those language names, see the highlight.js demo page.

---

# 7. Tables

Tables aren't part of the core Markdown spec, but they are part of GFM and Markdown Here supports them. They are an easy way of adding tables to your email -- a task that would otherwise require copy-pasting from another application.

```
Colons can be used to align columns.

| Tables        |      Are      |  Cool |
| ------------- | :-----------: | ----: |
| col 3 is      | right-aligned | $1600 |
| col 2 is      |   centered    |   $12 |
| zebra stripes |   are neat    |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

| Markdown | Less      | Pretty     |
| -------- | --------- | ---------- |
| *Still*  | `renders` | **nicely** |
| 1        | 2         | 3          |
```

Colons can be used to align columns.

| Tables        |      Are      |  Cool |
| ------------- | :-----------: | ----: |
| col 3 is      | right-aligned | $1600 |
| col 2 is      |   centered    |   $12 |
| zebra stripes |   are neat    |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

| Markdown | Less      | Pretty     |
| -------- | --------- | ---------- |
| *Still*  | `renders` | **nicely** |
| 1        | 2         | 3          |

---

# 8. Blockquotes

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

    Blockquotes are very handy in email to emulate reply text. This line is part of the same quote.

Quote break.

    This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can put Markdown into a blockquote.

> Blockquotes are like quoted text in email replies
>> And, they can be nested
>>> One more and so on

# 9. Inline HTML

You can also use raw HTML in your Markdown, and it'll mostly work pretty well.

```
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
```

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>

---

# 10. Horizontal Rule

```
Three or more...

---

Hyphens

***

Asterisks

___

Underscores
```

Three or more...

---

Hyphens

***

Asterisks

___

Underscores

---

# 11. Line Breaks

My basic recommendation for learning how line breaks work is to experiment and discover -- hit <Enter> once (i.e., insert one newline), then hit it twice (i.e., insert two newlines), see what happens. You'll soon learn to get what you want. "Markdown Toggle" is your friend.

```
Here are some things to try out:

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.
```
Here are some things to try out:

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.

(Technical note: *Markdown Here* uses GFM line breaks, so there's no need to use MD's two-space line breaks.)

---
# 12. Link / Hyperlinks
```
[Title](https://www.example.com)
```
[Title](https://www.example.com)

---

# 13. YouTube Videos

They can't be added directly but you can add an image with a link to the video like this:

```html
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
```

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

Or, in pure Markdown, but losing the image sizing and border:

```
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
```

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

---

# 14. TeX Mathematical Formulae

A full description of TeX math symbols is beyond the scope of this cheatsheet. Here's a good reference, and you can try stuff out on CodeCogs. You can also play with formulae in the Markdown Here options page.

Here are some examples to try out:

```
$-b \pm \sqrt{b^2 - 4ac} \over 2a$
$x = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \frac{1}{a_3 + a_4}}}$
$\forall x \in X, \quad \exists y \leq \epsilon$
```

>$-b \pm \sqrt{b^2 - 4ac} \over 2a$
$x = a_0 + \frac{1}{a_1 + \frac{1}{a_2 + \frac{1}{a_3 + a_4}}}$
$\forall x \in X, \quad \exists y \leq \epsilon$

The beginning and ending dollar signs ($) are the delimiters for the TeX markup.

# 15. Footnote

```
Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.
```
Here's a sentence with a footnote. [^a]

[^a]: This is the footnote.

```
Here's a simple footnote,[^1] and here's a longer one.[^bignote]. 2nd time referring a footnote,[^a]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

[^a]: This is the Second time footnote.

Indent paragraphs to include them in the footnote.

`{ my code }`

Add as many paragraphs as you like.
```
Here's a simple footnote,[^1] and here's a longer one.[^bignote]. 2nd time referring a footnote so [1:1],[^a]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

[^a]: This is the Second time footnote.

Indent paragraphs to include them in the footnote.

`{ my code }`

Add as many paragraphs as you like.

--- 

# 16. Heading ID
```
Help with [Blockquotes or quotes](#8-blockquotes)
```

Help with [Blockquotes or quotes](#8-blockquotes)

| Markdown                      | HTML                                     | Rendered Output             |
| :---------------------------- | :--------------------------------------- | :-------------------------- |
| `[Heading IDs](#heading-ids)` | `<a href="#heading-ids">Heading IDs</a>` | [Heading IDs](#heading-ids) |

--- 

# 17. Definition List
```
term
: definition
```
term
: definition

```
term
: definition 1
: defination 2
: defination 3
: definition 4
```
term
: definition 1
: defination 2
: defination 3
: definition 4

--- 

# 18. Task List
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

--- 

# 19. Escaping Backticks

If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks (``).

| Markdown                              | HTML                                           | Rendered Output                   |
| :------------------------------------ | :--------------------------------------------- | :-------------------------------- |
| ``Use `code` in your Markdown file.`` | <code>Use `code` in your Markdown file.</code> | Use `code` in your Markdown file. |

--- 

# 20. URLs and Email Addresses

To quickly turn a URL or email address into a link, enclose it in angle brackets.

<https://www.markdownguide.org>
<fake@example.com>

The rendered output looks like this:

https://www.markdownguide.org
fake@example.com

Escaping Characters

To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (\) in front of the character.

\* Without the backslash, this would be a bullet in an unordered list.

The rendered output looks like this:

* Without the backslash, this would be a bullet in an unordered list.
Characters You Can Escape

You can use a backslash to escape the following characters.
| Character | Name                                           |
| --------- | ---------------------------------------------- |
| \\        | backslash                                      |
| \`        | backtick (see also escaping backticks in code) |
| *         | asterisk                                       |
| _         | underscore                                     |
| { }       | curly braces                                   |
| [ ]       | brackets                                       |
| ( )       | parentheses                                    |
| #         | pound sign                                     |
| +         | plus sign                                      |
| -         | minus sign (hyphen)                            |
| .         | dot                                            |
| !         | exclamation mark                               |
| \|        | pipe (see also escaping pipe in tables)        |

---

# 21. Container
::::: container
:::: row
::: col-xs-6 alert alert-success
success text
:::
::: col-xs-6 alert alert-warning
warning text
:::
::::
:::::

--- 

# 22. Colors via html tags
```
item **bold red**{style="color:red"}
```
item **bold red**{style="color:red"}

item **bold red**{style="background-color:green"}

item **bold red**{style="color:red;background-color:green"}

--- 

# 23. markdown-it-abbr

```
*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium
The HTML specification
is maintained by the W3C.
```
*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium
The HTML specification
is maintained by the W3C.

--- 

# 24. Tips and Tricks

## 24.1. List inside blockquotes
Ref: https://meta.stackexchange.com/questions/252498/how-can-i-embed-a-list-inside-a-blockquote
```
> You don't need HTML:
> 
> * a markdown
> * list in quotes
>
> Even with numbers:
>
> 1. more
> 2. less
```
> You don't need HTML:
> 
> * a markdown
> * list in quotes
>
> Even with numbers:
>
> 1. more
> 2. less



## 24.2. List inside Table

### 24.2.1. Using html tag break: `<br>`

Ref: https://github.com/markdown-it/markdown-it/issues/406
```
| column 1 | column 2                  |
| :------: | ------------------------- |
|  value   | <p>value 1<br>value 2</p> |
|  value   | <p>value 1<br>value 2</p> |
```
| column 1 | column 2                  |
| :------: | ------------------------- |
|  value   | <p>value 1<br>value 2</p> |
|  value   | <p>value 1<br>value 2</p> |

### 24.2.2. Using html lists:

#### 24.2.2.1. Unorder list: `<ul><li></li></ul>`

Ref: https://github.com/markdown-it/markdown-it/issues/406
```
| column 1 | column 2                                  |
| -------- | ----------------------------------------- |
| value    | <ul><li>value 1</li><li>value 2</li></ul> |
| value    | <ul><li>value 1</li><li>value 2</li></ul> |
```
| column 1 | column 2                                  |
| -------- | ----------------------------------------- |
| value    | <ul><li>value 1</li><li>value 2</li></ul> |
| value    | <ul><li>value 1</li><li>value 2</li></ul> |

#### 24.2.2.2. Order list: `<ol><li></li></ol>`

Ref: https://github.com/markdown-it/markdown-it/issues/406
```
| column 1 | column 2                                  |
| -------- | ----------------------------------------- |
| value    | <ol><li>value 1</li><li>value 2</li></ol> |
| value    | <ol><li>value 1</li><li>value 2</li></ol> |
```
| column 1 | column 2                                  |
| -------- | ----------------------------------------- |
| value    | <ol><li>value 1</li><li>value 2</li></ol> |
| value    | <ol><li>value 1</li><li>value 2</li></ol> |

