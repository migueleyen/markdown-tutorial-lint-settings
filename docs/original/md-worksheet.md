# Markdown Worksheet
It's a "plain text" format for writing structured documents,based on formatting conventions from email and usenet(~redit).

---

### **How Usenet & Email Influenced Markdown**  
Before Markdown, people used **simple text symbols** in Usenet and email to format their messages. Markdown borrowed many of these ideas.  

| **Feature**         | **Usenet & Email Style**   | **Markdown Style**  |
|---------------------|--------------------------|----------------------|
| **Bold Text**       | `*bold*` or `_bold_`      | `**bold**` or `__bold__` |
| **Italic Text**     | `/italic/` or `_italic_`  | `*italic*` or `_italic_` |
| **Lists**          | `- Item` or `* Item`      | `- Item` or `* Item` |
| **Blockquotes**     | `> Quoted text`          | `> Quoted text` |
| **Code blocks**     | `Preformatted text` (indented) | `` `code` `` or triple backticks |

---

Markdown in comparison to HTML,is much simpler to read and write.

Specifically,VSCode uses the [CommonMark](https://commonmark.org/) Markdown specification.This means that VSCode natively supports CommonMark for rendering .md files but it also includes GitHub Flavored Markdown (GFM) by default.

## Sections

- [Block Quotes](#block-quotes)
- [Emphasis](#emphasis)
- [Headers](#headers)
- [Horizontal Rule](#horizontal-rule)
- [Links](#links)
- [Navigate Document Link](#navigate-document-link)
- [Code](#code)
- [Html & CSS](#html--css)


## BlockQuotes

> This is a single line blockquote.
<!-- __ Add Two Spaces(whitespaces) at the End of Each Line
> This is a multiline__
> blockquote.__
> Each line starts with `>`.   -->
> This is a multiline  
> blockquote.  
> Each line starts with `>`.

<!-- Aisled blockquotes Enter between lines-->
>This is one blockquote.

>This is another blockquote.

## Emphasis
### Bold 
<!-- **Text** __Text__ -->
**BOLD TEXT**

### Italics 
<!-- *Text* _Text_ -->
*ITALICS* _ITALICS_

### Combo
<!-- ***Text*** ___Text___ -->
***BOLD & ITALIC***

___BOLD & ITALIC___


## Headers
Header 1 # to Header 4 ####

> **TODO**. Create H1 like `<h1>`
# Header 1

> **TODO**. Create H2 like `<h2>`
## Header 2

> **TODO**. Create H3 like `<h3>`
### Header 3

> **TODO**. Create H4 like `<h4>`
#### Header 4


## Horizontal Rule

--- , *** , ___

---

    SECTION 1
***
    SECTION 2
___
    SECTION 3

## Lists 


### like `<ol>` 
1, 2 , 3 ...

1. item 1
2. item 2
3. item 3
### like `<ul>` 
- , * , +

- item 1
* item 2
+ item 3

### indent list or sublist
- list
    - sublist 1
        - sublist 2

## Links

### plain link
<https://google.com>

### anchor url link
[Google](https://google.com)

### reusable var key link
[key]:https://google.com

[Google][key]
[Google][key]
[Google][key]
[Google][key]

### image link
![google](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)


## Navigate Document Link
<!-- [any label](#id)
- for space  
-- for & -->

<!-- refer Header: ## Nav 1 Doc Link -->
[Nav 1 Doc Link](#nav-1-doc-link) 

<!-- refer Header: ## Nav 2 & Doc & Link -->
[Nav 2 Doc Link](#nav-2--doc--link) 



## Nav 1 Doc Link
> **TODO**. Link with _space  (#id) section
## Nav 2 & Doc & Link
**TODO**. Link with & (#id) section

## Navigate External *.md Link
[What Is Usenet](what-is-usenet.md)  
[Why Need CommonMark](why-need-commonmark.md)

## Code
### `` inline or `````` block multiline
inline: 
  
` var x=10 `` single backticks. `  

multiline :
```
<!-- ``` ``` block code -->
var x=10
var y=100
var z=1000000
```

### lang format
<!-- lang format -->
```javascript
<!-- ``` ``` block code -->
var x=10
var y=100
var z=1000000
```
```html
<div>
    <span>Hide feature</span>
    <h1>Hello World</h1>
</div>
```

## Html & Css
<div id="my-div">
    <span>
        <h1>Header 1</h1>
        <p> paragraph 1 </p>    
    </span>
    <span>
        <h1>Header 2</h1>
        <p> paragraph 2 </p>    
    </span>
   
</div>

<!-- Css style for entire file -->
<!-- <style>
    body {
        background-color:magenta
    }
</style> -->
<!-- Css style for div sections
<style>
    div {
        background-color:magenta
    }
</style>
Css style for # named my-div sections
<style>
    #my-div {
        background-color:blue
    }
    #my-div h1{
        color: white;
        font-size: 24px;
    }
    #my-div p {
        color: red;
        font-size: 12px;
    }

</style> -->

## Additional Resources

[VideoTutorial](https://www.youtube.com/watch?v=pTCROLZLhDM)

[Markdown Cheat Sheet Adam P on Github](https://github.com/adam-p/markdown-here/wiki/markdown-cheatsheet)

[Daring Fireball Markdown syntax](https://daringfireball.net/projects/markdown/syntax)

[Markdown in VSCode](https://code.visualstudio.com/docs/languages/markdown)












