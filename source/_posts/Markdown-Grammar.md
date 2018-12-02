---
title: Markdown 语法
date: 2018-08-05 15:08:06
tags:
 - markdown
---


# Header 1
```markdown
# Header 1
```

## Header 2
```markdown
## Header 2
```

### Header 3
```markdown
### Header 3
```

#### Header 4
```markdown
#### Header 4
```

##### Header 5
```markdown
##### Header 5
```

###### Header 6
```markdown
###### Header 6
```

An h1 header
============
```markdown
An h1 header
============
```

Paragraphs are separated by a blank line.

2nd paragraph. *Italic*, **bold**, and `monospace`. Itemized lists

```markdown
2nd paragraph. *Italic*, **bold**, and `monospace`. Itemized lists
```

look like:

  * this one
  * that one
  * the other one
  
```markdown
look like:

  * this one
  * that one
  * the other one
```    

There are ordered lists as well:

1. Foo Foo
2. Bar Bar
3. Foo Bar

> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.

```markdown
> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.
```

Use 3 dashes for an em-dash. (rabbit---cute animal) Use 2 dashes for ranges (ex., "it's all
in chapters 12--14").

Three dots ... will be converted to an ellipsis.

Unicode is supported. ☺


An h2 header
------------

```markdown
An h2 header
------------
```

Here's a code sample

```python
# Let me re-iterate ...
for x in xrange(10):
    print 'foo' + 'bar'
```

```python
def foobar():
    print "Welcome to flavor country!"
```

### An h3 header ###

Now a nested list:

 1. First, get these ingredients:

    * carrots
    * celery
    * lentils
    

 2. Boil some water.

 3. Dump everything in the pot.

Here's a link to [a website](http://foo.bar), 
to a [local doc](local-doc.html), 
and to a [section heading in the current doc](#an-h2-header). 
Here's a footnote [^1].

[^1]: Footnote text goes here.

Tables can look like this:

size |  material    |  color
---- |  ------------|  ------------
9    | leather      | brown
10   | hemp canvas  | natural
11   | glass        | transparent


```markdown
size |  material    |  color
---- |  ------------|  ------------
9    | leather      | brown
10   | hemp canvas  | natural
11   | glass        | transparent
```

Table: Shoes, their sizes, and what they're made of

A horizontal rule follows.

***

``` markdown
***
```

Here's a definition list:

apples
  : Good for making applesauce.
  
oranges
  : Citrus!
  
tomatoes
  : There's no "e" in tomatoe.
  
```markdown
apples
  : Good for making applesauce.
  
oranges
  : Citrus!
  
tomatoes
  : There's no "e" in tomatoe.
```    

Here's a "line block":

| Line one
| Line too
| Line tree


```markdown
| Line one
| Line too
| Line tree
```

and images can be specified like so:

![example image](/static/img/van-gogh.jpg)

```markdown
![example image](/static/img/van-gogh.jpg)
```

$$I = \int \rho R^{2} dV$$

And note that you can backslash-escape any punctuation characters
which you wish to be displayed literally, ex.: \`foo\`, \*bar\*, etc.


***

this page is based on [accent](https://github.com/bk2dcradle/accent)

