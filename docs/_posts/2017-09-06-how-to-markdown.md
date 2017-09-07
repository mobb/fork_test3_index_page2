---
layout: page
title:  "How to markdown"
date:   2017-09-07
categories: tut
---

Describes markdown format for EDI documentation. Based on Kramdown

This page has examples, and also shows you what how the md is transformed to html. nice. \ 
 https://kramdown.gettalong.org/quickref.html

# Typical Components - headers, sections

# H1 header

## H2 header

### H3 header

### horizontal rules
Insert a horizontal rule with three or more asterisks, dashes or underscores, optionally separated by spaces or tabs, on an otherwise blank line:

* * *

---

  _  _  _  _

---------------



### code block

<pre><code>this is a code block defined by pre and code tags.
</code></pre>

~~~~~
This is a code block defined by tildes.
~~
Ending lines must have at least as
many tildes as the starting line. this code block has 2 imbedded tildes that did not close the block.
~~~~~~~~~~~


code block with language specified is defined by backquotes:

```ruby
def what?
  42
end
```


### nested lists
1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two




