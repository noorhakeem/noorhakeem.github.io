---
layout: posts
title: Blog
permalink: /blog/
---

Welcome to the blog. 

{% for post in _posts.posts %}
## [{{ post.title }}]({{ post.url }})
{{ post.excerpt }}

<p>{{ post.date | date: "%B %-d, %Y" }}</p>
{% endfor %}
