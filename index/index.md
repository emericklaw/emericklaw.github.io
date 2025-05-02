---
layout: default
title: Home
---

# Welcome to My Site

This is a minimal Jekyll site hosted on **GitHub Pages**.

Check out the [About](about.md) page or read the latest posts below.

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%B %d, %Y" }}  
{{ post.excerpt }}
{% endfor %}
