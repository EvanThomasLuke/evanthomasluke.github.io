---
layout: page
title: Blog
permalink: /blog/
---

{% raw %}{% for post in site.posts %}{% endraw %}
- [{% raw %}{{ post.title }}{% endraw %}]({% raw %}{{ post.url }}{% endraw %}) — {% raw %}{{ post.date | date: "%Y-%m-%d" }}{% endraw %}
{% raw %}{% endfor %}{% endraw %}
