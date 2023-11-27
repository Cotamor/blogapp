+++
title = 'My First Post My First Post My First Post'
date = 2023-11-26T03:15:07+09:00
draft = false
description = "This is a description"
image = "/images/sample1.jpg"
imageBig = "/images/sample1.jpg"
categories = ["general", "life", "music"]
authors = ["Kota"]
avatar = "/images/avatar.webp"
+++

# Markdown Example
---
## Table of Contents
**[Images](#images)**
**[Movies](#movies)**  
**[Headers](#headers)**
**[Lists](#lists)**
**[Footnotes](#footnotes)**
**[Emphasis](#emphasis)**
**[Line Breaks](#line-breaks)**  
**[Inline HTML](#inline-html)**
**[Blockquotes](#blockquotes)**
**[Tables](#tables)**
**[Code and Syntax Highlighting](#code-and-syntax-highlighting)**



## Images
<!-- {{< figure src="/images/1s.webp" title="some image" width="50" height="70" >}} -->
![some image](/images/sample1.jpg)


## Movies
{{< youtube E8H-67ILaqc >}}


## Headers
# Header1
## Header2
### Header3
#### Header4

```
# H1
## H2
### H3
#### H4
```
## Lists

1. First list item
   1. sub item
   2. sub item
2. Second list item
3. Third list item
4. Another list item
<br>
<br>
* Unordered list item
* List item
* Another list item

## Footnotes

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.

## Emphasis

Emphasis, aka italics, with *asterisks* or _underscores_  
Strong empasis with **asterisks** and __underscores__

## Line Breaks
Add two or more spaces at the end of the line, it will put a line break  
You see? 👍

```
This is some description.    
This is another description.

This is the start of different paragraph.
This is some description.
```

## Inline HTML
You can alse use raw HTML in your Markdown, and it'll mostly work pretty well.
```
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
```

## Blockquotes
> Blockquotes are very handy in email to  emulate reply text.  
> This line is part of the same quotes

Quote break.[^test]
[^test]: This is a test reference.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can put Markdown into a blockquote.  

## Tables
There must be at least 3 dashes separating each header cell. The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

| Tables | Are    | Cool | default  |
|:------ |:-----: | ----:| -------- |
| apple  | red    | ¥1600| something|
| orange | orenge |  ¥600| something|
| banana | yellow |  ¥800| something|

## Code and Syntax Highlighting

Inline `code` has `back-ticks around` it.

JavaScript
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```  
Python
```python
s = "Python syntax highlighting"
print s
```

No code
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```
That's all for now
<br>
<br>
