---
layout: post
title:  "Writing My Own Post"
date:   2018-01-22
categories: [ jekyll, post, whatever ]
permalink: /post/
---

## Apply your markdown knowledge!

<p>{% for category in page.categories %}
 {{ category }}{% unless forloop.last %}, {% endunless %}
{% endfor %}</p>

I'm a brand new post and can be about anything you want. Try playing around with lists, links, images, and etc., and reference the [Markdown Cheatsheet](https://github.com/mnyrop/nycdh-jekyll/blob/master/docs/markdown-cheatsheet.md) whenever you get stuck.
