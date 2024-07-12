---
layout: blog
title: Blog
permalink: /blog/
---

# Blog

Welcome to the blog. Here you can find the latest posts.

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}

<p>{{ post.date | date: "%B %-d, %Y" }}</p>
{% endfor %}
