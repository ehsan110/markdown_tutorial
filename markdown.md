# Markdown Language in Visual Studio Code

Click Ctrl + Shft + k to open side view
<br>
<br>

# I. Table of Contents

> Making contents able to navigate to the pages

[1. Headings-Styles](#1-headings-styles)\
[2. Block of Words Citation](#2-block-of-words)\
[3. Line Breaks](#3-line-breaks)\
[4. Combine Two things](#4-combine-two-things)\
[5. Face of Text](#5-face-of-text)\
[6. Bullets / Lists](#6-bullets--lists)\
[7. Line Breaks or page Break](#7-line-breaks-or-page-break)\
[8. Link and Hyperlinks](#8-link-and-hyperlinks)\
[9. Inserting Images/Figures](#9-inserting-imagesfigures)\
[10. Adding code or or code block](#10-adding-code-or-or-code-block)\
[11. Adding Tables](#11-adding-tables)\
[12. Install extension](#12-install-extension)

# 1. Headings Styles

Here we will learn about Headings styles

<br>

# Heading 1

>This is used to give Title of the Project

## Heading 2

>We can Heading 1 for Contents and Chapter names

### Sub Headings 3

>Used for the Sub Headings

#### Sub Headings 4

##### Small Bold

###### Extra Small Text

<br>

# 2. Block Of Words / Citation

This a normal text in markdown

> This is a block of special text
> We say this as giving a quotes

> We can seperate the quotes by giving a space between `>`  <br>

<br>

# 3. Line Breaks

Give `<br>` or `\` to shift to next line. <br> Thats how we go to next line or \ gives the same result.
<br>
<br>

# 4. Combine Two things

Combine Block of words and headings

`> ## Heading 2`

> ## Heading 2

<br>
<br>

# 5. Face of Text

**Bold** `**` or `__` on both sides

*Italic* `*` or `_` on both sides
<br>
<br>

# 6. Bullets / Lists

> Bullets

- Day-1
- Day-2
  - Day-2a
  - Day-2b
    - Day-2b1

> **Use `*` or `+` to make bullets

> Numbering

1. Day-0
2. Day-1
    1. Day-1a
    2. Day-1a
        1. Day-1aa
        2. Day-1ab
<br>
<br>

# 7. Line Breaks or page Break

> Use `---` or `___` or `***` to put lines

Line 1

---
___
***

Line 2
<br>
<br>

# 8. Link and Hyperlinks

> Weblink

<https://www.google.com>

`<https://www.google.com>`

>Hyperlink

[Google](www.google.com)

`[Google](www.google.com)`

> Key of a link

[Codanics]:https://www.youtube.com/c/codanics/featured

You can watch the whole playlist from [here][Codanics]
<br>
<br>

# 9. Inserting Images/Figures

> Images on local dir

Move the image to the folder containing the currently working file

- > Only display picture

![GitHub](github.jfif)

Format `![GitHub](name of file)`

- > Only Display the Title of a picture

[GitHub](github.jfif)
<br>
<br>

> Images on the web

Copy the link image address of the image from the web and paste inside `()`

- > Only display picture

![GitHub](https://www.thesoftwarereport.com/wp-content/uploads/2018/06/github-collab-retina-preview.gif)

Format `![GitHub](URL)`
<br>
<br>
<br>

- > Only Display the Title of a picture

[GitHub](https://www.thesoftwarereport.com/wp-content/uploads/2018/06/github-collab-retina-preview.gif)
<br>
<br>

# 10. Adding code or or code block

To print a string or code use `` like `Python` or `print`

> To display a block of code use three ``` at start and end.

```
print("Hello Python")
```

```
x = 5+6
y = 4*7
z = x+y
print(z)
```

> Shows Python-language syntax color

```python
x = 5+6
y = 4*7
z = x+y
print(z)
```

> Shows R-language syntax color

```r
x = 5+6
y = 4*7
z = x+y
print(z)
```

<br>

# 11. Adding Tables

|Codanics|Data_Science|With_Python|
|:---:|:---:|:---:|
|Baba|Aammar|ka_Chilla|
|Kya|Yaad_Rakho|Gay|
|Learning|Python|Data_Science
<br>

# 12. Install extension

[Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)  <br>
[Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf) <br>
[markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) <br>
[Markdown Shortcuts](https://marketplace.visualstudio.com/items?itemName=mdickin.markdown-shortcuts) <br>
[vscode-pdf](https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf)

`Ctrl + B` to bold <br>
`Ctrl + i` to make italic <br>
`Alt + C` typo

**Text**

_Text_

~~Text~~

`Text`

[Link](www.google.com)

Column A | Column B | Column C
---------|----------|---------
 A1 | B1 | C1
 A2 | B2 | C2
 A3 | B3 | C3
