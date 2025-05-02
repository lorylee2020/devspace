---
title: Welcome to my blog
author: Lory
---

{% for post in site.blog %}

  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
