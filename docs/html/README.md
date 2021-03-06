- [Basic HTML site](#basic-html-site)
- [Headers](#headers)
- [Text](#text)
- [Lists](#lists)
- [Tables](#tables)
- [Content Dividers](#content-dividers)
- [Text Modifiers](#text-modifiers)
- [Misc.](#misc)
- [Styling & Scripting Tags](#styling--scripting-tags)
# Basic HTML site
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Title</title>
        <style>
        </style>
        <!-- Other Data -->
    </head>
    <body>
        Visual Elements
    </body>
    <script>
        <!-- javascript here -->
    </script>
</html>
```

# Headers
`<h1></h1>` 
 *** 
 Header (largest)

`<h2></h2>`
  *** 
  Header

`<h3></h3>`
  ***
   Header

`<h4></h4>` 
 *** 
 Header

`<h5></h5>` 
 ***
  Header

`<h6></h6>` 
 *** 
 Header (smallest)

# Text
***
`<p></p>`
  ***
   paragraph (normal text); treats linebreaks and multiple spaces as a single space

`<pre></pre>`
  *** 
  same as p only that this preserves linebreaks and spaces

# Lists
`<ul></ul>`
 ***
  unordered list (renders bullet points by default)

`<ol></ol>`
 *** 
 ordered list (renders numers by default)

`<li></li>`
  ***
   renders a list item (each one is rendered with bullet/numer in front)

# Tables
`<table></table>` 

 *** 
 creates a table

`<tr></tr>` 
 *** 
 renders a new row in the table

`<th></th>` 
 *** 
 table header (bold) otherwise same as td

`<td></td>` 
 *** 
 renders a new cell in row in table

# Content Dividers
`<div></div>` 
 ***
  divides content (leaves a linebreak after)

`<span></span>` 
 ***
  same as div only that content afterwards is on the same line

# Text Modifiers
`<a></a>` 
 *** 
 creates a link (links to what is inside the href attribute)

`<i></i>`  
*** 
makes the text italics

`<strong></strong>` 
 *** 
 makes the text bold

`<u></u>` 
 ***
  makes the text underlined

`<sup></sup>` 
 ***
  makes the text superscript

`<sub></sub>`  
*** 
makes the text subscript

# Misc.
`<img />` 
 ***
  Creates an image from src attribute, if not loaded displays text in alt attribute

`<br />` 
 ***
  Creates a linebreak

`<link />` 
 ***
  used for CSS files outside HTML file (`<link href="some css file" ref="stylesheet" type="text/css" />`)

`<!-- -->`  
***
 HTML comment(not rendered)

`<iframe></iframe>`
  *** 
  displays HTML site at href attribute

`<navbar></navbar>` 
 ***
  no real difference but used for navigation

# Styling & Scripting Tags
`<style></style>`  
***
 Used for CSS in HTML file
 
`<script></script>`
  ***
   executes js inside or from src attribute
