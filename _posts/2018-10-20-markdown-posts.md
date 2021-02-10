---
layout: post
title: Testde
subtitle: This post explains how you can write posts using Markdown.
tags: [guide, markdown]
---

This post is written in markdown, but you can also write a [post using html]({% link _posts/2020-02-27-html-posts.html %}).

<span class="color-red">[NEW]:</span> Now you can also create a private post, which will not be visible on the blog homepage, but is accessible via a URL. See [this secret post]({% link _posts/2020-04-05-private-example.html %}) as an example.

Posts should be named as `%yyyy-%mm-%dd-your-post-title-here.md`, and placed in the `_posts/` directory. Drafts can be kept in `_drafts/` directory.

-------------

# Primeiro
## Segundo 
### Terceiro

<span class="color-blue">Some</span>
<span class="color-green">cool</span>
<span class="color-orange">colorful</span>
<span class="color-red">text.</span><br>

<span class="highlight-blue">And</span>
<span class="highlight-green">some</span>
<span class="highlight-orange">highlighting</span>
<span class="highlight-red">styles.</span>

**Here is a bulleted list,**
 - K
 - KK


**Here is a numbered list,**
1. Lista 1
2. Lista 2

**Here is a sample code snippet in C,**
```C
#include <stdio.h>

int main(void){
    printf("hello world!");
}
```

**Here is a horizontal rule,**

--------------

**Here is a blockquote,**

> There is no such thing as a hopeless situation. Every single 
> circumstances of your life can change!

**Here is a table,**

ID  | Name   | Subject
----|--------|--------
201 | John   | Physics
202 | Doe    | Chemistry
203 | Samson | Biology

**Here is a link,**<br>
[GitHub Inc.](https://github.com) is a web-based hosting service
for version control using Git

**Here is an image,**<br>
![](../assets/autumn.jpg)
