---
title: How to get started
date: 2020-08-26
description: Learn how to write a new blog post and insert a readalongs widget.
featured_image: ""
---
# What do I need?

To get started, you'll need to have admin access to the blog, a GitHub account, and working ReadAlongs files.

## How to make a new post

First, create a new post:

![new post](/img/new-post.png)

Then, make sure you are editing your post in "markdown" mode:

![new post](/img/markdown-mode.png)

Then, add your files to GitHub:

![new post](/img/gh.png)

Then, you can add your readalongs 'shortcode' anywhere you like. This is supposed to be wrapped by two curly brackets, but for some reason the rendering engine here still renders the readalong if I do that. So, when putting this in your blog, just add an extra opening '{' and an extra closing '}'

This code:

```html
{< 
  readalongs
  text=/readalongs/danish.xml 
  alignment=/readalongs/danish.smil 
  audio=/readalongs/danish.wav 
>}
```

produces this:

{{< readalongs
  text=/readalongs/danish.xml 
  alignment=/readalongs/danish.smil 
  audio=/readalongs/danish.wav >}}