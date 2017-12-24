---
layout: default
title: Michael | Dev Me
---

# Michael

Full stack web developer who has been programming for over 10 years, and currently holds a full time job. On the side runs this blog, and manages servers for small local businesses. For updates, you can find me on <a href="https://github.com/michaelgv">Github</a>

## Blog

{% for post in site.posts limit:3 %}
- `{{ post.date | date: "%Y-%m-%d" }}` - [{{ post.title }}]({{ post.url }}) {% endfor %}

[View all posts](/blog.html)