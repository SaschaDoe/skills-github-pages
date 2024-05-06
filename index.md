---
title: Welcome to the coding journey torwards Randomaze
date: 2024-05-06
---
This is my first commit!

# My Blog Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
