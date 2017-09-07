---
layout: page
title:  "Documentation template"
date:   2017-09-07
categories: tut
---

Page template based on kramdown  
Copy this page to a new file with a filename of this form: YYYY-MM-DD-filename-for-html.md
When it is converted by git, it will be in a subdir of docs based on the category, and have a filename "filename-for-html.html"

This page has examples, and also shows you what how the md is transformed to html. nice. \ 
 https://kramdown.gettalong.org/quickref.html

# Typical Components - headers, sections

# H1 header

## H2 header

### H3 header

## horizontal rules
Insert a horizontal rule with three or more asterisks, dashes or underscores, optionally separated by spaces or tabs, on an otherwise blank line:

* * *

---

  _  _  _  _

---------------



# code block

<pre><code>this is a code block.
</code></pre>

~~~~~
This is a code block defined by tildes.
~~
Ending lines must have at least as
many tildes as the starting line.
~~~~~~~~~~~


code block with language specified:
~~ ruby
def what?
  42
end
~~


# nested lists
1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two




