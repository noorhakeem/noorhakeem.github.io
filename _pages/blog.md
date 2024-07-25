---
layout: posts
title: Blog
permalink: /blog/
---

Welcome to the blog. Here you can find the latest posts.

{% for post in _posts.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}

<p>{{ post.date | date: "%B %-d, %Y" }}</p>
{% endfor %}
