---
layout: page
title:  "Best Practice guide template"
date:   2017-09-07
categories: tut
---

Page template based on kramdown  
Copy this page to a new file with a filename of this form: YYYY-MM-DD-filename-for-html.md
When it is converted by git, it will be in a subdir of docs based on the category, and have a filename "filename-for-html.html"

This page has examples, and also shows you what how the md is transformed to html. nice. \ 
 https://kramdown.gettalong.org/quickref.html


## Introduction
Short paragraph, maybe some background.

---
## Recommendation
what the recommendation is.

---
## How to or examples
how to do it. put exampes in code blocks


~~~~~
simplest way to do a code block is to surround by defined by tildes.
~~
Ending lines must have at least as
many tildes as the starting line. 
~~~~~~~~~~~


Code block with language specified uses backticks:
```ruby
def what?
  42
end
```



