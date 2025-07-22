---
layout: default
title: weblog
---

# posts

<ul>
{% for post in site.posts %}
  {% if post.path contains '_posts/' %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endif %}
{% endfor %}
</ul>
