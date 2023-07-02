---
layout: default
title: "Blog"
---

## My blog posts

{% for post in site.posts %}
  <h2>{{ post.date }}: {{ post.title }}</h2>
  <p>{{ post.excerpt }}</p>
  <p><a href="{{ post.url }}">Read more</a></p>
{% endfor %}